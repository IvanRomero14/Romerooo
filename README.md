<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Para mi niña hermosa</title>

<style>
    body {
        margin: 0;
        height: 100vh;
        background: linear-gradient(to bottom, #0b1d26, #143d2b);
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: "Arial", sans-serif;
        color: #ffffff;
        text-align: center;
    }

    .card {
        background: rgba(0, 0, 0, 0.35);
        border-radius: 20px;
        padding: 25px;
        max-width: 360px;
        box-shadow: 0 0 25px rgba(0,0,0,0.4);
    }

    .star {
        font-size: 2.8rem;
        animation: glow 1.5s infinite alternate;
    }

    .tree {
        font-size: 1.7rem;
        line-height: 1.2;
        margin: 15px 0;
    }

    .message {
        margin-top: 20px;
        font-size: 1.1rem;
        line-height: 1.5;
    }

    .heart {
        font-size: 1.4rem;
        animation: beat 1.2s infinite;
        display: inline-block;
        margin-top: 10px;
    }

    @keyframes glow {
        from { text-shadow: 0 0 5px gold; }
        to   { text-shadow: 0 0 18px gold; }
    }

    @keyframes beat {
        0%   { transform: scale(1); }
        50%  { transform: scale(1.2); }
        100% { transform: scale(1); }
    }
</style>
</head>

<body>
    <div class="card">
        <div class="star">⭐</div>

        <div class="tree">
            🎄<br>
            🎄🎄<br>
            🎄✨🎄<br>
            🎄🎁🎄🎄<br>
            🎄🎄🎄🎄🎄<br>
            🎄🎄🎄🎄🎄🎄<br>
            🪵🪵🪵
        </div>

        <div class="message">
            💚 Feliz Navidad, mi niña hermosa 💚<br><br>
            Gracias por llegar a mi vida<br>
            y hacerla más bonita de lo que ya era.<br>
            Que esta Navidad te abrace fuerte,<br>
            como yo lo hago cuando te pienso 😘
        </div>

        <div class="heart">❤️</div>
    </div>
</body>
</html>