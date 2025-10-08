# Frontend Mentor - Contact form solution

This is a solution to the [Contact form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/contact-form--G-hYlqKJj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- Complete the form and see a success toast message upon successful submission
- Receive form validation messages if:
  - A required field has been missed
  - The email address is not formatted correctly
- Complete the form only using their keyboard
- Have inputs, error messages, and the success message announced on their screen reader
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: https://github.com/HarunaZakaria/contact-form
- Live Site URL: https://harunazakaria.github.io/contact-form/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- javascript

### What I learned

During this project I learned some format as to how to group sosme items for better positioning purpose

```html
<h1>Some HTML code I'm proud of</h1>
```

<div class="form-groups">
  <div>
    <label for="firstname">First Name *</label> <br />
    <input type="text" name="firstname" required />
  </div>
  <div>
    <label for="lastname">Last Name *</label> <br />
    <input type="text" name="lastname" required />
  </div>
</div>
```css
* {
   --white-color: hsl(0, 0%, 100%);
  --red-color: hsl(0, 66%, 54%);
  --grey-lighter-color: hsl(148, 38%, 91%);
  --grey-mediu-color: hsl(186, 15%, 59%);
  --grey-dark-color: hsl(187, 24%, 22%);
  --green-color: hsl(169, 82%, 27%);
}
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
```

```js
const proudOfThisFunc = () => {
  console.log('🎉');
};
```

### Continued development

In my future project, I'm going to focus more on DOM and build more interactive projects to foster my learning

## Author

- Website - https://harunzy.netlify.app/
- Frontend Mentor - https://www.frontendmentor.io/profile/HarunaZakaria
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
