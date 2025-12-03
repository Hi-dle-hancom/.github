# 🎯 Hi-dle (Hancom AI Python Assistant)

> **AI 기반 Python 코딩 어시스턴트 프로젝트**  
> SSAFY 11기 자율 프로젝트 | 한컴MDS 특화 프로젝트

## 📌 프로젝트 소개

Hi-dle은 Python 개발자를 위한 **AI 기반 통합 코딩 어시스턴트**입니다.  
코드 생성, 분석, 최적화, 그리고 실시간 코드 리뷰까지 - 개발 프로세스 전반을 지원합니다.

### 🌟 주요 기능

- **🤖 AI 코드 생성**: 자연어로 요청하면 즉시 Python 코드 생성
- **📊 코드 분석**: 복잡도 분석, 성능 병목 지점 탐지
- **⚡ 최적화 제안**: 더 나은 알고리즘과 패턴 추천
- **🔍 실시간 코드 리뷰**: 코딩 컨벤션 검사 및 개선 사항 제안
- **🎨 프롬프트 엔지니어링**: vLLM + LoRA 기반 고성능 추론

## 🏗️ 시스템 아키텍처

```
┌─────────────┐      ┌──────────────┐      ┌─────────────┐
│   Frontend  │─────▶│   Backend    │─────▶│  AI Server  │
│   (Vue.js)  │      │ (Spring Boot)│      │   (vLLM)    │
└─────────────┘      └──────────────┘      └─────────────┘
                            │
                            ▼
                     ┌──────────────┐
                     │   Database   │
                     │  (PostgreSQL)│
                     └──────────────┘
```

## 🛠️ 기술 스택

### Frontend
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)

### Backend
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### AI/ML
![vLLM](https://img.shields.io/badge/vLLM-FF6F00?style=flat-square)
![LoRA](https://img.shields.io/badge/LoRA-8B5CF6?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

## 📂 Repository 구조

| Repository | 설명 | 기술 스택 |
|-----------|------|----------|
| [frontend](https://github.com/Hi-dle-hancom/frontend) | 사용자 인터페이스 | Vue.js, TypeScript |
| [backend](https://github.com/Hi-dle-hancom/backend) | RESTful API 서버 | Spring Boot, Java |
| [AI](https://github.com/Hi-dle-hancom/AI) | AI 모델 추론 서버 | Python, FastAPI |
| [vLLM-LoRA-Server-Prompt-Engineering](https://github.com/Hi-dle-hancom/vLLM-LoRA-Server-Prompt-Engineering) | LLM 서버 & 프롬프트 | vLLM, LoRA |
| [Data_process](https://github.com/Hi-dle-hancom/Data_process) | 데이터 전처리 파이프라인 | Python |

## 🎓 팀 소개

**SSAFY 11기 자율 프로젝트팀** - 한컴MDS 특화 프로젝트

## 📞 Contact

- **Organization**: Hi-dle-hancom
- **Project Period**: 2024.07 - 2024.08

---

<div align="center">

**⭐ 프로젝트가 도움이 되셨다면 Star를 눌러주세요!**

</div>
