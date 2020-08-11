# Animations in CSS
## Transitions (Example)
```css
transition-property: width, height;
transition-duration: 1s;
transition-delay: 1s;
transition-timing-function: ease;
/* Short */
/* property - duration - delay - timing-function */
transition: width 1s 1s ease;
```
## Transforms
With `transform` we can rotate, skew, change the position or size of an element.
### Rotate
```css
element {
  /* transform: rotate(-45deg); Z */
  /* transform: rotateX(-45deg); */
  /* transform: rotateY(-45deg); */
  /* transform: rotateZ(-45deg); */

  /* transform: rotate3d(x, y, z, deg); */
  transform: rotate3d(1, 1, 1, 45deg);
}
```
