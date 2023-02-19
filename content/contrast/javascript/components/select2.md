---

title: 'Select 2'
metaTitle: 'Bootstrap 5 Select - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap Select is a form control, that after the click displays a collapsible list of multiple values which can be used in forms, menus or surveys'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/select2.md"
---
# Bootstrap 5 Select2

Bootstrap 5 Select is a component in our Contrast that displays a collapsible list of options. It may be used in forms, menus, and surveys.

Use the `↑` and `↓` arrow keys to browse between the options, and the `↵` key to choose the appropriate item with our Contrast Bootstrap 5 Select (does not works for stateless select).

<i/>

## Bootstrap Select2 Button

Give your `div` the class `select2` to use the Contrast Bootstrap 5 Select2 Button in your project.

<Select2a />

###### HTML

```html
<div class="select2">
  <div id="div">
    <span class="option">
      Choose Option
    </span>
    <i class="fa fa-angle-down"></i>
  </div>
  <div id="options">
    <div>
      <i class="fa fa-facebook"></i>
      <span>Option 1</span>
    </div>
    <div>
      <i class="fa fa-twitter"></i>
      <span>Option 2</span>
    </div>
    <div>
      <i class="fa fa-instagram"></i>
      <span>Option 3</span>
    </div>
    <div>
      <span>Option 4</span>
    </div>
    <div>
      <span>Option 5</span>
    </div>
  </div>
</div>
```

## Disable Select Button

To switch off your form select, use the `disabled` property.
<Select2b/>

###### HTML

```html
         <div
            class="select2 disabled"
          >
            <div id="div">
              <span class="option">
                Choose Option
              </span>
              <i class="fa fa-angle-down"></i>
            </div>
            <div id="options">
              <div>
                <i class="fa fa-facebook"></i>
                <span>Option 1</span>
              </div>
              <div>
                <i class="fa fa-twitter"></i>
                <span>Option 2</span>
              </div>
              <div>
                <i class="fa fa-instagram"></i>
                <span>Option 3</span>
              </div>
              <div>
                <span>Option 4</span>
              </div>
              <div>
                <span>Option 5</span>
              </div>
            </div>
          </div>

        </div>
```

## Colored Select Button

Use the select2 class and add the color code for the color you want your choose choice to be. This will give your select component color.

<Select2c/>

###### HTML

```html
<div class="select2 select2-primary">
  <div id="div">
    <span class="option">
      Choose Option
    </span>
    <i class="fa fa-angle-down"></i>
  </div>
  <div id="options">
    <div>
      <i class="fa fa-facebook"></i>
      <span>Option 1</span>
    </div>
    <div>
      <i class="fa fa-twitter"></i>
      <span>Option 2</span>
    </div>
    <div>
      <i class="fa fa-instagram"></i>
      <span>Option 3</span>
    </div>
    <div>
      <span>Option 4</span>
    </div>
    <div>
      <span>Option 5</span>
    </div>
  </div>
</div>
<div class="select2 select2-secondary">
  <div id="div">
    <span class="option">
      Choose Option
    </span>
    <i class="fa fa-angle-down"></i>
  </div>
  <div id="options">
    <div>
      <i class="fa fa-facebook"></i>
      <span>Option 1</span>
    </div>
    <div>
      <i class="fa fa-twitter"></i>
      <span>Option 2</span>
    </div>
    <div>
      <i class="fa fa-instagram"></i>
      <span>Option 3</span>
    </div>
    <div>
      <span>Option 4</span>
    </div>
    <div>
      <span>Option 5</span>
    </div>
  </div>
</div>
<div class="select2 select2-success">
  <div id="div">
    <span class="option">
      Choose Option
    </span>
    <i class="fa fa-angle-down"></i>
  </div>
  <div id="options">
    <div>
      <i class="fa fa-facebook"></i>
      <span>Option 1</span>
    </div>
    <div>
      <i class="fa fa-twitter"></i>
      <span>Option 2</span>
    </div>
    <div>
      <i class="fa fa-instagram"></i>
      <span>Option 3</span>
    </div>
    <div>
      <span>Option 4</span>
    </div>
    <div>
      <span>Option 5</span>
    </div>
  </div>
</div>
<div class="select2 select2-danger">
  <div id="div">
    <span class="option">
      Choose Option
    </span>
    <i class="fa fa-angle-down"></i>
  </div>
  <div id="options">
    <div>
      <i class="fa fa-facebook"></i>
      <span>Option 1</span>
    </div>
    <div>
      <i class="fa fa-twitter"></i>
      <span>Option 2</span>
    </div>
    <div>
      <i class="fa fa-instagram"></i>
      <span>Option 3</span>
    </div>
    <div>
      <span>Option 4</span>
    </div>
    <div>
      <span>Option 5</span>
    </div>
  </div>
</div>
<div class="select2 select2-warning">
  <div id="div">
    <span class="option">
      Choose Option
    </span>
    <i class="fa fa-angle-down"></i>
  </div>
  <div id="options">
    <div>
      <i class="fa fa-facebook"></i>
      <span>Option 1</span>
    </div>
    <div>
      <i class="fa fa-twitter"></i>
      <span>Option 2</span>
    </div>
    <div>
      <i class="fa fa-instagram"></i>
      <span>Option 3</span>
    </div>
    <div>
      <span>Option 4</span>
    </div>
    <div>
      <span>Option 5</span>
    </div>
  </div>
</div>
<div class="select2 select2-dark">
  <div id="div">
    <span class="option">
      Choose Option
    </span>
    <i class="fa fa-angle-down"></i>
  </div>
  <div id="options">
    <div>
      <i class="fa fa-facebook"></i>
      <span>Option 1</span>
    </div>
    <div>
      <i class="fa fa-twitter"></i>
      <span>Option 2</span>
    </div>
    <div>
      <i class="fa fa-instagram"></i>
      <span>Option 3</span>
    </div>
    <div>
      <span>Option 4</span>
    </div>
    <div>
      <span>Option 5</span>
    </div>
  </div>
</div>
```

## Colored Options with Hover

The `hoverColor` property adds a hover effect to your choose options.

<Select2d/>

###### HTML

```html
<div class="select2 select2-danger hoverColor">
  <div id="div">
    <span class="option">
      Choose Option
    </span>
    <i class="fa fa-angle-down"></i>
  </div>
  <div id="options">
    <div>
      <i class="fa fa-facebook"></i>
      <span>Option 1</span>
    </div>
    <div>
      <i class="fa fa-twitter"></i>
      <span>Option 2</span>
    </div>
    <div>
      <i class="fa fa-instagram"></i>
      <span>Option 3</span>
    </div>
    <div>
      <span>Option 4</span>
    </div>
    <div>
      <span>Option 5</span>
    </div>
  </div>
</div>
```

###### JavaScript

```js
    <script>
      const select = document.querySelectorAll('.select2')
      for (let i = 0; i < select.length; i++) {
        const div = select[i].querySelector('#div')
        const options = select[i].querySelector('#options')
        div.addEventListener("click", () => {
          div.classList.toggle("active")
          options.classList.toggle("display")
          select[i].classList.toggle("shadow")
        })
        const option = options.querySelectorAll('div')
        for (let i = 0; i < option.length; i++) {
          option[i].addEventListener("click", () => {
            div.querySelector("span").innerHTML= option[i].innerHTML
            console.log(option[i].innerHTML)
          })
        }
      }
    </script>
```
