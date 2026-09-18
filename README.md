# 심태훈 · AI Engineer

LLM·RAG를 실제 업무 흐름에 연결합니다. 실패한 질문을 재현해 원인을 좁히고, 검색 결과가 답변과 판단에 어떻게 쓰이는지 확인하며 개발합니다.

[이메일](mailto:cheein11@gmail.com) · [기술 블로그](https://sthun11.tistory.com/) · [포트폴리오](https://www.notion.so/328df9d7858a8144bc36c0868eb5c531)

## 대표 프로젝트

### Senior Companion · 독거노인 개인화 음성 말벗

**㈜디엠티랩스 AI연구개발팀 인턴 · 1인 개발 · 사내 PoC (코드 비공개)**  
어르신 음성 화면, 대화 기억 파이프라인, 담당자 대시보드와 백엔드를 만들고 사내 배포까지 연결했습니다. 정답 기억을 상위에 둬도 간접 질문에 실패하는 것을 확인해 병목을 검색이 아닌 생성 단계로 좁혔고, 실패한 턴에만 재시도를 붙였습니다.  
**검증:** 사내 평가의 고정 문항에서 기억 활용 107/110문항(10계정×11문항, 2026-07-29).

### [DART 공시 데이터 GraphRAG](https://github.com/team-polaris-dev/polaris-backend)

**3인 팀 · [백엔드](https://github.com/team-polaris-dev/polaris-backend) · [프론트엔드](https://github.com/team-polaris-dev/polaris-frontend)**  
공시 질의응답 시스템에서 MariaDB 구조화 검색과 Qdrant Dense·BM25 하이브리드 검색을 담당했습니다. LLM이 만드는 SQL은 기업·문서 식별자 기반 고정 SQL로 바꾸고, `sqlglot`으로 단일 SELECT만 허용했습니다. 팀은 교육 최종 심사 6개 팀 중 2위에 올랐습니다.

### [Tax-Copilot · 세무사를 위한 AI 영수증 검토](https://github.com/shimtaehun/Tax_Agent)

**1인 개발 · FastAPI · LangGraph · Qdrant · Next.js**  
영수증 파싱 → 거래일 기준 법령 검색 → 세무 판단 후보 제시까지 연결했습니다. 최종 판단은 세무사가 검토 API에서 승인·반려하며, 부가세 계산에는 `Decimal`을 사용합니다. 테스트 166개로 주요 경로를 검증했습니다.

## 다른 프로젝트

- **아동 영어학습 튜터 PoC** · 사내 프로젝트, 코드 비공개. 음성 루프를 옮기고 문항·채점·난이도를 설계했습니다. 인식에 실패한 발화는 오답 대신 미판정으로 처리하고, 문항 교차 감사로 채점 문제 13건을 수정했습니다.
- **[EXAONE LLM 양자화](https://github.com/shimtaehun/LG_Aimers-8-)** · GPTQ/W8A8 실험을 담당했습니다. LG Aimers 8기 628팀 중 71위는 3인 팀 결과입니다.
- **[Tank Challenge](https://github.com/shimtaehun/AI_battlefield_situation)** · 8인 팀에서 A*·Pure Pursuit 주행, YOLOv8 데이터셋 구축·파인튜닝, TensorRT 추론 경로를 맡았습니다.
- **[TripMeet](https://github.com/shimtaehun/tripmeet)** · React Native·FastAPI 기반 여행 앱을 1인 개발했습니다. pgvector 동행 매칭과 RAG 일정 생성을 구현했습니다.
- **[Auto Readme](https://github.com/shimtaehun/Auto_Readme)** · 코드 분석 기반 README 생성과 FAISS 검색을 이용한 코드 질의응답 도구를 만들었습니다.

## 기술

**AI·검색** Python · LangGraph · RAG · Qdrant · YOLOv8 · TensorRT  
**서비스·데이터** FastAPI · React · Next.js · MySQL/MariaDB · PostgreSQL  
**배포·검증** Docker · Kubernetes · Jenkins · pytest
