---

title: 'Multiselect'
metaTitle: 'Bootstrap 5 MultiSelect - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 Multiselect is one of Contrast components that allows you to control the numerous options available in one record. it is mostly used in forms, menus and surveys.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/multiselect.md"
---
# Bootstrap 5 Multiselect

Bootstrap 5 Multiselect is a Contrast Design component that allows you to control how a user chooses numerous options available in a record. it is mostly used in forms, menus and surveys.

It allows navigation through options by using the `↑` and `↓` arrow keys, and to choose the required option by using the `↵` key.

<i/>

## Basic Multiselect

To use Contrast Bootstrap 5 Multiselect in your project, use the `multiselect` class.

The Multiselect method in the CDB targets the element with the `multiselect` class.

The `options` array represents values of options to be displayed in the multiselect component, while the `multiple` prop accepts a Boolean value which allows multiple selection of options, when set to true. The `icon` prop specifies which icon should appear in your multiselect, and the `placeholder` property gives a brief description of the expected value(s).

![Bootstrap Multiselect Default](./images/multiselect1.png)

###### HTML

```html
<span class="multiselect"></span>
```

###### JavaScript

```js
  <script src="../build/cdbbootstrap.js"></script>
  <script>
    var multiSelect1 = new CDB.MultiSelect('.multiselect', {
      options: [
        {
          label: 'New York',
          value: 'NY',
        },
        {
          label: 'Washington',
          value: 'WA',
        },
        {
          label: 'California',
          value: 'CA',
        },
        {
          label: 'New Jersey',
          value: 'NJ',
        },
        {
          label: 'North Carolina',
          value: 'NC',
        },
      ],
      multiple: true,
      icon: 'fa fa-times',
      placeholder: 'Select a State',
    });
  </script>
```
