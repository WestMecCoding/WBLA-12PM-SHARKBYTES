# Project Documentation Micah Kinnard

## Project Summary
     What I have worked on for our team project is the gallery and trying to make it work nicely whilst also looking amazing Throughout this time, I had gone ahead and found some help with the slides from online, and I have successfully implemented it along with a few images into our gallery. For the gallery itself, I used some images of people who have gone ahead and purchased different packages along the way. As an example, the first image on the slideshow is someone who purchased the other package, and they requested for a sunset image near the ocean, so we made said thing happen. 

     I also have gone ahead and given some support towards making our wireframe, and, although it wasn't exactly all that much, I still gave some support towards it. Another thing I had done is gather most of our images for said project and implemented them all into it so that we could use them for certain things, such as the info page, the gallery, and more. Finally, I also worked on the CSS for the gallery so that all of our code would work properly for said gallery.
## Code Descriptions
>Code1: in the below code I added a query selector, along with an interval of 2000, and a touch element of false to make the gallery slides able to switch between left and right on click in certain areas.
```js
const myCarouselElement = document.querySelector('#myCarousel')

const carousel = new bootstrap.Carousel(myCarouselElement, {
  interval: 2000,
  touch: false
})
```
>Code2: The code below this text is the code that I used for the images to be incorperated inside of the slides, and, without it, I would have only been able to produce one image and it would be unable to move left to right to swap slides, as there would be no slides to switch from.
```html
<div id="carouselExample" class="carousel slide">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="./wedding1.png" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="./wedding2.png" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="./wedding4.png" class="d-block w-100" alt="...">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
```
> Code example 3: The code below I have added to the gallery.css because, without it, we would be unable to add in the colors for the nav bar along with making the nav bar appear alongside the images properly.
```css
:root {
    --primary: #BE8868;
    --secondary: #D5B8A1;
    --tertiary: #E1D5CA;
    --quaternary: #EDE2D9;
}
.primaryBGC {
    background-color: var(--primary);
    margin-bottom: 5%;
  }
  .secondaryBGC {
    background-color: var(--secondary);
  }
  .tertiaryBGC {
    background-color: var(--tertiary);
  }
  .quaternaryBGC {
    background-color: var(--quaternary);
  }

  .nav-item{
    margin-left:5vw;
    font-size: 1.5vw;
  }
```