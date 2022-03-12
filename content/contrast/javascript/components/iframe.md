---
title: 'Iframe'
metaTitle: 'Bootstrap 5 Iframe - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 IFrame is a web page that has an HTML document that is embedded in another HTML document.'
---# Bootstrap 5 Iframe

Bootstrap 5 IFrame is a web page that has an HTML document that is embedded in another HTML document. IFrames are used to display content from other websites.

You may use the Bootstrap integration to put the IFrame's content inside a modal to make it even more interactive and fun.

Bootstrap 5 IFrames are fully responsive components that change to the screen size, so you don't have to worry about your content quality.

Application of Iframes:

- Video tutorial
- Promotional video presentation
- Google Maps in contact section

## Default Iframe

Use the id `cdb-iframe1` for the default iframe and the class `cdb-iframe` for the Bootstrap 5 Iframe in your project.

The `src` attribute denotes the location of the material you want to play. The `ratio` attribute specifies the width-to-height ratio in pixels. The `allowFullScreen` parameter enables your Iframe to be full-screen.

![Bootstrap Iframe Default](./images/iframe.png)

######html

```html
<div
  id="cdb-iframe1"
  class="cdb-iframe"
  src="https://www.youtube.com/embed/xnczyP2jSR0"
  title="main video"
  allowFullScreen
  frameBorder="10"
  ratio="4x3"
></div>
```

######Script

```js
    <script>
      new CDB.IFrame(document.querySelector('#cdb-iframe1'));
      new CDB.IFrame(document.querySelector('#cdb-iframe2'));
    </script>
```

## Iframe Customized

Use the id `cdb-iframe2` to include the Contrast Bootstrap 5 Customized Iframe in your project.

######html

```html
<div
  id="cdb-iframe2"
  class="cdb-iframe"
  src="https://www.youtube.com/embed/xnczyP2jSR0"
  title="main video"
  allowFullScreen
  frameBorder="10"
  ratio="4x3"
></div>
```

######Script

```js
    <script>
      new CDB.IFrame(document.querySelector('#cdb-iframe1'));
      new CDB.IFrame(document.querySelector('#cdb-iframe2'));
    </script>
```
