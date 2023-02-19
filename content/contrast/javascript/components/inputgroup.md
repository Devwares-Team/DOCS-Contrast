---

title: 'InputGroup'
metaTitle: 'Bootstrap 5 InputGroup - Bootstrap CSS tutorial'
metaDescription: 'To capture user-entered data, the Bootstrap 5 Input group component is used.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/inputgroup.md"
---

# Bootstrap 5 InputGroup

To capture user-entered data, the Bootstrap 5 Input group component is used. It typically includes buttons, text fields, and other inputs. Your forms will be visually appealing and simple to customize using this component.

## Default InputGroup

This is the defualt InputGroup
<Inputgroup1/>

###### HTML

```html
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
```

## Basic input with appended text

<Inputgroup2/>

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
```
