# WorkUp: 운영 효율을 극대화한 통합 스마트 워크플레이스

> **Role: AA (Application Architect) / Backend Lead**

## Core Capabilities

### 1️. 근태 & 통합 업무 관리
* **카카오 QR 인증**: 2차 인증 기반 무결성 출입 통제 및 실시간 상태 제어 시스템 구축
* **PMS 로직 설계**: 업무 계층 구조화 및 상태별(진행/지연) 동적 UI 구현을 통한 업무 가시성 확보

### 2️. 데이터 자동화 & 지능형 분석
* **행정 자동화**: PL/SQL 프로시저 및 계층형 쿼리 기반 인사 통계 자동화로 운영 리소스 절감
* **AI 근태 비서**: RAG(검색 증강 생성) 기반 실시간 데이터 분석 및 자연어 응답 서비스 구현

### 3️3. 인프라 모니터링 & 시각화
* **AOP 로그 추적**: 비침습적 전역 로그 수집 및 시각화로 시스템 안정성 및 유지보수성 확보
* **실시간 시각화**: D3.js 활용 서버 가동률 및 트래픽 데이터 가시화 (Real-time Monitoring)

---
##  Tech Stack & Libraries

###  Backend & Infrastructure
* **Framework**: Spring Boot, Spring Security, Spring AOP (비침습적 로그 추적 및 보안 제어)
* **Database**: Oracle Database (계층형 쿼리 및 PL/SQL 프로시저 최적화)
* **Scheduling**: Oracle DBMS_SCHEDULER (근태 데이터 자동 보정 및 배치 자동화)
* **API & Auth**: Kakao Login API (OAuth 2.0 기반 QR 인증 및 간편 로그인 연동)

###  Frontend & UI/UX
* **Core**: React (v18), JavaScript (컴포넌트 기반 UI 설계 및 고속 빌드)
* **State Management**: TanStack Query (React Query) (비동기 통신 최적화 및 실시간 데이터 캐싱)
* **Visualization**: D3.js (전사 통계 시각화 및 인터랙티브 대시보드 구현)
* **UI Library**: MUI (Material UI) (일관된 관리자 페이지 인터페이스 구축)
* **Communication**: Axios, WebSocket (실시간 상태 동기화 및 서버 데이터 통신)

###  DevOps & VCS
* **VCS**: Git/GitHub, TortoiseSVN (팀 내 형상 관리 및 버전 통합)
* **IDE**: IntelliJ IDEA, VS Code
