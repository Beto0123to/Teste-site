<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site de Vídeos Adultos</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site de Vídeos!</h1>
        <p>Verifique sua idade antes de continuar.</p>
    </header>

    <div id="idadeVerificacao">
        <p>Você tem 18 anos ou mais?</p>
        <button onclick="confirmarIdade()">Sim</button>
        <button onclick="alert('Acesso negado!')">Não</button>
    </div>

    <div id="videos" class="video-container" style="display: none;">
        <h2>Vídeos:</h2>
        <div class="video-item">
            <video controls>
                <source src="videos/video1.mp4" type="video/mp4">
                Seu navegador não suporta o elemento de vídeo.
            </video>
        </div>
        <!-- Adicione mais vídeos conforme necessário -->
    </div>

    <script src="js/script.js"></script>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    background-color: #333;
    color: white;
    text-align: center;
    margin: 0;
    padding: 0;
}

header {
    background-color: #222;
    padding: 20px;
}

#idadeVerificacao {
    margin-top: 20px;
}

button {
    background-color: #FF6347;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    margin: 5px;
    font-size: 16px;
    border-radius: 5px;
}

button:hover {
    background-color: #FF4500;
}

.video-container {
    margin-top: 30px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.video-item {
    background-color: #444;
    padding: 10px;
    border-radius: 10px;
}

video {
    width: 320px;
    height: 240px;
}


