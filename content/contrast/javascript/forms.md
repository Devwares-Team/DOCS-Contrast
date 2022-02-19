---
title: 'Forms'
metaTitle: 'Bootstrap 5 Forms - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 forms are input-based components that are used to collect information from users.'
---

# Bootstrap 5 Forms

Bootstrap 5 forms are input-based components that are used to collect information from users. All of these forms, whether used as a login, subscription, or contact form, may be readily altered.

We were conscious of their importance in practically every project while developing Contrast Design Bootstrap, thus we put a lot of effort into getting them correct.

Predefined Form logins, Form registers, Form subscriptions, Form contacts, and other layout forms in a variety of designs are all available to you. Each of them has an own set of capabilities.

## Default Form Login

![Default Form Login](./images/1.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center mt-4 mb-4">
        <p class="h4">Sign in</p>
      </div>
      <div class="cdb-form">
        <input type="email" class="form-control border-top-0 border-left-0 border-right-0" />
        <label>E-mail</label>
      </div>
      <div class="cdb-form">
        <input type="password" class="form-control border-top-0 border-left-0 border-right-0" />
        <label>Password</label>
      </div>
      <div class="d-flex flex-wrap justify-content-center align-items-center">
        <input type="checkbox" class="mr-1" />
        <p class="m-0">Remember me</p>
        <span class="text-primary ml-3" href="#">Forgot Password ?</span>
      </div>
      <button class="btn btn-dark btn-block my-3">
        Sign in
      </button>
      <p class="text-center">Not a member? <span class="text-primary" href="#">Register</span></p>
      <p class="text-center">or sign in with</p>
      <div class="my-3 d-flex justify-content-center">
        <button class="m-0 btn btn-flat">
          <i class="fab fa-facebook-f"></i>
        </button>
        <button class="m-0 btn btn-flat">
          <i class="fab fa-twitter"></i>
        </button>
        <button class="m-0 btn btn-flat">
          <i class="fab fa-google-plus-g"></i>
        </button>
      </div>
    </div>
  </div>
</div>
```

## Contrast Form Login

![Bootstrap Form Login](./images/2.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div style="background:black;" class="text-center text-white">
      <p class="h5 mt-2 py-4 font-weight-bold">Sign in</p>
    </div>
    <div class="mx-4 mt-4 p-3">
      <div class="cdb-form">
        <input type="email" class="form-control" />
        <label>E-mail</label>
      </div>
      <div class="cdb-form">
        <input type="password" class="form-control" />
        <label>Password</label>
      </div>
      <div class="mt-5 d-flex flex-wrap justify-content-center align-items-center">
        <input type="checkbox" class="mr-2" />
        <p class="m-0">Remember me</p>
        <span href="#" class="text-primary ml-3">Forgot Password ?</span>
      </div>
      <button class="btn btn-block btn-outline-dark my-3">
        Sign in
      </button>
      <p class="text-center">Not a member? <span class="text-primary" href="#">Register</span></p>
      <p class="text-center">or sign in with</p>
      <div class="my-3 d-flex justify-content-center">
        <button class="btn m-0">
          <i class="fab fa-facebook-f"></i>
        </button>
        <button class="btn m-0">
          <i class="fab fa-twitter"></i>
        </button>
        <button class="btn m-0">
          <i class="fab fa-linkedin-in"></i>
        </button>
        <button class="btn m-0">
          <i class="fab fa-github"></i>
        </button>
      </div>
    </div>
  </div>
</div>
```

## Default Form Register

![Bootstrap Form Register](./images/3.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center mt-4 mb-2">
        <p class="h4 mb-5">Sign up</p>
      </div>
      <div class="row mb-n4">
        <div class="col">
          <div class="cdb-form">
            <input type="email" class="form-control border-top-0 border-left-0 border-right-0" />
            <label>First Name</label>
          </div>
        </div>
        <div class="col">
          <div class="cdb-form">
            <input type="text" class="form-control border-top-0 border-left-0 border-right-0" />
            <label>Last Name</label>
          </div>
        </div>
        <div class="cdb-form">
          <input type="email" class="form-control border-top-0 border-left-0 border-right-0" />
          <label>E-mail</label>
        </div>
        <div class="cdb-form">
          <input type="password" class="form-control border-top-0 border-left-0 border-right-0" />
          <label>Password</label>
        </div>
        <p class="text-muted text-center small">At least 8 characters and 1 digit</p>
        <div class="cdb-form">
          <input type="text" class="form-control border-top-0 border-left-0 border-right-0" />
          <label>Phone number</label>
        </div>
        <p class="text-muted text-center small">Optional - for two step authentication</p>
      </div>
      <div class="d-flex justify-content-center align-items-center mt-4">
        <input class="mr-2" type="checkbox" />
        <p class="m-0">Subscribe to our newsletter</p>
      </div>
      <button class="btn btn-block my-3 btn-dark">
        Sign up
      </button>
      <p class="text-center">or sign up with</p>
      <div class="mb-3 d-flex justify-content-center">
        <button class="m-0 btn btn-flat">
          <i class="fab fa-facebook-f"></i>
        </button>
        <button class="m-0 btn btn-flat">
          <i class="fab fa-twitter"></i>
        </button>
        <button class="m-0 btn btn-flat">
          <i class="fab fa-google-plus-g"></i>
        </button>
      </div>
      <p class="text-center m-0">
        Already have an account? <span class="text-primary" href="#">Sign In</span>
      </p>
      <hr />
      <p class="text-center">
        By clicking <em>Sign up</em> you agree to our
        <span class="text-primary" href="#">terms of service</span>
      </p>
    </div>
  </div>
</div>
```

## Contrast Form Register

![Bootstrap Form Register](./images/4.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="text-center text-white" style="background:black;">
      <p class="h5 mt-2 py-4 font-weight-bold">Sign up</p>
    </div>
    <div class="mx-4 mt-4 p-3">
      <div class="row mb-n4">
        <div class="col">
          <div class="cdb-form">
            <input type="email" class="form-control" />
            <label>First Name</label>
          </div>
        </div>
        <div class="col">
          <div class="cdb-form">
            <input type="text" class="form-control" />
            <label>Last Name</label>
          </div>
        </div>
        <div class="cdb-form">
          <input type="email" class="form-control" />
          <label>E-mail</label>
        </div>
        <div class="cdb-form">
          <input type="password" class="form-control" />
          <label>Password</label>
        </div>
        <p class="text-muted text-center small mt-n3">At least 8 characters and 1 digit</p>
        <div class="cdb-form">
          <input type="text" class="form-control" />
          <label>Phone number</label>
        </div>
        <p class="text-muted text-center small mt-n3">Optional - for two step authentication</p>
      </div>
      <div class="d-flex justify-content-center align-items-center mt-4">
        <input class="mr-2" type="checkbox" />
        <p class="m-0">Subscribe to our newsletter</p>
      </div>
      <button class="btn btn-block my-3 btn-outline-dark">
        Sign up
      </button>
      <p class="text-center">or sign up with</p>
      <div class="mb-3 d-flex justify-content-center">
        <button class="m-0 btn">
          <i class="fab fa-facebook-f"></i>
        </button>
        <button class="m-0 btn">
          <i class="fab fa-twitter"></i>
        </button>
        <button class="m-0 btn">
          <i class="fab fa-linkedin-in"></i>
        </button>
        <button class="m-0 btn">
          <i class="fab fa-github"></i>
        </button>
      </div>
      <p class="text-center m-0">
        Already have an account? <span class="text-primary" href="#">Sign In</span>
      </p>
      <hr />
      <p class="text-center">
        By clicking <em>Sign up</em> you agree to our
        <span class="text-primary" href="#">terms of service</span>
      </p>
    </div>
  </div>
</div>
```

## Default Form Subscription

![Bootstrap Form Subscription](./images/5.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center mt-4 mb-2">
        <p class="h4">Subscribe</p>
      </div>
      <p class="text-center mt-4 font-weight-light">
        Join our mailing list. We write rarely, but only the best content.
      </p>
      <p class="text-center">
        <span class="font-weight-light text-primary mb-4" href="#">See the last newsletter</span>
      </p>
      <div class="cdb-form">
        <input type="text" class="form-control border-top-0 border-left-0 border-right-0" />
        <label>Name</label>
      </div>
      <div class="cdb-form">
        <input type="email" class="form-control border-top-0 border-left-0 border-right-0" />
        <label>E-mail</label>
      </div>
      <button class="btn btn-dark btn-block my-3">
        Subscribe
      </button>
    </div>
  </div>
</div>
```

## Contrast Form Subscription

![Bootstrap Form Contrast Subscription](./images/6.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="text-center text-white" style="background:black;">
      <p class="h5 mt-2 py-4 font-weight-bold">Subscribe</p>
    </div>
    <div class="mx-4 p-3">
      <p class="text-center mt-2">
        Join our mailing list. We write rarely, but only the best content.
      </p>
      <p class="text-center"><span class="text-primary" href="#">See the last newsletter</span></p>
      <div class="cdb-form">
        <input type="text" class="form-control" />
        <label>Name</label>
      </div>
      <div class="cdb-form">
        <input type="email" class="form-control" />
        <label>E-mail</label>
      </div>
      <button class="btn btn-block btn-outline-dark my-3">
        Subscribe
      </button>
    </div>
  </div>
</div>
```

## Default Form Contact

![Bootstrap Form Contact Default](./images/7.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center mt-4 mb-5">
        <p class="h4">Contact us</p>
      </div>
      <div class="cdb-form">
        <input type="text" class="form-control border-top-0 border-left-0 border-right-0" />
        <label>Name</label>
      </div>
      <div class="cdb-form">
        <input type="email" class="form-control border-top-0 border-left-0 border-right-0" />
        <label>E-mail</label>
      </div>
      <p class="text-center m-0">Subject</p>
      <select class="select w-100">
        <option>Resources</option>
        <option>Docs</option>
        <option>Contact</option>
      </select>
      <div class="cdb-form mt-4">
        <textarea class="form-control border-top-0 border-left-0 border-right-0"></textarea>
        <label>Message</label>
      </div>
      <div class="d-flex justify-content-center align-items-center mt-4">
        <input class="mr-2" type="checkbox" />
        <p class="m-0">Send me a copy of this message</p>
      </div>
      <button class="btn btn-block btn-dark my-3">
        Send
      </button>
    </div>
  </div>
</div>
```

## Contrast Form Contact

![Bootstrap Form Contact Contrast](./images/8.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div style="background:black;" class="text-center text-white mb-4">
      <p class="h5 mt-2 py-4 font-weight-bold">Contact Us</p>
    </div>
    <div class="mx-4 p-3">
      <div class="cdb-form">
        <input type="text" class="form-control" />
        <label>Name</label>
      </div>
      <div class="cdb-form">
        <input type="email" class="form-control" />
        <label>E-mail</label>
      </div>
      <p class="text-center m-0 text-muted">Subject</p>
      <select class="select w-100">
        <option>Resources</option>
        <option>Docs</option>
        <option>Contact</option>
      </select>
      <div class="cdb-form mt-4">
        <textarea class="form-control"></textarea>
        <label>Message</label>
      </div>
      <div class="d-flex justify-content-center align-items-center mt-4">
        <input class="mr-2" type="checkbox" />
        <p class="m-0">Send me a copy of this message</p>
      </div>
      <button class="btn btn-block btn-outline-dark my-3">
        Send
      </button>
    </div>
  </div>
</div>
```

## Login Form with Icons

![Bootstrap Form Login with Icons](./images/9.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center my-4">
        <p class="h4 font-weight-bold">Sign in</p>
      </div>
      <div class="cdb-form">
        <i class="fa fa-envelope prefix"></i>
        <input type="email" class="form-control" />
        <label>E-mail</label>
      </div>
      <div class="cdb-form">
        <i class="fa fa-lock prefix"></i>
        <input type="password" class="form-control" />
        <label>Password</label>
      </div>
      <button style="width:40%;" class="btn btn-success btn-block mt-5 mx-auto">
        Login
      </button>
    </div>
  </div>
</div>
```

## Login Form with Outside Label

![Bootstrap Form Login with Outside Label](./images/10.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center mt-4 mb-4">
        <p class="h4">Sign in</p>
      </div>
      <label htmlFor="defaultLoginEmail" class="text-muted">
        Your email
      </label>
      <div class="cdb-form">
        <input type="email" id="defaultLoginEmail" class="form-control" />
      </div>
      <label htmlFor="defaultLoginPassword" class="text-muted">
        Your password
      </label>
      <div class="cdb-form">
        <input type="password" id="defaultLoginPassword" class="form-control" />
      </div>
      <button style="width:40%;" class="btn btn-primary btn-block mt-5 mx-auto">
        Login
      </button>
    </div>
  </div>
</div>
```

## Sign Up Form with Icon

![Bootstrap Form Signup with Icon](./images/11.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center my-4">
        <p class="h4 font-weight-bold">Sign in</p>
      </div>
      <div class="cdb-form">
        <i class="fa fa-user prefix text-muted"></i>
        <input type="text" class="form-control" />
        <label>Your name</label>
      </div>
      <div class="cdb-form">
        <i class="fa fa-envelope prefix text-muted"></i>
        <input type="email" class="form-control" />
        <label>Your Email</label>
      </div>
      <div class="cdb-form">
        <i class="fa fa-exclamation-triangle prefix text-muted"></i>
        <input type="email" class="form-control" />
        <label>Confirm your Email</label>
      </div>
      <div class="cdb-form">
        <i class="fa fa-lock prefix text-muted"></i>
        <input type="password" class="form-control" />
        <label>Your Password</label>
      </div>
      <button style="width:40%;" class="btn btn-primary btn-block mt-5 mx-auto">
        Register
      </button>
    </div>
  </div>
</div>
```

## Sign Up Form Outside Label

![Bootstrap Form Sign Up Outside Label](./images/12.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center mt-4 mb-4">
        <p class="h4">Sign in</p>
      </div>
      <label htmlFor="defaultLoginName" class="text-muted">
        Your name
      </label>
      <div class="cdb-form">
        <input type="text" id="defaultLoginName" class="form-control" />
      </div>
      <label htmlFor="defaultLoginEmail1" class="text-muted">
        Your email
      </label>
      <div class="cdb-form">
        <input type="email" id="defaultLoginEmail1" class="form-control" />
      </div>
      <label htmlFor="confirmLoginEmail1" class="text-muted">
        Confirm your Email
      </label>
      <div class="cdb-form">
        <input type="email" id="confirmLoginEmail1" class="form-control" />
      </div>
      <label htmlFor="defaultLoginPassword1" class="text-muted">
        Your password
      </label>
      <div class="cdb-form">
        <input type="password" id="defaultLoginPassword1" class="form-control" />
      </div>
      <button style="width:40%;" class="btn btn-danger btn-block mt-5 mx-auto">
        Register
      </button>
    </div>
  </div>
</div>
```

## Subscription Form with Icon

![Bootstrap Form Subscription with Icon](./images/13.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center my-4">
        <p class="h4 font-weight-bold">Subscribe</p>
      </div>
      <div class="cdb-form">
        <i class="fa fa-user prefix text-muted"></i>
        <input type="text" class="form-control" />
        <label>Your Name</label>
      </div>
      <div class="cdb-form">
        <i class="fa fa-envelope prefix text-muted"></i>
        <input type="email" class="form-control" />
        <label>Your Email</label>
      </div>
      <button style="width:40%;" class="btn btn-outline-primary btn-block mt-5 mx-auto">
        Send
        <i class="fa fa-paper-plane"></i>
      </button>
    </div>
  </div>
</div>
```

## Subscription Form with Outside Label

![Bootstrap Form Subscription with Outside Label](./images/14.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center mt-4 mb-4">
        <p class="h4">Subscribe</p>
      </div>
      <label htmlFor="defaultLoginName2" class="text-muted">
        Your Name
      </label>
      <div class="cdb-form">
        <input type="text" id="defaultLoginName2" class="form-control" />
      </div>
      <label htmlFor="defaultLoginEmail2" class="text-muted">
        Your email
      </label>
      <div class="cdb-form">
        <input type="email" id="defaultLoginEmail2" class="form-control" />
      </div>
      <button style="width:40%;" class="btn btn-outline-danger btn-block mt-5 mx-auto">
        Send
        <i class="fa fa-paper-plane"></i>
      </button>
    </div>
  </div>
</div>
```

## Contact Form with Icon

![Bootstrap Form Contact with Icon](./images/15.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center my-4">
        <p class="h4 font-weight-bold">Write to us</p>
      </div>
      <div class="cdb-form">
        <i class="fa fa-user prefix text-muted"></i>
        <input type="text" class="form-control" />
        <label>Your name</label>
      </div>
      <div class="cdb-form">
        <i class="fa fa-envelope prefix text-muted"></i>
        <input type="email" class="form-control" />
        <label>Your Email</label>
      </div>
      <div class="cdb-form">
        <i class="fa fa-tags prefix text-muted"></i>
        <input type="text" class="form-control" />
        <label>Subject</label>
      </div>
      <div class="cdb-form">
        <i class="fa fa-envelope prefix text-muted"></i>
        <input type="text" class="form-control" />
        <label>Your Message</label>
      </div>
      <button style="width:40%;" class="btn btn-outline-secondary btn-block mt-5 mx-auto">
        Send
        <i class="fa fa-paper-plane"></i>
      </button>
    </div>
  </div>
</div>
```

## Contact Form without Icon

![Bootstrap Form Contact without Icon](./images/16.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center mt-4 mb-4">
        <p class="h4">Write to us</p>
      </div>
      <label htmlFor="defaultLoginName3" class="text-muted">
        Your name
      </label>
      <div class="cdb-form">
        <input type="text" id="defaultLoginName3" class="form-control" />
      </div>
      <label htmlFor="defaultLoginEmail3" class="text-muted">
        Your email
      </label>
      <div class="cdb-form">
        <input type="email" id="defaultLoginEmail3" class="form-control" />
      </div>
      <label htmlFor="confirmLoginEmail3" class="text-muted">
        Subject
      </label>
      <div class="cdb-form">
        <input type="text" id="confirmLoginEmail3" class="form-control" />
      </div>
      <label htmlFor="defaultLoginPassword3" class="text-muted">
        Your message
      </label>
      <div class="cdb-form">
        <textarea id="defaultLoginPassword3" class="form-control"></textarea>
      </div>
      <button style="width:40%;" class="btn btn-outline-secondary btn-block mt-5 mx-auto">
        Send
        <i class="fa fa-paper-plane"></i>
      </button>
    </div>
  </div>
</div>
```

## Form Login

![Bootstrap Form Login](./images/17.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center my-4">
        <p class="h4 font-weight-bold">Sign in</p>
      </div>
      <div class="cdb-form">
        <input type="email" class="form-control" />
        <label>E-mail</label>
      </div>
      <div class="cdb-form">
        <input type="password" class="form-control" />
        <label>Password</label>
      </div>
      <p class="mt-n3 text-right"><span class="text-primary" href="#">Forgot Password ?</span></p>
      <button class="btn btn-dark btn-block my-4 mx-0">
        Sign in
      </button>
      <p class="text-center">or sign in with</p>
      <div class="my-3 d-flex justify-content-center">
        <button class="m-0 btn">
          <i class="fab fa-facebook-f"></i>
        </button>
        <button class="m-0 btn">
          <i class="fab fa-twitter"></i>
        </button>
        <button class="m-0 btn">
          <i class="fab fa-google-plus-g"></i>
        </button>
      </div>
      <hr />
      <p class="text-center">Not a member? <span class="text-primary" href="#">Sign up</span></p>
    </div>
  </div>
</div>
```

## Sign Up

![Bootstrap Form SignUp](./images/18.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div class="mx-4 p-3">
      <div class="text-center my-4">
        <p class="h4">Sign up</p>
      </div>
      <div class="cdb-form">
        <input type="email" class="form-control" />
        <label>E-mail</label>
      </div>
      <div class="cdb-form">
        <input type="password" class="form-control" />
        <label>Password</label>
      </div>
      <div class="d-flex align-items-center">
        <input type="checkbox" />
        <p class="mb-0 ml-3">
          Accept the <span class="text-primary" href="#">terms and conditions</span>
        </p>
      </div>
      <div class="d-flex mt-4 align-items-center">
        <button
          style="width:30%; background:linear-gradient(0deg, rgba(152,117,196,1) 0%, rgba(169,208,213,0.8746849081429446) 100%);"
          class="btn btn-block"
        >
          Sign up
        </button>
        <p class="ml-auto mb-0">
          Have an account? <span class="text-primary" href="#">Log in</span>
        </p>
      </div>
    </div>
    <div
      class="pt-4"
      style="background:linear-gradient(0deg, rgba(152,117,196,1) 0%, rgba(169,208,213,0.8746849081429446) 100%);"
    >
      <p class="text-center m-0">or sign up with</p>
      <div class="mb-3 d-flex justify-content-center">
        <button class="m-0 btn">
          <i class="fab fa-facebook-f"></i>
        </button>
        <button class="m-0 btn">
          <i class="fab fa-twitter"></i>
        </button>
        <button class="m-0 btn">
          <i class="fab fa-google-plus-g"></i>
        </button>
      </div>
    </div>
  </div>
</div>
```

## Login Form

![Bootstrap Form Login](./images/19.png)

###### html

```html
<div class="container">
  <div class="border d-flex flex-column" style="width:30rem;">
    <div
      style="background:linear-gradient(0deg, rgba(152,117,196,1) 0%, rgba(169,208,213,0.8746849081429446) 100%);"
      class="text-center mb-4"
    >
      <p class="h5 mt-2 mt-5 mb-2 font-weight-bold">Login</p>
      <div class="mb-3 d-flex justify-content-center">
        <button class="m-0 btn btn-flat">
          <i class="fab fa-facebook-f"></i>
        </button>
        <button class="m-0 btn btn-flat">
          <i class="fab fa-twitter"></i>
        </button>
        <button class="m-0 btn btn-flat">
          <i class="fab fa-linkedin-in"></i>
        </button>
        <button class="m-0 btn btn-flat">
          <i class="fab fa-github"></i>
        </button>
      </div>
    </div>
    <div class="mx-4 p-3">
      <div class="cdb-form">
        <input type="email" class="form-control" />
        <label>E-mail</label>
      </div>
      <div class="cdb-form">
        <input type="password" class="form-control" />
        <label>Password</label>
      </div>
      <p class="text-right">Forgot <span class="text-primary ml-auto" href="#">Password ?</span></p>
      <button
        style="width:40%; background:linear-gradient(0deg, rgba(152,117,196,1) 0%, rgba(169,208,213,0.8746849081429446) 100%);"
        class="btn btn-block my-3 mx-0 font-weight-bold"
      >
        Login
      </button>
      <p class=" text-right mt-4">
        Don't have an account? <span class="text-primary" href="#">Sign Up</span>
      </p>
    </div>
  </div>
</div>
```

## Sign Up with Background Image

![Bootstrap Form Sign Up with Background Image](./images/20.png)

###### html

```html
<div class="container">
  <div
    class="border d-flex flex-column view"
    style="width:30rem; background:url(https://images.unsplash.com/photo-1528287942171-fbe365d1d9ac?ixlib=rb-1.2.1&q=85&fm=jpg&crop=entropy&w=1200&cs=srgb&ixid=eyJh); background-size:cover;"
  >
    <div class="mask rgba-dark-strong"></div>
    <div class="mx-4 p-3" style="z-index:2;">
      <div class="text-center my-5">
        <p class="h4 font-weight-bold text-white">Sign up</p>
      </div>
      <div class="cdb-form">
        <input type="email" class="form-control border-top-0 border-left-0 border-right-0" />
        <label class="bg-transparent">E-mail</label>
      </div>
      <div class="cdb-form">
        <input type="password" class="form-control border-top-0 border-left-0 border-right-0" />
        <label class="bg-transparent">Password</label>
      </div>
      <div class="d-flex mt-3 align-items-center justify-content-center">
        <input type="checkbox" />
        <p class="text-white mb-0 ml-2">
          Accept the <span class="text-primary" href="#">terms and conditions</span>
        </p>
      </div>
      <button class="btn btn-block my-4">
        Sign up
      </button>
      <p class="text-white text-center mb-5">
        Have an account? <span class="text-primary" href="#">Log in</span>
      </p>
    </div>
  </div>
</div>
```

## Sign In Forms

![Bootstrap Form Sign In](./images/21.png)
![Bootstrap Form Sign In](./images/22.png)
![Bootstrap Form Sign In](./images/23.png)

###### html

```html
<div class="shadow border d-flex flex-column m-0 mx-auto" style="width:100%; max-width:30rem;">
  <div class="p-5">
    <div class="mt-4 mb-5">
      <h4 class="h2 font-weight-bold">Sign up</h4>
    </div>
    <label htmlFor="defaultRegisterUsername" class="text-muted m-0">
      Username
    </label>
    <div class="cdb-form">
      <input type="text" class="form-control" />
      <label>Username</label>
    </div>
    <label htmlFor="defaultRegisterPassword" class="text-muted m-0">
      Password
    </label>
    <div class="cdb-form">
      <input type="password" class="form-control" />
      <label>Password</label>
    </div>
    <button class="btn btn-dark btn-block mb-3 mt-5">
      Sign up
    </button>
    <p class="text-muted">
      By Clicking sign up, you agree to the Contrast
      <a style="font-weight:600;" class="text-decoration-none text-dark" href="#"
        >terms and conditions</a
      >
    </p>
    <div class="d-flex align-items-center">
      <span style="border:0.5px solid black; width:45%;"></span>
      <span class="text-center" style="width:10%;">OR</span>
      <span style="border:0.5px solid black; width:45%;"></span>
    </div>
    <div class="my-3 d-flex justify-content-center">
      <button class="btn btn-flat btn-dark p-2">
        <i class="fab fa-facebook-f"></i>
      </button>
      <button class="btn btn-flat btn-dark p-2">
        <i class="fab fa-twitter"></i>
      </button>
      <button class="btn btn-flat btn-dark p-2 mr-0">
        <i class="fab fa-google-plus-g"></i>
      </button>
    </div>
    <p class="text-muted text-center">
      Have an Account?
      <a style="font-weight:600;" class="text-decoration-none text-dark" href="#">Sign In</a>
    </p>
  </div>
</div>

<div class="shadow border d-flex flex-column mt-4 mx-auto" style="width:100%; max-width:30rem;">
  <div class="p-5">
    <div class="my-4 d-flex align-items-center">
      <div>
        <h4 class="h4 mt-0 font-weight-bold">Sign up</h4>
        <p class="m-0" style="font-weight:600;">Let's get started</p>
      </div>
      <button class="btn btn-outline-dark ml-auto px-4" style="font-weight:600;">Sign In</button>
    </div>
    <label htmlFor="defaultRegisterUsername" class="text-muted m-0">
      Username
    </label>
    <div class="cdb-form">
      <input type="text" class="form-control" />
      <label>Username</label>
    </div>
    <label htmlFor="defaultRegisterPassword" class="text-muted m-0">
      Password
    </label>
    <div class="cdb-form">
      <input type="password" class="form-control" />
      <label>Password</label>
    </div>
    <button class="btn btn-dark btn-block mb-3 mt-5">
      Sign up
    </button>
    <p class="text-muted">
      By Clicking sign up, you agree to the Contrast
      <a style="font-weight:600;" class="text-decoration-none text-dark" href="#"
        >terms and conditions</a
      >
    </p>
    <div class="d-flex align-items-center">
      <span style="border:0.5px solid black; width:45%;"></span>
      <span class="text-center" style="width:10%">OR</span>
      <span style="border:0.5px solid black; width:45%;"></span>
    </div>
    <div class="my-3 d-flex justify-content-center">
      <button class="btn btn-dark btn-flat p-2">
        <i class="fab fa-facebook-f"></i>
      </button>
      <button class="btn btn-dark btn-flat p-2">
        <i class="fab fa-twitter"></i>
      </button>
      <button class="btn btn-dark btn-flat p-2 mr-0">
        <i class="fab fa-google-plus-g"></i>
      </button>
    </div>
    <p class="text-muted text-center">
      Have an Account?
      <a style="font-weight:600;" class="text-decoration-none text-dark" href="#">Sign In</a>
    </p>
  </div>
</div>

<div class="container">
  <div class="shadow border d-flex flex-column m-0 mx-auto" style="width:100%; max-width:30rem;">
    <div class="p-5">
      <div class="mt-4 mb-5">
        <h4 class="h2 font-weight-bold">Sign in</h4>
      </div>
      <label htmlFor="defaultRegisterUsername" class="text-muted m-0">
        Username
      </label>
      <div class="cdb-form">
        <input type="text" class="form-control" />
        <label>Username</label>
      </div>
      <label htmlFor="defaultRegisterPassword" class="text-muted m-0">
        Password
      </label>
      <div class="cdb-form">
        <input type="password" class="form-control" />
        <label>Password</label>
      </div>
      <a style="font-weight:600;" class="text-decoration-none text-dark" href="#"
        >Forgot Password?</a
      >
      <button class="btn btn-dark btn-block mb-3 mt-5">
        Sign in
      </button>
      <div class="d-flex align-items-center">
        <span style="border:0.5px solid #555; width:45%;"></span>
        <span class="text-center" style="width:10%;">OR</span>
        <span style="border:0.5px solid #555; width:45%;"></span>
      </div>
      <div class="my-3 d-flex justify-content-center">
        <button class="btn btn-dark btn-flat p-2">
          <i class="fab fa-facebook-f"></i>
        </button>
        <button class="btn btn-dark btn-flat p-2">
          <i class="fab fa-twitter"></i>
        </button>
        <button class="btn btn-dark btn-flat p-2 mr-0">
          <i class="fab fa-google-plus-g"></i>
        </button>
      </div>
      <p class="text-muted text-center">
        Don't have an Account?
        <a style="font-weight:600;" class="text-decoration-none text-dark" href="#">Sign Up</a>
      </p>
    </div>
  </div>
  <div class="shadow border d-flex flex-column mt-4 mx-auto" style="width:100%; max-width:30rem;">
    <div class="p-5">
      <div class="my-4 d-flex align-items-center">
        <div>
          <h4 class="h4 mt-0 font-weight-bold">Sign in</h4>
          <p class="m-0" style="font-weight:600;">Welcome Back.</p>
        </div>
        <button class="btn btn-outline-dark ml-auto px-4" style="font-weight:600;">Sign Up</button>
      </div>
      <label htmlFor="defaultRegisterUsername" class="text-muted m-0">
        Username
      </label>
      <div class="cdb-form">
        <input type="text" class="form-control" />
        <label>Username</label>
      </div>
      <label htmlFor="defaultRegisterPassword" class="text-muted m-0">
        Password
      </label>
      <div class="cdb-form">
        <input type="password" class="form-control" />
        <label>Password</label>
      </div>
      <a style="font-weight:600;" class="text-decoration-none text-dark" href="#"
        >Forgot Password?</a
      >
      <button class="btn btn-dark btn-block mb-3 mt-5">
        Sign in
      </button>
      <div class="d-flex align-items-center">
        <span style="border:0.5px solid #555; width:45%;"></span>
        <span class="text-center" style="width:10%;">OR</span>
        <span style="border:0.5px solid #555; width:45%;"></span>
      </div>
      <div class="my-3 d-flex justify-content-center">
        <button class="btn btn-dark btn-flat p-2">
          <i class="fab fa-facebook-f"></i>
        </button>
        <button class="btn btn-dark btn-flat p-2">
          <i class="fab fa-twitter"></i>
        </button>
        <button class="btn btn-dark btn-flat p-2 mr-0">
          <i class="fab fa-google-plus-g"></i>
        </button>
      </div>
      <p class="text-muted text-center">
        Don't have an Account?
        <a style="font-weight:600;" class="text-decoration-none text-dark" href="#">Sign Up</a>
      </p>
    </div>
  </div>
</div>
```
