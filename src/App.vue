<template>
  <div id="app">

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg  fixed-top" id="mainNav">
      <div class="container">
        <a class="navbar-brand js-scroll-trigger" href="#page-top">Leddy's Bakery</a>
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav text-uppercase ml-auto" style="color:black">
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#aboutUs">About Us</a>
            </li>    
              <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#newsletter">Our Newsletter</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#products">Our Products</a>
            </li>
      
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#bakers">Our Bakers</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Header -->
    <header class="masthead">
      <div class="container">
        <div class="intro-text">
          <div class="intro-lead-in">Welcome!</div>
          <div class="intro-heading text-uppercase">Leddy's Bakery</div>
          <a id="scrolldown" href="#aboutUs">
          Come See Our Delicious Goods
          </a>
        </div>
      </div>
    </header>

    <!-- About Us -->
    <section id="aboutUs">
      <div class="container">
        <div class="row">
          <div class="col-sm-8">
           <h2 class="edgtf-st-title" style="color: #303030;font-weight: 600;letter-spacing: 4px">
             <span>Our Story</span>
           </h2>
            <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
            <p style="text-align:left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          <br/>
           <p style="text-align:left">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
          </div>
         
        <div class="col-sm-4">
          <img src="./assets/img/baker.jpg" alt="baker" style="width:400px">
        </div>

        </div>
      </div>
    </section>

        <!-- Newsletter -->
    <section id="newsletter">
    <div class="row">
    <div class="col-sm-7">
    <h1>Join Our Newsletter</h1>
    <h2 class="newsletterBlerb">Be the first to hear about our new products, specials, and recieve coupons!</h2>
          <div class="edgtf-column-left">
      <span class="wpcf7-form-control-wrap your-email">
       <input type="email" name="your-email" value="" size="40" maxlength="100" class="wpcf7-form-control wpcf7-text wpcf7-email wpcf7-validates-as-required wpcf7-validates-as-email" aria-required="true" aria-invalid="false" placeholder="Email Address">
     </span>
    </div>
    <div class="edgtf-column-right">
      <input type="submit" value="Join" class="wpcf7-form-control wpcf7-submit"><span class="ajax-loader"></span>
    </div>
    </div>
    </div>
   </section>

    <!-- Products Grid -->
    <Products></Products>


    <!-- Our Bakers -->
    <section class="bg-light" id="bakers">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Our Amazing Bakers</h2>
            <h3 class="section-subheading">Lorem ipsum dolor sit amet consectetuipsum dolor sit amet consectetuipsum dolor sit amet consectetur.</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-sm-3"> 
            <div class="team-member">
         <img class="mx-auto rounded-circle" src="./assets/img/baker1.jpg" alt="baker">
              <h4>Kay Garland</h4>
               <p class="section-subheading" style="text-align:left">Lorem ipsum dolor sit amet consectetuipsum dolor sit amet consectetuipsum dolor sit amet consectetur.</p>
              <p class="text-muted">Pastry Chef</p>  
            </div>
          </div>
          <div class="col-sm-3">
            <div class="team-member">
             <img class="mx-auto rounded-circle" src="./assets/img/baker2.jpg" alt="baker">
              <h4>Larry Parker</h4>
                <p style="text-align:left">Lorem ipsum dolor sit amet consectetuipsum dolor sit amet consectetuipsum dolor sit amet consectetur.</p>
    
              <p class="text-muted">Head Baker</p>
              
            </div>
          </div>
          <div class="col-sm-3">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="./assets/img/baker3.jpg" alt="baker">
              <h4>Diana Pertersen</h4>
                <p style="text-align:left">Lorem ipsum dolor sit amet consectetuipsum dolor sit amet consectetuipsum dolor sit amet consectetur.</p>
              <p class="text-muted">Decorator</p>
            </div>
          </div>
                    <div class="col-sm-3">
            <div class="team-member">
              <img class="mx-auto rounded-circle" src="./assets/img/baker4.jpg" alt="baker">
              <h4>Diana Pertersen</h4> 
                <p style="text-align:left">Lorem ipsum dolor sit amet consectetuipsum dolor sit amet consectetuipsum dolor sit amet consectetur.</p>
              <p class="text-muted">Baker</p>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-8 mx-auto text-center">
            <p class="section-subheading">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut eaque, laboriosam veritatis, quos non quis ad perspiciatis, totam corporis ea, alias ut unde.</p>
          </div>
        </div>
      </div>
    </section>
    
    <!-- Contact -->
    <section id="contact">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Need to place a custom order?</h2>
            <h3 class="section-subheading" >Lorem ipsum dolor sit amet consectetur.</h3>
          </div>
        </div>
        <div class="row">
        <div class="col-sm-6">
            <form id="contactForm" name="sentMessage" novalidate="novalidate">
                  <div class="form-group">
                    <input class="form-control" id="name" type="text" placeholder="Your Name *" required="required" data-validation-required-message="Please enter your name.">
                    <p class="help-block text-danger"></p>
                  </div>
                  <div class="form-group">
                    <input class="form-control" id="email" type="email" placeholder="Your Email *" required="required" data-validation-required-message="Please enter your email address.">
                    <p class="help-block text-danger"></p>
                  </div>
                  <div class="form-group">
                    <input class="form-control" id="phone" type="tel" placeholder="Your Phone *" required="required" data-validation-required-message="Please enter your phone number.">
                    <p class="help-block text-danger"></p>
                  </div>                
                  <div class="form-group">
                    <textarea class="form-control" id="message" placeholder="Your Message *" required="required" data-validation-required-message="Please enter a message."></textarea>
                    <p class="help-block text-danger"></p>
                </div>  
                  <button id="sendMessageButton" class="btn btn-xl text-uppercase" type="submit" style="float:right">Send Message</button>       
            </form>
          </div>
          <div class="col-sm-3">   
          <img class="img-fluid d-block mx-auto" src="./assets/img/contact-image1.jpg" alt="" style="height:400px">
   </div>
          <div class="col-sm-3"><img class="img-fluid d-block mx-auto" src="./assets/img/contact-image2.jpg" alt="" style="height:400px">
   </div>
    </div>            
      </div>

    </section>

    <!-- Footer -->
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
          <br/>
          <br/>
            <span class="copyright">Copyright &copy; McLeddy 2020</span>
          </div>
          <div class="col-md-4">
          <br/>
            <img src="./assets/img/icon-twitter.png" alt="" style="height:50px; margin: 20px">
              <img src="./assets/img/icon-instagram.png" alt="" style="height:55px; margin: 20px">
                 <img src="./assets/img/icon-facebook.webp" alt="" style="height:55px; margin: 20px">
          </div>
           <div class="col-md-4">
<br/>
           Come See Us!
           <br/>
            999 Made Up Drive Tucson, AZ 99955
            <br/>
            (999) 955-9955
          </div>
        </div>
      </div>
    </footer>

    <!-- Product Modals -->

    <!-- Modal 1 -->
    <div class="products-modal modal fade" id="productsModal1" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-dismiss="modal">
            <div class="lr">
              <div class="rl"></div>
            </div>
          </div>
          <div class="container">
            <div class="row">
              <div class="col-lg-8 mx-auto">
                <div class="modal-body">
                  <!-- Project Details Go Here -->
                  <h2 class="text-uppercase">Donuts</h2>
                  <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>
                  <img class="img-fluid d-block mx-auto" src="img/products/01-full.jpg" alt="">
                  <p>Use this area to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo!</p>
                  <ul class="list-inline">
                    <li>Date: January 2017</li>
                    <li>Client: Threads</li>
                    <li>Category: Illustration</li>
                  </ul>
                  <button class="btn btn-primary" data-dismiss="modal" type="button">
                    <i class="fas fa-times"></i>
                    Close Project</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Modal 2 -->
    <div class="products-modal modal fade" id="productsModal2" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-dismiss="modal">
            <div class="lr">
              <div class="rl"></div>
            </div>
          </div>
          <div class="container">
            <div class="row">
              <div class="col-sm-12 mx-auto">
                <div class="modal-body">
                  <!-- Project Details Go Here -->
                  <h2 class="text-uppercase">Donuts</h2>
                  <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>      
                  <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>
                  <div class="row">
                  <div class="col-sm-3">
                  <h4>Classic Glazed</h4>
                            <br/>
                  <img class="img-fluid d-block mx-auto" src="./assets/img/glazeDonut.jpg" alt="">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3">
                            <h4>Old Fasioned Cake</h4>
                            <img class="img-fluid d-block mx-auto" src="./assets/img/strawberry.jpg" alt="">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3" style="margin-bottom:15px">
                         <h4>Chocolate Frosted</h4>
                                   <br/>
                         <img class="img-fluid d-block mx-auto" src="./assets/img/chocolateFrosted.jpg" alt="">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Strawberry</h4>
                                        <br/>
                                        <img class="img-fluid d-block mx-auto" src="./assets/img/strawberry.jpg" alt="">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Chocolate Frosted with Sprinkes</h4>
                                        <img class="img-fluid d-block mx-auto" src="./assets/img/strawberry.jpg" alt="">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Blueberry</h4>
                                        <br/>
                                        <img class="img-fluid d-block mx-auto" src="./assets/img/Blueberry.jpg" alt="">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Double Chocolate</h4>
                                                  <br/>
                  <img class="img-fluid d-block mx-auto" src="./assets/img/strawberry.jpg" alt="">
  
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Vanilla Frosted</h4>
                                                  <br/>
                                         <img class="img-fluid d-block mx-auto" src="./assets/img/vanilla.jpg" alt="">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                          <div class="col-sm-3">
                                        <h4>Cream-Filled</h4>
                                                  <br/>
                                        <img class="img-fluid d-block mx-auto" src="./assets/img/creamFilled.jpg" alt="">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditat.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Chocolate Frosted Cream-Filled</h4>
                                        <img class="img-fluid d-block mx-auto" src="./assets/img/chocolateFrostedFilled.jpg" alt="">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditat.</p>  
                  </div>
                </div> 
                
                  <button class="btn btn-primary" data-dismiss="modal" type="button">
                  <i class="fas fa-times"></i>
                  Close Project</button>
                </div>
             </div>
            </div>
            </div>
         </div>
        </div>
</div>
    <!-- Modal 3 -->
    <div class="products-modal modal fade" id="productsModal3" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-dismiss="modal">
            <div class="lr">
              <div class="rl"></div>
            </div>
          </div>
<div class="container">
            <div class="row">
              <div class="col-sm-12 mx-auto">
                <div class="modal-body">
                  <!-- Project Details Go Here -->
                  <h2 class="text-uppercase">Cakes</h2>
                  <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>      
                  <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>
                  <div class="row">
                  <div class="col-sm-3">
                  <h4>Carrot Cake</h4>
                  <img class="img-fluid d-block mx-auto item" src="./assets/img/strawberry.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3">
                            <h4>Vanilla Cake</h4>
                            <img class="img-fluid d-block mx-auto item" src="./assets/img/cake-vanilla.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3" style="margin-bottom:15px">
                         <h4>Chocolate Cake</h4>
                         <img class="img-fluid d-block mx-auto item" src="./assets/img/cake-chocolate.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Cream Cake</h4>               
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/cake-cream.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Red Velvet Cake</h4>
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/cake-red-velvet.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Devil's Cake</h4>
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/strawberry.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Cheese Cake</h4>
                  <img class="img-fluid d-block mx-auto item" src="./assets/img/cake-cheese.jpg" alt="" style="height:250px">
  
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>                    
                </div> 
                
                  <button class="btn btn-primary" data-dismiss="modal" type="button">
                  <i class="fas fa-times"></i>
                  Close Project</button>
                </div>
             </div>
            </div>
            </div>
            </div>
      </div>
    </div>

    <!-- Modal 4 -->
    <div class="products-modal modal fade" id="productsModal4" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-dismiss="modal">
            <div class="lr">
              <div class="rl"></div>
            </div>
          </div>
         <div class="container">
            <div class="row">
              <div class="col-sm-12 mx-auto">
                <div class="modal-body">
                  <!-- Project Details Go Here -->
                  <h2 class="text-uppercase">Pastries</h2>
                  <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>      
                  <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>
                  <div class="row">
                  <div class="col-sm-3">
                  <h4>Blueberry Tart</h4>
                  <img class="img-fluid d-block mx-auto item" src="./assets/img/pastries-blueberry-tart.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3">
                            <h4>Lemon Tart</h4>
                            <img class="img-fluid d-block mx-auto item" src="./assets/img/pastries-lemon-tart.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3" style="margin-bottom:15px">
                         <h4>Cannoili</h4>
                         <img class="img-fluid d-block mx-auto item" src="./assets/img/pastries-cannoli.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Apple Pie</h4>               
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/pie-apple.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Blueberry Pie</h4>
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/strawberry.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Cherry Pie</h4>
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/strawberry.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Pumpkin Pie</h4>
                  <img class="img-fluid d-block mx-auto item" src="./assets/img/pie-pumpkin.jpg" alt="" style="height:250px">
  
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>     
                                 <div class="col-sm-3">
                                        <h4>Key Lime Pie</h4>
                  <img class="img-fluid d-block mx-auto item" src="./assets/img/pie-key-lime.jpg" alt="" style="height:250px">
  
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>     
                                 
                </div> 
                
                  <button class="btn btn-primary" data-dismiss="modal" type="button">
                  <i class="fas fa-times"></i>
                  Close Project</button>
                </div>
             </div>
            </div>
            </div>
            </div>
      </div>
    </div>

    <!-- Modal 5 -->
    <div class="products-modal modal fade" id="productsModal5" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-dismiss="modal">
            <div class="lr">
              <div class="rl"></div>
            </div>
          </div>
                   <div class="container">
            <div class="row">
              <div class="col-sm-12 mx-auto">
                <div class="modal-body">
                  <!-- Project Details Go Here -->
                  <h2 class="text-uppercase">Pastries</h2>
                  <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>      
                  <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>
                  <div class="row">
                  <div class="col-sm-3">
                  <h4>Ham and Cheese Quiche</h4>
                  <img class="img-fluid d-block mx-auto item" src="./assets/img/strawberry.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3">
                            <h4>Spinach Quiche</h4>
                            <img class="img-fluid d-block mx-auto item" src="./assets/img/savory-spinach-quiche.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3" style="margin-bottom:15px">
                         <h4>Chicken Quiche</h4>
                         <img class="img-fluid d-block mx-auto item" src="./assets/img/savory-chicken-quiche.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Ham and Cheese Croissant</h4>               
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/strawberry.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Spinach Croissant</h4>
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/savory-spinach-croissant.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                </div>                
                  <button class="btn btn-primary" data-dismiss="modal" type="button">
                  <i class="fas fa-times"></i>
                  Close Project</button>
                </div>
             </div>
            </div>
            </div>           
        </div>
      </div>
    </div>

    <!-- Modal 6 -->
    <div class="products-modal modal fade" id="productsModal6" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-dismiss="modal">
            <div class="lr">
              <div class="rl"></div>
            </div>
          </div>
                            <div class="container">
            <div class="row">
              <div class="col-sm-12 mx-auto">
                <div class="modal-body">
                  <!-- Project Details Go Here -->
                  <h2 class="text-uppercase">Cookies</h2>
                  <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>      
                  <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>
                  <div class="row">
                  <div class="col-sm-3">
                  <h4>Lemon Cookie</h4>
                  <img class="img-fluid d-block mx-auto item" src="./assets/img/cookies-lemon.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3">
                            <h4>Chocolate Chip Cookie</h4>
                            <img class="img-fluid d-block mx-auto item" src="./assets/img/cookie-chocolate-chip.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3" style="margin-bottom:15px">
                         <h4>M&M Cookie</h4>
                         <img class="img-fluid d-block mx-auto item" src="./assets/img/cookie-m&m.jpeg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Oatmeal Raisin Cookie</h4>               
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/cookie-oatmeal-raisin.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Macadamia Nut Cookie</h4>
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/cookie-white-chocolate.png" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                                      <div class="col-sm-3">
                                        <h4>Peanut Butter Cookie</h4>
                                        <br/>
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/cookie-peanutbutter.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                </div>                
                  <button class="btn btn-primary" data-dismiss="modal" type="button">
                  <i class="fas fa-times"></i>
                  Close Project</button>
                </div>
             </div>
            </div>
            </div>     
        </div>
      </div>
      
    </div>
    <!-- Modal 7 -->
    <div class="products-modal modal fade" id="productsModal7" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="close-modal" data-dismiss="modal">
            <div class="lr">
              <div class="rl"></div>
            </div>
          </div>
                            <div class="container">
            <div class="row">
              <div class="col-sm-12 mx-auto">
                <div class="modal-body">
                  <!-- Project Details Go Here -->
                  <h2 class="text-uppercase">Bread</h2>
                  <p class="item-intro text-muted">Lorem ipsum dolor sit amet consectetur.</p>      
                  <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>
                  <div class="row">
                  <div class="col-sm-3">
                  <h4>Focaccia</h4>
                  <img class="img-fluid d-block mx-auto item" src="./assets/img/bread-focaccia.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3">
                            <h4>Chiabatta</h4>
                            <img class="img-fluid d-block mx-auto item" src="./assets/img/strawberry.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                     <div class="col-sm-3" style="margin-bottom:15px">
                         <h4>Rye</h4>
                         <img class="img-fluid d-block mx-auto item" src="./assets/img/bread-rye.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Croissant</h4>               
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/pastries-croissant.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                  <div class="col-sm-3">
                                        <h4>Baguette</h4>               
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/bread-baguette.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                    <div class="col-sm-3">
                                        <h4>Banana Bread</h4>
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/bread-banana.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                                                      <div class="col-sm-3">
                                        <h4>Pumpkin Bread</h4>
                                        <img class="img-fluid d-block mx-auto item" src="./assets/img/strawberry.jpg" alt="" style="height:250px">
                 <p>Eaperiam quasi sunt officia expedita beatae cupiditate.</p>  
                  </div>
                </div>                
                  <button class="btn btn-primary" data-dismiss="modal" type="button">
                  <i class="fas fa-times"></i>
                  Close Project</button>
                </div>
             </div>
            </div>
            </div>     
        </div>
      </div>
      </div>
  </div>
</template>

<script>

import Products from './components/Products'

export default {
  name: 'app',
  components: {
    Products
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background: black;
}
</style>
