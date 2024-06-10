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
        </style>
    </head>
    <body>
        <div class="container mt-3 ">
            <h1>Project 주제 소개</h1>
            <hr>
            <h1>Project 바로가기</h1>
            <button class="button" onclick="redirectToLink()">Final Project</button>
            <hr>
        </div>
        <script>
            function redirectToLink() {
                window.location.href = "main.html"
            }
        </script>
    </body>
</html>
