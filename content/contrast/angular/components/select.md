---
title: "Select"
metaTitle: "Angular Bootstrap Select"
metaDescription: "Angular Bootstrap Select is a form control, that after the click displays a collapsible list of multiple values which can be used in forms, menus or surveys"
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/components/select.md"
---

# Contrast Angular Bootstrap Select

Contrast Angular Bootstrap Select is a form control component that displays a collapsible list of values which can be used in forms, menus or surveys.

Contrast Angular Bootstrap Select enables you to use `↑` and `↓` arrow keys to navigate through options and use `↵` key to select required option (works for stateful select).

## Importing the Angular Bootstrap Select Component

To use the Contrast Angular Bootstrap Rating component, you import `CDBSelect` into your project.

```ts
import {SelectModule } from 'cdbangular';
```

## Default Select 

The `CDBSelect` prop takes in an [option] prop whose value is an array of different user options.

![Angular Bootstrap Select Default](./images/select.png)

###### HTML
```html
<CDBSelect [options]='option' selected="Choose an option"></CDBSelect>
```
###### TypeScript
```ts
import { Component, OnInit } from '@angular/core';

@Component({
  selector: 'app-select',
  templateUrl: './select.component.html',
  styleUrls: ['./select.component.scss'],
})
export class SelectComponent implements OnInit {
  option = [
    {
      text: 'Option 1',
      value: '1',
    },
    {
      text: 'Option 2',
      value: '2',
    },
    {
      text: 'Option 3',
      value: '3',
    },
  ];

  constructor() {}

  ngOnInit(): void {}
}
```
## API Reference: Contrast Angular Bootstrap Select Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Select component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBSelect`.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |     class="myClass" |
| optionClassName  | String       |              | Adds custom classes to options | optionClassName="my-class" |
| selected       | String       |              | Set default select text content. | selected="Choose one" |
| options        | Array of Objects |              | Sets options array as source of data. This property is used in alternative `Select2` version. | options=[options] |
