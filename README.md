<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Instagram</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background:#fafafa;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.container{
    width:350px;
}

.login-box{
    background:white;
    border:1px solid #dbdbdb;
    padding:40px;
    text-align:center;
}

.logo img{
    width:90px;
    margin-bottom:10px;
}

.logo h1{
    font-family:cursive;
    font-size:42px;
    margin-bottom:25px;
}

input{
    width:100%;
    padding:10px;
    margin:6px 0;
    border:1px solid #dbdbdb;
    border-radius:3px;
    background:#fafafa;
}

button{
    width:100%;
    padding:10px;
    border:none;
    border-radius:8px;
    background:#0095f6;
    color:white;
    font-weight:bold;
    cursor:pointer;
    margin-top:10px;
}

button:hover{
    background:#1877f2;
}

.or{
    margin:20px 0;
    color:#8e8e8e;
    font-size:14px;
}

.forgot{
    margin-top:15px;
}

.forgot a{
    text-decoration:none;
    color:#00376b;
    font-size:12px;
}

.signup{
    background:white;
    border:1px solid #dbdbdb;
    text-align:center;
    padding:20px;
    margin-top:10px;
}

.signup a{
    text-decoration:none;
    color:#0095f6;
    font-weight:bold;
}
</style>
</head>
<body>

<div class="container">

    <div class="login-box">

        <div class="logo">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
            <h1>Instagram</h1>
        </div>

        <input type="text" placeholder="Phone number, username, or email">
        <input type="password" placeholder="Password">

        <button>Log In</button>

        <div class="or">──────── OR ────────</div>

        <div class="forgot">
            <a href="#">Forgot password?</a>
        </div>

    </div>

    <div class="signup">
        Don't have an account?
        <a href="#">Sign up</a>
    </div>

</div>

</body>
</html># Instagram-login
