<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>Good Morning, Priyanka ❤️</title>  
  
<style>  
*{margin:0;padding:0;box-sizing:border-box;}  
body{  
    font-family:Arial,sans-serif;  
    background:linear-gradient(135deg,#ff7eb3,#ff758c,#ffd3a5);  
    height:100vh;  
    display:flex;  
    justify-content:center;  
    align-items:center;  
    overflow:hidden;  
}  
.card{  
    width:90%;  
    max-width:420px;  
    background:#fff;  
    padding:30px;  
    border-radius:25px;  
    text-align:center;  
    box-shadow:0 15px 35px rgba(0,0,0,.2);  
}  
h1{color:#ff4081;margin-bottom:10px;}  
p{font-size:18px;color:#555;line-height:1.6;}  
button{  
    margin-top:20px;  
    padding:12px 28px;  
    border:none;  
    border-radius:30px;  
    background:#ff4081;  
    color:#fff;  
    font-size:18px;  
    cursor:pointer;  
}  
#love{  
    display:none;  
    margin-top:20px;  
    color:#e91e63;  
    font-size:20px;  
    animation:fade 1s ease;  
}  
@keyframes fade{  
from{opacity:0;transform:translateY(20px);}  
to{opacity:1;transform:translateY(0);}  
}  
.heart{  
    position:absolute;  
    color:#ff4081;  
    animation:float 6s linear infinite;  
}  
@keyframes float{  
0%{transform:translateY(100vh) scale(.5);opacity:0;}  
20%{opacity:1;}  
100%{transform:translateY(-120vh) scale(1.4);opacity:0;}  
}  
</style>  
</head>  
  
<body>  
  
<div class="card">  
<h1>🌞 Good Morning, Priyanka ❤️</h1>  
  
<p>  
Every morning feels brighter because you exist.  
I hope today brings you happiness, success, and countless reasons to smile.  
</p>  
  
<button onclick="showLove()">Tap Here 💖</button>  
  
<div id="love">  
❤️ Dear Priyanka ❤️<br><br>  
  
You are the first thought on my mind every morning and the last before I sleep.  
Thank you for making my life more beautiful.  
  
Have a wonderful day, my love. 🌸☀️  
  
<br><br>  
Forever yours,<br>  
<b>Ankumar ❤️</b>  
</div>  
</div>  
  
<script>  
function showLove(){  
    document.getElementById("love").style.display="block";  
}  
for(let i=0;i<25;i++){  
    let h=document.createElement("div");  
    h.className="heart";  
    h.innerHTML="❤";  
    h.style.left=Math.random()*100+"vw";  
    h.style.fontSize=(15+Math.random()*25)+"px";  
    h.style.animationDuration=(4+Math.random()*4)+"s";  
    h.style.animationDelay=Math.random()*5+"s";  
    document.body.appendChild(h);  
}  
</script>  
  
</body>  
</html>  
