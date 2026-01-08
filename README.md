# proposal
index.html
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Для тебя ❤️</title>
<style>
body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    background: linear-gradient(180deg, #0f2027, #203a43, #2c5364);
    color: white;
    text-align: center;
}
.container {
    padding: 40px 20px;
}
img {
    max-width: 90%;
    border-radius: 20px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.5);
}
h1 {
    margin-top: 30px;
    font-size: 32px;
}
p {
    font-size: 22px;
    margin-top: 20px;
}
.heart {
    font-size: 50px;
    animation: pulse 1.5s infinite;
}
@keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.2); }
    100% { transform: scale(1); }
}
</style>
</head>
<body>
<div class="container">
    <img src="photo.jpg" alt="Мы">
    <h1>Солнце, я люблю тебя ❤️</h1>
    <p>Ты выйдешь за меня?</p>
    <div class="heart">💍</div>
</div>
</body>
</html>
