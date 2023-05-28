<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
<!-- Bootstrap CSS -->
<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
    <title>Techie-WeB</title>
      
  </head>
  <body>
    
    <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-white border-bottom px-2 fixed-top" style="position: fixed;" >
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Techie- <span class="text-primary fs-3">WeB</span></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0 fs-5 text-center">
              <li class="nav-item">
                <a class="nav-link active text-primary" aria-current="page" href="#home1"><i class="bi bi-house-door-fill"></i></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#about1">About</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle " href="#services1" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Services
                </a>
                <ul class="dropdown-menu " aria-labelledby="navbarDropdown">
                  <li><a class="dropdown-item" href="#services1">App Development</a></li>
                  <li><a class="dropdown-item" href="#services1">Web Development</a></li>
                  
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#team1">Our Team</a>
              </li> <li class="nav-item">
                <a class="nav-link" href="#contact1">Contact</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#reach">How to reach us</a>
              </li>
            </ul>
            
          </div>
        </div>
      </nav>
    </header>
    <div id="carouselExampleCaptions " class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active " id="home1">
          <img src="data:image/jpeg;base64,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" class="d-block w-100" alt="..." >
          <div class="carousel-caption  d-md-block">
            <h5>Frontend Development</h5>
            
          </div>
        </div>
        <div class="carousel-item">
          <img src="C:\Users\Amir\Desktop\techie web\pho1.png" class="d-block w-100" alt="...">
          <div class="carousel-caption  d-md-block">
            <h5>Backend Development</h5>
            
          </div>
        </div>
        <div class="carousel-item">
          <img src="C:\Users\Amir\Desktop\techie web\pho4.jpg" class="d-block w-100" alt="..." >
          <div class="carousel-caption  d-md-block">
            <h5>Full Stack Development</h5>
           
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
  </header>
  <section class="about my-5" id="about1">
    <div class="container text-center">
      <div>
        <h1  data-aos="fade-up" data-aos-offset="200"><pre>
        </pre>
        <i>  About <span class="text-primary">me</span> </i>
        </h1>
        <hr / class="w-25 m-auto">
      </div>
      <div class="row">
        
          <marquee behavior="scroll" direction="left"  style="position: fixed;"><i class="bi bi-patch-check-fill text-primary"></i>Join Techie-WeB,<span class="text-primary">No Prior coding knowledge is needed</Span></marquee>
            <div class="col-sm-12 col-md-6 col-lg-6 col-12 " data-aos="zoom-in" data-aos-offset="200">
          
            
            
            <p class="lead fs-1">What do you <span class="text-primary" >want to know?</span></p>
<p>
  One of the most popular YouTube tech channels Techie WeB with 17.9 million subscribers. The presenter, Lewis Hilsenteger, is knowledgeable and passionate about what he does. So what does he do? As the name suggests, videos are generally centred around the unboxing of consumer electronics ranging from PCs and smartphones to peripherals and consoles. The items are taken out of the packaging on-camera and reviewed based on first impressions. Apart from unboxing, Lewis discusses specs, tackles DIY projects, and announces limited tech deals and products. Lewis reviews products both niche and mainstream. The videos are informative and cut straight to the point.
  </p>
  <button type="button" class="btn btn-light mb-5">More about me</button>
  <div class="accordion" id="accordionExample">
    <div class="accordion-item">
      <h2 class="accordion-header" id="headingOne">
        <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
          My hobbies
        </button>
      </h2>
      <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
        <div class="accordion-body">
          <strong> Make the others learn coding. </strong>
        </div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header" id="headingTwo">
        <button class="accordion-button collapsed " type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
          My qualification
        </button>
      </h2>
      <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
        <div class="accordion-body">
          <strong>
            B.tech ,<br>
            MS
          </strong></div>
      </div>
    </div>
    <div class="accordion-item">
      <h2 class="accordion-header" id="headingThree">
        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
          Dream
        </button>
      </h2>
      <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
        <div class="accordion-body">
          <strong>My dream is to make this channel no.1 all over the WORLD</strong>       </div>
      </div>
    </div>
  </div>
 </div>
        <div class="col-sm-12 col-md-6 col-lg-6 col-12 m-auto text-end">
<img src="C:\Users\Amir\Desktop\techie web\sir3.jpg" alt="young man" class="img-fluid "  data-aos="zoom-out" data-aos-offset="200" >
        </div>
      </div>
    </div>
  </section>
  <section class="Services" id="services1"><div class="container ">
    <div class="container text-center">
      <div>
        <h1 data-aos="fade-left" data-aos-offset="200"><pre>
       </pre>
         <i> Our<span class="text-primary">Services</span> </i>
        </h1>
        <hr /  class="w-25 m-auto">
      </div>
      <div class="row mt-4">
        <div class="col-sm-12 col-lg-4 col-md-4 col-12"><div class="card">
          <div class="card-body">
            <i class="fa fa-users bg-primary text-white p-2 rounded-pill"></i>
            <h5 class="card-title">Web development</h5>
            <p class="card-text">The course was beneficial and it definitely helped me upskill. Since I am a fresher, I am glad that I was also to grab my first job after completing the course.</p>
            <a href="#" class="btn btn-primary">Book now!</a>
          </div>
        </div></div>
        <div class="col-sm-12 col-lg-4 col-md-4 col-12"><div class="card">
          <div class="card-body bg-primary text-white rounded-pill">
            <i class="fa fa-amazon bg-white text-primary p-2 rounded-pill"></i>
            <h5 class="card-title">App development</h5>
            <p class="card-text">Start here for a high-level overview of how to build apps using the latest Modern Android Development practices</p>
            <a href="#" class="btn btn-white bg-white text-primary">Book now!</a>
          </div>
        </div></div> 
        
      </div>
      <div class="row mt-4">
        <div class="col-sm-12 col-lg-4 col-md-4 col-12"><div class="card">
          <div class="card-body">
            <i class="fa fa-facebook bg-primary text-white p-2 rounded-pill"></i>
            <h5 class="card-title">Web development</h5>
            <p class="card-text">This MEAN full stack developer program offers a comprehensive curriculum using our unique Blended Learning approach to make you career-ready as a full stack MEAN developer upon successful completion of the program.</p>
            <a href="#" class="btn btn-primary">Book now!</a>
          </div>
        </div></div>
        <div class="col-sm-12 col-lg-4 col-md-4 col-12"><div class="card">
          <div class="card-body bg-primary text-white rounded-pill">
            <i class="fa fa-code bg-white text-primary p-2 rounded-pill"></i>
            <h5 class="card-title">App development</h5>
            <p class="card-text">For experienced Android developers
              Dive deeper into more advanced topics in Modern Android Development. These resources assume that you have existing knowledge of how to build Android apps.</p>
            <a href="#" class="btn btn-white bg-white text-primary">Book now!</a>
          </div>
        </div></div> 
        
      </div>
    </div>

  </section>
  <section class=" team text-center mt-4" id="team1">
<div class="container">
  <div class="text-center">
    <h1 data-aos="fade-left" data-aos-offset="200"><pre>
 </pre>
     <i> Our<span class="text-primary">Team</span> </i>
    </h1>
    <hr /  class="w-25 m-auto">
  </div>
  <div class="row mt-4">
    <div class="col"><div class="card">
      <div class="card-body">
        <img src="C:\Users\Amir\Desktop\techie web\sir1.jpg" alt="" class="img-fluid rounded-circle border border-primary">
        <h5 class="card-title">John Bobby</h5>
        <p class="card-text"></p>
        <a href="#" class="btn btn-primary">Book now!</a>
      </div>
    </div></div>
    <div class="col"><div class="card">
      <div class="card-body">
        <img src="C:\Users\Amir\Desktop\techie web\sir2.jpg"  class="img-fluid rounded-circle border border-primary">
        <h5 class="card-title">Nakshatra Reddy</h5>
        <p class="card-text"></p>
        <a href="#" class="btn btn-primary">Book now!</a>
      </div>
    </div></div>
    <div class="col"><div class="card">
      <div class="card-body">
        <img src="C:\Users\Amir\Desktop\techie web\sir3.jpg" style="height:195px;"alt=" data-aos="flip-left" data-aos-offset="200" class="img-fluid rounded-circle border border-primary">
        <h5 class="card-title">Karan Malhotra</h5>
        <p class="card-text"></p>
        <a href="#" class="btn btn-primary">Book now!</a>
      </div>
    </div></div>
  </div>
</div>
  </section>
  
  <section class="contact mt-4 text-center mb-5" id="contact1">
    <div class="container text-center">
    <div>
      <h1 data-aos="fade-left" data-aos-offset="200"><pre>
      </pre>
       <i> Contact<span class="text-primary">Us</span></i>
      </h1>
      <hr /  class="w-25 m-auto">
    </div>
    <div class="row mt-4">
      <div class="col-sm-12 col-md-6 col-lg-6 col-12"><form class="row g-3">
        <div class="col-md-6">
          <label for="inputEmail4" class="form-label">Name</label>
          <input type="email" class="form-control" id="inputEmail4">
        </div>
        <div class="col-md-6">
          <label for="inputPassword4" class="form-label">Email</label>
          <input type="password" class="form-control" id="inputPassword4">
        </div>
        <div class="col-12">
          <label for="inputAddress" class="form-label">Address</label>
          <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St">
        </div>
        
        <div class="col-md-6">
          <label for="inputCity" class="form-label">City</label>
          <input type="text" class="form-control" id="inputCity">
        </div>
        <div class="col-md-4">
          <label for="inputState" class="form-label">State</label>
          <select id="inputState" class="form-select">
            <option selected>Choose...</option>
            <option>...</option>
          </select>
        </div>
        <div class="col-md-2">
          <label for="inputZip" class="form-label">Zip</label>
          <input type="text" class="form-control" id="inputZip">
        </div>
        <div class="col-12">
          <div class="form-check">
            <input class="form-check-input" type="checkbox" id="gridCheck">
            <label class="form-check-label" for="gridCheck">
              Check me out
            </label>
          </div>
        </div>
        <div class="col-12">
          <button type="submit" class="btn btn-primary">Sign in</button>
        </div>
      </form></div>
      <div class="col-sm-12 col-md-6 col-lg-6 col-12">
        <img src="C:\Users\Amir\Desktop\techie web\mam.jpg" alt="" class="img-fluid text-start">
      </div>
    </div>
    </div>
  </section>
  <div class="container text-center mt-4" id="reach">
    <div>
      <h1 data-aos="fade-left" data-aos-offset="200"><pre>
      </pre>
       <i> Reach<span class="text-primary">Us</span></i>
      </h1>
      <hr /  class="w-25 m-auto">
    </div>
    <div class="row mt-4">
      <div class="col-sm-12 col-lg-6 col-md-6 col-12">
        <h3><pre>
          Building.no 12,
          Plot.no 4,
          Sharbati Canal,
          Bodhan,
          Nizamabad,
          Telangana,
          Pin:503180.
        </pre></h3>
      </div>
      <div class="col-sm-12 col-lg-6 col-md-6 col-12">
        <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d15120.08536014336!2d77.89388890000001!3d18.663038349999997!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sin!4v1683713037813!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </div>
    </div>
  <footer class="container">
    <p class="float-end"><a href="#">Back to top</a></p>
    <p>© 2023–2028 Company, Inc. · <a href="#">Privacy</a> · <a href="#">Terms</a></p>
  </footer>
    <!-- Optional JavaScript; choose one of the two! -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
      AOS.init();
    </script>
    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->
  </body>
</html>
