---
title: 'PopOver'
metaTitle: 'Bootstrap 5 Popover - Bootstrap CSS tutorial'
metaDescription: Bootstrap 5 popover is component that allows you to add a popover to your project."
---# Bootstrap 5 Popover

Bootstrap 5 popover is component that allows you to add a popover to your project. They are applied when you wish to give a user more information about an elements he/she is hovering about.

This is a guide to adding Bootstrap 5 popovers to any element on your website. They're similar to the ones on iOS.

<i/>

## Popovers

###### html

```html
<button
  type="button"
  class="btn btn-dark example1"
  data-toggle="popover"
  title="Popover title"
  data-content="And here's some amazing content. It's very engaging. Right?"
>
  Click to toggle popover
</button>
```

## Dismiss Popovers

###### html

```html
<a
  tabindex="0"
  class="btn btn-dark example2"
  role="button"
  data-toggle="popover"
  data-trigger="focus"
  title="Dismissible popover"
  data-content="And here's some amazing content. It's very engaging. Right?"
  >Dismissible popover
</a>
```

## Four directions

###### html

```html
<button
  type="button"
  class="btn btn-dark example3"
  data-container="body"
  data-toggle="popover"
  data-placement="top"
  data-content="Sed nulla elit, suscipit sed porta non, consequat a purus."
>
  Popover on top
</button>

<button
  type="button"
  class="btn btn-dark example4"
  data-container="body"
  data-toggle="popover"
  data-placement="right"
  data-content="Sed nulla elit, suscipit sed porta non, consequat a purus."
>
  Popover on right
</button>

<button
  type="button"
  class="btn btn-dark example5"
  data-container="body"
  data-toggle="popover"
  data-placement="bottom"
  data-content="Sed nulla elit, suscipit sed porta non, consequat a purus."
>
  Popover on bottom
</button>

<button
  type="button"
  class="btn btn-dark example6"
  data-container="body"
  data-toggle="popover"
  data-placement="left"
  data-content="Sed nulla elit, suscipit sed porta non, consequat a purus."
>
  Popover on left
</button>
```

###### Script

```javascript
   <script src="bootstrap/bootstrap.bundle.min.js"></script>
    <script>
      // Example 1
      new bootstrap.Popover(document.querySelector('.example1'), {
        container: 'body',
      });
      // Example 2
      new bootstrap.Popover(document.querySelector('.example2'), {
        trigger: 'focus',
      });

      // Example 3, 4, 5, 6
      new bootstrap.Popover(document.querySelector('.example3'), {
        trigger: 'focus',
      });
      new bootstrap.Popover(document.querySelector('.example4'), {
        trigger: 'focus',
      });
      new bootstrap.Popover(document.querySelector('.example5'), {
        trigger: 'focus',
      });
      new bootstrap.Popover(document.querySelector('.example6'), {
        trigger: 'focus',
      });
    </script>
```
