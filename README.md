# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

I've made:

- Hover and focus states for all interactive elements on the page
- Two different representations of this card

### Screenshot

![](</assets/images/Blog%20Preview%20Card%20(Beglis%20Edition).png>)

### Links

- Solution URL: [Solution Repository](https://github.com/begli-amanov/frontendmentor/tree/blog-card)
- Live Site URL: [Solution on GitHub Pages](https://begli-amanov.github.io/frontendmentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive text elements without media queries
- Mobile-first workflow

### What I learned

I've learned, that there is a possibility to make text responsive (even with a lot of tweaks from my side for now) without media queries.

Reduced css lines with nesting and combining:

```css
.description {
	font: 500 calc(0.8313rem + 0.188vw) / 150% 'Figtree-Variable', sans-serif;
	color: var(--paragraph-text-color);
	margin-bottom: var(--main-margin);
}

.category,
.title,
.author {
	&:hover {
		color: var(--main-color);
		cursor: pointer;
	}
}
```

### Continued development

I am still not completely comfortable with css flex-box and centering. I will likely do more projects where both of this concepts are involved. However, CSS Grid is unknown for me as well, so I will try to use it in my next project.

### Useful resources

- [Modern CSS reset](https://www.joshwcomeau.com/css/center-a-div/) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Responsive text without media queries](https://stackoverflow.com/questions/15649244/responsive-font-size-in-css) - This can give and Idea where to start if you know nothing about responsive text. But there is definitely better resources out there for fully understanding this concept.

## Author

- Website - [My Blog Post](https://story-journal.online)
- Frontend Mentor - [@begli-amanov](https://www.frontendmentor.io/profile/begli-amanov)

## Acknowledgments

Ghat GPT-1o
