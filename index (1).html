<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>JAYS 67 MINES 💎</title>

<style>

body{
margin:0;
background:#03060c;
font-family:Arial;
color:white;
text-align:center;
}

h1{
color:#3fa7ff;
text-shadow:0 0 20px #3fa7ff;
}

.panel{
background:#081425;
margin:10px;
padding:15px;
border-radius:15px;
box-shadow:0 0 25px rgba(63,167,255,0.3);
}

button{
padding:12px;
border:none;
border-radius:10px;
background:#0f2a4d;
color:white;
box-shadow:0 0 10px #3fa7ff;
margin:5px;
}

input,select{
padding:12px;
border-radius:10px;
border:none;
margin:5px;
}

.grid{
display:grid;
grid-template-columns:repeat(5,1fr);
gap:10px;
max-width:360px;
margin:auto;
}

.tile{
height:65px;
background:#0f2a4d;
border-radius:14px;
display:flex;
align-items:center;
justify-content:center;
font-size:28px;
cursor:pointer;
transition:0.4s;
}

.tile.flip{transform:rotateY(180deg);}

.diamond{
color:#00c3ff;
text-shadow:0 0 15px #00c3ff;
}

.mine{background:#350000;}

.bar{
height:10px;
background:#111;
border-radius:10px;
overflow:hidden;
margin:10px;
}

.barFill{
height:100%;
background:#00c3ff;
width:0%;
transition:0.3s;
}

.modal{
position:fixed;
top:50%;
left:50%;
transform:translate(-50%,-50%);
background:#081425;
padding:20px;
border-radius:15px;
box-shadow:0 0 25px #3fa7ff;
display:none;
}

</style>
</head>

<body>

<h1>JAYS 67 MINES 💎</h1>

<div class="panel">
Balance: <span id="balance">0</span><br>

<input id="user" placeholder="Username">
<input id="pass" type="password" placeholder="Password">
<button onclick="login()">Login</button>
<button onclick="openDaily()">Daily Rewards 🎁</button>
</div>

<!-- REDEEM CODE UI -->
<div class="panel">
<h3>Redeem Code 🎟️</h3>
<input id="redeemInput" placeholder="Enter Code">
<button onclick="redeemCode()">Redeem</button>
</div>

<div class="panel">
<input id="bet" type="number" placeholder="Bet">
<select id="mineCount">
<option value="3">3 Mines</option>
<option value="5">5 Mines</option>
<option value="7">7 Mines</option>
<option value="10">10 Mines</option>
</select>
<br>

<button onclick="startGame()">START</button>
<button onclick="cashout()">CASHOUT 💰</button>
<button onclick="autoPick()">AUTO PICK 🤖</button>

<br>

Auto Cashout:
<input id="autoCash" type="number" placeholder="2.0">

<p>Multiplier: <span id="multi">1.00</span>x</p>

<div class="bar"><div id="barFill" class="barFill"></div></div>

</div>

<div id="grid" class="grid"></div>

<div id="mineModal" class="modal">
<h2>💥 Mine Hit!</h2>
<button onclick="closeMine()">OK</button>
</div>

<script>

/* ===== 100 RANDOM REDEEM CODES ===== */

const redeemCodes = [
"J67A91","J67B02","J67C33","J67D44","J67E55","J67F66","J67G77","J67H88","J67I99","J67J10",
"J67K21","J67L32","J67M43","J67N54","J67O65","J67P76","J67Q87","J67R98","J67S09","J67T11",
"J67U22","J67V33","J67W44","J67X55","J67Y66","J67Z77","J67AA1","J67BB2","J67CC3","J67DD4",
"J67EE5","J67FF6","J67GG7","J67HH8","J67II9","J67JJ1","J67KK2","J67LL3","J67MM4","J67NN5",
"J67OO6","J67PP7","J67QQ8","J67RR9","J67SS1","J67TT2","J67UU3","J67VV4","J67WW5","J67XX6",
"J67YY7","J67ZZ8","J67A12","J67B23","J67C34","J67D45","J67E56","J67F67","J67G78","J67H89",
"J67I90","J67J01","J67K12","J67L23","J67M34","J67N45","J67O56","J67P67","J67Q78","J67R89",
"J67S90","J67T01","J67U12","J67V23","J67W34","J67X45","J67Y56","J67Z67","J67AAA","J67BBB",
"J67CCC","J67DDD","J67EEE","J67FFF","J67GGG","J67HHH","J67III","J67JJJ","J67KKK","J67LLL",
"J67MMM","J67NNN","J67OOO","J67PPP","J67QQQ","J67RRR","J67SSS","J67TTT","J67UUU","J67VVV"
];

/* ===== GAME LOGIC ===== */

let userName;
let mines=[];
let playing=false;
let multiplier=1;
let betAmount=0;

function getData(){ return JSON.parse(localStorage.getItem("J67_"+userName)); }
function saveData(d){ localStorage.setItem("J67_"+userName,JSON.stringify(d)); }

function updateBalance(){
balance.innerText=getData().balance;
}

function login(){

let u=user.value;
let p=pass.value;

if(!u||!p)return;

let data=JSON.parse(localStorage.getItem("J67_"+u));

if(!data){
data={pass:p,balance:100000,rewardDay:0,lastReward:0,usedCodes:[]};
}

if(data.pass!==p)return alert("Wrong password");

userName=u;
saveData(data);
updateBalance();

}

/* ===== REDEEM SYSTEM ===== */

function redeemCode(){

let code=redeemInput.value.trim();
let d=getData();

if(!redeemCodes.includes(code)){
alert("Invalid code");
return;
}

if(d.usedCodes.includes(code)){
alert("Code already used");
return;
}

d.balance+=1000000;
d.usedCodes.push(code);

saveData(d);
updateBalance();

alert("Redeemed +1,000,000 💎");

}

/* ===== GAME ===== */

function startGame(){

let d=getData();
betAmount=parseInt(bet.value);

if(!betAmount||betAmount>d.balance)return;

d.balance-=betAmount;
saveData(d);
updateBalance();

grid.innerHTML="";
mines=[];
playing=true;
multiplier=1;

multi.innerText="1.00";
barFill.style.width="0%";

let mineAmount=parseInt(mineCount.value);

while(mines.length<mineAmount){
let r=Math.floor(Math.random()*25);
if(!mines.includes(r))mines.push(r);
}

for(let i=0;i<25;i++){
let tile=document.createElement("div");
tile.className="tile";
tile.onclick=()=>pick(i,tile);
grid.appendChild(tile);
}

}

function pick(i,tile){

if(!playing||tile.innerHTML!="")return;

tile.classList.add("flip");

if(mines.includes(i)){
tile.classList.add("mine");
tile.innerHTML="💎";
playing=false;
mineModal.style.display="block";
return;
}

tile.innerHTML="💎";
tile.classList.add("diamond");

multiplier+=0.25;
multi.innerText=multiplier.toFixed(2);

barFill.style.width=(multiplier*10)+"%";

let auto=parseFloat(autoCash.value);
if(auto && multiplier>=auto){
cashout();
}

}

function autoPick(){
let tiles=document.querySelectorAll(".tile");
for(let t of tiles){
if(t.innerHTML==""){ t.click(); break; }
}
}

function cashout(){

if(!playing)return;

let d=getData();
let win=Math.floor(betAmount*multiplier);

d.balance+=win;
saveData(d);
updateBalance();

playing=false;

}

function closeMine(){
mineModal.style.display="none";
}

</script>
</body>
</html>
