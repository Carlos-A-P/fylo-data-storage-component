# Fylo data storage component

- Live website -(https://cpwd-fylo-storage-component.netlify.app/)

## Table of contents

- [The challenge](#the-challenge)
- [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

## My process

### Screenshot

### End Result

![result](https://user-images.githubusercontent.com/85038929/129496173-6aa98e4f-fd27-4497-858b-f4b86e61a81a.JPG)

### Active image

![mobile](https://user-images.githubusercontent.com/85038929/129496175-a4bbd696-167a-47f5-bfb7-9455a272b0eb.JPG)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS FlexBox
- Media Queries

### What I learned

This is project is a challenge to test my css skills. I used HTML and CSS to complete the project and what I found most helpful was the clip-path style property and position property

Here is some code that I wrote in order to complete this task

```HTML
    <div class="pop-up-2">
      <p><span>185</span> GB Left</p>
      <div class="clipped-square"></div>
    </div>

```

```CSS
	.clipped-square {
		background: white;
		position: absolute;
		clip-path: polygon(100% 0%, 0% 100%, 100% 100%);
		transform: rotate(270deg);
		height: 44px;
		width: 40px;
		top: 45px;
		right: 1.2px;
	}
```

### Questions

- What could be a better way to position the storage data div?

### Useful resources

- [clip-path](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path) - this helped me clip a div so that I can use it under the storage data div

- [position](https://developer.mozilla.org/en-US/docs/Web/CSS/position) - I used this property to position the data div

## Author

- Website - [Carlos Perez](https://github.com/Carlos-A-P/fylo-data-storage-component)
- Frontend Mentor - [@Carlos-A-P](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@WDCarlosP](https://www.twitter.com/WDCarlosP)
