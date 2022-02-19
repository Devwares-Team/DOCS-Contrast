---
title: 'Input'
metaTitle: 'Bootstrap 5 Input - Bootstrap CSS tutorial '
metaDescription: 'Bootstrap 5 Input is a special field which is used in order to receive data from the user. '
---# Bootstrap 5 Input

Bootstrap 5 Input is a specific field that is used to collect data from the user. Mostly used in a variety of web-based forms. You have the option of using the material design version or the default bootstrap style.

## Default Input Types

Create an input field in your project by using the `input` element. Next, we utilize the `type` attribute to specify the sort of data we want to gather in the input field, which can range from text, emails, passwords, and checkboxes, among other things.

![Bootstrap Input Default](./images/input1.png)

###### html

```html
<div class="cs-form">
  <input type="text" class="form-control" />
  <label>Email</label>
</div>
<div class="cs-form">
  <input type="number" class="form-control" />
  <label class="">Number</label>
</div>
<div class="cs-form">
  <textarea class="form-control"></textarea>
  <label>TextArea</label>
</div>
<div class="form-check">
  <input class="form-check-input" type="checkbox" value="" id="defaultCheck" />
  <label class="form-check-label" for="defaultCheck">
    checkbox1
  </label>
</div>
```

## Input Sizing

To specify how small or large you want your input field to be, give the parent `div` (the element holding the input field) a form class and apply the desired size code to it (sm for small, and lg for large).

![Bootstrap Input With Sizing](./images/inputsizing.png)

###### html

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

![Bootstrap Input With Icons](./images/inputwithicons.png)

###### html

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

## Input with Different Styling

The Contrast Bootstrap comes with preconfigured styling out of the box. To modify the text colors of your input field labels, add a text class to the labels and append the color code of the desired color. For example `<label class="text-info">Username</label>`.

To alter the border color of your inputs, use the border class and append the color code of their choice. For example `<input type="text" class="form-control border-info" />`

![Bootstrap Input With Different Styling](./images/inputwithmd.png)

###### html

```html
<div class="cs-form">
  <input type="text" class="form-control border-info" />
  <label class="text-info">Username</label>
</div>
<div class="cs-form">
  <input type="password" class="form-control border-warning" />
  <label class="text-warning">Password</label>
</div>
<div class="cs-form">
  <input
    type="password"
    class="form-control border-success border-top-0 border-left-0 border-right-0"
  />
  <label class="text-success">Password</label>
</div>
```

## Placeholder

Use the `placeholder` attribute to inform users about the data that should be entered into the input forms.

![Bootstrap Input with Placeholder](./images/inputplaceholder.png)

###### html

```html
<div class="cs-form">
  <input type="text" class="form-control" placeholder="Username" />
</div>
<div class="cs-form">
  <input type="password" class="form-control" placeholder="Email" />
</div>
```
