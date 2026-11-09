# 임하형 (Hahyeong Lim)

안정적이면서 많은 사용자가 불편 없이 쓰는 시스템을 만들고 싶습니다.  
특히 한 번의 오류가 신뢰로 이어지는 서비스에서, 문제가 조용히 새어 나가지 않는 구조에 관심이 많습니다.

- Seoul, Korea
- hahyeong_0817@ewhain.net

<br>

## Tech

| 분야 | 스택 |
|------|------|
| **Backend** | Java, Spring Boot, JPA, Ruby on Rails, Sidekiq |
| **Database** | PostgreSQL, MySQL, MariaDB, Flyway |
| **Infra / DevOps** | Docker, GitHub Actions, NCP |
| **Monitoring** | Datadog, Sentry |
| **AI Tools** | GitHub Copilot, Claude Code |

<br>

## Experience

**링글 (Ringle) · Full-stack Developer Intern** — 2025.08 ~ 2026.01  

기업 고객사 임직원의 영어 학습 관리 어드민, 운영툴 개발 및 유지보수. 요구사항 수신부터 기획, 개발, QA까지 담당.

- 알림톡 이관 과정에서 기존 Braze 호출 150개 가까이를 찾아 교체하고, 놓친 호출은 Sentry Alert로 감지
- 운영자가 코드 수정 없이 알림톡 발송 여부를 켜고 끄는 on/off 기능 기획, 구현
- Sidekiq 스케줄러를 날짜 단위에서 시간 단위까지 확장
  - AI가 추천한 perform_at 대신, Redis 장애 시 잡 유실 위험이 적은 polling을 사수와 검증 후 유지
- 대량 가입 시 언어와 시간대를 일괄 지정하는 입력 항목을 추가해 운영자 수동 작업 제거
- 페이지마다 다르게 집계되던 출석률의 원인을 찾아 세 곳에 복제된 집계 로직 통합. 기존 동작을 검증하는 테스트 코드를 먼저 작성
- Slack 알림 연동, Datadog과 Sentry로 에러 로그 분석

<br>

## Projects

### [이모저모 (IMJM)](https://github.com/ncamp16-final-team1/IMJM) · 팀장

외국인 대상 헤어살롱 예약, 소통 플랫폼. 실시간 채팅 번역 지원. (2025.03 ~ 2025.05)

- WebSocket 채팅에 HyperCLOVA X 다국어 번역 연동. 번역 결과가 자소 분리 형태로 오던 문제는 NFC 정규화로 해결
- 번역이 실패해도 실패 상태만 기록하고 원문 메시지는 그대로 전송
- PostgreSQL 스키마 설계 참여, Flyway 마이그레이션 관리
- Docker + GitHub Actions + NCP CI/CD 구축

`Java` `Spring Boot` `JPA` `WebSocket` `HyperCLOVA X` `PostgreSQL`

### [이직그램 (Izikgram)](https://github.com/ncamp16-team3/ncamp16-team3) · 팀장

대화형 이직 상담, 채용공고 추천 서비스. (2025.02 ~ 2025.03)

- 사람인 API로 사용자 조건에 맞는 공고를 가져와 챗봇 대화 흐름에 연결
- HyperCLOVA X 기반 챗봇 페이지 UI
- 메인페이지, 스크랩 기능

`Java` `Spring Boot` `사람인 API`

### [우산 (우리 산에 가자)](https://github.com/BDA2022-2/team08) · 23팀 중 1위

산악 기상 빅데이터를 활용한 웹 서비스. 학부 빅데이터 응용 프로젝트. (2022.10 ~ 2022.11)

- 팀과 함께 스키마를 구성하고 ERD 작성 담당
- 로그인, 산 검색, 관리자 페이지 구현. 검색 쿼리와 로그인 세션 처리 담당
- Python, Pandas로 데이터 전처리

`PHP` `MariaDB` `Python` `Pandas`

<br>

## Education

- 네이버 클라우드 부트캠프 — 클라우드 네이티브 기반 웹 풀스택 개발자 과정 (2024.10 ~ 2025.05, 리더십상)
- 이화여자대학교 — 컴퓨터공학전공 및 자기설계(스크랜튼-디지털인문학) (2018.02 ~ 2024.02)
