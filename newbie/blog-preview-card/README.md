# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

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

### What I learned

Structuring images inside div to get the required height of the image dimensions without cropping it.

```html
<div class="img-box">
  <img
    src="./assets/images/illustration-article.svg"
    alt="illustration-article for the card"
    class="illustration-article-img"
  />
</div>
```

```css
.img-box {
  width: 100%;
  height: 220px;
}

.illustration-article-img {
  width: 100%;
  height: 100%;
  border-radius: 12px;
  object-fit: cover;
}
```

### Continued development

With more practise will be able to master more skillfully image dimensions and focus state concept.

### Useful resources

- [Resource 1](https://developer.mozilla.org/en-US/) - This helped me for understanding what is the purpose of the focus and how it works.

### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- What tools did you use (e.g., ChatGPT, Claude, GitHub Copilot)?
  --> Used github copilot to understand why I was not getting the desired image dimesions ...it helped me understand the core problem and devlop solution for it.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
