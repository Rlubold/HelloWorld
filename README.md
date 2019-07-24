# HelloWorld<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <title>Advanced Data Systems</title>
  <link rel="font2" href="<style>
@import url('https://fonts.googleapis.com/css?family=Amatic+SC|Dosis|Indie+Flower|Quicksand|Shadows+Into+Light&display=swap');
</style>"
  <link rel="icon" href="/Users/RLubold/Desktop/ADSINM/favicon (3).ico">
  <link rel="stylesheet" href="/Users/RLubold/Desktop/Web Development Class/selfpage/CSS/styles.css">


</head>

<body>
  <div class="topcontainer">
    <img class="cloudtop" src="/Users/RLubold/Desktop/Web Development Class/selfpage/CSS/CSS - My Site Images/cloud.png" alt="">
    <h1>I am Robert</h1>
    <div class="p1">
      <p>A programmer</p>
    </div>

    <img class="cloudbot" src="/Users/RLubold/Desktop/Web Development Class/selfpage/CSS/CSS - My Site Images/cloud.png" alt="">
    <img class="mtn" src="/Users/RLubold/Desktop/Web Development Class/selfpage/CSS/CSS - My Site Images/mountain.png" alt="">
  </div>
  <div class="middle-container">
    <div class="profile">
      <img class = "stang" src="/Users/RLubold/Desktop/Web Development Class/selfpage/bobnsteve.jpeg" alt="">
      <h2><img class = "beard" src="/Users/RLubold/Desktop/Web Development Class/selfpage/CSS/beard.png" alt="">Howdy
        <img class = "beard1" src="/Users/RLubold/Desktop/Web Development Class/selfpage/CSS/beard.png" alt=""> </h2>
      <p class="howdy">I am a computer programmer and website devolper. I am currently freelancing for your new and exciting projects! I have a
      passion for coding that I will use to bring you the most up-to-date website possible.</p>
    </div>
    <hr>
    <div class="skills">
      <h2>My Skills</h2>
      <div class="skill-row">
        <img class="computer" src="/Users/RLubold/Desktop/Web Development Class/selfpage/CSS/CSS - My Site Images/computer.png" alt="">
        <h3>Website Design</h3>
        <p>Proffecient in HTML, CSS, and Java Script
          with the ability to custom-tailor all of your
          website needs.
        </p>
      </div>
      <div class="skill-row">
        <img class="mgmnt" src="/Users/RLubold/Desktop/Web Development Class/selfpage/projectmgmnt.png" alt="">
        <h3>Project Manager</h3>
        <p>The ability to take the lead in your
          technical project and provide

          valuable feedback.
        </p>
      </div>
    </div>
    <hr>
    <div class="contact-me">
      <h2>Get In Touch</h2>
      <h3>It's time to make the next move.</h3>
      <p>Contact me at the link below to take the next step</p>
      <p>
        towards the digital age.
      </p>
      <a class="btn" href="mailto:name@email.com">CONTACT ME</a>
    </div>
  </div>

body {
  text-align: center;
  margin-top: 0;
  font-family: verdana, sans-serif;
}

hr {
  border-style: dotted;
  width: 20%;
  border: 10px dotted grey;
  border-top-style: none;
  border-right-style: none;
  border-left-style: none;
  padding-top: 20px;
}

h1 {
  margin-top: 50;
  font-size: 500%;
  font-family: 'Shadows Into Light', cursive;
  color: #66BFBF;
  line-height: 2;
}

h2 {
  color: #66bfba;
  padding-top: 25px;
}

h3 {
  text-align: center;
  color: #11999E;
}

.footer-link {
  color: #11999E;
}

.p1 {
  color: #66BFBF;
  font-weight: normal;
  line-height: 2;
}

.howdy {
  margin: auto;
  width: 50%;
  line-height: 2;
  padding-bottom: 30px;
  padding-top: 10px;
}

p {
  font-family: 'Indie Flower', cursive;
}

.skill-row {
  margin: 50px auto 100px auto;
  width: 50%;
  text-align: left;
  line-height: 2;
}

.stang {
  margin-top: 50px;
  border-radius: 100%;
}

.topcontainer {
  background-color: teal;
  position: relative;
  padding-top: 100px;
}

.cloudtop {
  position: absolute;
  right: 300px;
  top: 50px;
}

.cloudbot {
  position: absolute;
  left: 300px;
  bottom: 300px;
}

.beard {
  padding-right: 30px;
}

.computer {
  float: left;
  width: 25%;
  border-radius: 100%;
  margin-right: 30px;
}

.mgmnt {
  border-radius: 100%;
  float: right;
  margin-left: 30px;
  width: 35%;
}

.beard1 {
  padding-left: 20px;
}

  <div class="bottom-container">
    <a class="footer-link" href="https://www.linkedin.com/">LinkedIn</a>
    <a class="footer-link" href="https://twitter.com/">Twitter</a>
    <a class="footer-link" href="https://www.appbrewery.co/">Website</a>
    <p>© 2018 Robert Richard Lubold.</p>
    <div>Icons made by <a href="https://www.flaticon.com/<?=_('authors').'/'?>freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/"             title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/"             title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>
  </div>



</body>

</html>
