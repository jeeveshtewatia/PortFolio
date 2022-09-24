# Portfolio-Project
HTML : 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PortFolio</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="shortcut icon" href="img/css/css.png" type="image/x-icon">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@200&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/a8b026bf60.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="responsive">
    <div id="header">
        <div class="logo">AKASH MEENA</div>
        <input type="checkbox" id="openSidebarMenu">
        <label for="openSidebarMenu" class="sidebarIconToggle">
            <div class="spinner top"></div>
            <div class="spinner middle"></div>
            <div class="spinner bottom"></div>
        </label>
        <div id="sidebarMenu">
            <ul class="menu">
                <li><a href="">Home</a></li>
                <li><a href="">About</a></li>
                <li><a href="">Portfolio</a></li>
                <li><a href="">Resume</a></li>
                <li><a href="">Contact</a></li>
            </ul>
        </div>
    </div>
    <div id="banner">
        <div class="left-side">
            <div class="head-dev">
                <h1>Hi, I am Akash Meena</h1>
                <span class="fron-end-dev">A Front-End Developer</span>
                <p>Get ready to turn ideas into reality</p>
                <input type="submit" class="btn1" value="Hire Me">
                <input type="submit" class="btn2" value="Get Resume">
            </div>
        </div>
        <div class="right-side">
            <img src="img/banner-guy/banner-guy.png" alt="">
        </div>
        <div class="wave">
            <div class="waveWrapper waveAnimation">
                <div class="waveWrapperInner bgTop">
                    <div class="wave waveTop" style="background-image: url('http://front-end-noobs.com/jecko/img/wave-top.png')">
                    </div>
                </div>
                <div class="waveWrapperInner bgMiddle">
                    <div class="wave waveMiddle" style="background-image: url('http://front-end-noobs.com/jecko/img/wave-mid.png')">
                    </div>
                </div>
                <div class="waveWrapperInner bgBottom">
                    <div class="wave waveBottom" style="background-image: url('http://front-end-noobs.com/jecko/img/wave-bot.png')">
                    </div>
                </div>
            </div>
        </div>
    </div>

<!-- <!-ABOUT ME -------------------------------------------->

    <div id="about-Me">
        <div class="abt-left">
            <img src="img/banner-guy/banner-guy@2x.png" width="100%" height="85%" alt="">
        </div>
        <div class="abt-right">
            <span class="pp">About Me</span>
            <p>I'm Web Developer & Full-Stack Developer with 2 years of Professional Experience. I'm intrested in all kinds of visual communication, but my major focus on development part and designing in Web , Mobile & tablets interfaces. I also have skills in other fields like branding, icon dessign and Web development.</p>
            <p>I enjoy turning complex problems into simple, beautifull and intuitive designs. when I'm not pushing pixels, you'll Find me cooking, gardening or working out in the park.</p>
            <div class="road-map">
                <h4>Languages/Library/Technology</h4>
                <div class="boxx">
                    <img src="img/html.png" alt="">
                    <img src="img/css/css.png" alt="">
                    <img src="img/js/js.png" alt="">
                    <img src="img/netlify/netlify.png" alt="">
                    <img src="img/bootstrap.png" alt="">
                    <img src="img/react-native/react-native.png" alt="">
                    <img style="padding-left:25px;" src="img/github/github.png" alt="">
                </div>
            </div>
        </div>
    </div>

    <!-- <!-My Portfolio -------------------------------------------->

    <div class="Mpp">My Portfolio</div>
    <div id="portfolio">
        <div class="items item1"><img src="img/img-1/img-1.png" width="100%" alt=""></div>
        <div class="items item2"><img src="img/img-2/img-2.png" width="100%" alt=""></div>
        <div class="items item3"><img src="img/img-3/img-3.png" width="100%" alt=""></div>
        <div class="items item4"><img src="img/img-4/img-4.png" width="100%" alt=""></div>
        <div class="items item5"><img src="img/img-5/img-5.png" width="100%" alt=""></div>
        <div class="items item6"><img src="img/img-6/img-6.png" width="100%" alt=""></div>
    </div>

    <!-- <!-MyResume -------------------------------------------->

    <div class="Mpp">Resume</div>

    <div id="resume">
        <div class="resume-left">
            <h2>Work Experience</h2>
            <hr>
            <div class="sr-dev">
                <div class="round"></div>
                <div class="sr-dev-text">Senior Fron-End Developer - FULLTIME
                    <input type="button" class="year-btn" value="2022-2023">
                    <p>Facebook,Inc.</p>
                </div>
                <div class="v-line"></div>

                <div class="round"></div>
                <div class="sr-dev-text">Senior Fron-End Developer - FULLTIME
                    <input type="button" class="year-btn" value="2022-2023">
                    <p>Facebook,Inc.</p>
                </div>
                <div class="v-line"></div>
            </div>
            <h2>Education</h2>
            <hr>
            <div class="sr-dev">
                <div class="round"></div>
                <div class="sr-dev-text">Senior Fron-End Developer - FULLTIME
                    <input type="button" class="year-btn" value="2022-2023">
                    <p>Facebook,Inc.</p>
                </div>
                <div class="v-line" style="height: 90px; top: 43%;"></div>
            </div>
        </div>
        <div class="resume-right">
            <div class="innerbox">
                <img src="img/banner-guy/banner-guy.png" width="120%" height="100%" alt="">
            </div>
            <div class="innerbox-second">
                <div class="items2"><img src="img/innderbox-second/skype/skype.png" alt=""></div>
                <div class="items2"><img src="img/innderbox-second/behance/behance.png" alt=""></div>
                <div class="items2"><img src="img/innderbox-second/pinterest/pinterest.png" alt=""></div>
                <div class="items2"><img src="img/innderbox-second/skype/skype.png" alt=""></div>
                <div class="items2"><img src="img/innderbox-second/dribbble/dribbble.png" alt=""></div>
                <!-- <div class="items"><img src="img/innderbox-second/" alt=""></div> -->
            </div>
        </div>
    </div>
    
    <!-- <!-WHAT PEOPLE SAY ABOUT MEE -------------------------------------------->
    
    <div class="Mpp2">What People Say About Me</div>

    <div id="about-Me" class="testimonial">
        <div class="card">
            <img src="img/Tenstimonials/testimonial-img1.png" alt="">
            <h3>PRIYANSHI SHARMA</h3>
            <p>SaveSpace Inc.</p>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora nam impedit nesciunt autem quis voluptatum. Ducimus facere commodi consequatur quae?</p>
        </div>
        <div class="card">
            <img src="img/Tenstimonials/testimonial-img2.png" alt="">
            <h3>MANVENDRA SINGH</h3>
            <p>ScreenApp Inc.</p>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora nam impedit nesciunt autem quis voluptatum.
                Ducimus facere commodi consequatur quae?</p>
        </div>
        <div class="card">
            <img src="img/Tenstimonials/img-3 (1).png" width="60%" style="border-radius:50%;" alt="">
            <h3>SAIRAAM</h3>
            <p>My Travel.com Inc.</p>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora nam impedit nesciunt autem quis voluptatum.
                Ducimus facere commodi consequatur quae?</p>
        </div>
        <div class="view-more-testimonial"><h1 align="center">View More Testimonial</h1></div>
    </div>

        <!--Contact Me -------------------------------------------->
        
        <div class="Mpp">Contact Me</div>

        <div id="contact-us">
            <div class="contact-left">
                <h3>Let's Connect</h3>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Optio praesentium officiis facilis laudantium unde ipsam temporibus maxime laboriosam vel ab! Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure necessitatibus quidem soluta explicabo illo reprehenderit cumque repellendus tempore. Repudiandae, iusto.</p><br><br>
                <img src="img/contact/email/email.png" alt=""> info@mysite.com <br><br>
                <img src="img/contact/phone (1)/phone (1).png" alt=""> +(91)122-345-769 <br><br>
                <img src="img/contact/marker/marker.png" alt=""> PREPBYTES Sector 66,Gurugram,Haryana
            </div>
            <div class="contact-right">
                <h3>Send Me a message</h3>
                <label for="name">First & Last Name  <span style="color:red;">*</span></label>
                <input type="text" class="inpp" placeholder="@Akash Meena">

                <label for="name">Phone Number <span style="color:red;">*</span></label>
                <input type="text" class="inpp" placeholder="1234456789">

                <label for="name">Email adress <span style="color:red;">*</span></label>
                <input type="text" class="inpp" placeholder="@gmail.com">

                <label for="name">Messages<span style="color:red;">*</span></label>
                <textarea name="" class="inpp" id="" cols="30" rows="4" placeholder="Anything Wanna Say!!!"></textarea>
            </div>
        </div>
<div id="footer">©️ Akash Meena. All rights reserved</div>
</div>
</body>
</html>

For CSS : 

body{
    margin: 0%;
    padding: 0%;
    font-family: 'Source Sans Pro', sans-serif;
    background-color: rgba(128, 128, 128, 0.232);
}

#header{
    width: 100%;
    height: 80px;
    /* border: 2px solid #000; */
    /* background-color: #F7F7F7; */
    background-color: #fc950fd5;
}

.logo{
    width: 35%;
    font-size: 2rem;
    color: rgb(42, 101, 42);
    margin-left: 10%;
    font-weight: 900;
    /* border: 1px solid #000; */
    margin-top: 15px;
    display: inline-block;
}
#sidebarMenu{
    margin-right: 5%;
    float: right;
    display: inline-block;
    /* border: 1px solid #000; */
}
#sidebarMenu .menu li{
    padding: 10px;
    display: inline-block;
}
#sidebarMenu .menu li a{
    font-size: 1.3rem;
    color: black;
    font-weight: 600;
    text-decoration: none;
}
#sidebarMenu .menu li a:hover{
    color: rgb(64, 148, 64);
}

input#openSidebarMenu {
    display: none;
}
.sidebarIconToggle{
    display: none;
}


#banner{
    width: 100%;
    /* height: 475px; */
    /* border: 1px solid #000;  */
    background-color: #0e5c55;
    position: relative;
    overflow: hidden;
    /* z-index: -1; */
    /* opacity: 1; */
    animation: banner 2s ease-in-out 0s 1 alternate none;
}
@keyframes banner {
	0% {
		animation-timing-function: ease-in;
		opacity: 0;
		transform: translateY(-250px);
	}

	38% {
		animation-timing-function: ease-out;
		opacity: 1;
		transform: translateY(0);
	}

	55% {
		animation-timing-function: ease-in;
		transform: translateY(-65px);
	}

	72% {
		animation-timing-function: ease-out;
		transform: translateY(0);
	}

	81% {
		animation-timing-function: ease-in;
		transform: translateY(-28px);
	}

	90% {
		animation-timing-function: ease-out;
		transform: translateY(0);
	}

	95% {
		animation-timing-function: ease-in;
		transform: translateY(-8px);
	}

	100% {
		animation-timing-function: ease-out;
		transform: translateY(0);
	}
}
.wave{
    /* background-color: #09BEAD; */
    width: 100%;
    position: absolute;
    bottom: 0%;
    height: 100px;
    /* display: none; */
    /* z-index: -; */
}
@keyframes move_wave {
    0% {
        transform: translateX(0) translateZ(0) scaleY(1)
    }

    50% {
        transform: translateX(-25%) translateZ(0) scaleY(0.55)
    }

    100% {
        transform: translateX(-50%) translateZ(0) scaleY(1)
    }
}

.waveWrapper {
    overflow: hidden;
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
    top: 380px;
    margin: auto;
}

.waveWrapperInner {
    position: absolute;
    width: 100%;
    overflow: hidden;
    height: 100%;
    bottom: -1px;
   
}

.bgTop {
    z-index: 15;
    opacity: 0.5;
}

.bgMiddle {
    z-index: 10;
    opacity: 0.75;
}

.bgBottom {
    z-index: 5;
}

.wave {
    position: absolute;
    left: 0;
    width: 200%;
    height: 100%;
    background-repeat: repeat no-repeat;
    background-position: 0 bottom;
    transform-origin: center bottom;
}

.waveTop {
    background-size: 50% 100px;
}

.waveAnimation .waveTop {
    animation: move-wave 3s;
    -webkit-animation: move-wave 3s;
    -webkit-animation-delay: 1s;
    animation-delay: 1s;
}

.waveMiddle {
    background-size: 50% 120px;
}

.waveAnimation .waveMiddle {
    animation: move_wave 10s linear infinite;
}

.waveBottom {
    background-size: 50% 100px;
}

.waveAnimation .waveBottom {
    animation: move_wave 15s linear infinite;
}
.fron-end-dev{
    color: white;
    font-size: 3rem;
    font-family: 'Roboto', sans-serif;
}
.left-side{
    width: 50%;
    height: 473px;
    /* border: 2px solid #000; */
}
.left-side p{
    margin-top: 60px;
    color: white;
}
.btn1{
    width: 30%;
    padding: 15px;
    border-radius: 15px;
    border: none;
    margin-bottom: 80px;
    color :#FBF3E4;
    font-size: 1.2rem;
    box-shadow: 0px 16px 29px #0BBEAD69;
    background-color: #09BEAD;
    cursor: pointer;
    animation: banner 2s ease-in-out 0s 1 alternate none;
}
.btn1:hover{
    box-shadow: 0px 20px 40px #0BBEAD69;
    color: #000;
    background-color: #23eddc;
}
.btn2{
    width: 30%;
    padding: 15px;
    border-radius: 15px;
    border: none;
    margin-bottom: 80px;
    margin-left: 60px;
    color :#FBF3E4;
    font-size: 1.2rem;
    cursor: pointer;
    background-color: #FCA738;
    box-shadow: 0px 16px 28px #F57F1769;
    animation: banner 2s ease-in-out 0s 1 alternate none;
}
.btn2:hover{
    box-shadow: 0px 20px 40px #f9872369;
    color: #000;
    background-color: #fc950f;
}
.right-side{
    width: 30%;
    /* display: inline-block; */
    position: absolute;
    right: 10%;
    bottom: 0%;
    /* border: 1px solid #000; */
    z-index: 20;
}
.head-dev{
    width: 60%;
    margin: 60px auto;
    /* border: 2px solid #000; */
    color: #FCA738;
    font-size: 1.5rem;
    font-weight: bolder;
}

#about-Me{
    width: 80%;
    /* height: 600px; */
    margin: 50px auto;
    border-radius: 30px;
    /* border: 2px solid #000; */
    box-shadow: 5px 15px 15px grey;
    background-color: #FFFFFF;
    position: relative;
    animation: banner 2s ease-in-out 0s 1 alternate none;
}
.abt-left{
    position: relative;
    width: 50%;
    height: 600px;
    /* border: 1px solid #000; */
    /* border-right: 2px solid; */
    display: inline-block;
    
}
.abt-left img{
    position: absolute;
    bottom: 0%;
    left: 0%;
    /* border: 1px solid #000; */
    /* display: inline-block; */
}
.abt-right{
    width: 50%;
    height: 600px;
    /* border: 1px solid #000; */
    box-sizing: border-box;
    display: inline-block;
    position: absolute;
    top: 0%;
    padding: 30px;
}
.abt-right > .pp{
    width: 30%;
    font-size: 2.5rem;
    display: inline-block;
    padding-top: 15px;
    padding-bottom: 15px;
    font-weight: 800;
    border-bottom: 8px solid #FCA738;
}
.abt-right p{
    font-weight: 600;
    font-size: 1.5rem;
    color: #105652;
}
.road-map{
    width: 90%;
    height: 120px;
    /* border: 1px solid #000; */
    background-color: white;
    border-radius: 15px;
    box-shadow: 5px 10px 10px grey;
    color:orange;
    font-size: 1.2rem;
}
h4{
    margin-top: 10px;
    margin-left: 2%;
}
.boxx{
    width: 100%;
    /* border: 1px solid #000; */
}
.boxx img{
    padding-left: 5%;
}
.Mpp{
    width: 12%;
    text-align: center;
    font-size: 2.5rem;
    display: block;
    margin: 0 auto;
    padding-top: 15px;
    padding-bottom: 15px;
    font-weight: 800;
    border-bottom: 8px solid #FCA738;
}
#portfolio{
    width: 62%;
    margin: 50px auto;
    display: flex;
    flex-wrap: wrap;
    
}

 #resume{
    width: 62%;
    /* border: 1px solid #000; */
    margin: 50px auto;
 }
.items{
    animation: portfolio 5s ease 0s infinite alternate forwards;
    padding-left: 15px;
    /* display: inline-block; */
}
@keyframes portfolio {
	0% {
		transform: translate(0);
	}

	10% {
		transform: translate(-2px, -2px);
	}

	20% {
		transform: translate(2px, -2px);
	}

	30% {
		transform: translate(-2px, 2px);
	}

	40% {
		transform: translate(2px, 2px);
	}

	50% {
		transform: translate(-2px, -2px);
	}

	60% {
		transform: translate(2px, -2px);
	}

	70% {
		transform: translate(-2px, 2px);
	}

	80% {
		transform: translate(-2px, -2px);
	}

	90% {
		transform: translate(2px, -2px);
	}

	100% {
		transform: translate(0);
	}
}

.resume-left{
    width: 58%;
    min-height: 600px;
    padding: 20px;
    /* border: 1px solid #000; */
    display: inline-block;
}
.sr-dev{
    width: 100%;
    /* min-height: 600px; */
    /* border: 2px solid #000; */
    position: relative;
}
.sr-dev-text{
    width: 92%;
    height: 100px;
    color: #105652;
    font-size: 1.5rem;
    font-family: 'Oswald', sans-serif;
    font-weight: bolder;
    padding-left: 1%;
    /* border: 1px solid #000; */
    position: relative;
    top: 50px;
    position: relative;
    top: -26px;
    margin-left: 20px;
}
.sr-dev-text > p{
    font-family: 'Oswald', sans-serif;
    font-size: 1.2rem;
    font-weight: bolder;
}
.year-btn{
    width: 20%;
    border-radius: 100px;
    padding: 10px;
    position: absolute;
    right: 0%;
    background-color: #FCA738;
}
.round{
    width: 19px;
    height: 19px;
    border-radius: 50%;
    background-color: #09BCAB;
    margin-top: 50px;
    margin-left: -10px;
    display: inline-block;
}

.v-line{
    width: 100%;
    height: 250px;
    border-left: 3px solid #09BCAB;
    margin-top: -20px;
    margin-left: -3px;
    position: absolute;
    top: 22%;
    z-index: 20;
}
.resume-right{
    width: 38%;
    height: 720px;
    /* border: 1px solid #000; */
    display: inline-block;
    float: right;
}
.innerbox{
    width: 100%;
    height: 500px;
    float: right;
    box-shadow: 10px 20px 20px gray;
    border-radius: 10px;
    margin-top: 80px;

    background-color: #FFFFFF;
    /* border: 1px solid #000; */
    position: relative;
}
/* .innerbox img{
    position: absolute;
    top: 0%;
    left: 2%;
    border: 1px solid #000;
} */
.innerbox-second{
    width: 100%;
    margin: auto;
    height: 100px;
    background-color: #FFFFFF;
    /* border: 2px solid #000; */
    box-shadow: 10px 20px 20px gray;
    border-radius: 10px;
    z-index: 50;
    margin-top: 640px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}
.items2{
    padding: 20px;
    /* border: 1px solid #000; */
}

/* WHAT PEOPLE SAY ABOUT MEE SECTION*/

.Mpp2{
    width: 25%;
    text-align: center;
    font-size: 2.5rem;
    display: block;
    margin: 0 auto;
    padding-top: 15px;
    padding-bottom: 15px;
    font-weight: 800;
    border-bottom: 8px solid #FCA738;
}

.testimonial{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    /* border: 1px solid #000; */
}
.card{
    margin-top: 40px;
    width: 20%;
    min-height: 350px;
    padding: 20px;
    text-align: center;
    font-size: 1.2rem;
    /* border: 1px solid #000; */
}
.view-more-testimonial{
    width: 100%;
    height: 100px;
    background-color: #FBF3E4;
    /* border: 1px solid #000; */
    /* margin-top: 0px; */
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
    color: #FCA738;
    text-decoration: underline;
}
#contact-us{
    width: 80%;
    height: 800px;
    margin: 50px auto;
    border-radius: 30px;
    /* border: 2px solid #000; */
    box-shadow: 5px 15px 15px grey;
    background-color: #FBF3E4;
    /* position: relative;` */
    margin-bottom: 200px;
}
.contact-left{
    width: 50%;
    height:800px;
    box-sizing: border-box;
    /* border: 1px solid #000; */
    padding: 70px;   
    color: #000;
    font-size:1.2rem;
    display: inline-block;
    position: relative;
    top: -178px;
    background-color: #FFFFFF;
}
.contact-left > h3{
    font-size: 2.2rem;
    color: #105652;
    font-family: 'Oswald', sans-serif;
}
.contact-right{
    width: 49.5%;
    height: 800px;
    /* border: 1px solid #000; */
    position: relative;
    /* top: -295px; */
    display: inline-block;
    font-size: 1.4rem;
    padding: 70px;
    position: relative;
        /* top: -100px; */
    box-sizing: border-box;
}
.contact-right > h3 {
    font-size: 2.2rem;
    color: #105652;
    font-family: 'Oswald', sans-serif;
}
label{
    display: block;
    margin-top: 20px;
}
.inpp{
    width: 80%;
    /* height: 20px; */
    margin-top: 20px;
    font-size: 1.2rem;
    border-radius: 5px;
    border: none;
    border-bottom: 2px solid;
    padding: 10px;
}
textarea{
    resize: none;
}
#footer{
    width: 100%;
    height: 80px;
    background-color: #FBF3E4;
    font-size: 1.7rem;
    line-height: 80px;
    text-align: center;
    color: #000;
    font-weight: 400;
}
.resume-left h2 {
    font-size: 2rem;
}
@media only screen and (min-width:1200px) and (max-width:1650px){
    .right-side{
        margin-right: 200px;
    }
    #banner{
        height: 700px;
    }
    .btn1{
        width: 26%;
    }
    .btn2{
        margin-left: 14%;
        width: 26%;
    }
    .left-side{
        width: 70%;
    }
    .fron-end-dev{
        font-size: 2.2rem;
        /* border: 1px solid #000; */
        width: 80%;
    }
    .left-side p{
        margin-top: 30px;
    }
    #about-Me{
        width: 95%;
        height: 800px;
    }
    .road-map{
        width: 100%;
        height: 140px;
    }
    .boxx img{
        padding: 2%;
        width: 8%;
    }
    .boxx h4{
        margin-left: 0%;
    }
    .abt-right > .pp{
        width: 50%;
    }
    .Mpp{
        width: 20%;
    }
    #portfolio{
        width:97%;
    }
    #resume{
        width: 100%;
    }
    /* .resume-right{
        width: 30%;
    } */
    .innerbox{
        width: 90%;
        float: none;
    }
    .innerbox-second{
        width: 90%;
        margin: 30px auto;
        margin-left: -5px;
    }
    .view-more-testimonial{
        margin-top: 180px;
    }
    .card{
        /* padding-bottom: 0%; */
        padding-left: 100px;
    }
    #contact-us{
        width: 95%;
    }
    .contact-left{
        top: -155px;
    }
    .Mpp2{
        width: 40%;
    }
    #responsive{
        border: 1px solid #000;
        overflow: hidden;
    }
    
}

@media only screen and (min-width:1000px) and (max-width:1199px) {
    body{
        overflow: hidden;
    }
    .right-side {
        margin-right: 200px;
    }

    #banner {
        height: 700px;
        overflow: hidden;
    }

    .btn1 {
        width: 26%;
    }

    .btn2 {
        margin-left: 14%;
        width: 33%;
    }

    .left-side {
        width: 70%;
    }

    .fron-end-dev {
        font-size: 2.2rem;
        /* border: 1px solid #000; */
        width: 80%;
    }

    .left-side p {
        margin-top: 30px;
    }

    #about-Me {
        width: 95%;
        height: 800px;
    }

    .road-map {
        width: 100%;
        height: 140px;
    }

    .boxx img {
        padding: 2%;
        width: 8%;
    }

    .boxx h4 {
        margin-left: 0%;
    }

    .abt-right>.pp {
        width: 50%;
    }

    .Mpp {
        width: 20%;
    }

    #portfolio {
        width: 97%;
        flex-grow: 1;
        justify-content: space-evenly;
    }

    #resume {
        width: 100%
    }
    .resume-left{
        width: 100%;
        display: block;
    }
    .resume-right{
        display: block;
        width: 100%;
    }
    .innerbox{
        width: 90%;
        margin: 10px auto;
        overflow: hidden;
    }
    .innerbox img{
        position: relative;
        right: 100px;
    }
    .innerbox-second{
     position: absolute;
     right: 5%;
    }

    /* .resume-right{
        width: 30%;
    } */
    .innerbox {
        width: 90%;
        float: none;
    }

    .innerbox-second {
        width: 90%;
        margin: 30px auto;
        margin-left: -5px;
        /* float: right; */
        /* float: none; */
        /* margin-top: 30px; */
    }
   .Mpp2{
    width: 45%;
    /* display: inline-block; */
   }
   
    .view-more-testimonial {
        /* margin-top: 180px; */
        position: absolute;
        bottom: 0%;
    }

    .card {
        /* padding-bottom: 0%; */
        padding-left: 100px;
        margin-bottom: 0%;
        padding-bottom: 0%;
    }

    #contact-us {
        width: 95%;
        position: relative;
    }

    .contact-left {
        padding: 5%;
        position: relative;
        top: -19%;
    }
    .inpp{
        width: 90%;
    }
    #responsive{
        border: 1px solid #000;
        overflow: hidden;
    }

}

@media only screen and (min-width:600px) and (max-width:1000px){
#header{
    /* background-color: #FBF3E4; */
    /* border: 1px solid #000; */
}
#sidebarMenu {
    height: 100%;
    position: fixed;
    right: 30px;
    top: 20px;
    width: 250px;
    margin-top: 60px;
    transform: translateX(350px);
    transition: transform 250ms ease-in-out;
    background: rgba(128, 128, 128, 0.333);
    z-index: 100;
}
.menu li {
    border-bottom: 1px solid rgba(255, 255, 255, 0.10);
}
.menu li a {
    display: block;
    padding: 20px;
    text-transform: uppercase;
    font-weight: bold;
    text-decoration: none;
    color: #fff;
}
input#openSidebarMenu {
    display: none;
}
#openSidebarMenu:checked~#sidebarMenu {
    transform: translateX(94px);
}
.sidebarIconToggle {
    display: block;
    height: 22px;
    width: 22px;
    position: absolute;
    z-index: 99;
    top: 10px;
    right: 50px;
    transition: all 0.3s;
    cursor: pointer;
}
.spinner {
    height: 3px;
    background-color: #fff;
    transition: all 0.3s;
}
.spinner.middle,
.spinner.bottom {
    margin-top: 3px;
}
#openSidebarMenu:checked~.sidebarIconToggle>.spinner.middle {
    opacity: 0;
}
#openSidebarMenu:checked~.sidebarIconToggle>.spinner.top {
    transform: rotate(135deg);
    margin-top: 8px;
}
#openSidebarMenu:checked~.sidebarIconToggle>.spinner.bottom {
    transform: rotate(-135deg);
    margin-top: -9px;
}
.logo{
    margin-left: 100px;
}
.left-side {
    /* border: 1px solid #000; */
    width: 100%;display: block;
}
.head-dev{
    width: 100%;
    padding: 20px;
}
.right-side{
    width: 100%;
}
#banner{
    height: 900px;
}
.abt-left{
    display: none;
}
.abt-right{
    width: 100%;
    height: 700px;
    display: block;
    position: static;
}
#about-Me{
    width: 100%;
    border-radius: 0%;
    margin: 0%;
}
.abt-right>.pp{
    width: 30%;
}
.road-map{
    width: 100%;
}
.boxx img{
    padding-left: 4%;
}
.Mpp{
    width: 40%;
    margin-top: 50px;
}
#portfolio{
    width: 100%;
    justify-content: center;
    /* align-items: center; */
    /* padding: 0% 130px; */
    /* border: 1px solid #000; */
}
.items{
    /* width: 100%; */
    margin-bottom: 20px;
}
#resume{
    width: 100%;
    overflow: hidden;
}
.resume-left{
    width: 100%;
    /* border: 1px solid #000; */
    /* margin-left: 50px; */
    display: block;
}
.year-btn{
    display: block;
    margin-top: 20px;
}
.resume-right{
    width: 100%;
}
.innerbox{
    border-radius: 0%;
    background-color: aliceblue;
    /* border: 1px solid #000; */
    background-color: rgba(128, 128, 128, 0.232);
    z-index: 0;
}
.innerbox-second{
    width: 80%;
    /* height: 120px; */
    /* margin-top: 640px; */
    position: static;
    margin-bottom: 20px;
    border: 1px solid #000;
    z-index: 0;
}
.Mpp2{
    width: 80%;
    /* margin-top: 100px; */
}
.testimonial{
    justify-content: space-evenly;
}
#contact-us{
    width: 100%;
    height: 1200px;
    border-radius: 0%;
}
.contact-left{
    width: 100%;
    display: block;
    height: 600px;
}
.contact-right{
    width: 100%;
    height: 1000px;
    display: block;
    position: relative;
    top: -230px;
    padding: 10%;
    margin: 0%;
}
label{
    /* display: none; */
    margin-top: 20px;
}
#responsive{
    border: 1px solid #000;
    overflow: hidden;
}
}

@media only screen and (min-width:350px) and (max-width:599px) {
    .nav {
        /* border: 1px solid #000; */
        width: 100%;
        /* padding: 0%; */
        padding-top: 10px;
        margin: 0%;
        
        /* margin-right: 100px; */
        /* margin-left: 100px; */
    }
    .nav ul{
        padding: 0%;
        margin: 0%;
        padding: 20px 0;
        /* overflow: hidden; */
    }
    .nav ul li a{
        font-size: 1.1rem;
    }

    .logo {
        width: 100%;
        /* overflow: hidden; */
        margin-left: 5px;
    }

    .left-side {
        /* border: 1px solid #000; */
        width: 100%;
        display: block;
    }

    .head-dev {
        width: 100%;
        padding: 5px;
        font-size: 1.4rem;
    }
    .fron-end-dev{
        font-size: 2rem;
    }

    .right-side {
        width: 90%;
        /* border: 1px solid #000; */
    }
    .right-side img{
        position: relative;
        left: -180px;
    }
    .left-side p{
        width: 100%;
    }
    .btn1{
        width: 35%;
    }
    .btn2{
        width: 35%;
    }
    #banner {
        width: 100%;
        height: 900px;
    }

    .abt-left {
        display: none;
    }

    .abt-right{
        width: 100%;
        height: 700px;
        display: block;
        position: static;
    }

    #about-Me {
        width: 100%;
        height: 1100px;
        border-radius: 0%;
        margin: 0%;

    }

    .abt-right>.pp {
        width: 50%;
    }

    .road-map{
        width: 100%;
        height: 200px;
    }
    .boxx{
        display: flex;
        flex-wrap: wrap;
    }
    .boxx img {
        /* width: 10%; */
        padding-top: 15px;
        padding-left: 4%;
    }

    .Mpp {
        width: 60%;
        margin-top: 50px;
    }

    #portfolio {
        width: 100%;
        /* padding: 10px; */
        justify-content: center;
        /* align-items: center; */
        /* padding: 0% 130px; */
        /* border: 1px solid #000; */
    }
    /* .item1{
        width: 40%;
    }
    .item5{
        display: none;
    }
    .item3{
        width: 100%;
        display: none;
    } */

    .items {
        /* border: 3px solid #000; */
        flex: none;
        width: 90%;
        margin-bottom: 20px;
    }

    #resume {
        width: 100%;
        overflow: hidden;
    }

    .resume-left {
        width: 100%;
        /* border: 1px solid #000; */
        /* margin-left: 50px; */
        display: block;
    }

    .year-btn {
        width: 30%;
        display: block;
        margin-top: 20px;
        margin-right:30px;
    }

    .resume-right {
        width: 100%;
    }

    .innerbox{
        border-radius: 0%;
        background-color: aliceblue;
        /* border: 1px solid #000; */
        background-color: rgba(128, 128, 128, 0.232);
        z-index: 0;
    }

    .innerbox-second {
        width: 100%;
        /* height: 120px; */
        /* margin-top: 640px; */
        position: relative;
        top: -40px;
        margin-bottom: 20px;
        border: 1px solid #000;
        z-index: 0;
    }

    .Mpp2 {
        width: 100%;
        display: none;
        /* display: block; */
        /* margin-top: 100px; */
    }

    .testimonial {
        display: none;
    }

    #contact-us {
        width: 100%;
        height: 1100px;
        border-radius: 0%;
        margin: 0%;
    }

    .contact-left {
        width: 100%;
        display: block;
        height: 600px;
        padding: 1%;
    }
    .contact-left h3{
        padding-top: 40px;
        /* border: 1px solid #000; */
        width: 100%;
        
        margin: 0%;
    }

    .contact-right {
        width: 100%;
        /* height:400px; */
        display: block;
        position: relative;
        top: -200px;
        padding: 2%;
        margin: 0%;
    }

    label {
        /* display: none; */
        margin-top: 20px;
    }
    #responsive{
        border: 1px solid #000;
        overflow: hidden;
    }
    #footer{
        font-size: 1rem;
    }
    /* .sidebarIconToggle{
        display:block;
    } */
#sidebarMenu {
    height: 100%;
    position: fixed;
    right: 30px;
    top: 20px;
    width: 250px;
    margin-top: 60px;
    transform: translateX(350px);
    transition: transform 250ms ease-in-out;
    background: rgba(128, 128, 128, 0.333);
    z-index: 100;
}
.menu li {
    border-bottom: 1px solid rgba(255, 255, 255, 0.10);
}
.menu li a {
    color: #fff;
    display: block;
    padding: 20px;
    text-transform: uppercase;
    font-weight: bold;
    text-decoration: none;
}
input#openSidebarMenu {
    display: none;
}
#openSidebarMenu:checked~#sidebarMenu {
    transform: translateX(94px);
}
.sidebarIconToggle{
    display: block;
    height: 22px;
    width: 22px;
    position: absolute;
    z-index: 99;
    top: 10px;
    right: 50px;
    transition: all 0.3s;
    cursor: pointer;
}
.spinner {
    height: 3px;
    background-color: #fff;
    transition: all 0.3s;
}
.spinner.middle,
.spinner.bottom {
    margin-top: 3px;
}
#openSidebarMenu:checked~.sidebarIconToggle>.spinner.middle {
    opacity: 0;
}
#openSidebarMenu:checked~.sidebarIconToggle>.spinner.top {
    transform: rotate(135deg);
    margin-top: 8px;
}
#openSidebarMenu:checked~.sidebarIconToggle>.spinner.bottom {
    transform: rotate(-135deg);
    margin-top: -9px;
}
}

/* @media only screen and (min-width:560px) and (max-width:){
    
} */
