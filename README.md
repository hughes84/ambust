https://github.com/hughes84/ambust.git

Newport Ambulance Station is fully responsive website, created to show the user the basic running of the ambulance service, including fleet, what to do int the event of an emergency and an introduction to some staff. Please note this is not based on a real ambulance station.

*Images from Am I Responsive!

1. First time visitor goals
   As a first time visitor, I want to understand purpose of this site and to easily navigate through it
   As a first time visitor, I want to be able to find pictures &/or descriptions 
   As a first time visitor, I want to be able to see where the company is based and to find contact details with ease, e.g. social media links/contact form

2. Returning visitor goals
   As a returning visitor, I want to be able to contact the company with ease and get a prompt response 
   As a returning visitor, I want to find links to other community groups who use the National Park area for recreation.

3. Frequent user goals
   As a frequent user, I want to view some new pictures or updates on the service
   As a frequent user, I want to read more about the service and updates on joining or promoting
   As a frequent user, I want to check to see if there is any news, or any new updates on the website

Colours

The colours chosen for this project are those similar to the national ambulance service colours. I used 'green' with it's hex value of '#0e540e', which was used for headings, hover effects and borders. I also used another light green/yellow color to symbolize the luminous bright colour of the Irish ambulances with an rgba(177, 219, 39, 0.7) this also gave the appearance of a see through effect. Around the image of myself I used a brighter 'chartreuse' colour to brighten up the page a bit more with a hex value of '#7fff00'.

Typography

The Inconsolata font is the title font I used with Sans Serif as the fallback font in case for any reason the font wouldn't import into the site correctly. I used Poppins in my paragraphs as it complimented well with the Inconsolata I felt.

Imagery

The large, background image stretches through the landing page and is designed to be striking and catch the user's attention at the very first glance and to give the user the idea behind the website. I sourced this image of the fleet of the Irish ambulance service online and downloaded it. The second image is a picture I took of myself at work in the National Ambulance Service.

Languages Used

HTML
CSS

Frameworks, Program's and Platforms Used

Google fonts

I used Google fonts to import the Inconsolata and Poppins fonts into the style.css file which is used on all pages throughout the project.

Visual Studio Code

VS Code my main platform used to code while utilizing the terminal to commit and Push to GitHub.

GitHub

GitHub is used to store the projects code after being pushed from Git.

Testing

When testing my index.html code i used W3C Markup Validator and found an error.
I had misused an <id> tag.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="The basic function of an ambulance station">
    <meta name="keywords" content="ambulance station, ambulance, Newport">
    <link rel="stylesheet" href="assets/css/style.css">
    <title>Newport Ambulance Station</title>
    
</head>
<body>
    <header>
        <a href="index.html">
            <h1 id="logo">Newport Ambulance Station</h1>
        </a>
        <nav>
            <ul id="menu">
                <li>
                    <a href="index.html" class="active">Home</a>
                    
                </li>
                <li>
                    <a href="#About">About</a>
                </li>
                <li>
                    <a href="#staff-section">Staff</a>
                </li>
                <li>
                    <a href="#form">Sign Up</a>
                </li>
            </ul>
        </nav>
    </header>
    <section id="ambulance-outer">
        <div id="ambulance-image">
        <div id="cover-text">
        <h2>Serving the Community of Newport</h2>
        </div>
    </div>
    </section>
    <section id="About">
        <h2 id="welcome">What we do, Our vision and values</h2>
        <div id="left-about">
         <div class="left-about-heading">
            <h2>When should you call 999?</h2>
            <hr>
            <p>
                You should call 999 when someone is seriously ill or injured and you think their life is at risk! For example, shortness of breath, persistent chest pains, stroke symptoms, serious bleeding or loss of consciousness.
            </p>
        </div>
        <div class="left-about-heading">
            <h2>What happens when you call 999?</h2>
            <hr>
            <p>
                When you call 999, an operator will ask you which emergency service you need. In a medical emergency, ask for the ambulance service.
                You will then be put through to one of our call-takers. They will ask you some questions about the patient and your location. This is so we can start arranging help straight away.
            </p>
        </div>
        </div>
        <div id="right-about">
        <div class="right-about-heading">
            <h2>Get Involved with us</h2>
            <hr>
            <p>
                Ready to help us save lives?
                There has never been a more exciting time to join us. Over the last 10 years the role of frontline ambulance crew has changed dramatically and continues to evolve to meet a growing demand for urgent healthcare.
            </p>
        </div>
        <div class="right-about-heading">
            <h2>Working on the frontline</h2>
            <hr>
            <p>
                For those with drive and ambition we offer many diverse clinically focused career opportunities to deliver care to the communities we serve. These include working as a community paramedic in primary care, as an emergency care practitioner working in both the emergency and GP out of hours settings, or becoming a dispatcher in our modern control centres.
            </p>
        </div>
        </div>
        <div id="center-about">
            <div id="circle-cover-bg"></div>
            <div id="phecc-badge"></div> 
        </div>
        
        </section>
        <section id="staff-section">
                <h4 id="staff">Meet our Staff</h4>
            <div id="staff-div">
            <div class="box">
                <h3>Edward</h3>
                <hr>
                <p>Meet Edward, a full-time Paramedic working in Newport Ambualnce Station for the past 8 years. Edward is a local man and passionate about caring for the community. He is currently studying for his Masters of Science, Emergency Medical Science. He is eager to progress his skills to further treat those in need and dreams of being a solo responder on our Rapid Response Vehicle (RRV). </p>
                <img src="assets/images/Ed-para1.jpg" alt="Image of staff member">
                
            </div>
            <div class="box">
                <h3>Brian</h3>
                <hr>
                <p>Meet Brian, a former Paramedic for over a decade. Brian has many years of experience on the frontline both on an Emergency Ambulance and Rapid Response Vehicle. He has recently been appointed as an Advanced Paramedic with the Irish Coastguard helping save lives on both land and sea. Brian is also a local to Newport. </p>
                <img src="assets/images/Brian-CG2.jpg" alt="Image of staff member">
            
            </div>
        <div class="box">
            <h3>Patrick</h3>
            <hr>
            <p>Meet Patrick, a dedicated Paramedic from Co.Galway. Patrick divides his time between farming and serving the public working long hours day and night. Patrick also worked on our swabbing team during the Covid 19 pandemic giving up more of his time to serve the community. He recently transferred to Newport Ambulance to be closer to home.  </p>
            <img src="assets/images/Pat-C191.jpg" alt="Image of staff member">
            </div>
        </div>
    

        
        </section>
        
 <form id="form" style="border:1px solid #ccc" class="form-fields" method = "GET" action= "thankyou.html">
    <div class="container">
      <h3>Sign Up</h3>
      <p>Please fill in this form to create an account.</p>
      <hr>
  
      <label id="email"><b>Email</b></label>
      <input type="email" placeholder="Enter Email" name="email" required>
  
      <label id="psw"><b>Password</b></label>
      <input type="password" placeholder="Enter Password" name="psw" required>
  
      <label id="psw-repeat"><b>Repeat Password</b></label>
      <input type="password" placeholder="Repeat Password" name="psw-repeat" required>
  
      <label>
        <input type="checkbox" checked="checked" name="remember" style="margin-bottom:15px"> Remember me
      </label>
  
      
  
      <div class="clearfix">
        <button type="button" class="cancelbtn">Cancel</button>
        <button type="submit" class="signupbtn">Sign Up</button>
      </div>
    </div>
  </form>
    <footer>
        <ul class="social-media">
            <li>
                <a href="https://facebook.com" target="_blank" rel="noopener"
                    aria-label="Visit our Facebook page (opens in a new tab)"><i class="fab fa-facebook"></i></a>
            </li>
            <li>
                <a href="https://twitter.com" target="_blank" rel="noopener"
                    aria-label="Visit our Twitter page (opens in a new tab)"><i class="fab fa-twitter-square"></i></a>
            </li>
            <li>
                <a href="https://youtube.com" target="_blank" rel="noopener"
                    aria-label="Visit our YouTube page (opens in a new tab)"><i class="fab fa-youtube-square"></i></a>
            </li>
            <li>
                <a href="https://instagram.com" target="_blank" rel="noopener"
                    aria-label="Visit our Instagram page (opens in a new tab)"><i class="fab fa-instagram"></i></a>
            </li>
        </ul>

    </footer>

 <!-- font awesome script -->
 <script src="https://kit.fontawesome.com/c7dbda0798.js" crossorigin="anonymous"></script>

  
</body>
</html>

This is the result for my index.html page


When testing my about.html code i used W3C Markup Validator and found some errors.
I had two unclosed <div> elements.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="The basic function of an ambulance station">
    <meta name="keywords" content="ambulance station, ambulance, Newport">
    <link rel="stylesheet" href="assets/css/style.css">
    <title>Newport Ambulance Station</title>
    
</head>
<body>
    <header>
        <a href="index.html">
            <h1 id="logo">Newport Ambulance Station</h1>
        </a>
        <nav>
            <ul id="menu">
                <li>
                    <a href="index.html">Home</a>
                    
                </li>
                <li>
                    <a href="about.html" class="active">About</a>
                </li>
                <li>
                    <a href="staff.html">Staff</a>
                </li>
                <li>
                    <a href="signup.html">Sign Up</a>
                </li>
            </ul>
        </nav>
    </header>
   
    <section id="About">
        <h2 id="welcome">What we do, Our vision and values</h2>
        <div id="left-about">
         <div class="left-about-heading">
            <h2>When should you call 999?</h2>
            <hr>
            <p>
                You should call 999 when someone is seriously ill or injured and you think their life is at risk! For example, shortness of breath, persistent chest pains, stroke symptoms, serious bleeding or loss of consciousness.
            </p>
        </div>
        <div class="left-about-heading">
            <h2>What happens when you call 999?</h2>
            <hr>
            <p>
                When you call 999, an operator will ask you which emergency service you need. In a medical emergency, ask for the ambulance service.
                You will then be put through to one of our call-takers. They will ask you some questions about the patient and your location. This is so we can start arranging help straight away.
            </p>
        </div>
        </div>
        <div id="right-about">
        <div class="right-about-heading">
            <h2>Get Involved with us</h2>
            <hr>
            <p>
                Ready to help us save lives?
                There has never been a more exciting time to join us. Over the last 10 years the role of frontline ambulance crew has changed dramatically and continues to evolve to meet a growing demand for urgent healthcare.
            </p>
        </div>
        <div class="right-about-heading">
            <h2>Working on the frontline</h2>
            <hr>
            <p>
                For those with drive and ambition we offer many diverse clinically focused career opportunities to deliver care to the communities we serve. These include working as a community paramedic in primary care, as an emergency care practitioner working in both the emergency and GP out of hours settings, or becoming a dispatcher in our modern control centres.
            </p>
        </div>
        </div>
    <div id="center-about"></div>
        <div id="circle-container"></div>
          <div id="circle-cover-bg">
            </div>
        <div id="bottom-about">
          </div>
        </section>
        

    <footer>
        

    </footer>

 <!-- font awesome script -->
 <script src="https://kit.fontawesome.com/c7dbda0798.js" crossorigin="anonymous"></script>

</body>
</html>

This is the result for my about.html page


When testing my staff.html code i used W3C Markup Validator and found some errors.
I had a stray end </div> tag. I had an unclosed </section> and I had a section requiring a heading or a div.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="The basic function of an ambulance station">
    <meta name="keywords" content="ambulance station, ambulance, Newport">
    <link rel="stylesheet" href="assets/css/style.css">
    <title>Newport Ambulance Station</title>
    
</head>
    <body>
    <header>
        <a href="index.html">
            <h1 id="logo">Newport Ambulance Station</h1>
</a>
        <nav>
            <ul id="menu">
            <li>
                <a href="index.html">Home</a>
                    
</li>
            <li>
                <a href="about.html">About</a>
</li>
            <li>
                <a href="staff.html" class="active">Staff</a>
</li>
            <li>
                <a href="signup.html">Sign Up</a>
</li>
</ul>
</nav>
</header>
    <section id="staff-section">
    <h4 id="staff">Meet our Staff</h4>
        <div id="staff-div">
        <div class="box">
    <h3>Edward</h3>
    <hr>
    <p>Meet Edward, a full-time Paramedic working in Newport Ambualnce Station for the past 8 years. Edward is a local man and passionate about caring for the community. He is currently studying for his Masters of Science, Emergency Medical Science. He is eager to progress his skills to further treat those in need and dreams of being a solo responder on our Rapid Response Vehicle (RRV). </p>
</div>
        <div class="box">
    <h3>Brian</h3>
    <hr>
    <p>Meet Brian, a former Paramedic for over a decade. Brian has many years of experience on the frontline both on an Emergency Ambulance and Rapid Response Vehicle. He has recently been appointed as an Advanced Paramedic with the Irish Coastguard helping save lives on both land and sea. Brian is also a local to Newport. </p>
</div>
            <div class="box">
    <h3>Patrick</h3>
    <hr>
    <p>Meet Patrick, a dedicated Paramedic from Co.Galway. Patrick divides his time between farming and serving the public working long hours day and night. Patrick also worked on our swabbing team during the Covid 19 pandemic giving up more of his time to serve the community. He recently transferred to Newport Ambulance to be closer to home.  </p>
</div>
</div>
        <div>
            <section id="staff-pic"></section>
        <div id="staff-pic-ed">
        <div id="staff-pic-brian">
        <div id="staff-pic-patrick">
</div>
</div>
</div>
</div>
</section>
        <footer>
        <ul class="social-media">
        <li>
            <a href="https://facebook.com" target="_blank" rel="noopener"
                    aria-label="Visit our Facebook page (opens in a new tab)"><i class="fab fa-facebook"></i></a>
</li>
        <li>
            <a href="https://twitter.com" target="_blank" rel="noopener"
                    aria-label="Visit our Twitter page (opens in a new tab)"><i class="fab fa-twitter-square"></i></a>
</li>
        <li>
            <a href="https://youtube.com" target="_blank" rel="noopener"
                    aria-label="Visit our YouTube page (opens in a new tab)"><i class="fab fa-youtube-square"></i></a>
</li>
        <li>
            <a href="https://instagram.com" target="_blank" rel="noopener"
                    aria-label="Visit our Instagram page (opens in a new tab)"><i class="fab fa-instagram"></i></a>
</li>
</ul>
</footer>

 <!-- font awesome script -->
            <script src="https://kit.fontawesome.com/c7dbda0798.js" crossorigin="anonymous"></script>

</body>
</html>


This is the result for my staff.html page


When testing my thankyou.html code i used W3C Markup Validator and found no errors.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="The basic function of an ambulance station">
    <meta name="keywords" content="ambulance station, ambulance, Newport">
    <link rel="stylesheet" href="assets/css/style.css">
    <title>Newport Ambulance Station</title>
    
</head>
<body>
    <header>
        <a href="index.html">
            <h1 id="logo">Newport Ambulance Station</h1>
        </a>
        <nav>
            <ul id="menu">
                <li>
                    <a href="index.html">Home</a>
                    
                </li>
                <li>
                    <a href="index.html#About">About</a>
                </li>
                <li>
                    <a href="index.html#staff-section">Staff</a>
                </li>
                <li>
                    <a href="index.html#form">Sign Up</a>
                </li>
            </ul>
        </nav>
    </header>
    <main id="thank-you-info">
        <div>
        <h2>Thank you, your form has been submitted!</h2>
        <p>Thank you for your application, we will be in contact in due course.</p>
    </div>
    </main>
    <footer>
        <ul class="social-media">
            <li>
                <a href="https://facebook.com" target="_blank" rel="noopener"
                    aria-label="Visit our Facebook page (opens in a new tab)"><i class="fab fa-facebook"></i></a>
            </li>
            <li>
                <a href="https://twitter.com" target="_blank" rel="noopener"
                    aria-label="Visit our Twitter page (opens in a new tab)"><i class="fab fa-twitter-square"></i></a>
            </li>
            <li>
                <a href="https://youtube.com" target="_blank" rel="noopener"
                    aria-label="Visit our YouTube page (opens in a new tab)"><i class="fab fa-youtube-square"></i></a>
            </li>
            <li>
                <a href="https://instagram.com" target="_blank" rel="noopener"
                    aria-label="Visit our Instagram page (opens in a new tab)"><i class="fab fa-instagram"></i></a>
            </li>
        </ul>

    </footer>

 <!-- font awesome script -->
 <script src="https://kit.fontawesome.com/c7dbda0798.js" crossorigin="anonymous"></script>

  
</body>
</html>

This is the result for my thankyou.html page.



CSS

When testing my style.css I used W3C CSS Validator and had found some an error with my title.

<!DOCTYPE html><html lang="en">
<title>Newport Ambulance Station</title>
@import url('https://fonts.googleapis.com/css2?family=Inconsolata:wght@300&family=Poppins:ital,wght@1,700&display=swap');
* {
    margin: 0;
    padding: 0;
    border: none;
}
body {
    background-color: #FFF2CC;
    font-family: Inconsolata, light;
    font-weight: 200;
    color: #0E540E;
}
a {
    text-decoration: none;
}
/* headings and logo */
header {
    display: flex;
    flex-direction: row;
}
h1 {
    font-family: Poppins, sans-serif;
    text-transform: uppercase;
    letter-spacing: 4px;
    color: #0E540E;
    padding: 4px;
    border-top: 8px solid #7FFF00;
    border-bottom: 8px solid #7FFF00;
    width: fit-content;
    line-height: 40px ;
    
}
h2, h3 {
    font-family: Poppins, sans-serif;
    text-transform: capitalize;
    letter-spacing: 3px;
    color: #0E540E;
}
h4 {
    font-family: Poppins, sans-serif;
    text-transform: capitalize;
    letter-spacing: 3px;
    color: #0E540E;
    
    
}
#logo {
    
    font-size: 280%;
    margin-left: 35px;
    margin-top: 50px;
        
    
}
/* navigation links */
#menu {
    display: inline-flex;
    flex-direction: row;
    justify-content: space-between;
    font-size: 120%;
    letter-spacing: 2px;
    padding-left: 30px;
}
#menu li {
    list-style-type: none;
    margin: 50px 5px 0 5px;
}
#menu a {
    text-decoration: none;
    color: inherit;
}
#menu a:hover {
    border-bottom: 1px solid #0E540E;
}
.active {
    border-bottom: 1px solid #0E540E;
}
/* ambulance image and cover-text */
#ambulance-outer {
    height: 500px;
    width: 100%;
    
}
#cover-text h2, #cover-text h3 {
    color: #0E540E;
}
#ambulance-image {
    height: 500px;
    width: 100%;
    margin-top: 50px;
    background: url(../images/ambu1.jpg) no-repeat center center;
}
#cover-text {
    position: absolute;
    right: 100px;
    bottom: 80px;
    font-size: 100%;
    font-family: Inconsolata, light;
    text-transform: uppercase;
    letter-spacing: 3px;
    width: 200px;
    height: 120px;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 15px;
    background-color: rgba(177, 219, 39, 0.7);
}
/* about */
#about {
    height: 500px;
    display: flex;
    flex-direction: column;
    
}
#left-about {
    padding-top: 50px;
    width: 25%;
    float: left;
}
#right-about {
    padding-top: 50px;
    width: 25%;
    float: right;
    text-align: right;
}
#center-about {
    width: 25%;
    margin: 0 auto;
    height: 1000px;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
}
hr {
    border-top: 2px solid #0E540E;
    
    margin: 3px 0;
}
.left-about-heading {
    width: 70%;
    float: right;
    line-height: 25px;
    clear: both;
    margin-bottom: 40px;
}


.right-about-heading {
    width: 70%;
    line-height: 25px;
    clear: both;
    margin-bottom: 40px;
}

#welcome {
    text-align: center;
    margin: 40px 0;
    font-size: 280%;
}
#staff {
    text-align: center;
    margin: 100px 0;
    font-size: 280%;
    margin-bottom: 30px;
}


#circle-container {
    width: 300px;
    height: 450px;
    padding: 10px;
    border-style: solid;
    border-color: #7FFF00;
    border-width: 8px;
    border-radius: 50%;
}
#circle-cover-bg {
    background: url(../images/para2.jpg) no-repeat center;
    height: 100%;
    border-radius: 70%;
    border: 5px solid #7FFF00;
    padding: 5px;
    
    background-size: cover;
}
#phecc-badge {
    background: url(../images/phecc2.jpg) no-repeat center;
    height: 100%;
    width:100%;
}
#staff-heading {
    width: 70%;
    line-height: 25px;
    
    margin: 0px auto 40px auto;
}
#staff-section {
   width: 100%;
   display: flex;
    flex-direction: column;
    
}
#staff-div {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    margin-top: 50px;
}



.box {
    max-width: 250px;
    height: 500px;
    display: flex;
    flex-direction: column;
    
}

.box img {
    height: auto;
    width: 150px;
    margin: 10px auto;
    align-self: flex-end;
    display: flex;
}


footer {
    height: 200px;
}

.social-media {
    text-align: center;
    
}

footer {
    height: 200px;
    margin-top: 50px;
}

.social-media {
    
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    list-style-type: none;

}
.social-media i {
    font-size: 200%;
    
    padding: 8%;
    color:#0E540E;
}

* {box-sizing: border-box}

/* Full-width input fields */
  input[type=text], input[type=password], input[type=email] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}

hr {
  border: 1px solid #0E540E;
  margin-bottom: 25px;

}

/* Set a style for all buttons */
button {
  background-color: #0E540E;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

button:hover {
  opacity:1;
}

/* Extra styles for the cancel button */
.cancelbtn {
  padding: 14px 20px;
  background-color: #f44336;
}

/* Float cancel and signup buttons and add an equal width */
.cancelbtn, .signupbtn {
  float: left;
  width: 50%;
}

/* Add padding to container elements */
.container {
  padding: 16px;
}

.container h3 {
    text-align: center;
    border-bottom: 8px solid #7FFF00;
    border-top: 8px solid #7FFF00;
    font-size: 30px;
}

/* Clear floats */
.clearfix::after {
  content: "";
  clear: both;
  display: table;
}

#thank-you-info {
    width: 100%;
    height: 70vh;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
}

/* Change styles for cancel button and signup button on extra small screens */
@media screen and (max-width: 600px) {
  .cancelbtn, .signupbtn {
    width: 100%;
  }
 

#logo {
    
    font-size: 200%;
    
        
    
}

}

/* media queries */

/* for larger to medium screen size from 1200px wide and down */


    
/* for medium screen sizes of 950px wide and down */

@media screen and (max-width: 950px) {

    header {
    
        flex-direction: column;
    }
    
    .left-about-heading {
        
        float: none;
        line-height: 25px;
        clear: both;
        margin: 0 auto;
        margin-bottom: 20px;

        
    }
    
    
    .right-about-heading {
        
        line-height: 25px;
        clear: both;
        text-align: left;
        margin: 0 auto;
        margin-bottom: 20px;
    }
    

    #left-about {
        width: 90%;
        float: none;
        margin: 0 auto;
    
        
    }
    #right-about {
        float: none;
        clear: both;
        width: 90%;
        margin: 0 auto;
        
    }
    #center-about {
        width: 90%;
        height: 800px;
        margin: 0 auto;
        float: none;
        clear: both;
        
    }


#cirlcle-cover-bg {
    width: 300px;
    margin: 0 auto;
    flex-direction: column;
    
}

#staff {
    width: 100%;
    clear: both;
    height: 150px;
    font-size: 30px;
    
    
}

#staff-div {
    flex-direction: column;
    margin: 0 auto;
    
}

.box {
    max-width: 500px;
    margin: 0 30px;
}

}

This is the result for my style.css page




Colours

The colours chosen for this project are those similar to the national ambulance service colours. I used 'green' with it's hex value of '#0e540e', which was used for headings, hover effects and borders. I also used another light green/yellow color to symbolize the luminous bright colour of the Irish ambulances with an rgba(177, 219, 39, 0.7) this also gave the appearance of a see through effect. Around the image of myself I used a brighter 'chartreuse' colour to brighten up the page a bit more with a hex value of '#7fff00'. I used a red hex value '#f44336' for my cancel button on sign up form to highlight the cancel.

Typography

The Inconsolata font is the title font I used with Sans Serif as the fallback font in case for any reason the font wouldn't import into the site correctly. I used Poppins in my paragraphs as it complimented well with the Inconsolata I felt.

Imagery

The large, background image stretches through the landing page and is designed to be striking and catch the user's attention at the very first glance and to give the user the idea behind the website. I sourced this image of the fleet of the Irish ambulance service online and downloaded it. The second image is a picture I took of myself at work in the National Ambulance Service. I used some pictures of my work collegaues for the staff section from Facebook with their consent.


Languages Used

HTML
CSS

Frameworks, Program's and Platforms Used

Google fonts

I used Google fonts to import the Inconsolata and Poppins fonts into the style.css file which is used on all pages throughout the project.

Visual Studio Code

VS Code my main platform used to code while utilizing the terminal to commit and Push to GitHub.

GitHub

GitHub is used to store the projects code after being pushed from Git.

W3C Schools

I used W3C Schools for assistance with my sign up form. 

NHS South Central Ambulance Service

I used this website for some ideas in the about section.


Bugs

As I was buliding my website I was constantly debuging and changing my code
I had some preformance issues in the begining but I managed to rectify it by increasing and decreasing the size of my images and testing different style, ie. float to flex. I tested my page regularly through inspect as well as on various different websites for responsive testing.
 

Features

Navigation

My navigation is placed on the top right of the page . It displays clicklable tabs which will bring us on directly onto the pages clicked, Home, About, Staff, Sign up.
On the Home page there is a large image of various fleet and personnel with bright colors linked with the ambulance service. I also have the name of the website at the top as well as a short description of the service embedded on the image.
On the About page I have a centred picture of myself at work in uniform with an ambulance in the background. I have this centred with a bright border again showing the bright ambulance colors.

