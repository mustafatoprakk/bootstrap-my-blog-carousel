![Screenshot_1](https://user-images.githubusercontent.com/37051222/142578980-becea4f8-611b-4ccb-bf2e-e4eeed8e0fa4.png)
![Screenshot_2](https://user-images.githubusercontent.com/37051222/142579005-81716afd-c3c5-4eb6-a384-e177d5a024d7.png)



```
 <!DOCTYPE html>
 <html lang="tr">
 <head>
     <meta charset="UTF-8">
     <meta http-equiv="X-UA-Compatible" content="IE=edge">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>My Blog</title>

     <style>
     </style>

     <link rel="stylesheet" href="css/bootstrap.css">
 </head>
 <body>

    <!--Navbar-->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top shadow-sm ps-1">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">
                    <img src="img/logo.png" alt="" width="30" height="24" class="">
                    <span class="ps-1">Toprak</span>
                  </a>
              <div class="collapse navbar-collapse " id="navbarNavAltMarkup">
                <div class="navbar-nav">
                  <a class="nav-link" aria-current="page" href="#">Home</a>
                  <a class="nav-link " href="#">Features</a>
                  <a class="nav-link" href="#">Pricing</a>
                  <a class="nav-link disabled">Disabled</a>
                </div>
              </div>
            </div>
          </nav>
    </header>

    <!--Carousel-->
    <div id="carouselExampleControlsNoTouching" class="carousel slide shadow-lg mt-5" data-bs-touch="false" data-bs-interval="false">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="img/img3.jpg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="img/img4.jpg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="img/img5.jpg" class="d-block w-100" alt="...">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>


    <!--Container-->
    <div class="container mt-5">
        <div class="row">
            <section class="col-md-8">
                <!--Title Heading-->
                <div class="row">
                    <div class="shadow-lg rounded">
                        <img src="img/woods.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                          <h5 class="card-title">TITLE HEADING</h5>
                          <p class="card-text">Title description, <span class="text-muted">April 7, 2014</span></p>
                          <p class="card-text">Mauris neque quam, fermentum ut nisl vitae, convallis maximus nisl. Sed mattis nunc id lorem euismod placerat. Vivamus porttitor magna enim, ac accumsan tortor cursus at. Phasellus sed ultricies mi non congue ullam corper. Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla.</p>
                          <a href="#" class="btn btn-outline-dark">READ MORE >></a>
                          <span class="bg-dark text-white float-end ps-2 pe-2 ms-2 me-4">0</span>
                          <span class="float-end">Comments</span>                
                        </div>
                    </div>
                </div>
                <!--Blog-->
                <div class="row">
                    <div class="shadow-lg rounded mt-4">
                        <img src="https://picsum.photos/id/504/200/100" class="card-img-top" alt="...">
                        <div class="card-body">
                          <h5 class="card-title">TITLE HEADING</h5>
                          <p class="card-text">Title description, <span class="text-muted">April 7, 2014</span></p>
                          <p class="card-text">Mauris neque quam, fermentum ut nisl vitae, convallis maximus nisl. Sed mattis nunc id lorem euismod placerat. Vivamus porttitor magna enim, ac accumsan tortor cursus at. Phasellus sed ultricies mi non congue ullam corper. Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla.</p>
                          <a href="#" class="btn btn-outline-dark">READ MORE >></a>
                          <span class="bg-dark text-white float-end ps-2 pe-2 ms-2 me-4">2</span>
                          <span class="float-end">Comments</span>                
                        </div>
                      </div>
                </div>
            </section>
            <!--Trends-->
            <aside class="col-md-4">
                <div class="shadow-lg rounded mb-3">
                    <img src="https://picsum.photos/id/271/200/120" class="card-img-top" alt="...">
                    <div class="card-body">
                      <h3 class="card-title">My Name</h3>
                      <p class="card-text">Just me, myself and I, exploring the universe of uknownment. I have a heart of love and a interest of lorem ipsum and mauris neque quam blog. I want to share my world with you.</p>
                    </div>
                </div>

                  <div class="card shadow-lg rounded">
                    <div class="card-header pt-3 pb-3 fs-4">
                        Popular Posts
                    </div>
                    <ul class="list-group list-group-flush">
                      <li class="list-group-item">
                          <div class="row">
                              <div class="col-md-2">
                                  <img src="https://picsum.photos/id/295/40/40" class="pt-1" alt="">
                              </div>
                              <div class="col-md-10">
                                  <span>Lorem</span><br>
                                  <span>Sed mattis nunc</span>
                              </div>
                          </div>
                      </li>
                      <li class="list-group-item">
                        <div class="row">
                            <div class="col-md-2">
                                <img src="https://picsum.photos/id/296/40/40" class="pt-1" alt="">
                            </div>
                            <div class="col-md-10">
                                <span>Lorem</span><br>
                                <span>Sed mattis nunc</span>
                            </div>
                        </div>
                    </li>
                    <li class="list-group-item">
                        <div class="row">
                            <div class="col-md-2">
                                <img src="https://picsum.photos/id/297/40/40" class="pt-1" alt="">
                            </div>
                            <div class="col-md-10">
                                <span>Lorem</span><br>
                                <span>Sed mattis nunc</span>
                            </div>
                        </div>
                    </li>
                    <li class="list-group-item">
                        <div class="row">
                            <div class="col-md-2">
                                <img src="https://picsum.photos/id/299/40/40" class="pt-1" alt="">
                            </div>
                            <div class="col-md-10">
                                <span>Lorem</span><br>
                                <span>Sed mattis nunc</span>
                            </div>
                        </div>
                    </li>
                    </ul>
                  </div>
            </aside>
        </div>
    </div>

    <div class="card mt-4 ">
        <div class="card-body bg-secondary pt-4 pb-4">
          <a href="#" class="btn btn-dark disabled btn-lg">Previous</a>
          <a href="#" class="btn btn-dark btn-lg ">Next ></a>
          <p class="text-white pt-3">Powered by Toprak</p>
        </div>
      </div>
     
      <script src="js/bootstrap.js"></script>
 </body>
 </html>
```
