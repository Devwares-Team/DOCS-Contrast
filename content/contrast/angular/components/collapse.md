---
title: "Collapse"
metaTitle: "Angular Bootstrap Collapse Component"
metaDescription: "Angular Bootstrap Collapse is a component which toggles content"
---


# Angular Bootstrap Collapse

Angular Bootstrap Collapse is a component which toggles content. Useful for grouping great amount of texts and/or graphics into expanding and collapsing items.

Contrast Angular Bootstrap Collapse is used to show and hide content. Buttons or anchors are used as triggers that are mapped to specific elements you toggle. Collapsing an element will animate the `height` from its current value to `0`.

## Importing the Contrast Angular Bootstrap Collapse Module

To use the Contrast Angular Bootstrap Collapse component in your project you need to import `CollapseModule`.

```typescript
import {CollapseModule } from 'cdbangular';
```

## Default Collapse 

![Angular Bootstrap Collapse Default](https://i.imgur.com/PqwJe4o.gif)

###### html
```html
<CDBBtn color="primary" style="margin-bottom: 1rem" (click)="content.toggleCollapse()">
    COLLAPSE BUTTON
</CDBBtn>
<CDBCollapse #content="cdbCollapse">
    <span>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
        enim ad minim veniam, quis nostrud exercitation ullamco laboris
        nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
        reprehenderit in voluptate velit esse cillum dolore eu fugiat
        nulla pariatur. Excepteur sint occaecat cupidatat non proident,
        sunt in culpa qui officia deserunt mollit anim id est laborum
    </span>
</CDBCollapse>
```

## Opened Collapse

![Angular Bootstrap Collapse Opened](https://i.imgur.com/PqwJe4o.gif)

###### html
```html
<CDBBtn color="secondary" style="margin-bottom: 1rem" (click)="content2.toggleCollapse()">
    COLLAPSE BUTTON
</CDBBtn>
<CDBCollapse #content2="cdbCollapse" [isOpen]=true>
    <span>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor harum, molestias ducimus dolorem,
        ipsa asperiores sequi quaerat quidem non eius facere vitae pariatur at voluptatibus sint blanditiis
        facilis sunt accusamus quae quia voluptas, enim numquam! Maxime nulla omnis soluta sequi consequatur
        iusto repudiandae obcaecati, eius numquam delectus veniam possimus fugiat qui nobis neque eveniet
        quasi doloribus magnam amet nihil! Et perferendis ipsum repellat est deserunt. Mollitia labore
        deserunt rerum nulla, at ratione, quis aperiam soluta atque beatae totam incidunt maxime voluptatem
        fugit libero! Molestias tempore illo assumenda repellat atque commodi sint nam illum voluptate a
        perspiciatis, delectus ex nesciunt harum! Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Vero deleniti quibusdam ex voluptas. Possimus autem facere natus a voluptas ad ipsum beatae
        expedita, nemo nisi vero impedit eveniet nulla. Voluptates?
    </span>
</CDBCollapse>
```


# API

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Collapse component. You will find out what these props do, their default values, and how you would use them in your code.

## API Reference: Contrast Collapse Bootstrap Inputs

The table below lists other prop options of the `CDBCollapse` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |     class="myClass" |
| delay          | Number or Object | {show: 350, hide: 350} | Defines how many milliseconds the open/close event are delayed | delay={show: 3000, hide: 7000} |
| navbar         | Boolean      | false        | Adds `navbar-collapse` bootstrap class to class name property    |     navbar=true |
| isOpen         | Boolean |         | Defines if accordion is opened or closed	      |     isOpen=true |
| onOpened       | function     |              | Defines the function which fires when Accordion has opened  |     onOpened={yourFunction} |
| onClosed       | function     |              | Defines the function which fires when Accordion has closed  |     onClosed={yourFunction} |
