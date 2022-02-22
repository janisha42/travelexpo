# travelexpo
Travel Website
<!DOCTYPE html>
<html lang="en">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />
  <link rel="stylesheet" href="styles.css" />
  <!-- styles -->
  <link rel="icon"
    href="https://www.pinclipart.com/picdir/big/528-5281823_earth-airliner-travel-clipart-travel-png-download.png" />
  <title>TravelExpo.com</title>
</head>
<style>
  body {
    background-color: rgb(241, 253, 253);
  }

  .height_idk:before {
    content: "";
    position: absolute;
    z-index: -1;
    background-color: black;
  }

  .height_idk {
    margin-left: auto;
    margin-right: auto;
    height: 90vh;
    width: 100vw;
    filter: brightness(0.8);
  }

  #animation {
    animation-name: moon;
    animation-duration: 4s;
    animation-delay: 1s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
  }

  @keyframes moon {
    0% {
      transform: rotate(0deg);
    }

    90% {
      transform: rotate(90deg);
    }

    180% {
      transform: rotate(180deg);
    }
  }

  .heading {
    margin-top: 3cm;
    text-align: center;
    padding: 2.5rem 0
  }

  .heading span {
    margin-bottom: 8 cm;
    font-size: 2.5rem;
    background: rgba(255, 165, 0, .2);
    color: var(--orange);
    border-radius: .5rem;
    padding: .2rem 1rem;
  }

  .heading span.space {
    background: none;
  }
</style>

<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark" id="top">
    <div class="container-fluid" class="container">
      <a class="navbar-brand" href="index.html">
        <img
          src="https://www.pinclipart.com/picdir/big/528-5281823_earth-airliner-travel-clipart-travel-png-download.png"
          alt="site_logo" id="animated" width="40" height="30" style="filter: brightness(0.9)" />
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="form.html">Form</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown"
              aria-expanded="false">
              popular
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li>
                <a class="dropdown-item" href="#">blackholes,supernovas and more</a>
              </li>
              <hr class="dropdown-divider" />
              <li>
                <a class="dropdown-item" href="#">universal systems
                  <span class="badge bg-info text-dark">New</span></a>
              </li>
              <li>
                <hr class="dropdown-divider" />
              </li>
              <li>
                <a class="dropdown-item" href="#">space technology</a>
              </li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact us</a>
          </li>
          <!-- <li class="nav-item">
              <a class="nav-link disabled"></a>
            </li> -->
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search" />
          <button class="btn btn-outline-info" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
</body>

</html>
<div id="carouselExampleCaptions" class="carousel slide carousel-fade" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
      aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="height_idk" src="https://upload.wikimedia.org/wikipedia/commons/a/af/All_Gizah_Pyramids.jpg"
        class="d-block w-100" alt="pyramid" />
      <div class="carousel-caption d-none d-md-block">
        <h5>Pyramid</h5>
        <p>
          The Pyramids travel guide · Great Pyramid of Khufu. The oldest and
          largest of the three Pyramids is the Great Pyramid of Khufu (Cheops;
          2589–2566BC).
        </p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="height_idk" src="https://img2.goodfon.com/wallpaper/nbig/7/37/paris-parizh-france-franciya-la.jpg"
        class="d-block w-100" alt="space.jpg" />
      <div class="carousel-caption d-none d-md-block">
        <h5>Paris</h5>
        <p>
          A comprehensive budget travel guide to Paris, with tips and advice on
          things to see & do, ways to save money, where to stay, costs, and
          more!
        </p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="height_idk"
        src="https://th-thumbnailer.cdn-si-edu.com/jzm3Sdi-A4nHAwY_q8LAoOVMKJc=/1072x720/filters:no_upscale():focal(1471x1061:1472x1062)/https://tf-cmsv2-smithsonianmag-media.s3.amazonaws.com/filer/b6/30/b630b48b-7344-4661-9264-186b70531bdc/istock-478831658.jpg"
        class="d-block w-100" alt="earth.jpg" />
      <div class="carousel-caption d-none d-md-block">
        <h5>Taj Mahal</h5>
        <p>
          An immense mausoleum of white marble, built in Agra between 1631 and
          1648 by order of the Mughal emperor Shah Jahan in memory of his
          favourite wife, the Taj Mahal is the jewel of Muslim art in India and
          one of the universally admired masterpieces of the world's heritage.
        </p>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<h1 class="heading my-4" align="center">
  <span>A</span>
  <span>B</span>
  <span>O</span>
  <span>U</span>
  <span>T</span>
  <span class="space">-</span>
  <span>U</span>
  <span>S</span>
</h1>
<!-- about us begins here -->
<div class="container my-5" style="margin-top: 40px">
  <div class="row featurette">
    <div class="col-md-7 order-md-2">
      <p class="lead">
        Are you looking for a safe vacation? If yes then this website is for you! As the world is under constraint due
        to covid-19, this sites tell you everything from places to visit with less covid to hotels at less polluted
        places!
        We Provide a Safe space for exploring and ensure All Types Of Accomodation Are
        Available With Full Cleanliness. Happy travelling!!
      </p>
    </div>
    <div class="col-md-5 order-md-1">
      <img class="
          bd-placeholder-img bd-placeholder-img-lg
          featurette-image
          img-fluid
          mx-auto
        " id="animated"
        src="https://www.pinclipart.com/picdir/big/528-5281823_earth-airliner-travel-clipart-travel-png-download.png"
        width="300" height="300" />
    </div>
  </div>
</div>

<div class="container">
  <div class="aform">
    <!--<div>
      <img src="aeroplane.jpeg" width="400px"
          style="align-items: center;margin-top: 170px;margin-right: 40px;margin-left: 40px;" alt="">
  </div>-->
    <hr>


    <h1 class="heading">
      <span>B</span>
      <span>O</span>
      <span>O</span>
      <span>K</span>

      <span class="space">-</span>
      <span>N</span>
      <span>O</span>
      <span>W</span>
    </h1>
    <!-- form begun -->

    <form action="">
      <div class="inputBox">
        <h3 class="fontt">where to</h3>
        <input type="text" placeholder="place name">
      </div>
      <div class="inputBox">
        <h3 class="fontt">how many</h3>
        <input type="number" placeholder="number of guests">
      </div>
      <div class="inputBox">
        <h3 class="fontt">arrivals</h3>
        <input type="date">
      </div>

      <div class="inputBox">
        <h3 class="fontt">leaving</h3>
        <input type="date">
      </div>


      <div class="inputBox">
        <h3 class="fontt">Check the crowd</h3>
        <input type="date">

      </div>
      <br>
      <div class=" input box">
        <h3 class="fontt"> Upload your vaccination card</h3>


        <br>
        Upload vaccination card:
        <input type="submit" class="btn btn-outline-info" value="Upload your Vaccination card" name="submit">
      </div>
      <div style="margin: 30px;"></div>
      <a href="https://www.aarogyasetu.gov.in/gu/" class="btn btn-info"> Take self assesment</a>
      <button type="submit" class="btn btn-info">Submit</button>
  </div>
</div>
</div>










<footer class="
        blog-footer
        d-flex
        justify-content-center
        align-items-center
        text-white
        flex-column
        my-10
        sticky
      ">
  <p>&copy; 2022, blog template by mdo(bootsrap)</p>
  <div>
    <a href="#top" style="color: white">Back to top</a>
  </div>
</footer>


<!-- script -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
  integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
