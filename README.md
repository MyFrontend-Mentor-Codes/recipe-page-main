# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.  


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
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge
1. Build out the recipe page and get it looking as close to the design as possible.
2. Reduce the font size for smaller screens without using media queries.

### Screenshot
./assets/images/myscreenshot.png

### Links

- Solution URL: 
https://www.frontendmentor.io/solutions/social-links-profile-page-using-semantic-html-and-media-queries-COVHwEvdSR

- Live Site URL: 
https://arecipe-page.netlify.app/



## My process
### Built with
- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- Pseudo-elements


### What I learned
-- Pseudo elements
-- Styling the bullets of a list element differently from the copy of the content

```html
 <ul class="ingredients-meta">
    <li>2-3 large eggs</li>
    <li>Salt, to taste</li>
    <li>Pepper, to taste</li>
    <li>1 tablespoon of butter or oil</li>
    <li>Optional fillings: cheese, diced vegetables, cooked meats, herbs</li>
</ul>
```

```css
.ingredients-meta li {
    position: relative;
}

.ingredients-meta li::before {
    content: "\2022";
    color: var(--brown800);
    font-size: 2em;
    position: absolute;
    left: -.6em;
    top: -.3em;
}
```
```js
  No js code
}
```

### Continued development



### Useful resources


## Author
- Frontend Mentor - https://www.frontendmentor.io/profile/wisdomugo
- Twitter - https://www.twitter.com/wisdomnukas


## Acknowledgments