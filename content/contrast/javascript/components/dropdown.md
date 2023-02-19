---
title: 'Dropdown'
metaTitle: 'Bootstrap Dropdown - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 Dropdown is a toggleable menu embedding additional links or content.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/dropdown.md"
---

# Bootstrap 5 Dropdown

Dropdown in Bootstrap 5 is a toggleable menu that can contain additional links or content. You can create complex navigation and link classification with it.

Dropdowns are vital parts in more complex navigation systems because they allow you to place all of the most relevant links in our navigation bar (or other navigational components).

CDB dropdowns are not only highly functional, but they are also really appealing visually. When dropdown items are clicked, they generate certain distinctive Material Design effects such as shadows, vibrant hues, and attractive waves.

It's an intentional design decision that they're toggled by clicking rather than hovering. Why?

Because CDB is a "mobile first" framework, we avoid hovering over functional parts and interactions because it degrades the user experience of mobile device users.

The Bootstrap Contrast By modifying props and prop values, we can give our dropdown component several predefined styles.

## Dark Toggle Bar

<Dropdown1/>

###### HTML

```html
<div class="dropdown">
  <button
    class="btn btn-dark dropdown-toggle"
    type="button"
    id="dropdownMenuButton"
    data-toggle="dropdown"
    aria-haspopup="true"
    aria-expanded="false"
  >
    Dark Toggle Bar
  </button>
  <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
    <a class="dropdown-item" href="#">This is the toggle menu</a>
  </div>
</div>
```

## Primary Toggle Bar with Caret

<Dropdown2/>

###### HTML

```html
<div class="dropdown">
  <button
    class="btn btn-primary dropdown-toggle"
    type="button"
    id="dropdownMenuButton"
    data-toggle="dropdown"
    aria-haspopup="true"
    aria-expanded="false"
  >
    Primary Toggle Bar
  </button>
  <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
    <a class="dropdown-item" href="#">This is the toggle menu with caret</a>
  </div>
</div>
```

## Secondary Toggle Bar

<Dropdown3/>

###### HTML

```html
<div class="btn-group dropright">
  <button
    class="btn btn-secondary dropdown-toggle"
    type="button"
    id="dropdownMenuButton"
    data-toggle="dropdown"
    aria-haspopup="true"
    aria-expanded="false"
  >
    Secondary Toggle Bar as Nav
  </button>
  <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
    <a class="dropdown-item" href="#">This is the toggle menu to the right</a>
  </div>
</div>
```

## Danger Toggle Bar

<Dropdown4/>

###### HTML

```html
<div class="btn-group dropup">
  <button
    class="btn btn-danger dropdown-toggle"
    type="button"
    id="dropdownMenuButton"
    data-toggle="dropdown"
    aria-haspopup="true"
    aria-expanded="false"
  >
    Danger Toggle Bar
  </button>
  <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
    <a class="dropdown-item" href="#">This is the toggle menu to the top</a>
  </div>
</div>
```

## Success Toggle Bar

<Dropdown5/>

###### HTML

```html
<div class="btn-group dropleft">
  <button
    class="btn btn-success dropdown-toggle"
    type="button"
    id="dropdownMenuButton"
    data-toggle="dropdown"
    aria-haspopup="true"
    aria-expanded="false"
  >
    Success Toggle Bar
  </button>
  <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
    <a class="dropdown-item" href="#">This is the toggle menu to the left</a>
  </div>
</div>
```

## Large Dropdown

<Dropdown6/>

###### HTML

```html
<div class="container">
  <div class="dropdown">
    <button
      class="btn btn-light btn-lg dropdown-toggle"
      type="button"
      id="dropdownMenuButton"
      data-toggle="dropdown"
      aria-expanded="false"
    >
      Large Dark Toggle Bar
    </button>
    <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
      <li><span class="dropdown-item">This is the toggle menu to the right</span></li>
    </ul>
  </div>
</div>
```

## Small Dropdown

<Dropdown7/>

###### HTML

```html
<div class="container">
  <div class="dropdown dropright">
    <button
      class="btn btn-secondary btn-sm dropdown-toggle"
      type="button"
      id="dropdownMenuButton"
      data-toggle="dropdown"
      aria-expanded="false"
    >
      small secondary toggle bar
    </button>
    <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
      <li><span class="dropdown-item">cold place</span></li>
      <div class="dropdown-divider"></div>
      <li><span class="dropdown-item">First Item in Cold Place</span></li>
      <li><span class="dropdown-item">second</span></li>
      <li><span class="dropdown-item">second</span></li>
      <li><span class="dropdown-item">second</span></li>
      <li>
        <span class="dropdown-item"><a href="/docs/contrast/react/components/alert">Alert</a></span>
      </li>
    </ul>
  </div>
</div>
```

## Disabled Danger Toggle Bar

<Dropdown8/>

###### HTML

```html
<div class="container">
  <div class="dropdown">
    <button
      class="btn btn-danger dropdown-toggle"
      type="button"
      id="dropdownMenuButton"
      data-toggle="dropdown"
      aria-expanded="false"
    >
      Disabled Danger Toggle Bar
    </button>
  </div>
</div>
```

## Menu with Header

<Dropdown9/>

###### HTML

```html
<div class="container">
  <div class="dropdown">
    <button
      class="btn btn-secondary dropdown-toggle"
      type="button"
      id="dropdownMenuButton"
      data-toggle="dropdown"
      aria-expanded="false"
    >
      Dropdown
    </button>
    <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
      <li><span class="dropdown-header">Cold place</span></li>
      <li><span class="dropdown-item">First Item in Cold Place</span></li>
      <li><span class="dropdown-item">second</span></li>
      <li><span class="dropdown-item">second</span></li>
    </ul>
  </div>
</div>
```

## Menu with Divider

<Dropdown10/>

###### HTML

```html
<div class="container">
  <div class="dropdown dropleft">
    <button
      class="btn btn-warning text-dark dropdown-toggle"
      type="button"
      id="dropdownMenuButton"
      data-toggle="dropdown"
      aria-expanded="false"
    >
      Dropdown
    </button>
    <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
      <li>
        <span class="dropdown-item"><a href="/docs/contrast/react/components/alert">Alert</a></span>
      </li>
      <div class="dropdown-divider"></div>
      <li><span class="dropdown-item">First Item in Cold Place</span></li>
      <li><span class="dropdown-item">second</span></li>
      <li><span class="dropdown-item">second</span></li>
    </ul>
  </div>
</div>
```

## Disabled Menu Items

<Dropdown11/>

###### HTML

```html
<div class="container">
  <div class="dropdown dropup">
    <button
      class="btn btn-success dropdown-toggle"
      type="button"
      id="dropdownMenuButton"
      data-toggle="dropdown"
      aria-expanded="false"
    >
      Dropdown
    </button>
    <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
      <li><span class="dropdown-item">Cold place</span></li>
      <li><span class="dropdown-item disabled">Disabled</span></li>
      <li><span class="dropdown-item">Second</span></li>
      <li><span class="dropdown-item">Last</span></li>
    </ul>
  </div>
</div>
```

## Active Menu Items

<Dropdown12/>

###### HTML

```html
<div class="container">
  <div class="dropdown dropup">
    <button
      class="btn btn-dark dropdown-toggle"
      type="button"
      id="dropdownMenuButton"
      data-toggle="dropdown"
      aria-expanded="false"
    >
      Dropdown
    </button>
    <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
      <li><span class="dropdown-item">Cold place</span></li>
      <li><span class="dropdown-item active">Active</span></li>
      <li><span class="dropdown-item">Second</span></li>
      <li><span class="dropdown-item">Last</span></li>
    </ul>
  </div>
</div>
```
