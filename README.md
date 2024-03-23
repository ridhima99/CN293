# CN293
Team name-Tech Turtle
Team code-CN293
Problem code- WD213
Problem Statement-Organizing events, whether they're conferences, weddings, or corporate gatherings, involves numerous tasks such as venue selection, attendee registration, agenda planning, and logistics coordination. Traditional methods of managing events through spreadsheets or manual processes can be inefficient and error-prone. Your task is to develop an event management website that streamlines the entire event planning process, from initial setup to post-event evaluation, providing organizers with the tools they need to plan, promote, and execute successful events seamlessly.
Plan of our project -

1. Homepage: Introduce your website and its services, featuring upcoming events and highlights.

2. Event Listings: Allow users to browse through a variety of events, filterable by date, location, category, etc.

3. Event Details: Provide comprehensive information about each event, including date, time, venue, description, and ticketing options.

4. User Registration/Login: Enable users to create accounts, save favorite events, and manage their bookings.

5. Feedback and Reviews: Allow attendees to leave feedback and ratings for events they've attended, helping others make informed decisions.
6. Email Notifications: Send confirmation emails for ticket purchases, event reminders, and updates to registered users.
Code of our project
(HOME PAGE)
<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width,
         initial-scale=1.0">       
         <title>Artsy Hub</title>
         <link rel="stylesheet" href="style.css">
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
    <body>
        <section class="header">
            <nav>
                <a href="ind.html">
                    <img src="https://i.pinimg.com/736x/bb/35/14/bb35142f2a709c75fee37d8a5b44e0a1.jpg"
                    ></a>
                
                   <div class="nav-links" id="navLinks">
                    <i class="fa fa-times" onclick="hideMenu()"></i>
                        <ul>
                            <li><a href="ind.html">HOME</a></li>
                            <li><a href="about.html">ABOUT</a></li>
                            <li><a href="catagories.html">CATAGORIES</a></li>
                            <li><a href="contact.html">CONTACT</a></li>
                        </ul>
                    </div>
                    <i class="fa fa-bars" onclick="showMenu()"></i>
                </nav>
<div class="text-box">
<h1>VirtuOLO</h1>
<p>You dream your event
    <br>we create accordingly</p>
    <a href="catagories.html" class="btn">Visit our categories</a> 
</div>
                



        </section>

<!-------call to action-------->
<section class="cta">
    <h1>Explore Our Event Categories From Anywhere
  <br>In The World</h1>
  <a href="contact.html" class="btn">CONTACT US</a>
  <div class="icons">
    <i class="fa fa-instagram"></i>
    <i class="fa fa-facebook"></i>
    <i class="fa fa-twitter"></i>
  </div>
  <p>We <i class="fa fa-heart-o"></i> Events</p>
</section>






<!-----JavaScript for toggle menu----->
<script>
var navLinks = document.getElementById("navLinks");
function showMenu(){
    navLinks.style.right = "0";
}
function hideMenu(){
    navLinks.style.right = "-200px";
}


</script>




    </body>
</html>

(ABOUTE PAGE)
<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width,
         initial-scale=1.0">       
         <title>Artsy Hub</title>
         <link rel="stylesheet" href="style.css">
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
    <body>
        <section class="sub-header">
            <nav>
                <a href="ind.html">
                    <img src="https://i.pinimg.com/736x/bb/35/14/bb35142f2a709c75fee37d8a5b44e0a1.jpg">
                </a>
                
                   <div class="nav-links" id="navLinks">
                    <i class="fa fa-times" onclick="hideMenu()"></i>
                        <ul>
                            <li><a href="ind.html">HOME</a></li>
                            <li><a href="about.html">ABOUT</a></li>
                            <li><a href="catagories.html">CATAGORIES</a></li>
                            <li><a href="contact.html">CONTACT</a></li>
                        </ul>
                    </div>
                    <i class="fa fa-bars" onclick="showMenu()"></i>
                </nav>
<h1>About Us</h1>
                
</section>
<!-----about us content------>
<section class="about-us">
    <div class="row">
        <div class="about-col">
        <h1>We Provide Best Categories Through Our Website.</h1>
        <p>VirtuOLO provides number of catagories with different themes<br>
            so that client can get the decor according to their requirements.<br> 
            We provide a management team to provide satisfaction to the client.<br>
            <a href="" class="btn red-btn">EXPLORE NOW</a>
        </div>
            <div class="about-col">
                <img src="pa1.png">

            </div>
        </p>
    </div>

</section>








<!-----Footer------>
<section class="footer">
    <h4>About Us</h4>
    <p>We created virtuOLO to convert your dream event to reality</p>
    <div class="icons">
        <i class="fa fa-instagram"></i>
        <i class="fa fa-facebook"></i>
        <i class="fa fa-twitter"></i>
      </div>
      <p>We <i class="fa fa-heart-o"></i>
         Events</p>
</section>



<!-----JavaScript for toggle menu----->
<script>
var navLinks = document.getElementById("navLinks");
function showMenu(){
    navLinks.style.right = "0";
}
function hideMenu(){
    navLinks.style.right = "-200px";
}


</script>




    </body>
</html>
(CONTACT PAGE)
<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width,
         initial-scale=1.0">       
         <title>Artsy Hub</title>
         <link rel="stylesheet" href="style.css">
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
    <body>
        <section class="sub-header">
            <nav>
                <a href="ind.html">
                    <img src="https://i.pinimg.com/736x/bb/35/14/bb35142f2a709c75fee37d8a5b44e0a1.jpg"
                    ></a>
                
                   <div class="nav-links" id="navLinks">
                    <i class="fa fa-times" onclick="hideMenu()"></i>
                        <ul>
                            <li><a href="ind.html">HOME</a></li>
                            <li><a href="about.html">ABOUT</a></li>
                            <li><a href="catagories.html">CATAGORIES</a></li>
                            <li><a href="contact.html">CONTACT</a></li>
                        </ul>
                    </div>
                    <i class="fa fa-bars" onclick="showMenu()"></i>
                </nav>
<h1>Contact Us</h1>
                
</section>
<!-----contact us------>
<section class="contact-us">
<div class="row">
    <div class="contact-col">
        <div>
            <i class="fa fa-home"></i>
            <span>
                <h5>VirtuOLO</h5>
                <p>Phagwara, Punjab</p>
            </span>
        </div>
        <div>
            <i class="fa fa-phone"></i>
            <span>
                <h5>+91 9113747294</h5>
                <h5>+91 7017106758</h5>
                <h5>+91 7288910528</h5>
                <h5>+91 9888751928</h5>
                <h5>+91 7482900138</h5>
            </span>
        </div>
        <div>
            <i class="fa fa-envelope-o"></i>
            <span>
                <h5>ridhibthbth@gmail.com</h5>
                <h5>shreya13@gmail.com</h5>
                <h5>shubhangi24@gmail.com</h5>
                <h5>rufienia07@gmail.com</h5>
                <h5>vidhisha03@gmail.com</h5>
            <p>Email us if you are interested for events</p>
                
            </span>
        </div>
        
        

    </div>
<div class="contact-col">
    <form action="">
    <input type="text" placeholder="Enter Your Name"required>
    <input type="email" placeholder="Enter Email Address"required>
    <input type="text" placeholder="Enter Catagory"required>
    <textarea rows="8" placeholder="Message" required></textarea>
    <button type="submit" class="btn red-btn">Submit Message</button>
    </form>
        





    </div>
</div>


</section>








<!-----Footer------>
<section class="footer">
    <h4>About Us</h4>
    <p>We created virtuOLO to convert your dream event to reality</p>
    <div class="icons">
        <i class="fa fa-instagram"></i>
        <i class="fa fa-facebook"></i>
        <i class="fa fa-twitter"></i>
      </div>
      <p>We <i class="fa fa-heart-o"></i>
         Events</p>
</section>



<!-----JavaScript for toggle menu----->
<script>
var navLinks = document.getElementById("navLinks");
function showMenu(){
    navLinks.style.right = "0";
}
function hideMenu(){
    navLinks.style.right = "-200px";
}


</script>




    </body>
</html>

(CSS FOR THESE)
*{
    margin: 0;
    padding: 0;
}
.header{
    min-height: 100vh;
    width: 100%;
    background-image: linear-gradient(rgba(228, 59, 214, 0.7),
    rgba(228, 59, 214, 0.7)),
    url(pa.png);
    background-position: center;
    background-size: cover;
    position: relative;
}
nav{
  display: flex;
  padding:2% 6%;
  justify-content: space-between;
  align-items: center;
}
nav img{
    width: 100px;
}
.nav-links{
    flex: 1px;
    text-align: right;
}
.nav-links ul li{
    list-style: none;
    display: inline-block;
    padding: 8px 12px;
    position: relative;
}
.nav-links ul li a{
    color:aliceblue;
    text-decoration: none;
    font-size: 13px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.nav-links ul li::after{
    content: '';
    width: 0%;
    height: 2px;
    background: #000;
    display: block;
    margin: auto;
    transition: 0.5s;
}
.nav-links ul li:hover::after{
    width: 100%;

}
.text-box{
    width: 90%;
    color: #fff;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    text-align: center;
}
.text-box h1{
font-size: 62px;
font-family: Arial, Helvetica, sans-serif;
}
.text-box p{
    margin: 10px 0 30px;
    font-size: 20px;
    color:#fff;
    font-family: monospace;
}
.btn{
    display: inline-block;
    text-decoration: none;
    color: #fff;
    border: 1px solid #160101;
    padding: 12px 34px;
    font-size: 13px;
    background: transparent;
    position: relative;
    cursor: pointer;

}
.btn:hover{
    border: 1px solid rgb(134, 4, 23);
    background: rgb(134, 4, 23);
    transition: 1s;
}

nav .fa{
    display: none;
}

@media(max-width: 700px){
    .text-box h1{
        font-size: 20px;
    }
        .nav-links ul li {
          display: block;  
        }
        .nav-links{
            position:fixed;
            background: #6d0a2e;
            height: 100vh;
            width: 200px;
            top: 0;
            right: -200px;
            text-align: left;
            z-index: 2;
            transition: 1s;
        }
        nav .fa{
            display:block;
            color:#fff;
            margin:10px;
            font-size: 22px;
            cursor: pointer;
        }
        .nav-links ul{
            padding: 30px;
        }
    }
/*-------------Catagories--------------*/

/*----------call to action-------*/
.cta{
    margin: 100px auto;
    width: 80%;
    background-image: linear-gradient(rgba(0, 0, 0, 0.7),
    rgba(0, 0, 0, 0.7)),url(pa2.png);
    background-position: center;
    background-size: cover;
    border-radius: 10px;
    text-align: center;
    padding: 100px 0;
}
.cta h1{
    color:#fff;
    margin-bottom: 40px;
    padding: 0;
}

.cta .icons .fa{
    color: #f44336;
    margin: 0 13px;
    cursor: pointer;
    padding: 18px 0;
}

@media(max-width: 700px){
    .cta h1{
        font-size: 24px;
    }

}
/*----Footer----*/
.footer{
    width: 100%;
    text-align: center;
    padding: 30px 0;

}
.footer h4{
    margin-bottom: 25px;
    margin-top: 20px;
    font-weight: 600;
}
.footer .icons .fa{
    color: #f44336;
    margin: 0 13px;
    cursor: pointer;
    padding: 18px 0;
}
.fa-heart-o{
    color: #f44336
}
/*-----about us page-------*/

.sub-header{
    height: 50hv;
    width: 100%;
    background-image: linear-gradient(rgba(4,9,30,0.7),
    rgba(4,9,30,0.7)),url(pa.png);
    background-position: center;
    background-size: cover;
    text-align: center;
    color: #fff;

}
.sub-header h1{
    margin-top: 100px;
}
.about-us{
    width: 80%;
    margin: auto;
    padding-top: 80px;
    padding-bottom: 50px;
}
.about-col{
    flex-basis: 48%;
    padding: 30px 2px;
}
.about-col img{
    width: 100%;

}
.about-col h1{
    padding-top: 0;
}
.about-col p{
    padding: 15px 0 25px;
}
.red-btn{
    border: 1px solid #f44336;
    background: transparent;
    color: #f44336;
    transition: 0.5s;
}
.red-btn:hover{
    color:#fff;

}
/*-----contact us page-------*/
.contact-us{
    width: 80%;
    margin: auto;
}
.contact-col{
    flex-basis: 48%;
    margin-bottom: 30px;
}
.contact-col div{
    display: flex;
    align-items: center;
    margin-bottom: 40px;
}
.contact-col div .fa{
    font-size: 28px;
    color: #f44336;
    margin: 10px;
    margin-right: 30px;
}
.contact-col div p{
    padding: 0;
}
.contact-col div h5{
    font-size: 20px;
    margin-bottom: 5px;
    color: #555;
    font-weight: 400;
}
.contact-col input, .contact-col textarea{
    width: 100%;
    padding: 15px;
    margin-bottom: 17px;
    outline: none;
    border: 1px solid #ccc;
    box-sizing: border-box;
}
