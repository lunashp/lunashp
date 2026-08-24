### 양희진 · 프론트엔드 개발자

AI 브랜드 분석 SaaS에서 프론트엔드를 전담하고 있습니다.
**사람 눈으로는 잡히지 않는 결함을 자동 검증 게이트로 바꾸는 일**과, 답변 엔진·AI 에이전트가 읽고 쓰는 프론트엔드에 관심이 있습니다.

<br>

#### 만들고 있는 것

**[component-explorer](https://github.com/lunashp/component-explorer)**
React·TypeScript 프로젝트를 **읽기 전용으로** 스캔해 컴포넌트를 분류하고, 격리 환경에서 실제로 렌더링해 확인한 뒤 이식 가능한 코드로 추출하는 도구입니다.
유닛 테스트 1,090개가 전부 통과하는 상태에서 실제로 렌더되는 컴포넌트가 75.3%뿐이라는 것을 발견하고, 그 조사 도구 자체를 게이트로 만들어 91.8%까지 올렸습니다.
같은 엔진을 MCP 서버로 감싸 AI 에이전트도 쓸 수 있게 했습니다.

**[jiny-log](https://github.com/lunashp/jiny-log)**
케이스 스터디와 트러블슈팅 기록을 남기는 블로그입니다. Astro 7 · 한국어/영어.
Next.js로 만들었다가 클라이언트 컴포넌트를 전부 제거해도 JS 138KB가 남는 것을 실측하고 Astro로 옮겼습니다(현재 2.2KB).
번들 예산·접근성·시각 회귀를 **CI 하드 게이트**로 묶어, 예산을 올려서 통과시키지 않습니다.

**[blog-publisher](https://github.com/lunashp/blog-publisher)**
위 블로그에 글을 발행하는 MCP 서버입니다. 초안이 기본값이고, GitHub 커밋을 거쳐 배포됩니다.

<br>

TypeScript · React · Next.js · Astro · Vitest · Playwright · MCP
