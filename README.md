<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=3B82F6&height=145&section=header&text=%EC%8B%AC%ED%83%9C%ED%9B%88&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=AI%20Engineer&descSize=17&descAlignY=64" width="100%" alt="심태훈 · AI Engineer"/>
</p>

<p align="center">
  <b>LLM·RAG를 실제 업무 흐름에 연결하는 AI 엔지니어입니다.</b><br/>
  검색이 답변으로 이어지지 않을 때 실패를 재현하고, 어느 단계에서 막히는지 확인합니다.
</p>

<p align="center">
  <a href="mailto:cheein11@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://sthun11.tistory.com/"><img src="https://img.shields.io/badge/Tech%20Blog-FF5722?style=for-the-badge&logo=blogger&logoColor=white" alt="Tech Blog"/></a>
  <a href="https://www.notion.so/328df9d7858a8144bc36c0868eb5c531"><img src="https://img.shields.io/badge/Portfolio-222222?style=for-the-badge&logo=notion&logoColor=white" alt="Portfolio"/></a>
</p>

## 👋 한눈에 보기

- **AI 서비스** — ㈜디엠티랩스 AI연구개발팀 인턴으로 독거노인 음성 말벗 PoC를 화면·백엔드·사내 배포까지 1인 개발했습니다.
- **검색과 에이전트** — DART 공시 검색에서는 구조화·하이브리드 검색을, Tax-Copilot에서는 법령 검색부터 세무사 검토 API까지 연결했습니다.
- **일하는 방식** — 테스트 숫자보다 실패한 입력과 판단의 이유를 먼저 확인하고, 확인된 범위만 결과로 남깁니다.

---

## 🚀 대표 프로젝트

### 🗣️ Senior Companion — 독거노인 개인화 음성 말벗

> **AI 인턴 · 1인 개발 · 사내 PoC (코드 비공개)** · Python · FastAPI · MySQL · React · Kubernetes

대화에서 나온 사실·일화·취향을 저장해 다음 대화에 쓰는 기억 파이프라인과 어르신용 음성 화면, 담당자 대시보드를 만들고 사내 배포까지 연결했습니다.

- **판단**: 정답 기억을 항상 상위에 둔 검색기에서도 간접 질문 10건을 모두 놓쳤습니다. 검색보다 생성 단계가 병목이라고 보고, 실패한 턴에만 기억 선택·응답 생성을 분리해 재시도했습니다.
- **검증**: 사내 평가의 고정 문항에서 기억 활용 **107/110문항**(10계정×11문항, 2026-07-29).

### 🧒 아동 영어학습 튜터 PoC

> **AI 인턴 · 1인 개발 · 사내 PoC (코드 비공개)** · Python · FastAPI · 사내 STT/TTS/LLM 연동

말벗의 음성 루프와 기억 검증을 가져오고, 영어 문항·채점·난이도 조절은 새로 설계했습니다.

- **판단**: 음성 인식에 실패한 발화는 오답 대신 미판정으로 보류했습니다. 잘못된 학습 기록이 다음 출제까지 영향을 주기 때문입니다.
- **검증**: 문항 교차 감사로 채점 문제 **13건**을 수정했습니다. 발화 종료부터 전사 확정까지의 구간을 스트리밍으로 바꿔, 같은 발화 3회 측정에서 **5.6~6.2초 → 2.5초**를 확인했습니다.

### 📊 [DART 공시 데이터 GraphRAG](https://github.com/team-polaris-dev/polaris-backend)

> **3인 팀** · [백엔드](https://github.com/team-polaris-dev/polaris-backend) · [프론트엔드](https://github.com/team-polaris-dev/polaris-frontend) · MariaDB · Qdrant · FastAPI

공시 문서에 질문하는 시스템에서 MariaDB 구조화 검색과 Qdrant 하이브리드 검색을 맡았습니다. 뉴스 분석 탭과 카드뉴스는 백엔드·프론트엔드까지 구현했습니다.

- **판단**: Dense와 BM25 결과를 RRF(k=60)로 결합했습니다. 비결정적인 LLM SQL은 기업·문서 식별자 기반 고정 SQL로 바꾸고, `sqlglot`으로 단일 SELECT만 허용했습니다.
- **결과**: 팀은 교육 최종 심사 **6개 팀 중 2위**에 올랐습니다(팀 결과).

### 🧾 [Tax-Copilot — 세무사를 위한 AI 영수증 검토](https://github.com/shimtaehun/Tax_Agent)

> **1인 개발** · FastAPI · LangGraph · Qdrant · Celery · PostgreSQL · Next.js

영수증 파싱 → 거래일 기준 법령 검색 → 세무 판단 후보 제시를 연결했습니다. 최종 판단은 세무사가 검토 API에서 승인·반려합니다.

- **판단**: 법령 근거가 없거나 추출·계산이 불확실하면 ‘검토 필요’로 보내고, 부가세 계산은 전 구간 `Decimal`로 처리했습니다.
- **검증**: LangGraph **9노드** 워크플로우와 검토 API를 구현하고, 테스트 **166개**로 주요 경로를 확인했습니다.

## 🔎 다른 프로젝트

- **[EXAONE LLM 양자화](https://github.com/shimtaehun/LG_Aimers-8-)** — GPTQ/W8A8 실험을 맡아 캘리브레이션 구간과 양자화 대상을 조정했습니다. LG Aimers 8기 **628팀 중 71위**는 3인 팀 결과입니다.
- **[Tank Challenge](https://github.com/shimtaehun/AI_battlefield_situation)** — 8인 팀에서 강화학습 주행의 재현 문제를 겪고 A*·Pure Pursuit으로 전환했습니다. YOLOv8 데이터셋 구축·파인튜닝과 TensorRT 추론 경로도 맡았습니다.
- **[TripMeet](https://github.com/shimtaehun/tripmeet)** — React Native·FastAPI 여행 앱을 1인 개발했습니다. pgvector로 동행을 매칭하고, RAG 일정 생성에서 부가 데이터 조회가 실패해도 일정 생성은 이어지게 했습니다.
- **[Auto Readme](https://github.com/shimtaehun/Auto_Readme)** — 저장소 코드를 분석해 README를 만들고, FAISS 검색 기반 코드 질의응답을 제공하는 도구를 개발했습니다.

---

## 🛠️ Tech Stack

| 분야 | 주로 사용한 기술 |
|:--|:--|
| **AI · 검색** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![Qdrant](https://img.shields.io/badge/Qdrant-24386C?style=flat-square) ![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white) |
| **서비스 · 데이터** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) |
| **배포 · 검증** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) |
