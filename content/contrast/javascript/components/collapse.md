---
title: 'Collapse'
metaTitle: 'Bootstrap 5 Collapse - Bootstrap CSS tutorial'
metaDescription: 'Toggle content with Bootstrap 5 Collapse'
---

# Bootstrap 5 Collapse

Content is toggled by using the Bootstrap 5 Collapse component. It can be used to organize a large number of texts and/or visuals into expanding and collapsing items.

They're utilized to reveal and conceal information. Buttons, also known as anchors, are utilized as triggers for certain items that you toggle. When you collapse an element, the `height` value will animate to `0`.

## Default Collapse

![Bootstrap Collapse Default](https://i.imgur.com/PqwJe4o.gif)

###### html

```html

```

## Opened Collapse

###### html

```html
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img
        src="https://mdbootstrap.com/img/Photos/Slides/img%20(45).jpg"
        class="d-block w-100"
        alt="first slide"
      />
    </div>
    <div class="carousel-item">
      <img
        src="https://mdbootstrap.com/img/Photos/Slides/img%20(46).jpg"
        class="d-block w-100"
        alt="second slide"
      />
    </div>
    <div class="carousel-item">
      <img
        src="https://mdbootstrap.com/img/Photos/Slides/img%20(47).jpg"
        class="d-block w-100"
        alt="third slide"
      />
    </div>
  </div>
  <a
    class="carousel-control-prev"
    href="#carouselExampleIndicators"
    role="button"
    data-slide="prev"
  >
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a
    class="carousel-control-next"
    href="#carouselExampleIndicators"
    role="button"
    data-slide="next"
  >
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
```
