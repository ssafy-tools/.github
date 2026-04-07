<div align="center">

# SSAFY Tools

**Samsung Software Academy for Youth — 내부 도구 & 프로젝트 아카이브**

[![Org](https://img.shields.io/badge/org-ssafy--tools-blue?style=flat-square)](https://github.com/ssafy-tools)
[![Repos](https://img.shields.io/badge/repos-19-green?style=flat-square)]()
[![Access](https://img.shields.io/badge/access-private-red?style=flat-square)]()

</div>

---

SSAFY 교육 과정에서 개발한 자동화 도구, 인프라 구성, 팀 프로젝트 산출물을 체계적으로 관리하는 조직입니다.

## 자동화 도구

| Repo | 설명 | Stack |
|------|------|-------|
| [ssafy-crawler](https://github.com/ssafy-tools/ssafy-crawler) | 강의 다시보기 크롤링 + HLS 다운로드 + Whisper 전사 | Python |
| [ssafy-peer-eval](https://github.com/ssafy-tools/ssafy-peer-eval) | 에듀싸피 상호평가 자동화 (API 리버스엔지니어링) | Python, JS |
| [ssafy-resume-automation](https://github.com/ssafy-tools/ssafy-resume-automation) | 채용박람회 자소서 자동화 (Claude Code + Chrome MCP) | Python |
| [ssafy-spec-ocr](https://github.com/ssafy-tools/ssafy-spec-ocr) | 프로젝트 명세서 텍스트 추출 + 아이디어 분석 | Python, JS |
| [ssafy-net-profiles](https://github.com/ssafy-tools/ssafy-net-profiles) | 유선랜 IP 프로파일 전환 도구 | PowerShell |
| [ssafy-galaxy-fan-fix](https://github.com/ssafy-tools/ssafy-galaxy-fan-fix) | Galaxy Book 팬 제어 스크립트 | PowerShell |

## 인프라 & 가이드

| Repo | 설명 | Stack |
|------|------|-------|
| [ssafy-infra](https://github.com/ssafy-tools/ssafy-infra) | 학습 환경 인프라 구성 및 설정 관리 | — |
| [ssafy-infra-docs](https://github.com/ssafy-tools/ssafy-infra-docs) | A408 인프라 포털 (구조도 + 대시보드 + 운영 가이드) | HTML, CSS, JS |
| [ssafy-gpu](https://github.com/ssafy-tools/ssafy-gpu) | GPU 개발서버 + EC2 접속 가이드 | Shell |
| [ssafy-mm](https://github.com/ssafy-tools/ssafy-mm) | Mattermost 설정 및 채널 가이드 | Shell |
| [ssafy-planning-docs](https://github.com/ssafy-tools/ssafy-planning-docs) | 프로젝트 기획 아이디어 저장소 | Markdown |
| [ssafy-llm-handbook](https://github.com/ssafy-tools/ssafy-llm-handbook) | LLM 교육 기반 RAG / Agent / Fine-Tuning 핸드북 | Markdown |

## 골목식당 — AI 기반 영세 요식업 통합 경영 솔루션

CCTV 영상 분석으로 매장 인력을 최적화하고, 날씨·매출 데이터를 기반으로 경영 의사결정을 지원하는 풀스택 프로젝트.

| Repo | 역할 | Stack |
|------|------|-------|
| [ssafy-golmok-backend](https://github.com/ssafy-tools/ssafy-golmok-backend) | REST API + 비즈니스 로직 | Spring Boot, Java |
| [ssafy-golmok-frontend](https://github.com/ssafy-tools/ssafy-golmok-frontend) | 매장 관리 대시보드 UI | Next.js, TypeScript |
| [ssafy-golmok-ai](https://github.com/ssafy-tools/ssafy-golmok-ai) | CCTV 인력 분석 + 추론 서버 | FastAPI, Python |
| [ssafy-golmok-infra](https://github.com/ssafy-tools/ssafy-golmok-infra) | AWS 인프라 + Docker + CI/CD | Shell, Docker |
| [ssafy-golmok-camera](https://github.com/ssafy-tools/ssafy-golmok-camera) | 매장 영상 촬영 + AI 업로드 앱 | Kotlin, Android |

## YEJI — EC2 기반 AI 서비스 인프라

| Repo | 역할 | Stack |
|------|------|-------|
| [ssafy-yeji-infra](https://github.com/ssafy-tools/ssafy-yeji-infra) | EC2 인프라 구축 + vLLM 서빙 + 운영 문서 | Shell, Python |

---

> **이 조직의 모든 저장소는 PRIVATE입니다.** 팀원 전용 — org 멤버에게 자동 읽기 권한이 부여됩니다.
