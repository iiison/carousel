carousel
========

Minimal Carousel.

Dependency: Juqery.

How To Use:

- Include carousel.js and styles.min.css to your code html.
- Give `slide` class  to the div you want to animate.
    This should be HTML sturucture:

      `<div class="random-class-name">
        <div class="slide"></div>
        <div class="slide"></div>
        <div class="slide"></div>
        <div class="slide"></div>
      </div>`
      
      
  Inner Div should have `slide` class otherwise it won't work.
- Initialte Carousel using JS/JQ:  $('.car').carousel({'speed':700});
- `speed` is a parameter to control the animation speed.
- I will add more params soon :).

A working example can be seen at http://codepen.io/iiison/pen/XJbqYM.
