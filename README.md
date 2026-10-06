# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./Screenshot_6-10-2026_84342_.jpeg)

### Links

- Solution URL: [https://github.com/Saboor03/bento-grid](https://github.com/Saboor03/bento-grid)
- Live Site URL: [https://bento-grid-weld-beta.vercel.app/](https://bento-grid-weld-beta.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to use CSS Grid to place cards differently on mobile and desktop. On mobile the cards simply stack in HTML order. On desktop, `grid-template-areas` works like a map of the layout:

```css
grid-template-areas:
  "create hero   hero     schedule"
  "create manage maintain schedule"
  "write  manage maintain schedule"
  "write  stat   grow     grow";
```

I also learned that file paths are case-sensitive on Vercel. A folder named `CSS` worked on my computer but not online until the link in my HTML matched the exact spelling.

### Continued development

I want to get more comfortable with CSS Grid, especially placing items across rows and columns, and with measuring sizes from a static design image. I would also like to add a tablet layout.

## Author

- Name - Saboor Orimadegun
- Frontend Mentor - [@Saboor03](https://www.frontendmentor.io/profile/Saboor03)