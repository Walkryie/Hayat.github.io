# Hayat.github.io
<!DOCTYPE html><html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hayat'ın Duygu Durumu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            padding: 20px;
        }
        .container {
            max-width: 400px;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        h1 {
            color: #ff6f61;
        }
        #moodDisplay {
            font-size: 2em;
            margin: 20px 0;
        }
        button {
            background: #ff6f61;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 10px;
            cursor: pointer;
        }
        button:hover {
            background: #e55b50;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hayat'ın Duygu Durumu</h1>
        <div id="moodDisplay">😊</div>
        <input type="text" id="moodInput" placeholder="Emoji veya duygu gir...">
        <button onclick="updateMood()">Güncelle</button>
    </div><script>
    function updateMood() {
        var mood = document.getElementById('moodInput').value;
        document.getElementById('moodDisplay').innerText = mood;
    }
</script>

</body>
</html>
