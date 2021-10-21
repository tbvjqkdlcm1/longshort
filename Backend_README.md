## Backend Contributors

<table>
<td> <strong>문지윤</strong> </td>
<td> <strong>백승욱</strong> </td>
<td> <strong>정희재</strong> </td>

<tr>
<td> I'm on the next level </td>
<td> "슉.슈슉.슈슈..슉 슉..슈슈슉 " </td>
<td> 빠세이 호! </td>
</table>

## Structure

![B33E99EA-9B3B-42AC-879C-AC398676101C_4_5005_c](https://user-images.githubusercontent.com/52040901/138164998-c371bd8e-c526-41fd-8f8e-65fb13f8f2ee.jpeg)

<pre>
<code>
🔥 server🔥
├──apis
│ └─Controller (컨트롤러)
│ │ ├─analysisController.py (분석 컨트롤러)
│ │ └─dataAccessController.py (데이터접근 컨트롤러)
│ └─dto (data transfer object / 데이터 교환)
│   ├─requestDto.py (요청 전달)
│   └─responseDto.py (응답 전달)
├──domain (db / 모델)
│ ├─dao (data access object / 데이터 접근)
│ │ ├─articleDao.py (기사 접근)
│ │ ├─exampleDao.py (문제 접근)
│ │ ├─quizDao.py (퀴즈 접근)
│ │ ├─recyclingDao.py (재활용 접근)
│ │ ├─resultDao.py (결과 접근)
│ │ └─userDao.py (유저 접근)
│ └─models (모델생성)
│   ├─article.py (기사 모델)
│   ├─example.py (문제 모델)
│   ├─quiz.py (퀴즈 모델)
│   ├─recycling.py (재활용 모델)
│   ├─result.py (결과 모델)
│   └─user.py (유저 모델)
├──service (view / 뷰)
│ ├─analysisService.py (분석 로직)
│ ├─mainService.py (메인 로직)
│ ├─quizService.py (퀴즈 로직)
│ ├─rankService.py (점수랭크 로직)
│ ├─resultService.py (결과 로직)
│ ├─userRankService.py (유저랭크 로직)
│ └─userService.py (유저 로직)
├──app.py (실행)
├──config.py (비밀키)
└──db_connect.py (데이터베이스)

</code>
</pre>
