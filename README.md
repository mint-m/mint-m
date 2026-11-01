### mint-m

---

#### 🫘 [Bean-Hoarder](https://github.com/mint-m/bean-hoarder) — 원두 소분 QR 라벨 서비스

상품 페이지 링크를 넣으면 AI가 원두 정보를 채우고, 소분 용기에 붙일 QR을 만들어 줍니다.
**[데모 보기](https://bnhd.pages.dev/demo)** (로그인 없이) · [서비스](https://bnhd.pages.dev)

- TypeScript 모노레포, Cloudflare Pages · Functions · D1 · R2, 운영비 0원
- 린트·Vitest·Playwright e2e를 통과해야 배포되는 CI.
- 문서는 한 곳에서만 갱신: [STRUCTURE](https://github.com/mint-m/bean-hoarder/blob/main/STRUCTURE.md)(코드에서 생성) · [DESIGN](https://github.com/mint-m/bean-hoarder/blob/main/DESIGN.md)(디자인 시스템) · [CLAUDE](https://github.com/mint-m/bean-hoarder/blob/main/CLAUDE.md)(작업 원칙)

#### 🀄 [kanji](https://github.com/mint-m/kanji) — JLPT 일본어 단어 학습 앱

슬라이딩 윈도우 덱으로 모르는 단어만 돌려 가며 외우는 학습 앱. [라이브](https://kanji-red.vercel.app) (Google·Kakao 로그인)

- React · TypeScript · Redux Toolkit / Express · MongoDB, JWT 인증, Vercel + Render
- 학습 진행을 자동 저장하는 체크포인트, 북마크 복습 세션

---

#### 일하는 방식

- 코드를 한 줄씩 읽기보다, 완성된 결과물과 AI의 보고·테스트 결과를 확인합니다. 이게 가능하도록 검증 게이트를 먼저 만듭니다.
- AI는 파일을 늘리기만 하고 관리하지 않기 때문에, 파일 생성을 제한하고 수정은 한 곳(SSOT)에서만 하게 합니다. 여러 에이전트와 모델을 같이 써도 작업이 이어집니다.
- 빠르게 많이 만드는 것보다 정확하고 낭비 없는 과정을 우선합니다.

그 외: [swipeclean](https://github.com/mint-m/swipeclean) (iOS 사진 정리 앱) · 오래된 프로젝트는 [mmm-attic](https://github.com/mmm-attic)
