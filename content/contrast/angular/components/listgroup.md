---
title: 'ListGroup'
metaTitle: 'Angular Bootstrap ListGroup'
metaDescription: 'Angular Bootstrap List group is a flexible component which displays not only simple list of elements but complex custom content'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/components/listgroup.md"
---# Contrast Angular Bootstrap ListGroup

Contrast Angular Bootstrap List group is a flexible component which displays not only simple list of elements but complex custom content.

## Importing the Contrast Angular Bootstrap ListGroup Module

To use the Contrast Angular Bootstrap ListGroup component in your project you need to import `ListGroupModule`.

```ts
import { ListgroupModule } from 'cdbangular';
```

## Default LIstGroup

The `CDBListGroupItem` component is a single list item in a `CDBListGroup`.

![Angular Bootstrap ListGroup Default](./images/listgroup1.png)

###### HTML

```html
<CDBListGroup style="width: 30rem">
  <CDBListGroupItem>List Group </CDBListGroupItem>
  <CDBListGroupItem>List Group</CDBListGroupItem>
  <CDBListGroupItem>List Group</CDBListGroupItem>
  <CDBListGroupItem>List Group</CDBListGroupItem>
  <CDBListGroupItem>List Group</CDBListGroupItem>
  <CDBListGroupItem>List Group</CDBListGroupItem>
</CDBListGroup>
```

## List Group as Link

Passing the `CDBLIstGroupItem` a `href` attribute makes the list group item act like an `a` tag.

![Angular Bootstrap ListGroup as Link](./images/listgroup2.png)

###### HTML

```html
<CDBListGroup style="width: 30rem">
  <CDBListGroupItem href="/" [active]="true">
    List Group
  </CDBListGroupItem>
  <CDBListGroupItem href="/" [hover]="true">
    List Group
  </CDBListGroupItem>
  <CDBListGroupItem href="/" [hover]="true">
    List Group
  </CDBListGroupItem>
  <CDBListGroupItem href="/" [hover]="true">
    List Group
  </CDBListGroupItem>
  <CDBListGroupItem href="/" [hover]="true">
    List Group Link
  </CDBListGroupItem>
  <CDBListGroupItem href="/" [hover]="true">
    List Group
  </CDBListGroupItem>
</CDBListGroup>
```

## Label

Use the [CDBBadge](https://www.devwares.com/docs/contrast/angular/components/badge) component to put labels in our list group.

![Angular Bootstrap ListGroup Label](./images/listgroup3.png)

###### HTML

```html
<CDBListGroup style="width: 30rem">
  <CDBListGroupItem class="d-flex justify-content-between align-items-center">
    List Group <CDBBadge color="primary">19</CDBBadge>
  </CDBListGroupItem>
  <CDBListGroupItem class="d-flex justify-content-between align-items-center">
    List Group
    <CDBBadge color="secondary">19</CDBBadge>
  </CDBListGroupItem>
  <CDBListGroupItem class="d-flex justify-content-between align-items-center">
    List Group
    <CDBBadge color="success">19</CDBBadge>
  </CDBListGroupItem>
  <CDBListGroupItem class="d-flex justify-content-between align-items-center">
    List Group
    <CDBBadge color="danger">19</CDBBadge>
  </CDBListGroupItem>
  <CDBListGroupItem class="d-flex justify-content-between align-items-center">
    List Group<CDBBadge color="info">19</CDBBadge>
  </CDBListGroupItem>
  <CDBListGroupItem class="d-flex justify-content-between align-items-center">
    List Group<CDBBadge color="warning">19</CDBBadge>
  </CDBListGroupItem>
</CDBListGroup>
```

## Color List Group

Use the `color` prop to give your list group a background color.

![Angular Bootstrap ListGroup Color](./images/listgroup4.png)

###### HTML

```html
<CDBListGroup style="width: 30rem">
  <CDBListGroupItem color="primary">List Group </CDBListGroupItem>
  <CDBListGroupItem color="secondary">List Group</CDBListGroupItem>
  <CDBListGroupItem color="success">List Group</CDBListGroupItem>
  <CDBListGroupItem color="danger">List Group</CDBListGroupItem>
  <CDBListGroupItem color="info">List Group Link</CDBListGroupItem>
  <CDBListGroupItem color="warning">List Group</CDBListGroupItem>
</CDBListGroup>
```

<i/>

## Icons

We nest the []() component in our `CDBListGrpupItem` to have icons in our list group.

![Angular Bootstrap ListGroup Icons](./images/listgroup5.png)

###### HTML

```html
<CDBListGroup style="width: 30rem">
  <CDBListGroupItem>
    <CDBIcon [fab]="true" icon="facebook" class="mr-3"></CDBIcon>
    List Group
  </CDBListGroupItem>
  <CDBListGroupItem>
    <CDBIcon [fab]="true" icon="facebook" size="2x" class="mr-3"></CDBIcon>
    List Group
  </CDBListGroupItem>
  <CDBListGroupItem>
    <CDBIcon [fab]="true" icon="facebook" size="2x" class="mr-3"></CDBIcon>
    List Group
  </CDBListGroupItem>
  <CDBListGroupItem>
    <CDBIcon [fab]="true" icon="facebook" size="2x" class="mr-3"></CDBIcon>
    List Group
  </CDBListGroupItem>
  <CDBListGroupItem>
    <CDBIcon [fab]="true" icon="facebook" size="2x" class="mr-3"></CDBIcon>
    List Group
  </CDBListGroupItem>
  <CDBListGroupItem>
    <CDBIcon [fab]="true" icon="facebook" size="2x" class="mr-3"></CDBIcon>
    List Group
  </CDBListGroupItem>
</CDBListGroup>
```

# API

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap ListGroup component. You will find out what these props do, their default values, and how you would use them in your code.

## API Reference: Contrast Angular Bootstrap ListGroup Props

The table below lists other prop options of the `CDBListGroup` component.

| Name  |  Type  | Default |     Description     |         Example |
| :---- | :----: | ------: | :-----------------: | --------------: |
| class | String |         | Adds custom classes | class="myClass" |

## API Reference: Contrast Angular Bootstrap LIstGroupItem Properties

The table below lists other prop options of the `CDBListGroupItem` component.

| Name    |  Type   | Default |                                                                   Description                                                                   |         Example |
| :------ | :-----: | ------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | --------------: |
| class   | String  |         |                                                               Adds custom classes                                                               | class="myClass" |
| active  | Boolean |   false |                                                        Adds default active state to item                                                        |     active=true |
| color   | String  |         | Changes Item background and text color, accepts `["primary", "default", "secondary", "success", "dark", "danger", "info", "warning", "white" ]` | color="primary" |
| disable | Boolean |   false |                                                        Disables item from being clicked                                                         |   disabled=true |
| hover   | Boolean |   false |                                              Adds hover effect (slightly background color change)                                               |      hover=true |
