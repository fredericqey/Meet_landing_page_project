# Meet_landing_page_project
Amalitech Project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Red+Hat+Display&display=swap" rel="stylesheet">    
    <link rel="stylesheet" href="desktop.css">
</head>
<body id="body_text">
    <div class="container">
        <img  id="meet"  src="/meet-landing-page/starter-code/assets/logo.svg" alt="">
    </div>
    <!--Group chat for everyone-->
    <div class="everyone">
        <div>
            <img src="/meet-landing-page/starter-code/assets/desktop/image-hero-left.png" alt="">
        </div>
            
        <div>
            <h1 id="heading_text">Group Chat<br> for Everyone</h1>
            <p id="para_text">Meet makes it easy to connect with others face-to-face virtually<br> and collaborate across any device</p>
        </div>

        <div>
            <img src="/meet-landing-page/starter-code/assets/desktop/image-hero-right.png" alt="">
        </div>

    </div>
<!-- Adding Buttons, vertical line and cirle with number inclusive -->
    <section class="section">
        <button id="top_download_button">Download <p class="button1_para">v1.3</p></button>
        <button id="wht_is_it">What is it?</button>
    </section>

    <div class="vertical_line"></div>
    <div class="rounded_line"> 01</div>
<!-- Adding Image Containers for the four images -->
    <div class="img_container">
        <img src="/meet-landing-page/starter-code/assets/desktop/image-woman-in-videocall.jpg"  id="img" alt="">
       
        <img src="/meet-landing-page/starter-code/assets/desktop/image-women-videochatting.jpg" id="img" alt="">
        
        <img src="/meet-landing-page/starter-code/assets/desktop/image-men-in-meeting.jpg" id="img" alt="">
        
        <img src="/meet-landing-page/starter-code/assets/desktop/image-man-texting.jpg" id="img" alt="">
        
    </div>
    <!--Adding box container beneath the images  -->
    <div id="text_container">
        <p class="paragraph_cont"><strong>BUILT FOR MODERN USE</strong></p>
        <h2 class="heading_cont">Smarter Meetings, all <br> in one place</h2>
        <p id="paragraph_cont2">Send messages,share files, show your screen and record your meeting -all in one workspace. Control who can join with  <br>invite only team access ,data encryption and data export.</p>  
    </div>

   
    
    <!-- Adding Footer with Background Image -->
    <footer class="footer_container">
        <!-- <h2 id="mad"><strong>Experience more<br>together</strong></h2>
        <p>Stay connected with reliable HD meetings and unlimited one-on-one and group video sessions.</p> -->
            

    </footer>
    <div class="div_img"></div>
    <!--Adding  Second Vertical Line with number inclusive -->
    <div class="svertical_line"></div>
    <div class="srounded_line"> 02</div>
    
    <div class="on_footer">
        <h2 class="head_footer"><strong>Experience more<br>together</strong></h2>
        <p class="para_footer">Stay connected with reliable HD meetings<br> and unlimited one-on-one and group<br> video sessions.</p>
        <div>
        <button id="download_3">Download v1.3</button>
        </div>
    </div>


</body>
</html>

CSS

/* CSS */
#body_text{
    font-family: 'Red Hat Display', sans-serif;
    /* font-weight: bolder; */
    font-size: 20px;
}
.container{
    position: relative;
    width: 1440px;
    height: 1895px;
    background-color: #fafafa;
   }
#meet{
    position: absolute;
    width: 118.72px;
    height: 28px;
    left: 661px;
    top: 80px;
}
.everyone{
    position: absolute;
    width: 1504px;
    height:358px;
    left:-32px;
    top:169px;
    display: grid;
    grid-template-columns: 1fr 3fr 1fr;
}
#heading_text{
    text-align: center;
    position:absolute;
    top: 69px;
    left:650px;
    line-height: 50px;
    font-weight: 1000px;
    font-size: 45px;
}
#para_text{
    text-align:center;
    position: absolute;
    top:169px;
    left:467px;
    line-height: 42px;
    padding: 10px;
    font-weight: 100 !important;
    color: #87879d;
}
.section{
    position: absolute;
    top: 400px;
    left:530px; 
}
#top_download_button{
    background-color: #4d96a9;
    color:#fff;
    border-radius: 20px;
    position: absolute;
    top:70px;
    left:90px;
    padding-left: 25px;
    padding-right: 50px;
    padding-top: 10px;
    padding-bottom: 10px;
    border:none;
}
#top_download_button:hover{
    background-color: #8fe3f9;
    cursor: pointer;
}
#wht_is_it{
    background-color: #855fb1;
    color:#fff;
    border-radius: 20px;
    position: absolute;
    top:70px;
    left: 240px;
    padding-left: 25px;
    padding-right: 25px;
    padding-top: 10px;
    padding-bottom: 10px;
    white-space: nowrap;
    text-align: center;
    border: none;
}
#wht_is_it:hover{
    background-color: #d9b8ff;
    cursor: pointer;
}
.button1_para{
    position:absolute;
    color: #8fe3f9;
    padding: 0px 5px 5px 0px;
    left:95px;
    top:-3px;
}
.vertical_line{
    height: 110px;
    width: 0.9px;
    background-color: rgba(16, 7, 1, 0.3);
    position: absolute;
    top: 560px;
    left: 724px;
}
.rounded_line{
    position: absolute;
     left: 692px;
    top: 637px;
    background-color: #f3f3f3;
    padding: 20px;
    text-decoration: none;
    border-radius: 50%;
    margin: 4px 2px;
    color:#87879d;
    text-align: center;
    display: inline-block;
    font-size: 16px;
    border-color: #87879d;
}
.img_container{
    display: grid;
	grid-template-columns:auto auto auto auto;
	position: absolute;
	left: 165px;
    top: 841px;
    width: 1110px;
    height: 242px;
    
    
}
#img{
    width: 100%;
	max-width: 250px;
	height: 220px;
	display: inline-block;
	padding: 15px;
	border-radius: 20px;
}
#text_container{
    position: absolute;
    width: 540px;
    height: 240px;
    left: 450px;
    top: 1163px;
}
.paragraph_cont{
    font-family: 'Red Hat Display', sans-serif;
    font-size: 16px;
    line-height: 26px;
    letter-spacing: 4px;
    text-transform: uppercase;
    text-align: center;
    color: #4d96a9;
}
.heading_cont{
    text-align: center;
    font-size: 40px;
    font-weight: bolder;
    line-height: 44px; 
}   
#paragraph_cont2{
    font-size: 18px;
    line-height: 26px;
    text-align: center;
    color: #87879d;
}
.svertical_line{
    height: 110px;
    width: 0.9px;
    background-color: rgba(16, 7, 1, 0.3);
    position: absolute;
    top: 1475px;
    left: 724px;
}
.srounded_line{
    position: absolute;
    left: 692px;
    top: 1550px;
    background-color: #f3f3f3;
    padding: 20px;
    text-decoration: none;
    border-radius: 50%;
    margin: 4px 2px;
    color:#87879d;
    text-align: center;
    display: inline-block;
    font-size: 16px;
    border-color: #87879d;
}
.footer_container{
    position: absolute;
    width: 1440px;
    height: 308px;
    left:0px;
    top: 1587px;
    background-color: #4d96a9;
    background-image: url("/meet-landing-page/starter-code/assets/desktop/image-footer.jpg");
    opacity: 0.9;
    display:flex;
    justify-content:space-between;
}
.div_img{
    position: absolute;
    width: 1440px;
    height: 308px;
    left:0px;
    top: 1587px;
    background-color: #4d96a9;
    opacity: 0.9;
}
.on_footer{
    position: absolute;
    width: 1110px;
    height: 88px;
    left: 165px;
    top:1703px;
    display: flex;
    justify-content: space-between;
}
#download_3{
    background-color: #855fb1;
    border-radius: 30px;
    border: none;
    padding-left: 25px;
    padding-right: 25px;
    padding-top: 10px;
    padding-bottom: 10px;
   
}
#download_3:hover{
background-color: #d9b8ff;
cursor: pointer;
}
.head_footer{
    font-size: 30px;
    margin-top: -2px;
    color: #fafafa;
}
.para_footer{
    margin-top: -2px;
    font-size: 18px;
    color: #fafafa;
}
@media(max-width: 600px){
   footer{
    background-image:url("assets/mobile/image-footer.JPG");
    }
    }
