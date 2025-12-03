# 🎯 HAPA (Hancom AI Python Assistant)

> **한컴 AI 아카데미 1기 - Team 하이들(Hi-dle)**  
> AI 기반 Python 코딩 어시스턴트 프로젝트

## 📌 프로젝트 소개

**HAPA(하이들)**는 Python 개발자를 위한 **AI 기반 통합 코딩 어시스턴트**입니다.  
각자 걸어는 것은 같지만 각자의 것이 필요할 때 - 개발 프로세스 전반을 지원합니다.

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

### 👥 팀 소개

**한컴 AI 아카데미 1기 - Team HAPA**

| 팀장/원 | 이름 | 역할 | 담당 업무 |
|---------|------|------|----------|
| 팀장 | 김성윤 | 프로젝트 개발 총괄 | - LLM 모델 파인튜닝 (메인 담당)<br>- LLM 모델 서빙 및 관련 서버 관리<br>- 전체 기술 방향성 제시 및 리드<br>- email: seongyungim428@gmail.com |
| 팀원 | 이도선 | PM 및 백엔드 개발 | - 백엔드 API 서버 개발 (FastAPI 기반 구축)<br>- 프론트엔드 개발 (Extension)<br>- email: doseon1226@gmail.com |
| 팀원 | 김건희 | 개발 리드 | - LLM 모델 파인튜닝<br>- DevOps (배포 자동화, 인프라 관리)<br>- 데이터 크롤링<br>- DB<br>- 백엔드 서버 구축<br>- email: k1212gh@gmail.com |
| 팀원 | 전송이 | 데이터 엔지니어링 | - 데이터 전처리 및 가공 알고리즘 설계 (메인 담당)<br>- 데이터 검증 및 분석<br>- 발표 자료 준비<br>- email: songyi.9801@daum.net |
| 팀원 | 전윤재 | 데이터 및 프론트엔드 개발 | - 데이터 전처리 및 가공 구현<br>- 프론트엔드 개발 (Web UI 구현, 후반 작업 지원)<br>- email: gyuhyeonjeon4@gmail.com |
| 팀원 | 민성원 | 데이터 수집 및 프론트엔드 개발 | - 데이터 크롤링<br>- email: m3238190@naver.com (github) |

## 📞 Contact

- **Organization**: Hi-dle-hancom
- **Project**: 한컴 AI 아카데미 1기
- **Project Period**: 2025.12.01 - 2025.07.31
<div align="center">

**⭐ 프로젝트가 도움이 되셨다면 Star를 눌러주세요!**

</div>
