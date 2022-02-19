---

title: 'Stepper'
metaTitle: 'Bootstrap 5 Stepper - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 Stepper is a component that shows content in the form of a process with user milestones. ootstrap stepper are useful in some many ways.'
---# Bootstrap 5 Stepper

Bootstrap 5 Stepper is a component that shows content in the form of a process with user milestones. The steps that follow are separated and linked by buttons.

This is an excellent solution for a variety of registration forms in which you don't want to overwhelm the user with too many fields and queries.

The Contrast Bootstrap 5 Stepper can be positioned both vertically and horizontally. Bootstrap stepper are useful in some many ways.

Examples of places Bootstrap 5 stepper can be used include:

- Registration form
- Payment gateway
- Tutorial with steps

See the following Bootstrap 5 stepper examples:

<i/>

## Basic Vertical Stepper

![Bootstrap Stepper Vertical](https://i.imgur.com/khiy8Dd.gif)

###### html

```html
        <div id="stepper4" class="stepper vertical">
          <div class="stepper-header" role="tablist">
            <div class="step" data-target="#test-vl-1">
              <button
                type="button"
                class="step-trigger"
                role="tab"
                id="stepper4trigger1"
                aria-controls="test-vl-1"
              >
                <span class="stepper-circle">1</span>
                <span class="stepper-label">Email</span>
              </button>
            </div>
            <div class="stepper-line"></div>
            <div class="step" data-target="#test-vl-2">
              <button
                type="button"
                class="step-trigger"
                role="tab"
                id="stepper4trigger2"
                aria-controls="test-vl-2"
              >
                <span class="stepper-circle">2</span>
                <span class="stepper-label">Password</span>
              </button>
            </div>
            <div class="stepper-line"></div>
            <div class="step" data-target="#test-vl-3">
              <button
                type="button"
                class="step-trigger"
                role="tab"
                id="stepper4trigger3"
                aria-controls="test-vl-3"
              >
                <span class="stepper-circle">3</span>
                <span class="stepper-label">Validate</span>
              </button>
            </div>
          </div>
          <div class="stepper-content">
            <form onSubmit="return false">
              <div
                id="test-vl-1"
                role="tabpanel"
                class="stepper-pane fade"
                aria-labelledby="stepper4trigger1"
              >
                <div class="form-group">
                  <label for="exampleInputEmailV1">Email address</label>
                  <input
                    type="email"
                    class="form-control"
                    id="exampleInputEmailV1"
                    placeholder="Enter email"
                  />
                </div>
                <button class="btn btn-primary" onclick="stepper4.next()">
                  Next
                </button>
              </div>
              <div
                id="test-vl-2"
                role="tabpanel"
                class="stepper-pane fade"
                aria-labelledby="stepper4trigger2"
              >
                <div class="form-group">
                  <label for="exampleInputPasswordV1">Password</label>
                  <input
                    type="password"
                    class="form-control"
                    id="exampleInputPasswordV1"
                    placeholder="Password"
                  />
                </div>
                <button class="btn btn-primary" onclick="stepper4.previous()">
                  Previous
                </button>
                <button class="btn btn-primary" onclick="stepper4.next()">
                  Next
                </button>
              </div>
              <div
                id="test-vl-3"
                role="tabpanel"
                class="stepper-pane fade"
                aria-labelledby="stepper4trigger3"
              >
                <button
                  class="btn btn-primary mt-5"
                  onclick="stepper4.previous()"
                >
                  Previous
                </button>
                <button type="submit" class="btn btn-primary mt-5">
                  Submit
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
```

## Linear Stepper

![Bootstrap Stepper Linear](https://i.imgur.com/eQMikuS.gif)

###### html

```html
<div id="stepper1" class="stepper" style="width: 100%">
  <div class="stepper-header" role="tablist">
    <div class="step" data-target="#stepper-form-1">
      <button type="button" class="step-trigger" onclick="stepper1.to(1)">
        <span class="stepper-circle">1</span>
      </button>
    </div>
    <div class="stepper-line"></div>
    <div class="step" data-target="#stepper-form-2">
      <button type="button" class="step-trigger" onclick="stepper1.to(2)">
        <span class="stepper-circle">2</span>
      </button>
    </div>
    <div class="stepper-line"></div>
    <div class="step" data-target="#stepper-form-3">
      <button type="button" class="step-trigger">
        <span class="stepper-circle">3</span>
      </button>
    </div>
  </div>
  <div class="stepper-content">
    <form onSubmit="return false">
      <div
        id="stepper-form-1"
        role="tabpanel"
        class="stepper-pane"
        aria-labelledby="stepper1trigger1"
      >
        <div class="cs-form form-sm">
          <input type="email" class="form-control" />
          <label>Email</label>
        </div>
        <button class="mt-3 btn btn-dark btn-flat" onclick="stepper1.next()">
          Next
        </button>
      </div>
      <div
        id="stepper-form-2"
        role="tabpanel"
        class="stepper-pane"
        aria-labelledby="stepper1trigger2"
      >
        <div class="cs-form form-sm">
          <input type="password" class="form-control" />
          <label>Password</label>
        </div>
        <button class="mt-3 btn btn-dark btn-flat" onclick="stepper1.previous()">
          Previous
        </button>
        <button class="mt-3 btn btn-dark btn-flat" onclick="stepper1.next()">
          Next
        </button>
      </div>
      <div
        id="stepper-form-3"
        role="tabpanel"
        class="stepper-pane text-center"
        aria-labelledby="stepper1trigger3"
      >
        <div class="form-sm">
          <h4>Thanks for sunscribing. Have a nice day</h4>
        </div>
        <button class="mt-3 btn btn-dark btn-flat" onclick="stepper1.previous()">
          Previous
        </button>
        <button type="submit" class="mt-3 btn btn-dark btn-flat">
          Submit
        </button>
      </div>
    </form>
  </div>
</div>
```

## Non Linear Stepper

![Bootstrap Stepper Non Linear ](./images/stepper.png)

###### html

```html
<div id="stepper3" class="stepper">
  <div class="stepper-header" role="tablist">
    <div class="step" data-target="#test-nlf-1">
      <button
        type="button"
        class="step-trigger"
        role="tab"
        id="stepper3trigger1"
        aria-controls="test-nlf-1"
      >
        <span class="stepper-circle">
          <span class="fas fa-user" aria-hidden="true"></span>
        </span>
        <span class="stepper-label">Name</span>
      </button>
    </div>
    <div class="stepper-line"></div>
    <div class="step" data-target="#test-nlf-2">
      <button
        type="button"
        class="step-trigger"
        role="tab"
        id="stepper3trigger2"
        aria-controls="test-nlf-2"
      >
        <span class="stepper-circle">
          <span class="fas fa-map-marked" aria-hidden="true"></span>
        </span>
        <span class="stepper-label">Address</span>
      </button>
    </div>
    <div class="stepper-line"></div>
    <div class="step" data-target="#test-nlf-3">
      <button
        type="button"
        class="step-trigger"
        role="tab"
        id="stepper3trigger3"
        aria-controls="test-nlf-3"
      >
        <span class="stepper-circle">
          <span class="fas fa-save" aria-hidden="true"></span>
        </span>
        <span class="stepper-label">Submit</span>
      </button>
    </div>
  </div>
  <div class="stepper-content">
    <form onSubmit="return false">
      <div
        id="test-nlf-1"
        role="tabpanel"
        class="stepper-pane fade"
        aria-labelledby="stepper3trigger1"
      >
        <div class="form-group">
          <label for="exampleInputName2">Name</label>
          <input
            type="email"
            class="form-control"
            id="exampleInputName2"
            placeholder="Enter your name"
          />
        </div>
        <button class="btn btn-primary" onclick="stepper3.next()">
          Next
        </button>
      </div>
      <div
        id="test-nlf-2"
        role="tabpanel"
        class="stepper-pane fade"
        aria-labelledby="stepper3trigger2"
      >
        <div class="form-group">
          <label for="exampleInpuAddress2">Address</label>
          <input
            type="email"
            class="form-control"
            id="exampleInpuAddress2"
            placeholder="Enter your address"
          />
        </div>
        <button class="btn btn-primary" onclick="stepper3.next()">
          Next
        </button>
      </div>
      <div
        id="test-nlf-3"
        role="tabpanel"
        class="stepper-pane fade text-center"
        aria-labelledby="stepper3trigger3"
      >
        <button type="submit" class="btn btn-primary mt-5">
          Submit
        </button>
      </div>
    </form>
  </div>
</div>
```

###### Script

```javascript
    <script
      src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
      integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
      crossorigin="anonymous"
    ></script>
    <script src="../build/cdbbootstrap.js"></script>
    <script>
      const stepper1 = new CDB.Stepper(document.querySelector('#stepper1'));
      const stepper2 = new CDB.Stepper(document.querySelector('#stepper2'), {
        linear: false,
      });
      const stepper3 = new CDB.Stepper(document.querySelector('#stepper3'), {
        linear: false,
        animation: true,
      });
      const stepper4 = new CDB.Stepper(document.querySelector('#stepper4'));
    </script>
```
