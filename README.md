<!DOCTYPE html>
<html lang="en-US">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="refresh" content="40">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="style.css">
        <link rel="icon" type="image/x-icon" href="apple-touch-icon.png">
        <title>
          NIKE
        </title>
    </head>
    <body>
      <div class="sidebar">
        <img src="nike-png-12874.png" class="logo" alt="nike logo">
        <div class="menu">
        <a  href="index.html">Home</a>
        <a href="Product.html">Products</a>
        <a href="support.html">Support</a>
      </div>
      </div>
      <img src="freedy.jpg" alt="Nike air">
      <script src="script.js"></script>
    </body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products</title>
    <link rel="stylesheet" href="style2.css">
    <link rel="icon" type="image/x-icon" href="apple-touch-icon.png">
</head>
<body>
    <div class="sidebar">
        <img src="nike-png-12874.png" class="logo" alt="nike logo">
        <div class="menu">
        <a  href="index.html">Home</a>
        <a href="Product.html">Products</a>
        <a href="support.html">Support</a>
        </div>
      </div>
    <div class="product-container">
        <div class="product-card">
            <img src="Air1.jpg" alt="Product 1" class="product-image">
            <h3 class="product-title">Air Force 1</h3>
            <p class="product-description">classic style and cushioned comfort with the iconic Nike Air Force 1 </p>
            <button class="btn">Buy</button>
        </div>
        <div class="product-card">
            <img src="Air2.jpg" alt="Product 2" class="product-image">
            <h3 class="product-title">Air versanity</h3>
            <p class="product-description">The dual nature of the shoe, catering to those looking for athletic functionality and style.</p>
            <button class="btn">Buy</button>
        </div>
        <div class="product-card">
            <img src="Air3.jpg" alt="Product 1" class="product-image">
            <h3 class="product-title">Nike Runner PRO</h3>
            <p class="product-description">Hit the ground running with the Nike Air Runner.</p>
            <button class="btn">Buy</button>
        </div>
        <div class="product-card">
            <img src="Air4.jpg" alt="Product 2" class="product-image">
            <h3 class="product-title">Nike comfort</h3>
            <p class="product-description">Slip into unmatched comfort with the Nike Air Comfort.</p>
            <button class="btn">Buy</button>
        </div>
        <div class="product-card">
            <img src="Air5.jpg" alt="Product 1" class="product-image">
            <h3 class="product-title">Nike Air Jordan S1</h3>
            <p class="product-description">Step into a legacy of performance and streetwear prestige with the Nike Air Jordan 1.</p>
            <button class="btn">Buy</button>
        </div>
        <div class="product-card">
            <img src="Air6.jpg" alt="Product 2" class="product-image">
            <h3 class="product-title">Air Max 5</h3>
            <p class="product-description">The notable Air cushioning technology and the blend of style and performance</p>
            <button class="btn">Buy</button>
        </div>
        </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en-US">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="refresh" content="40">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="style1.css">
        <link rel="icon" type="image/x-icon" href="apple-touch-icon.png">
        <title>
          NIKE
        </title>
    </head>
    <body>
      <div class="sidebar">
        <img src="nike-png-12874.png" class="logo" alt="nike logo">
        <div class="menu">
        <a  href="index.html">Home</a>
        <a href="Product.html">Products</a>
        <a href="support.html">Support</a>
      </div>
      </div>
      <div class="container">  
        <form id="contact" action="" method="post">
          <h3>Contact Form</h3>
          <h4>Contact us</h4>
          <fieldset>
            <input placeholder="Your name" type="text" tabindex="1" required autofocus>
          </fieldset>
          <fieldset>
            <input placeholder="Your Email Address" type="email" tabindex="2" required>
          </fieldset>
          <fieldset>
            <input placeholder="Your Phone Number (optional)" type="tel" tabindex="3">
          </fieldset>
          <fieldset>
            <input placeholder="Your Web Site (optional)" type="url" tabindex="4" >
          </fieldset>
          <fieldset>
            <textarea placeholder="Type your message here...." tabindex="5" required></textarea>
          </fieldset>
          <fieldset>
            <button name="submit" type="submit" id="contact-submit" data-submit="...Sending">Submit</button>
          </fieldset>
        </form>
      </div>
    </body>
    </html>

    body {
    margin: 0;
    font-family:Helvetica;
    display: flex;
  }
  img{
    width: 100%;
    position: relative;
    display: block;
    height: auto;
    object-fit: fill;
  }
  
  /* Improved CSS keeping your original structure in mind */
.sidebar {
  width: 100%;
  background-color: #09131c;
  display: flex;
  align-items: center; /* Ensure vertical alignment is centered */
  position: fixed;
  top: 0; /* Explicitly define it's at the top */
  height: 60px; /* Adjusted to accommodate the logo better */
  z-index: 1000; /* Ensure it's above other content */
}

.logo {
  width: 70px; /* Original size, consider responsive adjustments below */
  height: 70px;
  margin-left: 25px;
}

.menu {
  margin-left: auto; /* Pushes the menu to the right */
  display: flex;
  align-items: center; /* Center items vertically */
}

.sidebar a {
  color: white;
  font-size: larger; /* adjusted for better readability */
  font-weight: bolder;
  padding: 10px;
  text-decoration: none;
  display: inline-flex; /* Improve alignment and spacing */
  align-items: center; /* Center text vertically */
}

.sidebar a:hover:not(.active) {
  color: #00f502;
}

@media screen and (max-width: 400px) {
  .sidebar {
      height: auto; /* Allow natural height adjustment */
      flex-direction: column; /* Stack items vertically */
  }
  .logo {
      width: 50px; /* Adjusted for smaller screens */
      height: 50px;
      margin-left: 10px; /* Adjust margin for smaller screens */
  }
  .menu {
      margin-left: 0; /* Adjust for smaller screens */
      width: 100%; /* Full width for easier navigation */
      justify-content: center; /* Center menu items */
  }
  .sidebar a {
      text-align: center;
      padding: 8px 0; /* Adjust padding for a stacked layout */
      width: 100%; /* Full width links for easier tap targets */
  }
}

