# huddle-landing-page-with-single-introductory-section-master
html, css, huddle_landing_page

# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![huddle_landing_page_screenshot](https://user-images.githubusercontent.com/76667866/174894519-fa7c17be-78af-4337-b823-88fe74e51d53.png)

### Links

- Solution URL: [https://github.com/OkeraM/huddle-landing-page-with-single-introductory-section-master](https://github.com/OkeraM/huddle-landing-page-with-single-introductory-section-master)
- Live Site URL: [https://okeram.github.io/huddle-landing-page-with-single-introductory-section-master/](https://okeram.github.io/huddle-landing-page-with-single-introductory-section-master/)

## My process

- My process was pretty simple. First I made sure to write out all of my HTML. Writing them out in a way were I can simply use display: flex later in css. 

### Built with

- Semantic HTML5 markup
- Html
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

- During this project I learned how to place cirlces around my social-media icon buttons.
To see how you can add code snippets, see below:

```html
<footer>

    <div class="social-media-icons">

    <a href="#" class="fa fa-facebook"></a>
    <a href="#" class="fa fa-twitter"></a>
    <a href="#" class="fa fa-instagram"></a>

    </div>

  </footer>
```
```css
.register_button {
    text-align: center;
    max-width: 12vw;
    background-color: white;
    box-shadow: 1px 1px 10px 1px;   /* in order: x offset, y offset, blur size, spread size, color */
    border-radius: 35px;
    cursor: pointer;
}

.register_button:hover {
    background-color: hsl(300, 69%, 71%);
    max-width: 12vw;
    border-radius: 35px;
}

a {

    color:hsl(257, 40%, 49%);
    display: flex;
    align-items: center;
    justify-content: center;
    height: 7vh;

}

.register_a:hover {

    background-color: hsl(300, 69%, 71%);
    border-radius: 35px;
    
}

.fa {
    padding: 12px;
    font-size: 30px;
    width: 40px;
    height: 40px;
    text-align: center;
    text-decoration: none;
    margin: 3px 2px;
    color: white;
    border-radius: 50%;
  }
  
  .fa:hover {
      opacity: 0.7;
  }
  
  .fa-facebook {
    background: transparent;
    color: white;
    border: 1px solid white;
    margin-left: 13px; /* works well to put space between */
  }

  .fa-facebook:hover {
    color: hsl(300, 69%, 71%);
    border: 1px solid hsl(300, 69%, 71%);
  }
  
  .fa-twitter {
    background: transparent;
    color: white;
    border: 1px solid white;
    margin-left: 13px; /* works well to put space between */
  }

  .fa-twitter:hover {
    color: hsl(300, 69%, 71%);
    border: 1px solid hsl(300, 69%, 71%);
  }

  .fa-instagram {
    background: transparent;
    color: white;
    border: 1px solid white;
    margin-left: 13px; /* works well to put space between */
  }

  .fa-instagram:hover {
    color: hsl(300, 69%, 71%);
    border: 1px solid hsl(300, 69%, 71%);
  }

  .social-media-icons {
    display: flex;
    float: right;
    padding-right: 7rem;
  }

```
```
```

## Author

- Frontend Mentor - [@OkeraM](https://www.frontendmentor.io/profile/OkeraM)

