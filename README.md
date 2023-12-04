# THIS-IS-FIRST
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <style>
        body{
            background-image:url("https://images.pexels.com/photos/1135995/pexels-photo-1135995.jpeg?auto=compress&cs=tinysrgb&w=600");
            color:rgb(133, 90, 37);
            background-repeat: no-repeat;
            height:100vh;
            background-size:cover;
            background-position:center;
            align-items:center;
            display:flex;
            justify-content:center;
            align-items:center;
        
        }
        h1{
            font-size:60px;
        }
        
        label{
            font-size:25px;
            display:block;
            margin-bottom:10px;
        }
        div{
            background-color:rgba(255,255,255,0.77);
            border-radius: 10px;
            padding:50px;
            width:400px;
         }
        input[type="text"],input[type="email"],input[type="password"],select,textarea{
            width:90%;
            padding:10px;
            border:none;
            border-radius:5px;
        }
        input:focus, textarea:focus, select:focus{
            background-color:bisque;

        }
        input[type="submit"],
        input[type="reset"]{
        background-color:bisque;
        color:black;
        border-radius:23px;
        }
        input[type="submit"]:hover,
        input[type="reset"]:hover
        {
            cursor:pointer;
            background: black;
            color: bisque;
            text-align: left;
     
        }
        
        
        </style>
</head>
<body>
    <div>
    <form>
        <h1>LOGIN</h1>
        <label for="name">Enter Your Name</label>
        <input type="text" id="name" name="name" placeholder="first name & last name"><br><br>
        <label for="email">Enter Your E-mail</label>
        <input type="email" id="email" name="email" placeholder="Enter your email"><br><br>
        <label for="password">Enter Your Password</label>
        <input type="password" id="password" name="password" placeholder="enter your password"><br><br>
        <input type="submit" value="Login">
        <input type="reset">


    </form>
    </div>
</body>
</html>
