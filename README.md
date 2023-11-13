# Assingment
#  html code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap" rel="stylesheet">


    <title>Document</title>
    <link rel="stylesheet" href="Home.css">
</head>
<body>
    <nav>
        <div class="logo">
            <div >
                <img src="asset/logo.png" alt="logo-image" class="logo-img">
            </div>
            <div class="logo-name">
                LOGO
            </div>
            <div  >
                <ul class="nav-list">
                    <li>Home</li>
                    <li>About</li>
                    <li>Service</li>
                    <li>Portpolio</li>
                    <li>Pricing</li>
                </ul>
            </div>
            <div >
                <button class="button-nav">Connect us</button>
            </div>
        </div>
    </nav>

    <section>
        <div class="left-section">
            <h1 class="body-word">We Help You<br> <span class="crush">Crush </span>Your<br>Competition</h1><br>
            <p class="body-p">
                Build Trust To Connect Your Brand To Bilions Of User and grow your revenue <br>
                throung SEO.
            </p>
            <button class="button-section">See our Service</button>
        </div>
        <div class="right-section">
            <img src="asset/section.png" alt="main-images" class="M-img">
        </div>
    </section>

    <footer>
       <div class="last"> <div class="T_C">
            <h3>Policy | Term and condition</h3>
        </div>
        <div class="mid_footer">
            <h4><span>Disiner</span> | The Website disined by disiner</h4>
        </div>
        <div class="last_footer">
            @ 2020 Disiner.come
        </div>
    </div>
    <p class="para">Lorem ipsum dolor sit amet consectetur adipisicing elit. Et aut non <br>
    asdflkjhasdfhlkjhqperoiu@gmail.com.</p>
    </footer>

</body>
</html>




# CSS code 
*{
    padding: 0;
    margin: 0;
}
body{
    background-color: aliceblue;
    font-family: 'Roboto', sans-serif;
}

/*  star css navigation bar */

nav{
    margin: 30px;
    display: flex;
    justify-content: space-evenly;
    justify-content: space-between;
    
}
.logo{
    display: flex;
}
.logo-img{
    height:45px;
    width: 45px;
    margin: 5px;
    transition: 0.5s;
}
.logo-img:hover{
    height:46px;
    width: 46px;
    margin: 5px;
}
.logo-name{
    font-size: 40px;
    font-weight: 300;

}
ul{
    margin: 9px;
    display: flex;
    justify-content: space-evenly;
    justify-content: space-around;
    font-size: 20px;
    font-weight: 100;
    cursor: pointer;
    justify-content: space-evenly;
    text-indent: none;
    gap:50px;
}
li{
    transition: 0.2s;
}
li:hover{
    font-size:22px ;
    font-weight: 200;
}

.button-nav{
    
    margin-left: 550px;
    height:40px;
    width: 90px;
    background-color: rgb(105, 92, 165);
    font-size: 12px;
    font-weight: 500;
    color: #fff;
    border-radius: 10%;
    align-items: end;
    cursor: pointer;
}
.button-nav:hover{
    background-color: rgb(95, 79, 165);
    height:41px;
    width: 92px;
}

/*  Satrt a section body */

section{
    display: flex;
    justify-content: space-evenly;
    margin-top: 20px;
}
.body-word{
    margin-top: 70px;
    margin-bottom: 0;
    font-size: 70px;
    font-weight: 500;
    color: rgb(75, 6, 118);
}
.crush{
    color: rgb(13, 13, 131);
}
.body-p{
    margin-top: 15px;
    font-size: 20px;
    font-weight: 100;
    color: rgb(142, 142, 150);
}
.button-section{
    margin-top: 40px;
    background-color:rgb(105, 92, 165);
    font-size: 17px;
    font-weight: 500;
    color: #fff;
    border-radius: 6%;
    height:45px;
    width: 150px;
    cursor: pointer;
}
.button-section:hover{
    background-color:rgb(90, 73, 164);
    height:47px;
    width: 153px;
}
.right-section{
    margin:5px;
}
.M-img{
    height: 600px;
    width: 600px;
    border-radius: 5%;
    transition: 0.5s;
    
}
.M-img:hover{
    height: 610px;
    width: 610px;
    border-radius: 5%;
    
}

/* footer section  */

footer{
    margin-top: 150px;
    height: 200px;
    width: auto;
    background-image:url(https://images.pexels.com/photos/3205736/pexels-photo-3205736.jpeg?auto=compress&cs=tinysrgb&w=600);
    background-repeat: 3;
    
    
}
.last{
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    display: flex;
    font-size: 20px;
    color: #fff;
    justify-content: space-between;
    padding: 10px;
    margin-top: 10px;
    gap: 50px;
}
.T_C, .mid_footer, .last_footer{
    margin-top: 10px;
    color:#cce1f0;
    cursor: pointer;
}
.para{
    color:#cae3f4;
    font-size: 20px;
    margin-top: 30px;
    justify-content: center;
    text-align: center;
}



