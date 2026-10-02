
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>For My Favourite Person ❤️</title>

<style>
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
 margin:0;background:#080808;color:white;
 font-family:Arial,sans-serif;overflow-x:hidden
}
.hero{
 min-height:100vh;display:flex;align-items:center;
 justify-content:center;text-align:center;padding:25px;
 background:
 radial-gradient(circle at 50% 20%,#651225 0,#19070d 35%,#080808 70%);
 position:relative;overflow:hidden
}
.hero:before{
 content:"";position:absolute;width:500px;height:500px;
 background:#e50914;filter:blur(160px);opacity:.18;
 border-radius:50%;animation:pulse 4s infinite
}
.content{position:relative;z-index:2;max-width:750px}
.badge{
 display:inline-block;padding:8px 18px;border:1px solid #e50914;
 border-radius:30px;color:#ff6b75;font-size:13px;
 letter-spacing:2px
}
h1{
 font-size:clamp(45px,10vw,95px);margin:20px 0 5px;
 background:linear-gradient(90deg,#fff,#ff3345,#fff);
 background-size:200%;color:transparent;
 background-clip:text;animation:shine 4s linear infinite
}
.subtitle{font-size:clamp(18px,4vw,28px);color:#ddd}
#typing{color:#ff4050;font-weight:bold}
.btn{
 display:inline-block;margin:15px 6px;padding:14px 25px;
 border-radius:30px;text-decoration:none;color:white;
 background:#e50914;box-shadow:0 0 20px #e5091466;
 transition:.3s;cursor:pointer;border:0;font-size:15px
}
.btn:hover{transform:scale(1.08);box-shadow:0 0 35px #e50914}
section{padding:80px 20px;max-width:1000px;margin:auto}
.title{text-align:center;font-size:38px;margin-bottom:35px}
.cards{
 display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));
 gap:20px
}
.card{
 background:linear-gradient(145deg,#171717,#0e0e0e);
 border:1px solid #292929;border-radius:18px;padding:28px;
 text-align:center;transition:.4s
}
.card:hover{
 transform:translateY(-10px);border-color:#e50914;
 box-shadow:0 15px 40px #e5091430
}
.icon{font-size:45px}
.card h3{color:#ff4050}
.message{
 background:linear-gradient(135deg,#18080d,#250b12);
 border-radius:25px;padding:35px;text-align:center;
 border:1px solid #46141d;line-height:1.8;font-size:18px
}
.counter{
 text-align:center;font-size:22px;margin-top:30px
}
.counter span{color:#ff4050;font-weight:bold;font-size:32px}
.surprise{
 text-align:center;padding:45px 20px;border-radius:25px;
 background:#111;border:1px solid #333
}
.hidden{display:none}
#secret{
 margin-top:25px;color:#ff8090;font-size:21px;
 animation:pop .5s ease
}
footer{text-align:center;padding:35px;color:#777}
.heart{
 position:fixed;bottom:-30px;font-size:20px;
 pointer-events:none;animation:float 6s linear forwards;
 z-index:10
}
@keyframes float{
 0%{transform:translateY(0) rotate(0);opacity:0}
 10%{opacity:1}
 100%{transform:translateY(-110vh) rotate(360deg);opacity:0}
}
@keyframes shine{
 to{background-position:200%}
}
@keyframes pulse{
 50%{transform:scale(1.4);opacity:.3}
}
@keyframes pop{
 from{transform:scale(.5);opacity:0}
 to{transform:scale(1);opacity:1}
}
</style>
</head>

<body>

<div class="hero">
 <div class="content">
  <div class="badge">BOYFRIEND'S DAY ❤️</div>

  <h1>My Person.</h1>

  <p class="subtitle">
   You are <span id="typing"></span>
  </p>

  <p>
   One little website for one very special person.
   Because some feelings deserve their own screen. ❤️
  </p>

  <a href="#story" class="btn">Start Watching ▶</a>
  <button class="btn" onclick="hearts()">Send Hearts 💕</button>
 </div>
</div>

<section id="story">
 <h2 class="title">Why You? ❤️</h2>

 <div class="cards">
  <div class="card">
   <div class="icon">🫶</div>
   <h3>My Comfort</h3>
   <p>Somehow talking to you makes ordinary days feel better.</p>
  </div>

  <div class="card">
   <div class="icon">✨</div>
   <h3>My Favourite</h3>
   <p>Out of all the people in this huge world, I'm glad I found you.</p>
  </div>

  <div class="card">
   <div class="icon">🌙</div>
   <h3>My Safe Place</h3>
   <p>You are one of those people I can simply be myself around.</p>
  </div>

  <div class="card">
   <div class="icon">♾️</div>
   <h3>My Always</h3>
   <p>No matter how crazy life gets, you'll always mean something special.</p>
  </div>
 </div>
</section>

<section>
 <h2 class="title">A Little Message 💌</h2>

 <div class="message">
  Happy Boyfriend's Day to the person who makes my
  world a little brighter. ❤️<br><br>

  Thank you for the laughs, the conversations,
  the silly moments and all the memories we've created.
  I hope we keep collecting thousands more.<br><br>

  You don't need to be perfect.
  Just keep being you — that's the person I love having
  in my life. 🫶
 </div>
</section>

<section>
 <h2 class="title">Our Little Timeline ⏳</h2>

 <div class="cards">
  <div class="card">
   <div class="icon">🌱</div>
   <h3>Then</h3>
   <p>Two people who didn't know where their story would go.</p>
  </div>

  <div class="card">
   <div class="icon">💬</div>
   <h3>Somehow</h3>
   <p>Conversations became memories, and memories became something more.</p>
  </div>

  <div class="card">
   <div class="icon">❤️</div>
   <h3>Now</h3>
   <p>Here we are, still writing our little story.</p>
  </div>
 </div>
</section>

<section>
 <h2 class="title">Time Since Our Story Began 🕰️</h2>

 <div class="counter">
  <span id="days">0</span> days
  <br>
  <small>and counting...</small>
 </div>
</section>

<section>
 <div class="surprise">
  <h2>🎁 One Last Thing...</h2>
  <p>There is a secret message waiting for you.</p>

  <button class="btn" onclick="secret()">Open Surprise ❤️</button>

  <div id="secret" class="hidden">
   If I could give you one thing today,
   it would be the ability to see yourself
   through my eyes. ❤️<br><br>
   Happy Boyfriend's Day, idiot. 🫶
  </div>
 </div>
</section>

<footer>
 Made with ❤️ for my favourite person.
</footer>

<script>
const words=[
 "my favourite person ❤️",
 "my comfort 🫶",
 "my happy place ✨",
 "someone very special 💕"
];

let i=0,j=0,deleting=false;

function type(){
 let word=words[i];
 document.getElementById("typing").textContent=
 word.substring(0,j);

 if(!deleting){
  j++;
  if(j>word.length){
   deleting=true;
   setTimeout(type,1200);
   return;
  }
 }else{
  j--;
  if(j===0){
   deleting=false;
   i=(i+1)%words.length;
  }
 }
 setTimeout(type,deleting?45:80);
}
type();

const start=new Date("2025-12-23");
const today=new Date();
const days=Math.floor((today-start)/86400000);
document.getElementById("days").textContent=days;

function secret(){
 document.getElementById("secret").classList.remove("hidden");
 hearts();
}

function hearts(){
 for(let x=0;x<18;x++){
  const h=document.createElement("div");
  h.className="heart";
  h.textContent=["❤️","💕","💗","💖","🫶"][Math.floor(Math.random()*5)];
  h.style.left=Math.random()*100+"vw";
  h.style.animationDuration=(3+Math.random()*4)+"s";
  h.style.fontSize=(15+Math.random()*25)+"px";
  document.body.appendChild(h);
  setTimeout(()=>h.remove(),7000);
 }
}

setInterval(()=>{
 if(Math.random()<.35) hearts();
},3000);
</script>

</body>
</html>
