<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>GAME ZONE</title>
<style>
*{box-sizing:border-box}
body{margin:0;background:#101116;color:white;font-family:Arial,sans-serif}
header{height:70px;background:#191b25;display:flex;align-items:center;justify-content:space-between;padding:0 25px;border-bottom:1px solid #30313c}
.logo{font-size:25px;font-weight:bold;color:#8b9dff}
nav{display:flex;gap:10px}
button{cursor:pointer;border:0;border-radius:8px;background:#292c3b;color:white;padding:11px 16px}
button:hover{background:#48517b}
main{max-width:1200px;margin:auto;padding:25px}
.hero{text-align:center;padding:35px 10px}
.hero h1{font-size:42px;margin:5px}
.hero p{color:#a7a9b8}
.search{width:100%;max-width:650px;padding:16px;border-radius:10px;border:1px solid #383b4d;background:#20222e;color:white;font-size:16px;margin-top:20px}
.categories{display:flex;gap:9px;flex-wrap:wrap;margin:20px 0}
.category.active{background:#5966bd}
h2{margin-top:30px}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(165px,1fr));gap:15px}
.game{background:#1e202b;border-radius:12px;overflow:hidden;cursor:pointer;border:1px solid #30313b;transition:.2s}
.game:hover{transform:translateY(-4px);border-color:#7888ff}
.art{height:115px;display:flex;align-items:center;justify-content:center;font-size:55px;background:linear-gradient(135deg,#303b69,#202333)}
.info{padding:13px}
.info strong{display:block;margin-bottom:5px}
.info small{color:#9da3b9}
a{text-decoration:none;color:inherit}
.empty{color:#aaa;display:none;padding:20px}
footer{text-align:center;color:#777;padding:30px}
</style>
</head>
<body>

<header>
<div class="logo">🎮 GAME ZONE</div>
<nav>
<button onclick="showGames()">Home</button>
<button onclick="window.open('https://www.youtube.com','_blank')">YouTube</button>
<button onclick="window.open('https://www.tiktok.com','_blank')">TikTok</button>
</nav>
</header>

<main>
<section class="hero">
<h1>PLAY SOMETHING AWESOME</h1>
<p>Find your next favorite game.</p>
<input class="search" id="search" placeholder="🔎 Search games..." oninput="filterGames()">
</section>

<div class="categories">
<button class="category active" onclick="choose('All',this)">All Games</button>
<button class="category" onclick="choose('Action',this)">Action</button>
<button class="category" onclick="choose('Sports',this)">Sports</button>
<button class="category" onclick="choose('Puzzle',this)">Puzzle</button>
<button class="category" onclick="choose('Arcade',this)">Arcade</button>
<button class="category" onclick="choose('Strategy',this)">Strategy</button>
</div>

<h2 id="heading">All Games</h2>
<div class="grid" id="games"></div>
<div class="empty" id="empty">No games found. Try another search!</div>

<h2>⭐ More Places to Play</h2>
<div class="grid">
<a class="game" href="https://poki.com/" target="_blank">
<div class="art">🎮</div><div class="info"><strong>Poki</strong><small>More browser games</small></div>
</a>
<a class="game" href="https://www.crazygames.com/" target="_blank">
<div class="art">🕹️</div><div class="info"><strong>CrazyGames</strong><small>Explore more games</small></div>
</a>
</div>
</main>

<footer>GAME ZONE • PLAY MORE</footer>

<script>
const games=[
{name:"2048",icon:"🔢",category:"Puzzle",url:"https://play2048.co/"},
{name:"Tetris",icon:"🧱",category:"Puzzle",url:"https://tetris.com/play-tetris"},
{name:"Chess",icon:"♟️",category:"Strategy",url:"https://www.chess.com/play/computer"},
{name:"Slither.io",icon:"🐍",category:"Arcade",url:"https://slither.io/"},
{name:"Agar.io",icon:"🔵",category:"Arcade",url:"https://agar.io/"},
{name:"Paper.io",icon:"📄",category:"Arcade",url:"https://paper-io.com/"},
{name:"Cookie Clicker",icon:"🍪",category:"Arcade",url:"https://orteil.dashnet.org/cookieclicker/"},
{name:"Basketball Stars",icon:"🏀",category:"Sports",url:"https://www.crazygames.com/game/basketball-stars"},
{name:"Soccer Skills",icon:"⚽",category:"Sports",url:"https://www.crazygames.com/t/soccer"},
{name:"Moto X3M",icon:"🏍️",category:"Sports",url:"https://www.coolmathgames.com/0-moto-x3m"},
{name:"Drift Hunters",icon:"🏎️",category:"Sports",url:"https://www.crazygames.com/game/drift-hunters"},
{name:"Crossy Road",icon:"🐔",category:"Arcade",url:"https://poki.com/en/g/crossy-road"},
{name:"Geometry Dash",icon:"🟪",category:"Arcade",url:"https://www.geometrydash.com/"},
{name:"Little Alchemy 2",icon:"🧪",category:"Puzzle",url:"https://littlealchemy2.com/"},
{name:"Fireboy & Watergirl",icon:"🔥",category:"Puzzle",url:"https://www.coolmathgames.com/0-fireboy-and-water-girl"},
{name:"Run 3",icon:"🏃",category:"Action",url:"https://www.coolmathgames.com/0-run-3"},
{name:"Subway Surfers",icon:"🚇",category:"Action",url:"https://poki.com/en/g/subway-surfers"},
{name:"Temple Run 2",icon:"🏃‍♂️",category:"Action",url:"https://poki.com/en/g/temple-run-2"},
{name:"Stickman Hook",icon:"🪝",category:"Action",url:"https://poki.com/en/g/stickman-hook"},
{name:"Minecraft",icon:"⛏️",category:"Action",url:"https://classic.minecraft.net/"},
{name:"Wordle",icon:"🔤",category:"Puzzle",url:"https://www.nytimes.com/games/wordle/index.html"},
{name:"Solitaire",icon:"🃏",category:"Strategy",url:"https://www.solitr.com/"},
{name:"Checkers",icon:"🔴",category:"Strategy",url:"https://www.coolmathgames.com/0-checkers"},
{name:"Pac-Man",icon:"👾",category:"Arcade",url:"https://www.google.com/logos/2010/pacman10-i.html"}
];

let category="All";

function render(){
let q=document.getElementById('search').value.toLowerCase();
let results=games.filter(g=>
(category==="All"||g.category===category)&&
g.name.toLowerCase().includes(q)
);
document.getElementById('games').innerHTML=results.map(g=>`
<a class="game" href="${g.url}" target="_blank" rel="noopener">
<div class="art">${g.icon}</div>
<div class="info"><strong>${g.name}</strong><small>${g.category}</small></div>
</a>`).join('');
document.getElementById('empty').style.display=results.length?'none':'block';
document.getElementById('heading').textContent=category==="All"?"All Games":category+" Games";
}

function choose(c,btn){
category=c;
document.querySelectorAll('.category').forEach(x=>x.classList.remove('active'));
btn.classList.add('active');
render();
}
function filterGames(){render()}
function showGames(){
category='All';
document.getElementById('search').value='';
document.querySelectorAll('.category').forEach(x=>x.classList.remove('active'));
document.querySelector('.category').classList.add('active');
render();
}
render();
</script>
</body>
</html>
