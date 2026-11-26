# Polyship AI

> 에디터와 Gemini·Claude·GPT 코파일럿을 분할 화면으로 결합한 멀티 모델 AI 작업 공간.

- 고객 대상: Prosumer (B2P)
- 분야: 생산성 · 워크스페이스
- 시장 범위: Horizontal
- 제공 방식: Web App
- 과금 모델: BYOAPI (무료/오픈)
- 상태: 배포완료
- 데모: https://jake12733.github.io/polyship-ai/
- GitHub: https://github.com/jake12733/polyship-ai

## 1. 문제 정의 & 타깃
- 문서·코드 작업 중 여러 AI 모델(Gemini, Claude, GPT)을 오가며 복사·붙여넣기하는 컨텍스트 스위칭 비용이 큼.

## 2. 핵심 기능 & 흐름 (MVP)
- 좌측 에디터 + 우측 AI 코파일럿 분할 화면(Split-screen) 워크스페이스
- Gemini / Claude / GPT 멀티 모델 전환 및 BYOAPI 연동

## 3. 수익 모델 & SaaS 구조
- 고객 대상: Prosumer (1인 작업자 · 크리에이터 · 개발자)
- 과금/운영: BYOAPI 기반으로 진입 장벽 제거 후 향후 팀 플랜/클라우드 동기화로 확장 가능

## 4. 아키텍처 & 기술 선택 이유
- 정적 빌드 기반 프론트엔드 + 멀티 LLM 프로바이더 어댑터 패턴
- [선택] 분할 화면 단일 워크스페이스: 탭 전환 없이 작성·수정·생성을 한 흐름으로 연결

## 5. 트러블슈팅 & 핵심 설명 포인트
- 향후 로그인·문서 클라우드 저장·사용량 과금을 붙이면 완전한 구독형 Prosumer SaaS로 전환 가능.
