# Project Documentation for Your Name

## Project Summary
    I created the Contact page of the Samiranna Website. I worked on the html and css on the contact page. I had to make a way for future costumers to get in contact with the owners of Samiranna.  
## Code Description
> Code Example 1: in the below code I made the css responisve to make the web page look nice even in smaller screens.
```css
@media (max-width:768px){
  nav {
    width: 100%;
    margin: auto;
   /* border: 1px solid black; */
    height: 15vh;
    z-index: 100;
    display: flex;
    background-color: var(--primary);
    scroll-behavior: smooth;
    flex-direction: row;
    box-shadow: 0px 0px 18px 0px rgba(0,0,0,0.59);
  }
}
```

> Code Example 2: This is how I created a way for customers to describe their request for more clear communication between the customer and the owners.
```html
<p style="text-align: center;">Describe Your Request</p>
        <input type="textera" class="description-control" placeholder="Any Special Request?">
        <div class="endButton"><button id="send">send</button></div>
```

> Code Example 3: I customized the sign up div to look the most presentable for the customer and to follow what the owners of SAMIRANNA requested.
``` css

div.sign-up{
    display: flex;
    align-items: center;
    justify-content: center;
    border-top: 1px solid rgba(0, 0, 0, alpha);
    border-left:1px solid black ;
    border-right: 1px solid black;
    border-bottom: 1px solid black;
    /* position: relative; */
    margin: auto;
    background-color: white ;
    width: 80%;
    padding: 0;
    box-shadow: 0px 14px 18px 5px rgba(0,0,0,0.59);
  }
```