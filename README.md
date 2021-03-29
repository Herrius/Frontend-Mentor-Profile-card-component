# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Github](design/desktop-design.jpg)


### Links

- Solution URL: [Add solution URL here](https://herrius.github.io/Frontend-Mentor-Profile-card-component/)

## My process

### Built with

- Semantic HTML5 markup 
- Flexbox
- CSS Grid
- Mobile Design

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I practice my skills in CSS3 and Flexbox. Specially, It do the background because It's my first do for myselft the partially hide and move images.

```css
.top-circle{
    position: absolute;
    object-fit: cover;
    bottom: 50%;
    right: 55%;
}
.bottom-circle{
    position: absolute;
    object-fit: cover;
    top: 50%;
    left: 50%;
}
.imagen-container{
    overflow: hidden;
    position: absolute;
    object-fit: cover;
    width: 100%;
    height: 100%;
}
@media only screen and (max-width:350px){
    .top-circle{
        right: 45%;
    }
    .bottom-circle{
        left: 45%;
    }
}
```

## Author

- Website - [Enrique Ubaldo](https://herrius.github.io/PortafolioWeb/)
- Frontend Mentor - [@Herrius](https://www.frontendmentor.io/profile/Herrius)
- Twitter - [@herrius_97](https://www.twitter.com/yourusername)

