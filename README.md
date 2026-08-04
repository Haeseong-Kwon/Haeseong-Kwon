<h1 align="center">HaeSeong Kwon | CEO & CTO · Full-Stack / AI Engineer</h1>
<hr />

<div align="center">
  <br />
  <p align="center">
    <font size="5"><strong>Research to product to company — 원천기술 연구부터 제품 출시, 법인 운영까지 직접 합니다.</strong></font>
  </p>
  <br />
  <a href="https://portfolio-website-pi-six-74.vercel.app/">
    <font size="5"><strong>🌐 [포트폴리오 웹사이트 보러가기]</strong></font>
  </a>
  <br />
</div>

<br />

## 👋 About Me

* 🏢 **Founder & Technical Executive (CEO × CTO)**
    * **AOP / INSPEC / ON-AX** 3개 법인 대표이사 겸 **그로윙업 주식회사 기술이사(CTO)**
    * 아키텍처 의사결정(ADR), 기술 부채 상환 순서, 릴리스 파이프라인을 직접 소유하는 **playing CTO** — 코드를 떠나지 않은 채 경영을 겸함
    * 기술 선택을 **단위 원가(요청당 추론 비용·지연)와 런웨이 기준으로 판단**하고, 그 근거를 문서화해 조직에 남기는 의사결정 구조 운용
    * 0 → 1 제품 출시부터 법인 설립·계약·자금 집행까지, 기술과 사업의 접점을 한 사람이 관통

* 🧠 **Agent AI R&D Lead (AOP)**
    * **AOP는 AI 에이전트 제품·플랫폼을 운영하는 동시에, 에이전트 특화 AI 원천기술을 연구개발하는 회사**
    * **Multi-agent orchestration** — planner–executor–critic 루프, 서브에이전트 위임, 툴 호출 실패 시 보상 트랜잭션 및 재시도 정책 설계
    * **Long-horizon 상태 관리** — 그래프 기반 체크포인팅, 중단·재개, Human-in-the-Loop 승인 인터럽트를 포함한 durable execution 구조
    * **MCP(Model Context Protocol) 기반 툴 계층** — 내부 도구를 MCP 서버로 표준화해 오케스트레이션 프레임워크 교체 비용 제거
    * **컨텍스트 엔지니어링** — prompt caching, 구조화 출력(constrained decoding), 토큰 예산 배분으로 품질 대비 비용 최적화
    * **에이전트 평가·관측** — LLM-as-judge 회귀 스위트, 트레이스 단위 비용/지연 추적, 실패 유형 분류 기반 개선 루프

* 🚀 **Full-Stack Engineer (End-to-End Ownership)**
    * **Frontend** — Next.js App Router(RSC / Server Actions) 기반 스트리밍 UI, TypeScript 모노레포(Turborepo) 구성, 디자인 시스템 토큰화
    * **Backend** — FastAPI·Node 비동기 서버, 큐 기반 워커와 백프레셔 제어, SSE/WebSocket 스트리밍 응답 파이프라인 설계
    * **Data** — PostgreSQL 스키마 정규화·인덱스 설계·쿼리 플랜 분석, 파티셔닝과 무중단 마이그레이션, RLS 기반 멀티테넌시 격리
    * **Reliability** — 구조화 로깅과 분산 트레이싱(OpenTelemetry) 표준화, 에러 버짓 기준 릴리스 판단, 감지 → 격리 → 복구 → 포스트모템 프로세스 운영

* 🔬 **Applied AI Research Engineer**
    * **PINN(Physics-Informed Neural Networks)** — PDE 제약 학습에서 물리항 가중치 스케줄링 및 loss term ablation으로 수렴 안정성 확보
    * 의료(Brain MRI) · 반도체(CMOS Sensor) · 광학(Metasurface) 도메인 특화 파이프라인을 **전처리 → 학습 → 정량 평가(Dice/PSNR/SSIM) → 리포트 자동화**까지 독자 구축
    * **추론 최적화** — mixed precision, ONNX/TensorRT 변환, CUDA·MPS 가속, 배치·캐싱 전략으로 처리량 대비 비용 개선
    * Surrogate model + gradient-based 최적화를 결합한 **Inverse Design** 문제 해결 경험

* 📱 **Systems & Realtime Engineering**
    * **Flutter & Dart** 기반 산업용 관제 앱 — 고빈도 텔레메트리 스트림의 처리·렌더링 최적화 및 프레임 드랍 제어
    * 재연결 백오프, 오프라인 큐잉, 메시지 스키마 버저닝을 포함한 **실시간 통신 계층 직접 설계**

* 🎓 **Academic Foundation**
    * **한양대학교 ERICA 컴퓨터학부 졸업** (Computer Science & Engineering)
    * 자료구조·알고리즘·운영체제·컴파일러 기반의 저수준 이해를 바탕으로 한 공학적 문제 해결 능력

---

## 💼 Business & Strategic Experience

### 🏢 **Corporate Affiliations**

| 법인 | 역할 | 사업 영역 |
|:------|:------|:------|
| **주식회사 에이오피 (AOP)** | 대표이사 / CEO | AI 에이전트 제품·플랫폼 운영 + 에이전트 특화 AI 원천기술 R&D |
| **주식회사 인스펙 (INSPEC)** | 대표이사 / CEO | 인테리어 감리자 파견 플랫폼 운영 |
| **주식회사 온엑스 (ON-AX)** | 대표이사 / CEO | 수출 분야 글로벌 에이전트 기술 — 해외 시장조사·바이어 발굴 자동화 |
| **그로윙업 주식회사 (GrowingUp)** | 기술이사 / CTO | 퍼포먼스 마케팅 에이전시 기술 총괄 |

### 🚀 **Technical Leadership & Foundership**
* **Service Launch & Platform Strategy**
    * AI 에이전트 기업 **'AOP'** 설립 및 자체 제품(Autopilot / INSPEC) 런칭 프로세스 주도
    * 마케팅 에이전시 **'GrowingUp'** 및 산업 플랫폼 **'Shotcrete117'** 웹 인프라 전면 현대화
* **Intellectual Property (IP) Strategy**
    * 사용자 피드백 기반 추천 및 공정 검증 시스템 관련 **2건의 특허 출원** 완료
* **Full-Cycle Business Management**
    * 기획·개발·마케팅부터 법인 설립 및 세무 행정까지 사업 전 과정을 독립적으로 운용

### 📈 **Market Validation & Growth**
* **Data-Driven E-commerce Operation**
    * **'오스타몰k'** 운영 3개월 내 **파워 등급** 달성을 통한 데이터 기반 시장 대응 역량 입증
* **Crowdfunding Success Record**
    * 와디즈 지식 서비스 및 AI 프로젝트 연속 성공 (달성률 **1200%**, **3000%**)
    * 시장 수요 기반의 MVP 기획 및 타겟 마케팅 최적화 프로세스 정립

---

## 🛠️ Tech Stack

| Category           | Tools |
|:------------------|:------|
| **Agent Engineering** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-D97757?style=flat) ![A2A_Protocol](https://img.shields.io/badge/A2A_Protocol-4285F4?style=flat) ![Claude_Agent_SDK](https://img.shields.io/badge/Claude_Agent_SDK-D97757?style=flat&logo=anthropic&logoColor=white) ![OpenAI_Agents_SDK](https://img.shields.io/badge/OpenAI_Agents_SDK-10A37F?style=flat&logo=openai&logoColor=white) ![Vercel_AI_SDK](https://img.shields.io/badge/Vercel_AI_SDK-000000?style=flat&logo=vercel&logoColor=white) ![Pydantic_AI](https://img.shields.io/badge/Pydantic_AI-E92063?style=flat&logo=pydantic&logoColor=white) ![LlamaIndex](https://img.shields.io/badge/LlamaIndex-4B0082?style=flat) ![CrewAI](https://img.shields.io/badge/CrewAI-FF5A5F?style=flat) ![DSPy](https://img.shields.io/badge/DSPy-2E4053?style=flat) ![Function_Calling](https://img.shields.io/badge/Function_Calling-6C5CE7?style=flat) ![RAG](https://img.shields.io/badge/RAG-0F9D58?style=flat) |
| **LLM Ops & Inference** | ![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white) ![OpenAI_API](https://img.shields.io/badge/OpenAI_API-10A37F?style=flat&logo=openai&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white) ![vLLM](https://img.shields.io/badge/vLLM-1B1F23?style=flat) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white) ![LiteLLM](https://img.shields.io/badge/LiteLLM-4B3F72?style=flat) ![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat) ![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat&logo=postgresql&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat&logo=qdrant&logoColor=white) ![Hugging_Face](https://img.shields.io/badge/HuggingFace-FCC624?style=flat&logo=huggingface&logoColor=black) ![ONNX_Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat&logo=onnx&logoColor=white) ![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat&logo=nvidia&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white) |
| **AI / ML Research** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat&logo=polars&logoColor=white) ![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white) ![PINN](https://img.shields.io/badge/PINN-1F4E79?style=flat) ![Weights_%26_Biases](https://img.shields.io/badge/Weights_%26_Biases-FFBE00?style=flat) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?style=flat&logo=shadcnui&logoColor=white) ![Radix_UI](https://img.shields.io/badge/Radix_UI-161618?style=flat&logo=radixui&logoColor=white) ![TanStack_Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat&logo=reactquery&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-000000?style=flat) ![Framer_Motion](https://img.shields.io/badge/Framer_Motion-EF3AAB?style=flat&logo=framer&logoColor=white) ![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat&logo=turborepo&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white) ![Bun](https://img.shields.io/badge/Bun-000000?style=flat&logo=bun&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white) ![Expo](https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white) |
| **Backend & Data Platform** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![Hono](https://img.shields.io/badge/Hono-E36002?style=flat&logo=hono&logoColor=white) ![tRPC](https://img.shields.io/badge/tRPC-398CCB?style=flat&logo=trpc&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Drizzle_ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat&logo=drizzle&logoColor=black) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white) ![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat&logo=temporal&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black) ![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat&logo=clickhouse&logoColor=black) ![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat&logo=openapiinitiative&logoColor=white) |
| **DevOps / Infra** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) ![GitHub_Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white) ![Cloudflare_Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat&logo=cloudflare&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white) ![Modal](https://img.shields.io/badge/Modal-7FEE64?style=flat&logo=modal&logoColor=black) ![Ray](https://img.shields.io/badge/Ray-028CF0?style=flat&logo=ray&logoColor=white) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat&logo=opentelemetry&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white) ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white) |
| **Automation / Growth** | ![n8n](https://img.shields.io/badge/n8n-E95F2B?style=flat&logo=n8n&logoColor=white) ![Make](https://img.shields.io/badge/Make-A543F4?style=flat&logo=make&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white) ![Browser_Use](https://img.shields.io/badge/Browser_Use-FF6B35?style=flat) ![GA4](https://img.shields.io/badge/GA4-E37400?style=flat&logo=googleanalytics&logoColor=white) ![GTM](https://img.shields.io/badge/GTM-246FDB?style=flat&logo=googletagmanager&logoColor=white) ![Meta_Pixel](https://img.shields.io/badge/Meta_Pixel-0866FF?style=flat&logo=meta&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white) |
| **Collaboration** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) ![Claude_Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white) ![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat&logo=cursor&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white) ![Linear](https://img.shields.io/badge/Linear-5E6AD2?style=flat&logo=linear&logoColor=white) |

---

### 🏆 수상 및 자격 (Awards & Certifications)

* 📘 **2026 한양대학교 SW/AI 융합 창업연구개발과제 선정**
* 🏆 **2026 인하대학교 예비창업패키지 선정 (개발 아이템 INSPEC)**
* 🥇 **2025 한양대학교 SW종합학술대회 대상 수상 (한양대학교 총장상)** [[상장](https://drive.google.com/file/d/1HVLk5WaSdNMeXb5haw91tNy3cuhtH-jl/view?usp=drive_link)]
* 🥈 **2025 한양대학교 AI-커리어 톤 최우수상 수상 (한양대학교 총장상)** [[상장](https://drive.google.com/file/d/1Q7BMRADEfffK7CFVtPD4OmeLpSshbMzr/view?usp=drive_link)]
* 🥇 **2025 한양대학교 SW창업우수상 수상 (우수사례 선정)** [[상장](https://drive.google.com/file/d/1ElzJeMyIpkpBTnQZkAfDp7iTOZ5_CIy2/view?usp=drive_link)]
* 🥉 **2025 한양대학교 SW창업 IR 경진대회 장려상 수상** [[상장](https://drive.google.com/file/d/1Zo5mHCgC7u1pol4WW1IgtiuM8KYdiIzb/view?usp=drive_link)]
* 🥉 **2025 한양대학교 (해동과학연구재단) 해동창업경진대회 장려상 수상** [[상장](https://drive.google.com/file/d/1eJF640O1n6q5uPLAVahV1ltBYKiN-q_Q/view?usp=drive_link)]
* 🥈 **2025 한양대학교 Deep-Tech Audition 최우수상 수상 – 드론 배터리 상태관리 및 관제 통합 시스템** [[상장](https://drive.google.com/file/d/1Oc3ZoVfWXgThTUCW2gSNPs-ZMgIMD1jR/view?usp=drive_link)]
* 🥈 **2025 한양대학교 SW융합대학 포트폴리오 경진대회 최우수상 수상 – 개인 앱/AI 프로젝트 기반 종합 평가** [[상장](https://drive.google.com/file/d/1XQXHYNCTuzd04Ttodz57X692wfN0Zd0h/view?usp=drive_link)]
* 🥈 **한양대학교 SW중심대학 에세이 공모전 우수상**
* 🥉 **한양대학교 SW중심대학 학생포트폴리오경진대회 동상**
* 🏆 **경기도 영주시 드론실증사업 선정 및 납품 - 드론 배터리 통합관제 시스템(Guardion)**
* 🏅 2024 한양대학교 SID Audition 본선 진출 – AI 기반 디테일 신체 치수별 패션 아이템 추천 알고리즘
* 📚 와디즈 전자책 프로젝트 2건 성공 – 달성률 1200%, 3000%로 콘텐츠 분야 연속 펀딩 달성
* 📘 SQLD (SQL 개발자 자격증) – 한국데이터산업진흥원
* 📗 ADsP (데이터분석 준전문가) – 한국데이터산업진흥원
* 📙 CPMS (프로젝트관리사)

---

## 📜 특허 (Patents)

💡 **블라인드 입찰 기반 인테리어 시공업체 공정 검증 및 공정 대금 분할지급 시스템 및 그 방법**
출원번호: KR-10-2025-0098033 (KIPO) 
주요 내용: 시공 단계별 검증을 통한 투명한 인테리어 거래 및 대금 지급 시스템 설계 

💡 **신체 데이터와 피드백 데이터를 활용한 개인 맞춤형 추천 시스템 및 방법**
출원번호: KR-10-2025-0009967 (KIPO) 
주요 내용: 사용자 체형 데이터와 피드백 기반의 정밀한 패션/아이템 추천 알고리즘

---

## 🚀 Products

<br>

<div align="center">

### 🛰️ [Autopilot (AI 마케팅 실행 시스템)](https://www.autopilot.it.kr/)
> 제품 하나만 넣으면 시장 판단 → 추적 세팅 → 상세페이지 진단 → 퍼포먼스 리포트가 한 흐름으로 이어지는, 마케팅 실행 자동화 에이전트 플랫폼

🔍 **Market Radar** — 경쟁 구도·검색 수요 분석으로 진입 가능성을 리포트 한 장으로 판단  
🏷️ **Tracking Setup / GTM Install** — GTM 컨테이너 자동 생성 및 스니펫 주입, GA4·Meta Pixel 누락 탐지와 개선 코드 제공  
📊 **Heatmap / Product Detail / Performance Lens** — 클릭·스크롤 심도 수집, 상세페이지 전환 품질 5축 진단, 일 단위 액션 처방

<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat"/>
<img src="https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/GTM-246FDB?style=flat&logo=googletagmanager&logoColor=white"/>

🔗 [서비스 바로가기](https://www.autopilot.it.kr/)

</div>

---

<div align="center">

### 🏗️ [INSPEC (인테리어 감리자 파견 플랫폼)](https://inspec.it.kr/)
> 인테리어 시공의 시작과 끝을 중립적 감리자가 점검하고, 철거부터 마감까지 단계별 기록을 발주자가 실시간으로 확인하는 감리 플랫폼

🧾 시공 단계별 체크리스트·사진 기록의 실시간 공유 구조 설계  
🛡️ 중립 감리자 파견 기반의 분쟁 예방 및 공정 검증 프로세스  
🔐 특허(KR-10-2025-0098033) 기반의 공정 검증·대금 분할지급 로직 연계

<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/REST_API-FF6F61?style=flat"/>

🔗 [서비스 바로가기](https://inspec.it.kr/)

</div>

---

## 🧪 Projects

<br>

<div align="center">

### 🧩 [MetaSurface Designer (메타표면 설계 웹앱)](https://github.com/Haeseong-Kwon/Metasurface-Designer)
> 목표 성능(파장/NA/초점거리/PSF 등)을 입력하면 메타표면(phase map/파라미터)을 자동 설계하고 결과를 시각화하는 Inverse Design 제품

<img src="https://github.com/Haeseong-Kwon/Metasurface-Designer/blob/main/demo_smooth.gif?raw=true" width="700" alt="MetaSurface Designer Demo">

⚡ 설계 프리셋(메타렌즈/빔 스티어링) + 결과 리포트(오차/효율/수렴 그래프) 자동 생성  
🧠 Surrogate Model 기반 빠른 탐색 + Gradient-based 최적화 지원  
📤 파라미터 Export(CSV/JSON) + 설계 히스토리/버전 관리

<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>

🔗 [Repository](https://github.com/Haeseong-Kwon/Metasurface-Designer) | [기술 문서](https://github.com/Haeseong-Kwon/Metasurface-Designer/blob/main/README.md)

</div>

---

<div align="center">

### 🧷 [Metasurface Process Yield Predictor (메타표면 공정 수율 예측)](https://github.com/Haeseong-Kwon/Metasurface-Process-Yield-Predictor)
> 공정 파라미터/측정 지표를 기반으로 수율 저하 원인을 예측하고, 개선 액션을 추천하는 메타표면 공정 분석 제품

<img src="https://github.com/Haeseong-Kwon/Metasurface-Process-Yield-Predictor/blob/main/docs/yield_predictor_demo.gif?raw=true" width="700" alt="Process Yield Predictor Demo">

📌 공정 조건(치수 편차/두께/리소그래피 오차 등) → 성능 저하 패턴 학습  
📈 수율 예측 + 원인 중요도(Feature importance) 시각화  
🧪 실험 케이스 저장/비교 + 리포트 자동 생성

<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Report_PDF-8E44AD?style=flat"/>

🔗 [Repository](https://github.com/Haeseong-Kwon/Metasurface-Process-Yield-Predictor) | [기술 문서](https://github.com/Haeseong-Kwon/Metasurface-Process-Yield-Predictor/blob/main/README.md)

</div>

---

<div align="center">

### 🧱 [Meta-Atom Dataset Factory (시뮬 데이터셋 생성/관리 플랫폼)](https://github.com/Haeseong-Kwon/Meta-Atom-Dataset-Factory)
> 메타-아톰 파라미터 sweep → 결과 수집/정제/검증 → 학습용 데이터셋을 “제품처럼” 만드는 연구 생산성 도구

<img src="https://github.com/Haeseong-Kwon/Meta-Atom-Dataset-Factory/blob/main/dataset_factory_demo.webp?raw=true" width="700" alt="Dataset Factory Demo">

🧪 Job Queue 기반 시뮬 실행/실패 재시도/버전 관리  
📦 데이터셋 카드(분포/커버리지/품질지표) 자동 생성 + 다운로드/공유  
🔌 향후 EM 시뮬 툴 연동을 고려한 확장형 파이프라인

<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>

🔗 [Repository](https://github.com/Haeseong-Kwon/Meta-Atom-Dataset-Factory) | [기술 문서](https://github.com/Haeseong-Kwon/Meta-Atom-Dataset-Factory/blob/main/README.md)

</div>

---

<div align="center">

### 🧠 [Brain MRI Assist (뇌 MRI 분석 웹뷰어)](https://github.com/Haeseong-Kwon/Brain-MRI-Assist)
> MRI 업로드 → 세그/분류 결과를 오버레이로 보여주고, 자동 요약 리포트를 생성하는 Biomedical AI 제품

<img src="https://github.com/Haeseong-Kwon/Brain-MRI-Assist/blob/main/brain_mri_assist_demo.gif?raw=true" width="700" alt="Brain MRI Assist Demo">

🧬 세그멘테이션(U-Net 등) / 분류 모델 + 신뢰도 제공  
🖼️ 슬라이스 뷰어 + 결과 오버레이 + 케이스 저장/비교  
📄 결과 요약 리포트(PDF) + 추론 API 제공

<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/HuggingFace-FCC624?style=flat&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/DICOM/NIfTI-000000?style=flat"/>

🔗 [Repository](https://github.com/Haeseong-Kwon/Brain-MRI-Assist) | [기술 문서](https://github.com/Haeseong-Kwon/Brain-MRI-Assist/blob/main/README.md)

</div>

---

<div align="center">

### 🌊 [PINN WaveLab (Physics-Informed Neural Network 실험 플랫폼)](https://github.com/Haeseong-Kwon/PINN-WaveLab)
> PDE 제약 기반으로 2D 파동/전자기 문제를 학습하고, 기준해 대비 오차/학습 안정성을 인터랙티브하게 검증하는 웹 실험실

<img src="https://github.com/Haeseong-Kwon/PINN-WaveLab/blob/main/pinn_wavelab_demo.gif?raw=true" width="700" alt="PINN WaveLab Demo">

🎛️ 경계조건/소스/재료상수 슬라이더로 실험 파라미터 조절  
🧠 Loss term ablation(경계/물리항 on/off) + 결과 heatmap/오차맵 자동 시각화  
📊 학습 곡선/리포트 자동 생성 + 실험 히스토리 저장

<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Recharts-8884D8?style=flat"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>

🔗 [Repository](https://github.com/Haeseong-Kwon/PINN-WaveLab) | [기술 문서](https://github.com/Haeseong-Kwon/PINN-WaveLab/blob/main/README.md)

</div>

---

<div align="center">

### 🧼 [Optics Restoration Studio (광학/센서 기반 이미지 복원 제품)](https://github.com/Haeseong-Kwon/Optics-Restoration-Studio)
> 광학 블러/수차/센서 노이즈(shot/read) 모델을 선택하면 자동으로 복원 모델을 적용하고 정량 지표와 전/후 비교를 제공하는 복원 스튜디오

<img src="https://github.com/Haeseong-Kwon/Optics-Restoration-Studio/blob/main/optics_restoration_demo_v6_final.webp?raw=true" width="700" alt="Optics Restoration Studio Demo">

📷 RAW/저조도/모션블러 모드 + 전/후 비교 뷰어  
📈 PSNR/SSIM 리포트 + 모델 비교(베이스라인 vs 개선모델)  
🚀 업로드 → 즉시 추론 → 결과 다운로드까지 “프로덕트 흐름” 완성

<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat&logo=reactquery&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/REST_API-FF6F61?style=flat"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white"/>

🔗 [Repository](https://github.com/Haeseong-Kwon/Optics-Restoration-Studio) | [기술 문서](https://github.com/Haeseong-Kwon/Optics-Restoration-Studio/blob/main/README.md)

</div>

---

<div align="center">

### 🧪 [CMOS Sensor Health Dashboard (센서 결함/노이즈 진단 대시보드)](https://github.com/Haeseong-Kwon/CMOS-Sensor-Health-Dashboard)
> 센서 프레임/로그를 업로드하면 핫픽셀/고정패턴노이즈/라인 결함 등을 자동 탐지하고 리포트화하는 QA형 제품

<img src="https://github.com/Haeseong-Kwon/CMOS-Sensor-Health-Dashboard/blob/main/assets/sensor_dashboard_full_workflow.gif?raw=true" width="700" alt="CMOS Sensor Health Dashboard Demo">

🧠 결함 탐지 모델 + 통계 기반 품질 지표 자동 산출  
🗺️ 결함 맵 시각화 + 배치 검사 + 불량률 추이 차트  
📄 PDF 리포트 생성 + 케이스 저장/비교 기능

<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/shadcn/ui-000000?style=flat&logo=shadcnui&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Data_Visualization-9F86C0?style=flat"/>

🔗 [Repository](https://github.com/Haeseong-Kwon/CMOS-Sensor-Health-Dashboard) | [기술 문서](https://github.com/Haeseong-Kwon/CMOS-Sensor-Health-Dashboard/blob/main/README.md)

</div>

---

<div align="center">

### 🕶️ [AR/VR Display Calibrator (디스플레이 보정 도구)](https://github.com/Haeseong-Kwon/AR-VR-Display-Calibrator)
> 캘리브레이션 패턴 촬영 → 왜곡/색수차/수차를 추정해 보정 LUT/파라미터를 생성하는 AR/VR 디스플레이 보정 제품

<img src="https://github.com/Haeseong-Kwon/AR-VR-Display-Calibrator/blob/main/ar_vr_calibrator_demo.gif?raw=true" width="700" alt="AR/VR Display Calibrator Demo">

🎯 기기 프로필 저장 + 전/후 비교  
🧠 최적화 기반 파라미터 추정 + 보정값 Export(LUT/JSON)  
📱 모바일 촬영 입력 지원을 고려한 UX 설계

<img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Optimization-FFB703?style=flat"/>
<img src="https://img.shields.io/badge/REST_API-FF6F61?style=flat"/>

🔗 [Repository](https://github.com/Haeseong-Kwon/AR-VR-Display-Calibrator) | [기술 문서](https://github.com/Haeseong-Kwon/AR-VR-Display-Calibrator/blob/main/README.md)

</div>

---

<div align="center">

### 📈 [Photonics Experiment Log Analyzer (측정 데이터 분석 SaaS)](https://github.com/Haeseong-Kwon/Photonics-Experiment-Log-Analyzer)
> 분광/스펙트럼/실험 로그를 업로드하면 피크 탐지·피팅·분류·이상치를 자동 리포팅하는 실험 데이터 분석 제품

<img src="https://github.com/Haeseong-Kwon/Photonics-Experiment-Log-Analyzer/blob/main/photonics_log_analyzer_demo.gif?raw=true" width="700" alt="Photonics Experiment Log Analyzer Demo">

🔍 자동 피크 탐지/피팅 모델 선택 + 실험 세션 관리  
📊 결과 공유 링크 + PDF 리포트 자동 생성  
🔌 다양한 측정 포맷(CSV 등) 확장형 파서 구조

<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Automation-FFD43B?style=flat"/>
<img src="https://img.shields.io/badge/Report_PDF-8E44AD?style=flat"/>

🔗 [Repository](https://github.com/Haeseong-Kwon/Photonics-Experiment-Log-Analyzer) | [기술 문서](https://github.com/Haeseong-Kwon/Photonics-Experiment-Log-Analyzer/blob/main/README.md)

</div>

---

<div align="center">

### ☀️ [Solar Cell Curve Intelligence (IV Curve 분석/최적화)](https://github.com/Haeseong-Kwon/Solar-Cell-Curve-Intelligence)
> IV curve/환경 파라미터로 효율을 추정하고 원인 분석 및 개선 액션을 추천하는 태양전지 분석/최적화 제품

<img src="https://github.com/Haeseong-Kwon/Solar-Cell-Curve-Intelligence/blob/main/solar_cell_intelligence_demo.gif?raw=true" width="700" alt="Solar Cell Curve Intelligence Demo">

📉 곡선 클러스터링 + 결함 유형 분류 + 성능 예측  
🧠 최적화 기반 추천(공정/재료/구조 방향)  
📊 실험 히스토리 관리 + 결과 대시보드 제공

<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat"/>
<img src="https://img.shields.io/badge/Optimization-FFB703?style=flat"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>

🔗 [Repository](https://github.com/Haeseong-Kwon/Solar-Cell-Curve-Intelligence) | [기술 문서](https://github.com/Haeseong-Kwon/Solar-Cell-Curve-Intelligence/blob/main/README.md)

</div>

---

<div align="center">

### 🧫 [Medical GenAI Augmentor (의료 데이터 증강 파이프라인)](https://github.com/Haeseong-Kwon/Medical-GenAI-Augmentor)
> 데이터 부족/불균형을 해결하기 위한 조건부 생성(증강) → 품질 필터링 → 성능 전/후 리포트까지 묶은 생성형AI 제품

<img src="https://github.com/Haeseong-Kwon/Medical-GenAI-Augmentor/blob/main/medical_augmentor_demo.gif?raw=true" width="700" alt="Medical GenAI Augmentor Demo">

🪄 생성 샘플 품질 자동 필터링 + 다양성/유사도 지표  
📊 증강 전/후 학습 성능 비교 리포트 자동 생성  
🔁 워크플로우 자동화(n8n/Make)와 연동 가능한 파이프라인 설계

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/HuggingFace-FCC624?style=flat&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/n8n-E95F2B?style=flat&logo=n8n&logoColor=white"/>
<img src="https://img.shields.io/badge/Make-A543F4?style=flat&logo=make&logoColor=white"/>
<img src="https://img.shields.io/badge/Automation-FFD43B?style=flat"/>

🔗 [Repository](https://github.com/Haeseong-Kwon/Medical-GenAI-Augmentor) | [기술 문서](https://github.com/Haeseong-Kwon/Medical-GenAI-Augmentor/blob/main/README.md)

</div>

---

<div align="center">

### 🏗️ INPICK (Interior Platform)
> 소비자와 인테리어 업체를 연결하는 실시간 견적 중개 + 감리 관리 앱

🛠️ Flutter 기반 **크로스플랫폼 앱 직접 개발** 🔧 PostgreSQL + REST API로 백엔드 구성 (RLS 정책, 트랜잭션 포함)  
💰 계약, 시공단계, **중도금** 지불 흐름을 포함한 **보증형 거래 시스템 설계**

<img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/REST_API-FF6F61?style=flat"/>

🔒 비공개 저장소 (Private Repository)

</div>

---

<div align="center">

### 🚁 GUARDION (드론 상태 대시보드 앱)
> 실시간 드론 상태 데이터(온도, 센서 등)를 시각화하는 모니터링 시스템

🖥️ Flutter 기반 **프론트엔드 개발 담당** 📡 실시간 API 연동을 통해 **온도/속도/센서 상태를 시각화** 📋 장치 목록 조회, 통합 데이터 상세, 알림 상세 화면 구현

<img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/API_Integration-000000?style=flat"/>
<img src="https://img.shields.io/badge/Team_Collaboration-Git?style=flat&logo=git&logoColor=white"/>

🔒 비공개 저장소 (Private Repository)

</div>

---

## 📫 Contact

- 📧 **Email**: aopbusiness2025@gmail.com
- 🐙 **GitHub**: [https://github.com/Haeseong-Kwon](https://github.com/Haeseong-Kwon)  
- 🌐 **Portfolio**: [포트폴리오 웹사이트](https://portfolio-website-pi-six-74.vercel.app/)  
- 🛰️ **Autopilot**: [https://www.autopilot.it.kr/](https://www.autopilot.it.kr/)  
- 🏗️ **INSPEC**: [https://inspec.it.kr/](https://inspec.it.kr/)
