# Project Documentation for Joseph Lopotko

## Project Summary
Samiranna Photography is a company catering to couples' wedding photos. The website maintains a classy theme, using elegant fonts. The color accent revolves around the color brown. The color brown symbolizes dependability and stability, which are the values of Samiranna Photography. "Our vision is to be the go-to local photography company for weddings and other significant life events".

I had the responsibility of designing the home page. The nav bar is built on bootstrap, utilizing bootstrap CSS styles to achieve a clean, modernistic look. I extracted the nav bar logo from the client request PDF. The buttons in the footer each lead to their appropriate social media website. The social media icons are from a bootstrap library of SVG icons.

## Code Descriptions
> Code Example 1: I created a footer, giving padding from bootstrap's class styling. I wrapped buttons in address tags, each button having an href to a social media website. I found icons from bootstrap's SVG icon library and used the icons to represent each button's social media page.
```html
    <footer class="p-5">
        <h1>Follow Our Socials!</h1>
        <a href="https://x.com"><button id="social-button" type="button"><svg alt="twitter" xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" class="bi bi-twitter-x" viewBox="0 0 16 16">
            <path d="M12.6.75h2.454l-5.36 6.142L16 15.25h-4.937l-3.867-5.07-4.425 5.07H.316l5.733-6.57L0 .75h5.063l3.495 4.633L12.601.75Zm-.86 13.028h1.36L4.323 2.145H2.865z"/>
          </svg></button></a>
        <a href="https://instagram.com"><button id="social-button" type="button"><svg alt="instagram" xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16">
            <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.9 3.9 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233s.008-2.388.046-3.231c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92m-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217m0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334"/>
          </svg></button></a>
        <a href="https://facebook.com"><button id="social-button" type="button"><svg alt="facebook" xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16">
            <path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951"/>
          </svg></button></a>
    </footer>
```
> Code Example 2: In the code below, I used classes to implement a cached background color, a padding of 3%, and a height of 100% on a div.
```html
<div class="quaternaryBGC p-3 h-100"><h1>Personalized Approach</h1>
                <p>What sets Samiranna apart is
                  our personalized approach to
                  each project.Taking the time
                  to understand the unique stories
                  and preferences of clients,
                  ensuring that each photoshoot
                  reflects the individuality of the
                  people and the event.
                </p></div>
```
> Code example 3: In the CSS below, I optimized the index page for mobile screens by styling the elements of the page's wrapper. I used @media to assign these styles for mobile resolution. I made sure there was no whitespace with the use of margin 0, padding 0, and overflow hidden.
```css
@media (max-width:768px){
    .site-container{
        width:100%;
        margin: 0;
        padding:0;
        overflow: hidden;
    }
}
```