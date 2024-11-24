<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> ECHO FARM - 동물복지 유정란</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header, section, article, footer {
            margin: 20px auto;
            max-width: 800px;
            padding: 20px;
            border-radius: 10px;
        }
        header {
            background-color: #eef5e9;
            text-align: center;
            position: relative;
        }
        header h1 {
            color: navy;
            font-size: 2.5em;
        }
        header p {
            color: #333;
            font-size: 1.2em;
        }
        .green-text {
            color: green;
            font-weight: bold;
        }
        nav {
            text-align: center;
            margin-top: 10px;
        }
        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: navy;
            font-weight: bold;
        }
        section {
            background-color: #ffffff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        article {
            margin-bottom: 20px;
        }
        article h3 {
            color: navy;
            font-size: 1.5em;
        }
        article img {
            display: block;
            margin: 10px auto;
            border-radius: 10px;
        }
        button {
            display: block;
            margin: 10px auto;
            padding: 10px 20px;
            background-color: green;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: darkgreen;
        }
        footer {
            background-color: #eef5e9;
            text-align: center;
        }
        footer p {
            color: #333;
            font-size: 1em;
        }
    </style>
</head>
<body>
    <header>
        <h1>🥚 ECHO FARM 🥚</h1>
        <p>행복한 닭이 낳은 ECHO FARM의 계란!<br>
           <span class="green-text">동물복지</span> 유정란으로 더 맛있고 윤리적인 선택을 시작해보세요.</p>
           <nav>
            <a href="#why-us">왜 ECHO FARM인가</a>
            <a href="#products">동물복지제품</a>
            <a href="#search">검색</a>
        </nav>
    </header>
    <aside id="why-us">
        <article>
            <h2>왜 ECHO FARM 의 1번, 2번란이 좋을까요? 🤔</h2>
            <p>4번란은 많이 생산되는 만큼 가격은 저렴하지만, <strong>닭들의 삶의 질</strong>은 보장되지 않아요.<br>
            반면에 ECHO FARM의 1번란과 2번란은 <span class="green-text">동물복지</span> 기준을 지켜 생산되죠! 🐔<br>
            닭들이 스트레스 없이 자라면 더 <em>맛있고 신선한</em> 달걀을 먹을 수 있어요! 🍳</p>
        </article>
        </aside>
    <section id="products">
        <h2>우리의 제품</h2>
        <div style="display: flex; justify-content: center; gap: 20px;">
            <article style="text-align: center;">
                <h3>은빛 훈제란</h3>
                <img src="media/훈제.jpg" width="200" height="200" alt="훈제란 이미지">
                <button>바로 구매</button>
            </article>
            <article style="text-align: center;">
                <h3>촉촉한 은빛 반숙란</h3>
                <img src="media/반숙.jpg" width="200" height="200" alt="반숙란 이미지">
                <button>바로 구매</button>
            </article>
        </div>
    </section>    
    <section id="search">
        <h2>검색하기 🔍</h2>
        <article>
            <input type="text" placeholder="찾고 싶은 정보를 입력하세요" style="width: calc(100% - 100px); padding: 10px;">
            <button>검색</button>
        </article>
    </section>
    <aside style="position: fixed; top: 20%; right: 5%; background-color: #eef5e9; padding: 15px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
        <h2>커뮤니티</h2>
        <ul style="list-style: none; padding: 0;">
            <li style="margin-bottom: 15px; text-align: center;">
                <a href="https://example.com/blog" target="_blank">
                    <img src="media/blog-icon.png" alt="블로그 아이콘" width="50" height="50"><br>
                    농장방문후기
                </a>
                <button style="margin-top: 5px;">보러가기</button>
            </li>
            <li style="margin-bottom: 15px; text-align: center;">
                <a href="https://youtube.com" target="_blank">
                    <img src="media/youtube-icon.png" alt="유튜브 아이콘" width="50" height="50"><br>
                    공장시설방문기
                </a>
                <button style="margin-top: 5px;">보러가기</button>
            </li>
            <li style="margin-bottom: 15px; text-align: center;">
                <a href="https://instagram.com" target="_blank">
                    <img src="media/instagram-icon.png" alt="인스타그램 아이콘" width="50" height="50"><br>
                    공식 인스타그램
                </a>
                <button style="margin-top: 5px;">바로가기</button>
            </li>
        </ul>
    </aside>
    <footer>
        <p> ECHO FARM - 동물복지 유정란. 모두의 행복을 위해!</p>
    </footer>
</body>
</html>
