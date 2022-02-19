---
title: "Alert"
metaTitle: "Angular Bootstrap Alert"
metaDescription: "Angular Bootstrap Alert can be used to provide feedback messages to users after specific actions are carried out"
---

# Angular Bootstrap Alert

Angular Bootstrap Alert can be used to provide feedback messages to users after specific actions are carried out.

## Examples

Contrast Alerts are available for any length of text, as well as an optional dismiss button. For proper styling, use one of the contextual props (e.g., color="success"). For inline dismissal, use the dismiss prop.

## Importing the Contrast Angular Bootstrap Alert

```typescript
import {AlertModule } from 'cdbangular';
```

![Angular Bootstrap Alert](./images/Alert.png)

###### Typescript

```typescript
import { Component, OnInit } from `@angular/core`;

@Component({
  selector: `app-alert`,
  templateUrl: `./alert.component.html`,
  styleUrls: [`./alert.component.scss`]
})
export class AlertComponent implements OnInit {

  constructor() { }

  ngOnInit(): void {
  }

}
```
###### HTML

```html
    <CDBAlert color="primary">
        A simple alert built with contrast design check it out!
    </CDBAlert>
    <CDBAlert color="secondary">
        A simple alert built with contrast design check it out!
    </CDBAlert>
    <CDBAlert color="success">
        A simple alert built with contrast design check it out!
    </CDBAlert>
    <CDBAlert color="danger" [dismiss]=true>
        A simple alert built with contrast design check it out!
    </CDBAlert>
    <CDBAlert color="warning">
        A simple alert built with contrast design check it out!
    </CDBAlert>
    <CDBAlert color="dark">
        A simple alert built with contrast design check it out!
    </CDBAlert>
```

## Contrast Angular Bootstrap Alert Props

This section will build on your information about the props you get to use with the Contrast React Bootstrap Alert component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBAlert` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
|  class     | String       |        |Adds custom classes	      |     [class]="myClass"  |
| color          | String       | primary      | Sets color of the alert. Choose one of these: `primary`, `secondary`, `success`, `danger`, `warning`, `info`, `light`, `dark` |  [color]="primary"   |
| dismiss     | Boolean       | false       | Shows a dismiss button |     [dismiss]=true  |
