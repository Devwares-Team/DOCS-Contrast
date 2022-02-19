---
title: "Iframe"
metaTitle: "Angular Bootstrap Iframe Component"
metaDescription: "Angular Bootstrap IFrame is an HTML document which is embedded in another HTML doc on a web page"

---

# Angular Bootstrap Iframe

Angular Bootstrap IFrame is used to embed another document within the current HTML document.

The Contrast Angular Bootstrap Iframe, like every other Contrast React Bootstrap Components, is very responsive. The `CDBIframe` has callback props that enable us to fire functions at various events making it more interactive.


## Importing the Contrast Angular Bootstrap Iframe Module

To use the Contrast Angular Bootstrap Iframe component in your project you need to import `IframeModule`.

```typescript
import {IframeModule } from 'cdbangular';
```

## Default Iframe 

![Angular Bootstrap Iframe Default](./images/iframe.png)

###### html

```html
<CDBIframe src="https://www.youtube.com/embed/xnczyP2jSR0"/>
```

# Contrast Angular Bootstrap Iframe Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Iframe component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBIframe` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |     class="myClass" |
| url            | String       |              | `Required`. The iframe url | url="https://www.youtube.com/embed/xnczyP2jSR0" |
| allowFullScreen | Boolean      | false        | If set, applies the allowFullScreen param | allowFullScreen=true |
| height         | Number       |              |  	Defines component height | height=300 |
| width          | Number       |              |  	Defines component width | width=300   |
| id             | String       |              |  	Adds id to the element | id="my_id" |
| name           | String       |              | Adds name attribute | name="myIframe" |
| onLoad         | function     |              |  	Function fired on onLoad event | onLoad={handleLoad} |
| onMouseOut     | function     |              |  	Function fired on onMouseOut event | onMouseOut={handleEvent} |
| onMouseOver    | function     |              |  	Function fired on onMouseOver event | onMouseOver={handleEvent} |
| ratio          | String       |              |  	Defines component ratio. Choose from "1by1", "4by3", "16by9" and "21by9"  | ratio="1by1" |
| sandbox        | String       |              | Adds optional sandbox values: (`no value`) -	Applies all restrictions, `allow-forms` -	Allows form submission, `allow-modals` 	Allows to open modal windows, `allow-orientation-lock` 	Allows to lock the screen orientation, `allow-pointer-lock` 	Allows to use the Pointer Lock API, `allow-popups` 	Allows popups, `allow-popups-to-escape-sandbox` 	Allows popups to open new windows without inheriting the sandboxing, `allow-presentation` 	Allows to start a presentation session, `allow-same-origin` 	Allows the iframe content to be treated as being from the same origin, `allow-scripts `	Allows to run scripts, `allow-top-navigation` 	Allows the iframe content to navigate its top-level browsing context, `allow-top-navigation-by-user-activation` 	Allows the iframe content to navigate its top-level browsing context, but only if initiated by user | sandbox=true |
| title          | String       |              | Defines component title | title="my_title" |
| style          | Object       |              | Add's additional styles. | style={color: 'red'}|

