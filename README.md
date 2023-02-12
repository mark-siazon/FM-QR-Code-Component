# Frontend Mentor - QR-Code-Component Solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). <br>
Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)
- [Feedback/Suggestions](#feedback--suggestions)
- [Notes](#note)


## Overview

### The challenge

Users should be able to:

- Your challenge is to build out this QR code component and 
- Get it looking as close to the design as possible.

### Screenshot

| Desktop View | Mobile View |
|---------|---------|
| ![](design-finished/Laptop-20230124_061347.png) | ![](design-finished/Mobile-20230124_061628.png) |

### Links
- Live Site URL: [Website Link - Click Me](https://qr-code-component-three-ecru.vercel.app/)
- Solution URL: [FrontEndMentor Link - Click Me](https://www.frontendmentor.io/solutions/qr-code-component-I0u3ok_Odp)

## My process

### Built with
- Plain: HTML, CSS 
- Mobile-first workflow (Using Media Queries)

### What I learned

Recap over some of the major learnings while working through this project:
- Basic review of HTML & CSS
- CSS Flex Layout

<br>

This code snippets/function, if what I'm proud to accomplished:

```css
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
```

### Continued development
<hr>

#### Here are a few possible areas that could be added or improved in the HTML and CSS code you provided:
1. **Accessibility:** - It could be more accessible to users with disabilities by:
    - Include appropriate ARIA attributes, alt text, and semantic HTML tags. 
    - Also, providing a larger font size, better color contrast, and using aria-label, aria-roles attributes for the interactive elements.
2. **Responsiveness:** - Using responsive design techniques and media queries for different screen sizes and devices.

## Author
- Github - [@Iron-Mark](https://github.com/Iron-Mark)
- Frontend Mentor - [@Iron-Mark](https://www.frontendmentor.io/profile/Iron-Mark)

## Acknowledgments
- I would like to acknowledge the hard work and dedication that I went into creating this website. 
  - (I'm still recovering from fever doing this lol)
- I am grateful for my friends and to those who motivate me push through and not settle in relaxation. 
- I hope that this website serves its intended purpose. Thank you.

## Feedback & Suggestions:
### Community Feedback:

- **Melvin Aguilar 🧑🏻‍💻** • 41,690 [_(@MelvinAguilar)_](https://github.com/MelvinAguilar)

  - Alt text 📷:
    - The `alt` attribute should not contain underscores or hyphens, it must be human readable and understandable.
    - The `alt` attribute should not contain the words "image", "photo", or "picture", because the image tag already conveys that information.
    - The `alt` attribute should **explain the purpose of the image**. 
      - Upon scanning the QR code, the user will be redirected to the frontendmentor.io website, 
      - So a better alt attribute would be: **`alt="QR code to frontendmentor.io"`**
    - If you want to learn more about the alt attribute, you can read this [article 📘](https://webaim.org/techniques/alttext/).

  - CSS 🎨:
    - Setting the width of the component with a percentage or a viewport unit will behave strangely on mobile devices or large screens. 
    - You should use a `max-width: 320px` or `20rem` to make sure that the component will have a **maximum width of 320px** on any device.
    - Also remove the width property with a percentage value.

    - A tip, instead of using `flexbox` and having `width: 87%` to center the image **you could use padding** on the component, 
      - This way you would create the space between the image and the component border and not repeat so much code. 
    - To give you an idea, the challenge does not require any media query, 
      - It can be made responsive for all devices just by using the necessary styles.

  ```css
    main > section {
        /* padding: 1rem 0rem; */
        background-color: var(--white);
        /* width: 85vw; */
        padding: 1rem;
        max-width: 318px;
        text-align: center;
    }

    div img {
        width: 100%;
        /* max-width: 87.5%; */
    }
  ```

<br>

### Next Action (Soon):
- [ ] Implement changes from community feedback
- [ ] TBA...

## Note:
- I would be happy to recieve comments, criticism, and such that could improve the website:
  - Better way of doing this website
  - Cleaner Code
  - Better Practice

<br>

_Updated Feb 12, 2023_
