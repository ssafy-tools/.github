<div align="center">

<img src="https://img.shields.io/badge/SSAFY-14기_A408-0066FF?style=for-the-badge&labelColor=000000" />
<img src="https://img.shields.io/badge/repos-19-00C853?style=for-the-badge&labelColor=000000" />
<img src="https://img.shields.io/badge/access-PRIVATE-FF1744?style=for-the-badge&labelColor=000000" />

# ssafy-tools

SSAFY 교육 과정에서 만든 **자동화 도구**, **인프라**, **팀 프로젝트**를 모아둔 조직입니다.

</div>

---

### 🔧 자동화 도구

> 반복 작업을 코드로 해결한 내부 유틸리티

| | Repo | 한 줄 설명 | Stack |
|:---:|------|-----------|:-----:|
| 📹 | **[ssafy-crawler]** | 강의 다시보기 HLS 다운로드 + Whisper 전사 | `Python` |
| 📝 | **[ssafy-resume-automation]** | 채용박람회 자소서 자동화 (Claude + Chrome MCP) | `Python` |
| ✅ | **[ssafy-peer-eval]** | 에듀싸피 상호평가 API 자동화 + 등급 최적화 | `Python` `JS` |
| 📄 | **[ssafy-spec-ocr]** | 프로젝트 명세서 텍스트 추출 + 아이디어 분석 | `Python` `JS` |
| 🌐 | **[ssafy-net-profiles]** | 유선랜 IP 프로파일 전환 도구 | `PowerShell` |
| 💨 | **[ssafy-galaxy-fan-fix]** | Galaxy Book 팬 제어 스크립트 | `PowerShell` |

### 📚 인프라 & 가이드

> 학습 환경 구성, 서버 운영, 교육 자료

| | Repo | 한 줄 설명 | Stack |
|:---:|------|-----------|:-----:|
| 📊 | **[ssafy-infra-docs]** | A408 인프라 포털 (구조도 + 대시보드) | `HTML` `CSS` |
| 🖥️ | **[ssafy-gpu]** | GPU 개발서버 + EC2 접속 가이드 | `Shell` |
| 💬 | **[ssafy-mm]** | Mattermost 설정 및 채널 가이드 | `Shell` |
| 🤖 | **[ssafy-llm-handbook]** | RAG / Agent / Fine-Tuning 기술 핸드북 | `Markdown` |

---

### 🍜 골목식당

> **AI 기반 영세 요식업 통합 경영 솔루션** — CCTV 영상 분석으로 매장 인력을 최적화하고, 날씨·매출 데이터 기반 경영 의사결정을 지원

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   Camera    │────▶│   AI Server │────▶│   Backend   │
│   (Kotlin)  │     │  (FastAPI)  │     │ (Spring Boot)│
└─────────────┘     └─────────────┘     └──────┬──────┘
                                               │
                    ┌─────────────┐     ┌──────▼──────┐
                    │    Infra    │     │  Frontend   │
                    │  (Docker)  │     │  (Next.js)  │
                    └─────────────┘     └─────────────┘
```

| | Repo | 역할 | Stack |
|:---:|------|------|:-----:|
| ☕ | **[ssafy-golmok-backend]** | REST API + 비즈니스 로직 | `Java` `Spring Boot` |
| 🎨 | **[ssafy-golmok-frontend]** | 매장 관리 대시보드 UI | `TypeScript` `Next.js` |
| 🧠 | **[ssafy-golmok-ai]** | CCTV 인력 분석 + 추론 서버 | `Python` `FastAPI` |
| 🐳 | **[ssafy-golmok-infra]** | AWS 인프라 + Docker + CI/CD | `Shell` `Docker` |
| 📱 | **[ssafy-golmok-camera]** | 매장 영상 촬영 + AI 업로드 앱 | `Kotlin` `Android` |

---

### 🏥 YEJI

> EC2 기반 AI 서비스 인프라 — vLLM 서빙 + GPU 인스턴스 운영

| | Repo | 역할 | Stack |
|:---:|------|------|:-----:|
| ☁️ | **[ssafy-yeji-infra]** | EC2 인프라 구축 + vLLM + 운영 문서 | `Shell` `Python` |

---

<div align="center">

<sub>모든 저장소는 <b>PRIVATE</b>입니다 · org 멤버에게 자동 읽기 권한 부여</sub>

</div>

<!-- link refs -->
[ssafy-crawler]: https://github.com/ssafy-tools/ssafy-crawler
[ssafy-resume-automation]: https://github.com/ssafy-tools/ssafy-resume-automation
[ssafy-peer-eval]: https://github.com/ssafy-tools/ssafy-peer-eval
[ssafy-spec-ocr]: https://github.com/ssafy-tools/ssafy-spec-ocr
[ssafy-net-profiles]: https://github.com/ssafy-tools/ssafy-net-profiles
[ssafy-galaxy-fan-fix]: https://github.com/ssafy-tools/ssafy-galaxy-fan-fix
[ssafy-infra-docs]: https://github.com/ssafy-tools/ssafy-infra-docs
[ssafy-gpu]: https://github.com/ssafy-tools/ssafy-gpu
[ssafy-mm]: https://github.com/ssafy-tools/ssafy-mm
[ssafy-llm-handbook]: https://github.com/ssafy-tools/ssafy-llm-handbook
[ssafy-golmok-backend]: https://github.com/ssafy-tools/ssafy-golmok-backend
[ssafy-golmok-frontend]: https://github.com/ssafy-tools/ssafy-golmok-frontend
[ssafy-golmok-ai]: https://github.com/ssafy-tools/ssafy-golmok-ai
[ssafy-golmok-infra]: https://github.com/ssafy-tools/ssafy-golmok-infra
[ssafy-golmok-camera]: https://github.com/ssafy-tools/ssafy-golmok-camera
[ssafy-yeji-infra]: https://github.com/ssafy-tools/ssafy-yeji-infra
