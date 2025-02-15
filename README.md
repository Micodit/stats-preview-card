# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

Large screen
![](./design/large-screen.png)

Small screen
![](./design/small-screen.png)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/stats-preview-card-component-gkdulzaSbo)
- [Live Site URL](https://micodit.github.io/stats-preview-card/)

### Built with

- Semantic HTML5 markup
- SASS
- Flexbox

### What I learned

I learnt how to use SASS, especially `@use` and `@forward` instead of `@import`. I also learnt how to organize SASS code using the 7-1 pattern architechture.

### Continued development

I want to practice further with SASS, espcially the advanced useage of mixins and functions.

I also want to improve my ability of controlling images in my projects. Currently, sometimes I couldn't control them as expected.

### Useful resources

- [Sass Guidelines](https://sass-guidelin.es/#architecture) - This helped me to understand the 7-1 pattern further.

## Author

- Github - [Micodit](https://github.com/Micodit)
- Frontend Mentor - [Micodit](https://www.frontendmentor.io/profile/Micodit)
  What specific areas of your project would you like help with? I couldn't give
  the overlay on the image the exact look of the one in the mockup. Do you guys
  have any ideas on how to achieve the same result? Also, would you give feedback
  on my current solution? &**img-box { width: 50%; background: linear-gradient( to
  right bottom, rgba($color-violet, 0.4), rgba($color-violet, 0.8) ),
  url(../../images/image-header-desktop.jpg); background-size: cover;
  background-position: center; } I also don't know how to insert a media query
  using SASS so I just wrote the code right beneath the corresponding class. For
  example .card**content-title { font-size: 3.2rem; color: $color-white;
  line-height: 1.2; margin-bottom: 3rem; @media (max-width: $breakpoint-lg) {
  font-size: 4.2rem; } Any ideas on how I should do it properly? Thank you all!
