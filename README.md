# Ex.07 Restaurant Website
## Date:28.11.2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
home.html

```
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Restraunt</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
        integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css" />
    <script type="text/javascript">
        
    </script>
</head>

<body>
    <nav class="navbar">
        <div class="navbar-container container">
            <input type="checkbox" name="" id="">
            <div class="hamburger-lines">
                <span class="line line1"></span>
                <span class="line line2"></span>
                <span class="line line3"></span>
            </div>
            <ul class="menu-items">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#food">Category</a></li>
                <li><a href="#food-menu">Menu</a></li>
               <li><a href="#openinghours">Opening Hours</a></li>
               <li><a href="#contact">Contact</a></li>
               <li><a href="#administration">Adminstration</a></li>
                <li><a href="#testimonials">Reviews</a></li>
                
            </ul>
            <h1 class="logo">DR</h1>
        </div>
    </nav>
    <section class="showcase-area" id="home">
        <div class="showcase-container">
            <h1 class="main-title">Dharsh Restaurant</h1>
            <p>Eat Right Food</p>
            <p>Eat Healty, it is good for our health.</p>
            <a href="#food-menu" class="btn btn-primary">Menu</a>
        </div>
    </section>
    
    <section class="nav-item active" id="about">
        <div class="about-wrapper container">
            <div class="about-text">
                <p class="small">About Us</p>
                <h2>We've beem making healthy food last for 10 years</h2>
                <p>
                    Crafting healthy, delicious meals for a decade, we’re proud to be your go-to destination for wholesome dining.
                    Our dishes are made with love, fresh ingredients, and a passion for flavor.
                    Whether you’re looking for a quick bite or a hearty meal, we’ve got you covered.
                    Savor the taste of health and happiness, perfected over 10 years.
                    Come dine with us, where every bite nourishes your body and soul!
                </p>
            </div>
            <div class="about-img">
                <img src="https://i.postimg.cc/mgpwzmx9/about-photo.jpg" alt="food" />
            </div>
        </div>
    </section>
        <section id="food">
            <h2>Category</h2>
            <div class="food-container container">
                <div class="food-type fruite">
                    <div class="img-container">
                        <img src="https://i.postimg.cc/yxThVPXk/food1.jpg" alt="error" />
                        <div class="img-content">
                            <h3>fruite</h3>
                            <a href="https://en.wikipedia.org/wiki/Fruit" class="btn btn-primary" target="blank">learn
                                more</a>
                        </div>
                    </div>
                </div>
                <div class="food-type vegetable">
                    <div class="img-container">
                        <img src="https://i.postimg.cc/Nffm6Rkk/food2.jpg" alt="error" />
                        <div class="img-content">
                            <h3>vegetable</h3>
                            <a href="https://en.wikipedia.org/wiki/Vegetable" class="btn btn-primary" target="blank">learn
                                more</a>
                        </div>
                    </div>
                </div>
                <div class="food-type grin">
                    <div class="img-container">
                        <img src="https://i.postimg.cc/76ZwsPsd/food3.jpg" alt="error" />
                        <div class="img-content">
                            <h3>grin</h3>
                            <a href="https://en.wikipedia.org/wiki/Grain" class="btn btn-primary" target="blank">learn
                                more</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    <section class="nav-item"  id="food-menu">
        <h1>Food Menu</h1>
        <div class="food-menu-container container">
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/wTLMsvSQ/food-menu1.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 1</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 280</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/sgzXPzzd/food-menu2.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 2</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 180</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/8zbCtYkF/food-menu3.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 3</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 250</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/Yq98p5Z7/food-menu4.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 4</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 200</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/sgzXPzzd/food-menu2.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 5</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 220</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/Yq98p5Z7/food-menu4.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 6</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 200</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/KYnDqxkP/food-menu5.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 7</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 150</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/Jnxc8xQt/food-menu6.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 8</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 200</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/wTLMsvSQ/food-menu1.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 9</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 180</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/Nffm6Rkk/food-menu2.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 10</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 300</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/76ZwsPsd/food-menu3.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 11</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 250</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/Yq98p5Z7/food-menu4.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-title">Food Menu Item 12</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, quae.</p>
                    <p class="food-price">Price: &#8377; 220</p>
                </div>
            </div>
        </div>
    </section>
    
   
    <section class="nav-item"  id="contact">
        <div class="contact-container container">
            <div class="contact-img">
                <img src="https://i.postimg.cc/1XvYM67V/restraunt2.jpg" alt="" />
            </div>
             
            <div class="form-container">
                <h2>Contact Us</h2>
                <input type="text" placeholder="Your Name" />
                <input type="email" placeholder="E-Mail" />
                <input type="phone no" placeholder="Phone no" />
                <textarea cols="30" rows="6" placeholder="Type Your Message"></textarea>
                <a href="#" class="btn btn-primary">Submit</a>
            </div>
        </div>
    </section>
   
    <section class="nav-item"  id="openinghours">
        <div class="Opening Hours-container container">
            <div class="Opening Hours-description">
                <h2 class="Opening Hours-titile"></h2>
                <h2>OPENING HOURS</h2>
                <p><span class="day">Monday to Friday:</span> 8:00 AM – 11:00 PM</p>

                <p><span class="day">Saturday:</span> 11:00 AM – 11:00 PM</p>

                <p><span class="day">Sunday:</span> 7:00 AM – 11:00 PM</p>
            </div>

            <div class="form-container">
                <br/>
                <h2>Table No</h2>
               
                <input type="Name" placeholder="Your Name" />
                <input type="email" placeholder="E-Mail" />
                <input type="contact no" placeholder="contact no" />
                <textarea cols="15" rows="2" placeholder="Slot of table time"></textarea>
                <a href="#" class="btn btn-primary">Submit</a>
            </div>
        </div>
    </section>
    <section class="nav-item"  id="testimonials">
        <h2 class="Reviews-title">What Our Customers Say</h2>
        <div class="testimonial-container container">
            <div class="testimonial-box">
                <div class="customer-detail">
                    <div class="customer-photo">
                        <img src="https://i.postimg.cc/5Nrw360Y/male-photo1.jpg" alt="" />
                        <p class="customer-name">Ross Lee</p>
                    </div>
                </div>
                <div class="star-rating">
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                </div>
                <p class="testimonial-text">
                    Highly recommend to anyone looking
                    for meals that are good for the body and soul
                   
                </p>

            </div>
            <div class="testimonial-box">
                <div class="customer-detail">
                    <div class="customer-photo">
                        <img src="https://i.postimg.cc/sxd2xCD2/female-photo1.jpg" alt="" />
                        <p class="customer-name">Amelia Watson</p>
                    </div>
                </div>
                <div class="star-rating">
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                </div>
                <p class="testimonial-text">
                    It's rare to find meals
                     that are both nutritious
                    and delicious, 
                    but this place nails it every time.
                    The quality is consistent,
                     and the variety keeps it exciting. 
                </p>

            </div>
            <div class="testimonial-box">
                <div class="customer-detail">
                    <div class="customer-photo">
                        <img src="https://i.postimg.cc/fy90qvkV/male-photo3.jpg" alt="" />
                        <p class="customer-name">Ben Roy</p>
                    </div>
                </div>
                <div class="star-rating">
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                </div>
                <p class="testimonial-text">
                    Absolutely love the food!
                    Everything is so fresh, healthy, and packed with flavor.
                    You can tell a lot of care goes into every dish. 
                </p>

            </div>
        </div>
    </section>
    <section class="nav-item" id="administration">
        <h1>Administration</h1>
        <br/>
        <br/>
        <div class="administration-container container">
            <div class="cssImag">
                <img src="1.png" alt="" />
                <div>Dharsheni</div>
                <p>Restaurant Manager</p>
            </div>
            <div class="cssImag">
                <img src="2.png" alt="" />
                <div>Vijay devarakonda </div>
                <p>Executive Chef</p>
            </div>
            <div class="cssImag">
                <img src="3.png" alt="" />
                <div>Vijay</div>
                <p>Sous Chef</p>
            </div>
            <div class="cssImag">
                <img src="4.png" alt="" />
                <div>Surya</div>
                <p>Front-of-House Manager</p>
            </div>
            <div class="cssImag">
                <img src="5.png" alt="" />
                <div>Dhanush</div>
                <p>Marketing Manager</p>
            </div>
            <div class="cssImag">
                <img src="6.png" alt="" />
                <div>Sivakarthikeyan</div>
                <p>Operations Manager</p>
            </div>
        </div>
    </section>
    <footer id="footer">
        <h2>Restraunt &copy; all rights reserved. Designed and developed by Dharsheni K</h2>
    </footer>
    <!-- .................../ JS Code for smooth scrolling /...................... -->

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="app.js"></script>

</html>

</body>

</html>
```
CSS
```
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

*,
*::after,
*::before {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

.html {
  font-size: 62.5%;
}

body {
  font-family: "Poppins", sans-serif;
}

/* ///////////..utility classes../////////// */


.container {
  max-width: 1200px;
  width: 90%;
  margin: auto;
}

.btn {
  display: inline-block;
  padding: 0.5em 1.5em;
  text-decoration: none;
  border-radius: 50px;
  cursor: pointer;
  outline: none;
  margin-top: 1em;
  text-transform: uppercase;
  font-weight: small;
}

.btn-primary {
  color: #fff;
  background: #16a083;
}

.btn-primary:hover {
  background: #117964;
  transition: background 0.3s ease-in-out;
}

/* ............/navbar/............ *

/* desktop mode............/// */

.navbar input[type="checkbox"],
.navbar .hamburger-lines {
  display: none;
}

.navbar {
  box-shadow: 0px 5px 10px 0px #aaa;
  position: fixed;
  width: 100%;
  background: #fff;
  color: #000;
  opacity: 0.85;
  height: 50px;
  z-index: 12;
}

.navbar-container {
  display: flex;
  justify-content: space-between;
  height: 64px;
  align-items: center;
}

.menu-items {
  order: 2;
  display: flex;
}

.menu-items li {
  list-style: none;
  margin-left: 1.5rem;
  margin-bottom: 0.5rem;
  font-size: 1.2rem;
}

.menu-items a {
  text-decoration: none;
  color: #444;
  font-weight: 500;
  transition: color 0.3s ease-in-out;
}

.menu-items a:hover {
  color: #117964;
  transition: color 0.3s ease-in-out;
}

.logo {
  order: 1;
  font-size: 2.3rem;
  margin-bottom: 0.5rem;
}

/* ............//// Showcase styling ////......... */

.showcase-area {
  height: 50vh;
  background: linear-gradient(
      rgba(240, 240, 240, 0.144),
      rgba(255, 255, 255, 0.336)
    ),
    url("https://i.postimg.cc/wT3TQS3V/header-image2.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.showcase-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100%;
  font-size: 1.6rem;
}

.main-title {
  text-transform: uppercase;
  margin-top: 1.5em;
}

/* ......//about us//...... */

#about {
  padding: 50px 0;
  background: #f5f5f7;
}

.about-wrapper {
  display: flex;
  flex-wrap: wrap;
}

#about h2 {
  font-size: 2.3rem;
}

#about p {
  font-size: 1.2rem;
  color: #555;
}

#about .small {
  font-size: 1.2rem;
  color: #666;
  font-weight: 600;
}

.about-img {
  flex: 1 1 400px;
  padding: 30px;
  transform: translateX(150%);
  animation: about-img-animation 1s ease-in-out forwards;
}

@keyframes about-img-animation {
  100% {
    transform: translate(0);
  }
}

.about-text {
  flex: 1 1 400px;
  padding: 30px;
  margin: auto;
  transform: translate(-150%);
  animation: about-text-animation 1s ease-in-out forwards;
}

@keyframes about-text-animation {
  100% {
    transform: translate(0);
  }
}

.about-img img {
  display: block;
  height: 400px;
  max-width: 100%;
  margin: auto;
  object-fit: cover;
  object-position: right;
}

/* ..........////Administration category///........... */

#administration {
    padding: 5rem 0 10rem 0;
  }
  #administration h1 {
    text-align: center;
    font-size: 2.5rem;
    font-weight: 400;
    margin-bottom: 40px;
    text-transform: uppercase;
    color: #555;
  }
  
  .administration-container {
    display: flex;
    justify-content: space-between;
  }
  .administration-container .cssImag div {
    font-weight: bold;
    text-align: center;
  }
  .administration-container .cssImag p {
    text-align: center;
  }
  .administration-container img {
    display: block;
    width: 100px;
    height: 100px;
    border-radius: 50px;
    margin: auto;
    max-height: 300px;
    object-fit: cover;
    object-position: center;
  }
  
  

/* ..........////Food category///........... */

#food {
  padding: 5rem 0 10rem 0;
}

#food h2 {
  text-align: center;
  font-size: 2.5rem;
  font-weight: 400;
  margin-bottom: 40px;
  text-transform: uppercase;
  color: #555;
}

.food-container {
  display: flex;
  justify-content: space-between;
}

.food-container img {
  display: block;
  width: 100%;
  margin: auto;
  max-height: 300px;
  object-fit: cover;
  object-position: center;
}

.img-container {
  margin: 0 1rem;
  position: relative;
}

.img-content {
  position: absolute;
  top: 70%;
  left: 50%;
  transform: translate(-50%, -50%);
  opacity: 0;
  z-index: 2;
  text-align: center;
  transition: all 0.3s ease-in-out 0.1s;
}

.img-content h3 {
  color: #fff;
  font-size: 2.2rem;
}

.img-content a {
  font-size: 1.2rem;
}

.img-container::after {
  content: "";
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.871);
  opacity: 0;
  z-index: 1;

  transform: scaleY(0);
  transform-origin: 100% 100%;
  transition: all 0.3s ease-in-out;
}

.img-container:hover::after {
  opacity: 1;
  transform: scaleY(1);
}

.img-container:hover .img-content {
  opacity: 1;
  top: 40%;
}

/* .........../Opening Hours/............ */
#openinghours {
    padding: 5rem 0 10rem 0;
  }

  #openinghours h1 {
    text-align: center;
    font-size: 2.5rem;
    font-weight: 400;
    text-transform: uppercase;
    color: #555;
  }

.openinghours-heading {
  text-align: center;
  font-size: 3.4rem;
  font-weight: 400;
  color: #666;
}

.openinghours-container {
  display: flex;
  flex-wrap: wrap;
  padding: 50px 0px 30px 0px;
}


/* .........../Food Menu/............ */
#food-menu {
    padding: 5rem 0 10rem 0;
  }

  #food-menu h1 {
    text-align: center;
    font-size: 2.5rem;
    font-weight: 400;
    text-transform: uppercase;
    color: #555;
  }

.food-menu-heading {
  text-align: center;
  font-size: 3.4rem;
  font-weight: 400;
  color: #666;
}

.food-menu-container {
  display: flex;
  flex-wrap: wrap;
  padding: 50px 0px 30px 0px;
}

.food-menu-container img {
  display: block;
  width: 250px;
  height: 250px;
  border-radius: 50%;
  object-fit: cover;
  object-position: center;
}

.food-menu-item {
  display: flex;
  flex: 1 1 600px;
  justify-content: space-evenly;
  margin-bottom: 3rem;
}

.food-description {
  margin: auto 1.5rem;
}

.font-title {
  font-size: 1.8rem;
  font-weight: 400;
  color: #444;
}

.food-description p {
  font-size: 1.4rem;
  color: #555;
  font-weight: 500;
}

.food-description .food-price {
  color: #117964;
  font-weight: 700;
}

/* ........./ Testimonial /.......... */

#testimonials {
  padding: 5rem 0;
  background: rgba(243, 243, 243);
}

.testimonial-title {
  text-align: center;
  font-size: 2.8rem;
  font-weight: 400;
  color: #555;
}

.testimonial-container {
  display: flex;
  justify-content: space-between;
  font-size: 1.4rem;
  padding: 1rem;
}

.testimonial-box .checked {
  color: #ff9529;
}

.testimonial-box .testimonial-text {
  margin: 1rem 0;
  color: #444;
}

.testimonial-box {
  text-align: center;
  padding: 1rem;
}

.customer-photo img {
  display: block;
  width: 150px;
  height: 150px;
  object-fit: cover;
  object-position: center;
  border-radius: 50%;
  margin: auto;
}

/* ........ Contact Us........... */

#contact {
  padding: 5rem 0;
  background: rgb(226, 226, 226);
}

.contact-container {
  display: flex;
  background: #fff;
}

.contact-img {
  width: 50%;
}

.contact-img img {
  display: block;
  height: 400px;
  width: 100%;
  object-position: center;
  object-fit: cover;
}

.form-container {
  padding: 1rem;
  width: 50%;
  margin: auto;
}

.form-container input {
  display: block;
  width: 100%;
  border: none;
  border-bottom: 2px solid #ddd;
  padding: 1rem 0;
  box-shadow: none;
  outline: none;
  margin-bottom: 1rem;
  color: #444;
  font-weight: 500;
}

.form-container textarea {
  display: block;
  width: 100%;
  border: none;
  border-bottom: 2px solid #ddd;
  color: #444;
  outline: none;
  padding: 1rem 0;
  resize: none;
}

.form-container h2 {
  font-size: 2.7rem;
  font-weight: 500;
  color: #444;
  margin-bottom: 1rem;
  margin-top: -1.2rem;
}

.form-container a {
  font-size: 1.3rem;
}

#footer h2 {
  text-align: center;
  font-size: 1.8rem;
  padding: 2.6rem;
  font-weight: 500;
  color: #fff;
  background: rgb(65, 65, 65);
}

/* ......../ media query /.......... */

@media (max-width: 768px) {
  .navbar {
    opacity: 0.95;
  }

  .navbar-container input[type="checkbox"],
  .navbar-container .hamburger-lines {
    display: block;
  }

  .navbar-container {
    display: block;
    position: relative;
    height: 64px;
  }

  .navbar-container input[type="checkbox"] {
    position: absolute;
    display: block;
    height: 32px;
    width: 30px;
    top: 20px;
    left: 20px;
    z-index: 5;
    opacity: 0;
  }

  .navbar-container .hamburger-lines {
    display: block;
    height: 23px;
    width: 35px;
    position: absolute;
    top: 17px;
    left: 20px;
    z-index: 2;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  .navbar-container .hamburger-lines .line {
    display: block;
    height: 4px;
    width: 100%;
    border-radius: 10px;
    background: #333;
  }

  .navbar-container .hamburger-lines .line1 {
    transform-origin: 0% 0%;
    transition: transform 0.4s ease-in-out;
  }

  .navbar-container .hamburger-lines .line2 {
    transition: transform 0.2s ease-in-out;
  }

  .navbar-container .hamburger-lines .line3 {
    transform-origin: 0% 100%;
    transition: transform 0.4s ease-in-out;
  }

  .navbar .menu-items {
    padding-top: 100px;
    background: #fff;
    height: 100vh;
    max-width: 300px;
    transform: translate(-150%);
    display: flex;
    flex-direction: column;
    margin-left: -40px;
    padding-left: 50px;
    transition: transform 0.5s ease-in-out;
    box-shadow: 5px 0px 10px 0px #aaa;
  }

  .navbar .menu-items li {
    margin-bottom: 1.5rem;
    font-size: 1.3rem;
    font-weight: 500;
  }

  .logo {
    position: absolute;
    top: 5px;
    right: 15px;
    font-size: 2rem;
  }

  .navbar-container input[type="checkbox"]:checked ~ .menu-items {
    transform: translateX(0);
  }

  .navbar-container input[type="checkbox"]:checked ~ .hamburger-lines .line1 {
    transform: rotate(35deg);
  }

  .navbar-container input[type="checkbox"]:checked ~ .hamburger-lines .line2 {
    transform: scaleY(0);
  }

  .navbar-container input[type="checkbox"]:checked ~ .hamburger-lines .line3 {
    transform: rotate(-35deg);
  }

  /* ......./ food /......... */

  .food-container {
    flex-direction: column;
    align-items: stretch;
  }

  .food-type:not(:last-child) {
    margin-bottom: 3rem;
  }

  .food-type {
    box-shadow: 5px 5px 10px 0 #aaa;
  }

  .img-container {
    margin: 0;
  }
}

@media (max-width: 500px) {
  html {
    font-size: 65%;
  }

  .navbar .menu-items li {
    font-size: 1.6rem;
  }

  .testimonial-container {
    flex-direction: column;
    text-align: center;
  }

  .food-menu-container img {
    margin: auto;
  }

  .food-menu-item {
    flex-direction: column;
    text-align: center;
  }

  .form-container {
    width: 90%;
  }

  .contact-container {
    display: flex;
    flex-direction: column;
  }

  .contact-img {
    width: 90%;
    margin: 3rem auto;
  }

  .logo {
    position: absolute;
    top: 06px;
    right: 15px;
    font-size: 3rem;
  }

  .navbar .menu-items li {
    margin-bottom: 2.5rem;
    font-size: 1.8rem;
    font-weight: 500;
  }

  
}

@media (min-width: 769px) and (max-width: 1200px) {
  .img-container h3 {
    font-size: 1.5rem;
  }

  .img-container .btn {
    font-size: 0.7rem;
  }
}

@media (orientation: landscape) and (max-height: 500px) {
  .showcase-area {
    height: 50vmax;
  }
}
```

## OUTPUT:
![alt text](dharsheni/restapp/static/HOME.png)
![alt text](dharsheni/restapp/static/ABOUT.png)
![alt text](dharsheni/restapp/static/CATEGORY.png)
![alt text](dharsheni/restapp/static/MENU.png)
![alt text](dharsheni/restapp/static/OPEN.png)
![alt text](dharsheni/restapp/static/CONTACT.png)
![alt text](dharsheni/restapp/static/REVIEWS.png)
![alt text](dharsheni/restapp/static/ADMINISTRATION.png)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
