---
title: "Accordion"
metaTitle: "Angular Bootstrap Accordion"
metaDescription: "Angular Bootstrap Accordion is a component which organizes content within collapsable items, showing only one collapsible item per time"
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/components/accordion.md"
---

# Contrast Angular Bootstrap Accordion

Constrast Angular Bootstrap Accordion organizes content within collapsable items. They can toggle through a number content with a single click. This property allows for an excellent user experience.

Applications of Angular Bootstrap Accordion are:

* FAQ page

* Multiple items presentation

* Data tables

## Importing the Angular Bootstrap Accordion Module

```ts
import {AccordionModule } from 'cdbangular';
```

## Default Accordion

![Angular Bootstrap Default Accordion](https://i.imgur.com/jg2QM8n.gif)

###### Typescript
```ts
import { Component, OnInit } from '@angular/core';

@Component({
  selector: 'app-accordion',
  templateUrl: './accordion.component.html',
  styleUrls: ['./accordion.component.scss'],
})
export class AccordionComponent implements OnInit {
  paragraph = `Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry
  richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard
  dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf
  moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla
  assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore
  wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur
  butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim
  aesthetic synth nesciunt you probably haven't heard of them accusamus
  labore sustainable VHS.`;

  data = [
    {
      title: 'Accordion 1',
      content: this.paragraph,
    },
    {
      title: 'Accordion 2',
      content: this.paragraph,
    },
    {
      title: 'Accordion 3',
      content: this.paragraph,
    },
    {
      title: 'Accordion 4',
      content: this.paragraph,
    },
  ];

  constructor() {}

  ngOnInit(): void {}
}

```


###### HTML
```html
<CDBAccordion [data]='data' ></CDBAccordion>
```

## Accordion without Icon

![Angular Bootstrap Accordion with Icons](./images/accordionwithouticon.png)

###### Typescript
```ts
import { Component, OnInit } from '@angular/core';

@Component({
  selector: 'app-accordion',
  templateUrl: './accordion.component.html',
  styleUrls: ['./accordion.component.scss'],
})
export class AccordionComponent implements OnInit {
  paragraph = `Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry
  richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard
  dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf
  moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla
  assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore
  wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur
  butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim
  aesthetic synth nesciunt you probably haven't heard of them accusamus
  labore sustainable VHS.`;

  data = [
    {
      title: 'Accordion 1',
      content: this.paragraph,
    },
    {
      title: 'Accordion 2',
      content: this.paragraph,
    },
    {
      title: 'Accordion 3',
      content: this.paragraph,
    },
    {
      title: 'Accordion 4',
      content: this.paragraph,
    },
  ];

  constructor() {}

  ngOnInit(): void {}
}

```


##### HTML
```html
        <CDBAccordion [data]='data' [hideIcon]=true ></CDBAccordion>
```




## API Reference: Contrast Accordion Bootstrap Modules

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Accordion component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists the prop options of the `CDBAccordion` component to personalize your Accordion.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| accordionClass | String       | |Adds custom classes	      |     [accordionClass]="myClass"
| accordionHeaderClass | String |              |Adds custom classes for the accordion header|    [accordionHeaderClass]="myHeaderClass" |
| accordionBodyClass | String   |              |Adds custom classes for the accordion body|      [accordionBodyClass]="myBodyClass" |
| data            | List       |           | Supplies data to the accordion | [data]="data1"
| hideIcon       | Boolean      | false        | Hides Accordion icon |  [hideIcon]=true  |
