---
title: 'Button'
metaTitle: 'Bootstrap 5 Button - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 button allows users to interact with your website.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/buttons.md"
---

# What is Bootstrap 5 button?

Users can interact with your website using the Bootstrap 5 Button. In terms of size, form, and color, they are simple to alter. They include a number of pre-defined button styles, each with its own logical function and a few more features.

## Default Buttons

Bootstrap button (Contrast) predefined style can be used by adding the classes `btn` and `btn-primary` (primary designating our button's background color) to a button element.

<buttonExample1 />

<!-- ![Bootstrap Box](./images/buttonbasic.png) -->

```html
<button class="btn btn-primary">Primary</button>
<button class="btn btn-secondary">Secondary</button>
<button class="btn btn-success">Success</button>
<button class="btn btn-danger">Danger</button>
<button class="btn btn-warning">Warning</button>
<button class="btn btn-info">Info</button>
<button class="btn btn-light">Light</button>
<button class="btn btn-dark">Dark</button>
<button class="btn btn-link">Link</button>
```

## Bootstrap 5 Circular Buttons (Contrast)

The class `btn-rounded` provides our Bootstrap 5 Button (Contrast ) a more rounded look.

<buttonExample2 />

```html
<button class="btn btn-primary btn-rounded">Primary</button>
<button class="btn btn-secondary btn-rounded">Secondary</button>
<button class="btn btn-rounded btn-success">Success</button>
<button class="btn btn-danger btn-rounded">Danger</button>
<button class="btn btn-warning btn-rounded">Warning</button>
<button class="btn btn-info btn-rounded">Info</button>
<button class="btn btn-light btn-light btn-rounded">Light</button>
<button class="btn btn-light btn-dark btn-rounded">Dark</button>
```

## Bootstrap 5 Outline Buttons

We use the `class` `btn-outline-primary` to make our buttons have only an outline and no background color. The color of the outline of your button is determined by the last word applied to the class name.

<buttonExample3 />

```html
<button className="btn btn-outline-primary">Primary</button>
<button className="btn btn-outline-secondary">Secondary</button>
<button className="btn btn-outline-success">Success</button>
<button className="btn btn-outline-danger">Danger</button>
<button className="btn btn-outline-warning">Warning</button>
<button className="btn btn-outline-info">Info</button>
<button className="btn btn-outline-light">Light</button>
<button className="btn btn-outline-dark">Dark</button>
```

## Bootstrap 5 Button Size

We can use the classes `btn-sm` (small size buttons), `btn-md` (medium or default sized button), and finally `btn-lg`(large sized button) to set the size of a button.

<buttonExample4 />

```html
<button className="btn btn-danger btn-xl">Xl</button>
<button className="btn btn-primary btn-lg">Lg</button>
<button className="btn btn-secondary btn-md">Md</button>
<button className="btn btn-success btn-sm">Sm</button>
```

<i/>

## Bootstrap 5 Buttons with Icon

<a href="/product/bootstrap-contrast-pro"><span class="badge badge-lg badge-pro">Pro Component</span></a>

<buttonExample5 />

On our website, we use the `i` element to add icons. We can have icons on our button by nesting a `i` tag in our button.

```html
<button type="button" class="btn btn-primary">
  <i class="fa fa-book"></i>
  <span> Primary </span>
</button>
<button type="button" class="btn btn-secondary">
  <i class="fa fa-user"></i>
  <span>Secondary </span>
</button>
<button type="button" class="btn btn-success">
  <i class="fa fa-check"></i>
  <span> Success </span>
</button>
<button type="button" class="btn btn-danger">
  <i class="fa fa-times"></i>
  <span> Cancel </span>
</button>
<button type="button" class="btn btn-dark btn-rounded">
  <i class="fa fa-home"></i>
  <span> Home </span>
</button>
<button type="button" class="btn btn-info btn-rounded">
  <i class="fa fa-book"></i>
  <span> Read </span>
</button>
<button type="button" class="btn btn-outline-warning btn-rounded">
  <i class="fa fa-lock"></i>
  <span> Lock </span>
</button>
```

<i/>

## Block Button

To make our Bootstrap 5 Button ( Contrast ) a block element, which means it will take up the entire width of the page or container it is in. We will use the class `btn-block` to achieve this result.

<buttonExample12 />

```html
<button type="button" class="btn btn-block btn-primary">
  Primary
</button>
<button type="button" class="btn btn-block btn-secondary">
  Secondary
</button>
<button type="button" class="btn btn-block btn-success">
  Success
</button>
<button type="button" class="btn btn-block btn-danger">Danger</button>
<button type="button" class="btn btn-block btn-warning">
  Warning
</button>
<button type="button" class="btn btn-block btn-info">Info</button>
<button type="button" class="btn btn-block btn-light">Light</button>
<button type="button" class="btn btn-block btn-dark">Dark</button>
<button type="button" class="btn btn-block btn-link">Link</button>
```

<i/>

## Button Gradients

<a href="/product/bootstrap-contrast-pro"><span class="badge badge-lg badge-pro">Pro Component</span></a>

We can customize the styles of our Bootstrap 5 Buttons (Contrast) to have a gradient background.

<buttonExample6 />

```html
<button className="btn btn-gradient-primary">Primary</button>
<button className="btn btn-gradient-secondary">Secondary</button>
<button className="btn btn-gradient-success">Success</button>
<button className="btn btn-gradient-danger">Danger</button>
<button className="btn btn-gradient-warning">Warning</button>
<button className="btn btn-gradient-info">Info</button>
<button className="btn btn-gradient-light">Light</button>
<button className="btn btn-gradient-dark">Dark</button>
```

<i/>
