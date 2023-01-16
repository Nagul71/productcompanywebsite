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

### Home Page:
``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WINDfree</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/images/logopp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitem"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/images/logopp.png" border-color="yellow" alt="logo" />
          <div class="contenttext">
            Wind Free Technologies, (known as WINDFREE) is an Indian multinational cybersecurity software company, 
            headquartered in Pune, Maharashtra, India. The company was formerly known as CAT Computer Services (P) Ltd and was started as a computer service centre in 1995. 
            The company was renamed as WindFree Technologies Pvt. Ltd. in 2007.
            The company develops security software for consumers, servers, cloud computing environments and small and medium enterprises and sells products directly to customers or through its partner channel.
            Its enterprise product offerings operate under the brand name Seqrite.
            The companies products are regularly tested with features and abilities compared against other similar products.
            Wind Free develops its own security suite and leverages a combination of signature-based and signatureless detection technologies to detect and block known and unknown threats in real-time.

            <br />
            <ul>
              <li>Wind Gives Security</li>
              <li>Cloud-Based AI-Powered</li>
              <li>Wind Free is a great antivirus. </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 Wind Free , Designed By Nagul K
      </div>
    </div>
  </body>
</html>
```

### Product Page:
``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WINDfree</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/images/logopp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitem"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      
      <div class="content">
        <div class="productcontent">
            <h1 class="hrr">Our Quick Heal Series Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/1.png" alt="product image">
                  </div>
                  <div class="itemname">Quick Heal Total Security</div>
                  <div class="itemprice">Price: Rs. 1,499.00  </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/2.png"  alt="product image">
                  </div>
                  <div class="itemname">Quick Heal Internet Security</div>
                  <div class="itemprice">Price: Rs.1,199.00</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/3.png"  alt="product image">
                </div>
                <div class="itemname">Quick Heal AntiVirus Pro</div>
                <div class="itemprice">Price:Rs.879.00  </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/4.webp"  alt="product image">
                </div>
                <div class="itemname">Quick Heal Total Security Festive Pack</div>
                <div class="itemprice">Price: Rs.2,009.00</div>
              </div><div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/5.png"  alt="product image">
                  </div>
                  <div class="itemname">Quick Heal Internet Security Essentials</div>
                  <div class="itemprice">Price: Rs.3,000 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/6.webp"  alt="product image">
                </div>
                <div class="itemname">Quick Heal AntiVirus for Server</div>
                <div class="itemprice">Price: Rs.1,890 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/7.webp"  alt="product image">
                </div>
                <div class="itemname">Quick Heal PCTuner 3.0</div>
                <div class="itemprice">Price:Rs.499 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/8.webp"  alt="product image">
                </div>
                <div class="itemname">Quick Heal Total Security Multi-Device</div>
                <div class="itemprice">Price: Rs.2,199 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/9.webp"  alt="product image">
                </div>
                <div class="itemname">Quick Heal Mobile Security</div>
                <div class="itemprice">Free </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/10.webp"  alt="product image">
                </div>
                <div class="itemname">Quick Heal Total Security for Android</div>
                <div class="itemprice">Price: Rs.199.00</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/11.webp"  alt="product image">
                </div>
                <div class="itemname">Quick Heal Total Security for Mac</div>
                <div class="itemprice">Price: 1,549.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/images/12.jpg"  alt="product image">
                </div>
                <div class="itemname">Qick Heal Internet Security</div>
                <div class="itemprice">Price: Rs.2,500</div>
             </div>
          </div>
          </div>        
          
        
      <div class="footer">
        Copyright &#169; 2023 Wind Free , Designed By Nagul K
      </div>
    </div>
  </body>
</html>
```

### People Page:
``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WINDfree</title>
    <link rel="stylesheet" href="./css/layout.css" />
     <link rel="icon" href="/static/images/logopp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitem"><a href="/contactus/">Contact Us</a></div>
      </div>
      
      <div class="content">
        <div class="productcontent">
            <h1>Our Crew Memebers</h1>
                    <div class="productitems">
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/a.avif" alt="people image">
                            </div>
                            <div class="itemname">Chief Executive Officer</div>
                            <div class="itemprice">Brat Robinson</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/b.avif" alt="people image">
                            </div>
                            <div class="itemname">Chief Financial Officer9</div>
                            <div class="itemprice">Chandramohan</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/c.avif" alt="people image">
                            </div>
                            <div class="itemname">Chief Operating Officer</div>
                            <div class="itemprice">Tony Willson</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/d.avif" alt="people image">
                            </div>
                            <div class="itemname">Chief Marketing Officer</div>
                            <div class="itemprice">Samuel Jackson</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/e.avif" alt="people image">
                            </div>
                            <div class="itemname">Chief Technology Officer</div>
                            <div class="itemprice">Niharika</div>
                        </div>
                        <div class="productitem">
                            <div class="itemimage">
                                <img src="/static/images/f.avif" alt="people image">
                            </div>
                            <div class="itemname">President</div>
                            <div class="itemprice">Sam Ketteson</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
        Copyright &#169; 2023 Wind Free , Designed By Nagul K
      </div>
    </div>
  </body>
</html>
```
### Contact Us Page:
``` html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>WINDfree</title>
    <link rel="stylesheet" href="./css/layout.css" />
     <link rel="icon" href="/static/images/logopp.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/home/">Home</a></div>
        <div class="menuitem"><a href="/products/">Products</a></div>
        <div class="menuitem"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          <div class="us">
              <h1>
                  <u>Contact Us</u>
                </h1>
                <h2>For Enquiry</h2>
                        <h3>EMAIL : windfreeprivatelimited@gmail.com</h3>
                        <h3>NUMBER: +91 9361199777,+91 8535647625</h3>
                        <h3>ADDRESS: 12B,Windfree,Pune,Maharastra.</h3>
                        <h3>WEBSITE: Windfree.com</h3>
          </div>
            </div>
            <div class="footer">
        Copyright &#169; 2023 Wind Free , Designed By Nagul K
      </div>
    </div>
  </body>
</html>
```

### CSS Layout:
``` css
<style>
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color:black;
  color:white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 10px;
  font-weight: bold;
  background-image: url("/static/images/windu.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 130px;
  padding-left:250px;
  color:white;
}



.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color:black;
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
  
}

.menuitem a {
  text-decoration:none;
  color: white;
}
h1 {
    color:white;
}

.content {
  display: block;
  width: 100%;
  background-color: rgb(48,48,48);
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color:rgb(48,48,48);
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-family: Arial, Helvetica, sans-serif;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color:honeydew;
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
  background-color:black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color:white;
}

</style>
```
## OUTPUT:

### Home Page:

![output](/home45.png)


### Product Page:
![output](/products.png)


### People Page:
![output](/people6.png)


### Contact Page:
![output](/contact.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
