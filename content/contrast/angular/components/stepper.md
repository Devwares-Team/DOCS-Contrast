---
title: "Stepper"
metaTitle: "Angular Bootstrap Stepper"
metaDescription: "Angular Bootstrap Stepper is a component that displays content as a process with defined by user milestones. Following steps are separated and connected by buttons"
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/components/stepper.md"
---

# Contrast Angular Bootstrap Stepper

Contrast Angular Bootstrap Stepper is a component that displays content as a process defined by user milestones. The steps are separated and linked by buttons.

This is a great solution for forms, where you don't want to overwhelm users with loads of fields and questions.

Stepper can be aligned vertically as well as horizontally.

Examples of Angular Bootstrap steps use:

* Registration form
* Payment gateway
* Tutorial with steps

See the following Bootstrap Angular stepper examples:


## Importing the Contrast Angular Bootstrap Stepper Module

To use the Contrast Angular Bootstrap Stepper component in your project you need to import `StepperModule`.

```ts
import {StepperModule } from 'cdbangular';
```

## Basic Vertical Stepper

Use the Contrast Angular Bootstrap `CDBStepper` component to create steppers in your project. We also use the `CDBStep` component alongside it. The `CDBStep` component is nested in the `CDBStepper` component. They indicate the various stages in the progression.

The `CDBStepper` takes in a `direction` prop, which specifies the orientation of your stepper.

Alongside our `CDBStepper`, we also import [CDBIcon](https://www.devwares.com/docs/contrast/angular/components/icon) for our icons, [CDBInput](https://www.devwares.com/docs/contrast/angular/components/input) for the input fields, and the [CDBButton](https://www.devwares.com/docs/contrast/angular/components/buttons) for our buttons.

![Angular Bootstrap Vertical Stepper Default](https://i.imgur.com/khiy8Dd.gif)

###### HTML
```html
<div class="container" style=" height: 500px; width:50px">
    <CDBStepper direction="vertical">
        <CDBStep [id]=1 [far]=true [active]='active' icon="folder-open" (onClick)='handleNextPrevClick(1,1)'
            name="Basic Information"></CDBStep>
        <CDBStep [id]=2 icon="pencil-alt" [active]='active' name="Personal Data"
            (onClick)='handleNextPrevClick(1,2)'>
        </CDBStep>
        <CDBStep [id]=3 icon="dragon" [active]='active' name="Terms and Conditions"
            (onClick)='handleNextPrevClick(1,3)'></CDBStep>
        <CDBStep [id]=4 icon="check" [active]='active' name="Finish" (onClick)='handleNextPrevClick(1,4)'>
        </CDBStep>
    </CDBStepper>
</div>
<div class="container" style="height:500px; width: 100%; display:flex; align-items: center">
    <div *ngIf='active === 1' md="12" class="container">
        <h3 class="font-weight-bold pl-0 my-4 " style="width: 100%; font-size: 30px; text-align: center">
            Your Information
        </h3>
        <CDBInput label="Email" class="mt-4"></CDBInput>
        <CDBInput label="username" class="mt-4"></CDBInput>
        <CDBInput label="Password" class="mt-4"></CDBInput>
        <CDBInput label="Repeat Password" class="mt-4"></CDBInput>
        <CDBBtn color="dark" [block]=true [flat]=true class="float-right" (click)='handleNextPrevClick(2)'>
            Next
        </CDBBtn>
    </div>
    <div *ngIf='active === 2' md="12" class="container">
        <h3 class="font-weight-bold pl-0 my-4" style="
              width: 100%;
              font-size: 30px;
              text-align: center">
            Personal Data
        </h3>
        <CDBInput label="First Name" class="mt-3"></CDBInput>
        <CDBInput label="Second Name" class="mt-3"></CDBInput>
        <CDBInput label="Surname" class="mt-3"></CDBInput>
        <CDBInput label="Address" type="textarea" rows="2"></CDBInput>
        <CDBBtn color="light" [flat]=true class="float-left" (click)='handleNextPrevClick(1)'>
            Previous
        </CDBBtn>
        <CDBBtn color="dark" [flat]=true class="float-right" (click)='handleNextPrevClick(3)'>
            Next
        </CDBBtn>
    </div>
    <div *ngIf='active === 3' md="12" class="container">
        <h3 class="font-weight-bold pl-0 my-4" style="
              width: 100%;
              font-size: 30px;
              text-align:center">
            Terms and conditions
        </h3>
        <CDBInput label="I agreee to the terms and conditions" type="checkbox" id="checkbox3"></CDBInput>
        <CDBInput label="I want to receive newsletter" type="checkbox" id="checkbox4"></CDBInput>
        <CDBBtn color="light" class="float-left" [flat]=true (click)='handleNextPrevClick(2)'>
            Previous
        </CDBBtn>
        <CDBBtn color="dark" class="float-right" [flat]=true (click)='handleNextPrevClick(4)'>
            Next
        </CDBBtn>
    </div>
    <div *ngIf='active === 4' md="12" class="container">
        <h3 class="font-weight-bold pl-0 my-4" style="
              width: 100%;
              font-size: 30px;
              text-align: center">
            Finish
        </h3>
        <h2 class="text-center font-weight-bold my-4">
            Registration completed!
        </h2>
        <CDBBtn color="light" [flat]=true class="float-left" (click)='handleNextPrevClick(3)'>
            Previous
        </CDBBtn>
        <CDBBtn color="success" [flat]=true class="float-right" (click)='handleSubmission()'>
            submit
        </CDBBtn>
    </div>
```
###### TypeScript
```ts
import { Component, OnInit } from '@angular/core';

@Component({
  selector: 'app-stepper',
  templateUrl: './stepper.component.html',
  styleUrls: ['./stepper.component.scss'],
})
export class StepperComponent implements OnInit {
  active = 1;
  active2 = 1;

  handleNextPrevClick(stepper, a) {
    if (stepper === 1) {
      this.active = a;
    } else if (stepper === 2) {
      this.active2 = a;
    }
  }

  handleSubmission = () => {
    alert('Form submitted!');
  };

  constructor() {}

  ngOnInit(): void {}
}
```

## Basic Horizontal Stepper


![Angular Bootstrap Stepper Horizontal](https://i.imgur.com/eQMikuS.gif)

###### HTML
```html
<div class="container" style="width:100%">
    <CDBStepper style="width:100%" direction="horizontal">
        <CDBStep [id]=1 [far]=true icon="folder-open" name="Basic Information"
            (onClick)='handleNextPrevClick(2,1)' [active]='active2'></CDBStep>
        <CDBStep [id]=2 icon="pencil-alt" name="Personal Data" (onClick)='handleNextPrevClick(2,2)'
            [active]='active2'>
        </CDBStep>
        <CDBStep [id]=3 icon="dragon" name="Terms and Conditions" (onClick)='handleNextPrevClick(2,3)'
            [active]='active2'></CDBStep>
        <CDBStep [id]=4 icon="check" name="Finish" (onClick)='handleNextPrevClick(2,4)' [active]='active2'>
        </CDBStep>
    </CDBStepper>
</div>
<div class="container" style="
        height: 500px;
        width: 100%;
        display:flex;
        align-items: center">
    <div *ngIf='active2 === 1' class="container" md="12">
        <h3 class="font-weight-bold pl-0 my-4 d-flex justify-content-center" style="
              width: 100%;
              font-size: 30px;
              text-align: center">
            Your Information
        </h3>
        <CDBInput label="Email" class="mt-4"></CDBInput>
        <CDBInput label="username" class="mt-4"></CDBInput>
        <CDBInput label="Password" class="mt-4"></CDBInput>
        <CDBInput label="Repeat Password" class="mt-4"></CDBInput>
        <CDBBtn color="dark" [block]=true [flat]=true class="float-right" (click)='handleNextPrevClick(2)'>
            Next
        </CDBBtn>
    </div>
    <div *ngIf='active2 === 2' class="container" md="12">
        <h3 class="font-weight-bold pl-0 my-4" style="
              width: 100%;
              font-size: 30px;
              text-align: center">
            Personal Data
        </h3>
        <CDBInput label="First Name" class="mt-3"></CDBInput>
        <CDBInput label="Second Name" class="mt-3"></CDBInput>
        <CDBInput label="Surname" class="mt-3"></CDBInput>
        <CDBInput label="Address" type="textarea" rows="2"></CDBInput>
        <CDBBtn color="light" [flat]=true class="float-left" (click)='handleNextPrevClick(1)'>
            Previous
        </CDBBtn>
        <CDBBtn color="dark" [flat]=true class="float-right" (click)='handleNextPrevClick(3)'>
            Next
        </CDBBtn>
    </div>
    <div *ngIf='active2 === 3' class="container" md="12">
        <h3 class="font-weight-bold pl-0 my-4" style="
              width: 100%;
              font-size: 30px;
              text-align: center">
            Terms and conditions
        </h3>
        <CDBInput label="I agreee to the terms and conditions" type="checkbox" id="checkbox3"></CDBInput>
        <CDBInput label="I want to receive newsletter" type="checkbox" id="checkbox4"></CDBInput>
        <CDBBtn color="light" class="float-left" [flat]=true (click)='handleNextPrevClick(2)'>
            Previous
        </CDBBtn>
        <CDBBtn color="dark" class="float-right" [flat]=true (click)='handleNextPrevClick(4)'>
            Next
        </CDBBtn>
    </div>
    <div *ngIf='active2 === 4' class="container" md="12">
        <h3 class="font-weight-bold pl-0 my-4" style="
              width: 100%;
              font-size: 30px;
              text-align: center">
            Finish
        </h3>
        <h2 class="text-center font-weight-bold my-4">
            Registration completed!
        </h2>
        <CDBBtn color="light" [flat]=true class="float-left" (click)='handleNextPrevClick(3)'>
            Previous
        </CDBBtn>
        <CDBBtn color="success" [flat]=true class="float-right" (click)='handleSubmission()'>
            submit
        </CDBBtn>
    </div>
```
###### TypeScript
```ts
import { Component, OnInit } from '@angular/core';

@Component({
  selector: 'app-stepper',
  templateUrl: './stepper.component.html',
  styleUrls: ['./stepper.component.scss'],
})
export class StepperComponent implements OnInit {
  active = 1;
  active2 = 1;

  handleNextPrevClick(stepper, a) {
    if (stepper === 1) {
      this.active = a;
    } else if (stepper === 2) {
      this.active2 = a;
    }
  }

  handleSubmission = () => {
    alert('Form submitted!');
  };

  constructor() {}

  ngOnInit(): void {}
}
```

## Stepper Without Icons


![Angular Bootstrap Stepper Without icons](./images/stepper.png)

###### HTML
```html
<CDBStepper style="width:100%" direction="horizontal">
    <CDBStep name="Label 1" id={1}></CDBStep>
    <CDBStep name="Label 2" id={2}></CDBStep>
    <CDBStep name="Label 3" id={3}></CDBStep>
    <CDBStep name="Label 4" id={4}></CDBStep>
</CDBStepper>
```
###### TypeScript
```ts
import { Component, OnInit } from '@angular/core';

@Component({
  selector: 'app-stepper',
  templateUrl: './stepper.component.html',
  styleUrls: ['./stepper.component.scss'],
})
export class StepperComponent implements OnInit {
  active = 1;
  active2 = 1;

  handleNextPrevClick(stepper, a) {
    if (stepper === 1) {
      this.active = a;
    } else if (stepper === 2) {
      this.active2 = a;
    }
  }

  handleSubmission = () => {
    alert('Form submitted!');
  };

  constructor() {}

  ngOnInit(): void {}
}
```

## API Reference: Contrast Angular Bootstrap Stepper Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Stepper component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBStepper`.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| direction      | String       | horizontal   | `Required!` Controls the orientation of generated stepper. Can be either `vertical` or `horizontal`     |     direction="vertical" |
