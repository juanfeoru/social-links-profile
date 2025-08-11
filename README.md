# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Preview of my solution](./design/desktop-design.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/social-links-profile-with-html-and-css-BpX0zH3Vsa](https://github.com/juanfeoru/social-links-profile)
- Live Site URL: [https://yourusername.github.io/social-links-profile/](https://juanfeoru.github.io/social-links-profile/#)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS reset for consistent styling

### What I learned

This project helped me strengthen my understanding of:

- Structuring semantic HTML for better accessibility and SEO
- Creating a responsive and centered card layout with Flexbox
- Using CSS custom properties to manage a color palette
- Styling hover and focus states for better UX
- Applying a global CSS reset to make styles consistent across browsers

Example of how I applied hover and focus styles for accessibility:

```css
.profile-card__social-link:hover,
.profile-card__social-link:focus-visible {
  background-color: var(--green);
  color: var(--grey-900);
  transition: background-color 0.3s ease, color 0.3s ease;
}
```

### Continued development

In future projects, I want to:

- Keep working on subtle animations to improve the user experience.
- Improve the handling of variable fonts and loading optimization.
- Implement better accessibility practices (e.g., smoother keyboard navigation).

## Author

- Frontend Mentor - @juanfeoru
- GitHub - @juanfeoru
