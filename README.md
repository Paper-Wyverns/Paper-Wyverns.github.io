# idea

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<title>Links website</title>
<style>

body {
    background-image: url(https://media.istockphoto.com/id/988364558/photo/decking-gray-seamless-texture-bump-displace-reflect-and-glossiness.jpg?s=612x612&w=0&k=20&c=lRPMSNSqqCwM3Ye_4b-K1AALigB17IFAbKm5oW7mYoQ=);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover; 
}

.container {
  width: 100%;
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
}

.image-container {
  text-align: center;
  width: 100%;
}

.links-container {
  display: flex;
  flex-direction: column;
  jusify-content: center;
  align-items: center;
}

.link {
  min-width: 50% !important;
}

@media (min-width: 1200px) .container {
  max-width: 1140px;
}
@media (min-width: 992px) .container {
  max-width: 960px;
}
@media (min-width: 768px) {
.container {
    max-width: 720px;
  }

.link {
    width: 100%;
  }
}
@media (min-width: 576px) {
.container {
    max-width: 540px;
  }
}

.w3-purple, .w3-hover-purple:hover {
color: #fff!important;
background-color: rgba(156, 39, 176, 0.6) !important;
}
</style>
  </head>


  <body class="w3-white">
    <!-- Content container -->
    <div class="container">

    <div class="image-container">
    <img src="https://i.redd.it/74v5z6dovcfb1.jpg" class="w3-margin" alt="Bio picture" max-width="100%" height="150px" style="border-radius: 50%; alt=">
     <div class="w3-text-white">
     <p class="w3-text-white w3-large">Welcome to The Paper Wyvern's link site!</p>
     <p class="w3-large"><strong>See what we made so far!</strong></p>
      </div>

    <div class="links-container">
      <a href="#" class="w3-button w3-hover-pink w3-large w3-round w3-purple w3-border link" target="_blank"><i class="fab fa-facebook"> </i>Sailor</a>
      <br>
      <a href="#" class="w3-button w3-hover-pink w3-large w3-round w3-purple w3-border link" target="_blank"><i class="fab fa-instagram"> </i>Ampitheater</a>
      <br>
      <a href="#" class="w3-button w3-hover-pink w3-large w3-round w3-purple w3-border link" target="_blank"><i class="fab fa-twitter"> </i>Masquerade</a>
      <br>
      <a href="#" class="w3-button w3-hover-pink w3-large w3-round w3-purple w3-border link" target="_blank"><i class="fa fa-code"> </i>Github</a>
    </div>
  </div>
</div>

  </body>  
</html>
