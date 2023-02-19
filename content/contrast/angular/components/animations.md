---
title: "Animation"
metaTitle: "Angular Bootstrap Animation"
metaDescription: "Angular Bootstrap Animations are illusions of motions for web elements"
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/components/animations.md"
---

# Contrast Angular Bootstrap Animation

Contrast Angular Bootstrap Animations give the illusion of movement on web elements. Over 70+ animations were written in CSS and tested to have all browsers support.

## Importing the Contrast Angular Bootstrap Animation Module

```ts
import {AnimationModule } from 'cdbangular';
```

## Using the Contrast Angular Bootstrap Animation

Use the `type` prop to specify what type animation you want in your app, set the `[infinite]` prop to true to keep the animation going on forever.

![Angular Bootstrap Animation](./images/animation.gif)

###### HTML

```html
<CDBAnimation type="bounce" [infinite]=true>
    <img alt="Angular Bootstrap Animation Bounce" src="https://pngimg.com/uploads/football/football_PNG52775.png" width="50" height="50" />
</CDBAnimation>
<CDBAnimation type="flash" [infinite]=true>
    <img alt="Angular Bootstrap Animation Flash" src="https://pngimg.com/uploads/football/football_PNG52775.png" width="50" height="50" />
</CDBAnimation>
<CDBAnimation type="pulse" [infinite]=true>
    <img alt="Angular Bootstrap Animation Pulse" src="https://pngimg.com/uploads/football/football_PNG52775.png" width="50" height="50" />
</CDBAnimation>
<CDBAnimation type="rubberBand" [infinite]=true>
    <img alt="Angular Bootstrap Animation Rubberband" src="https://pngimg.com/uploads/football/football_PNG52775.png" width="50" height="50" />
</CDBAnimation>
<CDBAnimation type="shake" [infinite]=true>
    <img alt="Angular Bootstrap Animation Shake" src="https://pngimg.com/uploads/football/football_PNG52775.png" width="50" height="50" />
</CDBAnimation>
<CDBAnimation type="headShake" [infinite]=true>
    <img alt="Angular Bootstrap Animation HeadShake" src="https://pngimg.com/uploads/football/football_PNG52775.png" width="50" height="50" />
</CDBAnimation>
<CDBAnimation type="swing" [infinite]=true>
    <img alt="Angular Bootstrap Animation Swing" src="https://pngimg.com/uploads/football/football_PNG52775.png" width="50" height="50" />
</CDBAnimation>
<CDBAnimation type="tada" [infinite]=true>
    <img alt="Angular Bootstrap Animation Tada" src="https://pngimg.com/uploads/football/football_PNG52775.png" width="50" height="50" />
</CDBAnimation>
<CDBAnimation type="wobble" [infinite]=true>
    <img alt="Angular Bootstrap Animation Wobble" src="https://pngimg.com/uploads/football/football_PNG52775.png" width="50" height="50" />
</CDBAnimation>
<CDBAnimation type="jello" [infinite]=true>
    <img alt="Angular Bootstrap Animation Jello" src="https://pngimg.com/uploads/football/football_PNG52775.png" width="50" height="50" />
</CDBAnimation>
<CDBAnimation type="heartBeat" [infinite]=true>
    <img alt="Angular Bootstrap Animation HeartBeat" src="https://pngimg.com/uploads/football/football_PNG52775.png" width="50" height="50" />
</CDBAnimation>
```

# API

In this section you will find advanced information about the Animation component. You will find out which modules are required, what are the possibilities of configuring the component, and what events and methods you can use to work with it.

## API Reference: Contrast Angular Animation Properties

The table below shows the configuration options of the `CDBAnimation` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |     class="myClass" |
| infinite       | Boolean      | false        | Makes an animation loop endlessly. Note: it overwrites the `count` prop | infinite=true |
| type           | String       |              | This prop defines the kind of animation desired 	| type="tada" |
