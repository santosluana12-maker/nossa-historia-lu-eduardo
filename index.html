<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Nossa História 💖</title>
<style>
body {
    margin: 0;
    overflow: hidden;
    background: linear-gradient(#ffdde1, #ee9ca7);
    font-family: Arial, sans-serif;
    text-align: center;
}
canvas {
    display: block;
    margin: auto;
}
#mensagemFinal {
    display: none;
    position: absolute;
    top: 30%;
    width: 100%;
    font-size: 22px;
    color: white;
    padding: 20px;
}
</style>
</head>
<body>

<canvas id="gameCanvas"></canvas>

<div id="mensagemFinal">
💖 Eduardo 💖<br><br>
Nossa história começou em 2019,<br>
na Aprimorar, como amigos e colegas.<br><br>
Mas em 12/05/2025<br>
nos permitimos viver nosso amor. 🩷<br><br>
Da viagem ao Paraguai<br>
até cada risada compartilhada,<br>
eu escolheria você mil vezes.<br><br>
Feliz nosso aniversário de namoro ✨<br>
Com amor, Lu.
</div>

<script>
const canvas = document.getElementById("gameCanvas");
const ctx = canvas.getContext("2d");

canvas.width = window.innerWidth;
canvas.height = window.innerHeight;

let heartY = canvas.height / 2;
let velocity = 0;
let gravity = 0.5;
let score = 0;
let gameOver = false;

let memories = [];

function drawHeart(x, y) {
    ctx.fillStyle = "red";
    ctx.beginPath();
    ctx.moveTo(x, y);
    ctx.bezierCurveTo(x-25, y-25, x-50, y+10, x, y+40);
    ctx.bezierCurveTo(x+50, y+10, x+25, y-25, x, y);
    ctx.fill();
}

function createMemory() {
    memories.push({
        x: canvas.width,
        y: Math.random() * canvas.height
    });
}

function update() {
    if (gameOver) return;

    ctx.clearRect(0, 0, canvas.width, canvas.height);

    velocity += gravity;
    heartY += velocity;

    drawHeart(100, heartY);

    memories.forEach((m, index) => {
        ctx.fillStyle = "white";
        ctx.beginPath();
        ctx.arc(m.x, m.y, 15, 0, Math.PI * 2);
        ctx.fill();

        m.x -= 3;

        if (Math.abs(m.x - 100) < 30 && Math.abs(m.y - heartY) < 30) {
            memories.splice(index, 1);
            score++;
        }
    });

    ctx.fillStyle = "white";
    ctx.font = "20px Arial";
    ctx.fillText("Memórias: " + score, 20, 30);

    if (score >= 5) {
        gameOver = true;
        document.getElementById("mensagemFinal").style.display = "block";
    }

    requestAnimationFrame(update);
}

canvas.addEventListener("click", () => {
    velocity = -10;
});

setInterval(createMemory, 2000);
update();
</script>

</body>
</html>
