DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Untuk Octa Gracia</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: #5a3e3e;
        }
        .container {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
            padding: 40px;
            max-width: 800px;
            width: 100%;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        h1 {
            color: #e91e63;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        .quote {
            font-size: 1.3rem;
            font-style: italic;
            color: #d81b60;
            margin: 25px 0;
            line-height: 1.6;
        }
        #magic-button {
            background: linear-gradient(45deg, #ff6b8b, #ff8e9e);
            color: white;
            border: none;
            padding: 15px 30px;
            border-radius: 50px;
            font-size: 1.2rem;
            cursor: pointer;
            margin: 20px 0;
            box-shadow: 0 5px 15px rgba(255, 107, 139, 0.4);
            transition: all 0.3s;
        }
        #magic-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(255, 107, 139, 0.6);
        }
        #surprise {
            display: none;
            margin-top: 30px;
            animation: fadeIn 1s;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        #special-message {
            background: rgba(255, 240, 245, 0.7);
            padding: 25px;
            border-radius: 15px;
            border-left: 5px solid #ff6b8b;
            text-align: left;
            font-size: 1.1rem;
            line-height: 1.8;
        }
        .heart {
            color: #ff6b8b;
            font-size: 1.5rem;
            animation: pulse 1.5s infinite;
            display: inline-block;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        .footer {
            margin-top: 30px;
            font-style: italic;
            color: #b76e79;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Untuk Octa Gracia <span class="heart">♥️</span></h1>
        <div class="quote">"Bumi itu luas, untung aja kita bertemu"</div>
        <button id="magic-button">Klik Aku, Octa!</button>
        <div id="surprise">
            <div id="special-message">
                Octa-octa, I never knew things would turn out like this. But thankfully I have you.<br><br>
                Awalnya, I thought you were just a replacement for the one who betrayed me...<br><br>
                But now, aku berpikir untuk lebih daripada itu. More than just a replacement.<br><br>
                Setiap hari bersamamu membuatku menyadari bahwa kamu berbeda.<br><br>
                You came like sunshine after rain, menghangatkan dan menyinari hidupku.<br><br>
                I never imagined finding someone like you setelah rasa sakit itu.<br><br>
                Dan sekarang... I want more. More than just a friend, lebih dari sekedar pengganti.<br><br>
                Dan yang akan selalu ada untukmu seperti kamu ada untukku.<br><br>
                Maaf kalau aku masih belajar, but I promise I'll keep trying to be better for us.
            </div>
        </div>
        <div class="footer">Dibuat dengan <span class="heart">♥️</span> khusus untukmu</div>
    </div>
    <script>
        document.getElementById('magic-button').addEventListener('click', function() {
            this.style.display = 'none';
            document.getElementById('surprise').style.display = 'block';
            document.getElementById('surprise').scrollIntoView({ behavior: 'smooth' });
        });
    </script>
</body>
</html>
