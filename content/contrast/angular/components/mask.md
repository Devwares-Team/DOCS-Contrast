---
title: "Mask"
metaTitle: "Angular Bootstrap Mask Component"
metaDescription: "Angular Bootstrap Masks alter the visibility of an element by either partially or fully hiding it"
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/components/mask.md"
---

# Contrast Bootstrap Mask

Contrast Angular Bootstrap Masks alter the visibility of an element by either partially or fully hiding it. Contrast Design Angular Masks are used to make content more visible in the picture.

## Importing the Contrast Angular Bootstrap Mask Module

To use the Contrast Angular Bootstrap Mask component in your project you need to import `MaskModule`.


```ts
import {MaskModule } from 'cdbangular';
```

We use two Contrast components `CDBMask` and `CDBView`. The content that we are trying to hide or partially hide stays in the `CDBView` component. Then the `CDBMask` is the overlay or pattern over the content.

## Mask Patterns

The Contrast Angular Bootstrap Mask component, the `CDBMask`, allows you to pass in a pattern parameter ( ranging from pattern1 to pattern4) into the `pattern` prop to use a pattern over your content.

![Angular Bootstrap Mask Patterns](https://imgur.com/MCquXaE.png)
![Angular Bootstrap Mask Patterns](https://imgur.com/qzyTCFL.png)
![Angular Bootstrap Mask Patterns](https://imgur.com/FOb0fkk.png)
![Angular Bootstrap Mask Patterns](https://imgur.com/FtwM3yj.png)

###### HTML
```html
<CDBView>
    <img src="../../../assets/../../../assets/img/food.jpg" class="img-fluid" alt="" style="width: 100%" />
    <CDBMask pattern="pattern1" class="flex-center" ></CDBMask>
</CDBView>
<CDBView>
    <img src="../../../assets/img/food.jpg" class="img-fluid" alt="" style="width: 100%" />
    <CDBMask pattern="pattern2" class="flex-center" ></CDBMask>
</CDBView>
<CDBView>
    <img src="../../../assets/img/food.jpg" class="img-fluid" alt="" style="width: 100%" />
    <CDBMask pattern="pattern3" class="flex-center" ></CDBMask>
</CDBView>
<CDBView>
    <img src="../../../assets/img/food.jpg" class="img-fluid" alt="" style="width: 100%" />
    <CDBMask pattern="pattern4" class="flex-center" ></CDBMask>
</CDBView>
```
## Mask Light Overlay

Use the' overlay' prop to use a light background color as your overlay over your content. Set the value to the color you would like, appending the word Light at the end. For example `overlay= "blueLight"`.

![Angular Bootstrap Mask Light Overlay](https://imgur.com/Yoxa6Xr.png)
![Angular Bootstrap Mask Light Overlay](https://imgur.com/XgzFd30.png)

###### HTML
```html
<CDBView>
    <img src="../../../assets/img/food.jpg" class="img-fluid" alt="" style="width: 100%" />
    <CDBMask overlay="blueLight" class="flex-center" ></CDBMask>
</CDBView>
<CDBView>
    <img src="../../../assets/img/food.jpg" class="img-fluid" alt="" style="width: 100%" />
    <CDBMask overlay="redLight" class="flex-center" ></CDBMask>
</CDBView>
```

## Mask Strong Overlay

Use the' overlay' prop to use a thick background color as your overlay over your content. Set the value to the color you would like, appending the word Strong at the end. For example `overlay= "blueStrong"`.

![Angular Bootstrap Mask Strong Overlay](https://imgur.com/Q0y0x7A.png)
![Angular Bootstrap Mask Strong Overlay](https://imgur.com/39KbCT0.png)

###### HTML
```html
<CDBView>
    <img src="../../../assets/img/food.jpg" class="img-fluid" alt="" style="width: 100%" />
    <CDBMask overlay="blueStrong" class="flex-center" ></CDBMask>
</CDBView>
<CDBView>
    <img src="../../../assets/img/food.jpg" class="img-fluid" alt="" style="width: 100%" />
    <CDBMask overlay="redStrong" class="flex-center" ></CDBMask>
</CDBView>
```

## API Reference: Contrast Angular Bootstrap Mask Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Mask component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBMask` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |     class="myClass" |
| overlay        | String       |              | Creates overlay in passed color | overlay="grey-light" |
| pattern        | String or Number |              | Creates pattern with chosen style | pattern="1" |
