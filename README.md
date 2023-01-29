# Moving-Particles

//HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="particles.css">
    <title>Moving Particles</title>
</head>
<body>
    <div class="logo">Welcome</div>
    <div class="welcome">
    
    <h1>Moving Particles</h1>
    <p>I Love Web Development. <br>Click below to see my other projects.</p>
    <a href="https://github.com/rammohanpatel">GITHUB</a>

    </div>
    <div id="particles-js">
      <script src="particles.js"></script> 
      <script src="app.js"></script> 

    </div>
</body>
</html>

//CSS

*{
    margin: 0;
    padding: 0;
}

#particles-js{
    background-image: linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)),url(images/space.jpg);
    height: 100vh;
    background-size: cover;
    background-position: center;
}
.logo{
    margin-left: 5%;
    margin-top: 100px;
    position:absolute;
    color: #fff;
    font-size: 50px;
    font-family: 'Times New Roman', Times, serif;
}
.welcome{
      margin-left: 5%;
      position: absolute;
      color: #fff;
      font-family: sans-serif;
}
.welcome h1{
    margin-top: 300px;
    letter-spacing: 2px;
    font-size:42px ;
    text-transform:uppercase ;

}
.welcome p{
    margin-top: 10px;
    font-size: 20px;
}
.welcome a{
    background-color: #dccc1d;
    color: black;
    text-decoration: none;
    letter-spacing: 2px;
    position: fixed;
    margin-top: 30px;
    padding: 15px 20px;
    border-radius: 15px;
}
