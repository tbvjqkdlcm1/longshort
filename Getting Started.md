## Getting Started

### Prerequisites
`db`운용시 `server`디렉토리 내에 `config.py`에 db 연결 후 `secret.py`생성 하세요.<br>

##### db migrate 연결시
`flask db init # 마이그레이션 연동 시작
flask db migrate # 데이터베이스 스키마 변경사항 감지
flask db update # 변경사항 적용`

### 웹 어플리케이션

<pre>
<code>
# Development
$ cd ~/frontend && yarn start or npm start
</code>
</pre>

### API 서버

<pre>
<code>
# Development
$ cd ~/backend/server/app.py && python app.py
</code>
</pre>
