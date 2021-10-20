## Structure

![B33E99EA-9B3B-42AC-879C-AC398676101C_4_5005_c](https://user-images.githubusercontent.com/52040901/138164998-c371bd8e-c526-41fd-8f8e-65fb13f8f2ee.jpeg)

<pre>
<code>
🔥 client🔥
├─public
│ ├─index.html (기본 HTML)
│ └─favicon.ico (파비콘)
├─src
│ ├─assets (이미지, 폰트 등)
│ ├─constants (상수, 라우트 경로)
│ ├─styles (글로벌 스타일)
│ ├─lib (리액트 라우터, styled-components)
│ ├─components (컴포넌트 like view)
│ ├─containers (like vm)
│ ├─pages (페이지)
│ ├─store (redux 모듈)
│ ├─saga (saga 함수)
│ ├─types (ts 공통 타입, 인터페이스)
│ ├─hooks (커스텀 훅)
│ ├─utils (공통 유틸 함수)
│ │ └─api (api axios 요청)
│ ├─index.tsx
│ └─App.tsx
├─config
│ ├─webpack.common.js
│ ├─webpack.dev.js
│ └─webpack.prod.js
├─package.json
├─tsconfig.json
├─jest.config.js
├─.eslintrc.json
└─.prettierrc

🔥 server🔥
├── src
│ ├─config (db설정, dotenv 등)
│ ├─loaders (설정 불러오기)
│ ├─middlewares (미들웨어)
│ ├─routes (라우트)
│ ├─controllers (컨트롤러 / controller)
│ ├─services (데이터 가공 / service)
│ ├─repositories (쿼리문 / dao)
│ ├─models (모델 / dto)
│ ├─validation (req.body query parameter 값 검증)
│ ├─types (ts 공통 타입, 인터페이스)
│ ├─utils (공통되는 작은 함수)
│ │ └─error (에러 처리)
│ └─app.ts
├─package.json
├─tsconfig.json
├─.eslintrc.json
├─.prettierrc
└─.env
</code>
</pre>
