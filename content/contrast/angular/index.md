---
title: "Getting Started"
metaTitle: 'Setting up Contrast Design Bootstrap Angular in our project'
metaDescription: 'Ways to set up Contrast Design Bootstrap Angular in our project'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/index.md"
---

# Contrast Design Bootstrap Angular

> Angular 15 & Bootstrap 5  Elegant UI Kit and reusable components for building mobile-first, responsive websites and web apps

[![NPM](https://img.shields.io/npm/v/ng-cdbangular.svg)](https://www.npmjs.com/package/ng-cdbangular)  [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)  ![npm](https://img.shields.io/npm/dw/ng-cdbangular)



## Usage
Be sure to have `ng-cdbangular` installed in your project, you can follow the guides on our [installation](https://www.devwares.com/docs/contrast/angular/Installation/) page to get `ng-cdbangular` working on your project.

Below is an example to show you how you can build your project using `ng-cdbangular` components.

Import preferred module in app.module.ts
```jsx
import { AlertModule, ButtonModule } from 'ng-cdbangular';

@NgModule({
  imports: [
    AlertModule,
    ButtonModule
  ]
})
```

You can also import all cdbangular modules this way
```jsx
import { CDBFreeModule } from 'ng-cdbangular';

@NgModule({
  imports: [
    CDBFreeModule,
  ]
})
```

In app.component.html
```jsx
<CDBAlert color="success">
  A simple alert built with contrast design check it out!
</CDBAlert>
<CDBAlert color="danger" [dismiss]=true>
  A simple alert built with contrast design check it out!
</CDBAlert>

<CDBBtn color="primary">Primary</CDBBtn>
<CDBBtn color="secondary">Secondary</CDBBtn>
<CDBBtn color="success">Success</CDBBtn>
<CDBBtn color="danger">Danger</CDBBtn>
<CDBBtn color="dark">Dark</CDBBtn>
<CDBBtn color="warning">Warning</CDBBtn>
<CDBBtn color="info">Info</CDBBtn>
<CDBBtn color="white">White</CDBBtn>
<CDBBtn color="light">Light</CDBBtn>
```

`ng-cdbangular` can be used on your projects to fit your projects needs. Yes, it's that easy! Check out the documentation for the components to see how you can use them.

# Browser support

## Browsers supported

|     |  [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="Edge / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br/>Opera |
|-----|  --------- | --------- | --------- | --------- | --------- |
|Mac | N/A  | supported  | supported   | supported   | supported  |
|Windows | supported  |supported   |supported   | N/A | supported  |

## Documentation

[Check out our documentation here](https://www.devwares.com/docs/contrast/angular/index)

## PRO Version

[Contrast Design Bootstrap PRO](https://www.devwares.com/product/contrast-pro)

## License

See License in &lt;license.pdf&gt; © [Devwares](https://github.com/Devwares)

## Support Devwares

### Follow us on Social Media

* [Twitter](https://twitter.com/devwares?s=09)
* [Facebook](https://www.facebook.com/Devwares-102291481719158/)
* [Instagram](https://instagram.com/devwares)
* [Linkedin](https://www.linkedin.com/company/devwares)
* [Youtube](https://www.youtube.com/channel/UCl0MxA8KB7EdmPcSsVwT3pQ)

### Check out and star our GitHub repository

* [Github](https://github.com/Devwares)

* Create pull requests
* Submit bugs
* Suggest new features
* Help us Improve our documentation with updates

We truly appreciate us all and everyone who has contributed to this project, as we continue to use and imporove this project.

A massive thank you to everyone!
