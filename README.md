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
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

- I have used Tailwind CSS to design the component, which is used to display the profile and its social media links.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop Sreenshot](./screenshot/Screenshot_Desktop.png)

![Mobile Sreenshot](./screenshot/Screenshot_Mobile.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/DhahiraThesneem/frontEnd-Mentor/tree/master/social-links-profile-main_tailwind)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- [Tailwind CSS](https://tailwindcss.com/) - Tailwind CSS 
- Flexbox
- Mobile-first workflow

### What I learned

- I have learned how to use Tailwind CSS using CDN

```html
<script src="https://cdn.tailwindcss.com"></script>
```

- I have understood how to customized font size, colors, and font-family. 

```html
<script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            transparent: 'transparent',
            current: 'currentColor',
            'font-color-white': '#ffffff', //hsl(0, 0%, 100%);
            'highlight': '#c5f82a', //hsl(75, 94%, 57%);
            'button-color': '#333333', //hsl(0, 0%, 20%);
            'card-color': '#1f1f1f', //hsl(0, 0%, 12%);
            'gray-color': '#141414', //hsl(0, 0%, 8%);
          },
          fontSize: {
            'smaller-title': '7px', // Define a custom font size for place
            'smaller-place': '8.4px',
            'smaller': '10px',
          },
          fontFamily: {
            'sans': ["Inter", 'sans-serif']
          },
        }
      }
    }
  </script>
```

### Continued development

- In this project, I have designed using normal HTML and then I converted into Tailwind CSS. In future project, I want to use Tailwind CSS from scratch. 

### Useful resources

- [Example resource 1](https://tailwindcss.com/) - This helped me for learing Tailwind CSS.


## Author

- Frontend Mentor - [@DhahiraThesneem](https://www.frontendmentor.io/profile/DhahiraThesneem)

