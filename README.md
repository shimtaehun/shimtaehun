<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=3B82F6&height=200&section=header&text=%EC%8B%AC%ED%83%9C%ED%9B%88&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20/%20ML%20Engineer&descSize=18&descAlignY=55&descAlign=50" width="100%"/>
</p>

<p align="center">
  <b>RAG 파이프라인 설계부터 모델 양자화·서빙까지, End-to-End AI 엔지니어</b>
</p>

<p align="center">
  <a href="mailto:sthun0211@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://sthun11.tistory.com/"><img src="https://img.shields.io/badge/Tech%20Blog-FF5722?style=for-the-badge&logo=blogger&logoColor=white"/></a>
  <a href="https://www.notion.so/328df9d7858a8144bc36c0868eb5c531"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=notion&logoColor=white"/></a>
</p>

---

## 🧑‍💻 About Me

pgvector 기반 RAG 파이프라인과 벡터 추천 시스템을 **설계부터 배포까지 1인으로 완성**하고, **LLM 모델 양자화 경험**이 있는 AI 엔지니어입니다.

빠르게 실험하고, 실패하면 원인을 기록하고, 결국 동작하는 결과물을 만들어내는 방식으로 일합니다.

- 🔭 W4A16 → W8A8 전환, dampening_frac 튜닝, VRAM 최적화 등 **체계적 실험 설계와 기록**으로 최적 조합 도출
- ⚡ YOLO 추론에 TensorRT를 적용해 **속도 3~5배 개선**
- 🌱 현재 **RAG 고도화 · 모델 파인튜닝 & 경량화 · AI Agent 설계 · 멀티모달 AI**에 관심

---

## 🛠️ Tech Stack

<table>
  <tr>
    <td align="center" width="140"><b>AI / ML</b></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
      <img src="https://img.shields.io/badge/vLLM-5C2D91?style=flat-square&logoColor=white"/>
      <img src="https://img.shields.io/badge/GPTQ-FF6F00?style=flat-square&logoColor=white"/>
      <img src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
      <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Backend</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
      <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Data & Search</b></td>
    <td>
      <img src="https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/Gemini_Embedding-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
      <img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Frontend</b></td>
    <td>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white"/>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center"><b>Infra & Tools</b></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white"/>
      <img src="https://img.shields.io/badge/WandB-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black"/>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
      <img src="https://img.shields.io/badge/Roboflow-6706CE?style=flat-square&logoColor=white"/>
    </td>
  </tr>
</table>

---

## 🚀 Projects

### ✈️ [TripMeet — pgvector RAG + 벡터 추천 시스템](https://github.com/shimtaehun/tripmeet)
> 1인 풀스택 개발 · Next.js · TypeScript · FastAPI · pgvector · Redis · WebSocket · Gemini 2.5-flash · Docker

AI 기반 여행 커뮤니티 플랫폼. 사용자 질문을 768차원 벡터로 변환 → pgvector에서 cosine distance 검색 → Gemini가 맞춤 답변을 생성하는 **RAG 파이프라인**을 설계·배포했습니다. WebSocket 실시간 채팅, JWT+bcrypt 인증도 직접 구현.

**핵심 판단**: Pinecone 대신 pgvector 선택(비용 0원, PostgreSQL 동일 인프라) / 태그 기반 → 벡터 임베딩 전환 / Redis 캐싱으로 API 비용 절감

---

### 🛡️ [Tank Challenge — 전장상황인식 AI 시스템](https://github.com/shimtaehun/AI_battlefield_situation)
> 8인 팀 · YOLO · TensorRT · A* · Pure Pursuit · Flask · Unity · Docker

현대로템 K-방산 AI 개발과정 최종 프로젝트. **본인 담당**: 강화학습(PPO/SAC) 실험 → A*+Pure Pursuit 재설계, 코드 모듈화, 포격 후 회피기동 구현, 주행 시나리오 계획.

**핵심 성과**: TensorRT 적용으로 YOLO **추론 속도 3~5배 개선** / 인터페이스 문서화 선행으로 통합 충돌 최소화

---

### ⚡ [EXAONE LLM 양자화 — 628팀 중 상위 11%](https://github.com/shimtaehun/LG_Aimers-8-)
> 개인 참가 · vLLM · GPTQ · LLMCompressor · W8A8 · MLflow · DAGsHub · Kaggle T4x2

EXAONE-4.0-1.2B 모델을 15회 이상 체계적으로 실험하며 최적 양자화 조합 도출. MLflow/DAGsHub로 전 과정 추적.

**실험 여정**: W4A16(0.57) → W8A8 전환(0.61x) → dampening_frac 튜닝 → max_position_embeddings 최적화 → **최종 0.624점 (상위 11%)**

**가장 큰 교훈**: embed_tokens 양자화 시 0.574→0.487 급락 — 입력층 오차가 30개 Transformer 레이어를 거치며 증폭

---

### 🛠️ [Auto Readme — AI 기반 README 자동 생성](https://github.com/shimtaehun/Auto_Readme)
> 개인 개발 · Python · Flask · Docker

GitHub 리포지토리 코드를 분석해 AI가 자동으로 README.md를 생성하는 도구. Docker 컨테이너화로 어디서든 실행 가능.

---

## 📚 Education

| 기간 | 내용 |
|:---:|:---|
| 2025.06 ~ 2025.12 | 현대로템 K-방산 AI 개발과정 수료 |
| 2026.01 ~ 2026.02 | LG Aimers 6기 수료 · LLM 경량화 해커톤 상위 11% |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shimtaehun&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shimtaehun&layout=compact&theme=tokyonight&hide_border=true" height="170"/>
</p>

---

<p align="center">
  <i>"빠르게 실험하고, 실패하면 원인을 기록하고, 결국 동작하는 결과물을 만든다."</i>
</p>
