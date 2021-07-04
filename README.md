# Fylo
# Frontend Mentor - Fylo dark theme landing page solution

This is a solution to the [Fylo dark theme landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-dark-theme-landing-page-5ca5f2d21e82137ec91a50fd). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

## My process
I started out by creating the html markups first before styling. I ensured i started styling my website from top to bottom.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

I learnt how to use flexbox and css grid for the very first time without aid of any framework.


```html
    <nav class="nav_bar">
        <div class="logo">
            <img src="images/logo.svg" alt="fylo logo">
        </div>
        <ul class="nav-links">
            <li><a href="#">Features</a></li>
            <li><a href="#">Team</a></li>
            <li><a href="#">Sign In</a></li>
        </ul>
    </nav>
```
```css
section.users .user:first-child::before {
    content: url('images/bg-quotes.png');
    position: absolute;
    top: -35px;
    left: -15px;
    z-index: -1;
}
```

### Continued development

- I'd like to continue focusing on media queries and also the flexbox and grid properties.

### Useful resources

- [Youtube](https://www.youtube.com) - This helped me understanding git and github and how to host my website on github pages.
- [StackOverflow](https://www.stackoverflow.com) - This is an site that helped me overcome some difficulties i encountered whilst designing this project. I'd recommend it to anyone.


## Author

- Name - [Esther Nwodu](https://www.your-site.com)
