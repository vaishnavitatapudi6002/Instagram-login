<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Instagram Login</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background:#f2f2f2;
    display:flex;
    justify-content:center;
    align-items:center;
    min-height:100vh;
}

.container{
    width:600px;
    text-align:center;
}

.logo-img{
    width:140px;
    margin-bottom:15px;
}

.logo-text{
    font-size:80px;
    font-weight:900;
    color:#000;
    margin-bottom:35px;
    font-family:cursive;
}

input{
    width:100%;
    padding:18px 20px;
    margin-bottom:22px;
    border:1px solid #d3d3d3;
    border-radius:4px;
    font-size:18px;
    background:white;
}

.login-btn{
    width:100%;
    border:none;
    background:#1696f4;
    color:white;
    padding:18px;
    font-size:22px;
    font-weight:bold;
    border-radius:18px;
    cursor:pointer;
}

.login-btn:hover{
    opacity:0.9;
}

.or{
    display:flex;
    align-items:center;
    justify-content:center;
    margin:35px 0;
    color:#888;
    font-size:20px;
}

.or::before,
.or::after{
    content:"";
    flex:1;
    height:2px;
    background:#999;
}

.or::before{
    margin-right:15px;
}

.or::after{
    margin-left:15px;
}

.forgot{
    text-decoration:none;
    color:#00376b;
    font-size:20px;
}

@media(max-width:700px){

.container{
    width:90%;
}

.logo-text{
    font-size:70px;
}

}
</style>
</head>

<body>

<div class="container">

<img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png"
class="logo-img"
alt="Instagram">

<h1 class="logo-text">Instagram</h1>

<input type="text"
placeholder="Phone number, username, or email">

<input type="password"
placeholder="Password">

<button class="login-btn">
Log In
</button>

<div class="or">OR</div>

<a href="#" class="forgot">
Forgot password?
</a>

</div>

</body>
</html>
