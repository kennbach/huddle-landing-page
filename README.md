# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

Mobile
![](screenshot-mobile.png)

Desktop
![](screenshot-desktop.png)

### Links

- Solution URL: [https://github.com/kennbach/huddle-landing-page](https://github.com/kennbach/huddle-landing-page)
- Live Site URL: [https://kennbach.github.io/huddle-landing-page/](https://kennbach.github.io/huddle-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- CSS Variables
- CSS Grid
- Mobile-First workflow
- Accessibility Aware

### What I learned

This project had a background image that required it to be blended with the primary color. This is the first time I've use the background blend mode. This was much easier than any methods I've used before.

```css
background: no-repeat;
background-image: url("/images/bg-mobile.svg");
background-color: var(--color-primary);
background-blend-mode: hard-light;
```

### Continued development

I've been wanting to clean up my css naming convention, so I tried the BEM method a little here. I think this is a good solution so far, but I want to keep working with it much more before making the decision to keep it.

### Useful resources

- [The Net Ninja: HTML & CSS Crash Course](https://youtube.com/playlist?list=PL4cUxeGkcC9ivBf_eKCPIAYXWzLlPAm6G) - This is a great resource to learn or refresh your HTML and CSS knowledge from the ground up.

- [The Net Ninja: CSS Variables](https://youtube.com/playlist?list=PL4cUxeGkcC9ii5PB2UMyYH7QFZWfGnVgZ) - This is a great resource to learn CSS variables.

- [The Net Ninja: CSS Grid](https://youtube.com/playlist?list=PL4cUxeGkcC9itC4TxYMzFCfveyutyPOCY) - This is a great resource to learn CSS grid.

- [Kevin Powell: Are you using the right CSS units?](https://youtu.be/N5wpD9Ov_To) - There are a lot of different units that we can use when writing CSS, in this video Kevin gives some general rules of thumb of which ones are best suited for which situations. This is also where I learned how to convert the root font-size to base-10.

- [Kevin Powell: Solutions to common struggles](https://www.youtube.com/playlist?list=PL4-IK0AVhVjMbyomzxwNOECQwioJLxX6n) - The title says it all.

- Both, [Kevin Powell](https://www.youtube.com/kepowob) and [The Net Ninja](https://www.youtube.com/c/TheNetNinja) have a virtual-ton of great web app development tutorials. I only listed a few above, but there are many, many more.

## Author

- Github - [kennbach](https://github.com/kennbach)
- Frontend Mentor - [@kennbach](https://www.frontendmentor.io/profile/kennbach)
