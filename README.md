# Frontend Mentor - Equalizer landing page solution

Solution provided by Julius Foo [Equalizer landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE).
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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

#### 2024.08.31
- This is my second project after completing the "workit-landing-page" to brush up on css
- I laid out the html strategically for all screen sizes first, as the last project I did it mobile first but ran into problems at desktop.
- Desktop first for HTML, mobile first for CSS
- Creating tailwind-like utilities to use as I'm writing the html, as I enjoy styling as I work my way to see the blocks
- The spacing in mobile is done, as are the color variables. I am still not full in tune with the "lobotomised owl selector", but am applying it via [Andy bell's flow snippet](https://piccalil.li/blog/my-favourite-3-lines-of-css/) as follows

```css
.flow > * + * {
  margin-block-start: var(--flow-space, 1em);
}
```

- Will familiarize with `margin-block-start` and the sibling `+` combinator
- Currently paused on aligning the elements in the cards, wondering why the $4 overlaps with the line above. Currently guessing because it is an in-line element. The "/ month" is also not aligning yet with the current flexbox properties I attempted to apply to it.
- The absolute positioned elements I will do last. Currently working on aligning all the text content first.


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.

## Author

- Website - [Add your name here](https://www.your-site.com)
