# Click-me
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Good Morning ❤️</title>
<style>
    body{
        margin:0;
        font-family:Arial,sans-serif;
        background:linear-gradient(135deg,#ff9ecf,#ffd6e8);
        display:flex;
        justify-content:center;
        align-items:center;
        height:100vh;
        overflow:hidden;
    }
    .card{
        background:white;
        padding:30px;
        border-radius:20px;
        text-align:center;
        box-shadow:0 10px 30px rgba(0,0,0,.2);
        max-width:350px;
    }
    h1{color:#ff4081;}
    p{color:#555;font-size:18px;}
    button{
        background:#ff4081;
        color:white;
        border:none;
        padding:12px 24px;
        border-radius:30px;
        cursor:pointer;
        font-size:16px;
    }
    #message{
        margin-top:20px;
        color:#e91e63;
        font-weight:bold;
        display:none;
    }
</style>
</head>
<body>

<div class="card">
    <h1>🌞 Good Morning, My Love! ❤️</h1>
    <p>I hope your day is as beautiful as your smile.</p>

    <button onclick="showLove()">Tap Me 💖</button>

    <div id="message">
        You are the first thought on my mind every morning. 🌹<br><br>
        Have an amazing day, beautiful! ❤️
    </div>
</div>

<script>
function showLove(){
    document.getElementById("message").style.display="block";
}
</script>

</body>
</html>
