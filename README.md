# smtng
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sign Language to Speech Converter</title>
<link rel="stylesheet" href="Motu.css">
</head>
<body>
    <div class="container">
        <h1>Sign Language to Speech Converter</h1>
        <div class="video-container">
            <video id="webcam" autoplay playsinline></video>
            <canvas id="output"></canvas>
        </div>
        <div class="output-container">
            <h2>Detected Text:</h2>
            <p id="detected-text">No sign detected</p>
            <h2>Select Language:</h2>
            <select id="language-selector">
                <option value="en-US">English (US)</option>
                <option value="es-ES">Spanish (Spain)</option>
                <option value="fr-FR">French (France)</option>
                <option value="de-DE">German</option>
            </select>
            <button id="speak-btn">Speak</button>
        </div>
    </div>
    <script src="Motu.js"></script>
</body>
</html>
