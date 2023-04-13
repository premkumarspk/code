# code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width= , initial-scale=1.0">
    <title>Sample Project</title>
    <link rel="stylesheet" href="main.css">
    <link rel="stylesheet" href=" 	https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style> * {
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
    font-family: sans-serif;
}








/*   Nav Link */
.logo{
    width: 25%;
    color: #1691f7;
    font-size: 20px;
    cursor: pointer;

    
}
.logo h1{
    color: #ee6056;
    font-weight: bolder;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
header
{
  
    position: absolute;
    left: 0;
    padding: 0 100px;

    width: 100%;
    box-sizing: border-box;
    background-image: linear-gradient(to right, #f7f6f5, #2c7ef8);

}
header .logo {
    float: left;
    height: 50px;

}

header nav {
    float: right;
}
header nav ul {
    display: flex;
    margin: 0px;
    padding: 0px;
}
header nav ul li {
    list-style-type: none;
    position: relative;
}

header nav ul li a{
    height: 50px;
    line-height: 50px ;
    padding: 0 15px;
    text-decoration: none;
    display: block;
    text-transform: capitalize;
    text-decoration: solid;
    color: rgb(255, 255, 255);
    font-size: 18px;
    text-align: center;

}

 header nav ul li a:hover
 {
    color: rgb(248, 255, 255);
    background-color: #1691f7;
    height: 50px;
    line-height: 50px ;

 }
header nav ul li ul {
    position: absolute;
    left: 0;
    background-color: #1691f7;
    display: none;
    padding: 5px;
}

header nav ul li ul li {
    display: block;
    width: 200px;
    height: fit-content;

}

header nav ul li:hover ul {
    display:block;
    padding: 0px;
}
 header nav ul li .submenu::before{
    content: '';
    position: absolute;

 }
 

 /*    toggle button */
 .menu_toggle
 {
    color: white;
    float:  right;
    line-height: 50px;
    font-size: 20px;
    cursor: pointer;
    display: none;
 }
 @media(max-width:900px){
    header {
        padding: 0 20px;

    }
    .menu_toggle{
        display: block;
    }
    header nav{
        display: none;
        position: absolute;
        width: 100%;
        height: calc (100vh-50px);
        top:50px;
        left: -100%;
        transition: 0.5s;
        background-color: #262626;
    }
    header nav.active{
        left: 0%;
    }
    header nav ul {
        display: block;
        text-align: center;

    }

    .intro_wall{
        display: flex;
        flex-wrap: wrap;

    }
    .intro_wall div{
        width: 100%;
         margin: 0;
   
    }
    .info_box{
        display: flex;
        flex-wrap: wrap;
        flex-direction:column ;
    }
    .info_box div {
        margin-top: 10px;
    }
    .slider {
        display:flex;
        flex-wrap: wrap;
        align-items: center;
    
    }
    .slider img {
        width: 50%;
    }

 }
 
 /* introll Wall paper */

 .intro_wall{
    background-image: linear-gradient(to right, #e0841a, #1de972);
    display:flex ;
    padding: 50px;
    height: fit-content;
 }
 
.intro_wall {
    justify-content: center;
    align-items: center;
}
.intro_wall div
{
    width: 100%;
}


.intro_wall div img {
    width: 100%;
}
 .content{
    box-sizing: border-box;
    line-height: 25px;
    
    padding: 10px;
    color: white;
    text-shadow: #262626, 1px 0.5;
 }
 .content h1 {
    padding: 20px;
 }
 .content p {
    padding-left: 20px;
 }
 .content button{
    justify-content: center;
    padding: 10px;
    border-radius: 25px;
    box-shadow: none;
    background-color: transparent;
    border:1px solid white;
    color: white;
    cursor: pointer;
 }
 .readbtnclass {
    display: flex;
    padding-top: 30px;
    justify-content: space-around;
 }


 /* ----Our Service____----*/
 
 

 .software {
    box-sizing: border-box;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    width: 100%;
    height: 450px;
    padding: 20px;
    justify-content: center;
    align-items: center;
    margin:  0 25px;
 }
 .software img {
    height: 200px;
    width: 300px;
 }
 .info_box {
    padding: 20px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content:space-evenly;
 }
.software:hover{
    cursor: pointer;
   color: #23527c;
}
.info_box> img {
    max-width: 100%;
}

.software button{
    padding: 10px;
    border-radius: 20px;
    background-color: #1691f7;
    border: 1px solid #fff;
    
}
.software button a{
    text-decoration: none;
    color: white;
}


/* cursolel */

.slider img {
    background-color: #ffffff;
    width: 25%;
    cursor: pointer;
    border-radius: 25px;
    box-shadow: #262626 2px;
    padding: 5px;
    margin: 20px;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
.slider{
    background-color: #ffffff;
    padding: 10px;
    display: flex;
    flex-wrap: wrap;
  
    justify-content: space-around;

}

.slider img:hover {
    transition: ease-in .5s;
    width: 280px;
    height:280pxs;
}

/* footer */
footer{
    background-color: #262626;
}
.foot-ser{
    margin: 0px;
    background-color: #262626;
}
footer .foot-ser div{
    background-color: #262626;
    padding:25px;
    margin: 0px;
}

footer h1{
    padding: 30px;
    cursor: pointer;
    font-size: 50px;

}   
.foot-ser ul h3 {
    color: #f7f6f5;
}

.foot-ser div{
    width: 33.3%;
    display: flex;
    float: left;
    height: 220px;
    padding: 25px;
}
.foot-ser div ul  {
    background-color: transparent;
}
.foot-ser div ul  {
    list-style-type: none;
}
.foot-ser div ul li a {
    color: #1de972;
    text-decoration: none;
    
}</style>
</head>
<body>

    
    <!--    #############      NAV BAR   ############-->
<!---   LinkTabS        -->
<header style="  position: fixed;">
    <div class="logo"> 
        <h1 > Hello;) </h1>
        </h1>
    </div>
    <nav class="active">
        <ul>
            <li><a href="main.html" class="active"> Home</a></li>
            <li class="submenu"><a href="#"> service</a>
                <ul>
                    <li><a href="#">Delvelopement </a></li>
                    <li><a href="#"> Maintain</a></li>
                    <li><a href="#"> Testing</a></li>
                    
                </ul>
            </li>
            <li class="submenu"><a href="#"> Technologies</a>
                <ul>
                    <li><a href="#">HTML </a></li>
                    <li><a href="#"> CSS</a></li>
                    <li><a href="#">Javascript</a></li>
                    <li><a href="#">Boostrap</a></li>
                    <li><a href="#">SQL</a></li>
                    <li><a href="#">Java</a></li>
                </ul></li>
                
                <li><a href="#"> Contact</a></li>
                <li><a href="about.html" target="_blank"> About</a></li>
                
            </ul>
        </nav>

</header>
<!--    background images-->
<div class="intro_wall">
<div>

    <img src="./Assets/Software Application.png" min-width="100%" height="auto" alt="images" srcset=""> 
</div>
    <div class="content">
        <h1>Softawre Product Engineering</h1>
        <p>
            Quicker time to Advertise, shorter item lifecycle,ideal usefulness,demonstrated aptitude.redid combination.
        </p>
        <p>We offering amazing item improvement</p>
        <div class="readbtnclass">
            <a href="">

                <button>
                    Read more
                </button>
            </a>
        </div>
    </div>
    </div>
    <div class="container">
        <div  id=" service"class="ourservices">
            <h3 id="h3" style="text-decoration:  5px solid blueviolet underline ; padding: 10px;">
            </blockquote> Our Service</h3>
            <div class="info_box">

                <div class="software">
                    <div class="image">

                        <img src="./Assets/27297-3-software-transparent-image.png" width="100%" alt="">
                    </div>
                    <h3>Development</h3>
                    <p>Business choice happen progressively and any sort of interference with the smooth stream of the business</p>
                    <button>
                        <a href="#"> Read more</a>
                    </button>
                </div>
                <div class="software">
                    <div class="image">

                        <img src="./Assets/2809413.jpg" width="100%" alt="">
                    </div>
                    <h3>Maintain</h3>
                    <p>Business choice happen progressively and any sort of interference with the smooth stream of the business</p>
                    <button> <a href="http://#"> Read more</a>   </button>
                </div>
            <div class="software">
                <div class="image">

                    <img src="./Assets/Wavy_Bus-15_Single-03.jpg"  width="100%" alt="100px">
                </div>
                <h3>Testing</h3>
                <p>We join forces with you past preparing your items advertise. By offering centered Software Testing</p>
                <button> <a href="#"> Read More</a> </button>
            </div>
        </div>
        <div>
            <h1  style="text-decoration:  5px solid blueviolet underline ; padding: 10px;"> Technologies</h1>
        </div>
        <div class="slider">
            <img src="./Assets/pngwing.com.png"  alt="">
            <img src="./Assets/pngwing.com(1).png" alt="" >
            <img src="./Assets/pngwing.com(2).png" alt="">
            <img src="./Assets/pngwing.com(3).png" alt="">
            <img src="./Assets/pngwing.com(4).png" alt="">
            <img src="./Assets/pngwing.com(5).png" alt="">
        </div>
        

</div>
</div>
<!----- footer-->
<footer>

        <h1 style="color:#ee6056; margin: 0px;">Hello ;)</h1>
        <div class="foot-ser">
           <div >

               <ul>
                   <h3>Service</h3>
                   <li><a href="#"> Develope</a></li>
                   <li><a href="#"> Mainatain</a></li>
                   <li><a href="#"> Testing</a></li>
                </ul>
            </div> 
            <div>
                <ul>
                    <h3>Service</h3>
                    <li><a href="#"> HTML</a></li>
                    <li><a href="#"> CSS</a></li>
                <li><a href="#"> Javascript</a></li>
                <li><a href="#"> Boostrap</a></li>
                <li><a href="#"> SQL</a></li>
                <li><a href="#"> Java</a></li>
            </ul>
        </div>
        <div>

            <ul>
                <h3>Quick Links</h3>
                <li><a href="#"> Home</a></li>
                <li><a href="#"> About</a></li>
                <li><a href="#"> logo</a></li>
            </ul>
        </div>
        </div>

    
</footer>
    <script src="https://code.jquery.com/jquery-3.6.4.js" ></script>
    
    
</body>
</html>
