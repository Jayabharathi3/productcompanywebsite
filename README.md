# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
Developed By: JAYABHARATHI.S
Register No: 212222100013
```
### layout.css
```css
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 350px;
  text-align: center;
  font-size: 80px;
  background-image: url("/static/img/backpro.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #4107c7;
  font-family: segoe print ;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
```
### home.html

```css
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FRESHWORKS</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">FRESHWORKS...</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/lohofr.jpg" alt="Building" />
          <div class="contenttext">
            Freshworks makes it fast and easy for businesses to delight their customers and employees.
          Happy customers. Ecstatic employees. Choose one. Or all. You will see better customer
          relationships and happier employees without the bloat, hassle, and expense of typical business software.
          To understand what it's like to work at Freshworks, it's important to understand Kudumba  a term derived 
          from the Tamil word for "family". It describes our culture perfectly: an eclectic, diverse family focused
          on one purpose: to help more people succeed, by continually finding better, more sustainable, more human
          ways to work.

            <br />

            Our purpose inspires and empowers us. Our community provides the trust you need to bring 
          your whole self to work and achieve more than you ever thought possible. Our growth potential is 
          unlimited for the same reason our Kudumba is so strong because there is always a new way to define success. 

            <ul>
              <li>Craftsmanship</li>
              <li>Happy 'work' environment</li>
              <li>Agility with accountability</li>
              <li>True friend of the customer</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#192; 2023 FW Private Limited, Developed by JAYABHARATHI.
      </div>
    </div>
  </body>
</html>
```
### products.html
```css

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FRESHWORKS</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.jpeg type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">FRESHWORKS...</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product1.png" alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product2.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL</div>
              </div> 
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product3.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product4.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product5.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product6.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">PFREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product7.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product8.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product9.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product10.png"  alt="product image">
                  </div>
                  <div class="itemname">Olay</div>
                  <div class="itemprice">Sign In</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product11.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product12.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#192; FW Private Limited, Developed by JAYABHARATHI.
      </div>
    </div>
  </body>
</html>
```
### people.html

```css
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FRESHWORKS</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.jpeg type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">FRESHWORKS...</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product1.png" alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product2.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL</div>
              </div> 
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product3.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product4.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product5.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product6.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">PFREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product7.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product8.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product9.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product10.png"  alt="product image">
                  </div>
                  <div class="itemname">Olay</div>
                  <div class="itemprice">Sign In</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product11.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/product12.png"  alt="product image">
                  </div>
                  <div class="itemname">Sign In</div>
                  <div class="itemprice">FREE TRAIL </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#192; FW Private Limited, Developed by JAYABHARATHI.
      </div>
    </div>
  </body>
</html>

```

### contact.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FRESHWORKS</title>
   <link rel="stylesheet" href="./css/layout.css">
    <link rel="icon" href="./img/backpro.png" type="image/x-icon">
     
  </head>

  <body>
    <div class="container">
      <div class="banner">FRESHWORKS..</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          
            <h1>Contact Us</h1>
            <p>If you have any questions or feedback, please don't hesitate to reach out to us.</p>
    <ul>
            <li>Address: 321 , East Main Road Street, Tamilnadu , India</li>
            <li>Phone: +91 85746922431</li>
            <li>Email: contact@freshwork.com</li>
    </ul>
  
<h2> Sales Inquiries</h2>

<ul><li>Interested in any of our products? Talk to our experts today</li></ul>
        <ul><li>US: +1 (855) 747 6767 || Australia: +61 1800 861 302</li></ul>
        <ul><li>UK: +44 8081 698 824 || +44 189 280 5040</li>
        <ul><li>India: +91 44 6667 8040 </li></ul>
        <ul><li>South Africa: +27 87 250 0373</li></ul>
        <ul><li>UAE: +971 800 032 0520</li></ul>
        <ul><li>Germany: +49 305 884 9246</li></ul>
        <ul><li>France: +33 17 585 0312 </li></ul>
        <ul><li>Spain: +34 51 888 0864 |</li></ul>
        <ul><li>Using any of our products and need help? Get in touch with customer support</li>
        <ul><li>Email: sales@freshworks.com | support@freshworks.com | careers@freshworks.com</li>
    
  </div>
   <div class="footer">
        Copyright &#192; 2023 F&W PVT LTD, Developed by JAYABHARATHI
      </div>
      </div>
</body>
</html>

```
## OUTPUT:

## HOME PAGE:

![home1](https://github.com/Jayabharathi3/productcompanywebsite/assets/120367796/d90306bc-fe38-4246-b47e-a83ed314d0df)


## PRODUCT PAGE:

![product](https://github.com/Jayabharathi3/productcompanywebsite/assets/120367796/c56d9176-40e6-4e38-958c-ba20dec34799)


## PEOPLE PAGE:

![people](https://github.com/Jayabharathi3/productcompanywebsite/assets/120367796/b5b6c22e-03b7-40e6-be5d-c53704751c55)


## CONTACT PAGE:

![contactus](https://github.com/Jayabharathi3/productcompanywebsite/assets/120367796/93e42d60-45b5-4eb0-abe0-7043a9a9b974)


## SERVER OUTPUT:

![serverpro](https://github.com/Jayabharathi3/productcompanywebsite/assets/120367796/17de01b8-8bc8-443f-ae7a-960c721d69cf)


## HTML VALIDATOR:

![htmlpro](https://github.com/Jayabharathi3/productcompanywebsite/assets/120367796/dc3da7ea-b32f-41f0-890c-6d5f43313fdd)



## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
