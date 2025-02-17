# harsh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<style>
    body{
        background-image: url(img.jpg) ;
        background-size: cover;
    }
    div{
        height: 230px;
        width: 400px;
        background-color: rgba(0, 0, 0, 0.8);
        margin-top: 280px;
        color: white;
        padding-top: 30px;
        font-size: 20px;
        

    }
    .b1{
        height: 30px;
        width: 260px;
        background-color: green;
        color: white;
    }
    input{
        height: 30px;
        width: 250px;
    }
</style>
</head>
<body>
    <form action="signin.html" method="post">
    <center><div>
        Sign In <br><br>
        <input type="email" name="email" id="email" placeholder="Login ID" required> <br><br>
        <input type="password" name="password" id="password" placeholder="Password" required> <br><br>
        <button class="b1">Sign In</button>
    </div></center>
    </form>
</body>
</html>
