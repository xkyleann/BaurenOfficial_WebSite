# **Bauren Official E-Commerce Website**
- E-commerce website for jewelery based products.
- The website displays products. Users can add and remove products to/from their cart while also specifying the quantity of each item. They can then enter their address and complete their payment process via PayPal.


## **Table of Contents**
* [Introduction](#general-info)
* [Index.html](#lab-works)
* [Style.css](https://tldp.org/LDP/abs/html/index.html)

## **Index.html** 
**_1. Simple HTML skeleton must me look like this:_** 
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

**_2. UTF-8 is a widely used character encoding that can represent all characters in the Unicode standart, which includes almost all characters used in the world's writing system. It can use like this_**
```html
<head>
    <meta charset="UTF-8">
  </head>
```

**_3. Adding [font](https://fonts.google.com/) type_** 
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

**_4. Adding logo to the site_**
```html
<head>
    <a href="#" class="logo"><img src="image/logo.png" alt""></a>
  </head>
```

**_5. Adding menu to the site_**
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

_6._ **_Adding [icons](https://boxicons.com/) such as; profile, cart_**
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
**_1. Simple CSS skeleton must me look like this:_** 
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

**_2. To make icons at the left side_**
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

**_3. Position of the Logo.png_**
```css
.logo img{ /* for fixing logo in the main*/
    max-width: 120px;
    height: auto;
}
```
**_4. Position of the navmenu_**
```css
.logo img{ /* for fixing logo in the main*/
    max-width: 120px;
    height: auto;
}

.navmenu{
    display: flex; /* all nav menu will be in one*/

}
.navmenu a{ /*in nav menu*/
    color: #2c2c2c;
    font-size: 16px;
    text-transform: capitalize;
    padding: 10px 20px;
    font-weight: 400;
    transition: all .42s ease;
}

.navmenu a:hover{ /*in nav menu*/
    color: #EE1C47;/*when you click icon it will change to this color*/
}
.nav-icon{
    display: flex;
    align-items: center;
}
.nav-icon i{ /*i = icons element within an element with the class of .nav-icon is set to 16 pixels, and a margin of 5 pixels is added to the right side of the element.*/
    margin: 20px;
    color: #2c2c2c;
    font-size: 25px;
    font-weight: 400;
    transition: all .42s ease;
}

.nav-icon i:hover{
    transform: scale(1.1);
    color:#EE1C47
}
```

**_5. Setting menu icons_**
```css
#menu-icon{ 
    font-size: 35px;
    color: #2c2c2c;
    z-index: 10001;
    cursor: pointer;
}

section{
    padding: 5% 10%;
}
```

**_5. Setting homepage background_**
```css
.main-home{   /*Main page adding picture and position(s) */
    width: 100%;
    height: 100vh;
    background-image: url(image/banner-3.png);
    background-position: center;
    background-size: cover;
}
```
