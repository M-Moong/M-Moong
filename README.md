<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:D9730D,100:F2C94C&height=180&section=header&text=M-Moong&fontSize=50&fontColor=FFFFFF&animation=fadeIn&fontAlignY=35" width="100%" />

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=24&duration=2500&pause=1200&color=D9730D&center=true&vCenter=true&width=520&lines=%EC%95%88%EB%85%95%ED%95%98%EC%84%B8%EC%9A%94+%F0%9F%91%8B;%ED%94%84%EB%A1%A0%ED%8A%B8%EC%97%94%EB%93%9C+%EA%B0%9C%EB%B0%9C%EC%9E%90+%EC%8B%A0%EC%8A%B9%EB%AF%BC%EC%9E%85%EB%8B%88%EB%8B%A4;PL%EB%A1%9C+%ED%8C%80%EC%9D%84+%EC%9D%B4%EB%81%8C%EA%B3%A0+%EC%9E%88%EC%8A%B5%EB%8B%88%EB%8B%A4;AI+%EC%9B%8C%ED%81%AC%ED%94%8C%EB%A1%9C%EC%9A%B0%EB%A5%BC+%EC%84%A4%EA%B3%84%ED%95%A9%EB%8B%88%EB%8B%A4" alt="Typing SVG" />

</div>

화면 개발 → 아키텍처 설계 → PL 승진 → 팀 AI 워크플로우 구축까지, **1년 7개월 만에 책임 범위를 넓혀온** 프론트엔드 개발자입니다.

<br>

### 🧭 저는 이런 개발자입니다

**① 기능 단위가 아니라 제품 관점에서 설계합니다**
Topology Page를 만들 때도 "그래프를 그린다"는 기능 단위가 아니라, 사용자가 실제로 네트워크 구조를 파악하고 조작하는 흐름 전체를 기준으로 화면을 구성했습니다. 데이터를 시각화하는 데서 그치지 않고, 운영 환경에서 실제로 쓸 수 있는 수준까지 고도화하는 데 집중합니다.

**② 기술 부채는 미루지 않고 정면돌파합니다**
PrimeReact는 컴포넌트 내부 스타일 오버라이드 자유도가 낮아서, 디자인 요구사항이 들어올 때마다 CSS로 땜질하는 게 계속 쌓이는 구조였습니다. "언젠가 갈아엎어야지"로 남겨두는 대신, 80개+ 컴포넌트를 shadcn/ui로 전면 리팩토링하는 판단을 실제로 실행했습니다.

**③ 반복되는 코드를 참지 못합니다**
같은 로직을 두 번째 짜는 순간이 리팩토링 타이밍이라고 생각합니다. 번역 리소스를 8개 카테고리로 나누고 공통 `useI18n` 훅으로 표준화해 프로젝트 전역 289개 파일이 이 훅 하나로 번역에 접근하게 만들었고, 화면마다 흩어져 있던 IP 검증 로직은 8단계 파이프라인·14종 에러 케이스로 표준화한 공통 유틸로 뽑아내 13개 파일에서 재사용하고 있습니다.

**④ 모호한 요구사항을 그냥 넘기지 않습니다**
기획·디자인 조직이 따로 없는 환경이라, 기술팀을 거쳐 전달되는 고객 요구사항이 "이런 기능이 있으면 좋겠다" 수준으로 뭉뚱그려져 오는 경우가 많았습니다. 그대로 개발에 착수하는 대신, 기술팀 담당자에게 정확한 의도를 재확인하는 절차를 스스로 만들어 적용했고, 그 결과 요구사항 불일치로 인한 재작업·불만 사례가 눈에 띄게 줄었습니다.

**⑤ 동료와 미래의 저를 위한 도구를 만듭니다**
QC가 배포 버전이 필요할 때마다 프론트에 매번 새 빌드를 요청해야 하는 불편을 겪는 걸 보고, 런타임에 버전을 조회해 QC가 직접 배포 버전을 조절할 수 있는 구조로 바꿨습니다. 배포 자동화 스크립트에는 실패 시 자동 롤백과 백업 관리를 처음부터 넣었습니다.

**⑥ 최신 흐름을 놓치지 않고, 실무로 연결하려는 태도를 갖고 있습니다**
모든 기술을 빠르게 학습하는 타입은 아니지만, AI가 개발 방식 자체를 바꾸고 있는 지금 흐름을 놓치지 않으려고 관련 아티클과 자료를 꾸준히 찾아봅니다. 팀에 적용 가능하다고 판단되면 직접 실험해보는 편이라, Claude Code·Codex용 팀 AI 워크플로우(`.agents.md` 가이드 + 자동 회의록 생성 Skill)를 실제로 설계해 배포까지 이어갔고, 회의록 작성 시간을 30분에서 10분으로 줄여 지금은 동료가 이어받아 팀 표준으로 쓰고 있습니다.

<br>

### 🔭 지금 하고 있는 일

- 🏢 폐쇄망 SaaS 환경에서 멀티 SKU·GS인증 대응 아키텍처 설계, 배포 자동화 구축
- 🤖 Claude Code·Codex용 팀 AI 워크플로우 설계·운영 (3주 연속 실사용, 팀 표준 워크플로우로 정착)
- 🧪 Vitest 기반 단위 테스트 환경 구축, 핵심 로직 위주로 커버리지 확대 중
- 🚀 dev → qc → demo 단계별 검증을 거치는 배포 파이프라인 운영 (환경별 자동 롤백·백업 관리)
- 💍 사이드 프로젝트 [모바일 청첩장](https://sm-se.com) 지속 운영·개선
- 🧩 [Baekjoon 알고리즘 문제](https://github.com/M-Moong/JavaScript__Algorithm) 꾸준히 풀이 (BaekjoonHub 자동 기록)

<br>

<details>
<summary>🌱 <b>관심사 / 요즘 들여다보는 것</b> (클릭해서 펼치기)</summary>
<br>

- AI 코딩 에이전트를 실무 워크플로우에 붙이는 방법 (Claude Code, Codex)
- React Flow 기반 대규모 실시간 시각화 성능 최적화
- 폐쇄망·엔터프라이즈 환경에서의 배포 자동화·릴리스 안정성

</details>

<br>

### 🛠️ Tech Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=react,ts,nextjs,tailwind,java,mysql,vitest,git,github,figma,vscode&theme=dark" />
</div>

<br>

### 🚀 대표 프로젝트

**[모바일 청첩장](https://sm-se.com)** — 결혼을 위해 기획부터 배포까지 혼자 만든 실사용 서비스
`Next.js 16` `Turborepo` `Drizzle ORM` `Supabase Postgres`

- 9개 챕터형 스크롤 내러티브 UX (갤러리·방명록·지도·퀴즈)
- Lighthouse 실측 기반 성능 튜닝 — 페이지 용량 11.5MB → 0.95MB (**92%↓**), LCP 6.1s → 4.6s
- 4.5개월간 152커밋, Vercel 커스텀 도메인 실배포
- 다음 목표: Lighthouse Performance 82점 → 90점대 진입

`→` [코드 보기](https://github.com/M-Moong/monorepo) · [사이트 방문](https://sm-se.com)

<br>

**팀 AI 워크플로우 자동화** (램파드, 사내 프로젝트 — 폐쇄망 환경이라 코드 비공개)
`Claude Code` `Codex` `.agents.md` `GitHub-style Skill`

- **Problem**: 매주 회의록 작성에 30분 이상 소요, 커밋 맥락 파악은 매번 수작업
- **Solution**: AI 코딩 에이전트용 공통 가이드(`.agents.md`, 153줄)를 작성하고, 매주 git 커밋을 자동 분석해 회의록을 생성하는 실행형 Skill(weekly-meeting)을 직접 설계·구현해 Claude Code·Codex 양쪽에 배포
- **Result**: 회의록 작성 시간 30분 → 10분(**66%↓**), 3주 연속 실사용, 동료 개발자가 이어받아 기능을 개선하며 팀 표준 워크플로우로 정착

<br>

### 📊 GitHub Stats

<div align="center">
<img src="https://github-stats-extended.vercel.app/api?username=M-Moong&show_icons=true&hide_border=false&border_color=30363d&hide_title=true&bg_color=00000000&title_color=D9730D&icon_color=D9730D&text_color=C9C9C9" height="165" />
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=M-Moong&layout=compact&hide_border=false&border_color=30363d&hide_title=true&bg_color=00000000&title_color=D9730D&text_color=C9C9C9" height="165" />
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=M-Moong&hide_border=true&bg_color=00000000&color=C9C9C9&line=D9730D&point=D9730D&area=true&area_color=D9730D" width="95%" />
</div>

<br>

### 📫 Contact

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-D9730D?style=flat-square&logo=Gmail&logoColor=white)](mailto:tmdals9154@gmail.com)

</div>
