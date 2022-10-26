# Pizza shop website (WIP)  

## Brief

For this mini project we are to create a small website for an upcoming pizza shop.  
The website should include a menu page, a booking page and the landing page.  

This is a work in progress, So far I have created the basic pages and links and worked on the responsive design of the landing page.  

**Images used:**  

- sliced pizza on white ceramic - [The Nix Company](https://unsplash.com/photos/ljvm17bH-e0)

- Dinner party -[Kraken Images](https://unsplash.com/photos/7BpuzmcxlHU)

- Disco ball - [No Revisions](https://unsplash.com/photos/UbujEmVOTXg)

***

## tech Stack

- HTML
- SCSS
- WireFrames via Figma

***

## HTML

This project involves a basic boiler plate, the linking of the index page with 3 separate pages. Using semantic html to define sections of the body  

```html
<header>
    
   <img class="logo-image" src="./images/logo.jpg" alt="Logo character">

    <nav class="nav-container">
      
      <ul class="navbar">
        <a href="./pages/menu.html"><li>Menu</li></a>
        <a href="./pages/booking.html"><li>Specials</li></a>
        <a href="./pages/location.html"><li>Location</li></a>
      </ul>

    </nav>

  </header>
```

## SCSS  

This is my first time using SCSS and trialing out various syntax associated. I defined colors using primary and secondary variables and found quite a lot of use with mixins.  

```scss
// Variables
$primary-color: rgb(217, 19, 19);
$secondary-color: rgb(247, 247, 23);


// General mixins
@mixin head-foot {
  background-color: $primary-color;
  border-top: $secondary-color solid 5px;
  border-bottom: $secondary-color solid 5px;
}
```
