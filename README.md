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
### home.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Breaking Bad</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./myimg/lospollos logo.png" type="image/x-icon" />
    <style>
    .bodyhome {
        background-image: url("myimg/bb\ bg2.png");
        object-fit:contain;
    }
        
    .bluebutton{
    background-color: rgb(255, 255, 255);
    height: 50px;
    width: 100px;
    border-width: 1px;
    border-radius: 3px;
    border-color: #16d1ae;
    cursor: pointer;
    transition: background-color 0.25s;
    }

    .bluebutton:hover{
    background-color: #16d1ae;
    color: rgb(255, 255, 255);
    }

    .bannerhome {
  display: block;
  width: 100%;
  height: 200px;
  object-position: center;
  background-image: url("/static/myimg/backgroundpic.jpg");
  background-size: 100% 180%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
}

    </style>
  </head>

  <body class="bodyhome">
    <div class="container">
      <div class="bannerhome"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html"><button class="bluebutton">Home</button></a></div>
        <div class="menuitem"><a href="/static/products.html"><button class="bluebutton">Products</button></a></div>
        <div class="menuitem"><a href="/static/people.html"><button class="bluebutton">People</button></a></div>
        <div class="menuitem"><a href="/static/contact.html"><button class="bluebutton">Contact Us</button></a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Me and My Partner</h1>
          <img src="./myimg/crystal bg.jpg" alt="crystal bg" />
          <div class="contenttext">
              <ul>
            I am <strong>Jesse Pinkman</strong> and a crystal meth cook and dealer who works with my former high school chemistry teacher, <strong>Walter Hartwell White also known as Heisenberg</strong>
            When Walt is diagnosed with lung cancer and considers making methamphetamine to provide for his family, he tries to learn the illegal drug business by accompanying his brother-in-law 
            Hank Schrader, After Walt cooks his first batch of meth, Jesse is struck by its quality, calling it the purest he has ever seen.
            Walt is now working for Gus as a meth cook persuades Gus to renew Jesse and Walt's partnership so Jesse will drop the lawsuit. Jesse and Walt cook larger amounts of meth in Gus' underground "superlab", earning considerably more money.
            </ul>
            <ul>
              <li>"Yeah Science!"</li>
              <li>"Yo, yo, yo. 148, 3-to-the-3-to-the-6-to-the-9. Representin the ABQ. What up, biiaaatch? Leave it at the tone!"</li>
              <li>"Are We In The Meth Business, Or The Money Business?"</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 Meth business Empire limited, Developed by A.Ashwin Kumar 
      </div>
    </div>
        <embed src="/static/bg-music/bb bg1.mp3" loop="true" autostart="true" width="2" height="0">
  </body>
</html>
```
### product.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>heisenberg enterprises</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./myimg/lospollos logo.png" type="image/x-icon" />
    <style>
            .bodyproducts {
        background-image: url("myimg/bb\ bg2.png");
        object-fit:contain;
        }
    .bodyproducts{
  background-color: rgb(0, 221, 255);
  color: #00500b;
    }

    .bluebutton{
    background-color: rgb(255, 255, 255);
    height: 50px;
    width: 100px;
    border-width: 1px;
    border-radius: 3px;
    border-color: #16d1ae;
    cursor: pointer;
    transition: background-color 0.25s;
    }

    .bluebutton:hover{
    background-color: #16d1ae;
    color: rgb(255, 255, 255);
    }

    .bannerprod{

          display: block;
  width: 100%;
  height: 200px;
  object-position: center;
  background-image: url("/static/myimg/lab-setup.jpg");
  background-size: 100% 180%;
  margin: 0px 0px 0px 0px;
  padding-top: 40px;

  text-align: center;
  font-weight: bold;
  font-size: 60px;
  color: rgb(0, 162, 255);
  text-shadow: 0 0 3px rgb(0, 0, 0), 0 0 5px #0000FF;
    }

    .productitem img {
  width: 165px;
  height: 100px;
  display: block;
}

.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 170px;
  margin-bottom: 5px;
} 
.productcontent {
  height: 10px;
  margin: 10px 10px 10px 10px;
  background-color: #16d1ae;
}
    .prodcontent {
  display: block;
  width: 100%;
  background-color: #cffffd;
  height: 540px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
 </style>
  </head>

  <body class="bodyproducts">
    <div class="container">
      <div class="bannerprod">To Our TOP Customers</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html"><button class="bluebutton">Home</button></a></div>
        <div class="menuitemselected"><a href="/static/products.html"><button class="bluebutton">Products</button></a></div>
        <div class="menuitem"><a href="/static/people.html"><button class="bluebutton">People</button></a></div>
        <div class="menuitem"><a href="/static/contact.html"><button class="bluebutton">Contact Us</button></a></div>
      </div>
      <div class="prodcontent">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/prod1.png" alt="product image">
                  </div>
                  <div class="itemname">crystal methamphetamine</div>
                  <div class="itemprice">Price: $ 60,000 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/prod2.png"  alt="product image">
                  </div>
                  <div class="itemname">Methylamines</div>
                  <div class="itemprice">Price: $ 10,000</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/prod3.jpg"  alt="product image">
                  </div>
                  <div class="itemname">vacuum coffee press</div>
                  <div class="itemprice">Price: $ 8,000</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/prod4.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Hazmat chemistry lab suits</div>
                  <div class="itemprice">Price: $ 5,000</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/prod5.jpg"  alt="product image">
                  </div>
                  <div class="itemname">chemistry lab RV</div>
                  <div class="itemprice">Price: $ 65,000</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/prod7.png"  alt="product image">
                  </div>
                  <div class="itemname">aircrash teddy bear</div>
                  <div class="itemprice">Price: $ 500</div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 Meth business Empire limited, Developed by A.Ashwin Kumar 
      </div>
    </div>
    <embed src="/static/bg-music/bb bg1.mp3" loop="true" autostart="true" width="2" height="0">
  </body>
</html>
```
### people.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Better call Saul</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./myimg/lospollos logo.png" type="image/x-icon" />
    <style>
        .bodypeople{
              background-image: url("myimg/bb\ bg2.png");
  color: #17421d;
        }

    .bannerpeople{

          display: block;
  width: 100%;
  height: 200px;
  object-position: center;
  background-image: url("/static/myimg/peoplebg.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 160px;

  text-align: center;
  font-weight: bold;
  font-size: 35px;
  color: rgb(255, 136, 0);
  text-shadow: 0 0 3px rgb(0, 0, 0), 0 0 5px rgb(255, 255, 255);
    }

        .bluebutton{
    background-color: rgb(255, 255, 255);
    height: 50px;
    width: 100px;
    border-width: 1px;
    border-radius: 3px;
    border-color: #16d1ae;
    cursor: pointer;
    transition: background-color 0.25s;
    }

    .bluebutton:hover{
    background-color: #16d1ae;
    color: rgb(255, 255, 255);
    }

    .peoplecontent {
  display: block;
  width: 100%;
  background-color: #cffffd;
  height: 540px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}

    .productitem img {
  width: 165px;
  height: 100px;
  display: block;
}

.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 170px;
  margin-bottom: 5px;
} 

.prodcontent {
  display: block;
  width: 100%;
  background-color: #cffffd;
  height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}

.productcontent {
  height: 10px;
  margin: 10px 10px 10px 10px;
  background-color: #16d1ae;
}
    </style>
  </head>

  <body class="bodypeople">
    <div class="container">
      <div class="bannerpeople">Fact is, Walter White couldn't have done it without me</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html"><button class="bluebutton">Home</button></a></div>
        <div class="menuitem"><a href="/static/products.html"><button class="bluebutton">Products</button></a></div>
        <div class="menuitemselected"><a href="/static/people.html"><button class="bluebutton">People</button></a></div>
        <div class="menuitem"><a href="/static/contact.html"><button class="bluebutton">Contact Us</button></a></div>
      </div>
      <div class="peoplecontent">
        <div class="productcontent">    
          <h1>Our Co workers</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/gus.jpg" alt="product image">
                  </div>
                  <div class="itemname">Gustavo Fring</div>
                  <div class="itemprice">Los pollos Hermanos</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/saul.png"  alt="product image">
                  </div>
                  <div class="itemname">Saul Goodman</div>
                  <div class="itemprice">American criminal defense lawyer</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/mike.png"  alt="product image">
                  </div>
                  <div class="itemname">Mike Ehrmantraut</div>
                  <div class="itemprice">American career criminal</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/todd.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Todd Alquist</div>
                  <div class="itemprice">Methamphetamine cook and former exterminator for Vamonos Pest</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/Tuco.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Tuco Salamanca</div>
                  <div class="itemprice">high-ranking distributor and drug kingpin from the Cartel</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/huell.png"  alt="product image">
                  </div>
                  <div class="itemname">Huell Babineaux</div>
                  <div class="itemprice">Saul Goodman's former employee</div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 Meth business Empire limited, Developed by A.Ashwin Kumar 
      </div>
    </div>
    <embed src="/static/bg-music/people.mp3" loop="true" autostart="true" width="2" height="0">
  </body>
</html>
```
### contact.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Breaking Bad</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./myimg/lospollos logo.png" type="image/x-icon" />
    <style>

        .bodycontact {
        background-image: url("myimg/bb\ bg2.png");
    }

    .bluebutton{
    background-color: rgb(255, 255, 255);
    height: 50px;
    width: 100px;
    border-width: 1px;
    border-radius: 3px;
    border-color: #16d1ae;
    cursor: pointer;
    transition: background-color 0.25s;
    }

    .bluebutton:hover{
    background-color: #16d1ae;
    color: rgb(255, 255, 255);
    }

    .contactbanner{
          display: block;
  width: 100%;
  height: 200px;
  object-position: center;
  background-image: url("/static/myimg/backgroundpic.jpg");
  background-size: 100% 180%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
    }

    .ctccontent {
  display: block;
  width: 100%;
  background-color: #cffffd;
  height: 540px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
    .productitem img {
  width: 165px;
  height: 100px;
  display: block;
}

.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 170px;
  margin-bottom: 5px;
} 

.prodcontent {
  display: block;
  width: 100%;
  background-color: #cffffd;
  height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}

.productcontent {
  height: 10px;
  margin: 10px 10px 10px 10px;
  background-color: #16d1ae;
}
    </style>
  </head>

  <body class="bodycontact">
    <div class="container">
      <div class="contactbanner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html"><button class="bluebutton">Home</button></a></div>
        <div class="menuitem"><a href="/static/products.html"><button class="bluebutton">Products</button></a></div>
        <div class="menuitem"><a href="/static/people.html"><button class="bluebutton">People</button></a></div>
        <div class="menuitemselected"><a href="/static/contact.html"><button class="bluebutton">Contact Us</button></a></div>
      </div>
      <div class="ctccontent">
        <div class="productcontent">    
          <h1>For Contact</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/walter.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Walter Hartwell White</div>
                  <div class="itemprice">308 Negra Arroyo Lane, Albuquerque, New Mexico, United States.</div>
                  <div class="itemprice">heisenberg@gmail.com</div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/myimg/jessepinkman.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Jesse Bruce Pinkman</div>
                  <div class="itemprice">9809 Margo Street</div>
                  <div class="itemprice">Pinkman@gmail.com</div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 Meth business Empire limited, Developed by A.Ashwin Kumar 
      </div>
    </div>
    <embed src="/static/bg-music/babyblue.mp3" loop="true" autostart="true" width="2" height="0">
  </body>
</html>
```
### layout.css
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
.bodyhome {
  color: #17421d;
}

.bodycontact {
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 10px rgb(34, 34, 34);
}

.banner {
  display: block;
  width: 100%;
  height: 400px;
  text-align: center;
  font-family: cursive;
  font-weight: bold;
  font-size: 60px;
  background-image: url("/static/myimg/bb bg3.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: rgb(254, 243, 44);
}

.menu {
  display: block;
  width: 100%;
  height: 60px;
  font-size: larger;
  background-color: #006702;
  text-align: center;
  padding-top: 5px;
  padding-bottom: 5px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 20px;
  margin-right: 20px;
  margin-bottom: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 20px;
  margin-right: 20px;
  margin-bottom: 10px;
  color: #16d1ae;
}


.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  height: 450px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  height: 415px;
  margin: 10px 10px 10px 10px;
  background-color: #16d1ae;
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
  background-color: #16d1ae;
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
  width: 160px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 200px;
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
  background-color: #006702;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #ffffff;
}
```
## OUTPUT:

### Home Page:
![home](https://github.com/ASHWINKUMAR2903/productcompanywebsite/assets/119407186/3b5f6c66-da72-47f0-a146-7781b9af83d7)
### Product Page:
![product](https://github.com/ASHWINKUMAR2903/productcompanywebsite/assets/119407186/2ea1d2bd-533f-444d-aed8-62142a152788)
### people Page:
![people](https://github.com/ASHWINKUMAR2903/productcompanywebsite/assets/119407186/b3cbb8e2-a469-4806-b54c-a4a214d05d06)
### contact Page:
![contact](https://github.com/ASHWINKUMAR2903/productcompanywebsite/assets/119407186/9c52cc08-f32c-4cdf-bfcd-ec01705d427b)


## Result:
Thus a website is designed for the software product company and the HTML,CSS code are validated.
