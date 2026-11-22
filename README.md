## 박예나 · Park Yena

**Backend Developer** — Java · Spring Boot · Python

Spring Boot로 서버를 만들고 Gemini · OpenAI · Claude 같은 AI API를 서비스에 붙이는 일을 주로 합니다.  
배포 · 모니터링 · 장애 알림까지 직접 챙기며 실제 사용자가 쓰는 서비스를 운영하고 있습니다.

[![Email](https://img.shields.io/badge/yena7park@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:yena7park@gmail.com)
[![GitHub](https://img.shields.io/badge/aneykrap-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/aneykrap)

<br/>

### 🙋‍♀️ About

- 이화여자대학교 컴퓨터공학 전공
- SOPT 38기 서버 파트 — AppJam에서 만든 Timo를 가입자 약 100명 서비스로 운영 중
- 이화글로벌프론티어 기술 총괄 — 국내 5곳 · 미국 6곳 기관을 직접 섭외해 영어 인터뷰 12회 진행
- ADsP (데이터분석 준전문가) · JLPT N2

<br/>

### 🛠 Projects

| Project | 한 일 | Stack |
|:--|:--|:--|
| **[Timo](https://github.com/Team-Timo/Timo-Server)**<br/><sub>AI가 걸릴 시간을 추천하는 타임박싱 투두<br/>SOPT AppJam 특별상 · 가입자 약 100명</sub> | **백엔드** · 3인<br/>Gemini 호출을 트랜잭션 밖으로 빼고 Redis Lua로 호출 한도 배분<br/>복합 인덱스로 AI 기록 조회 122ms → 4.12ms<br/>Nginx Blue/Green 무중단 배포 · Prometheus · Grafana 모니터링 | `Spring Boot` `MySQL` `Redis` `Gemini` `Docker` |
| **[Deary](https://github.com/Deary-App/Deary-Server)**<br/><sub>외국어 일기를 쓰고 서로 문장을 교정해 주는 앱<br/>가입자 30명</sub> | **서버** · 2인<br/>OpenAI Moderation 자동 검수를 커밋 후 비동기로 처리<br/>세션 ID로 로그아웃 · 탈퇴한 토큰 즉시 차단<br/>목록 조회 N+1 제거 · 낙관적 락으로 교정 요청 중복 방지 | `Java 21` `Spring Boot 4` `PostgreSQL` `Flyway` `Sentry` |
| **Deary 이슈 에이전트**<br/><sub>Sentry 5xx 오류를 보고 GitHub 이슈를 정리하는 AI 에이전트<br/>(비공개 레포)</sub> | **1인 개발**<br/>분명한 경우는 코드 규칙으로 먼저 처리하고 애매한 경우만 AI에 넘김<br/>이슈 규칙을 검사하는 MCP 서버를 만들고 도구는 3개만 공개<br/>웹훅 서명 검증 · 중복 제거 · 재시도 · 테스트 103개 | `Python` `FastAPI` `MCP` `Claude API` `Docker` |
| **[COMMA](https://github.com/WarmElephantMario/COMMA)**<br/><sub>시·청각장애 학습자를 위한 AI 학습 보조 앱<br/>캡스톤디자인 금상</sub> | **풀스택** · 3인<br/>대체텍스트 프롬프트 규칙으로 스크린리더가 읽던 기호 7개 → 0개<br/>시각장애 학우 6명 평가 평균 9.0점<br/>자막과 대체텍스트를 슬라이드별로 묶은 복습 화면 · Node.js API 약 20개 | `Flutter` `Node.js` `MySQL` `OpenAI` |

<details>
<summary><b>그 밖의 프로젝트</b></summary>
<br/>

- **[WhisSYNC](https://github.com/BFF-Barrier-Free-Forever/Automated-Captioning)** — Whisper가 받아 적은 대사를 대본과 맞춰 공연 자막을 띄우는 Python 알고리즘. 무관 발화 1,440개 실험으로 애드리브 기준을 0.30 → 0.35로 조정
- **[모두의 택배](https://github.com/aneykrap/Team_ModooBox)** — 우편 물류 공공데이터로 배송일이 줄어드는 하루 물량 지점을 찾아 공동배송 단계 기준을 정함 (pandas · statsmodels · SciPy)

</details>

<br/>

### 🏆 Awards

| | 수상 | 프로젝트 |
|:--:|:--|:--|
| 2026 | SOPT 38기 AppJam 특별상 | Timo |
| 2025 | 국토교통 데이터 활용 경진대회 우수상 (한국교통연구원 원장상) | 모두의 택배 |
| 2024 | Ewha Engineering Capstone Design Contest 금상 | COMMA |
| 2024 | Ewha Engineering Capstone Design Contest 은상 | WhisSYNC |
| 2024 | SW중심대학 연합 SW Festival 창업경진대회 대상 | COMMA |

<br/>

### 🧰 Tech Stack

| | |
|:--|:--|
| **Backend** | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![JPA](https://img.shields.io/badge/Spring_Data_JPA-59666C?style=flat-square&logo=hibernate&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white) |
| **AI · Data** | ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white) ![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=claude&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white) ![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) |
| **Infra · Ops** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white) ![Mixpanel](https://img.shields.io/badge/Mixpanel-7856FF?style=flat-square&logo=mixpanel&logoColor=white) |
| **Front · Tool** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
