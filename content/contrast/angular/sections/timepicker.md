---
title: "TimePicker"
metaTitle: "Angular Bootstrap TimePicker"
metaDescription: "Angular Bootstrap material time picker is a component which uses a dialog to select a single time in `hours:minutes` format. The selected time is indicated by the filled circle at the end of the clock hand"
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/sections/timepicker.md"
---

# Contrast Angular Bootstrap TimePicker

Contrast Angular Bootstrap material time picker is a component which uses a dialog to select time in `hours:minutes` format. The selected time is indicated by the filled circle at the end of the clock hand.


## Importing the Contrast Angular Bootstrap TimePicker Module

To use the Contrast Angular Bootstrap TimePicker component in your project you need to import `TimePickerModule`.

```ts
import {TimePickerModule } from 'cdbangular';
```

## Default TimePicker.

![Angular Bootstrap TimePicker Default](./images/timepicker.png)

###### HTML

```html
<CDBTimepicker placeholder="10:05 AM" theme="SoundCloud" colorPalette="dark"></CDBTimepicker>
```

## API Reference: Contrast Angular Bootstrap TimePicker Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap TimePicker component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBTimePicker` component.

| Name         |  Type   |             Default |                                       Description                                       |                   Example |
| :----------- | :-----: | ------------------: | :-------------------------------------------------------------------------------------: | ------------------------: |
| placeholder  | String  |                     |                  `Required!` Sets placeholder for time indicator input                  | placeholder="placeholder" |
| time         | String  |                     |                                      Sets the time                                      |        time="09:30:30 AM" |
| class        | String  | Adds custom classes |                                   Adds custom classes                                   |           class="myClass" |
| theme        | String  |                     | Sets the theme of the time picker. Can be either `material`, `classic` or `neomorphism` |           theme="classic" |
| colorPalette | String  |               light |      Changes the color palette of the time picker. Can be either `light` or `dark`      |       colorPalette="dark" |
| disable      | Boolean |               false |                              Disables TimePicker component                              |        [disabled] = false |
