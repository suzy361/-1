# -1
김수지 거
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>포트폴리오 - 홈</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>나의 포트폴리오</h1>
    <nav>
      <ul>
        <li><a href="index.html">홈</a></li>
        <li><a href="report.html">보고서</a></li>
        <li><a href="plan.html">계획서</a></li>
        <li><a href="future.html">미래 자료</a></li>
        <li><a href="career.html">진로</a></li>
        <li><a href="university.html">대학</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>안녕하세요!</h2>
      <p>이 포트폴리오는 저의 학업 및 진로 계획을 정리한 자료입니다.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 나의 포트폴리오</p>
  </footer>
</body>
</html>
/* 전체 초기화 */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Noto Sans KR', sans-serif;
  background-color: #fdf6f0;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #ffe0e9;
  padding: 20px;
  text-align: center;
}

header h1 {
  color: #444;
}

nav ul {
  list-style: none;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 10px;
}

nav ul li a {
  text-decoration: none;
  color: #555;
  font-weight: bold;
}

nav ul li a:hover {
  color: #d17b88;
}

main {
  padding: 40px 20px;
  text-align: center;
}

section {
  max-width: 800px;
  margin: auto;
}

footer {
  background-color: #fce5cd;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
  color: #777;
}
