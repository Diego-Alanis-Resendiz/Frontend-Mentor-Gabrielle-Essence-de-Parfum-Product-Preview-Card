# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

In this project I attempted to recreate a responsive version of the product preview card challenge provided by Frontend Mentor.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for add to cart button

### Screenshot

![](./dar-product-preview-screenshot-desktop.jpg)
![](./dar-product-preview-screenshot-mobile.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I started this project by adding all of the images and content to the html boilerplate. Then I added all of the google fonts and color styles for the fonts and body background. I continued adding to this code by implementing the bootstrap framework in order to use the column grids in bootstrap and make the website responsive depending on the size of your device. Finally I played around with margins, padding, font-size, and border radius to get my two version for mobile and desktop as close to the design images provided in the challange.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap v5

### What I learned

Throughout this project I really began to understand the relationship between parent and child components. Specifically how padding can be manipulated in a parent to manipulate the position of the child components. 

I very proud of learning how to switch between 2 images in response to the device using the bootstrap documentation.

This is the code snippets I will refer to in the future when building on what I learned today:
     <div id="img-perfume" class="col-md-6">
        <img class="d-md-none d-lg-none d-xl-none" id="gabrielle-parfum-mobile" src="images/image-product-mobile.jpg"
          alt="Gabrielle-Essence-de-Parfum-mobile-img">
        <img class="d-none d-md-block d-lg-block d-xl-block" id="gabrielle-parfum"
          src="images/image-product-desktop.jpg" alt="Gabrielle-Essence-de-Parfum-img">
      </div>

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.



### Continued development

In future version of this project I would like to make the mobile version more uniformly round. I do not like the flat top and bottoms created with my responsive designs and would love to fix that as I learn more about web development. I would also like to improve the way the perfume images respond to the size of your display. At times the images gets strecthed in awkward ways and the resolution declines. I am not the greatest fan of this feature of my site and I would like a smoother more responsive image. Additionally, if I could redo this proect I would change my workflow and develop the mobile version before the desktop version

### Useful resources

- [Bootstrap Documentation](https://getbootstrap.com/docs/4.0/utilities/display/) - This helped me refresh my memory on the column grid system and help me learn how to block/hide images depending on the size of your display
- [MDN Documentation](https://developer.mozilla.org/en-US/) - These documents were a great resource to fall back on whenever I needed to demistify concepts I am still new to. Reading through the documentation helped me grow my understanding on how div and borders work.



## Author


- Frontend Mentor - [Diego-Alanis-Resendiz](https://www.frontendmentor.io/profile/Diego-Alanis-Resendiz)
- GitHub - [@Diego-Alanis-Resendiz](https://github.com/Diego-Alanis-Resendiz)

## Acknowledgments

Shoutout to Angela Yu's Webdev bootcamp on udemy for providing me with the fundamental to complete this project.
