---
title: "Breadcrumb"
metaTitle: "Angular Bootstrap Breadcrumb "
metaDescription: "Angular Bootstrap Breadcrumb indicates the current page’s location within a navigational hierarchy that automatically adds separators via CSS"
gtihubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/components/breadcrumb.md"
---

# Contrast Angular Bootstrap Breadcrumb

Contrast Angular Bootstrap Breadcrumb reveals the user’s location in a website or web application.  It's a navigational component that allows website visitors or web application users to track their current location and previous navigated page(s).


## Importing the Contrast Angular Bootstrap Breadcrumb Module

To use the Contrast Angular Bootstrap Breadcrumb component in your project you need to import `BreadcrumbModule`.

```ts
import {BreadcrumbModule } from 'cdbangular';
```

## Default Breadcrumb

![Angular Bootstrap Breadcrumb](./images/breadcrumb.png)

###### HTML
```html
<CDBBreadcrumb color="none">
    <li class="breadcrumb-item">
        <CDBLink class="p-0" to="/breadcrumb">Home</CDBLink>
    </li>
    <li class="breadcrumb-item">
        <CDBLink class="p-0" to="/breadcrumb">Library</CDBLink>
    </li>
    <li class="breadcrumb-item active">Data</li>
</CDBBreadcrumb>
<CDBBreadcrumb color="none">
    <li class="breadcrumb-item">
        <CDBLink class="p-0" to="/breadcrumb">Home</CDBLink>
    </li>
    <li class="breadcrumb-item active">Library</li>
</CDBBreadcrumb>
<CDBBreadcrumb color="none">
    <li class="breadcrumb-item active">Home</li>
</CDBBreadcrumb>
```

## Breadcrumb with Icons


![Angular Bootstrap Breadcrumb with Icons](./images/breadcrumbwithicon.png)

###### HTNL
```html
<CDBBreadcrumb color="none" class="align-items-center">
    <li class="breadcrumb-item">
        <CDBLink class="p-0" to="/breadcrumb">Home</CDBLink>
    </li>
    <CDBIcon class="mx-2 text-muted" [fas]=true icon="angle-double-right"></CDBIcon>
    <li class="breadcrumb-item">
        <CDBLink class="p-0" to="/breadcrumb">Library</CDBLink>
    </li>
    <CDBIcon class="mx-2 text-muted" [fas]=true icon="angle-double-right"></CDBIcon>
    <li class="breadcrumb-item active">Data</li>
</CDBBreadcrumb>
<CDBBreadcrumb color="none" class="align-items-center">
    <li class="breadcrumb-item">
        <CDBLink class="p-0" to="/breadcrumb">Home</CDBLink>
    </li>
    <CDBIcon class="mx-2 text-muted" [fas]=true icon="angle-double-right"></CDBIcon>
    <li class="breadcrumb-item active">Library</li>
</CDBBreadcrumb>
<CDBBreadcrumb color="none">
    <li class="breadcrumb-item active">Home</li>
</CDBBreadcrumb>
```

<i/>

## Breadcrumb with colors


![Angular Bootstrap Breadcrumb with colors](./images/breadcrumbwithcolors.png)

###### HTML
```html
<CDBBreadcrumb color="dark" class="align-items-center text-white">
    <li class="breadcrumb-item">
        <CDBLink class="p-0 text-white" to="/breadcrumb">Home</CDBLink>
    </li>
    <CDBIcon class="mx-2 text-muted" [fas]=true icon="angle-double-right"></CDBIcon>
    <li class="breadcrumb-item">
        <CDBLink class="p-0 text-white" to="/breadcrumb">Library</CDBLink>
    </li>
    <CDBIcon class="mx-2 text-muted" [fas]=true icon="angle-double-right"></CDBIcon>
    <li class="breadcrumb-item">Data</li>
</CDBBreadcrumb>
<CDBBreadcrumb class="align-items-center">
    <li class="breadcrumb-item">
        <CDBLink class="p-0 text-white" to="/breadcrumb">Home</CDBLink>
    </li>
    <CDBIcon class="mx-2 text-muted" [fas]=true icon="angle-double-right"></CDBIcon>
    <li class="breadcrumb-item">Library</li>
</CDBBreadcrumb>
<CDBBreadcrumb color="info">
    <li class="breadcrumb-item">Home</li>
</CDBBreadcrumb>
```

## API Reference: Contrast Angular Bootstrap Breadcrumb Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Breadcrumb component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBBreadcrumb` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |     class="myClass"  |
| color          | String       | primary      | Determines breadcrumb background color, accepts CDB predefined color classes: `primary` `secondary` `success` `danger` `warning` `info` `light` `dark` | color="primary"   |
| light          | Boolean      | false        | Sets font color to white |  color="dark" light=true |
| uppercase      | Boolean      | false        | Transforms breadcrumbs text to uppercase   | color="secondary" uppercase=true |
