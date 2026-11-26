# Polyship

> 글로벌 1인 개발자·인디해커용 다국어(8개국어) Next.js 15 SaaS 보일러플레이트. Firebase 인증, BYOAPI AI 엔진, Paddle/Lemon Squeezy 결제, 크롬 확장(Polyship Agent) 포함.

- 고객 대상: B2D (개발자·엔지니어링 팀 대상)
- 분야: 보일러플레이트 · 스타터
- 시장 범위: Horizontal
- 제공 방식: Boilerplate / Starter (+ Chrome Extension)
- 과금 모델: One-time (일회성 라이선스)
- 상태: 배포완료
- 데모: https://jake12733.github.io/polyship-demo/
- GitHub: https://github.com/jake12733/polyship

## 1. 문제 정의 & 타깃
- 1인 개발자가 글로벌 SaaS를 만들 때마다 인증·결제·다국어(i18n)·AI 연동 보일러플레이트를 매번 새로 구축하느라 출시가 늦어짐.
- 해외 결제(Paddle/Lemon Squeezy) 웹훅과 AI API 키 관리(BYOAPI)를 처음부터 안정적으로 붙이기 번거로움.

## 2. 핵심 기능 & 흐름 (MVP)
- 8개국어 다국어(i18n) 지원 및 Next.js 15 + TypeScript strict 모듈 구조
- Firebase Auth + Firestore 기반 인증/데이터 레이어
- Paddle 구독 결제 및 웹훅 처리, BYOAPI 멀티 모델 AI 엔진, Chrome 확장(Polyship Agent)

## 3. 수익 모델 & SaaS 구조
- 고객 대상: B2D (글로벌 1인 개발자 · 인디해커)
- 형태: SaaS 제작용 보일러플레이트(스타터킷) — 이 코드베이스 위에서 다양한 SaaS를 빠르게 파생 배포

## 4. 아키텍처 & 기술 선택 이유
- Next.js 15 App Router + Tailwind CSS v4 + Firebase + Paddle Webhook
- [선택] 서버 과금 대신 BYOAPI 구조 지원: 초기 AI API 비용 리스크 없이 사용자가 본인 키로 즉시 테스트·운영 가능

## 5. 트러블슈팅 & 핵심 설명 포인트
- Polyship 자체는 B2D(개발자 대상) 스타터킷이며, 여기서 파생된 웹 앱(Polyship AI 등)은 Prosumer(B2P) SaaS로 확장됨.
