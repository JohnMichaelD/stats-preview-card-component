# Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). 

This example stats-component is designed for both mobile and desktop viewing, and was a great practice project to further deepen my knowledge of CSS, as well as learn new concepts!

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Desktop Layout](./images/desktopSS.png)
![Mobile Layout](./images/mobileSS.png)

### Links

- Solution URL: [Github Repo](https://github.com/JohnMichaelD/stats-preview-card-component)
- Live Site URL: [Live Site](https://johnmichaeld.github.io/stats-preview-card-component/)
- Image Source: [Image Source](https://unsplash.com/photos/VBLHICVh-lI?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Going into this project, I thought it would be a great way to practice my skills with CSS, and I was right! Most of the project was quite simple and flowed well. But there were a few cases where I got stuck, but was able to figure out the solutions.

First, I had trouble getting the image to sit aligned with it's parent container. This was solved using 

.img {
  display: block;.
}

and worked perfectly. 

I also had quite a bit of issue regarding the tint over the image. I found quite a few different ways to accomplish the tint via StackOverflow, but was having issues getting it to actually work. I was trying to tint the actual image, while what was needed was to apply a tint to a separate div, which then hovered over the image. 

### Continued development

This project was good practice for basic HTML and CSS properties. But for my next project(s), I would really like to get more practice using:
- Sass
- Styled COmponents
- CSS Grid

As well as starting the project with a Mobile-first workflow.

### Useful resources

- [display: block](https://www.tutorialrepublic.com/faq/how-to-remove-white-space-under-an-image-using-css.php)
- This helped figure out not only how to fix the spacing issue with the image, but also why it happens.
- [coloring an image with a tint](https://stackoverflow.com/questions/43938860/how-to-tint-image-with-css/43938944)
- This helped me with tinting the image container.
- [media queries](https://stackoverflow.com/questions/42586044/change-css-only-for-mobile-devices)
- This was useful in reminding me how to simply begin mobile-layout designs.

## Author

- Website - [JMD](https://www.johnmdarrin.com)
- Frontend Mentor - [@JohnMichaelD](https://www.frontendmentor.io/profile/JohnMichaelD)
