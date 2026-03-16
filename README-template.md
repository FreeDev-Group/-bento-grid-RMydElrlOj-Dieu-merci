# Frontend Mentor - Bento Grid Solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Bento Grid Solution](#frontend-mentor---bento-grid-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [CSS](#css)
    - [HTML](#html)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

**Desktop Version**  
![Desktop Screenshot](./screenshot-project-desktop.png)

**Mobile Version**  
![Mobile Screenshot](./screenshot-project-mobile.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/FreeDev-Group/-bento-grid-RMydElrlOj-Dieu-merci)
- Live Site URL: [Live Site Project](https://freedev-group.github.io/-bento-grid-RMydElrlOj-Dieu-merci/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

During this project, I focused on building a **responsive grid layout** and mastering **CSS Grid + Flexbox** combinations. I also improved my **mobile-first workflow** and **hover animations for cards**, including shadows and transitions.

Some CSS/HTML snippets I’m proud of:

### CSS

```css
.card:hover {
  transform: translateY(-6px);
  box-shadow: 0 24px 48px rgba(127, 64, 208, 0.15);
  border-color: rgba(127, 64, 208, 0.2);
}
```

### HTML

```html
<div class="card card--hero">
  <h1 class="card__hero-title">
    Social Media <span class="highlight-yellow">10x</span> <em>Faster</em> with
    AI
  </h1>
</div>
```
