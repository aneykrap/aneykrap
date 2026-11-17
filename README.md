# 박예나 | Park Yena

백엔드 개발자입니다. 실제 서비스에서 LLM 기능을 운영하고, AI가 안전하게 쓸 수 있는 도구를 서버로 만듭니다.

## 프로젝트

| 프로젝트 | 한 일 | 레포 |
| --- | --- | --- |
| **Timo** · 타임박싱 투두 (가입자 약 100명) | Gemini 소요시간 추천 · 사용자별 · 전체 호출 한도 배분(Redis Lua) · AI 호출 중 DB 커넥션 분리 · 인덱스로 조회 122ms → 4.12ms | [Team-Timo/Timo-Server](https://github.com/Team-Timo/Timo-Server) |
| **Deary 이슈 에이전트** · 서버 에러를 GitHub 이슈로 정리하는 AI 에이전트 | Sentry 웹훅 → Claude tool use → 직접 만든 MCP 서버(도구 3개, 규칙은 서버가 검사) · FastAPI · Docker Compose · GitHub Actions · 테스트 85개 | 공개 준비 중 |
| **Deary** · 외국어 일기 · 문장 교정 앱 서버 | 액세스 토큰 세션 ID로 로그아웃 즉시 차단 · 동시 재발급 8건 중 1건만 성공 · 교정 낙관적 잠금 · AI 코딩 도구 작업 규칙(AGENTS.md · CodeRabbit · PR 빌드 검사) | [Deary-App/Deary-Server](https://github.com/Deary-App/Deary-Server) |
| **COMMA** · 시 · 청각장애 학습자를 위한 AI 학습 보조 앱 | 스크린리더용 대체텍스트 프롬프트 규칙(GPT-4o) · Flutter 화면 · Node.js · MySQL API 약 20개 | [WarmElephantMario/COMMA](https://github.com/WarmElephantMario/COMMA) |

## 기술

- **Backend** Java · Spring Boot · Spring Data JPA · MySQL · PostgreSQL · Redis · Flyway · Node.js · FastAPI
- **AI** Gemini API · OpenAI API · Claude API · MCP
- **Infra · Ops** Linux · Docker · GitHub Actions · Nginx · AWS (Lambda · EC2 · RDS) · Sentry · Prometheus · Grafana
- **Tool** Git · Claude Code · Codex · CodeRabbit

## 연락

yena7park@gmail.com
