# Project Documentation for Jake Lawton

## Project Summary
The team project was a new challenge for us and we had to learn how to communicate and cooperate in a way we haven't before.
Initially we had problems with how we shared code, some technical problems with google drive and git.
However, we ultimately solved these technical problems and as a group we worked really well together able to put together a site we could be proud of.
Everyone contributed something to the project that was valuable and impactful so the end product was a success by the standards we set.

### Code
> Code Example 1: in the below code I made the cards, using bootstrap, that were displayed on the info page.
```html
    <div class="row">
      <div class="card col-lg-3">
        <button>
          <img
            src="https://images.unsplash.com/flagged/photo-1567793483424-e20eb6c94a53?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8d2VkZGluZyUyMHBpY3R1cmV8ZW58MHx8MHx8fDA%3D"
            alt="Samiranna Photography Wedding"
            class="object-fit-cover"
            style="width: 100%"
          />
          <div class="container">
            <h2><b>Weddings</b></h2>
            <p>Approximate price range: $800-$1200</p>
          </div>
        </button>
      </div>
      <div class="card col-lg-3">
        <button>
          <img
            src="https://images.unsplash.com/photo-1541014871-22a89a9281e6?q=80&w=3024&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            alt="Samiranna Photography Wedding"
            class="object-fit-cover"
            style="width: 100%"
          />
          <div class="container">
            <h2><b>Family Events</b></h2>
            <p>Approximate price range: $600-$1000</p>
          </div>
        </button>
      </div>
      <div class="card col-lg-3">
        <button>
          <img
            src="https://images.unsplash.com/photo-1517457373958-b7bdd4587205?q=80&w=3869&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
            alt="Samiranna Photography Wedding"
            class="object-fit-cover"
            style="width: 100%"
          />
          <div class="container">
            <h2><b>Dances</b></h2>
            <p>Approximate price range: $500-$900</p>
          </div>
        </button>
      </div>
      <div class="card col-lg-3">
        <button>
          <img
            src="https://images.unsplash.com/photo-1475503572774-15a45e5d60b9?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8aGFwcHklMjBmYW1pbHl8ZW58MHx8MHx8fDA%3D"
            alt="Samiranna Photography Wedding"
            class="object-fit-cover"
            style="width: 100%"
          />
          <div class="container">
            <h2><b>Other</b></h2>
            <p>Approximate price range: $400-$1400</p>
          </div>
        </button>
      </div>
    </div>
```
> Code Example 2: This is the CSS code for the cards, this was important for making them look more presentable and responsive.
```css
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  display: flex;
  margin: 1rem;
  margin-bottom: 0;
  padding: 1rem;
}
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
}
.card img {
  border-radius: 5px 5px 5px 5px;
  width: 10rem;
  height: 20rem;
}
.card button {
  border-width: 0;
  background-color: rgba(0, 0, 0, 0);
}
.row {
  width: 100%;
  margin-top: auto;
   display: flex;
  justify-content: space-evenly; 
}

```
> Code Example 3: In this code I did a lot of decoration for the background and site container of our home page and some of this code is applied to other pages, additionally I set colors for future use so that the theme would remain consistent on every page.
```css
body {
    background-color: var(--tertiary);
    background-image: url(./assets/floralBorder.png);
    background-size:100px;
    margin:0;
    padding:0;
}
.site-container {
    width:80%;
    height:100%;
    margin:auto;
    box-shadow: 0 0 10px;
    background-color: var(--tertiary);
}
:root {
    --primary: #BE8868;
    --secondary: #D5B8A1;
    --tertiary: #E1D5CA;
    --quaternary: #EDE2D9;
}
.primaryBGC {
    background-color: var(--primary);
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
@media (max-width:1024px){
    .site-container{
        width:100%;
        margin:0;
        padding:0;
        overflow:hidden;
    }
    body {
        background-image: none;
        padding:0;
        margin:0;
    }
    .p-3 {
        margin:0;
    }
}
```