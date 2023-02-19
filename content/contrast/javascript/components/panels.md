---

title: 'Panel'
metaTitle: 'Bootstrap 5 Panels - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 Panels are content containers that are flexible and expandable, allowing for a wide range of content, contextual backdrop colors, and elegant display choice.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/panels.md"
---
# Bootstrap 5 Panel

Bootstrap 5 Panels are content containers that are flexible and expandable, allowing a wide range of content, contextual backdrop colors, and elegant display choices. Panels are like cards, however they don't have any media.

<i/>

## Panel with Dropdown

The `panel` class allows us to have the Contrast Bootstrap 5 Panel predefined styles in your project. We also use the Contrast Bootstrap Dropdown in our Panel example below, visit [here](https://www.devwares.com/docs/contrast/javascript/components/dropdown) for more information on contrast dropdowns.

<Panels1/>

###### HTML

```html
<div class="panel" style="width: 25rem">
  <div class="panel-body">
    <div class="pane d-flex align-items-center mt-0 mb-3">
      <img
        class="pane-img"
        src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170"
        alt=""
      />
      <div class="ml-3">
        <h6 class="m-0" style="font-weight:600;">Warren Briggs</h6>
        <p class="m-0 pane-item">Cooking</p>
      </div>

      <div class="dropdown p-0 ml-auto pane-item">
        <i
          class="fa fa-ellipsis-h display-1"
          id="dropdownMenuButton"
          data-toggle="dropdown"
          aria-expanded="false"
        >
        </i>
        <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
          <li><a class="dropdown-item" href="#">Action</a></li>
          <li><a class="dropdown-item" href="#">Another action</a></li>
          <li><a class="dropdown-item" href="#">Something else here</a></li>
        </ul>
      </div>
    </div>

    <div class="card-text">
      Nullam feugiat est sed leo efficitur accumsan. Aenean rutrum, nisl ac ultricies efficitur,
      nunc lacus venenatis dui, eget ultrices odio libero et libero. Maecenas erat elit, scelerisque
      nec est nec, consequat varius
    </div>
  </div>
</div>
```

## Panel with Users

We use other classes to define the different parts of the panel, the `panel-title` for writing out the titles in your panel, `panel-text` for text, and `panel-img` for holding images in your panel.

<Panels2/>

###### HTML

```html
<div class="panel" style="width: 25rem">
  <div class="panel-img">
    <img src="https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__340.jpg" alt="" />
  </div>
  <div class="panel-body">
    <div class="panel-title ">
      Bristol
    </div>
    <div class="panel-text">
      Nullam feugiat est sed leo efficitur accumsan. Aenean rutrum, nisl ac ultricies efficitur,
      nunc lacus venenatis dui, eget ultrices odio libero et libero. Maecenas erat elit, scelerisque
      nec est nec, consequat varius
    </div>
    <img
      class="pane-img"
      src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170"
    />
    <img
      class="pane-img"
      src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQ7ntUU7AzmOxa5HB8zS83sa-JFHEfZJAoI2A&usqp=CAU"
    />
    <img
      class="pane-img"
      src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQ7ntUU7AzmOxa5HB8zS83sa-JFHEfZJAoI2A&usqp=CAU"
    />
  </div>
</div>
```

## Panel with Label

In this section of the tutorial we also use the Contrast Bootstrap Badge alongside the bootstrap panel, to understand the Bootstrap badge and how to use it in your project, go to [here](https://www.devwares.com/docs/contrast/javascript/components/badge).

<Panels3/>

###### HTML

```html
<div class="panel" style="width: 25rem">
  <div class="panel-body">
    <div class="panel-label">
      <div class="badge badge-flat bg-secondary">Label 1</div>
      <div class="badge badge-flat bg-warning">Label 2</div>
      <div class="badge badge-flat bg-danger">Label 3</div>
    </div>
    <div class="panel-title ">
      Moon Fever
    </div>
    <div class="panel-text">
      Nullam feugiat est sed leo efficitur accumsan. Aenean rutrum, nisl ac ultricies efficitur,
      nunc lacus venenatis dui, eget ultrices odio libero et libero. Maecenas erat elit, scelerisque
      nec est nec, consequat varius
    </div>
    <img
      class="pane-img"
      src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170"
    />
    <img
      class="pane-img"
      src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQ7ntUU7AzmOxa5HB8zS83sa-JFHEfZJAoI2A&usqp=CAU"
    />
  </div>
</div>
```

## Pane List

<Panels4/>

###### HTML

```html
<div class="panel" style="width: 25rem">
  <div class="panel-body">
    <div class="d-flex justify-content-between align-item-center mb-1">
      <p class="mb-0">My Messages</p>
      <div class="dropdown p-0">
        <i
          class="fa fa-ellipsis-h display-1"
          id="dropdownMenuButton"
          data-toggle="dropdown"
          aria-expanded="false"
        >
        </i>
        <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
          <li><a class="dropdown-item" href="#">Action</a></li>
          <li><a class="dropdown-item" href="#">Another action</a></li>
          <li><a class="dropdown-item" href="#">Something else here</a></li>
        </ul>
      </div>
    </div>

    <div class="pane d-flex align-items-center">
      <img
        class="pane-img"
        src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170"
        alt=""
      />
      <div class="ml-3">
        <h6 class="m-0" style="font-weight:600;">Warren Briggs</h6>
        <p class="m-0 pane-item">Cooking</p>
      </div>
      <p class="ml-auto pane-item">5mins Ago</p>
    </div>

    <div class="pane d-flex align-items-center">
      <img
        class="pane-img"
        src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170"
        alt=""
      />
      <div class="ml-3">
        <h6 class="m-0" style="font-weight:600;">Warren Briggs</h6>
        <p class="m-0 pane-item">Cooking</p>
      </div>
      <p class="ml-auto pane-item">5mins Ago</p>
    </div>

    <div class="pane d-flex align-items-center">
      <img
        class="pane-img"
        src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170"
        alt=""
      />
      <div class="ml-3">
        <h6 class="m-0" style="font-weight:600;">Warren Briggs</h6>
        <p class="m-0 pane-item">Cooking</p>
      </div>
      <p class="ml-auto pane-item">5mins Ago</p>
    </div>

    <div class="pane d-flex align-items-center">
      <img
        class="pane-img"
        src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170"
        alt=""
      />
      <div class="ml-3">
        <h6 class="m-0" style="font-weight:600;">Warren Briggs</h6>
        <p class="m-0 pane-item">Cooking</p>
      </div>
      <p class="ml-auto pane-item">5mins Ago</p>
    </div>

    <div class="pane d-flex align-items-center">
      <img
        class="pane-img"
        src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170"
        alt=""
      />
      <div class="ml-3">
        <h6 class="m-0" style="font-weight:600;">Warren Briggs</h6>
        <p class="m-0 pane-item">Cooking</p>
      </div>
      <p class="ml-auto pane-item">5mins Ago</p>
    </div>
  </div>
</div>
```


## Panel with Progress

We also use the Contrast Bootstrap Progress in our Panel example below, visit [here](https://www.devwares.com/docs/contrast/javascript/components/progress) for more information on contrast dropdowns.

<Panels5/>

###### HTML

```html
<div class="panel" style="width: 25rem">
  <div class="panel-body">
    <div class="pane d-flex align-items-center mt-0">
      <img
        class="pane-img"
        src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170"
        alt=""
      />
      <div class="ml-3">
        <h6 class="m-0" style="font-weight:600;">Warren Briggs</h6>
        <p class="m-0 pane-item">Cooking</p>
      </div>
      <p class="ml-auto pane-item">5mins Ago</p>
    </div>

    <div class="progress-container">
      <div class="progress-text pane-item">Instagram</div>
      <div class="progress progress-primary" role="progress" min="0" max="100" value="20">
        <div class="progress-bar"></div>
      </div>
    </div>

    <div class="progress-container">
      <div class="progress-text progress-text-secondary">Twitter</div>
      <div class="progress progress-secondary" role="progress" min="0" max="100" value="30">
        <div class="progress-bar"></div>
      </div>
    </div>

    <div class="progress-container">
      <div class="progress-text progress-text-danger">Facebook</div>
      <div class="progress progress-danger" role="progress" min="0" max="100" value="80">
        <div class="progress-bar"></div>
      </div>
    </div>
  </div>
</div>
```
