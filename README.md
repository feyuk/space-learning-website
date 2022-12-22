# Space Learning Website

![Space tourism website](./image-preview.png)

## Note:

I used **Vanilla javascript** to change the content of the pages by fetching the data from the `json` local file
```js
eleId.textContent = jsonData[idField];
```

### Features:

- View the optimal layout for each of the website's pages depending on their device's screen size
- See hover states for all interactive elements on the page
- View each page and be able to toggle between the tabs to see new information


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Accessibility workflow
- Vanilla Javascript

### What I learned

This challenge helped me to better understand the advanced use of the CSS `grid` and to discover some new CSS properties, such as :  
```css
.example {
  padding-inline: clamp(1.5rem, 5vw, 3.5rem);
  margin-block: 1rem;
  aspect-ratio: 1;
}
```
I was also able to learn more about `aria-attribute` and how to create a floating menu with it.
