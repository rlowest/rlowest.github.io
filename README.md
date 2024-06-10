<!DOCTYPE html>
<html lang="en">
    <head>
        <title>2311221 이은서</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <style>
            .button {
                color: white;
                background-color: rgb(2, 87, 79);
                padding: 10px 20px;
                font-size: 15px;
                border: none;
                border-radius: 5px;
                cursor: pointer;
            }
            table {
                width: 100%;
                border-collapse: collapse;
                text-align: center;
                border: 1px solid #898989;
            }
        </style>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    </head>
    <body>
        <h1>Project 주제 소개</h1>
        <p>내가 태어날 때부터 살고 있는 지역인 ‘고양특례시’를 소개하는 웹페이지를 제작하고자 한다. 이 웹페이지는 고양특례시에 관한 기본적인 정보를 제공하고, 맛집, 공부하기 좋은 장소, 관광하기 좋은 장소 등을 소개하여 고양특례시에 관한 새로운 정보를 제공할 수 있다. 이를 통해 더 많은 사람들이 고양특례시에 방문하고 싶은 마음이 들 수 있도록 하고자 한다.</p>
        <hr>
        <h1>Project 바로가기</h1>
        <button class="button" onclick="redirectToLink()">Final Project</button>
        <hr>
        <h1>진행 상황</h1>
        <table>
            <thead>
                <tr>
                    <th>Date</th>
                    <th>Update Content</th>
                    <th>Complete</th>
                </tr>
            </thead>
            <tbody>
                <tr class="bg-light">
                    <td>5/21</td>
                    <td>주제 선정 : 내가 살고 있는 지역인 고양시 소개</td>
                    <td span class="badge bg-success">완료</span></td>
                </tr>
                <tr class="bg-white">
                    <td>5/23</td>
                    <td>페이지 구성 및 화면 설계서 작성</td>
                    <td span class="badge bg-success">완료</span></td>
                </tr>
                <tr class="bg-light">
                    <td>5/27</td>
                    <td>프로젝트 제안서 작성</td>
                    <td span class="badge bg-success">완료</span></td>
                </tr>
                <tr class="bg-white">
                    <td>6/4</td>
                    <td>프로젝트 소개 페이지 깃 연결</td>
                    <td span class="badge bg-success">완료</span></td>
                </tr>
                <tr class="bg-light">
                    <td></td>
                    <td>웹페이지 메인 컬러 선정 : #darkgreen</td>
                    <td span class="badge bg-success">완료</span></td>
                </tr>
                <tr class="bg-white">
                    <td>6/6</td>
                    <td>HOME - nav, aside</td>
                    <td span class="badge bg-success">완료</span></td>
                </tr>
                <tr class="bg-light">
                    <td>6/10</td>
                    <td>HOME - 레이아웃</td>
                    <td span class="badge bg-warning">진행중</span></td>
                </tr>
            </tbody>
        </table>
        <script>
            function redirectToLink() {
                window.location.href = "main.html"
            }
        </script>
    </body>
</html>
