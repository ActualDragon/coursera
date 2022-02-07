<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link href="styles.css" rel="stylesheet">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oxygen:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital@1&display=swap" rel="stylesheet">

    <title>China Bistro</title>
  </head>
  <body>
    <header>
        <nav id="header-nav" class="navbar navbar-expand-md navbar-light"> <!-- Navigation bar-->
            <div class="container">
                <a class="navbar-brand" href="index.html">
                    <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2F4.bp.blogspot.com%2F-vDFJm66tBuY%2FTqnbwqxt4nI%2FAAAAAAAACCQ%2F6yevWQl2Z6o%2Fs1600%2Fzero.jpg&f=1&nofb=1" alt="" width="150" height="100" class="d-inline-block align-text-center">
                    <span id="MainName">Chinese Restaurant</span>
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="index.html"><div>Home</div></a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="menu-categories.html"><div>Menu</div></a>
                        </li>
                    </ul>
                </div>
                <span class="navbar-text">
                    <li id="phone" class="d-none d-md-block">
                        <a href="tel:410-602-5008">
                          <span>410-602-5008</span></a><div>* We Deliver</div>
                      </li>
                  </span>
            </div>
        </nav>
  </header>

    <div id="call-btn" class="d-md-none">
        <a class="btn" href="tel:410-602-5008">
        <span class="glyphicon glyphicon-earphone"></span>
        410-602-5008
        </a>
    </div>
    <div id="xs-deliver" class="text-center d-md-none">* We Deliver</div>

    <div id="main-content" class="container">
        <div class="jumbotron">
            <img src="castle.jpg" alt="Picture of restaurant" class="img-fluid d-none d-sm-block">
        </div>

    </div>

    <div id="home-tiles" class="row">
        <div class="col-md-4 col-sm-6 col-xs-12">
          <a href="menu-categories.html"><div id="menu-tile"><span>menu</span></div></a>
        </div>
        <div class="col-md-4 col-sm-6 col-xs-12">
          <a href="single-category.html"><div id="specials-tile"><span>specials</span></div></a>
        </div>
        <div class="col-md-4 col-sm-12 col-xs-12">
          <a href="https://www.google.com/maps/place/David+Chu's+China+Bistro/@39.3635874,-76.7138622,17z/data=!4m6!1m3!3m2!1s0x89c81a14e7817803:0xab20a0e99daa17ea!2sDavid+Chu's+China+Bistro!3m1!1s0x89c81a14e7817803:0xab20a0e99daa17ea" target="_blank">
            <div id="map-tile">
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3084.675372390488!2d-76.71386218529199!3d39.3635874269356!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c81a14e7817803%3A0xab20a0e99daa17ea!2sDavid+Chu&#39;s+China+Bistro!5e0!3m2!1sen!2sus!4v1452824864156" width="100%" height="250" frameborder="0" style="border:0" allowfullscreen></iframe>
              <span>map</span>
            </div>
          </a>
        </div>
    </div>

    <footer class="panel-footer">
        <div class="container">
          <div class="row">
            <section id="hours" class="col-sm-4">
              <span>Hours:</span><br>
              Sun-Thurs: 11:15am - 10:00pm<br>
              Fri: 11:15am - 2:30pm<br>
              Saturday Closed
              <hr class="visible-xs">
            </section>
            <section id="address" class="col-sm-4">
              <span>Address:</span><br>
              7105 Reisterstown Road<br>
              Baltimore, MD 21215
              <p>* Delivery area within 3-4 miles, with minimum order of $20 plus $3 charge for all deliveries.</p>
              <hr class="visible-xs">
            </section>
            <section id="testimonials" class="col-sm-4">
              <p>"The best Chinese restaurant I've been to! And that's saying a lot, since I've been to many!"</p>
              <p>"Amazing food! Great service! Couldn't ask for more! I'll be back again and again!"</p>
            </section>
          </div>
          <div class="text-center">&copy; Copyright David Chu's China Bistro 2016</div>
        </div>
    </footer>

    <!-- Optional JavaScript; choose one of the two! -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
  </body>
</html>
