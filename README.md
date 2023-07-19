https://github.com/hughes84/ambust.git

Newport Ambulance Station is fully responsive website, created to show the user the basic running of the ambulance service, including fleet, what to do int the event of an emergency and an introduction to some staff. Please note this is not based on a real ambulance station.


![ambustu am i responsive](https://github.com/hughes84/ambust/assets/134289376/f3724de9-7b6d-4e79-8d2e-79b549d4c0fb)

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

![Screenshot (3)](https://github.com/hughes84/ambust/assets/134289376/101f5c6d-82c7-4886-938a-26285ec753e0)
![Screenshot (4)](https://github.com/hughes84/ambust/assets/134289376/9ea259e3-3ef8-4eb1-9cc0-6385fd2a39b3)
![Screenshot (5)](https://github.com/hughes84/ambust/assets/134289376/cd680e72-c853-4228-9eed-eb73380b1ef5)
![Screenshot (6)](https://github.com/hughes84/ambust/assets/134289376/1e0aaecc-b671-4553-9ad5-61fdae52885c)
![Screenshot (7)](https://github.com/hughes84/ambust/assets/134289376/a9db8ba2-9c83-425f-98fb-3e3dfcec83ef)

This is the result for my index.html page


When testing my thankyou.html code i used W3C Markup Validator and found no errors.

![Screenshot (15)](https://github.com/hughes84/ambust/assets/134289376/d3868a2c-024f-4184-b61d-0fb58cacfde8)



This is the result for my thankyou.html page.

![Screenshot (13)](https://github.com/hughes84/ambust/assets/134289376/4a6a8474-36d3-4f6a-98cd-92e9019d2ed0)
![Screenshot (14)](https://github.com/hughes84/ambust/assets/134289376/f6ac9224-93a3-4e2e-88b3-6ead608b3b17)


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

