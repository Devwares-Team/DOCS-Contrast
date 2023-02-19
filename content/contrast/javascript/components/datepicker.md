---
title: 'DatePicker'
metaTitle: 'Bootstrap 5 DatePicker - Bootstrap CSS tutorial'
metaDescription: 'Pick a specific date and time with Bootstrap 5 DatePicker'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/datepicker.md"
---

# Bootstrap 5 DatePicker

Bootstrap 5 DatePicker is a component in the Contrast Design Library that makes it possible for you to pick a date and time easily in your web applications.

## Default DatePicker

<Link to="/product/bootstrap-contrast-pro"><CDBBadge size="large" className="badge-pro">Pro Component</CDBBadge></Link>

![Bootstrap DatePicker Default](https://i.imgur.com/ClWprya.gif)

###### HTML

```html
<div class="datepicker-container">
  <input name="foo" class="date-picker-input" style="width: 25rem" />
</div>
```

###### JavaScript

```js
<script>
  const elem = document.querySelector('input[name="foo"]'); const datepicker = new
  CDB.Datepicker(elem, {});
</script>
```
