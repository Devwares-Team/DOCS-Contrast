---
title: 'ButtonGroup'
metaTitle: 'Bootstrap 5 ButtonGroup - Bootstrap CSS tutorial'
metaDescription: 'A Bootstrap 5 button group is a vertical column that groups together a number of buttons into a single line or stack.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/buttonGroup.md"
---

# Bootstrap 5 ButtonGroup

A Bootstrap 5 ButtonGroup is a vertical column that bundles a set of buttons into a single line or stack.

Applications of Bootstrap 5 ButtonGroup:

- Group of pricing options
- Buying a a group of licenses from our PRO CDB website

## Basic Button Group

<ButtonGroup1/>

```html
<div class="btn-group">
  <button type="button" class="btn btn-primary">Left</button>
  <button type="button" class="btn btn-primary">Middle</button>
  <button type="button" class="btn btn-primary">Right</button>
</div>
```

## Basic Circular Group

<ButtonGroup2 />

```html
<div class="btn-group">
  <button type="button" class="btn btn-warning btn-rounded">Left</button>
  <button type="button" class="btn btn-success btn-rounded">Middle</button>
  <button type="button" class="btn btn-secondary btn-rounded">Right</button>
</div>
```

## Basic Button Group in Different Groups

<ButtonGroup3 />

```html
<div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-warning">Left</button>
  <button type="button" class="btn btn-success">Middle</button>
  <button type="button" class="btn btn-secondary">Right</button>
</div>

<div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-info">Left</button>
  <button type="button" class="btn btn-dark">Middle</button>
  <button type="button" class="btn btn-danger">Right</button>
</div>
```

<ButtonGroup4 />

## Vertical Button Group

Make a group of buttons appear vertically stacked instead of horizontally stacked.

```html
<div class="btn-group-vertical" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-primary">Click me</button>
  <button type="button" class="btn btn-secondary">Click me</button>
  <button type="button" class="btn btn-info">Click me</button>
  <button type="button" class="btn btn-success">Click me</button>
  <button type="button" class="btn btn-danger">Click me</button>
  <button type="button" class="btn btn-warning">Click me</button>
</div>
```

## Different Sizing for Button Groups

<ButtonGroup5 />

```html
<div class="btn-group btn-group-lg" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-dark">button</button>
  <button type="button" class="btn btn-dark">button</button>
  <button type="button" class="btn btn-dark">button</button>
</div>

<div class="btn-group" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-warning">button</button>
  <button type="button" class="btn btn-warning">button</button>
  <button type="button" class="btn btn-warning">button</button>
</div>

<div class="btn-group btn-group-sm" role="group" aria-label="Basic example">
  <button type="button" class="btn btn-dark">button</button>
  <button type="button" class="btn btn-dark">button</button>
  <button type="button" class="btn btn-dark">button</button>
</div>
```
