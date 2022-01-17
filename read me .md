# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Links

- Repository URL: [https://github.com/Sadalmelik-AT/stat-preview-card](github)
- Live Site URL: [https://sadalmelik-at.github.io/stat-preview-card/](Stat-preview)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Scss

### What I learned

I also got introduced to sass in the process, it's so much more convenient to right your style in sass, I also tried to use it for media queries but something went wrong so I should review it.

How to do image overlay using pseudo-classes:

```css
.image::before {
  content: "";
  display: block;
  height: 100%;
  width: 100%;
  background-color: $accent-img;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
}
```

### Continued development

I will continue to get more comfortable with Sass and media querie

### Useful resources

- [Joy Shaheb](https://www.youtube.com/channel/UCHG7IJuST_BXJkne-0u0Xtw) - This REALLY helped me understanding Media Queries more.

## Author

- Frontend Mentor - [@PyZzi](https://www.frontendmentor.io/profile/pyzzie)
- Twitter - [@sadalmel1k](https://www.twitter.com/sadalmel1k)
