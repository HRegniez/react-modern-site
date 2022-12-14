# GPT-3_OpenAI-REACT( ...in progress )

This is a solution to the [AK Shakir's figma design](https://www.figma.com/file/lz9lLpFHMxHm2odnwM3R0z/gpt3?node-id=0%3A1&t=NCINiLtMEFoxXNq0-0).

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

decided to take on this challenge in the idea of getting used to the REACT.js synthax and implementing the CSS BEM model to this one.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- Create-React-App
- Restructure my 'src' folder to fit the design
- install React icons
- set up global styles

### Built with

- CSS custom properties
  - BEM Method
  - CSS variables
- [React](https://reactjs.org/) - JS library
  - React icons

### What I learned

- React icons:

```js (react)
import { FaBeer } from "react-icons/fa";

class Question extends React.Component {
  render() {
    return (
      <h3>
        {" "}
        Lets go for a <FaBeer />?{" "}
      </h3>
    );
  }
}
```

https://react-icons.github.io/react-icons

- AngryTools: to make gradients

https://angrytools.com/gradient/

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- https://angrytools.com/gradient/ - To create a gradient
- https://animista.net/play/basic/shadow-inset - To animate site

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.
