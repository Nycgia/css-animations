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
### Translate
```css
  wrapper {
    /* Use this to translateZ */
    perspective: 200px;
    /* perspective-origin: x y -> (top, bottom, left. right) */
    perspective-origin: top right;
  }

  element {
    /* transform: translate(-100px, 100px) -> translate(x, y)*/
    /* transform: translateX(100px); */
    /* transform: translateY(100px); */
    /* transform: translateZ(100px); */
    /* transform: translate3d(x, y, z); */
    transform: translate3d(100px, 100px, 100px);
  }
```
### Scale
```css
  element {
    /* transform: scale(x, y || (xy)) */
    /* transform: scale(2); */
    /* 0 = 0%, .5 = 50%, 1 = 100%, 2 = 200% */
    transform: scale(2);
  }
```
### Skew
```css
  element {
    /* transform: skewX(45deg); */
    /* transform: skewY(45deg); */
    /* transform: skew(x, y); */
    transform: skew(20deg, 20deg);
  }
```
### Transform Origin
```css
  element {
    /* transform-origin: x y; -> (top, bottom, right, left)*/
    transform-origin: top left;
  }
```