![Uploading down-icon.png…]()
# Netflix-clone- 

<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title >Netflix Clone </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<div class="header">
    <nav>
        <img src="images/logo.png" class="logo">
        <div>
            <button class="language-btn">English <img src="images/down-icon.png"></button>
            <button>Sign In</button>
        </div>
    </nav>
    <div class="header-content">
        <h1>Unlimited movies, TV shows and more.</h1>
        <h3>Watch anywhere. Cancel anytime.</h3>
        <p>Ready to watch? Enter your email to create or restart your membership.</p>
        <form class="email-signup">
            <input type="email" placeholder="Email address" required>
            <button type="submit">Get Started</button>
        </form>
    </div>
</div>

<div class="features">
    <div class="row">
        <div class="text-col">
            <h2>Enjoy on your TV.</h2>
            <p>Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</p>
        </div>
        <div class="img-col">
            <img src="images/feature-1.png">
        </div>
    </div>
    <div class="row">
        <div class="img-col">
            <img src="images/feature-2.png">
        </div>
        <div class="text-col">
            <h2>Download your shows to watch offline.</h2>
            <p>Save your favourites easily and always have something to watch.</p>
        </div>
        
    </div>
    <div class="row">
        <div class="text-col">
            <h2>Watch everywhere.</h2>
            <p>Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</p>
        </div>
        <div class="img-col">
            <img src="images/feature-3.png">
        </div>
    </div>
    <div class="row">
        <div class="img-col">
            <img src="images/feature-4.png">
        </div>
        <div class="text-col">
            <h2>Create profiles for children.</h2>
            <p>Send children on adventures with their favourite characters in a space made just for them—free with your membership.</p>
        </div>
        
    </div>
</div>


<div class="faq">
    <h2>Frequently Asked Questions</h2>
    <ul class="accordion">
        <li>
            <input type="radio" name="accordion" id="first">
            <label for="first">What is Netflix?</label>
            <div class="content">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut maximus faucibus ligula in cursus. Aenean elementum mauris tellus, ullamcorper fringilla justo suscipit ut. Ut eu justo semper, cursus velit id, feugiat odio.</p>
            </div>
        </li>
        <li>
            <input type="radio" name="accordion" id="second">
            <label for="second">How much does Netflix cost?</label>
            <div class="content">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut maximus faucibus ligula in cursus. Aenean elementum mauris tellus, ullamcorper fringilla justo suscipit ut. Ut eu justo semper, cursus velit id, feugiat odio.</p>
            </div>
        </li>
        <li>
            <input type="radio" name="accordion" id="third">
            <label for="third">Where can I watch?</label>
            <div class="content">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut maximus faucibus ligula in cursus. Aenean elementum mauris tellus, ullamcorper fringilla justo suscipit ut. Ut eu justo semper, cursus velit id, feugiat odio.</p>
            </div>
        </li>
        <li>
            <input type="radio" name="accordion" id="fourth">
            <label for="fourth">How do I cancel?</label>
            <div class="content">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut maximus faucibus ligula in cursus. Aenean elementum mauris tellus, ullamcorper fringilla justo suscipit ut. Ut eu justo semper, cursus velit id, feugiat odio.</p>
            </div>
        </li>
        <li>
            <input type="radio" name="accordion" id="fifth">
            <label for="fifth">What can I watch on Netflix?</label>
            <div class="content">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut maximus faucibus ligula in cursus. Aenean elementum mauris tellus, ullamcorper fringilla justo suscipit ut. Ut eu justo semper, cursus velit id, feugiat odio.</p>
            </div>
        </li>
        <li>
            <input type="radio" name="accordion" id="sixth">
            <label for="sixth">Is Netflix good for kids?</label>
            <div class="content">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut maximus faucibus ligula in cursus. Aenean elementum mauris tellus, ullamcorper fringilla justo suscipit ut. Ut eu justo semper, cursus velit id, feugiat odio.</p>
            </div>
        </li>
    </ul>
    <small>Ready to watch? Enter your email to create or restart your membership.</small>
    <form class="email-signup">
        <input type="email" placeholder="Email address" required>
        <button type="submit">Get Started</button>
    </form>
</div>

<div class="footer">
    <h2>Questions? call 000-000-000-000</h2>

    <div class="row">
        <div class="col">
            <a href="#">FAQ</a>
            <a href="#">Investor Relations</a>
            <a href="#">Privacy</a>
            <a href="#">Speed Test</a>
        </div>
        <div class="col">
            <a href="#">Help Center</a>
            <a href="#">Jobs</a>
            <a href="#">Cookies Preferences</a>
            <a href="#">Legal Notices</a>
        </div>
        <div class="col">
            <a href="#">Account</a>
            <a href="#">Ways to watch</a>
            <a href="#">Corporate Information</a>
            <a href="#">Only on Netflix</a>
        </div>
        <div class="col">
            <a href="#">Media Centre</a>
            <a href="#">Terms of Use</a>
            <a href="#">Contact Us</a>
        </div>
    </div>
    <button class="language-btn">English <img src="images/down-icon.png"></button>
    <p class="copyright-txt">Netflix India</p>
</div>

</body>
</html>

*{
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    box-sizing: border-box;
}
body{
    background: #000;
    color: #fff;
}
.header{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)), url(images/header-image.png);
    background-size: cover;
    background-position: center;
    padding: 10px 8%;
    position: relative;
}

nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 0;
}

.logo{
    width: 150px;
    cursor: pointer;
}
nav button{
    border: 0;
    outline: 0;
    background: #db0001;
    color: #fff;
    padding: 7px 20px;
    font-size: 12px;
    border-radius: 4px;
    margin-left: 10px;
    cursor: pointer;
}

.language-btn{
    display: inline-flex;
    align-items: center;
    background: transparent;
    border: 1px solid #fff;
    padding: 7px 10px;
}
.language-btn img{
    width: 10px;
    margin-left: 10px;
}


.header-content{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    text-align: center;
    margin-top: 100px;
}

.header-content h1{
    font-size: 60px;
    line-height: 70px;
    font-weight: 600;
    max-width: 650px;
}
.header-content h3{
    font-weight: 400;
    margin-bottom: 20px;
}

.email-signup{
    background: #fff;
    border-radius: 4px;
    display: flex;
    align-items: center;
    margin-top: 30px;
    overflow: hidden;
}

.email-signup input{
    flex: 1;
    border: 0;
    outline: 0;
    margin-left: 20px;
}
.email-signup button{
    background: #db0001;
    border: 0;
    outline: 0;
    color: #fff;
    font-size: 16px;
    cursor: pointer;
    padding: 15px 30px;
}

/* -----------features---------------- */

.features{
    padding: 50px 12%;
    font-size: 22px;
}
.row{
    display: flex;
    width: 100%;
    align-items: center;
    flex-wrap: wrap;
    padding: 50px 0;
}

.text-col{
    flex-basis: 50%;
    margin-bottom: 20px;
}
.img-col{
    flex-basis: 50%;
    margin-bottom: 20px;
}
.img-col img{
    display: block;
    width: 90%;
    margin: auto;
}
.features h2{
    font-size: 50px;
    font-weight: 600;
    margin-bottom: 20px;
}

/* ----------------faq-------------- */
.faq{
    padding: 10px 12%;
    text-align: center;
    font-size: 18px;
}
.faq h2{
    font-weight: 500;
    font-size: 40px;
}

.accordion{
    margin: 60px auto;
    width: 100%;
    max-width: 750px;
}
.accordion li{
    list-style: none;
    width: 100%;
    padding: 5px;
}
.accordion li label{
    display: flex;
    align-items: center;
    padding: 20px;
    font-size: 18px;
    font-weight: 500;
    background: #303030;
    margin-bottom: 2px;
    cursor: pointer;
    position: relative;
}
label::after{
    content: '+';
    font-size: 34px;
    position: absolute;
    right: 20px;
    transition: transform 0.5s;
}
input[type="radio"]{
    display: none;
}
.accordion .content{
    background: #303030;
    text-align: left;
    padding: 0 20px;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.5s, padding 0.5s;
}
.accordion input[type="radio"]:checked + label + .content{
    max-height: 600px;
    padding: 30px 20px;
}
.accordion input[type="radio"]:checked + label::after{
    transform: rotate(135deg);
}
.faq .email-signup{
    max-width: 600px;
    margin: 20px auto 60px;
}
.faq small{
    font-size: 13px;
}

/* ----------------footer----------------- */
.footer{
    padding: 50px 15% 10px;
    border-top: 6px solid #333;
    color: #777;
}
.footer h2{
    font-size: 18px;
    font-weight: 400;
    margin-bottom: 30px;
}
.footer .col{
    flex-basis: 25%;
    flex-grow: 1;
    margin-bottom: 20px;
}
.footer .col a{
    display: block;
    text-decoration: none;
    color: #777;
    font-size: 14px;
    margin-bottom: 10px;
}
.footer .row{
    align-items: flex-start;
    padding: 10px 0;
}
.footer .language-btn{
    color: #fff;
    padding: 10px 20px;
    border-radius: 3px;
}
.copyright-txt{
    font-size: 14px;
    margin-top: 20px;
    margin-bottom: 10px;
}

/* ---------media-queries-for-small-screen-------- */
@media only screen and (max-width: 600px){
    .logo{
        width: 100px;
    }
    nav button{
        padding: 5px 10px;
    }
    nav .language-btn{
        padding: 4px 8px;
    }
    .header-content{
        position: unset;
        transform: none;
        padding-top: 150px;
    }
    .header-content h1{
        font-size: 30px;
    }
    .email-signup button{
        font-size: 12px;
        padding: 10px 15px;
    }
    .text-col, .img-col{
        flex-basis: 100%;
    }
    .features h2{
        font-size: 30px;
    }
    .features p{
        font-size: 15px;
    }
    .row:nth-child(2), .row:nth-child(4){
        flex-direction: column-reverse;
    }
    .features .row{
        padding: 10px 0;
    }
    .faq h2{
        font-size: 20px;
    }
    .accordion .content{
        font-size: 14px;
    }
    .accordion li label{
        padding: 10px;
        font-size: 14px;
    }
    label::after{
        font-size: 22px;
    }
}
