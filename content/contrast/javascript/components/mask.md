---
title: 'Mask'
metaTitle: 'Bootstrap 5 Mask - Bootstrap CSS tutorial '
metaDescription: "Bootstrap 5 Masks change an element's visibility by hiding it completely or partially."
---# Mask

Bootstrap 5 Masks change an element's visibility by hiding it completely or partially. Contrast Design Masks are used to increase the visibility of material in a photo.

## Mask Patterns

The material that we are attempting to hide or partially hide, usually an image, remains in the `div` with the class `view`. This content is positioned above the mask `div`. The overlay or pattern over the content is the `div` with the class `mask`. Patterns are used in the code below, and there are plenty to pick from, ranging from pattern-1 to pattern-4.

![Bootstrap Mask Patterns](https://imgur.com/MCquXaE.png)
![Bootstrap Mask Patterns](https://imgur.com/qzyTCFL.png)
![Bootstrap Mask Patterns](https://imgur.com/FOb0fkk.png)
![Bootstrap Mask Patterns](https://imgur.com/FtwM3yj.png)

###### html

```html
<div class="view">
  <img src="../img/food.jpg" />
  <div class="mask pattern-1"></div>
</div>
<div class="view">
  <img src="../img/food.jpg" />
  <div class="mask pattern-2"></div>
</div>
<div class="view">
  <img src="../img/food.jpg" />
  <div class="mask pattern-3"></div>
</div>
<div class="view">
  <img src="../img/food.jpg" />
  <div class="mask pattern-4"></div>
</div>
```

## Mask Light Overlay

To use a light mask overlay instead of a mask, give your mask `div` the class rgba, then the color you want your overlay to be, and finally the word light (to select the thickness of our overlay

![Bootstrap Mask Light Overlay](https://imgur.com/Yoxa6Xr.png)
![Bootstrap Mask Light Overlay](https://imgur.com/XgzFd30.png)

###### html

```html
<div class="view">
  <img src="../img/food.jpg" />
  <div class="mask rgba-blue3-light"></div>
</div>
```

## Mask Strong Overlay

If you'd prefer a more robust Overlay background, append strong to the class instead.

![Bootstrap Mask Strong Overlay](https://imgur.com/Q0y0x7A.png)
![Bootstrap Mask Strong Overlay](https://imgur.com/39KbCT0.png)

###### html

```html
<div class="view">
  <img src="../img/food.jpg" />
  <div class="mask rgba-blue-strong"></div>
</div>
```
