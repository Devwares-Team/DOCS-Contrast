---
title: "Accordion"
metaTitle: "Bootstrap 5 Accordion - Bootstrap CSS tutorial"
metaDescription: "Bootstrap 5 Accordion allows the content to be organized in a collapsible item. "
---

# Bootstrap 5 Accordion

Bootstrap 5 Accordion allows the content to be organized in a collapsible item. With a single click, they can cycle through a variety of text blocks. This attribute contributes to a positive user experience.

Applications of Bootstrap Accordion are:

* FAQ page

* Multiple items presentation

* Data tables

## Default Accordion

![Bootstrap Accordion](https://i.imgur.com/jg2QM8n.gif)

###### Script
```js
      [].slice
        .call(document.querySelectorAll('[role=cdb-accordion]'))
        .forEach(progress => {
          new CDB.Accordion(progress);
        });
```


###### HTML
```html
        <div role="cdb-accordion" class="cdb-accordion">
          <div class="accordion">
            <h2 class="accordion-header">Accordion 1</h2>
            <div class="accordion-panel">
               Curabitur vel aliquam nisi. Suspendisse sodales sem at sodales pulvinar. Duis vehicula risus odio, id sagittis ante elementum in. Vestibulum ornare pulvinar risus at tincidunt. Nullam porttitor ullamcorper dictum. Curabitur eu nisi tempor, rhoncus nisi ut, luctus ex.
            </div>
          </div>
          <div class="accordion">
            <h2 class="accordion-header">Accordion 2</h2>
            <div class="accordion-panel">
              Pellentesque neque nulla, volutpat a lacus non, euismod molestie velit. Nulla vitae elit blandit, placerat risus non, rutrum odio. Phasellus et nisl eget dui pulvinar rutrum. Nulla in nulla a lectus accumsan varius vel vitae metus. Phasellus ac finibus elit. Etiam at commodo diam. Pellentesque erat tellus, semper quis maximus in, iaculis vitae tellus.
            </div>
          </div>

          <div class="accordion">
            <h2 class="accordion-header">Accordion 3</h2>
            <div class="accordion-panel">
                Curabitur vel aliquam nisi. Suspendisse sodales sem at sodales pulvinar. Duis vehicula risus odio, id sagittis ante elementum in. Vestibulum ornare pulvinar risus at tincidunt. Nullam porttitor ullamcorper dictum. Curabitur eu nisi tempor, rhoncus nisi ut, luctus ex.
            </div>
          </div>
          <div class="accordion">
            <h2 class="accordion-header">Accordion 4</h2>
            <div class="accordion-panel">
             Pellentesque neque nulla, volutpat a lacus non, euismod molestie velit. Nulla vitae elit blandit, placerat risus non, rutrum odio. Phasellus et nisl eget dui pulvinar rutrum. Nulla in nulla a lectus accumsan varius vel vitae metus. Phasellus ac finibus elit. Etiam at commodo diam. Pellentesque erat tellus, semper quis maximus in, iaculis vitae tellusr.
            </div>
          </div>
        </div>
```

## Accordion without Icon

With Contrast Bootstrap Accordion, you can construct an Accordion without the caret icon by adding the `no-icon` class to the `h2` element

![Bootstrap Accordion with icons](./images/accordionwithouticon.png)

###### Script
```js
      [].slice
        .call(document.querySelectorAll('[role=cdb-accordion]'))
        .forEach(progress => {
          new CDB.Accordion(progress);
        });
```


###### HTML
```html
        <div role="cdb-accordion" class="cdb-accordion">
          <div class="accordion">
            <h2 class="accordion-header no-icon">Accordion 1</h2>
            <div class="accordion-panel">
             Pellentesque neque nulla, volutpat a lacus non, euismod molestie velit. Nulla vitae elit blandit, placerat risus non, rutrum odio. Phasellus et nisl eget dui pulvinar rutrum. Nulla in nulla a lectus accumsan varius vel vitae metus. Phasellus ac finibus elit. Etiam at commodo diam. Pellentesque erat tellus, semper quis maximus in, iaculis vitae tellus
            </div>
          </div>
          <div class="accordion">
            <h2 class="accordion-header no-icon">Accordion 2</h2>
            <div class="accordion-panel">
              Pellentesque neque nulla, volutpat a lacus non, euismod molestie velit. Nulla vitae elit blandit, placerat risus non, rutrum odio. Phasellus et nisl eget dui pulvinar rutrum. Nulla in nulla a lectus accumsan varius vel vitae metus. Phasellus ac finibus elit. Etiam at commodo diam. Pellentesque erat tellus, semper quis maximus in, iaculis vitae tellus
            
            </div>
          </div>

          <div class="accordion">
            <h2 class="accordion-header no-icon">Accordion 3</h2>
            <div class="accordion-panel">
            Pellentesque neque nulla, volutpat a lacus non, euismod molestie velit. Nulla vitae elit blandit, placerat risus non, rutrum odio. Phasellus et nisl eget dui pulvinar rutrum. Nulla in nulla a lectus accumsan varius vel vitae metus. Phasellus ac finibus elit. Etiam at commodo diam. Pellentesque erat tellus, semper quis maximus in, iaculis vitae tellus
            
            </div>
          </div>
          <div class="accordion">
            <h2 class="accordion-header no-icon">Accordion 4</h2>
            <div class="accordion-panel">
             Pellentesque neque nulla, volutpat a lacus non, euismod molestie velit. Nulla vitae elit blandit, placerat risus non, rutrum odio. Phasellus et nisl eget dui pulvinar rutrum. Nulla in nulla a lectus accumsan varius vel vitae metus. Phasellus ac finibus elit. Etiam at commodo diam. Pellentesque erat tellus, semper quis maximus in, iaculis vitae tellus.
            </div>
          </div>
        </div>
      </div>
```




