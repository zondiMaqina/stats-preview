# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

  i was struggling with knwoing how to include images that will be responsive, i didi not know whether to include them as background images or as image elements
`
` > <section class="image">
  >   <img src="path" alt="image" class="img">
  > </section>

   I struggled with knowing how to include a background-color to the image, i tried including the color straight to the ```img``` element

  > .img{
  >   backgroung-color: color;
  >}

  So i then used the img element as a background-image 

  > <div class="background"><span class="overlay">.</span></div>

  I then use the ```span``` element as an overlay to cover the image in color (hsl())

  > width: 100%;
  > height: 100%;
  > background-color: hsla(277, 82%, 25%, 0.644);



### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.


