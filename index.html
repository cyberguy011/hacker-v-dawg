<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HACKER V_DAWG SYSTEM</title>

<style>
*{
    box-sizing:border-box;
}

body{
    margin:0;
    font-family:monospace;
    background:black;
    color:#00ff66;
    overflow:hidden;
}

#matrix{
    position:fixed;
    top:0;
    left:0;
    z-index:0;
}

#login{
    position:absolute;
    width:100%;
    height:100%;
    background:rgba(0,0,0,.95);
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    z-index:5;
}

#login h2{
    text-shadow:0 0 10px #00ff66;
}

input{
    background:black;
    border:1px solid #00ff66;
    color:#00ff66;
    padding:10px;
    margin:10px;
    width:230px;
}

button{
    background:#00ff66;
    color:black;
    border:none;
    padding:10px 20px;
    cursor:pointer;
    font-weight:bold;
}

#boot{
    display:none;
    position:absolute;
    width:100%;
    height:100%;
    background:black;
    z-index:6;
    padding:30px;
}

.boot-text{
    white-space:pre-line;
}

#dashboard{
    display:none;
    position:relative;
    z-index:2;
    max-width:1200px;
    margin:auto;
    padding:20px;
}

h1{
    text-shadow:0 0 10px #00ff66;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    border:1px solid #00ff66;
    background:rgba(0,0,0,.7);
    padding:20px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-5px);
    box-shadow:0 0 20px #00ff66;
}

#cmd{
    width:100%;
    background:black;
    border:1px solid #00ff66;
    color:#00ff66;
    padding:10px;
}

#terminalOutput{
    margin-top:10px;
    min-height:120px;
    white-space:pre-wrap;
}

@media(max-width:700px){
    h1{
        font-size:1.8rem;
    }
}
</style>
</head>

<body>

<canvas id="matrix"></canvas>

<div id="login">
    <h2>ACCESS TERMINAL</h2>
    <input id="user" placeholder="Username">
    <input id="pass" type="password" placeholder="Password">
    <button onclick="login()">LOGIN</button>
</div>

<div id="boot">
    <div class="boot-text" id="bootText"></div>
</div>

<div id="dashboard">

<h1>HACKER V_DAWG SYSTEM</h1>

<p>Welcome back, Operator.</p>

<div class="grid">

<div class="card">
<h3>System Time</h3>
<p id="clock"></p>
</div>

<div class="card">
<h3>Status</h3>
<p id="status">Scanning...</p>
</div>

<div class="card">
<h3>Terminal</h3>
<input id="cmd" placeholder="Type command..." onkeydown="runCommand(event)">
<div id="terminalOutput"></div>
</div>

</div>

<h2>Projects</h2>

<div class="grid">

<div class="card">
<h3>Cyber Notes</h3>
<p>Secure note-taking application built with Python.</p>
</div>

<div class="card">
<h3>Portfolio Website</h3>
<p>Cyber-themed portfolio with Matrix animations.</p>
</div>

<div class="card">
<h3>Termux Toolkit</h3>
<p>Linux and Python utilities for learning.</p>
</div>

<div class="card">
<h3>CyberLab</h3>
<p>Practice scripts and cybersecurity exercises.</p>
</div>

</div>
</div>

<script>
const canvas=document.getElementById("matrix");
const ctx=canvas.getContext("2d");

canvas.width=window.innerWidth;
canvas.height=window.innerHeight;

let letters="01HACKERVDAWG$#@%&Ξ".split("");
const fontSize=14;
const columns=Math.floor(canvas.width/fontSize);
const drops=Array(columns).fill(1);

function drawMatrix(){
    ctx.fillStyle="rgba(0,0,0,.08)";
    ctx.fillRect(0,0,canvas.width,canvas.height);

    ctx.fillStyle="#00ff66";
    ctx.font=fontSize+"px monospace";

    for(let i=0;i<drops.length;i++){
        let text=letters[Math.floor(Math.random()*letters.length)];
        ctx.fillText(text,i*fontSize,drops[i]*fontSize);

        if(drops[i]*fontSize>canvas.height && Math.random()>.975){
            drops[i]=0;
        }

        drops[i]++;
    }
}

setInterval(drawMatrix,33);

function login(){
    let u=document.getElementById("user").value;
    let p=document.getElementById("pass").value;

    if(u && p){
        document.getElementById("login").style.display="none";
        bootSequence();
    }else{
        alert("ACCESS DENIED");
    }
}

function bootSequence(){

    document.getElementById("boot").style.display="block";

    let lines=[
        "Initializing system...",
        "Loading kernel modules...",
        "Checking security...",
        "Loading user profile...",
        "Access granted ✔",
        "Launching dashboard..."
    ];

    let i=0;
    let el=document.getElementById("bootText");

    let interval=setInterval(()=>{

        el.innerHTML+=lines[i]+"\n";

        i++;

        if(i>=lines.length){

            clearInterval(interval);

            setTimeout(()=>{

                document.getElementById("boot").style.display="none";
                document.getElementById("dashboard").style.display="block";
                document.body.style.overflow="auto";

            },1000);

        }

    },700);
}

function updateClock(){
    document.getElementById("clock").innerHTML=
    new Date().toLocaleTimeString();
}

setInterval(updateClock,1000);
updateClock();

setTimeout(()=>{
    let s=document.getElementById("status");
    if(s){
        s.innerHTML="System Secure ✔";
    }
},3000);

function runCommand(e){

    if(e.key!=="Enter") return;

    let cmd=document.getElementById("cmd").value.toLowerCase();
    let out=document.getElementById("terminalOutput");

    if(cmd==="help"){
        out.innerHTML+="help, about, projects, clear<br><br>";
    }
    else if(cmd==="about"){
        out.innerHTML+="Cybersecurity Student & Developer<br><br>";
    }
    else if(cmd==="projects"){
        out.innerHTML+="Cyber Notes, Portfolio, CyberLab, Termux Toolkit<br><br>";
    }
    else if(cmd==="clear"){
        out.innerHTML="";
    }
    else{
        out.innerHTML+="Unknown command<br><br>";
    }

    document.getElementById("cmd").value="";
}

setInterval(()=>{
    document.title=
    Math.random()>.5
    ? "HACKER V_DAWG SYSTEM"
    : "H4CK3R_V_D4WG";
},1500);

window.addEventListener("resize",()=>{
    canvas.width=window.innerWidth;
    canvas.height=window.innerHeight;
});
</script>

</body>
</html>
