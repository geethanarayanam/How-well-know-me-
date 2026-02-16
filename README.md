<html>
<head>
<style>
  body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; text-align: center; background-color: #fdf2f2; padding: 20px; }
  .card { background: white; padding: 20px; border-radius: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); max-width: 400px; margin: auto; }
  h2 { color: #d63384; }
  .question { margin: 20px 0; font-weight: bold; }
  button { padding: 10px 20px; margin: 5px; border: none; border-radius: 5px; cursor: pointer; transition: 0.3s; }
  .yes { background-color: #ffb6c1; color: white; }
  .no { background-color: #ddd; color: #555; }
  button:hover { opacity: 0.8; transform: scale(1.05); }
</style>
</head>
<body>

<div class="card">
  <h2>The "How Well Do You Know Me?" Quiz ❤️</h2>
  
  <div class="question">1. Do I like the color Green? <br>
    <button class="yes" onclick="alert('Correct! 🌿')">Yes</button>
    <button class="no" onclick="alert('Try again! 😉')">No</button>
  </div>

  <div class="question">2. Do I like the color Beige? <br>
    <button class="yes" onclick="alert('Yes! So aesthetic! ✨')">Yes</button>
    <button class="no" onclick="alert('Wrong! I love it!')">No</button>
  </div>

  <div class="question">3. Is a new Dress on my list of things I like? <br>
    <button class="yes" onclick="alert('Spot on! 👗')">Yes</button>
    <button class="no" onclick="alert('I always love a dress!')">No</button>
  </div>

  <div class="question">4. Do I like my Phone? <br>
    <button class="yes" onclick="alert('Correct! 📱')">Yes</button>
    <button class="no" onclick="alert('Wrong!')">No</button>
  </div>

  <div class="question">5. Is Finland a country I like? <br>
    <button class="yes" onclick="alert('Yes! 🇫🇮')">Yes</button>
    <button class="no" onclick="alert('Nope, I love it!')">No</button>
  </div>

  <div class="question">6. Is Switzerland a country I like? <br>
    <button class="yes" onclick="alert('Absolutely! 🇨🇭')">Yes</button>
    <button class="no" onclick="alert('Incorrect!')">No</button>
  </div>
</div>

</body>
</html>
