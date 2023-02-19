---
title: 'Alert'
metaTitle: 'Bootstrap 5 Alert - Bootstrap CSS tutorial'
metaDescription: 'Using Bootstrap 5 Alert, provide feedback for common user actions using configurable alert messages.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/alert.md"
---

# Bootstrap 5 Alert

Bootstrap 5 Alerts are used to send feedback messages to users after they perform particular activities.

Bootstrap 5 Alerts have an optional dismiss button. It is used with text of varying lengths to pass information to users. Contextual props (e.g., color="success") are used to give Bootstrap Alerts a suitable style. The dismiss prop is used  for inline dismissal of the Alert component.

## Default Alert

Bootstrap Alert Component can by used by adding `alert` to a `div` element's class. Our alerts can be styled with backdrop colors by adding the alert's color ( alert-primary, alert-secondary, alert-success, etc.) to the class of the `div` element.

###### HTML

```html
<div>
  <div className="alert alert-primary">
    A simple alert built with contrast design check it out!
  </div>
  <div className="alert alert-secondary">
    A simple alert built with contrast design check it out!
  </div>
  <div className="alert alert-success">
    A simple alert built with contrast design check it out!
  </div>
  <div className="alert alert-danger">
    A simple alert built with contrast design check it out!
  </div>
  <div className="alert alert-warning">
    A simple alert built with contrast design check it out!
  </div>
  <div className="alert alert-info">
    A simple alert built with contrast design check it out!
  </div>
  <div className="alert alert-dark">
    A simple alert built with contrast design check it out!
  </div>
</div>
```

## Dismissible Alert Button

<Alert2/>

###### HTML

```html
<div class="alert alert-danger alert-dismissible fade show" role="alert">
  <strong>Holy guacamole!</strong> You should check in on some of those fields below.
  <button type="button" class="btn-close" data-dismiss="alert" aria-label="Close"></button>
</div>
```

## Dismissible Alert Button with Javascript

<Alert3/>

###### HTML

```html
  <div
    class="alert alert-warning alert-dismissible fade show"
    id="alert1"
    role="alert"
  >
    Hey Dismiss me using Javascript
  </div>
  <button id="dismiss1" class="btn btn-dark btn-flat mt-4">
    Dismiss Alert
  </button>
</div>
```

###### JavaScript

```js
<script>
  document.querySelector('#dismiss1').addEventListener('click', () => {
    var alertNode = document.querySelector('#alert1');
    var alert = new bootstrap.Alert(alertNode);
    alert.close();
  });
</script>
```
