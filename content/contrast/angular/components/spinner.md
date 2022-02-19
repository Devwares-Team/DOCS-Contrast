---
title: "Spinner"
metaTitle: "Angular Bootstrap Spinner"
metaDescription: "Angular Bootstrap Spinner is animation that is used to keep visitors entertained while the page is still loading, which helps to increase the user experience"

---

# Angular Bootstrap Spinner

Angular Bootstrap Spinner is animation that is used to keep visitors entertained while the page is still loading, which helps to increase the user experience.

## Importing the Contrast Angular Bootstrap Spinner Module

To use the Contrast Angular Bootstrap Spinner component in your project you need to import `SpinnerModule`.

```typescript
import {SpinnerModule } from 'cdbangular';
```

## Default Spinner

Use the Contrast Bootstrap Spinner Component to create your spinner.

The `CDBSpinner` component takes in a `color` prop, this prop allows us to give the spinner any background color of our choice. 

![Angular Bootstrap Spinner Default](./images/spinner1.gif)

###### html
```html
<CDBSpinner ></CDBSpinner>
<CDBSpinner color='danger' ></CDBSpinner>
<CDBSpinner color='success' ></CDBSpinner>
<CDBSpinner color='warning' ></CDBSpinner>
<CDBSpinner color='info' ></CDBSpinner>
<CDBSpinner color='dark' ></CDBSpinner>
<CDBSpinner color='secondary' ></CDBSpinner>
```
## Multicolor Spinner

Set the `multicolor` prop to `true` to give your spinner multiple colors.

![Angular Bootstrap Spinner Multicolor](./images/spinner2.gif)

###### html
```html
<CDBSpinner [multicolor]=true ></CDBSpinner>
```

## Size Variations

Use the `size` prop to specify how large or little you want your spinner to be. The size options ranges from (small to big). the default size of the spinner is medium. 

![Angular Bootstrap Spinner Size Variations](./images/spinner3.gif)

###### html
```html
<CDBSpinner size="big" ></CDBSpinner>
<CDBSpinner color='secondary' ></CDBSpinner>
<CDBSpinner color='success' size="small" ></CDBSpinner>
```

## API Reference: Contrast Angular Bootstrap Spinner Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Spinner component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBSpinner`.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |     class="myClass" |
| size           | String       |              | Changes the size of the spinner. Select from one these keywords: `big` and `small`. | <CDBSpinner size="big" ... />  |
| color          | String       | primary      | Determines breadcrumb background color, accepts CDB predefined color classes: `primary` `secondary` `success` `danger` `warning` `info` `light` `dark` | color="primary"   |
| multicolor           | Boolean       |  false            |  Allows spinner multi colors  | [multicolor]=true |
