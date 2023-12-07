<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio THIS IS KIRAN</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js"></script>
    <script src="https://kit.fontawesome.com/e94a57fb36.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>
<style>*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    
}
html{
    scroll-behavior: smooth;
}
/*Navbar*/
.navbar{display: flex;
justify-content: right;
align-items: right;
background-color:#2B597E;
position: fixed;
top:0;
width: 100%;
}
.icon{
display: none;
}
.fa {
    font-size: 18px !important;
}
.w3-spin {
    animation: w3-spin 2s infinite linear;
}


.home-btn {
    text-align: right;
    display: none;
}

.Mobile{
    position: fixed;
    display: none;
    list-style: none;
    background-color: blue;
    color: white;
    text-align: center;
    line-height: 1.5;
  
     }
     .phone ul li a {
        text-decoration: none;
        color: white;
        /* padding: 8px 20px; */
    }

.navbar ul{
    display: flex;
    list-style: none;
    margin: 20px;
}
.navbar ul li{
    font-family: century;
    font-size: 1.1rem;
    font-weight: bold;
}
.navbar ul li a{
    text-decoration: none;
    color: white;
    padding: 8px 22px;
    transition: all .5s ease;
}
.navbar ul li a:hover{
    background-color: rgb(202, 209, 245);
    color: black;
    box-shadow: 0 0 10px rgb(10, 10, 10);
}
/*home section */
#home{
display: flex;
flex-direction: column;
background-color: rgba(0, 0, 0, 0.5);
height: 900px;
justify-content: center;
align-items: center;
color: white;
}
#home::before{
    content:"" ;
    position: absolute;
    top: 0;
    right:0;
    background: url("hii.jpg") no-repeat center center/cover;
    height: 900px;
    width:100%;
    z-index: -1;
    opacity: .8;
}
.main{
    display:flex;
    flex-direction: column;
    /*border:1px solid white;*/
    align-items: center;
    /* position:absolute; */
    top:30%;
    right:10%;
}
.heading{
    font-family: century;
    font-size: 3rem;
    text-align: center;
    margin: 40px 0px;

}
.btn{padding: 10px 35px;
background-color: transparent;
border:1px solid white;
color: white;
outline:none;
transition: .6s ease;
}
.btn:hover{
    cursor: pointer;
    background-color: white;
    color: black;
    box-shadow: 0 0 5px white, 0 0 15px white;
    font-weight: bold;
}
/*About section*/
#about{
    display: flex;
    flex-direction: row;
    box-sizing: border-box;
    padding: 50px;
    margin: 50px;
   

}
#pic img{width: 575px;
height: 400px ;
}
#intro{
    display: flex;
    flex-direction: column;
    text-align: justify;
    padding: 10px;
    margin-left: 20px;
    
}
#intro h2{
    font-size: 2rem;
    margin-bottom: 20px;
   

}
.heading{
    align-items:top;
}
/*portfolio section*/
#portfolio{
    display: flex;
    flex-direction:column;
   background-color: rgba(0, 0, 0, 0.9);
 color: white;
 align-items: center;
 padding: 20px;
}
.gallery{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    box-sizing: border-box;
}
.gallery img{
    width: 360px;
    height: 240px;
     margin: 10px;}
    
     /*service section*/
#services {
    display: flex;
    flex-direction: column;
    text-align: center;
    padding: 20px;
    background-color:rgba(211, 203, 203, 0.9);
}

.row {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    box-sizing: border-box;

}

.box{
display: flex;
flex-direction: column;
width: 350px;
height: 450px;
border: 1px solid black;
margin:10px;
align-items: center;
text-align: justify;
padding: 10px;
border-radius:15px;
background: linear-gradient(to top, rgb(255, 45, 45) 50%, white 50%);
background-size: 100% 200%;
transition: all .8s;
}
#pan{
    margin-top: 60px;
}
.box:hover{
    background-position: left bottom;
    color: white;
    border:none;
    box-shadow: 0 0 20px rgb(255, 45, 45);

}
.box img{
    width: 90px;
    height:90px;
    background-color: white;
    padding: 20px;
}

/*contact serives*/
#contact{
    display: flex;
    flex-direction: column;
    box-sizing: border-box;
    background-color: rgba(0, 0, 0, 0.9);
    color: white;
    padding: 20px;
    height: 710px;

}
.form{
    display: flex;
    flex-direction:column;
    box-sizing: border-box;
    align-items: center;
    margin: 20px 0px;

}
.input{
    padding: 12px;
    margin: 15px;
    width:30%;
    border:none;
    outline: none;

}
#msg{
    width:20%;
    padding:10px;
    margin: 15px;
    border: none;
    outline: none;

}
#send:hover{
    cursor: pointer;
    box-shadow:0 0 10px white;
    
}
.centerdiv>a{
    color: white;
    font-size: xx-large;
    
}
.centerdiv{
    display: flex;
    width: 100px;
    gap: 15px;
    align-self: flex-end;
    justify-content: flex-end;


}
.fa-envelope {
    font-size: 35px;
}


a i{
    transition: all 0.3s linear;


}
a:hover i{
    transform: scale(1.4);
}


@media screen and (max-width: 600px) {
    /* STYLES HERE */

    .centerdiv{
 
        position: relative;
        left: 20px;
        gap: 15px;
        align-items: center;
        align-self: center;
        
    
    }
    #about{
        display: block;
 
   
    }
    #pic img {
        width: 400px;}
        .heading {
            
            font-size: 18px;
            font-family: Arial, Helvetica, sans-serif;
        }
       
        .navbar ul li a {
            text-decoration: none;
            color: white;
            padding: 8px 22px;
        }
        .navbar{
            display: none;
    
        }
        
        .icon{
            display: block;
            cursor: pointer;
            color: white;
        }
    
        .display-mobile{
            display: block;
          }
        .Mobile{
            color: white;
            background-color: #00041c;
        }
        .home-btn {
            text-align: right;
            
        }
    
     
               
}
/*navbar*/
.navbar ul{
    flex-wrap: wrap;
    justify-content: center;
}




/*heading*/
.heading{
    font-size: 2.5rem;
}

/*about*/
#pic{
    flex-direction: column;
    align-items: center;
}
#pic img{
    width:475px;
    height:300px;

}
#intro h2{
    text-align: center;
    padding: 10px;
}
/* contact*/
.input{
    width:60%
}
#msg{
    width:55%
}
#send
{
    width:20%
    -webkit-transform: all 0.3s ease-in-out;
}
<body>
   
    <div>
  <nav class="navbar">
          <ul>
        <li><a href="#home" >Home</a></li>
        <li><a href="#about">About me</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
   </nav>
</div>
<div>
    <div onclick="bar()" class="icon"><i class=" fa-solid fa-bars" ></i></div>
    <div class="home-btn">
        <a href="#home" ><p><i class="w3-jumbo w3-spin fa fa-home"></i></p></a>
    </div>
    <nav class="phone">
        <ul id="phn" class="Mobile display-mobile" >
         <li><a href="#home" >Home</a></li>
        <li><a href="#about">About me</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
   </nav>
</div>
<section id="home">
    <div class="main">
    <h1 class="heading"> I AM <br>THELI SAI KIRAN</h1>
<button class="btn">
    Hire me
</button>
    </div>
</section>
<h1 class="heading">ABOUT ME</h1>
<section id="about">
    <div id="pic">
     <img src="hlo.jpg" alt="">
    </div>
        <div id="intro">
        <h2>THIS IS KIRAN</h2>
        <P>Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
            Vitae nobis iusto porro accusantium necessitatibus, 
            repellendus eligendi eum ut explicabo excepturi nam,
             nostrum officia architecto eveniet ipsa maiores corporis dolorem harum.</P>
         </div>    
    </div>
</section>
<section id="portfolio">
    <h1 class="heading">Portfolio</h1>
     <div class="gallery">
        <img src="./MG1.jpg" alt="">
        <img src="./IMG2.jpg" alt="">
        <img src="./IMG3.png" alt="">
        <img src="./IMG4.jpg" alt="">
        <img src="./IMG5.jpg" alt="">
        <img src="./IMG6.jfif" alt="">
        </div>

</section>

<section id="services">
    <h1 class="headings">SERVICES</h1>
    <div class="row">
        <div class="box">
            <img src="./pen.png" alt="">
    <h1 class="headings">Website Design</h1>
    <p id="pan">Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
        Ullam maxime explicabo veritatis fuga tempore velit architecto assumenda autem impedit,
         facilis dignissimos natus consequatur quos soluta maiores molestias corporis dolorem placeat?</p>
         </div>

         <div class="box">
            <img src="./pen3.png" alt="">
            <h1 class="headings">UX/UI  Design</h1>
            <p id="pan">Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
                Ullam maxime explicabo veritatis fuga tempore velit architecto assumenda autem impedit,
                 facilis dignissimos natus consequatur quos soluta maiores molestias corporis dolorem placeat?</p>
                 </div>
                  <div class="box">
                    <img src="./pen1.jfif" alt="">
            <h1 class="headings">Digital Marketing</h1>
            <p id="pan">Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
                Ullam maxime explicabo veritatis fuga tempore velit architecto assumenda autem impedit,
                 facilis dignissimos natus consequatur quos soluta maiores molestias corporis dolorem placeat?</p>
                 </div>
         </div>
</section>
<section id="contact">
    <h1 class="heading">CONTACT</h1>
    <form action="" class="form">
        <input type="text" name="name" class="input" placeholder="Enter Your Name">
        <input type="email" name="emial" class="input" placeholder="Enter Your Email">
        <textarea name="msg" id="msg" cols="30" rows="10" placeholder="Enter Your Message">
        </textarea>
        <input type="submit" value="SEND" id="send">
    </form>
    <div class="centerdiv"> 
        <a href="https://ms-my.facebook.com/saikiran.theli" target="_blank">
            <i class="fa-brands fa-brands-2x  fa-square-facebook"></i>
        </a>
        <a href="https://www.instagram.com/saikiran_theli/?hl=en" target="_blank">
            <i class="fa-brands fa-brands-2x  fa-square-instagram"></i>
        </a>
        <a href="https://twitter.com/theli_saikiran?lang=en" target="_blank">
            <i class="fa-brands fa-brands-2x fa-square-twitter"></i>
        </a>
        <a href="https://www.youtube.com/watch?v=uwJWyBc5j9o" target="_blank">
            <i class="fa-brands fa-brands-2x  fa-square-youtube"></i>
        </a>
        <a href="https://mail.google.com/mail/u/0/?tab=wm#inbox?compose=CllgCHrhTcJLFZMtXnhjBsQDVpTFhFGQzFPrBrNdQxJXHjlHRfVNBVZDhqtpNPHpLwfCXHtqLMg" target="_blank">
            <i class="fa-sharp fa-sharp2x fa-solid fa-square-envelope"></i>
        </a>
    </div>
   



</section>
</style>
</body>
</html>
