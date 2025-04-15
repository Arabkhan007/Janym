# Janym
<!DOCTYPE html>
<html lang="kk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Саған Арналған Ашықхат</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="card">
    <h1>Саған Арналған!</h1>
    <p>
      Бүгін – махаббат пен мейірімнің күні!<br><br>
      Сенің жанарыңдай жарқыраған күн болсын бұл күн.<br>
      Күлкің сөнбесін, жүрегің шаттыққа толсын.<br><br>
      Сүйкімді жаным, сен менің өмірімнің ең нәзік гүлісің.<br>
      Саған қарап, жүрегімде күн ашылады.<br>
      Достықтан басталған сезім – мәңгілік жылулыққа айналды.<br>
      Сенің жанында болғаным – мен үшін ең үлкен сый.<br><br>
      Әр күнің осындай әдемі әрі жүрекке жылы болсын!<br>
      Сенімен өмір – ғажайып ертегі секілді.
    </p>
    <div class="heart">❤️</div>
  </div>
</body>
</html>
body {
  background: linear-gradient(to right, #ffdde1, #ee9ca7);
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  display: flex;
  height: 100vh;
  align-items: center;
  justify-content: center;
}

.card {
  background: white;
  padding: 40px;
  border-radius: 25px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.2);
  max-width: 500px;
  text-align: center;
  animation: fadeIn 2s ease;
}

h1 {
  color: #e91e63;
}

p {
  font-size: 18px;
  line-height: 1.7;
  color: #333;
}

.heart {
  font-size: 40px;
  margin-top: 20px;
  animation: pulse 1.5s infinite;
}

@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.2); }
  100% { transform: scale(1); }
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
