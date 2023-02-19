---
title: "Pane"
metaTitle: "Angular Bootstrap Pane "
metaDescription: "Angular Bootstrap Pane is a component used in displaying information like a card"
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/components/pane.md"
---

# Contrast Angular Bootstrap Pane

Contrast Angular Bootstrap Pane is a component used in displaying information like a card. It is typically used in Chat UIs.


## Importing the Contrast Angular Bootstrap Pane Module

To use the Contrast Angular Bootstrap Pane component in your project you need to import `PaneModule`.

```ts
import {PaneModule } from 'cdbangular';
```

## Pane with Location Marker

Alongside the `CDBPane` component, we use other Contrast Angular Components, these components are, the `CDBPanelTitle` component to write headers in your pane, the `CDBPanelText` component to write texts or messages in your pane, the `CDBPaneImage` component component for your pane images. 

We also import the [CDBIcon](https://www.devwares.com/docs/contrast/angular/components/icon) component. Nesting the `CDBIcon` in our `CDBPane` allows us to have icons in our pane.

![Angular Bootstrap Pane](./images/panewithlocation.png)

###### HTML
```html
<CDBPanel class="pan">
    <CDBPane>
        <CDBPaneImage size="md"
            src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170" ></CDBPaneImage>
        <div class="ml-3">
            <CDBPanelTitle>Warren Briggs</CDBPanelTitle>
            <CDBPanelText small>Australia</CDBPanelText>
        </div>
        <p class="ml-auto mb-0 text-danger">
            300m
            <CDBIcon [fas]=true icon="map-marker-alt" ></CDBIcon>
        </p>
    </CDBPane>
</CDBPanel>
```


## Pane with Dropdown

In this tutorial section, we nest the Contrast Angular Bootstrap Dropdown component, [CDBDropDown](https://www.devwares.com/docs/contrast/angular/components/dropdown), in the `CDBPane` component. With this, we now have dropdowns in our pane.

![image info](./images/panewithdropdown.png)

###### HTML
```html
<CDBPanel class="pan" >
    <CDBPane>
        <CDBPaneImage size="md"
            src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170" ></CDBPaneImage>
        <div class="ml-3">
            <CDBPanelTitle>Warren Briggs</CDBPanelTitle>
            <CDBPanelText small>Breakfast</CDBPanelText>
        </div>
        <CDBDropDown cdbDropdown class="ml-auto">
            <CDBDropDownToggle color="white">
                <CDBIcon class="text-muted" [fas]=true icon="ellipsis-h" ></CDBIcon>
            </CDBDropDownToggle>
            <CDBDropDownMenu>
                <CDBDropDownItem [disabled]='true'>Edit Profile</CDBDropDownItem>
                <CDBDropDownItem [divider]='true' ></CDBDropDownItem>
                <CDBDropDownItem>Action 1</CDBDropDownItem>
                <CDBDropDownItem>Action 2</CDBDropDownItem>
            </CDBDropDownMenu>
        </CDBDropDown>
    </CDBPane>
</CDBPanel>
```


## Contrast Angular Bootstrap Pane Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Pane component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBPane` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |             |Adds custom classes	      |     class="myClass" |
