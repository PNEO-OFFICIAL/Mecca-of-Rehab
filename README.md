<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>온라인 재활 운동 강의</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #0077cc;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      margin-bottom: 0.5rem;
    }

    section {
      padding: 2rem 1rem;
      max-width: 800px;
      margin: auto;
    }

    .about {
      background: white;
      border-radius: 10px;
      margin-top: 1rem;
    }

    .videos iframe {
      width: 100%;
      height: 200px;
      margin-bottom: 1rem;
      border-radius: 10px;
      box-shadow: 0 0 5px rgba(0,0,0,0.2);
    }

    .video-container {
      display: grid;
      gap: 1rem;
    }

    @media(min-width: 600px) {
      .video-container {
        grid-template-columns: 1fr 1fr;
      }
    }

    .contact {
      background: #e0f0ff;
      border-radius: 10px;
      text-align: center;
    }

    .contact .btn {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.8rem 1.5rem;
      background: #0077cc;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }

    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      background: #eee;
    }
  </style>
</head>
<body>
  <header>
    <h1>재활 · 운동 강의 센터</h1>
    <p>건강을 되찾는 첫걸음, 집에서 시작하세요</p>
  </header>

  <section class="about">
    <h2>우리에 대해</h2>
    <p>
      물리치료 전문가들이 직접 제작한 온라인 재활 프로그램입니다.<br>
      각 과정은 단계별로 구성되어 누구나 쉽게 따라할 수 있어요.
    </p>
  </section>

  <section class="videos">
    <h2>대표 강의 미리보기</h2>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/VIDEO_ID1" frameborder="0" allowfullscreen></iframe>
      <iframe src="https://www.youtube.com/embed/VIDEO_ID2" frameborder="0" allowfullscreen></iframe>
    </div>
  </section>

  <section class="contact">
    <h2>문의하기</h2>
    <p>카카오톡: @rehabfit | 이메일: rehab@exercise.com</p>
    <a href="mailto:rehab@exercise.com" class="btn">이메일 문의</a>
  </section>

  <footer>
    <p>&copy; 2025 재활 운동 강의 센터. All rights reserved.</p>
  </footer>
</body>
</html>
