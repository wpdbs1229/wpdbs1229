![header](https://capsule-render.vercel.app/api?type=venom&color=b678e8&height=220&section=header&text=My%20cat%20allows%20me%20to%20code.%20When%20my%20laptop%20is%20cold.&fontColor=d6ace6&fontSize=28&animation=fadeIn)

# 이제윤 · Lee JeYoun

**문제를 찾아서, 만들고, 출시하고, 사용자 이야기로 다시 고칩니다.**

백엔드 개발자로 1년 8개월 일했고, 지금은 길고양이 기록 앱 **냥도감**을 혼자 만들어 운영하고 있습니다.
기획부터 구현, 스토어 출시, 운영, 마케팅까지 직접 합니다. 고양이를 좋아합니다. 🐈

<a href="mailto:ghdlrr2969@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=Gmail&logoColor=white"/></a>
<a href="https://hidevelop.tistory.com"><img src="https://img.shields.io/badge/Blog-006600?style=flat-square&logo=Tistory&logoColor=white"/></a>
<a href="https://www.instagram.com/nangdogam"><img src="https://img.shields.io/badge/냥도감-E4405F?style=flat-square&logo=Instagram&logoColor=white"/></a>

<br>

## 지금 만들고 있는 것

### 🐾 냥도감 — 길고양이를 사진 한 장으로 기록하는 도감 앱

`1인 창업` `2026.05 ~ 현재` · [소개 페이지](https://catdex.muppin.org) · App Store / Google Play에서 '냥도감' 검색

- 유기묘 봉사자에게서 "돌보는 고양이가 너무 많아 관리하기 어렵다"는 이야기를 듣고 시작했습니다.
- 첫 커밋부터 **4개월 만에 양대 스토어에 출시**했고, 출시 뒤 일주일 동안 사용자 피드백으로 **업데이트를 3번** 냈습니다.
- "등록이 느려요"라는 말에 직접 재 보니 서버(평균 100ms)가 아니라 3~5MB 사진 업로드가 병목이었습니다. 압축해서 고쳤습니다.
- 중성화 여부를 사진으로 가려내는 모델을 실험했습니다. 공개 모델은 제가 찍은 사진 17장 중 1장만 맞혀서, 사진 301장을 직접 분류해 다시 학습시켰습니다(교차검증 74%). 실제 사진에서는 아직 부족해 앱에는 넣지 않았습니다.
- 출시 한 달, 가입자 83명 · 최근 30일 접속자 82명 (2026.10.08 기준)

### 🎨 Wiggle — 초등 교실용 AI 그림 코칭 웹앱

`4인 팀 (개발 2 · 영업 2)` `2026.06 ~ 현재` · 제품 결정과 프론트엔드 담당 · [www.kkumtle.app](https://www.kkumtle.app)

- 초등학교 수업에서 직접 테스트했습니다. 아이들이 AI 도우미 버튼을 거의 누르지 않아서, 도우미가 먼저 말을 걸도록 바꿨습니다.
- "보안을 위해 6자리 코드" 의견과 "아이들은 긴 코드를 못 친다"는 선생님 의견이 부딪혔을 때, **반 QR + 4자리 코드**로 둘 다 지켰습니다.
- "도화지가 작아요", "펜보다 선이 늦게 따라와요"라는 현장 피드백을 받아 도화지를 넓히고 펜슬 지연을 없앴습니다.
- 2026 경기청년 갭이어 팀 선정

### 🏠 Muppin — 홈 라이프 SNS 앱

`팀` `2026.03 ~ 2026.08` · 백엔드 · 인프라 담당 · Google Play 출시

- 라즈베리파이 2대로 홈서버를 직접 구축하고, Docker 단일 배포를 Kubernetes로 전환해 모니터링과 장애 알림까지 붙였습니다.

<br>

## 경력

| 기간 | 회사 | 한 일 |
|---|---|---|
| 2025.06 ~ 2026.07 | **㈜날리지포인트** · 시스템본부 주임 | KT 스팸 차단 서비스(누적 가입자 2,500만 명) 서버 개발·운영<br>· 배치 프로그램 33개를 Solaris/C에서 Azure/Java 17로 전환<br>· GitHub Actions + Jenkins로 33개 모듈 배포 자동화<br>· 서버 4대가 같은 메시지를 중복 발송하던 문제 해결 |
| 2023.07 ~ 2023.12 | **㈜제이케이코어** · 웹연구개발부서 인턴 | 태양광 발전 모니터링 앱 '오늘해' 서버 개발<br>· 발전량·수익금 REST API, 로그인(Spring Security + JWT, OAuth2)<br>· Jenkins + Nginx로 자동 배포·무중단 배포 |

<br>

## 기술

**Backend** &nbsp; Java · Spring Boot · JPA · MariaDB · PostgreSQL(Supabase)<br>
**Infra** &nbsp; Docker · Kubernetes · AWS · Azure · GitHub Actions · Jenkins<br>
**Product** &nbsp; React Native(Expo) · Next.js · RevenueCat · PostHog · Sentry<br>
**AI** &nbsp; Claude Code · Codex · 프롬프트 설계 · PyTorch(EfficientNet 파인튜닝)

<br>

## 학력 · 자격

- 한국기술교육대학교 컴퓨터공학 졸업 (편입, 2021.03 ~ 2025.09)
- 정보처리기사 (2024.06) · 리눅스마스터 2급 (2025.07)
- 2026 모두의 창업 1라운드 합격 (냥도감)
