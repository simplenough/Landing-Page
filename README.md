# Landing Page

## Learnt

- Percentages for element sizes are relative to the next container with a static width, i.e. if the parent container is also using a relative size, like 25% or 100%, then it looks for the parent of the parent.

```css
.testimonials-img {
    float: right;
    width: 25%;
}
```
-Solution: added img class

```html
<div class="test-img-container">
          <img class="test-img" src="/assets/testimonials_img.jpg" alt="Testimonial image"/>
        </div>
````