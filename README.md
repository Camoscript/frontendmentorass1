# Frontend Mentor - Product preview card component solution


### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/screenshot.png)


### Links

- Solution URL: [Github](https://github.com/Camoscript/frontendmentorass1)
- Live Site URL: [Vercel site](https://frontendmentorass1.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

i am getting the hang of using media queries
```css

@media screen and (max-width: 375px) {
  #container {
    margin: auto;
    height: 1300px;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    /* overflow: visible; */
    /* border: 2px solid black; */
    width: 494px;
    border-radius: 15px;
  }
  #img{
    height: 500px;
    width: 494px;
    background-size: cover;
    background-image: url(images/image-product-mobile.jpg);
    margin-bottom: -5px;
  }
  #info-side{
    height: 750px;
    width: 494px;
  }
}
```
### Continued development

I would be grateful of I could get more insight on css grid and more flex box functionality


## Author

- Name - Emmanuel Tobi
- Frontend Mentor - [@Camoscript](https://www.frontendmentor.io/profile/Camoscript)
- Twitter - [@Camoscript(https://www.twitter.com/Camoscript1)


