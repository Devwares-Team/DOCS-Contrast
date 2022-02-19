---
title: "ButtonToolbar"
metaTitle: "Angular Bootstrap ButtonToolbar"
metaDescription: "Angular Bootstrap ButtonToolbar combines sets of button groups into button toolbars for more complex components"
---

# Angular Bootstrap ButtonToolbar

Angular Bootstrap ButtonToolbar combines sets of button groups into button toolbars for more complex components. Use utility classes as needed to space out groups, buttons, and more.

## Importing the Contrast Angular Bootstrap ButtonToolbar Module

To use the Contrast Angular Bootstrap ButtonToolbar component in your project you need to import `ButtonToolbarModule`.

```typescript
import {ButtontoolbarModule } from 'cdbangular';
```

## ButtonToolbar

Use the `color` prop to define the background color of the buttons in your button toolbar.

![Angular Bootstrap ButtonToolbar ](./images/buttontoolbar.png)

###### html
```html
      <CDBBtnTb>
        <CDBBtnGrp className="mr-2">
          <CDBBtn color="primary">click me</CDBBtn>
          <CDBBtn color="secondary">click me</CDBBtn>
          <CDBBtn color="success">click me</CDBBtn>
        </CDBBtnGrp>
        <CDBBtnGrp size="sm" className="mr-2">
          <CDBBtn color="primary">click me</CDBBtn>
          <CDBBtn color="secondary">click me</CDBBtn>
          <CDBBtn color="success">click me</CDBBtn>
        </CDBBtnGrp>
        <CDBBtnGrp >
          <CDBBtn color="danger">click me</CDBBtn>
          <CDBBtn color="dark">click me</CDBBtn>
          <CDBBtn color="warning">click me</CDBBtn>
        </CDBBtnGrp>
      </CDBBtnTb>
```


## API Reference: Contrast Angular Bootstrap ButtonToolbar Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap ButtonToolbar component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBBtnTb` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |     class="myClass"  |
| role           | String       | toolbar      | Change default component's role | role="toolbar"  |
