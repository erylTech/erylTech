- 👋 Hi, I’m @erylTech
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
\

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navbar</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
    <nav>
        <input type="checkbox" id="check">
        <label for="check" class="checkbtn">
            <i class="fa fa-bars" ></i>
        </label>
        <label class="logo">Eryl_TECH</label>
        <ul>
            <li class="active" ><a href="#">HOME</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">About</a></li>
        </ul>
    </nav>
</body>
</html>


this is css code 


***{
    padding: 0;
    margin: 0;
    text-decoration: none;
    list-style: none;
    box-sizing: border-box;
}

body{
    font-family: 'Times New Roman', Times, serif;
    background: black;
    background-position:center;
    background-repeat: no-repeat;
    background-size:100%;
    background-attachment: fixed;
   
}
nav{
    background-color: rgb(0, 204, 255);
    height: 100px;;
    width: 100%;
position: fixed;
top:0;
}

label.logo{
    color: rgb(0, 0, 0);
    font-size: 40px;
    line-height: 50px;
    padding: 0 40px;
    font-weight: bold;
}

nav ul{
    float: right;
    margin-right: 10px ;
    margin-top: 20px;
}
nav ul li{
    display: inline-block;
    line-height: 40px;
    margin: 0 23px;
    
}
nav ul li a{
    color: rgb(255, 255, 255);
    font-size: 20px;
    text-transform: uppercase;
    font-weight: bold;
}
nav ul li a:hover{
    background:rgb(106, 21, 163);
    transition: .2s;
}
.active a{
    background: rgb(10, 140, 191);
    height: 4.5vh;
    border-radius: 3px;
    padding: 5px;
    
}
.checkbtn{
    font-size: 50px;
    color: rgb(0, 0, 0);
    float: right;
    line-height: 80px;
    margin-right: 20px;
    cursor: pointer;
    display: none;
}
#check{
    display: none;
}
@media(max-width:952px){
    label.logo{
        font-size: 30px;
        padding-left: 50px;
    }
    .drop nav ul li a{
        font-size: 14px;
    }
    .wish{
        display: none;
    }
  }

  @media (max-width:873px){
    body{
        background-image: url(cof.jpg);
        background-repeat: no-repeat;
        background-position: top;
        height: 500%;
    }

    .checkbtn{
        display: block;
    }
    ul{
        position: fixed;
        width: 100%;
        height: 100vh;
        background: #4087ce;
        top: 80px;
        left: -100%;
        text-align: center;
        transition: all .8s;
       
    }
    nav ul li{
        display: block;
        margin: 20px 0;
        line-height: 80px;
    }
    nav ul li a{
     font-size: 20px;;
    }
    a:hover, a.active{
        background: none;
        color: #000000;
        transition: 0.5s ease-in-out;
        cursor: pointer;
    }
    #check:checked~ul {
        left: 0;

    }
}**
