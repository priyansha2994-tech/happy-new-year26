<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Main Character Moment 👑</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
html,body{
  margin:0;
  padding:0;
  height:100%;
  background:black;
  overflow:hidden;
  font-family: Arial, sans-serif;
  color:white;
  text-align:center;
}

#screen{
  position:absolute;
  inset:0;
  display:flex;
  justify-content:center;
  align-items:center;
  flex-direction:column;
  z-index:2;
}

.glitch{
  font-size:2rem;
  animation:glitch 0.15s infinite;
}

@keyframes glitch{
  0%{transform:translate(0)}
  25%{transform:translate(-2px,2px)}
  50%{transform:translate(2px,-2px)}
  75%{transform:translate(-1px,-1px)}
  100%{transform:translate(1px,1px)}
}

canvas{
  position:absolute;
  inset:0;
  z-index:1;
}

button{
  padding:14px 28px;
  border-radius:30px;
  border:none;
  background:hotpink;
  font-size:1.1rem;
  cursor:pointer;
}
</style>
</head>

<body>

<canvas id="fireworks"></canvas>

<div id="screen">
  <h1 class="glitch">loading vibes…</h1>
  <p>tap anywhere 👀</p>
</div>

<audio id="music" loop>
  <source src="https://assets.mixkit.co/music/preview/mixkit-new-year-party-1121.mp3" type="audio/mpeg">
</audio>

<script>
const screen = document.getElementById("screen");
const music = document.getElementById("music");

const chaos = [
 "wait—",
 "this kinda fire 🔥",
 "main character detected",
 "emotional damage loading",
 "NO SKIPPING 😤",
 "ok stay with me",
 "you ready?"
];

let i=0;
let interval;

document.body.addEventListener("click", start, {once:true});

function start(){
  music.play();
  interval = setInterval(()=>{
    screen.innerHTML = `<h1 class="glitch">${chaos[i%chaos.length]}</h1>`;
    i++;
  },900);

  setTimeout(finalDrop,7000);
}

function finalDrop(){
  clearInterval(interval);
  screen.innerHTML = `
    <h1>🎆 HAPPY NEW YEAR 🎆</h1>
    <p>
      MAIN CHARACTER ENERGY ONLY 👑<br><br>
      to my favorite humans 💖<br>
      thanks for the chaos, laughs,<br>
      breakdowns & glow-ups fr 🥂<br><br>
      2026 = OUR ERA.<br>
      no debates. no limits.
    </p>
  `;
  startFireworks();
}

/* 🎆 REAL CANVAS FIREWORKS */
const canvas = document.getElementById("fireworks");
const ctx = canvas.getContext("2d");
canvas.width = innerWidth;
canvas.height = innerHeight;

window.onresize = ()=>{
  canvas.width = innerWidth;
  canvas.height = innerHeight;
};

function startFireworks(){
  setInterval(()=>{
    const x = Math.random()*canvas.width;
    const y = Math.random()*canvas.height/2;
    explode(x,y);
  },700);
}

function explode(x,y){
  for(let i=0;i<40;i++){
    particles.push({
      x,y,
      vx:(Math.random()-0.5)*6,
      vy:(Math.random()-0.5)*6,
      life:60,
      color:`hsl(${Math.random()*360},100%,60%)`
    });
  }
}

const particles=[];

function animate(){
  ctx.clearRect(0,0,canvas.width,canvas.height);
  particles.forEach((p,i)=>{
    p.x+=p.vx;
    p.y+=p.vy;
    p.vy+=0.05;
    p.life--;
    ctx.fillStyle=p.color;
    ctx.fillRect(p.x,p.y,3,3);
    if(p.life<=0) particles.splice(i,1);
  });
  requestAnimationFrame(animate);
}
animate();
</script>

</body>
</html># happy-new-year26
