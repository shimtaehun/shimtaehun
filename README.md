<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=3B82F6&height=200&section=header&text=%EC%8B%AC%ED%83%9C%ED%9B%88&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%C2%B7%20LLM%20%C2%B7%20RAG%20%C2%B7%20Agent&descSize=18&descAlignY=55&descAlign=50" width="100%"/>
</p>

<p align="center">
  <b>LLM·RAG를 실제 업무 흐름에 연결하는 AI 엔지니어입니다.</b>
</p>

<p align="center">
  <a href="mailto:cheein11@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://sthun11.tistory.com/"><img src="https://img.shields.io/badge/Tech%20Blog-FF5722?style=for-the-badge&logo=blogger&logoColor=white"/></a>
  <a href="https://www.notion.so/328df9d7858a8144bc36c0868eb5c531"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=notion&logoColor=white"/></a>
</p>

---

## 🧑‍💻 About Me

**실패한 입력을 다시 실행해 원인을 좁힙니다.** 말벗 PoC에서는 정답 기억을 항상 상위에 두어도 간접 질문이 실패하는 것을 확인하고, 생성 단계의 실패 턴만 재시도하도록 바꿨습니다. 이처럼 가설을 작은 실험으로 확인한 뒤 구현에 반영합니다.

- 🧑‍💻 AI 인턴(2026.07–09) — 독거노인 개인화 음성 말벗 PoC를 **기획 구체화부터 사내 배포까지 1인으로** 개발 (사내 프로젝트라 코드는 비공개)
- 🏆 EXAONE-4.0 LLM 양자화 — **628팀 중 상위 11%** (W8A8 + 캘리브레이션 구간 최적화, 0.624점, 3인 팀 결과)
- ⚡ YOLO 추론 경로에 **TensorRT FP16** 적용 — GPU면 `.engine`, CPU면 `.onnx`, 변환에 실패하면 `.pt`로 내려가는 3단계 폴백
- 🧩 RAG 파이프라인을 **설계부터 배포까지 1인 완성** — 세무 자동화 에이전트는 **테스트 166개**로 검증
- 🌱 관심 분야: **RAG 고도화 · AI Agent 설계 · LLM 기능의 서비스 통합**

---

## 🛠️ Tech Stack

<table>
  <tr>
    <td align="center" width="150"><b>AI 서비스</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/LLM_API-412991?style=flat-square&logo=openai&logoColor=white"/>
      <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white"/>
      <img src="https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logoColor=white"/>
      <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center" width="150"><b>검색 · 데이터</b></td>
    <td>
      <img src="https://img.shields.io/badge/RAG-111F68?style=flat-square&logoColor=white"/>
      <img src="https://img.shields.io/badge/Qdrant-24386C?style=flat-square&logo=qdrant&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
      <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center" width="150"><b>제품 · 운영</b></td>
    <td>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
      <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/>
    </td>
  </tr>
</table>

<sub>이력서에 적은 기술과 같은 목록입니다. 아래 프로젝트에서 실제로 쓴 나머지 도구는 각 저장소 README에 적었습니다.</sub>

---

## 🚀 Projects

### 🗣️ Senior Companion — 독거노인 개인화 음성 말벗
> AI 인턴 · 1인 개발 · Python · FastAPI · MySQL · 사내 STT/TTS/오픈웨이트 LLM 연동 · React · Jenkins · Kaniko · Helm · Kubernetes · 사내 프로젝트라 코드는 비공개

2026.07–09 인턴십에서 만든 사내 PoC입니다. 대화에서 나온 **사실·일화·취향을 저장해 다음 대화에 쓰는 기억 파이프라인**을 만들고, 어르신용 음성 화면과 담당자 대시보드, 백엔드, 사내 배포까지 1인으로 연결했습니다. 이어서 같은 음성·기억 자산을 아동 영어학습 튜터 PoC로 옮겼습니다.

**핵심 판단**: 간접 질문에서 기억을 못 쓰자 벡터 DB를 넣기 전에 정답 기억을 항상 상위에 두는 진단용 검색기로 다시 재 **0/10**을 확인 → 병목을 검색이 아니라 생성 단계로 좁히고 실패한 턴만 2단계로 재시도 / 확신도 0.6 미만 기억은 사용자 확인 뒤 사용, 응급 표현은 자유 생성을 우회 / 개발셋에서만 맞던 화제 규칙 92줄은 holdout 기여가 0%라 삭제

**검증**: 사내 고정 문항에서 기억 활용 **107/110**(10계정×11문항, 11문항을 모두 통과한 계정은 7/10, 2026-07-29 내부 평가)

---

### 🧒 아동 영어학습 튜터 PoC
> AI 인턴 · 1인 개발 · Python · FastAPI · 사내 STT/TTS/LLM 연동 · 문항·채점·난이도 설계 · 사내 프로젝트라 코드는 비공개

인턴십 후반(2026.08–09)에 말벗의 음성 루프와 기억 검증을 옮기고, 영어 문항·채점·난이도는 새로 설계했습니다.

**핵심 판단**: 인식에 실패한 발화는 오답이 아니라 **미판정**으로 보류 — 틀린 기록이 쌓이면 다음 출제까지 틀어지기 때문 / 문항 교차 감사로 단위 테스트가 놓친 채점 구멍 **13건** 수정 / 느린 응답의 구간을 나눠 재어, 발화 종료부터 전사 확정까지가 가장 길다는 것을 확인하고 스트리밍으로 바꿔 같은 발화 3회 측정에서 **5.6~6.2초 → 2.5초**

**측정부터 의심한 일**: 처음 잰 인식률 33%는 STT 성능이 아니라, 측정 스크립트가 쓴 다른 TTS 경로가 절반가량 무음을 돌려줘 나온 값이었습니다. 제품이 실제로 거치는 경로로 다시 재고, 33%를 근거로 세웠던 설계 결정 세 가지를 되돌렸습니다.

---

### 📊 [DART 공시 데이터 GraphRAG](https://github.com/team-polaris-dev/polaris-backend)
> 3인 팀 · MariaDB · Qdrant(Dense·BM25·RRF) · sqlglot · FastAPI · 팀 저장소 [polaris-backend](https://github.com/team-polaris-dev/polaris-backend) · [polaris-frontend](https://github.com/team-polaris-dev/polaris-frontend)

2026.06 서울 매력일자리 교육의 최종 프로젝트입니다. 공시 문서를 묻고 답하는 시스템으로, 세 명이 초기 구조를 함께 설계한 뒤 역할을 나눴고, **저는 MariaDB 구조화 검색과 Qdrant 하이브리드 검색을**, 다른 팀원이 GraphRAG를 맡았습니다. 뉴스 분석 탭과 카드뉴스는 백엔드·프론트엔드까지 직접 구현했습니다.

**핵심 판단**: Dense + BM25를 **RRF(k=60)** 로 결합 — 의미 유사와 정확한 용어 일치가 질문마다 다르게 필요했습니다 / 비결정적인 LLM Text-to-SQL을 그래프가 찾은 기업·문서 식별자 기반 **파라미터화 고정 SQL**로 교체(dev 브랜치) / `sqlglot` AST 검사로 단일 SELECT만 허용하고 파일 접근·쓰기 쿼리는 실행 전 차단, 구조화 결과가 없으면 임의 답변 대신 명시적 미검색 반환

**결과**: 팀이 교육 최종 심사 6개 팀 중 2위(팀 결과)

---

### 🧾 [Tax-Copilot — 세무사를 위한 AI 영수증 검토 에이전트](https://github.com/shimtaehun/Tax_Agent)
> 1인 풀스택 개발 · FastAPI · LangGraph · Gemini Vision · Qdrant · Celery · PostgreSQL · Next.js · Docker

영수증을 올리면 AI가 **파싱 → 법령 RAG → 세무 판단**까지 후보를 만들고, 세무사가 승인/반려하는 **Human-in-the-Loop 에이전트**. LangGraph 9노드 워크플로우가 판단 후보까지 만들고, 법령 미검색·신뢰도 0.75 미만·계산 실패·증빙 미판별 중 하나라도 걸리면 '검토 필요'로 저장해 세무사가 검토 API로 승인/반려합니다.

**핵심 판단**: AI는 후보만 제시·최종 판단은 사람(세무사법 책임 구조) / 부가세는 전 구간 `Decimal`로 1원 오차 차단 / 법령은 **거래일 기준**으로 RAG 필터링 / Celery 분산 락 + `acks_late`로 중복 처리 방지 · **테스트 166개**

---

### ⚡ [EXAONE LLM 양자화 — 628팀 중 상위 11%](https://github.com/shimtaehun/LG_Aimers-8-)
> 3인 팀 참가 · vLLM · GPTQ · LLMCompressor · W8A8 · MLflow · DAGsHub · Kaggle T4x2

EXAONE-4.0-1.2B 모델을 15회 이상 체계적으로 실험하며 최적 양자화 조합 도출. MLflow/DAGsHub로 전 과정 추적.

**실험 여정**: W4A16(0.57) → W8A8 전환(0.61x) → dampening_frac 튜닝 → max_position_embeddings 최적화 → **최종 0.624점 (상위 11%)**

**가장 큰 교훈**: embed_tokens 양자화 시 0.574→0.487 급락 — 입력층 오차가 30개 Transformer 레이어를 거치며 증폭

---

### ✈️ [TripMeet — 여행 동행 매칭 + AI 일정 생성](https://github.com/shimtaehun/tripmeet)
> 1인 풀스택 개발 · React Native (Expo) · TypeScript · FastAPI · Supabase(pgvector) · Redis · Firebase · Gemini 2.5 Flash · Docker

자기소개를 768차원 벡터로 임베딩 → pgvector cosine 검색으로 성향이 비슷한 동행을 추천하고, 앱 데이터를 컨텍스트로 넣은 **RAG로 맞춤 여행 일정**을 생성하는 모바일 앱. Firestore 실시간 채팅까지 직접 구현했습니다.

**핵심 판단**: Pinecone 대신 pgvector 선택(비용 0원, 동일 PostgreSQL 인프라) / 예산을 구간으로 정규화해 Redis 캐시 히트율↑ / RAG 소스는 실패해도 일정 생성을 막지 않게(graceful degradation)

---

### 🛡️ [Tank Challenge — 전장상황인식 AI 시스템](https://github.com/shimtaehun/AI_battlefield_situation)
> 8인 팀 · YOLO · TensorRT · A* · Pure Pursuit · Flask · Unity · Docker

현대로템 K-방산 AI 개발과정 최종 프로젝트. **본인 담당**: 강화학습(PPO/SAC) 실험 → A*+Pure Pursuit 재설계, 코드 모듈화, 포격 후 회피기동 구현, 주행 시나리오 계획, 5클래스 데이터셋 구축·라벨링과 YOLOv8 파인튜닝, TensorRT 추론 경로 탑재.

**핵심 성과**: 재현되지 않던 강화학습 주행을 A*+Pure Pursuit으로 전환해 시나리오 완주 / TensorRT FP16 추론 경로와 3단계 폴백 탑재 / 인터페이스 문서화 선행으로 통합 충돌 최소화

---

### 🛠️ [Auto Readme — 코드 분석 기반 README 자동 생성](https://github.com/shimtaehun/Auto_Readme)
> 개인 개발 · Python · Streamlit · LangChain · FAISS · Gemini · Docker

GitHub 리포 코드를 분석해 AI가 README.md를 자동 생성하고, FAISS 벡터 검색으로 **코드 Q&A**까지 제공하는 도구. Docker로 어디서든 실행 가능.

---
