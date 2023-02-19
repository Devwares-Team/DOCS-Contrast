---

title: 'Stepper'
metaTitle: 'Bootstrap 5 Stepper - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 Stepper is a component that shows content in the form of a process with user milestones. ootstrap stepper are useful in some many ways.'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/stepper.md"
---

<ProAlertJavaScript/>

# Bootstrap 5 Stepper

Bootstrap 5 Stepper is a component that shows content in the form of a process with user milestones. The steps that follow are separated and linked by buttons.

This is an excellent solution for a variety of registration forms in which you don't want to overwhelm the user with too many fields and queries.

The Contrast Bootstrap 5 Stepper can be positioned both vertically and horizontally. Bootstrap steppers are useful in many ways.

Examples of instances Bootstrap 5 stepper can be used include:

- Registration form
- Payment gateway
- Tutorial with steps

See the following Bootstrap 5 Stepper examples:

<i/>

# Add Script

We add dynamicity and interactivity to our stepper with JavaScript, we use `querySelector` to select an element. We then create a new stepper object using the `new` keyword from CDB, passing it the element we just targeted as an argument.

Each stepper instance can be created with the following javascript code snippet. This gives you access to the event handlers and listeners available for the stepper.

```html
<script>
  const stepper = document.querySelector('#stepper');
  new CDB.Stepper(stepper);
</script>
```

## Horizontal Stepper
This is the basic stepper component with an horizontally arranged content.
<stepperExample2 />

```html
<div height="800px" class="stepper" id="stepper">
  <div class="steps-container">
    <div class="steps">
      <div class="step" icon="fa fa-pencil-alt" id="1">
        <div class="step-title">
          <span class="step-number">01</span>
          <div class="step-text">Basic Information</div>
        </div>
      </div>
      <div class="step" icon="fa fa-info-circle" id="2">
        <div class="step-title">
          <span class="step-number">02</span>
          <div class="step-text">Personal Data</div>
        </div>
      </div>
      <div class="step" icon="fa fa-book-reader" id="3">
        <div class="step-title">
          <span class="step-number">03</span>
          <div class="step-text">Terms and Conditions</div>
        </div>
      </div>
      <div class="step" icon="fa fa-check" id="4">
        <div class="step-title">
          <span class="step-number">04</span>
          <div class="step-text">Finish</div>
        </div>
      </div>
    </div>
  </div>
  <div class="stepper-content-container">
    <div class="stepper-content fade-in" stepper-label="1">
      <div>Step 1</div>
    </div>
    <div class="stepper-content fade-in" stepper-label="2">
      <div>Step 2</div>
    </div>
    <div class="stepper-content fade-in" stepper-label="3">
      <div>Step 3</div>
    </div>
    <div class="stepper-content fade-in" stepper-label="4">
      <div>Step 4</div>
    </div>
  </div>
</div>
```

<i/>

## Vertical Stepper

<a href="/product/bootstrap-contrast-pro"><span class="badge badge-lg badge-pro">Pro Component</span></a>

Set the `direction` attribute of the stepper HTML elment to `vertical` to arrange its content vertically.

<stepperExample1 />

```html
<div direction="vertical" height="800px" class="stepper" id="stepper">
  <div class="steps-container">
    <div class="steps">
      <div class="step" icon="fa fa-pencil-alt" id="1">
        <div class="step-title">
          <span class="step-number">01</span>
          <div class="step-text">Basic Information</div>
        </div>
      </div>
      <div class="step" icon="fa fa-info-circle" id="2">
        <div class="step-title">
          <span class="step-number">02</span>
          <div class="step-text">Personal Data</div>
        </div>
      </div>
      <div class="step" icon="fa fa-book-reader" id="3">
        <div class="step-title">
          <span class="step-number">03</span>
          <div class="step-text">Terms and Conditions</div>
        </div>
      </div>
      <div class="step" icon="fa fa-check" id="4">
        <div class="step-title">
          <span class="step-number">04</span>
          <div class="step-text">Finish</div>
        </div>
      </div>
      <div class="step" icon="fa fa-pencil-alt" id="5">
        <div class="step-title">
          <span class="step-number">05</span>
          <div class="step-text">More</div>
        </div>
      </div>
    </div>
  </div>
  <div class="stepper-content-container">
    <div class="stepper-content fade-in" stepper-label="1">
      <div>Step 1</div>
    </div>
    <div class="stepper-content fade-in" stepper-label="2">
      <div>Step 2</div>
    </div>
    <div class="stepper-content fade-in" stepper-label="3">
      <div>Step 3</div>
    </div>
    <div class="stepper-content fade-in" stepper-label="4">
      <div>Step 4</div>
    </div>
  </div>
</div>
```

<i/>

## Stepper Without Icons and Headers

<a href="/product/bootstrap-contrast-pro"><span class="badge badge-lg badge-pro">Pro Component</span></a>

<stepperExample3 />

```html
<div height="800px" class="stepper" id="stepper">
  <div class="steps-container">
    <div class="steps">
      <div class="step" icon="fa fa-pencil-alt" id="1"></div>
      <div class="step" icon="fa fa-pencil-alt" id="2"></div>
      <div class="step" icon="fa fa-pencil-alt" id="3"></div>
      <div class="step" icon="fa fa-pencil-alt" id="4"></div>
    </div>
  </div>
  <div class="stepper-content-container">
    <div class="stepper-content fade-in" stepper-label="1">
      <div>Step 1</div>
    </div>
    <div class="stepper-content fade-in" stepper-label="2">
      <div>Step 2</div>
    </div>
    <div class="stepper-content fade-in" stepper-label="3">
      <div>Step 3</div>
    </div>
    <div class="stepper-content fade-in" stepper-label="4">
      <div>Step 4</div>
    </div>
  </div>
</div>
```


## Classes and Events Reference: Contrast Bootstrap Stepper

This section will build on your information about the classes and events that makes Contrast Bootstrap stepper tick. You will find out what they do, their default values, and how you would use them in your code.

The table below lists css classes options for `Contrast Bootstrap Stepper`

| Name                        |                       Description                       |
| :-------------------------- | :-----------------------------------------------------: |
| `stepper`                   |               Wrapper styles for stepper                |
| `step-container`            | Defines styles for the container of the stepper content |
| `steps`                     |              Defines styles for steps list              |
| `step`                      |              Defines styles for each steps              |
| `stepper-content-container` |    Defines styles for the stepper content container     |
| `stepper-content`           |         Defines styles for each stepper content         |

## Attributes Reference: Contrast Bootstrap Stepper

These are attributes that control styles and properties of the stepper

| Name          |            Description             |                      Example                      |
| :------------ | :--------------------------------: | :-----------------------------------------------: |
| height        | Defines maximum height of stepper  |      `<div class="stepper" height='800px'>`       |
| icon          |     Defines icon for each step     |       `<div class="step" icon='fa-check'>`        |
| id            |      Defines id for each step      |            `<div class="step" id='5'>`            |
| stepper-label | Links stepper content item to step | `<div class="stepper-content" stepper-label='5'>` |

## Events Reference: Contrast Bootstrap Stepper

These are events you can call on the Contrast Bootstrap Stepper instance

| Name     |                                       Description                                        |                                  Example                                   |
| :------- | :--------------------------------------------------------------------------------------: | :------------------------------------------------------------------------: |
| navigate | This functions receives an id and navigates to the item on the stepper that has that id. | `const stepper = document.querySelector('.stepper')` `stepper.navigate(1)` |