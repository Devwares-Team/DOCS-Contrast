---
title: 'Box'
metaTitle: 'Bootstrap 5 Box - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 boxes are layout components that assist in the creation of build components for CSS utility purposes.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/box.md"
---

# Bootstrap 5 Box

Bootstrap 5 Boxes are layout components that assist in the creation of build components for CSS utility purposes.

Bootstrap Box component can become any element from `ElementType` like `div`, `span`, `img`, `video` etc.

<Box1/>

###### HTML

```html
<span>Span</span>
<div>Div</div>
<p>Paragraph</p>
<section>Section</section>
```

## Display

We can define display styles for our boxes by giving our `div` a `class` of d and then appending the display style we want (flex, block, inline). For example `<div class="d-flex">Display Flex</div>`, for a display style of `flex`.

<Box2/>

###### HTML

```html
<div class="d-flex">Display Flex</div>
<div class="d-block">Display Block</div>
<div class="d-inline">Display Inline</div>
```

## Flex

To determine the flex orientation of your elements. We add a flex `class` to our element, which adds the direction ( column or row). For example `<div class="d-flex flex-column"></div>`.

<Box3/>

###### HTML

```html
<div class="d-flex flex-column">
  <p>Coloumn</p>
  <p>Coloumn</p>
  <p>Coloumn</p>
</div>
<div class="d-flex flex-row ">
  <p>row</p>
  <p>row</p>
  <p>row</p>
</div>
```

## Colors

Text color can be set in elements by giving the element a `class` of text and appending a color code. For example `<div class="text-danger">Danger</div>`.

<Box4/>

###### HTML

```html
<div class="text-danger">Danger</div>
<div class="text-success">Success</div>
<div class="text-warning">Warning</div>
<div class="text-primary">Primary</div>
```

## Background Colors

Elements can be given a backdrop color with the Contrast Boostrap 5 Box component by adding the `bg` class and appending the desired color code to it. For example `<div class="bg-danger">Danger</div>`.

<box5/>

###### HTML

```html
<div class="bg-danger">Danger</div>
<div class="bg-success">Success</div>
<div class="bg-warning">Warning</div>
<div class="bg-primary">Primary</div>
```
