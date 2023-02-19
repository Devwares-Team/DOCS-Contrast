---

title: 'Tab'
metaTitle: 'Bootstrap 5 Tab'
metaDescription: 'Bootstrap 5 Tabs are components that divide content that is wrapped in the same wrapper but displayed in a distinct pane. At any given time, only one pane can be seen.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/navigation/tabs.md"
---
# Bootstrap 5 Tab

Bootstrap 5 Tabs are components that divide content that is wrapped in the same wrapper but displayed in a distinct pane. At any given time, only one pane can be seen.

Bootstrap tabs are components that divide content that is wrapped in the same wrapper but displayed in a distinct pane. At any given time, only one pane can be seen. The element with `nav` class manages the active and disabled states in CDB tabs, as well as the overall markup and styles.

<i/>

## Default Tab

<Tabs1/>

###### HTML

```html
<ul class="nav nav-tabs mb-3" id="ex1" role="tablist">
  <li class="nav-item" role="presentation">
    <a
      class="nav-link active"
      id="ex1-tab-1"
      data-toggle="tab"
      href="#ex1-tabs-1"
      role="tab"
      aria-controls="ex1-tabs-1"
      aria-selected="true"
      >Tab 1</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="ex1-tab-2"
      data-toggle="tab"
      href="#ex1-tabs-2"
      role="tab"
      aria-controls="ex1-tabs-2"
      aria-selected="false"
      >Tab 2</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="ex1-tab-3"
      data-toggle="tab"
      href="#ex1-tabs-3"
      role="tab"
      aria-controls="ex1-tabs-3"
      aria-selected="false"
      >Tab 3</a
    >
  </li>
</ul>
<div class="tab-content" id="ex1-content">
  <div
    class="tab-pane fade show active"
    id="ex1-tabs-1"
    role="tabpanel"
    aria-labelledby="ex1-tab-1"
  >
    Tab 1 content
  </div>
  <div class="tab-pane fade" id="ex1-tabs-2" role="tabpanel" aria-labelledby="ex1-tab-2">
    Tab 2 content
  </div>
  <div class="tab-pane fade" id="ex1-tabs-3" role="tabpanel" aria-labelledby="ex1-tab-3">
    Tab 3 content
  </div>
</div>
```

## Justified Tab 

<Tabs2/>

###### HTML

```html
<ul class="nav nav-tabs nav-justified mb-3" id="ex1" role="tablist">
  <li class="nav-item" role="presentation">
    <a
      class="nav-link active"
      id="ex3-tab-1"
      data-toggle="tab"
      href="#ex3-tabs-1"
      role="tab"
      aria-controls="ex3-tabs-1"
      aria-selected="true"
      >Link</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="ex3-tab-2"
      data-toggle="tab"
      href="#ex3-tabs-2"
      role="tab"
      aria-controls="ex3-tabs-2"
      aria-selected="false"
      >Very very very very long link</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="ex3-tab-3"
      data-toggle="tab"
      href="#ex3-tabs-3"
      role="tab"
      aria-controls="ex3-tabs-3"
      aria-selected="false"
      >Another link</a
    >
  </li>
</ul>

<div class="tab-content" id="ex2-content">
  <div
    class="tab-pane fade show active"
    id="ex3-tabs-1"
    role="tabpanel"
    aria-labelledby="ex3-tab-1"
  >
    Tab 1 content Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptates, doloremque
    minima mollitia sapiente illo ut harum fugit explicabo error perspiciatis at cumque nisi eaque
    commodi culpa est sed ad amet.
  </div>
  <div class="tab-pane fade" id="ex3-tabs-2" role="tabpanel" aria-labelledby="ex3-tab-2">
    Tab 2 content Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptates, doloremque
    minima mollitia sapiente illo ut harum fugit explicabo error perspiciatis at cumque nisi eaque
    commodi culpa est sed ad amet.
  </div>
  <div class="tab-pane fade" id="ex3-tabs-3" role="tabpanel" aria-labelledby="ex3-tab-3">
    Tab 3 content Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptates, doloremque
    minima mollitia sapiente illo ut harum fugit explicabo error perspiciatis at cumque nisi eaque
    commodi culpa est sed ad amet.
  </div>
</div>
```

## Filled Tabs

<Tabs3/>

###### HTML

```html
<ul class="nav nav-tabs nav-fill mb-3" id="ex1" role="tablist">
  <li class="nav-item" role="presentation">
    <a
      class="nav-link active"
      id="ex2-tab-1"
      data-toggle="tab"
      href="#ex2-tabs-1"
      role="tab"
      aria-controls="ex2-tabs-1"
      aria-selected="true"
      >Link</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="ex2-tab-2"
      data-toggle="tab"
      href="#ex2-tabs-2"
      role="tab"
      aria-controls="ex2-tabs-2"
      aria-selected="false"
      >Very very very very long link</a
    >
  </li>
  <li class="nav-item" role="presentation">
    <a
      class="nav-link"
      id="ex2-tab-3"
      data-toggle="tab"
      href="#ex2-tabs-3"
      role="tab"
      aria-controls="ex2-tabs-3"
      aria-selected="false"
      >Another link</a
    >
  </li>
</ul>
<div class="tab-content" id="ex2-content">
  <div
    class="tab-pane fade show active"
    id="ex2-tabs-1"
    role="tabpanel"
    aria-labelledby="ex2-tab-1"
  >
    Tab 1 content
  </div>
  <div class="tab-pane fade" id="ex2-tabs-2" role="tabpanel" aria-labelledby="ex2-tab-2">
    Tab 2 content
  </div>
  <div class="tab-pane fade" id="ex2-tabs-3" role="tabpanel" aria-labelledby="ex2-tab-3">
    Tab 3 content
  </div>
</div>
```

## Vertical Tabs

<Tabs4/>

###### HTML

```html
<div class="row">
  <div class="col-3">
    <div
      class="nav flex-column nav-tabs text-center"
      id="v-tabs-tab"
      role="tablist"
      aria-orientation="vertical"
    >
      <a
        class="nav-link active"
        id="v-tabs-home-tab"
        data-toggle="tab"
        href="#v-tabs-home"
        role="tab"
        aria-controls="v-tabs-home"
        aria-selected="true"
        >Home</a
      >
      <a
        class="nav-link"
        id="v-tabs-profile-tab"
        data-toggle="tab"
        href="#v-tabs-profile"
        role="tab"
        aria-controls="v-tabs-profile"
        aria-selected="false"
        >Profile</a
      >
      <a
        class="nav-link"
        id="v-tabs-messages-tab"
        data-toggle="tab"
        href="#v-tabs-messages"
        role="tab"
        aria-controls="v-tabs-messages"
        aria-selected="false"
        >Messages</a
      >
    </div>
  </div>

  <div class="col-9">
    <div class="tab-content" id="v-tabs-tabContent">
      <div
        class="tab-pane fade show active"
        id="v-tabs-home"
        role="tabpanel"
        aria-labelledby="v-tabs-home-tab"
      >
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptates, doloremque minima
        mollitia sapiente illo ut harum fugit explicabo error perspiciatis at cumque nisi eaque
        commodi culpa est sed ad amet.
      </div>
      <div
        class="tab-pane fade"
        id="v-tabs-profile"
        role="tabpanel"
        aria-labelledby="v-tabs-profile-tab"
      >
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptates, doloremque minima
        mollitia sapiente illo ut harum fugit explicabo error perspiciatis at cumque nisi eaque
        commodi culpa est sed ad amet.
      </div>
      <div
        class="tab-pane fade"
        id="v-tabs-messages"
        role="tabpanel"
        aria-labelledby="v-tabs-messages-tab"
      >
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptates, doloremque minima
        mollitia sapiente illo ut harum fugit explicabo error perspiciatis at cumque nisi eaque
        commodi culpa est sed ad amet.
      </div>
    </div>
  </div>
</div>
```
