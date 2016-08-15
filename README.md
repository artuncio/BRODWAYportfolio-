# BRODWAYportfolio-
BRODWAY project
<!DOCTYPE html>
<html>
  <head>
    <link href='https://fonts.googleapis.com/css?family=Raleway:400, 600' rel='stylesheet' type='text/css'>
  <link rel='stylesheet' href='style.css'/>
    
    
  </head>
  <body>
    <div class="header">
      <div class="container">
        <ul class="nav">
        <li> About</li> 
        <li>Work</li>
        <li>Team</li>
        <li>Contact</li>
      </ul>
      </div>
    </div>

    <div class="jumbotron">
      <div class="container">  
        <div class="main">
          <h1>Wee are Broadway</h1>
          <a href=www.onet.pl class="btn-main">Get Started</a>
            
        </div>
      </div>
    </div>

   <div class="supporting">
      <div class="container">
        <div class="col">
          <img src="https://s3.amazonaws.com/codecademy-content/projects/broadway/design.svg">
          <h2>Design</h2>
          <p>Make your projects look great and interact beautifully.</p>
          <a class="btn-default" href="google.com"> Learn More</a> 
        </div>
        <div class="col">
          <img src="https://s3.amazonaws.com/codecademy-content/projects/broadway/develop.svg">
          <h2>Develop</h2>
          <p>Use modern tools to turn your design into a web site</p>
          <a class="btn-default" href="google.com"> Learn More</a> 
          
        </div>
        <div class="col">
          <img src="https://s3.amazonaws.com/codecademy-content/projects/broadway/deploy.svg">
          <h2>Deploy</h2>
          <p>Use modern tools to turn your design into a web site</p>
          <a class="btn-default" href="google.com"> Learn More</a> 
          
        </div>
      </div>
      <div class="clearfix"></div>
    </div>

    <div class="footer">
      <div class="container">
        <p>&copy; Broadway 2015</p>
      </div>
    </div>
  </body>
</html>
html, body {
  margin: 0;
  padding: 0;
}
.header {
  background-color:#333333;
}
.container {
  max-width: 940px;
  margin:  auto;
  padding:  10px;
}

.jumbotron {
 background: url(http://s3.amazonaws.com/codecademy-content/projects/broadway/bg.jpg) no-repeat center center fixed; 
  height: 800px;
  background-size:cover;
}

.nav {
  margin: 0;
  padding: 20px 0;
  
 
}

.nav li {
  color:#fff;
  font-family: 'Raleway', sans-serif;
  font-weight: 600;
  font-size: 16px;
  display:inline;
  padding: 20px;
  
}

.main {
  position: relative;
  top: 180px;
  text-align: center;
}

.main h1 {
  color: #333;
  font-family: 'Raleway', sans-serif;
  font-weight: 600;
  font-size: 70px;
  margin-top: 0;
  margin-bottom: 80px;
  text-transform: uppercase;
}

.btn-main {
  background-color: #333;
  color: #fff;
  font-family: 'Raleway', sans-serif;
  font-weight: 600;
  font-size: 18px;
  letter-spacing: 1.3px;
  padding: 16px 40px;
  text-decoration: none;
  text-transform: uppercase;
}
.btn-dupa {
  border: 1px solid #333;
  color: #333333;
  padding: 16px 40px;
  font-family: sans-serif;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: 100;
  font-size: 10px;
}
.btn-default {
  border: 1px solid #333;
  color: #333333; 
  font-family: 'Raleway', sans-serif;
  font-weight: 600;
  font-size: 10px;
  letter-spacing: 1.3px;
  padding: 10px 20px;
  text-decoration: none;
  text-transform: uppercase;  
  display: inline-block;
  margin-bottom: 20px;      
}
.supporting {
  padding-top: 50px;
  padding-bottom: 50px;
}

.supporting .col {
  float: left;
  width: 33%;
  font-family: 'Raleway', sans-serif;
  text-align: center;
}

.supporting img {
 
  height: 30px;
}

.supporting h2 {
  font-weight: 10;
  font-size: 23px;
  text-transform: uppercase;
}

.supporting p {
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  padding:  50px;
  margin-bottom: 40px;
}

.clearfix {
  clear: both;
}

.footer {
  background-color: #333;
  color: #fff;
  padding: 30px 0;
}

.footer p {
  font-family: 'Raleway', sans-serif;
  text-transform: uppercase;
  font-size: 11px;
}

@media (max-width: 500px) {
  .main h1 {
    font-size: 50px;
    padding:  40px;
  }

  .supporting .col {
    position:clear;
    width: 100%;
    margin-top: px
  }
  
 
}
