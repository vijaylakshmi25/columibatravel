# columibatravel

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Columbia Travels</title>
    <link href="https://fonts.googleapis.com/css?family=Montserrat:100,200,300,400,500,600,700&display=swap"
        rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Playfair+Display:400,500,600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
</head>

<body>
    <div id="back">
        <video src="back.mp4" autoplay loop muted></video>
        <div id="nav">
            <h3 id="logo"><span id="bold">Columbia</span> Travels</h3>
            <div id="linksnsearch">
                <div id="searchfield">
                    <i class="fa fa-search"></i>
                    <input type="text">
                </div>
                <button>Get Quotation Now</button>
            </div>
        </div>
        <div id="main">
            <h5>Lorem ipsum dolor sit.</h5>
            <h1>Candolim Beach</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing.</p>
            <hr>
            <div id="searchbar">
                <i class="fa fa-search"></i>
                <input type="text" placeholder="Search For Places">
            </div>
        </div>
        <div id="bottomright">
            <h3>Current Offers</h3>
            <div id="offers">
                <div class="offer"></div>
                <div class="offer"></div>
            </div>
            <h3>Most Visited Places</h3>
            <div id="places">
                <div class="place">
                    <div class="image"></div>
                    <h4>Kashmiri Ghati</h4>
                </div>
                <div class="place">
                    <div class="image"></div>
                    <h4>Kashmiri Ghati</h4>
                </div>
            </div>
        </div>
    </div>

    <div id="body">
        <div class="container">
            <h1>The <span id="text-effect">Scotland</span> of <span id="bold">India</span>.</h1>
            <div id="collage">
                <div class="left">
                    <div id="leftIcon">
                        <i class="fa fa-arrow-left"></i>
                    </div>
                </div>
                <div class="right">
                    <div class="card">
                        <div id="headerofcard">
                            Reviews By Our Users
                        </div>
                        <div id="callouts">
                            <div class="callout">
                                <div class="userimg"></div>
                                <div class="rvw">
                                    <div class="arrow"></div>
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nulla necessitatibus
                                    officiis, totam, eos corporis doloribus nostrum cumque amet illum beatae
                                    reprehenderit doloremque maiores!
                                </div>
                            </div>
                            <div class="callout">
                                <div class="userimg"></div>
                                <div class="rvw">
                                    <div class="arrow"></div>
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nulla necessitatibus
                                    officiis, totam, eos corporis doloribus nostrum cumque amet illum beatae
                                    reprehenderit doloremque maiores!
                                </div>
                            </div>
                            <div class="callout">
                                <div class="userimg"></div>
                                <div class="rvw">
                                    <div class="arrow"></div>
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nulla necessitatibus
                                    officiis, totam, eos corporis doloribus nostrum cumque amet illum beatae
                                    reprehenderit doloremque maiores!
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
   
    <div id="destinationplan">
        <div id="destleft">
            <div id="dlfone">
                <h1>07</h1>
                <h1>plan your next vacation</h1>
            </div>
            <div id="dlftwo">
                <div id="upndownarrows">
                    <i class="fa fa-arrow-up"></i>
                    <i class="fa fa-arrow-down"></i>
                </div>
                <div id="choose">
                    <h5>Choose</h5>
                    <h3>Your Destination</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing.</p>
                </div>
            </div>
        </div>
        <div id="destright">
            <div id="circle">
                <div id="bigcircle">
                    <div id="image"></div>
                    <div id="targetwgrdnt">
                        <i class="fa fa-map"></i>
                    </div>
                </div>
                <div class="small" id="s-one"></div>
                <div class="small" id="s-two"></div>
            </div>
        </div>
    </div>

    <div id="mountain">
        <img id="backimg" src="backmountain.jpg" alt="">
        <img id="clouds" src="cloud_PNG4.png" alt="">
        <h1 id="heading">69&deg; Nord</h1>
        <img id="mountainpiece" src="mountain_PNG16.png" alt="">
    </div>

    <div id="footer">
        <h2>Columbia Travels</h2>
        <p>&copy; 2017 - 2019</p>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/2.1.3/TweenMax.min.js"
        integrity="sha256-lPE3wjN2a7ABWHbGz7+MKBJaykyzqCbU96BJWjio86U=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.7/ScrollMagic.min.js"
        integrity="sha256-2p2tRZlPowp3P/04Pw2rqVCSbhyV/IB7ZEVUglrDS/c=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.7/plugins/animation.gsap.min.js"
        integrity="sha256-+9YNuItWuR4sbqeaNiJOxG0BvptYz4fbUXbIZoH5Jwo=" crossorigin="anonymous"></script>

    <script>
        var ctrlr = new ScrollMagic.Controller()

        var tl = new TimelineMax();
        tl.fromTo('#mountain #backimg', 2, {
                top: '50%',
                scale: 1.1
            }, {
                top: '30%',
                scale: 1,
                ease: Expo.easeInOut
            }, 'first')
            .fromTo('#mountain #clouds', 2, {
                bottom: 0,
                scale: 1.2
            }, {
                bottom: '90%',var bottom = document.querySelector('#bottom');
var guess = document.querySelector('#guess');
var timer = document.querySelector('#timer');
var score = document.querySelector('#score');

var timerValue = 60;
var currentscore = 0;

function getScoreWorking(){
    currentscore = currentscore + 10;
    score.textContent = currentscore;
}

function getANewGuessNumber(){
    var random = Math.floor(Math.random() * 10);
    guess.textContent = random;
}

function makeTimerWork(){
    setInterval(function(){
        if(timerValue > 0){
            --timerValue;
            timer.textContent = timerValue;
        }
        else{
            bottom.innerHTML = '<h1 class="center">Game Over</h1>';
        }
    }, 1000);    
}

function makeBubbles(){
    for(var i = 0; i<80; i++){
        var random = Math.floor(Math.random() * 10);
        bottom.innerHTML += `<div class="bubble">${random}</div>`;
    }
}


bottom.addEventListener('click', function(dets){
    var ispeclickhua = dets.target.textContent;
    if(ispeclickhua === guess.textContent){
        getScoreWorking();
        bottom.innerHTML = '';
        makeBubbles();
        getANewGuessNumber();
    }
    else{
        bottom.innerHTML = '';
        makeBubbles();
        getANewGuessNumber();
    }
});

makeBubbles();
getANewGuessNumber();
makeTimerWork();
                scale: 1,
                ease: Expo.easeInOut
            }, 'first')
            .fromTo('#mountain #heading', 2, {
                top: '60%',
                scale: 1.2,
                opacity: 0.5
            }, {
                top: '50%',
                scale: 1,
                opacity: 1,
                ease: Expo.easeInOut
            }, 'first')
            .fromTo('#mountain #mountainpiece', 2, {
                bottom: '-200px',
                opacity: 0.5
            }, {
                bottom: '-250px',
                opacity: 1,
                ease: Expo.easeInOut
            }, 'first')

        // scene creation

        new ScrollMagic.Scene({
                triggerElement: '#mountain',
                duration: '100%',
                offset: 0,
                triggerHook: 0,
            })
            .setTween(tl)
            .setPin('#mountain')
            .addTo(ctrlr)
    </script>



* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Montserrat';
}

html, body {
    width: 100%;
    height: 100%;
}

#back {
    position: relative;
    width: 100%;
    height: 100%;
    overflow: hidden;
}

#back video {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    z-index: -999999;
    width: 100%;
}

#nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    height: 100px;
    padding: 0 30px;
    color: #fff;
    /* background-color: yellow; */
}

#nav #logo {
    font-weight: 400;
}

#nav #bold {
    font-weight: 800;
    /* color: black; */
}

#linksnsearch {
    display: flex;
    align-items: flex-end;
    /* width: 500px; */
    /* background-color: rebeccapurple; */
}

#linksnsearch button {
    margin-left: 50px;
    padding: 10px 32px;
    background-color: transparent;
    color: #fff;
    font-size: 11px;
    transition: all cubic-bezier(0.19, 1, 0.22, 1) .7s;
    border: 1px solid rgba(255, 255, 255, 0.507);
}

#linksnsearch i {
    color: white;
    font-size: 14px;
    margin-right: 20px;
}

#linksnsearch input {
    border: none;
    background-color: transparent;
    border-bottom: 1px solid white;
    outline: none;
    color: #fff;
}

#linksnsearch button:hover {
    color: black;
    cursor: pointer;
    background-color: white;
}

#main {
    position: absolute;
    top: 50%;
    left: 5%;
    transform: translate(0, -50%);
    width: 40%;
    /* height: 300px; */
    /* background-color: red; */
}

#main h5 {
    font-weight: 500;
    color: #fff;
    text-transform: uppercase;
    letter-spacing: 7px;
    font-size: 10px;
    margin-bottom: 10px;
}

#main h1 {
    color: #fff;
    line-height: 80px;
    font-size: 80px;
}

#main p {
    font-size: 16px;
    color: rgba(255, 255, 255, 0.315);
    margin-top: 10px;
}

#main hr {
    width: 70%;
    margin: 15px 0;
    opacity: .4;
}

#main #searchbar {
    margin-top: 30px;
    display: inline-block;
    /* background-color: rebeccapurple; */
    border-bottom: 1px solid #fff;
    /* padding-bottom: 0px; */
}

#main #searchbar i {
    color: #fff;
    margin-right: 30px;
}

#main #searchbar input {
    background-color: transparent;
    border: none;
    outline: none;
    color: #fff;
    font-size: 20px;
    width: 250px;
    padding: 11px 5px;
}

#main #searchbar input::placeholder {
    color: #fff;
    font-weight: 300;
    font-size: 17px;
}

#bottomright {
    position: absolute;
    bottom: 0;
    right: 0;
    width: 35%;
    height: 250px;
    padding: 16px 20px;
    background-color: rgb(255, 255, 255);
    /* backdrop-filter: blur(4px); */
}

#bottomright h3 {
    font-weight: 500;
    font-size: 17px;
}

#offers {
    display: flex;
    justify-content: space-between;
    width: 100%;
    /* height: 50px; */
    margin-top: 10px;
    /* background-color: red; */
    margin-bottom: 10px;
}

.offer {
    width: 46%;
    height: 40px;
    border-radius: 3px;
    background-color: #eeeeee;
    border: 1.3px ridge rgba(28, 110, 164, 0.15);
}

#places {
    display: flex;
    justify-content: space-between;
    width: 100%;
    height: 110px;
    margin-top: 5px;
    /* background-color: red; */
}

.place {
    width: 47%;
    height: 100%;
    border: 1.3px solid #eeeeee;
    /* background-color: yellow; */
    padding: 10px;
}

.place h4 {
    margin-top: 10px;
    font-weight: 500;
    color: rgb(68, 68, 68);
}

.image {
    width: 100%;
    height: 70%;
    background-size: cover;
    background-position: 50% 70%;
    background-image: url(https://images.unsplash.com/photo-1575389468025-4472bf833000?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80);
}

#body {
    width: 100%;
    min-height: 100vh;
    /* background-color: yellow; */
}

.container {
    margin: 0 auto;
    width: 90%;
    min-height: 100vh;
    padding: 40px 0px;
    background-color: #fff;
}

.container h1{
    color: rgb(180, 180, 180);
    font-weight: 700;
    text-transform: uppercase;
}

#text-effect {
    text-transform: uppercase;
    letter-spacing: 10px;
    font-size: 72px;
    background-size: cover;
    background-image: url(https://images.unsplash.com/photo-1541701494587-cb58502866ab?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80);
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
}

#bold{
    color: #777;
}

#collage{
    display: flex;
    width: 100%;
    min-height: 600px;
    margin-top: 30px;
    /* background-color: rgb(238, 238, 238); */
}

.left{
    position: relative;
    width: 60%;
    min-height: 600px;
    background-size: cover;
    background-position: center;
    background-image: url(https://images.unsplash.com/photo-1501555088652-021faa106b9b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1953&q=80);
    /* background-color: yellow; */
}

#leftIcon{
    display: flex;
    justify-content: center;
    align-items: center;
    position: absolute;
    z-index: 9999;
    top: 50%;
    left: -25px;
    box-shadow: 0 2px 2px 0 rgba(0,0,0,0.5);
    border-radius: 50%;
    width: 50px;
    height: 50px;
    background-color: white;
}

#leftIcon i{
    color: #c2c2c2;
    font-size: 12px;
}

.right{
    position: relative;
    width: 40%;
    min-height: 600px;
    background-color: #fff;
}

.card{
    position: absolute;
    top: 50%;
    left: -5%;
    overflow: auto;
    transform: translate(0, -50%);
    width: 70%;
    /* padding: 20px;
    padding-top: 60px; */
    height: 80%;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: -60px 2px 20px -20px rgba(0, 0, 0, 0.311), 7px 5px 10px 0 rgba(0, 0, 0, 0.062);
    border: 3px ridge rgba(236, 236, 236, 0.11);
}

#headerofcard{
    width: 100%;
    height: 50px;
    padding: 15px;
    font-size: 17px;
    color: rgb(102, 102, 102);
    background-color: #fff;
}

#callouts{
    width: 100%;
    height: calc(100% - 50px);
    padding: 10px 20px;
    overflow: auto;
    background-color: #fff;
}

#callouts::-webkit-scrollbar{
    width: 7px;
}


#callouts::-webkit-scrollbar-thumb{
    border-radius: 100px;
    background-color: rgb(216, 237, 245);
}

.callout{
    display: flex;
    justify-content: space-between;
    width: 100%;
    min-height: 100px;
    margin-bottom: 20px;
    /* background-color: #f3f3f3; */
}

.arrow{
    position: absolute;
    left: -40px;
    top: 0;
    width: 0;
    height: 0;
    border: 20px solid rgb(169, 214, 231);
    border-top-color: transparent;
    border-left-color: transparent;
    border-bottom-color: transparent;
}

.userimg{
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background-size: cover;
    background-position: center;
    background-image: url(https://images.unsplash.com/photo-1531251445707-1f000e1e87d0?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=562&q=80);
}

.rvw{
    position: relative;
    width: 72%;
    min-height: 100px;
    margin-top: 10px;
    border-radius: 8px;
    border-top-left-radius: 0px;
    padding: 10px;
    font-size: 13px;
    line-height: 23px;
    background-color: rgb(169, 214, 231);
}

#destinationplan{
    display: flex;
    width: 100%;
    height: 100vh;
    /* background-color: red; */
}

#destright{
    position: relative;
    overflow: hidden;
    width: 45%;
    height: 100%;
    background-color: #fff;
}

#circle{
    position: absolute;
    top: -10%;
    right: -40%;
    border-radius: 50%;
    width: 700px;
    height: 700px;
    background-color: transparent;
    border: 1.5px solid rgb(201, 201, 201);
}

.small{
    position: absolute;
    border-radius: 50%;
    width: 12px;
    height: 12px;
    transition: all cubic-bezier(0.19, 1, 0.22, 1) .2s;
    background-color: rgb(44, 44, 44);
}

.small:hover{
    cursor: pointer;
    transform: scale(3.2);
}

#s-one{
    
    left: 101px;
    bottom: 91px;
}

#s-one:hover{
    background-size: cover;
    background-color: initial;
    background-image: url(https://images.unsplash.com/photo-1579961611811-54b643ddbd91?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80);
}

#s-two{
    left: 302px;
    bottom: -4px;
}

#s-two:hover{
    background-size: cover;
    background-color: initial;
    background-image: url(https://images.unsplash.com/photo-1579706783492-081a217cd55e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjF9&auto=format&fit=crop&w=1950&q=80);
}

#bigcircle{
    position: absolute;
    top: 50%;
    left: 0%;
    transform: translate(-50%, -50%);
    width: 420px;
    height: 420px;
    border-radius: 50%;
    background-color: red;
}

#image{
    width: 100%;
    height: 100%;
    border-radius: 50%;
    background-size: cover;
    background-image: url(https://images.unsplash.com/photo-1579623430776-9ca237d80b20?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80);
}

#targetwgrdnt{
    position: absolute;
    top: 0;
    left: 0;
    z-index: 99;
    border-radius: 50%;
    width: 100%;
    height: 100%;
    color: #fff;
    background-color: rgba(0, 0, 0, 0.163);
}

#targetwgrdnt i{
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    position: absolute;
    top: 50%;
    left: 50%;
    width: 80px;
    height: 80px;
    background-color: transparent;
    border: 1.2px solid #fff;
    transform: translate(-50%, -50%);
}


#destleft{
    position: relative;
    width: 55%;
    height: 100%;
    /* background-color: yellow; */
}


#dlfone{
    display: flex;
    justify-content: space-around;
    align-items: center;
    position: absolute;
    top: 18%;
    right: 40px;
    width: 70%;
    /* height: 200px; */
    /* background-color: red; */
}

#dlfone h1:nth-child(1){
    font-size: 160px;
    font-weight: 300;
    color: rgb(240, 54, 95);
}

#dlfone h1:nth-child(2){
    width: 30%;
    font-weight: 600;
    color: rgb(124, 124, 124);
    text-transform: capitalize;
}

#dlftwo{
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: absolute;
    top: 47%;
    right: 40px;
    width: 62%;
    height: 170px;
    /* background-color: rebeccapurple; */
}

#upndownarrows{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    width: 15%;
    height: 100%;
    /* background-color: red; */
}

#upndownarrows i{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 50px;
    height: 50px;
    background-color: transparent;
    border-radius: 50%;
    font-size: 12px;
    border: 1.2px solid #666;
}

#choose{
    width: 70%;
    /* height: 100%; */
    /* background-color: yellow; */
}

#choose h5{
    color: orangered;
    font-size: 20px;
}

#choose h3{
    margin: 10px 0;
    font-size: 25px;
    font-weight: 600;
}

#choose p{
    font-size: 14px;
}


#mountain{
    position: relative;
    width: 100%;
    height: 100vh;
    overflow: hidden;
    background-color: red;
}

#mountain #backimg{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 150%;
    height: 150%;
}

#mountain #clouds{
    position: absolute;
    z-index: 999;
    width: 100%;
    bottom: 0;
}

#mountain #mountainpiece{
    position: absolute;
    bottom: -200px;
    left: 50%;
    height: 70%;
    z-index: 92;
    transform: translate(-50%, 0);
    opacity: .5;
}

#mountain #heading{
    position: absolute;
    top: 60%;
    left: 50%;
    width: 100%;
    text-align: center;
    opacity: .2;
    transform: translate(-50%, -50%);
    font-size: 202px;
    z-index: 70;
    color: rgb(22, 43, 71);
    font-family: "PlayFair Display";
}
</body>

</html>
