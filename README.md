# 이성준 (YIsungjoon)
### AI Engineer — RAG · LLM Agent · Model Serving

법학을 전공하고 AI 엔지니어로 전환했습니다. 2026년 2월부터 **건설 인허가·건설기준 도메인 RAG 챗봇**을 설계부터 구현·배포·운영까지 혼자 맡아 왔고, 법령 API·GraphDB·규제 카드를 결합해 "검증 가능한 답변"을 만드는 데 집중하고 있습니다.

📄 **포트폴리오**: https://yisungjoon.github.io

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-2E8B57?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/vLLM-000000?style=flat-square" />
  <img src="https://img.shields.io/badge/llama.cpp-000000?style=flat-square" />
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
</p>

---

## 🏗️ 실무 프로젝트 (2026.02 — 현재, 단독 개발·운영)

| 프로젝트 | 기간 | 한 줄 요약 | 핵심 |
| :--- | :--- | :--- | :--- |
| **[Contech-GPT](https://github.com/laonarctec/contech-gpt)** | 2026.05 — | 건설 인허가·건설기준 규제 판단 RAG 시스템 (운영 중) | Cascade Prefetch(법령API·GraphDB·KDS·RAG 병렬 선수집) · Golden Card 81장 5-Layer 검증 · 환각 방어 후처리 체인 · 1,000문항 QA셋 회귀 · 145K LOC |
| **[LAON_AI](https://github.com/laonarctec/LAON_AI)** | 2026.07 — 08 | LangGraph 네이티브 에이전트 재구현 | 자율 tool 선택 경로 제거, coverage_gate 후에만 제한 보완 · Send 팬아웃 · interrupt() · 자동 검사 542건 |
| **[laonOCR](https://github.com/laonarctec/laonOCR)** · **[laonCropper](https://github.com/laonarctec/laonCropper)** | 2026.04 · 07 — 08 | 영수증 크롭 + VLM 구조화 OCR 마이크로서비스 | 모델(Qwen3.5 2B~8B×FP4~FP16)·DPI(100~600→300)·프롬프트 3축 실험 · PaddleOCR 대비 96% · vLLM 전환 후 27초→3~5초/장 |
| **[Contech-DX Chatbot](https://github.com/laonarctec/contech-chatbot)** | 2026.03 — 05 | 로컬 LLM(Qwen3.6-35B, llama.cpp) 기반 1세대 챗봇 | LangGraph StateGraph · Golden Card · 법령 API 게이트 · 이후 Contech-GPT로 진화 |
| **LAWGraphDB** | 2026.03 — | 법령·KDS Neo4j 그래프 (전 챗봇 공통 기반) | 법령 1.1GB · KDS 1.4GB · On-Demand 적재 · LawNameGuard 대조 기준 |
| **공정 도우미 에이전트 PoC** | 2026.07 | LLM이 공정표를 작성·수정할 수 있는지 검증 | 제안→승인→적용 흐름 · superuser 2단 게이팅 · 골조 공정표 함수 생성기 tool화 (PoC 후 중단) |

운영: RTX 4090 서버 1대, Docker 컨테이너 18개 상시 기동 (prod / dev / 실험 프로파일 분리).

---

## 🧪 개인 프로젝트

| 프로젝트 | 설명 |
| :--- | :--- |
| **[cognitive-guard](https://github.com/YIsungjoon/cognitive-guard)** | AI 인지부채 방지 Claude Code 플러그인 — 메타인지 스크립트 기반 이해도 테스트·능동적 코드 리뷰·학습 대시보드 |
| **[myaicoder](https://github.com/YIsungjoon/myaicoder)** | 로컬 LLM(llama.cpp) + MCP 기반 VS Code 코딩 어시스턴트, 도구 9종 — 데이터가 로컬을 벗어나지 않음 |
| **[Agent](https://github.com/YIsungjoon/Agent)** · **[Agent_tools](https://github.com/YIsungjoon/Agent_tools)** | LangGraph 기반 계층형 추론 엔진(Fractal IRAC) · KCSC/법제처 OpenAPI 에이전트 도구 |
| **[MuseumChatbot](https://github.com/YIsungjoon/MuseumChatbot)** | 박물관 안내 특화 RAG 챗봇 (2023, DPR + Streamlit) |

---

## 🏆 Kaggle — Competitions Expert

<a href="https://www.kaggle.com/treetreeanderson"><img src="https://img.shields.io/badge/Kaggle-treetreeanderson-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" /></a>

랭킹 **2,796 / 217,574** (최고 1,982위) · 대회 11회

*   🥈 **Stanford RNA 3D Folding Part 2** — 72위 / 1,867팀 (상위 3.8%)
*   🥉 **Stanford RNA 3D Folding** — 145위 / 1,516팀 (상위 9.5%)
*   🥉 **ICR - Identifying Age-Related Conditions** — 349위 / 6,430팀 (상위 5.4%)

---

## 🎓 교육

*   **이어드림 AI 과정** (1년, 2023) — 모의경진대회 NMT 5위/64 · 시계열 9위/60 · 이미지 분류 9위/64
*   **에티버스러닝 AI 과정** (5.5개월)
*   **법학 학사**

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YIsungjoon&show_icons=true&theme=tokyonight" alt="YIsungjoon's GitHub Stats" />
</p>

---

## 📬 Contact

- 📧 [leehm21897@daum.net](mailto:leehm21897@daum.net)
- 📊 Kaggle [@treetreeanderson](https://www.kaggle.com/treetreeanderson)
- 📝 [Notion 공부·연구 노트](https://gleaming-watchmaker-b31.notion.site/7b214aac5705468b99b50b0104228732)
