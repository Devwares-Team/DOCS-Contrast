---
title: 'Notification'
metaTitle: 'Bootstrap 5 Notifications - Bootstrap CSS tutorial'
metaDescription: 'With a toast, a lightweight and easily customized alert message, Bootstrap 5 notifications is used to send information to your visitors.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/notification.md"
---

# Bootstrap 5 Notification

With a toast, a lightweight and easily customized alert message, Bootstrap 5 notifications is used to send information to your visitors.

Toasts are little notifications that are meant to look like the push notifications that have become popular on mobile and desktop platforms. Because they're made with flexbox, they're simple to align and place.

<i/>

## Custom Notification Types

<Notification1 />

###### HTML

```html
<div class="notification mb-3" id="dismiss1">
  <div class="notification-header">
    <div class="icon-box"><i class="fa fa-square"></i></div>
    <div class="d-flex flex-column">
      <strong class="ml-3">Contrast</strong>
      <small class="ml-3 small-text">11 mins ago</small>
    </div>
    <button type="button" class="btn p-0 ml-auto h-25">
      <button class="btn-close btn-close1" data-dismiss="toast"></button>
    </button>
    <div class="toggle">
      <span
        data-toggle="collapse"
        data-target="#collapseOne"
        aria-expanded="true"
        aria-controls="collapseOne"
      ></span>
    </div>
  </div>
  <div class="notification-message" id="collapseOne">
    Hello, world! This is a dismissible message.
  </div>
</div>

<div class="notification" id="dismiss2">
  <div class="notification-header">
    <div class="icon-box"><i class="fa fa-square"></i></div>
    <div class="d-flex flex-column">
      <strong class="ml-3">Contrast</strong>
      <small class="ml-3 small-text">11 mins ago</small>
    </div>
    <button type="button" class="btn p-0 ml-auto h-25">
      <button class="btn-close" data-dismiss="toast"></button>
    </button>
    <div class="toggle">
      <span
        data-toggle="collapse"
        data-target="#collapseOne"
        aria-expanded="true"
        aria-controls="collapseOne"
      ></span>
    </div>
  </div>
  <div class="notification-message" id="collapseOne">
    Hello, world! This message will dissapear in 5 seconds.
  </div>
</div>
```

## Icon Box Color

<Notification2/>

###### HTML

```html
<div class="notification mb-3">
  <div class="notification-header">
    <div class="icon-box bg-info">
      <i class="fa fa-square text-white"></i>
    </div>
    <div class="d-flex flex-column">
      <strong class="ml-3">Contrast</strong>
      <small class="ml-3 small-text">11 mins ago</small>
    </div>
    <button type="button" class="btn p-0 ml-auto h-25">
      <button class="btn-close" data-dismiss="toast"></button>
    </button>
    <div class="toggle">
      <span
        data-toggle="collapse"
        data-target="#collapseTwo"
        aria-expanded="true"
        aria-controls="collapseTwo"
      ></span>
    </div>
  </div>
  <div class="notification-message" id="collapseTwo">
    Hello, world! This is a primary message.
  </div>
</div>

<div class="notification mb-3">
  <div class="notification-header">
    <div class="icon-box bg-danger">
      <i class="fa fa-square text-white"></i>
    </div>
    <div class="d-flex flex-column">
      <strong class="ml-3">Contrast</strong>
      <small class="ml-3 small-text">11 mins ago</small>
    </div>
    <button type="button" class="btn p-0 ml-auto h-25">
      <button class="btn-close" data-dismiss="toast"></button>
    </button>
    <div class="toggle">
      <span
        data-toggle="collapse"
        data-target="#collapseThree"
        aria-expanded="true"
        aria-controls="collapseThree"
      ></span>
    </div>
  </div>
  <div class="notification-message" id="collapseThree">
    Hello, world! This is a primary message.
  </div>
</div>

<div class="notification mb-3">
  <div class="notification-header">
    <div class="icon-box bg-secondary">
      <i class="fa fa-square text-white"></i>
    </div>
    <div class="d-flex flex-column">
      <strong class="ml-3">Contrast</strong>
      <small class="ml-3 small-text">11 mins ago</small>
    </div>
    <button type="button" class="btn p-0 ml-auto h-25">
      <button class="btn-close" data-dismiss="toast"></button>
    </button>
    <div class="toggle">
      <span
        data-toggle="collapse"
        data-target="#collapseFour"
        aria-expanded="true"
        aria-controls="collapseFour"
      ></span>
    </div>
  </div>
  <div class="notification-message" id="collapseFour">
    Hello, world! This is a primary message.
  </div>
</div>
```

## Notification with Icons

<Notification3/>

###### HTML

```html
<div class="notification mb-3">
  <div class="notification-header">
    <div class="icon-box bg-dark">
      <i class="fa fa-cut text-white"></i>
    </div>
    <div class="d-flex flex-column">
      <strong class="ml-3">Contrast</strong>
      <small class="ml-3 small-text">11 mins ago</small>
    </div>
    <button type="button" class="btn p-0 ml-auto h-25">
      <button class="btn-close" data-dismiss="toast"></button>
    </button>
    <div class="toggle">
      <span
        data-toggle="collapse"
        data-target="#collapseFive"
        aria-expanded="true"
        aria-controls="collapseFive"
      ></span>
    </div>
  </div>
  <div class="notification-message" id="collapseFive">
    Hello, world! This is a primary message.
  </div>
</div>

<div class="notification mb-3">
  <div class="notification-header">
    <div class="icon-box bg-dark">
      <i class="fa fa-car text-primary"></i>
    </div>
    <div class="d-flex flex-column">
      <strong class="ml-3">Contrast</strong>
      <small class="ml-3 small-text">11 mins ago</small>
    </div>
    <button type="button" class="btn p-0 ml-auto h-25">
      <button class="btn-close" data-dismiss="toast"></button>
    </button>
    <div class="toggle">
      <span
        data-toggle="collapse"
        data-target="#collapseSix"
        aria-expanded="true"
        aria-controls="collapseSix"
      ></span>
    </div>
  </div>
  <div class="notification-message" id="collapseSix">
    Hello, world! This is a primary message.
  </div>
</div>

<div class="notification mb-3">
  <div class="notification-header">
    <div class="icon-box bg-dark">
      <i class="fa fa-compass text-danger"></i>
    </div>
    <div class="d-flex flex-column">
      <strong class="ml-3">Contrast</strong>
      <small class="ml-3 small-text">11 mins ago</small>
    </div>
    <button type="button" class="btn p-0 ml-auto h-25">
      <button class="btn-close" data-dismiss="toast"></button>
    </button>
    <div class="toggle">
      <span
        data-toggle="collapse"
        data-target="#collapseSeven"
        aria-expanded="true"
        aria-controls="collapseSeven"
      ></span>
    </div>
  </div>
  <div class="notification-message" id="collapseSeven">
    Hello, world! This is a primary message.
  </div>
</div>

<div class="notification mb-3">
  <div class="notification-header">
    <div class="icon-box bg-dark">
      <i class="fa fa-train text-success"></i>
    </div>
    <div class="d-flex flex-column">
      <strong class="ml-3">Contrast</strong>
      <small class="ml-3 small-text">11 mins ago</small>
    </div>
    <button type="button" class="btn p-0 ml-auto h-25">
      <button class="btn-close" data-dismiss="toast"></button>
    </button>
    <div class="toggle">
      <span
        data-toggle="collapse"
        data-target="#collapseEight"
        aria-expanded="true"
        aria-controls="collapseEight"
      ></span>
    </div>
  </div>
  <div class="notification-message" id="collapseEight">
    Hello, world! This is a primary message.
  </div>
</div>
```

###### JavaScript

```js
    <script src="../build/cdbbootstrap.js"></script>
    <script>
      var toastElList = [].slice.call(
        document.querySelectorAll('.notification'),
      );
      var toastList = toastElList.map(function (toastEl) {
        return new CDB.Notification(toastEl, { sticky: true });
      });

      const notificationId = document.querySelector('#dismiss1');
      const notification1 = new CDB.Notification(notificationId, {
        sticky: true,
        visibleDuration: 2000,
      });
      const notificationId2 = document.querySelector('#dismiss2');
      const notification2 = new CDB.Notification(notificationId2, {
        sticky: false,
        visibleDuration: 2000,
      });
    </script>
```
