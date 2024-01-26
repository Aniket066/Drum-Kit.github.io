# Drum-Kit
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Drum Kit</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-aFq/bzH65dt+w6FI2ooMVUpc+21e0SRygnTpmBvdBgSdnuTN7QbdgL+OapgHtvPp" crossorigin="anonymous">
</head>
<body>
    
    <section id="title" class="gradient-background">
        <!-- nav -->
        <nav class="navbar navbar-expand-lg bg-body-tertiary gradient-background">
            <div class="container-fluid">
              <a class="navbar-brand" href="#"><img src="./images/music-note-list.svg" alt="..." height="40"> DRUMMER</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                  <li class="nav-item">
                    <a class="nav-link" aria-current="page" href="#section-1">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#testimonial">Beats</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#pricing">Plans</a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>

          <!-- main -->
        <div id="section-1" class="container col-xxl-8 px-4 pt-5">
          <div class="row flex-lg-row-reverse align-items-center g-5 pt-5">
            <div class="col-10 col-sm-8 col-lg-6">
    
              <img src="./images/drum2.jpeg" class="d-block mx-lg-auto img-fluid hide-bg" alt="Bootstrap Themes" height="200"
                loading="lazy">
            </div>
            <div class="col-lg-6">
              <h1 class="display-5 fw-bold text-body-emphasis lh-1 mb-3">Dance to the beat of your own DRUMS .</h1>
              <p class="lead"></p>
              <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                <button type="button" class="btn btn-light btn-lg px-4 me-md-2"><svg xmlns="http://www.w3.org/2000/svg"
                    width="16" height="16" fill="currentColor" class="bi bi-apple mb-1" viewBox="0 0 16 16">
                    <path
                      d="M11.182.008C11.148-.03 9.923.023 8.857 1.18c-1.066 1.156-.902 2.482-.878 2.516.024.034 1.52.087 2.475-1.258.955-1.345.762-2.391.728-2.43Zm3.314 11.733c-.048-.096-2.325-1.234-2.113-3.422.212-2.189 1.675-2.789 1.698-2.854.023-.065-.597-.79-1.254-1.157a3.692 3.692 0 0 0-1.563-.434c-.108-.003-.483-.095-1.254.116-.508.139-1.653.589-1.968.607-.316.018-1.256-.522-2.267-.665-.647-.125-1.333.131-1.824.328-.49.196-1.422.754-2.074 2.237-.652 1.482-.311 3.83-.067 4.56.244.729.625 1.924 1.273 2.796.576.984 1.34 1.667 1.659 1.899.319.232 1.219.386 1.843.067.502-.308 1.408-.485 1.766-.472.357.013 1.061.154 1.782.539.571.197 1.111.115 1.652-.105.541-.221 1.324-1.059 2.238-2.758.347-.79.505-1.217.473-1.282Z" />
                    <path
                      d="M11.182.008C11.148-.03 9.923.023 8.857 1.18c-1.066 1.156-.902 2.482-.878 2.516.024.034 1.52.087 2.475-1.258.955-1.345.762-2.391.728-2.43Zm3.314 11.733c-.048-.096-2.325-1.234-2.113-3.422.212-2.189 1.675-2.789 1.698-2.854.023-.065-.597-.79-1.254-1.157a3.692 3.692 0 0 0-1.563-.434c-.108-.003-.483-.095-1.254.116-.508.139-1.653.589-1.968.607-.316.018-1.256-.522-2.267-.665-.647-.125-1.333.131-1.824.328-.49.196-1.422.754-2.074 2.237-.652 1.482-.311 3.83-.067 4.56.244.729.625 1.924 1.273 2.796.576.984 1.34 1.667 1.659 1.899.319.232 1.219.386 1.843.067.502-.308 1.408-.485 1.766-.472.357.013 1.061.154 1.782.539.571.197 1.111.115 1.652-.105.541-.221 1.324-1.059 2.238-2.758.347-.79.505-1.217.473-1.282Z" />
                  </svg> Download</button>
                <button type="button" class="btn btn-outline-light btn-lg px-4"><svg xmlns="http://www.w3.org/2000/svg"
                    width="16" height="16" fill="currentColor" class="bi bi-google-play mb-1" viewBox="0 0 16 16">
                    <path
                      d="M14.222 9.374c1.037-.61 1.037-2.137 0-2.748L11.528 5.04 8.32 8l3.207 2.96 2.694-1.586Zm-3.595 2.116L7.583 8.68 1.03 14.73c.201 1.029 1.36 1.61 2.303 1.055l7.294-4.295ZM1 13.396V2.603L6.846 8 1 13.396ZM1.03 1.27l6.553 6.05 3.044-2.81L3.333.215C2.39-.341 1.231.24 1.03 1.27Z" />
                  </svg> Download</button>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- drum -->
      <section id="testimonial">
        <div class="my-5">
          <div class="p-5 text-center bg-body-tertiary">
            <div class="container py-5">
              <h2 class="text-body-emphasis">“Stamina is the force that drives the drumming; it’s not really a sprint.”</h2>
              <img class="profile-img mt-5" src="./images/neil.jpeg" alt="dog image">
              <p class="col-lg-8 mx-auto lead mt-2">Neil Peart
              </p>
            </div>
            <div class="fire">
                <h1 class="Blazing" contenteditable="true">Drum Kit</h1>
          </div>
          <div class="set">
            <button class="w drum">w</button>
            <button class="a drum">a</button>
            <button class="s drum">s</button>
            <button class="d drum">d</button>
            <button class="j drum">j</button>
            <button class="k drum">k</button>
            <button class="l drum">l</button>
          </div>
          </div>
        </div>    
      </section>    


<!-- login -->
      <section id="pricing">
        <div class="container py-3">
            <div class="pricing-header p-3 pb-md-4 mx-auto text-center">
              <h2 class="display-4 fw-normal text-body-emphasis">A Plan for Every Drummer's Needs</h2>
              <p class="fs-5 text-body-secondary">Simple and affordable price plans for you.</p>
            </div>
          </header>
        
          <main>
            <div class="row row-cols-1 row-cols-md-3 mb-3 text-center">
              <div class="col">
                <div class="card mb-4 rounded-3 shadow-sm">
                  <div class="card-header py-3">
                    <h4 class="my-0 fw-normal">Chimes</h4>
                  </div>
                  <div class="card-body">
                    <h1 class="card-title pricing-card-title">$0<small class="text-body-secondary fw-light">/mo</small></h1>
                    <ul class="list-unstyled mt-3 mb-4">
                      <li>5 saves Per Day</li>
                      <li>10 challanges Per Day</li>
                      <li>Unlimited App Usage</li>
                    </ul>
                    <a href="./form.html">
                    <button type="button" class="w-100 btn btn-lg btn-outline-dark">Sign up for free</button></a>
                  </div>
                </div>
              </div>
              <div class="col">
                <div class="card mb-4 rounded-3 shadow-sm">
                  <div class="card-header py-3">
                    <h4 class="my-0 fw-normal">Glockenspiel</h4>
                  </div>
                  <div class="card-body">
                    <h1 class="card-title pricing-card-title">$15<small class="text-body-secondary fw-light">/mo</small></h1>
                    <ul class="list-unstyled mt-3 mb-4">
                      <li>Unlimited saves</li>
                      <li>Unlimited challanges</li>
                      <li>Unlimited App Usage</li>
                    </ul>
                    <a href="./form.html">
                    <button type="button" class="w-100 btn btn-lg btn-dark">Get started</button></a>
                  </div>
                </div>
              </div>
              <div class="col">
                <div class="card mb-4 rounded-3 shadow-sm border-dark">
                  <div class="card-header py-3 text-bg-dark border-dark">
                    <h4 class="my-0 fw-normal">Tympani</h4>
                  </div>
                  <div class="card-body">
                    <h1 class="card-title pricing-card-title">$29<small class="text-body-secondary fw-light">/mo</small></h1>
                    <ul class="list-unstyled mt-3 mb-4">
                      <li>Personal Training</li>
                      <li>Unlimited saves & challanges</li>
                      <li>Unlimited App Usage</li>
                    </ul>
                    <a href="./form.html">
                    <button type="button" class="w-100 btn btn-lg btn-dark">Get started</button></a>
                  </div>
                </div>
              </div>
            </div>
          </main>
        </div>
      </section>


      <!-- footer -->
      <section id="contact" class="gradient-background">
        <div class="container">
          <footer class="row row-cols-1 row-cols-sm-2 row-cols-md-5 py-5 mt-5 border-top">
            <div class="col mb-3">
              <p class="text-body-secondary center">© Drummer</p>
            </div>
        
            <div class="col mb-3">
        
            </div>
        
            <div class="col mb-3">
            </div>
        
            <div class="col mb-3">
              
            </div>
        
            <div class="col mb-3">
              <h5>Section</h5>
              <ul class="nav flex-column">
                <li class="nav-ite mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Home</a></li>
                <li class="nav-ite mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Play</a></li>
                <li class="nav-ite mb-2"><a href="#" class="nav-link p-0 text-body-secondary">Pricing</a></li>
              </ul>
            </div>
          </footer>
        </div>
      </section>



      <script src="./sound.js" charset="utf-8"></script>
</body>
</html>