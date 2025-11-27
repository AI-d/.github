<div align="center">
  <img src="./Dialogym_logo_symbol_bg_removal.png" alt="Dialogym Logo" width="200"/>

  # Dialogym

  ### AI 기반 대화 훈련 플랫폼

  **Dialogym - 대화도 훈련이 필요하다**

  AI와 함께하는 실시간 음성 대화 훈련 플랫폼
  헬스장에서 근육을 단련하듯, 대화 능력을 체계적으로 훈련합니다.

  **TEAM AId**

  [![Frontend](https://img.shields.io/badge/Frontend-dialogym.shop-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://dialogym.shop)
  [![API](https://img.shields.io/badge/API-api.dialogym.shop-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://api.dialogym.shop)
  [![Docs](https://img.shields.io/badge/API_Docs-Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)](https://api.dialogym.shop/swagger-ui.html)

</div>

---

## 목차

- [프로젝트 정보](#프로젝트-정보)
- [Getting Started](#getting-started)
- [프로젝트 비전](#프로젝트-비전)
- [주요 기능](#주요-기능)
- [사용자 시나리오](#사용자-시나리오)
- [팀 구성](#팀-구성)
- [개발 기간](#개발-기간)
- [기술 스택](#기술-스택)
- [시스템 아키텍처](#시스템-아키텍처)
- [대표 문서](#대표-문서)
- [향후 업데이트 계획](#향후-업데이트-계획)
- [라이선스 및 문의](#라이선스-및-문의)

---

## 프로젝트 정보

| 항목           | 내용                                                                       |
| ------------ | ------------------------------------------------------------------------ |
| **팀명**       | **AId (에이드)** — *AI + Aid의 합성어. AI가 사람들의 대화 성장을 돕는다는 철학* |
| **프로젝트명**    | **trAIn (트레인)** — *Train + AI. AI와 함께하는 커뮤니케이션 능력 향상 여정*         |
| **플랫폼명**     | **Dialogym (다이얼로짐)** — *Dialogue + Gym. 대화 근육을 단련하는 훈련 공간*    |
| **버전**       | v1.0.0 (MVP)                                                                   |
| **개발 기간** | 2025.09.29 ~ 2025.11.03 (5주)                                                 |
| **프로덕션 URL** | **Frontend**: https://dialogym.shop<br>**Backend API**: https://api.dialogym.shop |
| **로컬 개발 URL** | **Frontend**: http://localhost:5050<br>**Backend**: http://localhost:9090 |

---

## Getting Started

### 백엔드 실행

```bash
cd trAIn-backend
./gradlew bootRun
# http://localhost:9090
```

### 프론트엔드 실행

```bash
cd trAIn-frontend
npm install
npm run dev
# http://localhost:5050
```

### 문서

- [백엔드 README](https://github.com/AI-d/trAIn-backend/blob/dev/README.md)
- [프론트엔드 README](https://github.com/AI-d/trAIn-frontend/blob/dev/README.md)
- [프로젝트 문서](https://github.com/AI-d/Dialogym-docs/blob/dev/README.md)

---

## 프로젝트 비전

Dialogym은 "대화도 훈련이 필요하다"는 철학을 기반으로, 현대인의 커뮤니케이션 불안을 해결하고 누구나 자신 있게 말할 수 있는 세상을 만듭니다.

### Dialogym이 해결하는 문제

**현대 사회의 커뮤니케이션 위기:**

- **콜 포비아 (Call Phobia)**: 전화 통화에 대한 두려움과 불안, 실시간 음성 소통 능력 약화
- **세대 간 소통 단절**: MZ세대와 아동 세대의 언어 예절 약화, 존댓말·전화 대화 형식 미숙
- **비대면 문화의 부작용**: 코로나19 이후 대면 소통 경험 부족, 대인관계 형성 어려움
- **교육 공백**: 학교나 직장에서 실제적 대화 기술 교육 부재

**구체적 문제 상황:**

- **직장**: 상사 보고 한 문장에 따라 신뢰도 변화, 고객 연락에서의 적절한 표현 고민
- **취업**: 면접 답변의 말투에 따라 합격 여부 결정, 압박 질문 대응 능력 부족
- **가족**: 부모-자녀 간 소통 방식 차이, 학부모-선생님 간 적절한 표현 고민
- **개인**: 연인·친구와의 관계에서 "뭐라고 답장해야 하지?" 고민

### Dialogym의 철학

**"대화는 근육과 같다"**

- 헬스장에서 근육을 단련하듯, 대화 능력도 훈련을 통해 강화됩니다
- 반복적 연습으로 자연스러운 습관을 형성합니다
- 안전한 환경에서 실수를 통해 배우고 성장합니다

**AI의 3가지 역할:**

1. **Mirror (거울)**: 사용자의 표현을 반영하고 개선점을 명확하게 보여줌
2. **Coach (코치)**: 단순 교정이 아닌 성장을 돕는 맞춤형 피드백 제공
3. **Training Partner (훈련 파트너)**: 실제와 유사한 대화 상대로 역할 수행

### 플랫폼 차별성

| 구분         | 기존 챗봇/AI 서비스      | **Dialogym**                        |
| ---------- | --------------- | -------------------------------- |
| **대화 방식**  | 텍스트 대화만 가능 | **실시간 음성 대화** (GPT-4o Realtime API)         |
| **훈련 구조**  | 일회성 답변 제공   | **작성 → 피드백 → 수정 → 개선** 루프          |
| **피드백** | 일반적 개선안만 제시     | **점수화 + 3가지 개선안** (간결/공손/따뜻)      |
| **상황 맥락**  | 범용 AI, 매번 설명 필요    | **6가지 시나리오** 특화 (상사 보고, 면접 등) |
| **성장 추적** | 기록 없음       | **히스토리 저장 + 성장 리포트**    |

> Dialogym은 단순한 답변 제공을 넘어, **실전과 유사한 환경에서 체계적으로 대화 능력을 향상**시킵니다.

---

## 주요 기능

### 1. 회원 관리
- 이메일/비밀번호 회원가입 및 로그인
- 소셜 로그인 (Google, Kakao, Naver)
- 이메일 인증 (인증 토큰 발급 및 검증)
- JWT 토큰 관리 (Access Token + Refresh Token)
- Refresh Token Rotation (RTR) 보안 적용
- 프로필 조회 및 수정
- 비밀번호 변경 (로컬 계정 전용)

### 2. 시나리오 관리
- 6가지 기본 시나리오 제공
  1. 상사에게 휴가 요청하기 (직장)
  2. 부모님께 여행 요청하기 (가족)
  3. 친구에게 모임 제안하기 (친구)
  4. 식당 예약 요청하기 (일상)
  5. 동료에게 프로젝트 협조 요청하기 (직장)
  6. 연인에게 중요한 대화 요청하기 (연애)
- 시나리오 목록 조회 (전체/기본/사용자 생성)
- 커스텀 시나리오 생성 기능
- 사용자별 시나리오 관리 (생성/조회/삭제)

### 3. 실시간 음성 대화
- GPT-4o Realtime API 기반 실시간 음성 대화
- WebRTC P2P 연결을 통한 저지연 음성 통신
- Ephemeral Key 발급 (시나리오 프롬프트 포함)
- 상황별 역할극 (AI가 상사, 면접관, 부모 등 역할 수행)
- 실시간 음성-텍스트 변환 (STT)

### 4. AI 피드백
- 실시간 음성 분석
  - 발화 속도 (WPM - Words Per Minute)
  - 추임새 감지 ("음", "어", "그", "저기" 등)
- 점수화된 객관적 피드백
  - 공손도 (1~10)
  - 명료성 (1~10)
  - 종합 점수 (0~100)
- 3가지 개선안 제시
  - 간결하게
  - 정중하게
  - 따뜻하게

### 5. 히스토리 관리
- 대화 히스토리 저장
- 피드백 히스토리 조회 (페이징 지원)
- 성장 통계 (점수 변화 추이, 평균 점수, 등급 분포)

---

## 사용자 시나리오

### 1. 직장인 - 상사에게 휴가 요청

**상황:** 김대리는 팀장님께 휴가를 요청해야 합니다. 정중하면서도 명확하게 요청하고 싶지만, 말이 꼬이거나 추임새가 많아서 신뢰도가 떨어질까 걱정됩니다.

**Dialogym 사용:**
1. "상사에게 휴가 요청하기" 시나리오 선택
2. AI 팀장과 실전 대화 연습 (휴가 기간, 사유, 인수인계 계획 설명)
3. 실시간 피드백 (추임새, 발화 속도)
4. 대화 종료 후 상세 분석 확인
5. 개선안 3가지 (간결/공손/따뜻) 비교
6. 다시 연습하며 개선

**결과:** 자신감 있게 요청 완료, 팀장의 휴가 승인 획득

### 2. 대학생 - 부모님께 여행 요청

**상황:** 박학생은 방학에 친구들과 여행을 가고 싶어합니다. 부모님께 설득력 있게 요청하고 싶지만, 어떻게 말해야 허락받을 수 있을지 고민됩니다.

**Dialogym 사용:**
1. "부모님께 여행 요청하기" 시나리오 선택
2. AI 부모님과 실전 대화 연습 (여행 계획, 안전, 비용 설명)
3. 예상 질문에 대응 연습
4. 설득력, 명료성 피드백
5. 반복 훈련으로 자신감 향상

**결과:** 부모님 설득 성공, 여행 허락 획득

### 3. 직장인 - 동료에게 협조 요청

**상황:** 이대리는 프로젝트 마감이 다가오는데 혼자서는 어려워 동료에게 협조를 요청해야 합니다. 부담스럽지 않으면서도 명확하게 요청하고 싶습니다.

**Dialogym 사용:**
1. "동료에게 프로젝트 협조 요청하기" 시나리오 선택
2. AI 동료와 실전 대화 연습 (요청 범위, 마감일, 업무 분담 설명)
3. 협조 요청 톤 연습
4. 공손도, 명료성 피드백
5. 3가지 버전 비교 (간결/공손/따뜻)

**결과:** 동료의 흔쾌한 협조 약속, 프로젝트 성공적 완료

### 4. 일상 - 식당 예약 요청

**상황:** 최씨는 중요한 모임을 위해 식당에 예약을 해야 합니다. 전화 통화가 두렵고, 예약 정보를 명확하게 전달할 수 있을지 걱정됩니다.

**Dialogym 사용:**
1. "식당 예약 요청하기" 시나리오 선택
2. AI 식당 직원과 실전 대화 연습 (날짜, 시간, 인원, 특이사항 전달)
3. 명확한 정보 전달 연습
4. 발화 속도, 명료성 피드백
5. 반복 훈련으로 전화 공포증 극복

**결과:** 성공적인 예약 완료, 전화 통화 자신감 향상

---

## 팀 구성

| 역할 | 이름 | GitHub | 주요 담당 기능 |
| -- | -- | ------ | ------------- |
| **PO / Tech Lead / PM** | **왕택준** | [@TJK98](https://github.com/TJK98) | **Backend (인증/보안/AI)**: Spring Security + JWT 인증 시스템, OAuth2 소셜 로그인 (Google/Kakao/Naver), Refresh Token Rotation (RTR), Rate Limiting (Bucket4j), 이메일 인증 (JWT+OTP 이중 검증), 약관 관리, Spring AI + GPT-4 기반 AI 피드백 생성 (전체 대화 평가 + 문장별 분석 + 3가지 스타일 개선안), 피드백 히스토리 및 성장 통계, 데이터 정리 스케줄러<br>**Frontend (인증/피드백)**: 웰컴 페이지, 회원가입/로그인, 이메일 인증, 소셜 로그인 콜백, 피드백 결과 화면, 마이 페이지, Zustand 상태 관리, Axios Interceptor (토큰 갱신 자동화)<br>**Docs & PM**: 100개 이상의 문서 작성 (요구사항/설계/의사결정/팀/프로세스/회의/트러블슈팅), Git 브랜치 전략, PR 템플릿, 코딩 컨벤션, Jira 이슈 관리, 주 2회 정기 회의 주도 |
| **공동 SM / Fullstack** | **김경민** | [@minee0505](https://github.com/minee0505) | **Backend (실시간 통신/세션)**: WebSocket 실시간 통신 (Signaling/Audio/Feedback Handler), DialogueSession 생성 및 상태 관리, 세션 동시성 제어, Transcript 엔티티 및 STT 데이터 DB 저장, 대화 히스토리 관리, Ephemeral Key 발급 API<br>**Frontend (시나리오)**: 시나리오 선택 화면 (ScenarioListPage), 커스텀 시나리오 생성 화면 (CreateScenarioPage), scenarioStore 상태 관리<br>**Infra & DevOps**: AWS 배포 아키텍처 설계 및 구축 (EC2/S3/CloudFront/RDS/Route 53), Docker + Docker Compose 컨테이너화, Nginx 리버스 프록시 및 SSL 종료, Let's Encrypt 인증서 자동 갱신, GitHub Actions CI/CD 파이프라인 구축 (Backend/Frontend 자동 배포) |
| **공동 SM / Fullstack** | **진도희** | [@dohee-jin](https://github.com/dohee-jin) | **Backend (시나리오/분석)**: 시나리오 CRUD API (생성/조회/삭제), 6개 기본 시나리오 초기화, Ephemeral Key 발급 컨트롤러, WebSocket 핸들러 (실시간 메시지 처리), 실시간 음성 분석 (발화 속도 WPM 계산, 추임새 감지 알고리즘)<br>**Frontend (대화/WebRTC)**: AI 대화 화면 (DialoguePage), 시나리오 선택/생성 화면, GPT-4o Realtime API WebRTC P2P 연결 (useRealtimeSession 훅), getUserMedia 마이크 권한, 음성 데이터 전송 제어, 실시간 STT 데이터 WebSocket 전송, VAD (Voice Activity Detection), 실시간 피드백 UI, audio-processor.js 음성 처리, sessionStore 상태 관리<br>**Docs**: 회의록 작성 및 관리 |

### 팀 특징

**3인 풀스택 팀 - End-to-End 개발**
- 모든 팀원이 Backend와 Frontend를 함께 담당하여 기능별 완전한 구현
- 왕택준: 인증/보안 시스템 + AI 피드백 + 프로젝트 관리 + 문서화
- 김경민: 실시간 통신 + 세션 관리 + 인프라/DevOps
- 진도희: 시나리오 관리 + WebRTC 음성 통신 + 실시간 분석

**체계적인 협업 문화**
- 애자일 방식: 5주 5개 스프린트, 주 2회 정기 회의 (총 18회)
- 문서화: 105개 마크다운 문서로 모든 의사결정 과정 기록
- 코드 리뷰: PR 100개 이상 리뷰, 최소 1명 승인 필수
- 이슈 관리: Jira Epic-Story-Task 구조화, 50개 이상 Task 추적
- Git Flow: main(배포) - dev(통합) - feature(기능) 브랜치 전략

**협업 도구**
- Discord (실시간 커뮤니케이션), Jira (이슈 추적), GitHub (코드 리뷰)
- Swagger (API 자동 문서화), GitHub Docs Repo(105여 개의 기술 문서)

> 팀 구성 및 역할 상세 정보: [Team Roles 문서](https://github.com/AI-d/Dialogym-docs/blob/dev/docs/team/team-roles.md)

---

## 개발 기간

**2025.09.29 ~ 2025.11.03 (5주)**

| **Sprint**                          | **기간**         | **주요 내용**                               |
| ---------------------------------- | -------------- | --------------------------------------- |
| **Sprint 1. Planning**              | 09.29 ~ 10.06 | 프로젝트 기반 구축, 협업 도구 설정, 문서 체계 구축, 아키텍처 설계 |
| **Sprint 2. DB & Infra**           | 10.06 ~ 10.13 | ERD 설계, JWT 인증, OAuth2 소셜 로그인, Docker 설정 |
| **Sprint 3. Backend & React**        | 10.13 ~ 10.20 | 백엔드 API 완료, GPT-4o Realtime API 연동, React 프로젝트 시작 |
| **Sprint 4. UI/UX & Integration** | 10.20 ~ 10.27 | 피드백 생성 (GPT-4), WebSocket 통신, React UI 완성 |
| **Sprint 5. Frontend & Deploy** | 11.03 ~ 11.10 | React 개발 (웰컴, 회원가입, 로그인, 시나리오 선택, AI 대화, 피드백, 마이 페이지), **배포 (AWS EC2 + S3 + CloudFront)**, 발표 준비 |

---

## 기술 스택

### 프론트엔드

| 구분 | 기술 |
|------|------|
| **언어** | ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black) |
| **프레임워크** | ![React](https://img.shields.io/badge/React-19.1.1-61DAFB?logo=react&logoColor=black) |
| **빌드 도구** | ![Vite](https://img.shields.io/badge/Vite-7.1.11-646CFF?logo=vite&logoColor=white) |
| **라우팅** | ![React Router](https://img.shields.io/badge/React%20Router-7.9.4-CA4245?logo=reactrouter&logoColor=white) |
| **상태 관리** | ![Zustand](https://img.shields.io/badge/Zustand-5.0.8-000000?logo=react&logoColor=white) ![Immer](https://img.shields.io/badge/Immer-10.2.0-00E7C3) |
| **스타일링** | ![SASS](https://img.shields.io/badge/SASS-1.92.1-CC6699?logo=sass&logoColor=white) ![SCSS Modules](https://img.shields.io/badge/SCSS%20Modules-CC6699?logo=sass&logoColor=white) |
| **UI 라이브러리** | ![Ant Design](https://img.shields.io/badge/Ant%20Design-5.27.4-0170FE?logo=antdesign&logoColor=white) |
| **통신** | ![Axios](https://img.shields.io/badge/Axios-1.12.2-5A29E4?logo=axios&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-010101?logo=socketdotio&logoColor=white) |
| **음성** | ![WebRTC](https://img.shields.io/badge/WebRTC-333333?logo=webrtc&logoColor=white) |
| **AI** | ![OpenAI](https://img.shields.io/badge/OpenAI-4.104.0-412991?logo=openai&logoColor=white) |

### 백엔드

| 구분 | 기술 |
|------|------|
| **언어** | ![Java](https://img.shields.io/badge/Java-17-007396?logo=openjdk&logoColor=white) |
| **프레임워크** | ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.5-6DB33F?logo=springboot&logoColor=white) |
| **ORM** | ![JPA](https://img.shields.io/badge/JPA/Hibernate-59666C?logo=hibernate&logoColor=white) |
| **쿼리** | ![QueryDSL](https://img.shields.io/badge/QueryDSL-5.0.0-0078D4) |
| **데이터베이스** | ![MariaDB](https://img.shields.io/badge/MariaDB-10.x-003545?logo=mariadb&logoColor=white) |
| **캐시** | ![Caffeine](https://img.shields.io/badge/Caffeine-3.1.8-00897B) |
| **인증** | ![JWT](https://img.shields.io/badge/JWT-0.12.3-000000?logo=jsonwebtokens&logoColor=white) |
| **보안** | ![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?logo=springsecurity&logoColor=white) ![OAuth2](https://img.shields.io/badge/OAuth2-EB5424?logo=auth0&logoColor=white) |
| **Rate Limiting** | ![Bucket4j](https://img.shields.io/badge/Bucket4j-8.10.1-FF6B6B) |
| **빌드 도구** | ![Gradle](https://img.shields.io/badge/Gradle-8.x-02303A?logo=gradle&logoColor=white) |

### AI 및 음성 처리

| 구분 | 기술 |
|------|------|
| **음성 대화** | ![GPT-4o](https://img.shields.io/badge/GPT--4o%20Realtime%20API-412991?logo=openai&logoColor=white) |
| **텍스트 분석** | ![GPT-4](https://img.shields.io/badge/GPT--4%20API-412991?logo=openai&logoColor=white) |
| **AI 통합** | ![Spring AI](https://img.shields.io/badge/Spring%20AI-1.0.0--M4-6DB33F?logo=spring&logoColor=white) |
| **음성 활동 감지** | ![VAD](https://img.shields.io/badge/VAD--React-0.0.34-FF6B6B) |

### 인프라 및 배포

| 구분 | 기술 |
|------|------|
| **클라우드** | ![AWS](https://img.shields.io/badge/AWS-EC2%20%7C%20S3%20%7C%20CloudFront%20%7C%20RDS-232F3E?logo=amazonwebservices&logoColor=white) |
| **컨테이너** | ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?logo=docker&logoColor=white) |
| **CI/CD** | ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white) |
| **웹 서버** | ![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white) |
| **도메인** | ![Route 53](https://img.shields.io/badge/Route%2053-8C4FFF?logo=amazonroute53&logoColor=white) |
| **SSL/TLS** | ![Let's Encrypt](https://img.shields.io/badge/Let's%20Encrypt-003A70?logo=letsencrypt&logoColor=white) |

### 협업 도구

| 구분 | 기술 |
|------|------|
| **버전 관리** | ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white) |
| **이슈 관리** | ![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white) |
| **커뮤니케이션** | ![Discord](https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white) |
| **개발 환경** | ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?logo=intellijidea&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white) |

### 개발 도구

| 구분 | 기술 |
|------|------|
| **API 문서** | ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?logo=swagger&logoColor=black) ![SpringDoc](https://img.shields.io/badge/SpringDoc%20OpenAPI-2.8.13-6DB33F) |
| **API 테스트** | ![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white) |
| **테스트** | ![JUnit5](https://img.shields.io/badge/JUnit5-25A162?logo=junit5&logoColor=white) ![Mockito](https://img.shields.io/badge/Mockito-000000) ![Vitest](https://img.shields.io/badge/Vitest-4.0.3-6E9F18?logo=vitest&logoColor=white) |
| **E2E 테스트** | ![Playwright](https://img.shields.io/badge/Playwright-1.56.1-2EAD33?logo=playwright&logoColor=white) |
| **컴포넌트 개발** | ![Storybook](https://img.shields.io/badge/Storybook-9.1.15-FF4785?logo=storybook&logoColor=white) |
| **린팅** | ![ESLint](https://img.shields.io/badge/ESLint-9.33.0-4B32C3?logo=eslint&logoColor=white) |
| **코드 품질** | ![Lombok](https://img.shields.io/badge/Lombok-BC4521?logo=lombok&logoColor=white) ![p6spy](https://img.shields.io/badge/p6spy-1.9.1-4479A1) |

---

## 시스템 아키텍처

### 전체 구조 (프로덕션 환경)

```
[사용자]
   ↓ (HTTPS)
[CloudFront CDN]
   ↓
[S3 Static Hosting] ← React Frontend (SPA)
   ↓ (HTTPS REST API + WebSocket)
[Route 53 DNS]
   ↓
[EC2 Instance]
   ├─ [Nginx] (리버스 프록시, SSL 종료)
   │   ↓
   ├─ [Docker Container]
   │   └─ [Spring Boot Backend]
   │       │
   │       ├─ [인증/인가 계층]
   │       │   ├─ User (사용자 관리)
   │       │   ├─ Verification (이메일 인증)
   │       │   ├─ Terms (약관 관리)
   │       │   ├─ JWT 토큰 관리 (Access + Refresh)
   │       │   ├─ OAuth2 소셜 로그인 (Google, Kakao, Naver)
   │       │   └─ Spring Security + Filter Chain
   │       │
   │       ├─ [대화 계층]
   │       │   ├─ Scenario (시나리오 관리)
   │       │   ├─ Session (대화 세션 관리)
   │       │   └─ WebSocket Handler (실시간 통신)
   │       │
   │       ├─ [피드백 계층]
   │       │   └─ Feedback (피드백 생성 및 관리)
   │       │
   │       ├─ [외부 API 연동]
   │       │   ├─ GPT-4o Realtime API (실시간 음성 대화)
   │       │   └─ GPT-4 API (피드백 생성 및 점수 계산)
   │       │
   │       └─ [데이터 계층]
   │           ├─ MariaDB (영구 데이터 저장)
   │           └─ Caffeine Cache (세션 캐시)
   │
   └─ [RDS MariaDB] (관리형 데이터베이스)
```

### CI/CD 파이프라인

```
[개발자]
   ↓ git push (dev 브랜치)
[GitHub Repository]
   ↓ 트리거
[GitHub Actions]
   │
   ├─ [Backend Pipeline]
   │   ├─ 1. Checkout code
   │   ├─ 2. Setup JDK 17
   │   ├─ 3. Gradle build (bootJar)
   │   ├─ 4. SSH to EC2
   │   ├─ 5. Copy JAR + Docker files
   │   ├─ 6. Docker Compose down/up
   │   └─ 7. Health check
   │
   └─ [Frontend Pipeline]
       ├─ 1. Checkout code
       ├─ 2. Setup Node.js 22
       ├─ 3. npm ci (의존성 설치)
       ├─ 4. npm run build (Vite)
       ├─ 5. AWS S3 sync (파일 업로드)
       └─ 6. CloudFront invalidation (캐시 무효화)
```

### 핵심 기능별 아키텍처

#### 1. 인증/인가 흐름

```
[회원가입]
사용자 → POST /api/v1/users/signup
   ↓
Backend: 비밀번호 암호화 (BCrypt)
   ↓
Backend: 이메일 인증 토큰 생성
   ↓
Backend: User 저장 (DB)
   ↓
Frontend: 이메일 인증 안내

[로그인]
사용자 → POST /api/v1/users/login
   ↓
Backend: 자격 증명 검증 (Spring Security)
   ↓
Backend: JWT 토큰 생성 (Access + Refresh)
   ↓
Backend: Refresh Token → HttpOnly Cookie
   ↓
Frontend: Access Token 저장 (메모리)

[소셜 로그인]
사용자 → OAuth2 Provider (Google/Kakao/Naver)
   ↓
Backend: OAuth2 인증 처리
   ↓
Backend: 일회용 코드 생성
   ↓
Frontend: POST /api/v1/users/token/exchange
   ↓
Backend: JWT 토큰 발급
```

#### 2. 시나리오 선택 흐름

```
사용자: 시나리오 목록 조회
   ↓
Frontend: GET /api/v1/scenarios (또는 /default)
   ↓
Backend: 시나리오 목록 반환 (기본 6개 + 사용자 생성)
   ↓
사용자: 시나리오 선택
   ↓
Frontend: 선택한 시나리오 정보 저장
```

#### 3. 대화 세션 시작 흐름

```
사용자: "대화 시작" 버튼 클릭
   ↓
Frontend: POST /api/v1/sessions
   - userId
   - scenarioId
   ↓
Backend: DialogueSession 생성 및 저장 (DB)
   ↓
Backend: sessionId 반환
   ↓
Frontend: POST /api/v1/realtime/session
   - sessionId
   - model, voice, sttModel, language
   ↓
Backend: 시나리오 프롬프트 생성
   ↓
Backend: OpenAI Ephemeral Key 발급
   ↓
Frontend: WebRTC P2P 연결 시작
   ↓
Frontend: GPT-4o Realtime API와 음성 스트리밍 시작
```

#### 4. 실시간 대화 흐름

```
[음성 통신]
사용자 음성 (마이크)
   ↓ WebRTC (P2P)
Frontend
   ↓ WebSocket
GPT-4o Realtime API
   ↓ Audio Response
Frontend
   ↓ WebRTC (P2P)
사용자 (스피커)

[실시간 분석]
GPT-4o Realtime API
   ↓ Transcript (실시간 텍스트 변환)
Backend (WebSocket Handler)
   ↓ 음성 분석
   - 발화 속도 계산 (WPM)
   - 추임새 감지 ("음", "어", "그" 등)
   ↓ WebSocket
Frontend (실시간 피드백 표시)
```

#### 5. 대화 종료 및 피드백 생성 흐름

```
사용자: "대화 종료" 버튼 클릭
   ↓
Frontend: PUT /api/v1/sessions/{sessionId}/complete
   ↓
Backend: DialogueSession 상태 업데이트 (COMPLETED)
   ↓
Frontend: POST /api/v1/feedbacks/sessions/{sessionId}
   ↓
Backend: 세션 데이터 조회
   - transcript (대화 전체 내용)
   - wpm (발화 속도)
   - fillerCount (추임새 횟수)
   ↓
Backend: GPT-4 API 호출 (Spring AI)
   - 프롬프트: 대화 분석 요청
   - 응답: 공손도 (1~10), 명료성 (1~10)
   ↓
Backend: 종합 점수 계산
   - 발화 속도 (30점)
   - 추임새 (20점)
   - 공손도 (25점)
   - 명료성 (25점)
   - 총점 (0~100)
   ↓
Backend: 개선안 3가지 생성 (GPT-4)
   - Alternative A: 간결하게
   - Alternative B: 정중하게
   - Alternative C: 따뜻하게
   ↓
Backend: Feedback 저장 (DB)
   ↓
Frontend: 피드백 화면 표시
   - 점수 시각화
   - 개선안 선택 UI
```

---

## 배포 및 인프라

### 프로덕션 환경

**서비스 URL:**
- **메인**: https://dialogym.shop
- **대체**: https://www.dialogym.shop
- **API**: https://api.dialogym.shop

### 인프라 구성

#### Frontend (정적 웹사이트)
- **호스팅**: AWS S3 (정적 웹사이트 호스팅)
- **CDN**: AWS CloudFront (전 세계 엣지 로케이션)
- **도메인**: Route 53 (DNS 관리)
- **SSL/TLS**: AWS Certificate Manager (무료 인증서)
- **배포**: GitHub Actions (자동 배포)
  - 빌드: Vite (React SPA)
  - 업로드: S3 sync
  - 캐시 무효화: CloudFront invalidation

#### Backend (API 서버)
- **서버**: AWS EC2 (t3.medium)
- **컨테이너**: Docker + Docker Compose
- **웹 서버**: Nginx (리버스 프록시, SSL 종료)
- **데이터베이스**: AWS RDS MariaDB (관리형)
- **SSL/TLS**: Let's Encrypt (무료 인증서, Certbot 자동 갱신)
- **배포**: GitHub Actions (자동 배포)
  - 빌드: Gradle bootJar
  - 전송: SCP (SSH)
  - 재시작: Docker Compose

### CI/CD 워크플로우

#### Backend 배포 프로세스
1. `dev` 브랜치에 push
2. GitHub Actions 트리거
3. Gradle로 JAR 빌드 (테스트 스킵)
4. EC2로 JAR 파일 전송 (SCP)
5. Docker Compose로 컨테이너 재시작
6. 헬스체크 확인

#### Frontend 배포 프로세스
1. `dev` 브랜치에 push
2. GitHub Actions 트리거
3. npm으로 프로덕션 빌드 (Vite)
4. S3 버킷에 파일 동기화
5. CloudFront 캐시 무효화
6. 배포 완료 (즉시 반영)

### 보안

- **HTTPS 강제**: 모든 트래픽 암호화
- **CORS 설정**: 허용된 도메인만 API 접근
- **JWT 토큰**: HttpOnly 쿠키 (XSS 방지)
- **Rate Limiting**: Bucket4j (API 남용 방지)
- **환경 변수**: GitHub Secrets (민감 정보 보호)

---

## 대표 문서

### 요구사항 및 기획

- [프로젝트 개요](https://github.com/AI-d/Dialogym-docs/blob/dev/docs/requirements/project-overview.md) - Dialogym의 출발점과 목표
- [컨셉 정의서](https://github.com/AI-d/Dialogym-docs/blob/dev/docs/requirements/concept-definition.md) - 서비스 철학과 핵심 컨셉
- [문제 분석 보고서](https://github.com/AI-d/Dialogym-docs/blob/dev/docs/requirements/problem-analysis.md) - 해결하고자 하는 사회 문제
- [경쟁사 분석](https://github.com/AI-d/Dialogym-docs/blob/dev/docs/requirements/competitive-analysis.md) - 기존 서비스 대비 차별점
- [기능 명세서](https://github.com/AI-d/Dialogym-docs/blob/dev/docs/requirements/feature-specification.md) - 주요 기능 및 기술 스택

### 팀 및 협업

- [팀 역할 정의](https://github.com/AI-d/Dialogym-docs/blob/dev/docs/team/team-roles.md) - 팀원별 역할과 책임
- [팀 기술 스택](https://github.com/AI-d/Dialogym-docs/blob/dev/docs/team/team-tech-stack.md) - 팀원별 기술 담당 영역

### 설계 및 아키텍처

- [시스템 아키텍처](https://github.com/AI-d/Dialogym-docs/tree/dev/docs/design/architecture) - 전체 시스템 구조
- [데이터베이스 설계](https://github.com/AI-d/Dialogym-docs/tree/dev/docs/design/database) - ERD 및 스키마
- [API 설계](https://github.com/AI-d/Dialogym-docs/tree/dev/docs/design/api) - API 명세 및 설계

### 프로세스 및 가이드

- [문서 작성 가이드](https://github.com/AI-d/Dialogym-docs/blob/dev/docs/processes/document-template-guide.md) - 문서 표준 및 템플릿
- [협업 프로세스](https://github.com/AI-d/Dialogym-docs/tree/dev/docs/processes/collaboration) - Git 전략, 코드 리뷰 등
- [배포 가이드](https://github.com/AI-d/Dialogym-docs/tree/dev/docs/processes/deployment) - 배포 프로세스 및 체크리스트

---

## 향후 업데이트 계획

### Phase 1 (v1.1.0) — 기능 개선

- **프로필 관리**
  - 사용자 프로필 수정
  - 아바타 이미지 업로드

- **성장 통계**
  - 점수 변화 그래프
  - 주간/월간 리포트
  - 강점/약점 분석

- **시나리오 확장**
  - 추가 시나리오 (8~10개)
  - 사용자 커스텀 시나리오 생성

---

### Phase 2 (v1.2.0) — 기능 확장

- **상대방 스타일 학습**
  - 대화 상대 프로필 생성
  - 말투, 톤, 습관 반영

- **7일 대화 챌린지**
  - 연속 훈련 동기 부여
  - 배지 시스템

- **감정 톤 분석**
  - 대화 중 감정 변화 감지
  - 감정 조절 피드백

- **메시지 초안 추천**
  - 텍스트 기반 메시지 작성 지원
  - 톤 선택 (공식/친근/따뜻)

---

### Phase 3 (v2.0.0) — 차세대 확장

- **다국어 지원**
  - 영어, 중국어, 일본어 등

- **실시간 통화 중 AI 개입**
  - 실제 전화 중 실시간 코칭

- **동영상 대화**
  - 화상 통화 연습
  - 비언어적 커뮤니케이션 피드백

- **모바일 앱**
  - iOS, Android 네이티브 앱
  - 모바일 최적화 UI/UX

---

## 주요 성과

### 기술적 성과
- **실시간 음성 대화**: GPT-4o Realtime API + WebRTC P2P 연결로 저지연 음성 통신 구현
- **보안 강화**: JWT + Refresh Token Rotation (RTR) + Rate Limiting으로 3중 보안 체계 구축
- **AI 피드백**: Spring AI + GPT-4로 대화 분석 및 점수화 (발화 속도, 추임새, 공손도, 명료성)
- **확장 가능한 아키텍처**: 3-Tier 아키텍처 + 도메인 주도 설계로 유지보수성 확보
- **자동화**: GitHub Actions CI/CD + Docker로 배포 자동화

### 프로젝트 성과
- **개발 기간**: 5주 (2025.09.29 ~ 2025.11.03)
- **문서화**: 100개 이상의 문서 작성 (요구사항, 설계, 의사결정, 팀, 프로세스, 회의, 트러블슈팅)
- **API**: 25개 이상 RESTful API 엔드포인트 설계 및 구현
- **코드 품질**: JavaDoc 주석, Swagger 자동 문서화, 코드 리뷰 문화 정착
- **배포**: AWS 프로덕션 환경 구축 및 HTTPS 적용

---

## 라이선스 및 문의

Copyright (c) 2025 AId Team. All Rights Reserved.

이 프로젝트는 독점 소프트웨어입니다. 무단 사용, 복제, 수정 및 배포는 금지됩니다.

### 팀

**AId Team**
- 왕택준 ([@TJK98](https://github.com/TJK98)) - PO / Tech Lead / PM / Fullstack / Docs
- 김경민 ([@minee0505](https://github.com/minee0505)) - 공동 SM / Fullstack / Infra
- 진도희 ([@dohee-jin](https://github.com/dohee-jin)) - 공동 SM / Fullstack

### 문의

- **Email**: dialogym.official@gmail.com
- **GitHub**: [Dialogym Organization](https://github.com/AI-d)
- **Frontend**: https://dialogym.shop
- **API Docs**: https://api.dialogym.shop/swagger-ui.html

---

**작성자:** [왕택준](https://github.com/TJK98)
