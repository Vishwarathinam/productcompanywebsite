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

### Layout.css:
~~~
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
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/logo.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #3c16e6;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #0c0c0c;
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
  color: #ec370a;
}

.menuitem a {
  text-decoration: none;
  color: #fffefe;
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
  background-color: #010500;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #f7f2f2;
}
~~~
### Home Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Future Groups Private Ltd.,</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/office.jpg" alt="Building" />
          <div class="contenttext">
            We are on a mission to save humanity and revive the economy from the catastrophic effects of the pandemic with carrier tracking and non-pharmaceutical interventions.
            Flattening the curve of the Coronavirus is of top priority for almost every country today. Unless they are able to flatten the curve, peoples’ lives, as well as the economy, are in severe danger. We have developed a solution that governments can use to help stop the spread, and tools that will help resume commerce, and even travel.
            <br>
            
            We are on a mission to save humanity and revive the economy from the catastrophic effects of the pandemic with carrier tracking and non-pharmaceutical interventions.
            Flattening the curve of the Coronavirus is of top priority for almost every country today. Unless they are able to flatten the curve, peoples’ lives, as well as the economy, are in severe danger. We have developed a solution that governments can use to help stop the spread, and tools that will help resume commerce, and even travel.
<br>
 
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Future Groups Private Ltd., Developed by Vishwa Rathinam S.
      </div>
    </div>
  </body>
</html>
~~~
### Products:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Future Groups Private Ltd.,</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/s1.jfif" alt="product image">
                  </div>
                  <div class="itemname">Light Room</div>
                  <div class="itemprice">Price: Rs.1500/- </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/s2.png"  alt="product image">
                  </div>
                  <div class="itemname">Adobe InDesign</div>
                  <div class="itemprice">Price: Rs.1600/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s3.jfif"  alt="product image">
                </div>
                <div class="itemname">Adobe Acrobat</div>
                <div class="itemprice">Price: Rs.1700/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/s4.png"  alt="product image">
                </div>
                <div class="itemname">Adobe XD</div>
                <div class="itemprice">Price: Rs.4999/- </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/s5.jfif"  alt="product image">
              </div>
              <div class="itemname">Blender</div>
              <div class="itemprice">Price: Rs.1000/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/s6.png"  alt="product image">
            </div>
            <div class="itemname">Audacity</div>
            <div class="itemprice">Price: Rs.1070/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/s7.png"  alt="product image">
            </div>
            <div class="itemname">Adobe Photoshop</div>
            <div class="itemprice">Price: Rs.10070/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/s8.png"  alt="product image">
            </div>
            <div class="itemname">Adobe Premium Pro</div>
            <div class="itemprice">Price: Rs.2570/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/s9.png"  alt="product image">
            </div>
            <div class="itemname">After Effects</div>
            <div class="itemprice">Price: Rs.2000/- </div>
        </div>
      </div>  <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/s10.png"  alt="product image">
        </div>
        <div class="itemname">Hand Break</div>
        <div class="itemprice">Price: Rs.990/- </div>
      </div>  <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/s11.png"  alt="product image">
        </div>
        <div class="itemname">K7 Total Security</div>
        <div class="itemprice">Price: Rs.3570/- </div>
      </div>  <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/s12.jfif"  alt="product image">
        </div>
        <div class="itemname">Autodesk Fusion 360</div>
        <div class="itemprice">Price: Rs.22000/- </div>
    </div>
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Future Groups Private Ltd., Developed by Vishwa Rathinam S.
      </div>
    </div>
  </body>
</html>
~~~
### People:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Future Groups Private Ltd.,</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/1.jfif" alt="product image">
                </div>
                <div class="itemname">Shankar</div>
                <div class="itemprice">Managing Director</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/2.jfif"  alt="product image">
                </div>
                <div class="itemname">Ragul</div>
                <div class="itemprice">Office manager</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/3.jfif"  alt="product image">
              </div>
              <div class="itemname">Ishwarya</div>
              <div class="itemprice">Assistant HR</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/4.jfif"  alt="product image">
              </div>
              <div class="itemname">Guru Prasath</div>
              <div class="itemprice">Marketing Manager</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/5.jfif"  alt="product image">
            </div>
            <div class="itemname">Anto Richard</div>
            <div class="itemprice">Professional Staff</div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/6.jfif"  alt="product image">
          </div>
          <div class="itemname">Gal Gadot</div>
          <div class="itemprice">Operation Manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Future Groups Private Ltd., Developed by Vishwa Rathinam S.
    </div>
  </div>
</body>
</html>
~~~
### Contact Us:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Future Groups Private Ltd.,</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1>
          <h1>Address:</h1><br>
          <div class="contenttext">
            89/S Future Groups Private Ltd.,<br>
            T.Nagar,<br>
            Chennai - 600017.
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              Mr.Sarvesh  (MARKETING MANAGER): 8660177869<br><br>
              Mr.Shriram (OPERATION MANAGER): 8896432145<br><br>
              Mr.Anto Richard (OFFICE MANAGER): 7384512585<br><br>
          </div>
          <h1>E-Mail:</h1>
          <div class="contenttext">
              E-Mail:futuregroups@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Future Groups Private Ltd., Developed by Vishwa Rathinam S.
      </div>
    </div>
  </body>
</html>
~~~
## OUTPUT:

### Home Page:

![output](./images/homepage.png)

### Products:

![output](./images/products.png)

### People:

![output](./images/people.png)

### Contact Us:

![output](./images/about.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
