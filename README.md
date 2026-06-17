<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Instagram Login Clone</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#fafafa;
    display:flex;
    justify-content:center;
    align-items:center;
    min-height:100vh;
}

.container{
    width:350px;
}

.login-box{
    background:#fff;
    border:1px solid #dbdbdb;
    padding:40px;
    text-align:center;
}

.logo-img{
    width:90px;
    height:auto;
    margin-bottom:10px;
}

.logo-text{
    font-size:55px;
    font-family:cursive;
    color:#000;
    margin-bottom:25px;
}

input{
    width:100%;
    padding:12px;
    margin:6px 0;
    border:1px solid #dbdbdb;
    border-radius:4px;
    background:#fafafa;
    font-size:14px;
}

.login-btn{
    width:100%;
    padding:10px;
    margin-top:12px;
    border:none;
    border-radius:8px;
    background:#0095f6;
    color:white;
    font-weight:bold;
    font-size:15px;
    cursor:pointer;
}

.login-btn:hover{
    background:#1877f2;
}

.or{
    display:flex;
    align-items:center;
    text-align:center;
    margin:20px 0;
    color:#8e8e8e;
    font-size:13px;
    font-weight:bold;
}

.or::before,
.or::after{
    content:"";
    flex:1;
    border-bottom:1px solid #dbdbdb;
}

.or::before{
    margin-right:10px;
}

.or::after{
    margin-left:10px;
}

.forgot a{
    text-decoration:none;
    color:#00376b;
    font-size:12px;
}

.signup{
    background:#fff;
    border:1px solid #dbdbdb;
    text-align:center;
    padding:20px;
    margin-top:10px;
    font-size:14px;
}

.signup a{
    text-decoration:none;
    color:#0095f6;
    font-weight:bold;
}

.footer{
    text-align:center;
    margin-top:20px;
    color:#8e8e8e;
    font-size:12px;
}

@media(max-width:400px){
    .container{
        width:95%;
    }
}
</style>
</head>

<body>

<div class="container">

    <div class="login-box">

        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png"
        alt="Instagram Logo"
        class="logo-img">

        <div class="logo-text">Instagram</div>

        <form>
            <input type="text"
            placeholder="Phone number, username, or email"
            required>

            <input type="password"
            placeholder="Password"
            required>

            <button type="submit" class="login-btn">
                Log In
            </button>
        </form>

        <div class="or">OR</div>

        <div class="forgot">
            <a href="#">Forgot password?</a>
        </div>

    </div>

    <div class="signup">
        Don't have an account?
        <a href="#">Sign up</a>
    </div>

    <div class="footer">
        © 2026 Instagram Clone Project
    </div>

</div>

</body>
</html>
