<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Naksh ❤️ Samridhi</title>
<style>
body{margin:0;font-family:'Segoe UI',sans-serif;background:linear-gradient(to bottom,#ff9a9e,#fad0c4);overflow:hidden;}
.page{display:none;height:100vh;width:100vw;padding:25px;box-sizing:border-box;text-align:center;animation:fade 1s ease;}
.page.active{display:block;}
@keyframes fade{from{opacity:0}to{opacity:1}}
button{padding:14px 24px;border:none;border-radius:30px;background:#ff3366;color:white;font-size:18px;margin-top:15px;box-shadow:0 4px 10px rgba(0,0,0,.2);}
img{max-width:80%;border-radius:20px;margin:10px;box-shadow:0 0 15px rgba(255,0,80,0.5);}
.game-btn{display:block;margin:10px auto;}
.heart{position:fixed;font-size:22px;animation:float 6s linear infinite;}
@keyframes float{from{bottom:-20px;opacity:1}to{bottom:110%;opacity:0}}
</style>
</head>

<body>

<audio autoplay loop>
  <source src="song.mp3" type="audio/mpeg">
</audio>

<div class="page active">
<h1>Hey Samuuuuu 🐻💖</h1>
<p>Your Bubu Naksh built this love universe just for you 😏💃🕺</p>
<button onclick="next()">Enter Our Love World 🌍💘</button>
</div>

<!-- 💖 Memories Slider Page -->
<div class="page">
  <h2>Samridhi & Naksh 💖</h2>
  <p>Dance partners • Annoying • Funny • Forever</p>

  <div id="slider">
    <img id="slideImage" src="Snapchat-14081490.jpg"
         style="width:90%;height:60vh;object-fit:cover;border-radius:20px;box-shadow:0 0 15px rgba(255,0,80,0.5);" />
  </div>

  <button onclick="nextSlide()">Next Memory 💫</button>
  <br><br>
  <button onclick="next()">Next</button>
</div>

<script>
let slides = [
  "images/Snapchat-14081490.jpg",
  "images/Snapchat-1527682850.jpg",
  "images/Snapchat-1603898133.jpg",
  "images/Snapchat-1983733540.jpg",
  "images/Snapchat-509499410.jpg",
  "images/Snapchat-986324046.jpg",
  "images/Snapchat-98778515.jpg"
];
let currentSlide = 0;
function nextSlide(){
  currentSlide = (currentSlide + 1) % slides.length;
  document.getElementById("slideImage").src = slides[currentSlide];
}
</script>

<!-- 10 LOVE LETTER PAGES -->
<div class="page"><h2>Love Letter 1 💌</h2><p>My Parvati 😭❤️ My Radhaa Ji 🌸 My Hippopotamus 🐻🥹… bubu you are my safe place, my madness, my peace, my forever 😭🫶</p><button onclick="next()">Next 💌</button></div>
<div class="page"><h2>Love Letter 2 💌</h2><p>Samuuuuu 😭💖 Kuchuu Puchuu 😤💕 Laadooo 🌸 Goliiii 🥹🫶 Kamini Bhudhii 😂🐻 you turned my boring life into a dance floor 💃🕺</p><button onclick="next()">Next 💌</button></div>
<div class="page"><h2>Love Letter 3 💌</h2><p>Bubu 😭🐻 when you smile, my whole world lights up 🌍✨ when you get angry I still love you more 😤❤️</p><button onclick="next()">Next 💌</button></div>
<div class="page"><h2>Love Letter 4 💌</h2><p>My Radhaa 😭🌸 my Parvati 😭💖 you are my dream, my reality, my future 💍✨</p><button onclick="next()">Next 💌</button></div>
<div class="page"><h2>Love Letter 5 💌</h2><p>Kutti 😤💕 Kamini 😂🐻 you make me laugh even when life is heavy 🫶💖</p><button onclick="next()">Next 💌</button></div>
<div class="page"><h2>Love Letter 6 💌</h2><p>Hippopotamus 🐻💖 you are my comfort zone and my adventure both 🌍🔥</p><button onclick="next()">Next 💌</button></div>
<div class="page"><h2>Love Letter 7 💌</h2><p>Goliiii 🥹🫶 my heart belongs to you only 😭💘</p><button onclick="next()">Next 💌</button></div>
<div class="page"><h2>Love Letter 8 💌</h2><p>Laadooo 🌸💖 my forever Valentine 😭💍</p><button onclick="next()">Next 💌</button></div>
<div class="page"><h2>Love Letter 9 💌</h2><p>Samuuuuu 😭💖 you’re my miracle 🫶✨</p><button onclick="next()">Next 💌</button></div>
<div class="page"><h2>Love Letter 10 💌</h2><p>Bubu 😎💖 forever yours 😭💍</p><button onclick="next()">Next 💌</button></div>

<!-- 20 GAMES -->
<div class="page"><h2>Game 1 🎮 Who Loves More?</h2><button class="game-btn" onclick="alert('Wrong 😤 Naksh loves MORE 😎💖')">Samridhi</button><button class="game-btn" onclick="alert('Correct 😏💘 Forever Naksh')">Naksh</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 2 🎮 Best Couple?</h2><button class="game-btn" onclick="alert('Correct 💃🕺🔥')">Naksh & Samridhi</button><button class="game-btn" onclick="alert('Nope 😤')">Others</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 3 🎮 Cutest?</h2><button class="game-btn" onclick="alert('Correct 😍🐻 Samuuuuu')">Samridhi</button><button class="game-btn" onclick="alert('Nice try 😎 but Samuuuuu wins')">Naksh</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 4 🎮 More Annoying?</h2><button class="game-btn" onclick="alert('Correct 😤😂 Samuuuuu')">Samridhi</button><button class="game-btn" onclick="alert('Nope 😅')">Naksh</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 5 🎮 Best Dancer?</h2><button class="game-btn" onclick="alert('Both 😍💃🕺')">Both</button><button class="game-btn" onclick="alert('Wrong 😤 Both rule')">One Only</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 6 🎮 Future Together?</h2><button class="game-btn" onclick="alert('Correct 😭💍 Forever Us')">Yes Always</button><button class="game-btn" onclick="alert('Wrong 😏 Try again')">No</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 7 🎮 Who Misses More?</h2><button class="game-btn" onclick="alert('Correct 😭💖 Naksh')">Naksh</button><button class="game-btn" onclick="alert('Nope 😤')">Samridhi</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 8 🎮 Who Is Drama Queen?</h2><button class="game-btn" onclick="alert('Correct 😂🐻 Samuuuuu')">Samridhi</button><button class="game-btn" onclick="alert('Nope 😅')">Naksh</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 9 🎮 Who Starts Fights?</h2><button class="game-btn" onclick="alert('Correct 😤😂 Samuuuuu')">Samridhi</button><button class="game-btn" onclick="alert('Nice try 😎')">Naksh</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 10 🎮 Who Ends Fights?</h2><button class="game-btn" onclick="alert('Correct 😭💖 Naksh')">Naksh</button><button class="game-btn" onclick="alert('Nope 😅')">Samridhi</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 11 🎮 Who Cares More?</h2><button class="game-btn" onclick="alert('Both 😭💖')">Both</button><button class="game-btn" onclick="alert('Wrong 😤')">One Only</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 12 🎮 Who Is More Romantic?</h2><button class="game-btn" onclick="alert('Correct 😎💘 Naksh')">Naksh</button><button class="game-btn" onclick="alert('Nice try 😅')">Samridhi</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 13 🎮 Who Is More Cute?</h2><button class="game-btn" onclick="alert('Correct 😍🐻 Samuuuuu')">Samridhi</button><button class="game-btn" onclick="alert('Nice try 😎')">Naksh</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 14 🎮 Who Is My World?</h2><button class="game-btn" onclick="alert('Correct 😭🌍 Samridhi')">Samridhi</button><button class="game-btn" onclick="alert('Wrong 😤')">Others</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 15 🎮 Who Is My Forever?</h2><button class="game-btn" onclick="alert('Correct 😭💍 Samridhi')">Samridhi</button><button class="game-btn" onclick="alert('Wrong 😤')">Anyone Else</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 16 🎮 Who Is My Valentine?</h2><button class="game-btn" onclick="alert('Correct 😍💖 Samridhi')">Samridhi</button><button class="game-btn" onclick="alert('Wrong 😅')">Someone Else</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 17 🎮 Who Is My Queen?</h2><button class="game-btn" onclick="alert('Correct 👑💖 Samridhi')">Samridhi</button><button class="game-btn" onclick="alert('Nope 😤')">Anyone Else</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 18 🎮 Who Owns My Heart?</h2><button class="game-btn" onclick="alert('Correct 💖🔐 Samridhi')">Samridhi</button><button class="game-btn" onclick="alert('Wrong 😤')">Someone Else</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 19 🎮 Who Is My Parvati?</h2><button class="game-btn" onclick="alert('Correct 😭🌸 Samridhi')">Samridhi</button><button class="game-btn" onclick="alert('Wrong 😅')">Others</button><button onclick="next()">Next ➡️</button></div>
<div class="page"><h2>Game 20 🎮 WILL U MARRY ME ? </h2><button class="game-btn" onclick="alert('Ahhhhhhh U R MINEEEE😭💍')">Yes</button><button class="game-btn" onclick="alert('No option 😤😂')">No</button><button onclick="next()">Final ➡️</button></div>

<div class="page">
<h1>I LOVE YOU SO MUCHHH PANDAA,
 KUTTI,
 KAMINI,
 SAMUUU,
 PARVATI,
 RADHAA JI,
 GOLIII,
 GOLUU MOLUU,
 BHUDHIII,KUCHUU PUCHUUU,HIPPO, U R MINEEEEEEEEEE🐻💖</h1>
<p>Forever yours,<br><b>Naksh 😎💌</b></p>
</div>

<script>
let pages=document.querySelectorAll('.page');
let i=0;
function next(){
  pages[i].classList.remove('active');
  i++;
  pages[i].classList.add('active');
}

const emojis = ["💖","❤️‍🩹","🧿","🥰","💗","🥹","💞","💋"];

setInterval(()=>{
  let h=document.createElement("div");
  h.className="heart";
  h.innerHTML = emojis[Math.floor(Math.random()*emojis.length)];
  h.style.left=Math.random()*100+"%";
  document.body.appendChild(h);
  setTimeout(()=>h.remove(),6000);
},500);
</script>

</body>
</html>
