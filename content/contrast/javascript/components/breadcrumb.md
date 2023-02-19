---
title: 'Breadcrumb'
metaTitle: 'Bootstrap 5 Breadcrumb - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 Breadcrumb is a component that indicates to users where they are on a website or in a Web application.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/breadcrumb.md"
---

# Bootstrap 5 Breadcrumb

Bootstrap 5 Breadcrumb is a component that indicates to users where they are on a website or a web application. It's a navigational component that allows website visitors or web application users to track their current location and previous navigated page(s).

The breadcrumb Bootstrap navigation system follows a standard format. Each item in the navigation system is preceded by a chevron character and is followed by a forward slash. Each item in the navigation is also linked so that users can easily go back to the previous page.

## Navigation Breadcrumb

<Breadcrumb1/>

###### HTML

```html
<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item active">Home</li>
  </ol>
</nav>

<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item text-primary">Home</li>
    <li class="breadcrumb-item active" aria-current="page">Library</li>
  </ol>
</nav>

<nav aria-label="breadcrumb">
  <ol class="breadcrumb breadcrumb-flat">
    <li class="breadcrumb-item">Home</li>
    <li class="breadcrumb-item">Library</li>
    <li class="breadcrumb-item active" aria-current="page">Data</li>
  </ol>
</nav>
```

The breadcrumb bootstrap system is essential in any application or website a user visits.
