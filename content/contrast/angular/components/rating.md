---
title: "Rating"
metaTitle: "Angular Bootstrap Rating "
metaDescription: "Angular Bootstrap consists of interactive icons, which allow users to share their experience or thoughts on a product or service. It helps to gain insights from a product users' feedback in order to improve the product.  "
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/components/rating.md"
---

# Contrast Angular Bootstrap Rating

Contrast Angular Bootstrap Rating is made up of interactive icons, which allow users to share their experience or thoughts on a product or service. It helps to gain insights from a product users' feedback in order to improve the product.  

## Importing the Contrast Angular Bootstrap Rating Module

To use the Contrast Angular Bootstrap Rating component in your project you need to import `RatingModule`.

```ts
import {RatingModule } from 'cdbangular';
```

## Default Rating 

![Angular Bootstrap Rating Default](./images/rating.png)

###### HTML
```html
<CDBRating [iconRegular]=true></CDBRating>
<CDBRating [iconFaces]=true fillClass='black-text' [iconRegular]=true></CDBRating>
<CDBRating [feedback]=true></CDBRating>
```

## API Reference: Contrast Angular Bootstrap Rating Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Rating component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBRating`.


| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| containerClass      | String       | | Adds custom classes	to the container      |     containerClass="myClass" |
| data            | Array       |  [{tooltip: 'Very Bad'}, {tooltip: 'Poor'}, {tooltip: 'Ok'}, {tooltip: 'Good'},{tooltip: 'Excellent'}]         | Sets custom data of icon property.  | data=[{tooltip: 'Very Bad'}, {tooltip: 'Poor'}, {tooltip: 'Ok'}, {tooltip: 'Good'},{tooltip: 'Excellent'}] |
| feedback        | Boolean      | false        | If set to `true`, clicking a star will trigger a popover with a textarea | feedback=true |
| fillClass        | String      | fiveStars        | Sets custom classes for filled icons  | fillClass="red-text" |
| iconClass            | String       |           | Sets default icon's classes  | iconClass="blue-text" |
| iconFaces        | Boolean      | false        | Changes icon star for icon face  | iconFaces=true |
| iconSize            | String       | 1x          | Sets size of icons  | iconSize="2x" |
| iconRegular        | Boolean      | false        | Sets regular style of icons  | iconRegular=true |
| submitHandler        | function      |         | Returns feedback form value  | summitHandler={handleSubmit} |
