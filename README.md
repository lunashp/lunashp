### 양희진 · 프론트엔드 개발자

클라우드 엔지니어로 시작해 풀스택을 거쳐 프론트엔드로 왔습니다.
지금은 AI 브랜드 분석 SaaS에서 프론트엔드를 혼자 맡아 웹 프로덕트 7건을 담당하고, 그중 4건은 요구사항 정리부터 배포 구성까지 0에서 만들었습니다.

관심사는 둘로 모입니다 — **사람 눈으로는 잡히지 않는 결함을 자동 검증 게이트로 바꾸는 일**, 그리고 **답변 엔진·AI 에이전트가 읽고 쓰는 프론트엔드**. 아래 셋은 그 기록입니다.

<br>

**[component-explorer](https://github.com/lunashp/component-explorer)** — React·TypeScript 코드베이스를 읽기 전용으로 스캔해 컴포넌트를 분류·렌더·추출하는 도구

> 유닛 테스트 1,090개가 전부 통과하는데, 실제로 렌더되는 컴포넌트는 75.3%뿐이었습니다.
> 그 사실을 알아낸 조사 도구를 그대로 게이트로 만들어 91.8%까지 올렸습니다.
> 같은 엔진을 MCP 서버로 감싸 AI 에이전트도 쓸 수 있게 했습니다.

**[jiny-log](https://jiny-log.vercel.app)** · [저장소](https://github.com/lunashp/jiny-log) — 케이스 스터디와 트러블슈팅 기록. Astro 7 · 한국어/영어

> Next.js에서 클라이언트 컴포넌트를 전부 제거해도 JS 138KB가 남는 것을 실측하고 Astro로 옮겼습니다. 현재 2.2KB.
> 번들 예산·접근성·시각 회귀가 CI 하드 게이트입니다. 예산을 올려서 통과시키지 않습니다.
> 글마다 완결된 요약을 본문 최상단에 두고, 원문 마크다운과 `llms.txt`를 별도 라우트로 서빙합니다.

**[blog-publisher](https://github.com/lunashp/blog-publisher)** — 위 블로그에 글을 발행하는 MCP 서버

> 초안이 기본값이고, 발행은 명시적 호출로만 일어납니다.
> 상태 전이가 전부 git 커밋으로 남아 되돌릴 수 있습니다.

<br>

**만드는 것** &nbsp; TypeScript · React · Next.js · Astro
**검증하는 것** &nbsp; Vitest · Playwright · axe-core · Zod
**거쳐온 것** &nbsp; Docker · GitLab CI · Jenkins · SonarQube

<br>

[hijnshp@gmail.com](mailto:hijnshp@gmail.com) &nbsp;·&nbsp; [소개](https://jiny-log.vercel.app/ko/about) &nbsp;·&nbsp; [케이스 스터디](https://jiny-log.vercel.app/ko/work)
