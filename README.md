# web-tabanl-programlama
/*index.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basit Web Sitesi-1</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="navbar">
           <div class="logo">
            <a href="#">LOGO</a>
           </div> 
           <Ul>
            <li><a href="#" class="active">Ana Sayfa</a></li>
            <li><a href="#">Hakkımızda</a></li>
            <li><a href="#">Hizmetler</a></li>
            <li><a href="#">Ürünler</a></li>
            <li><a href="#">İletişim</a></li>
           </Ul>
        </div>
        <div class="center">
            <h1>Basit Web Sitesine</h1>
            <h2>HOŞGELDİNİZ</h2>
            <div class="buttons">
                <button>Daha Fazla...</button>
                <button>Abone Ol</button>
            </div>
        </div>
    </div>

</div>
   
</body>
</html>
/*syle.css
@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@100&display=swap');
*{
    margin:0;
    padding:0;
}

.container{
    background:url(images.jpg);
    height:100vh;
    background-size: 100% 100%;
}
.container .navbar{
    width: 100%;
    height:80px;
    background: rgba(22,112,214,0.4);
}

.navbar.logo{
    display:inline-block;
    margin-left: 50px;
    margin-top:20px;
}

.navbar.logo a {
    text-decoration: none;
    font-size: 30px;
    font-family: sans-serif;
    color: #f3f3f3;

}

.navbar ul{
    float:right;
    margin-right:20px;

}

.navbar ul li{
    list-style:none;
    display:inline-block;
    margin:0 8px;
    line-height: 80px;
}

.navbar ul li a{
    color:white;
    text-decoration: none;
    font-size: 20px;
    padding: 6px 13px;
    font-family: Roboto;
    transition: .5s;
}

.navbar ul li a.active,
.navbar ul li a:hover{
    background: #ff6e00;
    border-radius: 2px;
}
.container.center{
    position:absolute;
    top: 50%;
    left:50%;
    transform:translate(-50%,-50%);
    font-family: sans-serif;
    user-select: none;
}

.center h1{
    color:black;
    font-size: 70px;
    font-weight: bold;
    width: 900px;
    text-align: center;
    margin: 100px;
    margin-left: 300px;
}

.center h2{
    color:#fff;
    font-size:50px;
    font-weight: bold;
    width: 885px;
    margin-top: 10px;
    text-align: center;
    margin: 50px;
    margin-left: 300px;
}

.center .buttons{
    margin-top: 20px;
    margin-left: 370px;
}

.buttons button{
    height: 50px;
    width: 150px;
    font-size: 18px;
    display: inline;
    margin-left: 210px;
    margin-right: -210px;
    font-weight: bold;
    color: #ffb3b3;
    background: rgb(207,96,88);
    border: solid 1px red;
    cursor:pointer;
    outline: none;
    border-radius: 25px;
    transition:.5s;

}

.buttons button:hover{
    background: #fff;
}
