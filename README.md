<!DOCTYPE html>
<html>
<head>
<title>vai casar comigo? iris danielly???</title>
<style>
body {
background-color: #ff0000;
text-align: center;
padding-top: 50px;
}

button {
background-color: #ffffff;
color: #ff0000;
font-size: 24px;
font-weight: bold;
padding: 20px 40px;
border: none;
border-radius: 50px;
cursor: pointer;
margin: 20px;
}

button:hover {
background-color: #ff9999;
color: #ffffff;
}
</style>
</head>
<body>
<h1 style="color: #ffffff;">casa comigo???? quero sua atenção cade voce? responde isso</h1>
<button id="sim">Sim</button>

<button id="nao">Não</button>

<script>
var nao = document.getElementById("nao");
nao.addEventListener("click", function() {
var randomX = Math.floor(Math.random() * window.innerWidth);
var randomY = Math.floor(Math.random() * window.innerHeight);
nao.style.position = "absolute";
nao.style.top = randomY + "px";
nao.style.left = randomX + "px";
});

var sim = document.getElementById("sim");
sim.addEventListener("click", function() {
window.location.href = "URL Q VC QUISER";
});
</script>
</body>
</html>
