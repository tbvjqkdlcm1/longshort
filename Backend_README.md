## Structure

![B33E99EA-9B3B-42AC-879C-AC398676101C_4_5005_c](https://user-images.githubusercontent.com/52040901/138164998-c371bd8e-c526-41fd-8f8e-65fb13f8f2ee.jpeg)

<pre>
<code>
🔥 server🔥
├── apis
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
├── domain
│ ├─loaders
│ ├─loaders
│ └─loaders
└── service
  ├─loaders
  ├─loaders
  └─loaders
</code>
</pre>
