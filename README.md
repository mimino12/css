@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200&display=swap');
*{



    font-family: 'Montserrat', sans-serif;
}
html
{
    scroll-behavior: smooth;
}
body
{
    background-image:linear-gradient(rgba(0,0,0,0.9),rgba(0,0,0,0.9)),url("davaleba10.html") ;
    background-position:center ;
    background-size: cover;
    background-repeat:no-repeat;
    height:130vh;

}
header
{
    display: flex;
    justify-content: space-between;
    align-items: center;
    height:10vh ;
    width:100%;

    
}
.logo{
    margin-left: 50px;
    margin-top: 50px;
    height: 20px;

}

   
    
.logo img{
   height: 7vh;

}
.logo h3{
    color:rgb(18, 241, 241);
    font-size: 25px;
    margin-top:-35px;
    margin-left: 50px;

}
.nav ul{
    display: flex;

}
.nav ul li{
    list-style: none;


}
.nav ul li a{
    text-decoration: none;
    padding:0px 20px;
    color:rgb(227,238,227);


}

.nav ul li a:hover{
    color:teal;
    font-weight:bolder;

}
.user
{
   cursor: pointer;
   color:teal;
   margin-top:40px;
   margin-right:40px;

}
.user a{
    text-decoration: none;
    color:white;
    background-color: teal;
    border: radius 10px;
    padding:10px 30px;

}
.user a:hover{
    background-color: black;
    color:teal;
    font-weight: bolder;

}
.user i{
    font-size: 20px;
    margin-right: 10px;
    padding:0px 14px;
}
.heropage{
    position: absolute;
    color:white;
    margin-top:100px;
    margin-left:100px;
}
.inside-heropage{
    line-height: 2;

}
.inside-heropage h1{
    font-size: 40px;

}
.inside-heropage p{
    font-size:17px;


}
span{
    color:teal;
    font-weight:bold;
}
.line1{
    height:2px;
    color:rgba(18,241,241);
    width:12%;
    margin: left 0px;
    margin-top:0px;
    

}
.poster{
    margin-top:130px;
    margin-right:150px
}
.poster img{
    height:420px;
    float:right;
    border-radius:10px;
}
.btn1{
    margin-top:30px;

}
.btn1 a{
    text-decoration: none;
    color:white;
    padding:10px 25px;
    background:teal;
    border-radius:20px;

}
.btn1 a:hover{
    background:black;
    color:teal;


}
.btn1 i{
    color:black;
    padding:0px 10px;
}
.latest-movies{
    position: absolute;
    width: 97%;
    height: 100%;
    background-color: black;
    margin-top: 500px;
    padding: 10px 20px;
}
.latest-movies h1{
    font-size: 20px;
    color: teal;

}
.latest-container{
    padding: 10p 0px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 30px;
}
.latest-inside img{
    height: 200px;
    padding:4px;
    cursor:pointer;
    transition: all 500ms ease-in-out;

}
.latest-inside img:hover{
    transform:scale(1.2);
}
.heading1{
    color:white;
    line-height:1.5;

}
.heading1 h4{
    font-size: 15px;

}
.heading1 h6{
    font-size: 12px;

}
.btn2{
    margin-top: -30px;
    margin-left: 150px;

    
}
.btn2 a{
    text-decoration: none;
    font-size: 13px;
    background: teal;
    padding:7px 7px;
    color:white;
    border-radius:10%;



}
.hollywood-movies{
    position: absolute;
    width: 97%;
    height: 100%;
    background-color:black;
    padding: 0px 20px;
    color: white;
    margin-top: 1050px;
    
}
.hollywood-movies h1{
    font-size: 20px;
    color:teal;


}
.hollywood-container{
    margin-top:30px;
    display: flex;
    justify-content: space-between;
    align-items: right;
}
.hollywood-inside h3{
    font-size: 10px;
    font-weight: 500;
    margin-top:6px;

}
.hollywood-inside img{
    height: 290px;
    border-radius: 2px;
    transition:all 500ms ease-in-out;
    

}
.hollywood-inside img:hover{
    transform: scale(1.1);
    cursor: pointer;
}
.imdb{
    background: teal;
    border-radius:60px;
    position: absolute;
    padding: 5px 10px;
    color:white;
    margin-top: -80px;
    margin-left: 120px;
    font-weight: bolder;

}
.more1{
    
   position: absolute;
    margin-top: 1087PX;
    margin-left: 1730px;



}
.more1 a{
    color:teal;
    font-weight:bolder;
    text-decoration:none;
}
.tollywood-movies{
    position: absolute;
    width: 97%;
    height: 100%;
    background-color:black;
    padding: 0px 20px;
    color: white;
    margin-top: 1500px;
}
.tollywood-movies h1{
    font-size: 20px;
    color: teal;
}
.tollywood-container{
    margin-top: 30px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    
    
}
.tollywood-inside img{
    height:300px;
    border-radius: 10px;
    transition: all 500ms ease-in-out;

}
.tollywood-inside h3{
    font-size: 15px;
    font-weight: 500;
    margin-top:6px;
}
.tollywood-inside img:hover{
    transform: scale(1.1);
    cursor: pointer;
}
.more2{
    
    position: absolute;
    margin-top: 1530px;
    margin-left: 1730px;
 
 
 
 }
 .more2 a{
    text-decoration:none;
     color:teal;
     font-weight:bolder;
     
 }
 .collywood-movies{
    position: absolute;
    width: 97%;
    height: 100%;
    background:black;
    padding:0px 20px;
    margin-top: 1950px;

 }
 .collywood-movies h1{
    font-size: 20px;
    color:teal
 }
 .collywood-container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin:30px;


 }
 .collywood-inside img{
    height: 300px;
    border-radius: 10px;
    transition: all 500ms ease-in-out;


 }
 .collywood-inside img:hover{

    transform: scale(1.1);
    cursor: pointer;
 }
.collywood-inside h3{
    color:white;
    font-size: 15px;
    margin-top: 6px;
    
}
.more3{
    position:absolute;
    margin-top: -420px;
    margin-left:1720px
    
}
.more3 a{
    color:teal;
    font-weight: bolder;
    text-decoration: none;

}
.mimino{
    position: absolute;
    height:100%;
    width: 99%;
    background: black;
    color:white;
    margin-top:2500px;
}
.yt-movies{
    padding: 10px 170px;
    line-height: 1.9;
}
.yt-movies h1{
    color:teal;




}
.yt-movies p{
    font-size:25px;
}
.line{
    height:2px;
    background: white;
   
   

}
.yt-container{
    display: flex;
    justify-content: space-between;
    align-items: center;

}
.inside-yt img{
    padding:5px;
    height: 400px;
    border-top-left-radius:100px;
    border-top-left-radius: 100px;
}
.heading2 p{
    font-size: 15px;
}
.like{
    font-size: 15px;
    float: right;
    margin-top: -56px;
}
.youtubebtn{
    position: absolute;
    height: 30%;
    background:black;
    width:99%;
    margin-top:3300px;
    text-align:center ;
}
.youtubebtn a{
    text-decoration: none;
    padding:10px 40px;
    background:teal;
    color: black;
    font-weight: 700;
    border-radius: 4px;
}
.youtubebtn i{
    padding:0px 4px;
    font-size: 19px;
}
    

.scroll{
    position: fixed;
    width: 50px;
    height: 50px;
    background:teal;
    border-radius: 50px;
    bottom: 100px;
    right:50px;
    text-decoration: none;
    font-size: 22px;
    line-height: 50px;
    text-align: center;


}
.scroll i{
    color:black;

}
