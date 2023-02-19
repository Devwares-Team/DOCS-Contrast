---
title: "Tab"
metaTitle: "Angular Bootstrap Tab"
metaDescription: "Angular Bootstrap Tabs are components which separate content placed in the same wrapper, but in the separate pane. Only one pane can be displayed at the time"
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/navigation/tabs.md"
---

# Contrast Angular Bootstrap Tab

Contrast Angular Bootstrap Tabs are components which separate content placed in the same wrapper, but in the separate pane. Only one pane can be displayed at the time.

Bootstrap tabs are components which separate content placed in the same wrapper, but in the separate pane. Only one pane can be displayed at the time. Tabs available in CDB share general markup and styles, as well as the `.nav`ed element managing the active and disabled states.


## Importing the Contrast Angular Bootstrap Tab Module

To use the Contrast Angular Bootstrap Tab component in your project you need to import `TabModule`.

```ts
import {TabModule } from 'cdbangular';
```

## Default Tab

![Angular Bootstrap Tab Default](https://imgur.com/PR8nMiM.gif)

###### HTML
```html
<CDBNav [tab]=true class="mt-5">
    <CDBTabLink link to="/tab" [active]="content.activeTab === '1'" (click)="content.setActiveTab('1')">
        Label 1
    </CDBTabLink>
    <CDBTabLink link to="/tab" [active]="content.activeTab === '2'" (click)="content.setActiveTab('2')">
        Label 2
    </CDBTabLink>
    <CDBTabLink link to="/tab" [active]="content.activeTab === '3'" (click)="content.setActiveTab('3')">
        Label 3
    </CDBTabLink>
</CDBNav>
<CDBTabContent #content="cdbTabContent" activeTab="1">
    <CDBTabPane tabId="1" [active]="content.activeTab === '1'">
        <p class="mt-2">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Nihil odit magnam minima, soluta doloribus reiciendis
            molestiae placeat unde eos molestias. Quisquam aperiam,
            pariatur. Tempora, placeat ratione porro voluptate odit
            minima.
        </p>
    </CDBTabPane>
    <CDBTabPane tabId="2" [active]="content.activeTab === '2'">
        <p class="mt-2">
            Quisquam aperiam, pariatur. Tempora, placeat ratione porro
            voluptate odit minima. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Nihil odit magnam minima,
            soluta doloribus reiciendis molestiae placeat unde eos
            molestias.
        </p>
        <p>
            Quisquam aperiam, pariatur. Tempora, placeat ratione porro
            voluptate odit minima. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Nihil odit magnam minima,
            soluta doloribus reiciendis molestiae placeat unde eos
            molestias.
        </p>
    </CDBTabPane>
    <CDBTabPane tabId="3" [active]="content.activeTab === '3'">
        <p class="mt-2">
            Quisquam aperiam, pariatur. Tempora, placeat ratione porro
            voluptate odit minima. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Nihil odit magnam minima,
            soluta doloribus reiciendis molestiae placeat unde eos
            molestias.
        </p>
    </CDBTabPane>
</CDBTabContent>
```

## Tab Justified

![Angular Bootstrap Tab Justified](https://imgur.com/JNq6N3p.gif)

###### HTML
```html
<CDBNav [tab]=true [justified]=true class="mt-5">
    <CDBTabLink link to="/tab" [active]="content2.activeTab === '1'" (click)="content2.setActiveTab('1')">
        Label 1
    </CDBTabLink>
    <CDBTabLink link to="/tab" [active]="content2.activeTab === '2'" (click)="content2.setActiveTab('2')">
        Label 2
    </CDBTabLink>
    <CDBTabLink link to="/tab" [active]="content2.activeTab === '3'" (click)="content2.setActiveTab('3')">
        Label 3
    </CDBTabLink>
</CDBNav>
<CDBTabContent #content2="cdbTabContent" activeTab="2">
    <CDBTabPane tabId="1" [active]="content2.activeTab === '1'">
        <p class="mt-2">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Nihil odit magnam minima, soluta doloribus reiciendis
            molestiae placeat unde eos molestias. Quisquam aperiam,
            pariatur. Tempora, placeat ratione porro voluptate odit
            minima.
        </p>
    </CDBTabPane>
    <CDBTabPane tabId="2" [active]="content2.activeTab === '2'">
        <p class="mt-2">
            Quisquam aperiam, pariatur. Tempora, placeat ratione porro
            voluptate odit minima. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Nihil odit magnam minima,
            soluta doloribus reiciendis molestiae placeat unde eos
            molestias.
        </p>
        <p>
            Quisquam aperiam, pariatur. Tempora, placeat ratione porro
            voluptate odit minima. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Nihil odit magnam minima,
            soluta doloribus reiciendis molestiae placeat unde eos
            molestias.
        </p>
    </CDBTabPane>
    <CDBTabPane tabId="3" [active]="content2.activeTab === '3'">
        <p class="mt-2">
            Quisquam aperiam, pariatur. Tempora, placeat ratione porro
            voluptate odit minima. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Nihil odit magnam minima,
            soluta doloribus reiciendis molestiae placeat unde eos
            molestias.
        </p>
    </CDBTabPane>
</CDBTabContent>
```


## Tab with Icons

![Angular Bootstrap Tab with Icons](https://imgur.com/VPYMDeL.gif)

###### HTML
```html
<CDBNav [tab]=true [justified]=true class="mt-5">
    <CDBTabLink link to="/tab" [active]="content3.activeTab === '1'" (click)="content3.setActiveTab('1')">
        <CDBIcon icon="bomb" class="mr-2"></CDBIcon>
        Label 1
    </CDBTabLink>
    <CDBTabLink link to="/tab" [active]="content3.activeTab === '2'" (click)="content3.setActiveTab('2')">
        <CDBIcon icon="bomb" class="mr-2"></CDBIcon>
        Label 2
    </CDBTabLink>
    <CDBTabLink link to="/tab" [active]="content3.activeTab === '3'" (click)="content3.setActiveTab('3')">
        <CDBIcon icon="bomb" class="mr-2"></CDBIcon>
        Label 3
    </CDBTabLink>
</CDBNav>
<CDBTabContent #content3="cdbTabContent" activeTab="3" class="mt-5" style="margin-top: 30px">
    <CDBTabPane tabId="1" [active]="content3.activeTab === '1'">
        <p class="mt-2">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Nihil odit magnam minima, soluta doloribus reiciendis
            molestiae placeat unde eos molestias. Quisquam aperiam,
            pariatur. Tempora, placeat ratione porro voluptate odit
            minima.
        </p>
    </CDBTabPane>
    <CDBTabPane tabId="2" [active]="content3.activeTab === '2'">
        <p class="mt-2">
            Quisquam aperiam, pariatur. Tempora, placeat ratione porro
            voluptate odit minima. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Nihil odit magnam minima,
            soluta doloribus reiciendis molestiae placeat unde eos
            molestias.
        </p>
        <p>
            Quisquam aperiam, pariatur. Tempora, placeat ratione porro
            voluptate odit minima. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Nihil odit magnam minima,
            soluta doloribus reiciendis molestiae placeat unde eos
            molestias.
        </p>
    </CDBTabPane>
    <CDBTabPane tabId="3" [active]="content3.activeTab === '3'">
        <p class="mt-2">
            Quisquam aperiam, pariatur. Tempora, placeat ratione porro
            voluptate odit minima. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Nihil odit magnam minima,
            soluta doloribus reiciendis molestiae placeat unde eos
            molestias.
        </p>
    </CDBTabPane>
</CDBTabContent>
```

## API Reference: Contrast Angular Bootstrap Tab Pane Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Tabs component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBTabPane` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              | Sets custom classes, use class `card` to achieve card-like effect (you can use Card subcomponents inside)	      |     class="card" |
| activeItem     | Any       |              |  	Active TabPane id - use this prop to control the component | activeItem="activeTab" |
| tabId          | Any       |              |  Indicates active pane	| tabId="Tab1" |
