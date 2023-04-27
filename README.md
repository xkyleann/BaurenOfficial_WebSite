# **Bauren Official E-Commerce Website**
- E-commerce website for jewelery based products.
- The website displays products. Users can add and remove products to/from their cart while also specifying the quantity of each item. They can then enter their address and complete their payment process via PayPal.


## **Table of Contents**
* [Introduction](#general-info)
* [Index.html](#lab-works)
* [Style.css](https://tldp.org/LDP/abs/html/index.html)

## **Index.html** 
1. **_Simple HTML skeleton must me look like this:_** 
```html
<!DOCTYPE html>
<html>
  <head>
    <title> My Webpage </title>
  </head>
  <body>
    <h1> Hello, world! </h1>
    <p> This is my first webpage. </p>
  </body> 
</html>
```

2. **_UTF-8 is a widely used character encoding that can represent all characters in the Unicode standart, which includes almost all characters used in the world's writing system. It can use like this_**
```html
<head>
    <meta charset="UTF-8">
  </head>
```

3. **_Adding [font](https://fonts.google.com/) type_** 
```html
<head>
    <title>Bauren Offical</title>
    <!-- CSS-link-->
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DotGothic16&display=swap" rel="stylesheet">
  </head>
```

4. **_Adding logo to the site_**
```html
<head>
    <a href="#" class="logo"><img src="image/logo.png" alt""></a>
  </head>
```

5. **_Adding menu to the site_**
```html
<body>
  <head>
      <ul class="navmenu">
              <li><a href="#">home</a></li>
              <li><a href="#">shop</a></li>
              <li><a href="#">products</a></li>
              <li><a href="#">page</a></li>
              <li><a href="#">docs</a></li>
          </ul>

    </head>
  </body>
```

6. **_Adding [icons](https://boxicons.com/) such as; profile, cart_**
```html
<body>
  <head>
   <div class="nav-icon">
            <a href="#"><i class='bx bx-search-alt-2'></i></a>
            <a href="#"><i class='bx bx-user'></i></a>
            <a href="#"><i class='bx bx-cart'></i></a>

            <div class="bx bx-menu" id="menu-icon"></div>
        </div>
    </head>
  </body>
```

## **Style.css**
1. **_Simple CSS skeleton must me look like this:_** 
```css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
    font-family: 'DotGothic16', sans-serif; 
    list-style: none;
    text-decoration: none;
}
```
--------------------------------------------------------
2. **_To make icons at the left side_** 
```css
header{
    position: fixed; 
    width: 100%;
    top: 0;
    right: 0;
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 10%; /* specifies that the element should have a top and bottom padding of 20 pixels, and a left and right padding of 10% of the element's width. **
}
```
--------------------------------------------------------
