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
### HOME PAGE
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KS SQUARE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    
    
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>      
    </body>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/ex07ours.jpg" alt="ex07ours" />
          <div class="contenttext">
           Lights, camera, action! Welcome to KS SQUARE, the ultimate destination for film posters. 
            Step into a world where art and cinema collide, as we showcase the most iconic and visually 
            stunning posters from the golden age of Hollywood to the latest blockbusters.
            Indulge your senses and immerse yourself in a gallery of breathtaking designs.
            <br />
            From striking minimalist compositions to captivating illustrations, 
            our collection celebrates the artistry behind film promotion. 
            Each poster tells a story, enticing you to embark on a thrilling cinematic journey that transcends 
            the boundaries of the screen.
            <ul>
              <li>POSTERS</li>
              <li>CUSTOMIZED T-SHIRTS & CUSTOMIZED MOBILE CASES</li>
              <li>BADGES</li>
              <li>ACCESSORIES</li>
              <li>MUGS</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 KS SQUARE, Developed by SANDHIYA R.
      </div>
    </div>
  </body>
</html>

```
### PRODUCT PAGE
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>KS SQUARE</title>
    <link rel="stylesheet" href="./css/layout.css" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a herf="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/POSTERR.png" alt="product image">
                  </div>
                  <div class="itemname">Kaara Atakaara poster</div>
                  <div class="itemprice">Price: Rs.199.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tshirt1.png"  alt="product image">
                  </div>
                  <div class="itemname">You Go Man! Why Me? T-Shirt</div>
                  <div class="itemprice">Price: Rs.549.00 </div>
              </div>
                <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/poster.png"  alt="product image">
                  </div>
                  <div class="itemname">Gautham Menon Tribute Poster</div>
                  <div class="itemprice">Price: 169.00 </div>
              </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tshirt2.png"  alt="product image">
                  </div>
                  <div class="itemname">Thalapathy Forever T-Shirt - Limited Edition</div>
                  <div class="itemprice">Price: 699.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/badge1.png"  alt="product image">
                  </div>
                  <div class="itemname">Teru Teru Bozu Badge</div>
                  <div class="itemprice">Price: 59.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/mug1.png"  alt="product image">
                  </div>
                  <div class="itemname">Idhu Beast'u Mode Mug</div>
                  <div class="itemprice">Price: 399.00 </div>
              </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/mug2.png"  alt="product image">
                  </div>
                  <div class="itemname">Thala Mug</div>
                  <div class="itemprice">Price: 549.00 </div>
              </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ring.png"  alt="product image">
                  </div>
                  <div class="itemname">Ring</div>
                  <div class="itemprice">Price: 399.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 KS SQUARE, Developed by SANDHIYA R.
      </div>
    </div>
  </body>
</html>
```
### PEOPLE PAGE
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>KS SQUARE</title>
        <link rel="stylesheet" href="./css/layout.css" />
    </head>
    <body> 

        <div class="container">

            <div class="banner"></div>
            <div class="menu">
            <div class="menuitem"><a href="/static/home.html">Home</a></div>
            <div class="menuitem"><a href="/static/products.html">Products</a></div>
            <div class="menuitemselected"><a href="/static/people.html">People</a></div>
            <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
            
        </div>
        <div class="content">
        <div class="productcontent">    
        <h2 style="text-align:center;">PEOPLE</h2>
          
        <div class="productitems">
            
        <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/alia.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">ALIA BHATT</div>
                  
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/kat.jpg"  alt="product image">
                  </div>
                  <div class="itemname">KATRINA KAIF</div>
                  
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/mahesh.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">MAHESH BABU</div>
                  
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ranveer.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">RANVEER SINGH</div>
                  
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/surya.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">SURIYA</div>
              </div>
              </div>
    <div class="footer">
        Copyright &#169; 2023 KS SQUARE, Developed by SANDHIYA R.
    </div>
              
        
                  
    </body>
</html>
```
### CONTACT US PAGE
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>KS SQUARE</title>
        <link rel="stylesheet" href="./css/layout.css" />
    
    </head>
    <body>
        <div class="container">
        <div class="banner"></div>
            <div class="menu">
            <div class="menuitem"><a href="/static/home.html">Home</a></div>
            <div class="menuitem"><a href="/static/products.html">Products</a></div>
            <div class="menuitem"><a href="/static/people.html">People</a></div>
            <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
            
        </div>
        <div class="content">
            <h1>CONTACT US</h1>
            <div class="contenttext">
            <h2>ADDRESS:</h2>
            <p>#27 Nehru road</p>
            <p>Anna Nagar</p>
            <p>Chennai</p>
        </div>
        <div>
            <h2>EMAIL id: </h2>
            <p>kssquare@gmail.com</p>
            <p>kssquare@kSScom</p>
        </div>
        <h2>CONTACT NUMBER</h2>
        <p>236417980</p>
        <strong>You may also contact us through<strong>
        <p><b>INSTAGRAM</b> @kS_square</p>
        <p><b>FACEBOOK</b> @kS_square</p>
        <p><b>LINKEDIN</b> @kS_square</p>
        </div>
        </div>
    <div class="footer">
        Copyright &#169; 2023 KS SQUARE, Developed by SANDHIYA R.
    </div>
            
    </body>
</html>
```


## OUTPUT:

### Home Page:
![ex071](https://github.com/SandhiyaR1/productcompanywebsite/assets/113497571/21af29e2-6339-400a-9483-15dac4415852)

### PRODUCTPAGE:
![ex072](https://github.com/SandhiyaR1/productcompanywebsite/assets/113497571/f9a9d559-51fd-46d0-8635-7fab53ce4dca)


### PEOPLE PAGE:
![ex073](https://github.com/SandhiyaR1/productcompanywebsite/assets/113497571/e99c8707-e56a-4423-8ba4-d943d3b0bf9a)


### CONTACT US PAGE:

![ex074](https://github.com/SandhiyaR1/productcompanywebsite/assets/113497571/e6ade568-e717-4ce7-a6a7-ef593664a1f1)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
