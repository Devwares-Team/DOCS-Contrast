---
title: 'Input'
metaTitle: 'Bootstrap 5 Input - Bootstrap CSS tutorial '
metaDescription: 'Bootstrap 5 Input is a special field which is used in order to receive data from the user. '
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/input.md"
---
# Bootstrap 5 Input

Bootstrap 5 Input is a specific field that is used to collect data from the user. Mostly used in a variety of web-based forms. You have the option of using the material design version or the default bootstrap style.

## Default Input Types

Create an input field in your project by using the `input` element. Next, we utilize the `type` attribute to specify the sort of data we want to gather in the input field, which can range from text, emails, passwords, and checkboxes, among other things.


<inputExample1 />


```html

<div class="contrast-input">
  <input type="text" class="form-control" placeholder="Text" />
</div>
<div class="contrast-input">
  <input type="email" class="form-control" placeholder="Email" />
</div>

```

## Input Sizing

To specify how small or large you want your input field to be, give the parent `div` (the element holding the input field) a form class and apply the desired size code to it (sm for small, and lg for large).



<inputExample3 />


```html
          <div class="cs-form form-sm">
            <input type="email" class="form-control" />
            <label>Email</label>
          </div>
          <div class="cs-form">
            <input type="email" class="form-control" />
            <label class="">Email</label>
          </div>
        </div>
```

## Input with icons

To embed icons in your input fields, use the `i` element tag.

<inputExample4 />

```html
<div class="cs-form">
  <i class="fa fa-user prefix"></i>
  <input type="text" class="form-control" />
  <label>Username</label>
</div>
<div class="cs-form">
  <i class="fa fa-lock prefix"></i>
  <input type="password" class="form-control" />
  <label>Password</label>
</div>
```

