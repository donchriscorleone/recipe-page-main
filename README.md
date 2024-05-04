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
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshots/Desktop%20screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/mobile-first-using-plain-css-E2r4FJvIbo)
- Live Site URL: [Add live site URL here](https://donchriscorleone.github.io/recipe-page-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

To add some space between the ::marker element (bullet) and the content, you can put position: relative to the content and left: x-value.

```html
    <ul>  
        <li>
            <span><em>Total: </em>Approximately 10 minutes</span>
        </li>
        <li>
            <span><em>Preparation: </em>5 minutes</span>
        </li>
        <li>
            <span><em>Cooking: </em>5 minutes</span>
        </li>
    </ul>
```
```css
ul li > *, ol li > * {
    position: relative;
    left: 20px;
}
```

### Useful resources

- [Control space between ::marker and li](https://stackoverflow.com/questions/4373046/css-control-space-between-bullet-and-li) - This helped me for the spacing between the content of the li and ::marker.

## Author

- Frontend Mentor - [@donchriscorleone](https://www.frontendmentor.io/profile/donchriscorleone)
- Twitter - [@topheriidev](https://twitter.com/topheriidev)