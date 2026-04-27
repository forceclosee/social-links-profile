# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/assets/img/Screenshot.png)

### Links

<!-- edit live site url -->

- Solution URL: [solution](https://github.com/forceclosee/social-links-profile)
- Live Site URL: [live site](https://forceclose-social-links-profile.pages.dev/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties \(variables\)
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Through this project, I learned the difference between **Flexbox and Grid** and when to use each one:

- **Flexbox** is ideal for arranging items in a single direction (row or column) with spacing between them
- **Grid** is better for complex, multi-dimensional layouts

For my profile card, I initially used Grid, but realized Flexbox was the simpler and cleaner choice since I only needed to stack items vertically. Here's what I used:

```css
.profile {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}
```

This taught me an important lesson: **simpler solutions are often better when they achieve the same result**. I also implemented hover and focus states for the social links, which improves the user experience and accessibility.

### Continued development

In future projects, I want to focus on:

- **JavaScript interactivity** — Adding dynamic features like click handlers, form validation, and DOM manipulation
- **Responsive Flexbox layouts** — Building more complex layouts with Flexbox in both row and column directions
- **Accessibility improvements** — Ensuring keyboard navigation works smoothly and testing with screen readers
- **CSS animations and transitions** — Adding subtle hover and focus animations for better user feedback

I'm particularly interested in learning how to use JavaScript to make user interactions feel smooth and responsive.

### Useful resources

- [Google Font](https://fonts.google.com/) - This platform have tons of licensed free font. I really liked this platform and will use it going forward.
- [Tinypng](https://tinypng.com/) - This is an amazing tool to optimize image size. I'd recommend it to anyone to improve site load time.

### AI Collaboration

I'm using Github Copilot to help write documentations.

## Author

- Frontend Mentor - [@forceclosee](https://www.frontendmentor.io/profile/forceclosee)
- Github - [Force Close](https://github.com/forceclosee)
- X - [@forceclosee](https://x.com/forceclosee)
