# Tindog
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>tindog's-by kashyap</title>
  <!-- favicon -->
  <link rel="icon" href="favicon.ico">
  <!-- bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  <!-- css -->
  <link rel="stylesheet" href="styles.css">
  <!-- Js  -->
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
  <!-- Google fonts -->
  <link href="https://fonts.googleapis.com/css?family=Montserratzzzz|Ubuntu" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@800&display=swap" rel="stylesheet">
  <!-- Font awesome -->
  <script defer src="https://use.fontawesome.com/releases/v5.0.7/js/all.js"></script>
</head>

<body>
  <!--top Section -->
  <section class="colored-section" id="title">
    <div class="container-fluid">
      <!-- adding  fluid container for padding H1 -->

      <!-- Nav Bar -->
      <!-- Removing dark back ground <nav class="navbar navbar-expand-lg navbar-dark bg-dark">  -->
      <nav class="navbar navbar-expand-lg navbar-dark">

        <div class="container-fluid">
          <!-- edit vikas fonts -->
          <a class="navbar-brand" href="">tindog </a>
          <button class="navbar-toggler butpo" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <!-- <a class="navbar-brand" href="">tindog </a> -->

          <!-- <a class="navbar-brand" href="">Vikas </a> -->

          <div class="collapse navbar-collapse" id="navbarTogglerDemo02">

            <ul class="navbar-nav ml-auto" style="margin-left:72%;">
              <!-- <li class="nav-iteam">
                <a class="nav-link" href="">Home</a>
              </li> -->
              <li class="nav-iteam">
                <a class="nav-link" href="#testimonials">About</a>
              </li>
              <li class="nav-iteam">
                <a class="nav-link" href="#pricing">Pricing</a>
              </li>
              <li class="nav-iteam">
                <a class="nav-link" href="#cta">Download</a>
              </li>
              <li class="nav-iteam">
                <a class="nav-link" href="#footer">Contact</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>



      <!-- Title -->
      <div class="row">
        <div class="col-lg-6">
          <h1 class="big-heading">Meet new and interesting dogs nearby.</h1>
          <!-- Adding button by bootstrap  -->
          <button type="button" class="btn btn-dark btn-lg downb"><i class="fab fa-apple"> </i> Download</button>
          <button type="button" class="btn btn-outline-light btn-lg downb"><i class="fab fa-google-play"></i> Download</button>
        </div>
        <div class="col-lg-6">
          <img class="t-img" src="iphone6.png" alt="iphone-mockup">
        </div>

      </div>

    </div>

  </section>

  <!--top Section -->

  <!-- Features -->

  <section class="white-section" id="features">
    <div class="container-fluid">


      <div class="row">
        <div class="feature-box col-lg-4">
          <i class="icon fas fa-check-circle fa-4x"></i>
          <h3 class="feature-title">Easy to use.</h3>
          <p>So easy to use, even your dog could do it.</p>
        </div>
        <div class="feature-box col-lg-4">
          <i class="icon fas fa-bullseye fa-4x"></i>
          <h3 class="feature-title">Elite Clientele</h3>
          <p>We have all the dogs, the greatest dogs.</p>
        </div>
        <div class="feature-box col-lg-4">
          <i class="icon fas fa-heart fa-4x"></i>
          <h3 class="feature-title">Guaranteed to work.</h3>
          <p>Find the love of your dog's life or your money back.</p>
        </div>
      </div>

    </div>



  </section>


  <!-- Testimonials -->

  <section class="colored-section" id="testimonials">

    <!-- Carousel with control button and indicator -->
    <div id="carouselExampleControls" class="carousel slide" data-bs-ride="false">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <!-- <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button> -->
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active container-fluid">
          <h2 class="testimonial-text">I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
          <img class="testimonial-img" src="dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
        </div>
        <div class="carousel-item container-fluid">
          <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
          <img class="testimonial-img" src="lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em>
        </div>
        <!-- <div class="carousel-item" style="background-color:#ef8172;">

        </div> -->
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
        <span class="carousel-control-prev-icon"></span>

      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
        <span class="carousel-control-next-icon"></span>

      </button>
    </div>
    <!-- Carousel with control button and indicator -->





  </section>


  <!-- Press -->

  <section class="colored-section" id="press">
    <img class="press-logo" src="techcrunch.png" alt="tc-logo">
    <img class="press-logo" src="tnw.png" alt="tnw-logo">
    <img class="press-logo" src="bizinsider.png" alt="biz-insider-logo">
    <img class="press-logo" src="mashable.png" alt="mashable-logo">

  </section>

  <!-- Press -->



  <!-- Pricing -->

  <section class="white-section" id="pricing">
    <h2 class="section-heading">A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>

    <div class="row">
      <div class="pr-col col-lg-4 col-md-6">
        <!-- making card-1 for pricing -->
        <div class="card">
          <div class="card-header">
            <h3>Chihuahua</h3>
          </div>
          <div class="card-body">
            <h2 class="price-text">Free</h2>
            <p>5 Matches Per Day</p>
            <p>10 Messages Per Day</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-block btn-outline-dark" type="button">Sign Up</button>
          </div>
          <!-- <div class="card-footer">
            no need for this card
            </div> -->

        </div>
      </div>

      <div class="pr-col col-lg-4 col-md-6">
        <!-- making card-2 for pricing -->

        <div class="card">
          <div class="card-header">
            <h3>Labrador</h3>
          </div>
          <div class="card-body">
            <h2 class="price-text">$49 / mo</h2>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
          </div>

        </div>
      </div>
      <div class="pr-col col-lg-4">
        <!-- making card-3 for pricing -->

        <div class="card">
          <div class="card-header">
            <h3>Mastiff</h3>
          </div>
          <div class="card-body">
            <h2 class="price-text">$99 / mo</h2>
            <p>Pirority Listing</p>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
          </div>

        </div>
      </div>


    </div>






  </section>


  <!-- Call to Action -->

  <section class="colored-section" id="cta">
    <div class="container-fluid">

      <h3 class="big-heading">Find the True Love of Your Dog's Life Today.</h3>
      <button class="btn btn-dark btn-lg downb" type="button"><i class="fab fa-apple"> </i> Download</button>
      <button class="btn btn-outline-light btn-lg downb" type="button"> <i class="fab fa-google-play"></i> Download</button>
      <!-- <button type="button" class="btn btn-dark btn-lg downb"><i class="fab fa-apple"> </i> Download</button> -->
      <!-- <button type="button" class="btn btn-outline-light btn-lg downb"><i class="fab fa-google-play"></i> Download</button> -->

    </div>
  </section>


  <!-- Footer -->

  <footer class="white-section" id="footer">
    <div class="container-fluid">

      <p>© Copyright 2021 TinDog</p>
      <i class="social-icon fab fa-facebook"></i>
      <i class="social-icon fab fa-instagram"></i>
      <i class="social-icon fab fa-twitter"></i>
      <i class="social-icon far fa-envelope-open"></i>

    </div>
  </footer>


</body>

</html>
