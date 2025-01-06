---
layout: null
permalink: /strong/
---

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>你很強壯！</title>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background: #000;
    color: #fff;
    font-family: 'Helvetica Neue', sans-serif;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    overflow: hidden;
}

.message {
    font-size: 8em;
    font-weight: 900;
    text-align: center;
    margin-bottom: 1em;
    animation: powerUp 2s infinite;
    text-shadow: 
        0 0 20px #ff0000,
        0 0 40px #ff0000,
        0 0 60px #ff0000;
}

.image-container {
    position: relative;
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
}

.bodybuilders {
    width: 100%;
    height: auto;
    filter: contrast(150%) brightness(120%) saturate(150%);
    animation: flex 1s infinite;
    border: 5px solid #ff0000;
    box-shadow: 0 0 50px rgba(255, 0, 0, 0.5);
}

@keyframes powerUp {
    0% { transform: scale(1); }
    50% { transform: scale(1.1); }
    100% { transform: scale(1); }
}

@keyframes flex {
    0% { transform: rotate(-1deg); }
    50% { transform: rotate(1deg); }
    100% { transform: rotate(-1deg); }
}

.back-home {
    position: fixed;
    bottom: 2em;
    left: 50%;
    transform: translateX(-50%);
    padding: 1em 2em;
    font-size: 1.2em;
    text-decoration: none;
    color: #fff;
    background: #ff0000;
    border: none;
    border-radius: 5px;
    transition: all 0.3s ease;
}

.back-home:hover {
    background: #ff3333;
    transform: translateX(-50%) scale(1.1);
}
</style>
</head>
<body>
    <div class="message">你很強壯！</div>
    <div class="image-container">
        <img src="https://i.pinimg.com/originals/8f/14/91/8f149137b8b0d4f9c0d99f6e2c130b40.jpg" alt="Buff anime characters" class="bodybuilders">
    </div>
    <a href="/" class="back-home">返回</a>
</body>
</html> 