---
title: 'EditableTable'
metaTitle: 'Angular Bootstrap EditableTable'
metaDescription: 'Angular Bootstrap EditableTable enables you to add and remove rows and change text and information within cells'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/table/editabletable.md"
---
<ProAlertAngular />

# Angular Bootstrap EditableTable

The Contrast Angular Bootstrap Editable component allows you to create tables you can edit on the website. You can add and remove rows, change texts and informaton within cells.

## Importing the Contrast Angular Bootstrap EditableTable Module

To use the Contrast Angular Bootstrap EditableTable component in your project you need to import `EditableTableModule`.

```ts
import { EditabletableModule } from 'cdbangular';
```

## Default EditableTable

Set the `striped` prop to true to have a striped table, the `bordered` to true for borders. The `data` prop takes in an array of arrays, this is the data displayed in the bootstrap editable Table component.

![Angular Bootstrap EditableTable](https://i.imgur.com/3B7rCoy.gif)

###### HTML

```html
<CDBCard>
  <CDBCardBody>
    <CDBEditableTable
      [striped]="true"
      [bordered]="true"
      [data]="data"
      [columns]="columns"
    ></CDBEditableTable>
  </CDBCardBody>
</CDBCard>
```

###### TypeScript

```ts
import { Component, OnInit } from '@angular/core';

@Component({
  selector: 'app-editable-table',
  templateUrl: './editable-table.component.html',
  styleUrls: ['./editable-table.component.scss'],
})
export class EditableTableComponent implements OnInit {
  columns = ['Fullname', 'Age', 'Company Name', 'City', 'Country'];

  data = [
    ['Guerra Cortez', 45, 'Insectus', 'San Francisco', 'USA'],
    ['Elisa Gallagher', 31, 'Portica', 'London', 'United Kingdom'],
    ['Aurelia Vega', 30, 'Deepends', 'Madrid', 'Spain'],
    ['Guadalupe House', 26, 'Isotronic', 'Berlin', 'Germany'],
  ];

  constructor() {}

  ngOnInit(): void {}
}
```

## API Reference: Contrast Angular Bootstrap EditableTable Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap EditableTable component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBEditableTable` component.

| Name         |  Type   | Default |                         Description                         |                                        Example |
| :----------- | :-----: | ------: | :---------------------------------------------------------: | ---------------------------------------------: |
| class        | String  |         |                     Adds custom classes                     |                                class="myClass" |
| autoWidth    | Boolean |   false |               Adds `w-auto` to the className                |                                 autoWidth=true |
| bordered     | Boolean |   false |      Adds borders on all sides of the table and cells.      |                                  bordered=true |
| borderless   | Boolean |   false |    Removes borders on all sides of the table and cells.     |                                borderless=true |
| data         |  Array  |         |             Binds your data into the component.             |         data = ['Aurelia Vega', 30, 'Depends'] |
| columns      |  Array  |         |            Specify headers and number of columns            | columns=['Person Name', 'Age', 'Company Name'] |
| hover        | Boolean |   false |  Enables a hover state on table rows within a table body.   |                                     hover=true |
| responsive   | Boolean |         |         Makes table responsive across all viewports         |                                responsive=true |
| responsiveSm | Boolean |         |      Makes table responsive up to the small breakpoint      |                              responsiveSm=true |
| responsiveMd | Boolean |         |     Makes table responsive up to the medium breakpoint      |                              responsiveMd=true |
| responsiveLg | Boolean |         |      Makes table responsive up to the large breakpoint      |                              responsiveLg=true |
| responsiveXl | Boolean |         |   Makes table responsive up to the extra large breakpoint   |                              responsiveXl=true |
| hover        | Boolean |   false |  Enables a hover state on table rows within a table body.   |                                     hover=true |
| small        | Boolean |   false | Makes tables more compact by cutting cell padding in half.  |                                     small=true |
| striped      | Boolean |   false | Adds zebra-striping to any table row within the table body. |                                   striped=true |
