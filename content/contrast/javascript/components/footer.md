---
title: 'Footer'
metaTitle: 'Bootstrap 5 Footer - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 Footer is an additional navigation for the website'
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/javascript/components/footer.md"
---

# Bootstrap 5 Footer

The website's additional navigation is provided through the Bootstrap 5 Footer. It can contain `links`, `business information`, `copyrights`, `buttons`, `forms`, and a variety of other items.

You can change the color of the footer by using one of our `color palette` classes.

For alternative footer layouts, the Contrast Bootstrap 5 Footer component provides several default styles. These layouts are flexible, responsive, and simple to use, much like the rest of the Contrast Bootstrap components.

The Contrast Bootstrap Footer provides a list of pre-defined styles and classes for everyday used sections that can be found in a footer.

## Default Footer

This examples details a default footer layout. You can control to background and text colors with the following CSS classes `footer-background-` with the following appended to it; `primary`, `secondary`, `success` , `danger`, `warning`, `dark`, `info`. Without this style it just defaults to a white background and black text.

Below you can see examples for `dark` and `secondary` sidebars

<footerExampleBootstrap8 />

<footerExampleBootstrap9 />

```html link=github.com/Devwares-Team/Contrast-Docs/blob/master/content/contrast/javascript/components/footer.md

    <footer className="contrast-footer footer-dark footer-shadow-dark p-5">
      <div className="container d-flex flex-column">
        <div className="row">
          <div className="col-md-6">
            <p>
              <div className=" d-flex ">
                <h2
                  style='font-weight: bold'
                  className="d-inline font-weight-bold text-uppercase mr-1"
                >
                  Devwares.
                </h2>
                A creative agency
              </div>
              <br />
              <a href="mailto:devwares@gmail.com" className="text-success font-bold mb-2">
                Click to contact us at devwares
              </a>
              <div className="d-flex flex-column">
                <span className="d-flex align-items-center my-1">
                  <span
                    className=" mr-2 bg-success"
                    style="border-radius: 10px; width:10px; height:10px"
                  />
                  <span>07055555555</span>
                </span>
                <span className="d-flex align-items-center">
                  <span
                    className=" mr-2 bg-success"
                    style="border-radius: 10px; width:10px; height:10px"
                  />
                  <span>07005050505</span>
                </span>
              </div>
              <br />
              Lagos, Nigeria
            </p>
          </div>
          <div className="col-md-6">
            <div className="d-flex flex-row">
              <div className="mx-2 text-uppercase">Facebook</div>
              <div className="mx-2 text-uppercase">+</div>
              <div className="mx-2 text-uppercase">Instagram</div>
              <div className="mx-2 text-uppercase">+</div>
              <div className="mx-2 text-uppercase">Dribbble</div>
            </div>
          </div>
        </div>
        <small className="text-center mt-5 footer-copyright">
          &copy; Devwares, 2023. All rights reserved.
        </small>
      </div>
    </footer>

```

## Light Background Footer

You can customize the footer to have a lighter background based on our color schemes. This is controlled by the `footer-light-` css class

<footerExampleBootstrap10 />

<footerExampleBootstrap11 />

```html link=github.com/Devwares-Team/Contrast-Docs/blob/master/content/contrast/javascript/components/footer.md
<footer className="contrast-footer footer-light-secondary footer-shadow-dark p-5">
  <div className="container d-flex flex-column">
    <div className="row mb-3">
      <div className="col-md-9">
        <h2
          className=" text-black font-weight-light mb-3"
          style="font-size: 23px; font-weight: 900"
        >
          Take your client exposure to the next level
        </h2>
        <div className="d-flex flex-wrap align-items-center mb-3" style="flex-wrap: wrap">
          <span
            className="text-black mr-3 my-2"
            style="font-weight: bold; font-size: 17px; whitespace: nowrap"
          >
            Consulting
          </span>
          <span
            className="d-flex align-items-center text-black mr-3 my-2"
            style="font-weight: bold; font-size: 17px; whitespace: nowrap"
          >
            Research Fields
            <span
              className="ml-1 bg-warning text-black d-flex align-items-center justify-content-center"
              style=" width:20px; height:20px; border-radius: 20px; font-weight: 100"
            >
              3
            </span>
          </span>
          <span
            className="d-flex align-items-center text-black mr-3 my-2"
            style="font-weight: bold; font-size: 17px; whitespace: nowrap"
          >
            Documentations
            <span
              className="ml-1 bg-secondary text-white d-flex align-items-center justify-content-center"
              style=" width:20px; height:20px; border-radius: 20px; font-weight: 100"
            >
              7
            </span>
          </span>
          <span
            className="text-black mr-3 my-2"
            style="font-weight: bold; font-size: 17px; whitespace: nowrap"
          >
            Exposure
          </span>
          <span
            className="text-black mr-3 my-2"
            style="font-weight: bold; font-size: 17px; whitespace: nowrap"
          >
            About Us
          </span>
        </div>
        <p className="d-flex">
          <strong className="text-black mr-3" style="font-weight: 700">
            Follow us :
          </strong>
          <span className="text-black mr-2" style="font-weight: 100">
            Twitter
          </span>
          <span className="text-black mr-2" style="font-weight: 100">
            Facebook
          </span>
          <span className="text-black mr-2" style="font-weight: 100">
            Youtube
          </span>
          <span className="text-black mr-2" style="font-weight: 100">
            Instagram
          </span>
          <span className="text-black mr-2" style="font-weight: 100">
            Linkedin
          </span>
        </p>
      </div>
      <div className="col-md-3">
        <div className="d-flex ">
          <strong
            className="text-black"
            style="whitespace: nowrap; font-size: 20px; font-weight: 900"
          >
            Book a meeting with us
          </strong>
          <i className="fa fa-solid fa-calendar text-black ml-2" style="font-size: 24px"></i>
        </div>
      </div>
    </div>
    <div className="row pt-5" style="height:100px; border-top: 1px solid #cccccc">
      <div className="col-md-9">
        <div className="d-flex align-items-center">
          <span className="text-black mr-2">Contact Us</span>
          <span className="text-black mr-2">F.A.Q</span>
          <span className="text-black mr-2">Cookies Policy</span>
          <span className="text-black mr-2">Legal Terms</span>
          <span className="text-black mr-2">Privacy Policy</span>
          <div className="d-flex align-items-center ml-4">
            English
            <i className="ml-2 fa fa-solid fa-globe" style=" fontSize: 15px"></i>
          </div>
        </div>
      </div>
      <div className="col-md-3">
        <span className="text-black">Private Cloud Stackscale</span>
      </div>
    </div>
  </div>
</footer>
```

## Footer Sitemaps

Contrast Bootstrap Footer has custom classes to help you create footer sitemaps out of the box, using the `footer-sitemaps`, `footer-sitemap` classes

<footerExampleBootstrap12 />

```html link=github.com/Devwares-Team/Contrast-Docs/blob/master/content/contrast/javascript/components/footer.md
<footer className="contrast-footer footer-shadow-dark p-5">
  <div className="container d-flex flex-column">
    <div className="row mb-3">
      <div className="col-md-4">
        <div className="d-flex flex-row align-items-center mr-3">
          <div className="footer-logo">
            <img src="https://img.icons8.com/doodle/344/numbers.png" alt="" />
          </div>
          <h2 className="footer-header ml-3 mb-0" style="font-weight: 800">
            Devwares
          </h2>
        </div>
        <p className="footer-text my-3" style="width: 250px">
          We are creating High Quality Resources and tools to Aid developers during the developement
          of their projects
        </p>
      </div>
      <div className="col-md-8">
        <div className="footer-sitemaps">
          <div className="footer-sitemap">
            <h2 className="footer-sitemap-header">Products</h2>
            <span className="footer-sitemap-link">Baby Care</span>
            <span className="footer-sitemap-link">Adult Care</span>
            <span className="footer-sitemap-link">Teenagers Care</span>
            <span className="footer-sitemap-link">Merch</span>
          </div>
          <div className="footer-sitemap">
            <h2 className="footer-sitemap-header">Documentation</h2>
            <span className="footer-sitemap-link">Svelte</span>
            <span className="footer-sitemap-link">React</span>
            <span className="footer-sitemap-link">Angular</span>
            <span className="footer-sitemap-link">Bootstrap</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</footer>
```

## Footer Examples

<footerExampleBootstrap1 />

```html link=github.com/Devwares-Team/Contrast-Docs/blob/master/content/contrast/javascript/components/footer.md
<div class="blockcode">
  <div class="header">Footer</div>

  <footer class="page-footer shadow">
    <div class="d-flex flex-column mx-auto py-5" style="width: 80%">
      <div class="d-flex flex-wrap justify-content-between">
        <div>
          <a href="/" class="d-flex align-items-center p-0 text-dark">
            <img alt="logo" src="../img/logo.png" width="30px" />
            <span class="ml-3 h5 font-weight-bold">Devwares</span>
          </a>
          <p class="my-3" style="width: 250px">
            We are creating High Quality Resources and tools to Aid developers during the
            developement of their projects
          </p>
          <span class="mt-4">
            <button class="btn btn-dark btn-flat p-2">
              <i class="fa fa-facebook"></i>
            </button>
            <button class="btn btn-dark btn-flat p-2">
              <i class="fa fa-twitter"></i>
            </button>
            <button class="btn btn-dark btn-flat p-2">
              <i class="fa fa-instagram"></i>
            </button>
          </span>
        </div>
        <div>
          <p class="h5 mb-4" style="font-weight: 600">Devwares</p>
          <ul class="p-0" style="list-style: none; cursor: pointer">
            <li class="my-2">
              <a class="text-dark" href="/">Resources</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">About Us</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Contact</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Blog</a>
            </li>
          </ul>
        </div>
        <div>
          <p class="h5 mb-4" style="font-weight: 600">Help</p>
          <ul class="p-0" style="list-style: none; cursor: pointer">
            <li class="my-2">
              <a class="text-dark" href="/">Support</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign Up</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign In</a>
            </li>
          </ul>
        </div>
        <div>
          <p class="h5 mb-4" style="font-weight: 600">Help</p>
          <ul class="p-0" style="list-style: none; cursor: pointer">
            <li class="my-2">
              <a class="text-dark" href="/">Support</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign Up</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign In</a>
            </li>
          </ul>
        </div>
      </div>
      <small class="text-center mt-5">&copy; Devwares, 2020. All rights reserved.</small>
    </div>
  </footer>
</div>
```
<br />

<footerExampleBootstrap2 />

```html link=github.com/Devwares-Team/Contrast-Docs/blob/master/content/contrast/javascript/components/footer.md
<div class="blockcode">
  <div class="header">Footer</div>

  <footer class="page-footer shadow">
    <div class="d-flex flex-column mx-auto py-5" style="width: 80%">
      <div class="d-flex flex-wrap justify-content-between">
        <div class="align-self-center">
          <a href="/#" class="d-flex align-items-center p-0 text-dark">
            <img alt="logo" src="../img/logo.png" width="30px" />
            <span class="ml-3 h5 font-weight-bold">Devwares</span>
          </a>
          <div class="mt-5">
            <button class="btn btn-dark btn-flat p-2">
              <i class="fa fa-facebook"></i>
            </button>
            <button class="btn btn-dark btn-flat p-2">
              <i class="fa fa-twitter"></i>
            </button>
            <button class="btn btn-dark btn-flat p-2">
              <i class="fa fa-instagram"></i>
            </button>
          </div>
        </div>
        <div>
          <p class="h5 mb-4" style="font-weight: 600">Devwares</p>
          <ul class="p-0" style="list-style: none; cursor: pointer">
            <li class="my-2">
              <a class="text-dark" href="/">Resources</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">About Us</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Contact</a>
            </li>
            <li class="my-2"><a class="text-dark" href="/">Blog</a></li>
          </ul>
        </div>
        <div>
          <p class="h5 mb-4" style="font-weight: 600">Help</p>
          <ul class="p-0" style="list-style: none; cursor: pointer">
            <li class="my-2">
              <a class="text-dark" href="/">Support</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign Up</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign In</a>
            </li>
          </ul>
        </div>
        <div>
          <p class="h5 mb-4" style="font-weight: 600">Help</p>
          <ul class="p-0" style="list-style: none; cursor: pointer">
            <li class="my-2">
              <a class="text-dark" href="/">Support</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign Up</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign In</a>
            </li>
          </ul>
        </div>
      </div>
      <small class="text-center mt-5">&copy; Devwares, 2020. All rights reserved.</small>
    </div>
  </footer>
</div>
```

<br />

<footerExampleBootstrap3 />

```html link=github.com/Devwares-Team/Contrast-Docs/blob/master/content/contrast/javascript/components/footer.md
<div class="blockcode">
  <div class="header">Footer</div>

  <footer class="page-footer shadow">
    <div class="d-flex flex-column mx-auto py-5" style="width: 80%">
      <div class="d-flex flex-wrap justify-content-between">
        <div>
          <a href="/#" class="d-flex align-items-center p-0 text-dark">
            <img alt="logo" src="../img/logo.png" width="30px" />
            <span class="ml-3 h5 font-weight-bold">Devwares</span>
          </a>
          <p class="my-3" style="width: 250px">
            We are creating High Quality Resources and tools to Aid developers during the
            developement of their projects
          </p>
        </div>
        <div>
          <p class="h5 mb-4" style="font-weight: 600">Devwares</p>
          <ul class="p-0" style="list-style: none; cursor: pointer">
            <li class="my-2">
              <a class="text-dark" href="/">Resources</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">About Us</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Contact</a>
            </li>
            <li class="my-2"><a class="text-dark" href="/">Blog</a></li>
          </ul>
        </div>
        <div>
          <p class="h5 mb-4" style="font-weight: 600">Help</p>
          <ul class="p-0" style="list-style: none; cursor: pointer">
            <li class="my-2">
              <a class="text-dark" href="/">Support</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign Up</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign In</a>
            </li>
          </ul>
        </div>
        <div>
          <p class="h5 mb-4" style="font-weight: 600">Help</p>
          <ul class="p-0" style="list-style: none; cursor: pointer">
            <li class="my-2">
              <a class="text-dark" href="/">Support</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign Up</a>
            </li>
            <li class="my-2">
              <a class="text-dark" href="/">Sign In</a>
            </li>
          </ul>
        </div>
      </div>
      <div class="text-center mt-4">
        <div class="mb-4">
          <button class="btn btn-dark btn-flat p-2">
            <i class="fa fa-facebook"></i>
          </button>
          <button class="btn btn-dark btn-flat p-2">
            <i class="fa fa-twitter"></i>
          </button>
          <button class="btn btn-dark btn-flat p-2">
            <i class="fa fa-instagram"></i>
          </button>
        </div>
        <small>&copy; Devwares, 2020. All rights reserved.</small>
      </div>
    </div>
  </footer>
</div>
```

<footerExampleBootstrap4 />

```html link=github.com/Devwares-Team/Contrast-Docs/blob/master/content/contrast/javascript/components/footer.md
<footer className="shadow">
  <div className="d-flex flex-column mx-auto py-5" style="width: 90%">
    <div className="flex-wrap d-flex justify-content-between">
      <div>
        <a href="/" className="d-flex align-items-center p-0 text-dark">
          <img alt="logo" src="logo" width="30px" />
          <span className="ml-3 h5 font-weight-bold">Devwares</span>
        </a>
        <p className="my-3" style="width:250px">
          We are creating High Quality Resources and tools to Aid developers during the developement
          of their projects
        </p>
      </div>
      <div>
        <p className="h5 mb-4" style="font-weight: 600">
          Devwares
        </p>
        <div className="d-flex flex-column" style="cursor: pointer; padding: 0">
          <a href="/">Resources</a>
          <a href="/">About Us</a>
          <a href="/">Contact</a>
          <a href="/">Blog</a>
        </div>
      </div>
      <div>
        <p className="h5 mb-4" style="font-weight: 600">
          Help
        </p>
        <div className="d-flex flex-column" style="cursor: pointer; padding: 0">
          <a href="/">Support</a>
          <a href="/">Sign Up</a>
          <a href="/">Sign In</a>
        </div>
      </div>
      <div>
        <p className="h5 mb-4" style="font-weight: 600">
          Products
        </p>
        <div className="d-flex flex-column" style="cursor: pointer; padding: 0">
          <a href="/">Windframe</a>
          <a href="/">Loop</a>
          <a href="/">Contrast</a>
        </div>
      </div>
    </div>
    <div className="d-flex mt-4 mx-auto" style="width:100%">
      <small className="text-center" style="width:50%">
        &copy; Devwares, 2023. All rights reserved.
      </small>
      <button className="btn btn-dark btn-flat p-2">
        <i className="fab fa-facebook-f" />
      </button>
      <button className="btn btn-dark btn-flat p-2">
        <i className="fab fa-twitter" />
      </button>
      <button className="btn btn-dark btn-flat p-2">
        <i className="fab fa-instagram" />
      </button>
    </div>
  </div>
</footer>
```


<br/>

<footerExampleBootstrap5 />

```html link=github.com/Devwares-Team/Contrast-Docs/blob/master/content/contrast/javascript/components/footer.md
<div class="blockcode">
  <div class="header">Footer</div>
  <div class="description">Footer</div>
  <footer class="page-footer shadow">
    <div
      class="d-flex flex-wrap justify-content-between align-items-center mx-auto py-4"
      style="width: 80%"
    >
      <div class="d-flex flex-wrap align-items-center">
        <a href="/#" class="d-flex align-items-center p-0 text-dark">
          <img alt="logo" src="../img/logo.png" width="30px" />
          <span class="ml-4 h5 mb-0 font-weight-bold">Devwares</span>
        </a>
        <span
          style="
                        font-size: 3em;
                        margin: -2rem 0px -1.5rem 1rem;
                        color: #c4c4c4;
                      "
          >&#8226;</span
        >
        <small class="ml-2">&copy; Devwares, 2020. All rights reserved.</small>
      </div>
      <div>
        <button class="btn btn-dark btn-flat p-2">
          <i class="fa fa-facebook"></i>
        </button>
        <button class="btn btn-dark btn-flat p-2">
          <i class="fa fa-twitter"></i>
        </button>
        <button class="btn btn-dark btn-flat p-2">
          <i class="fa fa-instagram"></i>
        </button>
      </div>
    </div>
  </footer>
</div>
```


<br/>

<footerExampleBootstrap7 />

```html link=github.com/Devwares-Team/Contrast-Docs/blob/master/content/contrast/javascript/components/footer.md
<div class="blockcode">
  <div class="header">Footer</div>
  <div class="description">Footer</div>
  <footer class="shadow">
    <div
      class="d-flex justify-content-between align-items-center mx-auto py-4 flex-wrap"
      style="width: 80%"
    >
      <a href="/#" class="d-flex align-items-center p-0 text-dark">
        <img alt="logo" src="../img/logo.png" width="30px" />
        <span class="ml-4 h5 font-weight-bold">Devwares</span>
      </a>
      <small>&copy; Devwares, 2020. All rights reserved.</small>
      <div>
        <button class="btn btn-dark btn-flat p-2">
          <i class="fa fa-facebook"></i>
        </button>
        <button class="btn btn-dark btn-flat p-2">
          <i class="fa fa-twitter"></i>
        </button>
        <button class="btn btn-dark btn-flat p-2">
          <i class="fa fa-instagram"></i>
        </button>
      </div>
    </div>
  </footer>
</div>
```
