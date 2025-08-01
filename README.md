# Frontend Mentor - Bento Grid Solution

This is a solution to the [Bento Grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your HTML, CSS, and responsive design skills by building real-world projects.

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

---

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![Screenshot](./screenshot.jpg)

> Replace the path with your actual screenshot after capturing one using your browser or a tool like FireShot.

### Links

- Solution URL: [https://github.com/Shola-tech/bento-grid](https://github.com/Shola-tech/bento-grid)
- Live Site URL: _Coming soon on Netlify_

---

## My process

### Built with

- Semantic **HTML5**
- Custom **CSS3**
- **CSS Grid** for layout
- **Flexbox** for centering content
- **Mobile-first workflow**

### What I learned

I deepened my understanding of CSS Grid layout and how to make complex grid-based interfaces responsive across different screen sizes. I also practiced layering, spacing, and element alignment using Flexbox.

```html
<div class="grid-container">
  <div class="card card1 purple">
    <h3>Social Media <span>10x</span><br><span1>Faster</span1></h3>
    <img src="./assets/images/illustration-five-stars.webp" alt="">
    <p>Over 4,000 5-star reviews</p>
  </div>
</div>
.grid-container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(3, auto);
  gap: 1rem;
}
Continued development
I want to continue improving my responsive design skills and also focus on writing more maintainable and DRY CSS. I'd also like to explore using SCSS or Tailwind in future projects for more scalable styling.

Useful resources
CSS-Tricks - A Complete Guide to Grid – Helped me understand how to structure the grid layout effectively.

MDN Web Docs - Flexbox – A solid reference while aligning items inside each card.

Author
Frontend Mentor - @Shola-tech

GitHub - Shola-tech