---
title: 'InputGroup'
metaTitle: 'Bootstrap 5 InputGroup - Bootstrap CSS tutorial'
metaDescription: 'To capture user-entered data, the Bootstrap 5 Input group component is used.'
---# Bootstrap 5 InputGroup

To capture user-entered data, the Bootstrap 5 Input group component is used. It typically includes buttons, text fields, and other inputs. Your forms will be visually appealing and simple to customize using this component.

## Default InputGroup

This is the defualt InputGroup

![Bootstrap InputGroup Default](./images/inputgroup1.png)

###### html

```html
<div class="input-group mb-3">
  <div class="input-group-prepend">
    <span class="input-group-text" id="basic-addon1">@</span>
  </div>
  <input
    type="text"
    class="form-control"
    placeholder="Username"
    aria-label="Username"
    aria-describedby="basic-addon1"
  />
</div>

<div class="input-group mb-3">
  <input
    type="text"
    class="form-control"
    placeholder="Recipient's username"
    aria-label="Recipient's username"
    aria-describedby="basic-addon2"
  />
  <div class="input-group-append">
    <span class="input-group-text" id="basic-addon2">@example.com</span>
  </div>
</div>
<label for="basic-url">Your vanity URL</label>
<div class="input-group mb-3">
  <div class="input-group-prepend">
    <span class="input-group-text" id="basic-addon3">https://example.com/users/</span>
  </div>
  <input type="text" class="form-control" id="basic-url" aria-describedby="basic-addon3" />
</div>

<div class="input-group mb-3">
  <div class="input-group-prepend">
    <span class="input-group-text">$</span>
  </div>
  <input type="text" class="form-control" aria-label="Amount (to the nearest dollar)" />
  <div class="input-group-append">
    <span class="input-group-text">.00</span>
  </div>
</div>

<div class="input-group">
  <div class="input-group-prepend">
    <span class="input-group-text">With textarea</span>
  </div>
  <textarea class="form-control" aria-label="With textarea"></textarea>
</div>
```

## Basic input with appended text

![Bootstrap InputGroup with appended text](./images/inputgroup2.png)

###### html

```html
<div class="input-group input-group-sm mb-3">
  <div class="input-group-prepend">
    <span class="input-group-text" id="inputGroup-sizing-sm">Small</span>
  </div>
  <input
    type="text"
    class="form-control"
    aria-label="Small"
    aria-describedby="inputGroup-sizing-sm"
  />
</div>

<div class="input-group mb-3">
  <div class="input-group-prepend">
    <span class="input-group-text" id="inputGroup-sizing-default">Default</span>
  </div>
  <input
    type="text"
    class="form-control"
    aria-label="Default"
    aria-describedby="inputGroup-sizing-default"
  />
</div>

<div class="input-group input-group-lg">
  <div class="input-group-prepend">
    <span class="input-group-text" id="inputGroup-sizing-lg">Large</span>
  </div>
  <input
    type="text"
    class="form-control"
    aria-label="Large"
    aria-describedby="inputGroup-sizing-sm"
  />
</div>
```
