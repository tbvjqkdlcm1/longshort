## Getting Started

### Prerequisites
`secret.py` `gitignore` 해놨으니 `db`운용시 `server`디렉토리 내에 `secret.py`생성 하시고.<br>
`secret.py` 내에 `db_pw = 'Database-password'`, `secret_key = 'Server-Secret-Key'` 

### 웹 어플리케이션

<pre>
<code>
# Development
$ cd SSrang/frontend && yarn start or npm start
</code>
</pre>

### API 서버

<pre>
<code>
# Development
$ cd SSrang/server/app.py && flask run app.py
</code>
</pre>
