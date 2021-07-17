# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot-desktop.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://cla91.github.io/stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This was my first project and it was quite challenging, but I learnt a lot.
* I'm not a PRO Member, so I've had to guess a lot of sizes with not so little trouble 😅. I used Photoshop and the firefox developer tool to aid me in all the process, expecially for typography;
* I found out that when resizing window with firefox developer tool, instead of int number for the content it uses float. This gave me a lot of trouble with the media queries, because at first I wanted to set the max width for the mobile at 375px and the min width for the desktop at 376px. The problem arose because when selecting a viewport of 375px the browser actually calculated the content at 375.2px (which makes no sense to me, I mean portions of 1 px don't exist), so in the range between 375 and 376 the media queries didn't work, because it was outside of range. After serching on google I found this [link](https://stackoverflow.com/questions/63637584/bug-with-browsers-interpretation-of-media-queries) that explained well my problem. It seems this is "normal" firefox behavior and it's not a "real" problem because media queries usally target a broad range of screen size and there's little to no device that actually has a width so near to the breakpoints. In the end, I changed the breakpoint to a wider one because I thougth that the one column layout would work well on tablet too. The problem is still there, but I don't know what's the best solution.
* I learnt that when using the picture element, if you don't apply the display: block property to the img element, the picture element actually adds height to the img itself;
* I also learnt how to apply a color overlay on an image;
* I learnt how to vertical align div in the whole page using the vh unit;
* It was my first time using rem units and it was way more manageable than em units;

### Continued development

* I should practice more using flexbox and should definitely learn CSS grids.

### Useful resources

- [Convert typographic property from PS to CSS](https://martinwolf.org/before-2018/blog/2016/02/convert-typographic-properties-from-photoshop-to-css/) - This helped me with the typography. I don't this I would have made it this well without it. I'll definitely use it again, if like this time I've only a static image of the design.
- [PX to EM conversion](https://www.w3schools.com/tags/ref_pxtoemconversion.asp) - It was fundamental. 
- [Autoprefixer](https://autoprefixer.github.io/) - I wouldn't know where to begin whitout it 😄.


## Author

- Frontend Mentor - [@cla91](https://www.frontendmentor.io/profile/cla91)



