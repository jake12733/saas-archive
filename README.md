# Owen's SaaS Archive

> 직접 기획하고 개발한 다양한 유형의 SaaS 프로젝트와 **기획서(PRD)**, **기술적 의사결정(ADR)**, **면접 설명 포인트**를 정리해 둔 아카이브입니다.

- **라이브 아카이브 링크**: https://jake12733.github.io/saas-archive/
- **기존 웹 포트폴리오 (Owen's Archive)**: https://jake12733.github.io/acharive/

---

## SaaS 프로젝트 & 기획서 목록

| # | 프로젝트명 | SaaS 유형 | 상태 | 기획서(PRD) |
|---|---|---|---|---|
| 01 | AI 마케팅 콘텐츠 자동화 스튜디오 | Micro-SaaS / Prosumer | 기획중 | [01-ai-marketing-micro-saas.md](plans/01-ai-marketing-micro-saas.md) |
| 02 | B2B 리드·CS 자동화(AX) 워크스페이스 | B2B / Vertical | 기획중 | [02-b2b-ax-workspace.md](plans/02-b2b-ax-workspace.md) |
| 03 | RAG AI 튜터 미니 구독형 클래스 플랫폼 | B2B2C / 교육 | 기획중 | [03-rag-class-platform.md](plans/03-rag-class-platform.md) |

---

## 저장소 구조

```text
saas-archive/
├── index.html                           # GitHub Pages 대시보드 (Owen's Archive 스타일 + 기획서 뷰어/에디터)
├── plans/                               # 프로젝트별 기획서(PRD) 마크다운 모음
│   ├── 01-ai-marketing-micro-saas.md
│   ├── 02-b2b-ax-workspace.md
│   └── 03-rag-class-platform.md
└── templates/
    └── saas-prd-template.md             # 새 SaaS 시작 시 복사해서 쓰는 표준 기획서 템플릿
```

## 새 SaaS 프로젝트 추가 방법

1. [라이브 아카이브](https://jake12733.github.io/saas-archive/)에서 **+ SaaS 추가** 버튼으로 프로젝트와 기획서를 작성합니다.
2. 기획서 모달에서 **.md 저장** 버튼으로 기획서를 내려받아 `plans/` 폴더에 올립니다.
3. 모든 방문자에게도 보이도록 영구 반영하려면 상단 툴바의 **코드 복사(↓)** 버튼으로 `DEFAULT_PROJECTS` 코드를 복사해 `index.html`에 붙여넣고 커밋하면 GitHub Pages에 자동 반영됩니다.
