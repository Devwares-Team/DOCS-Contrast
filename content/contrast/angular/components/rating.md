---
title: "Rating"
metaTitle: "Angular Bootstrap Rating "
metaDescription: "Angular Bootstrap 5-star rating plugin can be used to allow the users to share their opinion about the product, documentation page, photo and more"

---

# Angular Bootstrap Rating

Angular Bootstrap 5-star rating plugin can be used to allow the users to share their opinion about the product, documentation page, photo and more.

## Importing the Contrast Angular Bootstrap Rating Module

To use the Contrast Angular Bootstrap Rating component in your project you need to import `RatingModule`.

```typescript
import {RatingModule } from 'cdbangular';
```

## Default Rating 

![Angular Bootstrap Rating Default](./images/rating.png)

###### html
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
