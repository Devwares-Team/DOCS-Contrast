---
title: 'Alert'
metaTitle: 'Bootstrap 5 Accordion - Bootstrap CSS tutorial'
metaDescription: 'Using Bootstrap 5 Alert, provide feedback for common user actions using configurable alert messages.'
---

# Bootstrap 5 Alert

Bootstrap 5 Alerts are used to send feedback messages to users after they perform particular activities.

Bootstrap 5 Alerts come with an optional dismiss button and may be used with any amount of text. Use one of the contextual props (e.g., color="success") for suitable style. Use the dismiss prop for inline dismissal.

![Bootstrap Alerts](./images/Alert.png)

## Default Alert

We may use the Bootstrap Alert Component to give our div element the alert `class`. As a result, our `div` element becomes an alert. We can also give several backdrop colors for our alerts by giving our `div` a class of alert and attaching the various color keywords ( primary, secondary, success, etc.).

###### html

```html
<div class="alert alert-primary" style="width: fit-content" role="alert">
  A simple alert built with contrast design check it out!
</div>
<div class="alert alert-secondary" style="width: fit-content" role="alert">
  A simple alert built with contrast design check it out!
</div>
<div class="alert alert-success" style="width: fit-content" role="alert">
  A simple alert built with contrast design check it out!
</div>
<div class="alert alert-danger" style="width: fit-content" role="alert">
  A simple alert built with contrast design check it out!
</div>
<div class="alert alert-warning" style="width: fit-content" role="alert">
  A simple alert built with contrast design check it out!
</div>
<div class="alert alert-info" style="width: fit-content" role="alert">
  A simple alert built with contrast design check it out!
</div>

<div class="alert alert-dark" style="width: fit-content" role="alert">
  A simple alert built with contrast design check it out!
</div>
```

## Dismissable Alert Button

![Bootstrap Dismissable Alert Button](./images/alertdismissible.png)

###### HTML

```html
<div class="alert alert-warning alert-dismissible fade show" role="alert">
  <strong>Holy guacamole!</strong> You should check in on some of those fields below.
  <button type="button" class="btn-close" data-dismiss="alert" aria-label="Close"></button>
</div>
```

## Dismissable Alert Button with Javascript

![image info](./images/alertdismissiblewithjs.png)

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

###### Script

```js
<script>
  document.querySelector('#dismiss1').addEventListener('click', () => {
    var alertNode = document.querySelector('#alert1');
    var alert = new bootstrap.Alert(alertNode);
    alert.close();
  });
</script>
```
