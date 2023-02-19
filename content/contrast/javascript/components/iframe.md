---
title: 'IFrame'
metaTitle: 'Bootstrap 5 IFrame - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 IFrame is a web element that has an HTML document embedded in another HTML document.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/iframe.md"
---
# Bootstrap 5 IFrame

Bootstrap 5 IFrame is a web element that has an HTML document  embedded in another HTML document. IFrames are used to display content from other websites.

You may use the Bootstrap integration to put the IFrame's content inside a modal to make it even more interactive and fun.

Bootstrap 5 IFrames are fully responsive components that change to the screen size, so you don't have to worry about your content quality.

Application of IFrames:

- Video tutorial
- Promotional video presentation
- Google Maps in contact section

## Default IFrame

Use the id `cdb-iframe1` for the default IFrame and the class `cdb-iframe` for the Bootstrap 5 IFrame in your project.

The `src` attribute denotes the location of the material you want to play. The `ratio` attribute specifies the width-to-height ratio in pixels. The `allowFullScreen` parameter enables your IFrame to be full-screen.

<Iframe1/>

###### HTML

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

###### JavaScript

```js
    <script>
      new CDB.IFrame(document.querySelector('#cdb-iframe1'));
      new CDB.IFrame(document.querySelector('#cdb-iframe1'));
    </script>
```

## IFrame Customized

Use the id `cdb-iframe` to include the Contrast Bootstrap 5 Customized IFrame in your project.

###### HTML

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

###### JavaScript

```js
<script>
  new CDB.IFrame(document.querySelector('#cdb-iframe1')); new
  CDB.IFrame(document.querySelector('#cdb-iframe2'));
</script>
```
