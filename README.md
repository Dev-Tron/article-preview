# Frontend Mentor - Article preview component solution

This is a solution to the [Article preview component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See the social media share links when they click the share icon

### Screenshot

![](images/Screen Shot 2022-01-05 at 6.53.24 AM.png)
![](images/Screenshot 2022-01-05 at 06-57-34 Frontend Mentor Article preview component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [JQuerry](https://jquery.com/) - JS library
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

In this challenge, I further learned the importance of layouts and their relations to screen sizes. This was a very tough challenge styles wise but doing it really helped solidify my progress.

Some of the useful code snippets that I used include:

```HTML:
<time id="lighten" datetime="2020-06-28">28 Jun 2020</time>

```CSS:
.social-media-icons::after {
    
    @media #{$brk-wide} {    
        content: '';
        background-color: $drk-blu-grey;
        width: 10px;
        height: 10px;
        position: absolute;
        top: 100%;
        left: 48%;
        transform: translate(-50%, -50%) rotate(45deg);
  }
}

```JavaScript:
$('.social-media-icons').hide();

$('button').click(function() {
    $('.social-media-icons').toggle('active');
})

### Continued development

Areas I need to improve on include:

- Deeper understanding of layouts using, flex, grid, inline, and block elements.

## Author

- Website - Keytron Brown (website to be announced)
- Frontend Mentor - (https://www.frontendmentor.io/profile/Dev-Tron)
- Twitter - (https://www.twitter.com/@BrownKeytron)