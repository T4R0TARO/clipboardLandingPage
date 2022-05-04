# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
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


### Built with

- Semantic HTML5 markup
- SASS/SCSS
- Grid

### What I learned

RE:WORK
```html
<header>
</header>

<main>

  <section>
  </section>

  <section>
  </section>

  <section>
  </section>

</main>

<footer>
</footer>
```
Rework in HTML structure. Organized the document by using header, main, section tag.

```css
:is(header, .about, .access, .features, .download) > p {
    max-width: 690px;
    margin: auto;
    text-align: center;
}
```
The :is() CSS psedo-class function takes a selector list as its argument, and selects any element that can be selected from that list. In this case, is() has a list of all the sections and checks if they have a child p tag. If any of them do then the p tag will take on the styles in the code block. 


## Author

- Website - [Joshua Manansala](https://github.com/T4R0TARO)
- Frontend Mentor - [@T4R0TARO](https://www.frontendmentor.io/profile/T4R0TARO)
- Twitter - [@taro_code](https://twitter.com/taro_code)