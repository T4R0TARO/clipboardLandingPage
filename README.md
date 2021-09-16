# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
 

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot
![image](https://user-images.githubusercontent.com/76195521/133682829-9b8c2148-5056-4c0f-9d4b-6d972dcbc197.png)

![image](https://user-images.githubusercontent.com/76195521/133682918-20608c88-6544-4542-afab-4d05153ecbd1.png)

### Links

- Solution URL: [Git Repo](https://github.com/T4R0TARO/clipboardLandingPage)
- Live Site URL: [Git Pages](https://t4r0taro.github.io/clipboardLandingPage/)

## My process
1. HTML STRUCTURE (Layout)
2. CSS (Base Styles and Layout)
3. CSS (Mobile Stlyes)
4. CSS (Desktop Styles)
5. Adjust Padding and Margin 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Footer
```html
     <footer class="mainfooter"> 
       <img src="./images/logo.svg" alt="logo icon">
       
       <div class="footerLinks">
        <a href="#">FAQs</a>
        <a id="marginFix"href="#">Privacy Policy</a>
        <a href="#">Install Guide</a>
        <a href="#">Contact Us</a>
        <a href="#">Press Kit</a>
       </div>
       
       <div class="socialIcons">
         <a href="https://www.facebook.com/login/"><i class="icon fab fa-facebook-square fa-lg"></i></a>
         <a href="https://twitter.com/?lang=en"><i class="icon fab fa-twitter fa-lg"></i></a>
         <a href="https://www.instagram.com/accounts/login/"><i class="icon fab fa-instagram fa-lg"></i></a>
       </div>
       
     </footer> 
```
Media Query for Desktop Style
```css
@media screen and (min-width: 1025px){
/* Hero Desktop */
.hero {
    background-image: linear-gradient(rgba(255, 255, 255, 0.459), rgba(255, 255, 255, 0.74)), url(.././images/bg-header-desktop.png);
    background-size: cover;
    width: 100%;
}
/* Desktop Layout */
button {
    margin-left: 20px;
}
.topButtons, .botButtons {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;   
}
.rowContainer {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
  .colImgContainer {
    display: flex;
    flex-direction: row;
    
}
  .colContainer {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    flex-direction: column;
    text-align: left;
    margin-left: 100px;
}
```


## Author

- Website - [Joshua Manansala](https://github.com/T4R0TARO)
- Frontend Mentor - [@T4R0TARO](https://www.frontendmentor.io/profile/T4R0TARO)
- Twitter - [@taro_code](https://twitter.com/taro_code)