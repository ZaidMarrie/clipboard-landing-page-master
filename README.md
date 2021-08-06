# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Screenshot 2021-08-06 at 15-32-24 Frontend Mentor Clipboard landing page](https://user-images.githubusercontent.com/84665360/128518316-e7143c22-5a04-4d3b-a4a7-1f6bb93734a5.png)


### Links

- [My Solution](https://www.frontendmentor.io/solutions/clipboard-landing-page-c2ACbjoJL![Screenshot 2021-08-06 at 15-32-24 Frontend Mentor Clipboard landing page](https://user-images.githubusercontent.com/84665360/128518125-9bddf456-fbaa-49b2-97ba-c5bfef0d6a45.png)
)
- [Live Site Demo](https://zaidmarrie.github.io/clipboard-landing-page-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In this challenge I came across a very weird behaviour with margins. I initially had a margin bottom on my first button and it was causing the second to have a heigth as the first + that margin bottom. It took me quite a while to figure out what caused that on my second button. I then added the margin bottom on both buttons and it worked how I initially expected.

To see some code snippets see below:

```css
.button-1 {
    margin-bottom: 1em;
}
```

- This fixed it:
```css
.hero__button {
  margin-bottom: 1em;
}
```

### Useful resources

- [FontAwesome](https://fontawesome.com/) - Used to add social icons to page.

## Author

- Frontend Mentor - [@ZaidMarrie](https://www.frontendmentor.io/profile/ZaidMarrie)
- Twitter - [@LeKoels27](https://twitter.com/LeKoels27)
