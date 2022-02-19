---
title: 'Carousel'
metaTitle: 'Bootstrap 5 Carousel - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 Carousel is a dynamic and interactive slideshow designed for presenting content, particularly images and videos.'
---

# Bootstrap 5 Carousel

Bootstrap 5 Carousel is a dynamic and interactive slideshow designed for presenting content, particularly images and videos.

It's a slideshow that allows you to cycle through a variety of stuff. Photos, text, and custom markup can all be utilized with it. Also supported are previous/next buttons and indicators.

## Default Carousel

![Bootstrap Carousel Default](https://i.imgur.com/NH00iYw.gif)

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
