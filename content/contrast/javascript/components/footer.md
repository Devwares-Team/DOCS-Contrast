---
title: 'Footer'
metaTitle: 'Bootstrap 5 Footer - Bootstrap CSS tutorial'
metaDescription: 'Bootstrap 5 Footer is an additional navigation for the website'
---

# Bootstrap 5 Footer

The website's additional navigation is provided through the Bootstrap 5 Footer. It can contain `links`, `business information`, `copyrights`, `buttons`, `forms`, and a variety of other items.

You can change the color of the footer by using one of our `color palette` classes.

For alternative footer layouts, the Contrast Bootstrap 5 Footer component provides several default styles. These layouts are flexible, responsive, and simple to use, much like the rest of the Contrast Bootstrap components.

## Default Footer Layout

![Bootstrap Footer Default](./images/footer1.png)

###### html

```html
<footer class="page-footer shadow">
  <div class="d-flex flex-column mx-auto py-5" style="width: 80%">
    <div class="d-flex justify-content-between">
      <div>
        <a href="/" class="d-flex align-items-center p-0 text-dark">
          <img alt="logo" src="/img/pages/logo.png" width="30px" />
          <span class="ml-3 h5 font-weight-bold">Devwares</span>
        </a>
        <p class="my-3" style="width: 250px">
          We are creating High Quality Resources and tools to Aid developers during the developement
          of their projects
        </p>
        <div class="mt-4">
          <button class="btn btn-dark btn-flat">
            <i class="fa fa-facebook"></i>
          </button>
          <button class="btn btn-dark btn-flat">
            <i class="fa fa-twitter"></i>
          </button>
          <button class="btn btn-dark btn-flat">
            <i class="fa fa-instagram"></i>
          </button>
        </div>
      </div>
      <div>
        <p class="h5 mb-4" style="font-weight: 600">Devwares</p>
        <ul style="list-style: none; cursor: pointer">
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
        <ul style="list-style: none; cursor: pointer">
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
        <ul style="list-style: none; cursor: pointer">
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
```

## Example 2

![Bootstrap Footer Layout 2](./images/footer2.png)

###### html

```html
<footer class="page-footer shadow">
  <div class="d-flex flex-column mx-auto py-5" style="width: 80%">
    <div class="d-flex justify-content-between">
      <div class="align-self-center">
        <a href="/#" class="d-flex align-items-center p-0 text-dark">
          <img alt="logo" src="/img/pages/logo.png" width="30px" />
          <span class="ml-3 h5 font-weight-bold">Devwares</span>
        </a>
        <div class="mt-5">
          <button class="btn btn-dark btn-flat">
            <i class="fa fa-facebook"></i>
          </button>
          <button class="btn btn-dark btn-flat">
            <i class="fa fa-twitter"></i>
          </button>
          <button class="btn btn-dark btn-flat">
            <i class="fa fa-instagram"></i>
          </button>
        </div>
      </div>
      <div>
        <p class="h5 mb-4" style="font-weight: 600">Devwares</p>
        <ul style="list-style: none; cursor: pointer">
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
        <ul style="list-style: none; cursor: pointer">
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
        <ul style="list-style: none; cursor: pointer">
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
```

## Example 3

![Bootstrap Footer Layout 3](./images/footer3.png)

###### html

```html
<footer class="page-footer shadow">
  <div class="d-flex flex-column mx-auto py-5" style="width: 80%">
    <div class="d-flex justify-content-between">
      <div>
        <a href="/#" class="d-flex align-items-center p-0 text-dark">
          <img alt="logo" src="/img/pages/logo.png" width="30px" />
          <span class="ml-3 h5 font-weight-bold">Devwares</span>
        </a>
        <p class="my-3" style="width: 250px">
          We are creating High Quality Resources and tools to Aid developers during the developement
          of their projects
        </p>
      </div>
      <div>
        <p class="h5 mb-4" style="font-weight: 600">Devwares</p>
        <ul style="list-style: none; cursor: pointer">
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
        <ul style="list-style: none; cursor: pointer">
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
        <ul style="list-style: none; cursor: pointer">
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
        <button class="btn btn-dark btn-flat">
          <i class="fa fa-facebook"></i>
        </button>
        <button class="btn btn-dark btn-flat">
          <i class="fa fa-twitter"></i>
        </button>
        <button class="btn btn-dark btn-flat">
          <i class="fa fa-instagram"></i>
        </button>
      </div>
      <small>&copy; Devwares, 2020. All rights reserved.</small>
    </div>
  </div>
</footer>
```

## Example 4

![Bootstrap Footer Layout 4](./images/footer4.png)

###### html

```html
<footer class="page-footer shadow">
  <div class="d-flex flex-column mx-auto py-5" style="width: 80%">
    <div class="d-flex justify-content-between">
      <div class="align-self-center">
        <a href="/#" class="d-flex align-items-center p-0 text-dark">
          <img alt="logo" src="/img/pages/logo.png" width="30px" />
          <span class="ml-4 h5 font-weight-bold">Devwares</span>
        </a>
      </div>
      <div>
        <p class="h5 mb-4" style="font-weight: 600">Devwares</p>
        <ul style="list-style: none; cursor: pointer">
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
        <ul style="list-style: none; cursor: pointer">
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
        <ul style="list-style: none; cursor: pointer">
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
    <div class="d-flex justify-content-between align-items-center mt-4">
      <small>&copy; Devwares, 2020. All rights reserved.</small>
      <div>
        <button class="btn btn-dark btn-flat">
          <i class="fa fa-facebook"></i>
        </button>
        <button class="btn btn-dark btn-flat">
          <i class="fa fa-twitter"></i>
        </button>
        <button class="btn btn-dark btn-flat">
          <i class="fa fa-instagram"></i>
        </button>
      </div>
    </div>
  </div>
</footer>
```

## Example 5

![Bootstrap Footer Layout 5](./images/footer5.png)

###### html

```html
<footer class="page-footer shadow">
  <div class="d-flex justify-content-between align-items-center mx-auto py-4" style="width: 80%">
    <div class="d-flex align-items-center">
      <a href="/#" class="d-flex align-items-center p-0 text-dark">
        <img alt="logo" src="/img/pages/logo.png" width="30px" />
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
      <button class="btn btn-dark btn-flat">
        <i class="fa fa-facebook"></i>
      </button>
      <button class="btn btn-dark btn-flat">
        <i class="fa fa-twitter"></i>
      </button>
      <button class="btn btn-dark btn-flat">
        <i class="fa fa-instagram"></i>
      </button>
    </div>
  </div>
</footer>
```

## Example 6

![Bootstrap Footer Layout 6](./images/footer6.png)

###### html

```html
<footer class="page-footer shadow">
  <div class="d-flex flex-column mx-auto py-5" style="width: 80%">
    <div class="d-flex justify-content-between">
      <div class="align-self-center">
        <a href="/#" class="d-flex align-items-center p-0 text-dark">
          <img alt="logo" src="/img/pages/logo.png" width="30px" />
          <span class="ml-4 h5 font-weight-bold">Devwares</span>
        </a>
      </div>
      <div class="d-flex justify-content-between" style="width: 40%">
        <div>
          <p class="h5 mb-4" style="font-weight: 600">Devwares</p>
          <ul style="list-style: none; cursor: pointer">
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
          <ul style="list-style: none; cursor: pointer">
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
    </div>
    <div class="d-flex justify-content-between align-items-center mt-4">
      <small>&copy; Devwares, 2020. All rights reserved.</small>
      <div>
        <button class="btn btn-dark btn-flat">
          <i class="fa fa-facebook"></i>
        </button>
        <button class="btn btn-dark btn-flat">
          <i class="fa fa-twitter"></i>
        </button>
        <button class="btn btn-dark btn-flat">
          <i class="fa fa-instagram"></i>
        </button>
      </div>
    </div>
  </div>
</footer>
```

## Example 7

![Bootstrap Footer Layout 7](./images/footer7.png)

###### html

```html
<footer class="shadow">
  <div class="d-flex justify-content-between align-items-center mx-auto py-4" style="width: 80%">
    <a href="/#" class="d-flex align-items-center p-0 text-dark">
      <img alt="logo" src="/img/pages/logo.png" width="30px" />
      <span class="ml-4 h5 font-weight-bold">Devwares</span>
    </a>
    <small>&copy; Devwares, 2020. All rights reserved.</small>
    <div>
      <button class="btn btn-dark btn-flat">
        <i class="fa fa-facebook"></i>
      </button>
      <button class="btn btn-dark btn-flat">
        <i class="fa fa-twitter"></i>
      </button>
      <button class="btn btn-dark btn-flat">
        <i class="fa fa-instagram"></i>
      </button>
    </div>
  </div>
</footer>
```
