# 안녕하세요, 웹 애플리케이션 개발자 임세은입니다 👋

프론트엔드와 백엔드를 함께 이해하며,  
사용자에게 실제로 필요한 웹 서비스를 만드는 개발자입니다.

## Main Projects

### 🐥 DuckTack

AI 기반 주거 하자 진단 및 전문가 연계 서비스

- **개발 기간:** 2026.01 ~ 진행 중
- **담당 역할:** 팀장, 백엔드 및 관리자·제휴업체 웹 개발
- **주요 구현:** AI 하자 진단, 전문가 예약·수리 상태 관리, 업체 승인, 리뷰 관리, PDF 진단 리포트 생성
- **기술 스택:** `Spring Boot` `React` `React Native` `Flask` `PostgreSQL` `Docker` `YOLOv8` `SAM`
- **Repository:** [DDuckTTack/DuckTack](https://github.com/DDuckTTack/DuckTack)

---

### 🤖 경기대학교 Multi-LLM Workspace

학생과 관리자가 여러 LLM을 안전하게 이용하고 사용량과 비용을 관리할 수 있는 연구·학습용 AI 플랫폼

- **주요 구현:** GPT·Gemini 선택형 스트리밍 채팅, 대화 저장·검색·요약, 문서 첨부, 웹 검색 기반 답변
- **관리 기능:** 사용자·공급자·API 키별 토큰 및 비용 한도, 사용량 정산, 학생용 OpenAI 호환 API 키 발급
- **보안·안정성:** Argon2 비밀번호, HttpOnly 세션, CSRF 검사, Redis 기반 요청 제한 및 공급자 키 순환
- **기술 스택:** `Next.js` `TypeScript` `FastAPI` `Python` `PostgreSQL` `Redis` `Docker`
- **Repository:** Private

---

### 🩺 토닥 (Todak)

환자·보호자·의료진을 연결해 증상과 복약, 건강 기록을 함께 관리하는 헬스케어 서비스

- **주요 구현:** 환자·보호자 연결, 일일 증상 평가, 건강 기록, 복약 일정·이력, 의료진용 환자 조회 및 질문 답변
- **데이터 연동:** 건강보험심사평가원 데이터를 활용한 약 4만 개 의료기관 검색과 진료과 조회
- **AI 활용:** 환자 질문에 대한 AI 답변 초안을 생성하고 의료진이 검토·수정·승인하는 흐름 구성
- **기술 스택:** `Spring Boot` `Java` `React` `React Native` `PostgreSQL` `pgvector` `Docker`
- **Repository:** Private

---

### 📈 Auto Trading Platform

실시간 시세와 보조지표를 활용한 교육용 가상투자·자동매매 플랫폼

- **담당 역할:** 초보자 자동매매 및 가상계좌의 종목·시세 데이터 파이프라인 개선
- **주요 구현:** 금융위원회 API 기반 코스피·코스닥 종목 조회, 한국투자 과거 분봉 재생, Redis 토큰·캐시 관리
- **문제 해결:** 가상투자 기능의 키움 API 의존성을 제거하고, API 장애 시 Redis 캐시와 기본 종목으로 전환되는 구조 구성
- **검증:** 코스피·코스닥 2,771개 종목 조회, 백엔드 테스트 139개 및 Python 린트 통과
- **기술 스택:** `Spring Boot` `FastAPI` `React` `PostgreSQL` `Redis` `Kafka` `Docker`
- **Repository:** [trading-platform-team/auto-trading-platform](https://github.com/trading-platform-team/auto-trading-platform)

---

### 🎪 Festory

대학 축제의 공지와 주점·부스 홍보, 예약, QR 주문 및 현장 운영을 연결한 축제 통합 플랫폼

- **담당 역할:** 예약과 역할별 운영 흐름을 중심으로 프론트엔드 화면 및 사용성 개선
- **주요 구현:** 사용자·주점 운영자·총학생회·관리자 대시보드, 운영 타이머, 권한별 화면 이동
- **운영 흐름:** 주점 탐색 → 예약 → 대기·호출 → 테이블 배정 → QR 주문 → 조리·서빙 → 정산
- **협업:** Git 브랜치와 Pull Request 기반 기능 통합, 웹 빌드 및 Android 실기기 검증
- **기술 스택:** `React` `Spring Boot` `PostgreSQL` `Docker` `Flyway` `Android`
- **Repository:** Private

---

### 💬 여운 (YEOUN)

카카오톡 대화 기록에서 특정 인물의 말투와 표현을 분석해 AI 대화를 제공하는 감성 메신저 MVP

- **주요 구현:** 카카오톡 TXT 인코딩별 파싱, 발신자 선택, 표현 분석, 과거 기록 검색 기반 AI 응답
- **계정 기능:** 이메일·JWT 인증 및 카카오·Google·NAVER OAuth 로그인
- **데이터 보호:** 원본 TXT를 저장하지 않고 메모리에서 처리 후 폐기하며, 계정·인물 데이터 삭제 기능 제공
- **기술 스택:** `FastAPI` `Python` `JavaScript` `PostgreSQL` `JWT` `OAuth 2.0` `Nginx` `Docker`
- **Repository:** Private

> 비공개 프로젝트의 상세 코드와 구현 자료는 보안 및 협업 규정을 준수하는 범위에서 면접 시 설명할 수 있습니다.

## Tech Stack

### Frontend

`React` `Next.js` `TypeScript` `JavaScript` `React Native` `Android`

### Backend & AI

`Spring Boot` `Java` `FastAPI` `Python` `Flask` `OpenAI API` `Gemini API`

### Database & Infra

`PostgreSQL` `Redis` `Kafka` `Docker` `Nginx` `Flyway` `GitHub`

## Contact

- **Email:** [seeunlim29@gmail.com](mailto:seeunlim29@gmail.com)
