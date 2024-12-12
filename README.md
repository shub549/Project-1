<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-commerce Website</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap" rel="stylesheet">
</head>

<body> 
    <section>
        <div class="home" id="home"> 
            <!--- Navbar -->  
            <nav class="navbar navbar-expand-lg bg-primary data-bs-theme="> 
                <div class="container-fluid">
                    <a class="navbar-brand" href="#" style="color: rgb(214, 14, 14);">IPhone</a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                        data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                        aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span> 
                    </button>
                    <div class="collapse navbar-collapse" id="navbarSupportedContent"> 
                        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                            <li class="nav-item" >
                                <a class="nav-link active" aria-current="page" href="#home" style="color: white;">Home</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">About</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#product">Product</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Contact</a>
                            </li>
                            <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                                    aria-expanded="false">
                                    Dropdown
                                </a>
                                <ul class="dropdown-menu">
                                    <li><a class="dropdown-item" href="#">High to low</a></li>
                                    <li><a class="dropdown-item" href="#">low to high</a></li>
                                </ul>
                            </li>
                        </ul>
                        <form class="d-flex" role="search">
                            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                            <button class="btn btn-outline-success" type="submit">Search</button>
                        </form>
                    </div>
                </div>
            </nav>  

            <!--Content-->
            <div id="carouselExampleDark" class="carousel carousel-dark slide">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active"
                        aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1"
                        aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2"
                        aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active" data-bs-interval="10000">
                        <img src="/bg-1.png" class="d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block">
                            <h5>First slide label</h5>
                            <p>Some representative placeholder content for the first slide.</p>
                        </div>
                    </div>
                    <div class="carousel-item" data-bs-interval="2000">
                        <img src="/bg-2.png" class="d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block">
                            <h5>Second slide label</h5>
                            <p>Some representative placeholder content for the second slide.</p>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <img src="/bg-3.jpg" class="d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block">
                            <h5>Third slide label</h5>
                            <p>Some representative placeholder content for the third slide.</p>
                        </div>
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark"
                    data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark"
                    data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>
        </div>
    </section>
<!--Product Page-->
    <section>
        <div class="product" id="product"></div> 
        <br><br><br>
        <figure class="text-center">
            <blockquote class="blockquote">
                <h2>Product</h2>
            </blockquote>
            <figcaption class="blockquote-footer">
                Someone famous in <cite title="Source Title">Source Title</cite>
            </figcaption>
        </figure>
        <div class="product-card"> 
            <div class="card" style="width: 18rem;">
                <img src="/product-image/iphoine-6.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone 6</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹20,000</h5>
                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <img src="/product-image/iphoine-6s.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone 6s</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹40,000</h5>
                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <img src="/product-image/iphoine-7.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone 7</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹50,000</h5>
                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div>
            </div>  
            <div class="card" style="width: 18rem;">
                <img src="/product-image/iphoine-7 plus.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone 7 plus</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹60,000</h5>
                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div>
            </div>
        </div>   
        <div class="product-card">
            <div class="card" style="width: 18rem;">
                <img src="product-image/iphoine-8 1.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone 8</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹80,000</h5>
                        
                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <img src="/product-image/iphoine-8 plus.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone 8 plus</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹85,000</h5>

                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <img src="product-image/iphoine-9.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone 9</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹92,000</h5>

                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <img src="product-image/iphoine-9 plus.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone 9 plus</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹87,000</h5>

                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div> 
            </div>
        </div>
        <div class="product-card"> 
            <div class="card" style="width: 18rem;">
                <img src="/product-image/iphoine-10 pro max.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone 10 pro max</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹55,000</h5>
                        
                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <img src="/product-image/iphoine-11 pro max.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone 11 pro max</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹65,000</h5>

                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <img src="/product-image/iphoine-12 pro max.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone 12 pro max</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹57,000</h5> 

                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div>
            </div>
            <div class="card" style="width: 18rem;">
                <img src="/product-image/iphone-13 pro max.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">iphone-13 pro max</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                        card's content.</p>
                        <h5>Price: ₹80,000</h5>

                    <a href="#" class="btn btn-primary">Add to cart</a>
                </div>
            </div>
        </div>  
        </div>   
    </section> 
    <section>
        <div class="about-container">
            <h1>About Us</h1> 
            <section class="story">
                <h2>Our Story</h2>
                <p>Founded in [2000],[shopping_web] started with a basic idea: to get the best products to your doorstep. What began as a small online store has grown into a thriving e-commerce platform, offering an extensive range of items across various categories, including fashion, electronics, home goods, and more.</p>
            </section>
            <section class="offerings">
                <h2>What We Offer</h2>
                <ul>
                    <li><strong>Quality Products</strong>: We carefully curate our product selection to ensure that every item meets our high standards of quality and durability.</li>
                    <li><strong>Great Prices</strong>: We work directly with manufacturers and suppliers to get the best prices, passing the savings on to you.</li>
                    <li><strong>Customer Satisfaction</strong>: Our dedicated customer service team is always here to help. We strive to provide quick, efficient, and friendly support for any questions or concerns you may have.</li>
                </ul>
            </section>
            <section class="commitment">
                <h2>Our Commitment</h2>
                <p>We are committed to:</p>
                <ul>
                    <li><strong>Sustainability</strong>: We value eco-friendly products and packaging to reduce our environmental footprint.</li>
                    <li><strong>Quality Service</strong>: We aim to provide exceptional service and a seamless shopping experience.</li>
                    <li><strong>Innovation</strong>: We continuously seek out new and exciting products to offer our customers.</li>
                </ul>
            </section>
        </div>
    </section>

    <section>
        <div class="contact-container">
            <h1>Contact Us</h1>
            <p>If you have any queries, comments, or concerns, please feel free to contact us. We'd love to hear from you!</p>
            <form action="/submit_contact_form" method="POST" class="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
    
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
    
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="6" required></textarea>
    
                <button type="submit">Submit</button> 
            </form>
        </div>
    </section> 

      <!-- Site footer -->
      <footer class="site-footer"> 
        <div class="container">
          <div class="row">
            <div class="col-sm-12 col-md-6">
              <h6>About</h6>
              <p class="text-justify">Scanfcode.com <i>CODE WANTS TO BE SIMPLE </i> is an initiative  to help the upcoming programmers with the code. Scanfcode focuses on providing the most efficient code or snippets as the code wants to be simple. We will help programmers build up concepts in different programming languages that include C, C++, Java, HTML, CSS, Bootstrap, JavaScript, PHP, Android, SQL and Algorithm.</p>
            </div>
  
            <div class="col-xs-6 col-md-3"> 
              <h6>Categories</h6>
              <ul class="footer-links">






























                
                <li><a href="http://scanfcode.com/category/c-language/">C</a></li>
                <li><a href="http://scanfcode.com/category/front-end-development/">UI Design</a></li>
                <li><a href="http://scanfcode.com/category/back-end-development/">PHP</a></li>
                <li><a href="http://scanfcode.com/category/java-programming-language/">Java</a></li>
                <li><a href="http://scanfcode.com/category/android/">Android</a></li>
                <li><a href="http://scanfcode.com/category/templates/">Templates</a></li>
              </ul>
            </div>
  
            <div class="col-xs-6 col-md-3">
              <h6>Quick Links</h6>
              <ul class="footer-links">
                <li><a href="http://scanfcode.com/about/">About Us</a></li>
                <li><a href="http://scanfcode.com/contact/">Contact Us</a></li>
                <li><a href="http://scanfcode.com/contribute-at-scanfcode/">Contribute</a></li>
                <li><a href="http://scanfcode.com/privacy-policy/">Privacy Policy</a></li>
                <li><a href="http://scanfcode.com/sitemap/">Sitemap</a></li>
              </ul>
            </div>
          </div>
          <hr>
        </div>
        <div class="container">
          <div class="row">  
            <div class="col-md-8 col-sm-6 col-xs-12">
              <p class="copyright-text">Copyright &copy; 2017 All Rights Reserved by 
           <a href="#">Scanfcode</a>.
              </p>
            </div>
  
            <div class="col-md-4 col-sm-6 col-xs-12">
              <ul class="social-icons">
                <li><a class="facebook" href="#"><i class="fa fa-facebook"></i></a></li>
                <li><a class="twitter" href="#"><i class="fa fa-twitter"></i></a></li>
                <li><a class="dribbble" href="#"><i class="fa fa-dribbble"></i></a></li>
                <li><a class="linkedin" href="#"><i class="fa fa-linkedin"></i></a></li>   
              </ul>
            </div>
          </div>
        </div>
  </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script> 
</body>
</html>
