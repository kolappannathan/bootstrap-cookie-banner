# Bootstrap cookie banner

A cookie banner for websites using Bootstrap 4.

## Demo

[![Live demo](https://img.shields.io/badge/view-Live%20Demo-blue.svg?style=flat-square&logo=microsoft%20edge)](https://kolappannathan.github.io/bootstrap-cookie-banner/)

## Usage

 1. Include the css and js files.
 
```html
<!-- Cookie Banner -->
<link rel="stylesheet" href="./src/cookie-banner.css">
<script async src="./src/cookie-banner.js"></script>
```
 2. Minimum HTML to make it work

```html
<!-- Cookie Banner -->
<div class="nk-cookie-banner alert alert-dark text-center mb-0" role="alert">
  &#x1F36A; This website uses cookies to ensure you get the best experience on our website.
  <a href="https://www.cookiesandyou.com/" target="blank">Learn more</a>
  <button type="button" class="btn btn-primary btn-sm ml-3" onclick="window.nk_hideCookieBanner()">
    I Got It
  </button>
</div>
<!-- End of Cookie Banner -->
```

## Used in

 1. [kolappan.dev](https://kolappan.dev/)
 ![Demo image](./demo/demo.jpg)
