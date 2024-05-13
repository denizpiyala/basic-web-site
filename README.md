# basic-web-site
I created basic web site but that gives little bit CSS error .I will be glad if you help me
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basit Web Sitesi-1</title>
    <link rel="stlesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="navbar">
            <div class="logo">
                <a href="#">LOGO</a>
            </div>
            <ul>
                <li><a href="#" class="active">Ana Sayfa</a></li>
                <li><a href="#">Hakkımızda</a></li>
                <li><a href="#">hizmetler</a></li>
                <li><a href="#">ürünler</a></li>
                <li><a href="#">iletişim</a></li>
            </ul>
        </div>
        <div class="center">
            <h1>Basit Web Sitesi</h1>
            <h2>HOŞGELDİNİZ</h2>
            <div class="button">
                <button>Daha Fazla...</button>
                <button>daha da fazla bilgi</button>
            </div>
        </div>
    </div>


</body>
</html>



@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
*{
    margin:0;
    padding: 0;
}
.container{
    background: url(kahve.jpeg);
    height: 100vh;
    background-size: 100% 100%;
}
.container.navbar{
    width: 100%;
    height:80px;
    background-size: rgba(22,112,214,0.4);
}
.navbar.logo{
    display: inline-block;
    margin-left: 50px;
    margin-top: 20px;
}
.navbar.logo a{
    text-decoration: none;
    font-size: 30px;
    font-family: sans-serif;
    color: antiquewhite;
}

.navbar ul{
    float: right;
    margin: 20px;
}
.navbar ul li{
    list-style: none;
    display: inline-block;
    margin: 0 8px;
    line-height: 80px;
}
.navbar ul li a{
    color: white;
    text-decoration: none;
    font-size: 20px;
    padding: 6px 13px;
    font-family: Roboto;
}
.navbar ul li a.active,
.navbar ul li a:hover{
    background: #ff6;
    border-radius: 2px;

}
.container.center{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%-50%);
    font-family: sans-serif;
    user-select: none;
}

.center h1{
    color: black;
    font-size: 70px;
    font-weight: bold;
    width: 900px;
    text-align: center;
}

.center h2{
    color: white;
    font-size: 50px;
    font-weight: bold;
    width: 885px;
    margin-top: 10px;
    text-align: center;
}

.center.buttons{
    margin: 35px 280px;
}

.buttons button{
    height: 50px;
    width: 150px;
    font-size: 18px;
    font-weight: bold;
    color: aquamarine;
    background: rgb(207, 96, 88);
    border: solid 1px red;
    cursor: pointer;
    outline: none;
    border-radius: 25px;
    transition: none;
}

.buttons button:hover{
    background: #fff;
}

