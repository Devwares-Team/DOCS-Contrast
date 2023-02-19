---
title: 'Modal'
metaTitle: 'Bootstrap 5 Modal - Bootstrap CSS tutorial '
metaDescription: 'The Bootstrap 5 modal is a small but strong and multifunctional popup.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/modal.md"
---

# Bootstrap 5 Modal

The Bootstrap 5 modal is a lightweight yet powerful and multifunctional popup.

It is a dialog box or popup window that can be used for light boxes, user notifications, UI upgrades, e-commerce components, and a variety of other applications.

It is incredibly flexible, with the ability to simply change the size, position, and content to meet your design. It is efficient and uses simple syntax.

## Custom Modal

<Modal1/>

###### HTML

```html
<button type="button" class="btn btn-dark btn-flat" data-toggle="modal" data-target="#customModal1">
  Modal
</button>
<div
  class="modal fade"
  id="customModal1"
  tabindex="-1"
  role="dialog"
  aria-labelledby="exampleModalLabel"
  aria-hidden="true"
>
  <div class="modal-dialog">
    <div class="card-border card">
      <img style="width: 100%" src="../img/modal.jpg" />
      <div class="card-body">
        <div class="card-title">Title</div>
        <p class="card-text">
          Quisque a varius augue. Etiam volutpat ipsum nec mi porttitor, nec fermentum enim
          fermentum. Curabitur metus eros, scelerisque vel urna a, condimentum molestie mauris.
          Aliquam blandit congue risus ac sollicitudin. Proin tempus bibendum sem. Morbi pulvinar a
          metus sit amet ullamcorper.
        </p>
        <div class="d-flex">
          <div class="d-flex justify-content-start" style="flex: 50%">
            <button class="btn btn-dark btn-flat">Label</button>
          </div>
          <div class="d-flex justify-content-end" style="flex: 50%">
            <button class="btn btn-light btn-flat close" type="button" data-dismiss="modal">
              Cancel
            </button>
            <button class="btn btn-dark btn-flat">Done</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
```

## Modal Sizes

<Modal2/>

###### HTML

```html
<button
  type="button"
  class="btn btn-light btn-flat"
  data-toggle="modal"
  data-target="#customModal2"
>
  Small Modal
</button>
<div
  class="modal fade"
  id="customModal2"
  tabindex="-1"
  role="dialog"
  aria-labelledby="exampleModalLabel"
  aria-hidden="true"
>
  <div class="modal-dialog modal-sm">
    <div class="card">
      <div class="card-body">
        <div class="card-title">Title</div>
        <p class="card-text">
          Quisque a varius augue. Etiam volutpat ipsum nec mi porttitor, nec fermentum enim
          fermentum. Curabitur metus eros, scelerisque vel urna a, condimentum molestie mauris.
          Aliquam blandit congue risus ac sollicitudin. Proin tempus bibendum sem. Morbi pulvinar a
          metus sit amet ullamcorper.
        </p>
        <div class="d-flex">
          <div class="d-flex justify-content-start" style="flex: 50%">
            <button class="btn btn-dark btn-flat">Label</button>
          </div>
          <div class="d-flex justify-content-end" style="flex: 50%">
            <button class="btn btn-light btn-flat close" type="button" data-dismiss="modal">
              Cancel
            </button>
            <button class="btn btn-dark btn-flat">Done</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<button
  type="button"
  class="btn btn-light btn-flat"
  data-toggle="modal"
  data-target="#customModal3"
>
  Medium Modal
</button>
<div
  class="modal fade"
  id="customModal3"
  tabindex="-1"
  role="dialog"
  aria-labelledby="exampleModalLabel"
  aria-hidden="true"
>
  <div class="modal-dialog">
    <div class="card">
      <div class="card-body">
        <div class="card-title">Title</div>
        <p class="card-text">
          Quisque a varius augue. Etiam volutpat ipsum nec mi porttitor, nec fermentum enim
          fermentum. Curabitur metus eros, scelerisque vel urna a, condimentum molestie mauris.
          Aliquam blandit congue risus ac sollicitudin. Proin tempus bibendum sem. Morbi pulvinar a
          metus sit amet ullamcorper.
        </p>
        <div class="d-flex">
          <div class="d-flex justify-content-start" style="flex: 50%">
            <button class="btn btn-dark btn-flat">Label</button>
          </div>
          <div class="d-flex justify-content-end" style="flex: 50%">
            <button class="btn btn-light close" type="button" data-dismiss="modal">
              Cancel
            </button>
            <button class="btn btn-dark btn-flat">Done</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<button
  type="button"
  class="btn btn-light btn-flat"
  data-toggle="modal"
  data-target="#customModal4"
>
  Large Modal
</button>
<div
  class="modal fade"
  id="customModal4"
  tabindex="-1"
  role="dialog"
  aria-labelledby="exampleModalLabel"
  aria-hidden="true"
>
  <div class="modal-dialog modal-lg">
    <div class="card">
      <div class="card-body">
        <div class="card-title">Title</div>
        <p class="card-text">
          Quisque a varius augue. Etiam volutpat ipsum nec mi porttitor, nec fermentum enim
          fermentum. Curabitur metus eros, scelerisque vel urna a, condimentum molestie mauris.
          Aliquam blandit congue risus ac sollicitudin. Proin tempus bibendum sem. Morbi pulvinar a
          metus sit amet ullamcorper.
        </p>
        <div class="d-flex">
          <div class="d-flex justify-content-start" style="flex: 50%">
            <button class="btn btn-dark btn-flat">Label</button>
          </div>
          <div class="d-flex justify-content-end" style="flex: 50%">
            <button class="btn btn-light btn-flat close" type="button" data-dismiss="modal">
              Cancel
            </button>
            <button class="btn btn-dark btn-flat">Done</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<button
  type="button"
  class="btn btn-light btn-flat"
  data-toggle="modal"
  data-target="#customModal5"
>
  Fluid Modal
</button>
<div
  class="modal fade"
  id="customModal5"
  tabindex="-1"
  role="dialog"
  aria-labelledby="exampleModalLabel"
  aria-hidden="true"
>
  <div class="modal-dialog modal-fluid">
    <div class="card">
      <div class="card-body">
        <div class="card-title">Title</div>
        <p class="card-text">
          Quisque a varius augue. Etiam volutpat ipsum nec mi porttitor, nec fermentum enim
          fermentum. Curabitur metus eros, scelerisque vel urna a, condimentum molestie mauris.
          Aliquam blandit congue risus ac sollicitudin. Proin tempus bibendum sem. Morbi pulvinar a
          metus sit amet ullamcorper.
        </p>
        <div class="d-flex">
          <div class="d-flex justify-content-start" style="flex: 50%">
            <button class="btn btn-light btn-flat">Label</button>
          </div>
          <div class="d-flex justify-content-end" style="flex: 50%">
            <button class="btn btn-light btn-flat close" type="button" data-dismiss="modal">
              Cancel
            </button>
            <button class="btn btn-dark btn-flat">Done</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
```

## Modal Positions

<Modal3/>

###### HTML

```html
<div class="blockcode">
  <div class="header">Modal Positions</div>
  <div class="example">
    <button
      type="button"
      class="btn btn-light btn-flat"
      data-toggle="modal"
      data-target="#customModal11"
    >
      Top Left Modal
    </button>
    <div
      class="modal fade"
      id="customModal11"
      tabindex="-1"
      role="dialog"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog modal-top-left">
        <div class="card">
          <div class="card-body">
            <div class="card-title">Title</div>
            <p class="card-text">
              Quisque a varius augue. Etiam volutpat ipsum nec mi porttitor, nec fermentum enim
              fermentum. Curabitur metus eros, scelerisque vel urna a, condimentum molestie mauris.
              Aliquam blandit congue risus ac sollicitudin. Proin tempus bibendum sem. Morbi
              pulvinar a metus sit amet ullamcorper.
            </p>
            <div class="d-flex">
              <div class="d-flex justify-content-start" style="flex: 50%">
                <button class="btn btn-dark btn-flat">Label</button>
              </div>
              <div class="d-flex justify-content-end" style="flex: 50%">
                <button class="btn btn-light btn-flat close" type="button" data-dismiss="modal">
                  Cancel
                </button>
                <button class="btn btn-dark btn-flat">Done</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <button
      type="button"
      class="btn btn-light btn-flat"
      data-toggle="modal"
      data-target="#customModal12"
    >
      Top Right Modal
    </button>
    <div
      class="modal fade"
      id="customModal12"
      tabindex="-1"
      role="dialog"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog modal-top-right">
        <div class="card">
          <div class="card-body">
            <div class="card-title">Title</div>
            <p class="card-text">
              Quisque a varius augue. Etiam volutpat ipsum nec mi porttitor, nec fermentum enim
              fermentum. Curabitur metus eros, scelerisque vel urna a, condimentum molestie mauris.
              Aliquam blandit congue risus ac sollicitudin. Proin tempus bibendum sem. Morbi
              pulvinar a metus sit amet ullamcorper.
            </p>
            <div class="d-flex">
              <div class="d-flex justify-content-start" style="flex: 50%">
                <button class="btn btn-dark btn-flat">Label</button>
              </div>
              <div class="d-flex justify-content-end" style="flex: 50%">
                <button class="btn btn-light close" type="button" data-dismiss="modal">
                  Cancel
                </button>
                <button class="btn btn-dark btn-flat">Done</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <button
      type="button"
      class="btn btn-light btn-flat"
      data-toggle="modal"
      data-target="#customModal13"
    >
      Bottom Left Modal
    </button>
    <div
      class="modal fade"
      id="customModal13"
      tabindex="-1"
      role="dialog"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog modal-bottom-left">
        <div class="card">
          <div class="card-body">
            <div class="card-title">Title</div>
            <p class="card-text">
              Quisque a varius augue. Etiam volutpat ipsum nec mi porttitor, nec fermentum enim
              fermentum. Curabitur metus eros, scelerisque vel urna a, condimentum molestie mauris.
              Aliquam blandit congue risus ac sollicitudin. Proin tempus bibendum sem. Morbi
              pulvinar a metus sit amet ullamcorper.
            </p>
            <div class="d-flex">
              <div class="d-flex justify-content-start" style="flex: 50%">
                <button class="btn btn-dark btn-flat">Label</button>
              </div>
              <div class="d-flex justify-content-end" style="flex: 50%">
                <button class="btn btn-light btn-flat close" type="button" data-dismiss="modal">
                  Cancel
                </button>
                <button class="btn btn-dark btn-flat">Done</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <button
      type="button"
      class="btn btn-light btn-flat"
      data-toggle="modal"
      data-target="#customModal14"
    >
      Bottom Right Modal
    </button>
    <div
      class="modal fade"
      id="customModal14"
      tabindex="-1"
      role="dialog"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog modal-bottom-right">
        <div class="card">
          <div class="card-body">
            <div class="card-title">Title</div>
            <p class="card-text">
              Quisque a varius augue. Etiam volutpat ipsum nec mi porttitor, nec fermentum enim
              fermentum. Curabitur metus eros, scelerisque vel urna a, condimentum molestie mauris.
              Aliquam blandit congue risus ac sollicitudin. Proin tempus bibendum sem. Morbi
              pulvinar a metus sit amet ullamcorper.
            </p>
            <div class="d-flex">
              <div class="d-flex justify-content-start" style="flex: 50%">
                <button class="btn btn-light btn-flat">Label</button>
              </div>
              <div class="d-flex justify-content-end" style="flex: 50%">
                <button class="btn btn-light btn-flat close" type="button" data-dismiss="modal">
                  Cancel
                </button>
                <button class="btn btn-dark btn-flat">Done</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <button
      type="button"
      class="btn btn-light btn-flat"
      data-toggle="modal"
      data-target="#customModal15"
    >
      Center Modal
    </button>
    <div
      class="modal fade"
      id="customModal15"
      tabindex="-1"
      role="dialog"
      aria-labelledby="exampleModalLabel"
      aria-hidden="true"
    >
      <div class="modal-dialog modal-center">
        <div class="card">
          <div class="card-body">
            <div class="card-title">Title</div>
            <p class="card-text">
              Quisque a varius augue. Etiam volutpat ipsum nec mi porttitor, nec fermentum enim
              fermentum. Curabitur metus eros, scelerisque vel urna a, condimentum molestie mauris.
              Aliquam blandit congue risus ac sollicitudin. Proin tempus bibendum sem. Morbi
              pulvinar a metus sit amet ullamcorper.
            </p>
            <div class="d-flex">
              <div class="d-flex justify-content-start" style="flex: 50%">
                <button class="btn btn-light btn-flat">Label</button>
              </div>
              <div class="d-flex justify-content-end" style="flex: 50%">
                <button class="btn btn-light btn-flat close" type="button" data-dismiss="modal">
                  Cancel
                </button>
                <button class="btn btn-dark btn-flat">Done</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
```

###### JavaScript

```js
   <script type="text/javascript" src="../js/jquery.min.js"></script>
    <script
      type="text/javascript"
      src="../js/bootstrap.bundle.min.js"
      defer
    ></script>
    <script type="text/javascript" src="../js/popper.min.js"></script>
```

You can check out how to build a modal using Contrast Bootstrap [here](https://www.devwares.com/blog/how-to-create-a-bootstrap5-modal/)
