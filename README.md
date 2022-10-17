# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Write the HTML structure: There is one parent div ('card') that contains two divs ('top-section' and 'bottom-section'). bottom-section Is subdivided into two divs -> the left and rigth portion.

Then I designed the CSS by defining thick borders to identify each container, in order to position them properly. Before that, I had to make sure all the content within wouldn't surpass the parent div ('card'). 

After this I just copied the right colors, removed the borders and applied a nice shadow behind the card and made its borders round

In the end removed the bullet points and the padding from the list.


### Built with

- HTML5
- CSS 

### What I learned

'Map out the HTML first'
It's a great idea positioning the boxes with borders before adding any style. 

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
/* The boxes will be all inside the parent container */
html {
  box-sizing: border-box;
  font-family: 'Karla';
  font-size: 16px;
  font-weight: 400;
}

/* All elements will inherit that root level sizing (html) */
*, *:before, *:after {
  box-sizing: inherit;
}
```


### Continued development

I'm hopeful I'll be able to have a better grasp on how to position the elements on the page. It wasn't easy comming up with the best solution at first, but with practice, I'll be making those simple designs in shorter span of time.

### Useful resources

- [codepen](https://codepen.io) - This helped me for it made easy to visualize in real time the page I was designing while writing the code

## Author

- Frontend Mentor - [@g-Barsani](https://www.frontendmentor.io/profile/g-Barsani)
