# salesforce
html code ......

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sales Force</title>
    <link rel="stylesheet" href="style.css">
    <link
    href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css"
    rel="stylesheet"/>
</head>
<body>
    <div id="main"> 
        <div id="header">
            <div id="logo">
                <img src="https://a.sfdcstatic.com/shared/images/c360-nav/salesforce-with-type-logo.svg" alt="">
            </div>
            <div class="text">Products</div>
            <div class="text">Industries</div>
            <div class="text">Costomers</div>
            <div class="text">Learning</div>
            <div class="text">Support</div>
            <div class="text">Company</div>
            <div class="text">Salesforce <i class="ri-add-fill"></i></div>
            <div id="contact">
                <u>contact Us</u>
                <p>1800-420-7332</p>
            </div>
            <div class="icon"><i class="ri-search-line"></i></div>
            <div class="icon"><i class="ri-global-line"></i></div>
            <div id="login"><i class="ri-user-fill"></i> Login</div>
            <div id="try">
                <button>Try For Free</button>
            </div>
        </div>
        <div id="fackheader"></div>
        <div id="page1">
            <div id="stact">
                <img src="https://wp.sfdcdigital.com/en-in/wp-content/uploads/sites/21/2024/09/Dreamforce-2021-Cloud-Logo-RGB-1-2.png?resize=768,151" alt="">
                <h3>Humans with Agents, driving success together.</h3>
                <u>Discover Agentforce</u>
            </div>
            <div id="contact1">
                <div id="poem">
                    <h1>Try Salesforce Starter Suite for free.</h1>
                    <h3>Unite marketing, sales, and service in a single app. Try Salesforce Starter Suite today. There's nothing to install. No credit card required.</h3>
                    <div id="btuns">
                        <div  id="btuns1">Satrt freetrial</div>
                        <div id="btuns2">Watch demo</div>
                    </div>
                </div>
            <div id="box2">
                <img src="https://wp.sfdcdigital.com/en-ap/wp-content/uploads/sites/14/2024/02/php-marquee-starter-lg-bg.jpg?resize=2048,640" alt="">
                
            </div>    
                
            </div>
            <div id="heading">
                <h1>Learn What Salesforce Products Can do for You.</h1>
            </div>
        </div>
        <div id="page2"></div>
    </div>
</body>
</html>


css file....



*{
    margin:0%;
    padding:0%;
    box-sizing: border-box;
}

html,body{
    height: 100%;
    width: 100%;
}
#main{
    width: 100%;
    height: 100%;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    
}
#header{
    width: 100%;
    height: 13%;
    background-color:white;
    position: fixed;
    display: flex;
    align-items: center;
    font-size:large;
}
#fackheader{
    width: 100%;
    height: 13%;
    background-color: aqua;
}
#logo{
    height: 70%;
    margin: 25px;
    margin-left: 35px;
    
}
#logo img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    
}

.text{
    margin: 15px;
    color: rgb(2, 2, 49);
}
.text:hover{
    color: rgb(3, 3, 253);
}
#contact{
    margin-left: 120px ;
    font-weight: lighter;
    color: rgb(2, 2, 55);
    
}
#contact u{
    justify-content: center;
    display: flex;
    
}
#contact u:hover{
   color: blue;
    
}
.icon{
    margin-left: 20px;
    color: rgb(1, 1, 42);
    padding: 10px;
}
.icon:hover{
    color: blue;
    background-color:antiquewhite;
    border-radius: 50%;
}
#login{
    margin: 20px;
    color: rgb(1, 1, 42);
    padding: 10px;
}
#login:hover{
    color: blue;
    background-color:antiquewhite;
    border-radius: 20px;
}
#try{
    margin-left: 20px;
    
       
}
#try button{
    padding: 10px;
    padding-left: 20px;
    padding-right: 20px;
    border-radius: 10px;
    font-size: large;
    color: white;
    background-color: green;
}
#try button:hover{
    background-color: rgb(16, 15, 15);
}
#page1{
    width: 100%;
    height:87% ;
}

#stact{
    width: 100%;
    height: 8%;
    background-color: rgb(2, 2, 54);
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    
}
#stact img{
    height: 70%;
}

#stact h3{
    margin-left: 20px;
}
#stact u{
    margin-left: 20px;
}
#contact1{
    width: 100%;
    height: 80%;
    background-color: white;
    display: flex;
}
#poem{
    width: 50%;
    height: 100%;
    margin: 10px;
}
#poem h1{
    display: flex;
    align-items: center;
    justify-content: center;
    font-size:60px;
    margin: 30px 100px;
}
#poem h3{
    text-align: center;
    margin-left: 80px;
    margin-right: 80px;
    font-weight: 500;
    font-size:x-large;
}
#btuns{
    display: flex;
    
}

#btuns1{
    text-align: center;
    padding: 15px;
    width: 20%;
    margin: 70px;
    border-radius: 10px;
    color: white;
    background-color: rgb(59, 59, 248);
}
#btuns1:hover{
    background-color: rgb(2, 2, 45);
}
#btuns2{
    text-align: center;
    padding: 15px;
    width: 20%;
    margin: 70px;
    border-radius: 10px;
    color: blue;
    border: 1px solid blue;
    
}
#btuns2:hover{
    color: rgb(2, 2, 45);
    border: 1px solid rgb(2, 2, 45);
}
#box2{
    width: 50%;
    height: 100%;
    margin: 10px;
}
#box2 img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    
}


#heading{
    text-align: center;
    font-size: x-large;
    color: blue;
}
