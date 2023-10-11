# Muhammad Rizki Aldiansyah Profile

> This is an assignment example for "My Profile"

## My Bio

Hi, I'm Aldi. Product Owner

![Foto Aldi](/assets/foto-aldi.jpeg)

Experienced and passionate as Product Owner with a years experience then relentless drive for delivering excellence in the WEB3, ERP and SaaS industry. Committed to mastering the intricacies of the Product Development Life Cycle and constantly seeking deeper insights into the world of Software Engineering.

My mission is to craft solutions that empower businesses to thrive and evolve in the ever-changing digital landscape. I'm dedicated to delivering value through user-centered, innovative products and continuous improvement. My Skill-set as a Product Owner is in good communication to maintenance stakeholders with their prioritization, focused on Product/Project Management, Documentation BRD/PRD, Prioritization Decision, Brainstroming Ideas, and Product Market Fit.

## My Links

- Website: [rzkproject.com](https://rzkproject.com/)
- Github: [@rzkProject](https://github.com/rzkProject)
- LinkedIn: [rizkialdiansyah](https://www.linkedin.com/in/rizkialdiansyah/)

## My Technical Skills

1. Product Requirement Document
2. User Journey
3. SCRUM
4. Figma, Miro, Whimsical
5. Agile Development
6. Software Tester

## My Favorit Website

| Name         | URL                            | Reason                                           |
| ------------ | ------------------------------ | ------------------------------------------------ |
| Netflix      | <https://www.netflix.com>      | To view my favorite series and movies            |
| LinkedIn     | <https://www.linkedin.com>     | To search job opportunity and read good articles |
| Spotify      | <https://www.spotify.com>      | To listen my favorite podcasts and songs         |
| FreeCodeCamp | <https://www.freecodecamp.org> | To sharpen my coding knowledge                   |

## My Code Examples

### Markdown

```markdown
# Hello World

Markdown is a lightweight markup language that is commonly used for formatting and structuring plain text documents.
```

### HTML

```html
<h1>To Do List</h1>
<h2>Monday</h2>
<div class="box">
  <p class="done">Do these things today!</p>
  <ul class="list">
    <li>Wash Clothes</li>
    <li class="done">Read</li>
    <li class="done">Maths Questions</li>
  </ul>
</div>

<ul>
  <p class="done">Other items</p>
</ul>
<p>The best preparation for tomorrow is doing your best today.</p>
```

### CSS

```css
body {
  font-family: "Poppins", sans-serif;
  margin: 50px 50px 0 50px;
  background-color: #faf9f6;
  display: flex;
  flex-direction: column;
  min-height: 95vh;
}
.main {
  flex: 2;
}

h1 {
  font-size: 5rem;
}

footer {
  text-align: right;
  color: midnightblue;
}
```

### Java Script

```JS
let slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
}

let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}
  slides[slideIndex-1].style.display = "block";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
```

---

## I'm grateful that you've taken the time to peruse my profile. Thank you!

Open to networking, collaborations, and discussions on all things ERP, SaaS, and Software Engineering. Let's connect and explore the possibilities together!

Cheers!
[Muhammad Rizki Aldiansyah](https://www.linkedin.com/in/rizkialdiansyah/)
