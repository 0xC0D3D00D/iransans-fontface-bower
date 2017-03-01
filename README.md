 > Notice! Since this font family is licensed, This package does not include the fonts itself, you have to download it from the producer website. This package only supports IRANSans v4.

# IRANSans fontface

A simple package providing the [IRANSans](http://fontiran.com/%D8%AE%D8%A7%D9%86%D9%88%D8%A7%D8%AF%D9%87-%D9%81%D9%88%D9%86%D8%AA-%D8%A7%DB%8C%D8%B1%D8%A7%D9%86/) fontface. The font was created by [Moslem Ebrahimi](http://www.moslemebrahimi.com/).

## Installing

Assuming you have [NodeJS](http://nodejs.org/), [NPM](https://www.npmjs.com/) and [Bower](http://bower.io/) installed globally just open up a terminal, navigate to your projects root directory and then execute

```
# install via NPM
$ npm install iransans-fontface --save

# install via Bower
$ bower install iransans-fontface --save
```

Since the font is licensed you have to download the fonts from the [producer website](http://fontiran.com/%D8%AE%D8%A7%D9%86%D9%88%D8%A7%D8%AF%D9%87-%D9%81%D9%88%D9%86%D8%AA-%D8%A7%DB%8C%D8%B1%D8%A7%D9%86/) and then put all the web fonts in `fonts/IRANSansWeb`.

Also you need to rename regular fonts:
```
mv fonts/IRANSansWeb/IRANSansWeb.ttf fonts/IRANSansWeb/IRANSansWeb_Regular.ttf
mv fonts/IRANSansWeb/IRANSansWeb.eot fonts/IRANSansWeb/IRANSansWeb_Regular.eot
mv fonts/IRANSansWeb/IRANSansWeb.woff fonts/IRANSansWeb/IRANSansWeb_Regular.woff
mv fonts/IRANSansWeb/IRANSansWeb.woff2 fonts/IRANSansWeb/IRANSansWeb_Regular.woff2

```

## Usage

There're several files in the `css/` subdirectory. Import them in your project
to have access to "IRANSans" font face:

* `css/iransans/iransans-fontface.css` - whole font family compiled to CSS
* `css/iransans/sass/iransans-fontface.scss` - whole font family in SCSS
* `css/iransans/less/iransans-fontface.less` - whole font family in LESS

Importing whole family may be unnecessary and lead to huge build, so if you are
using SCSS or LESS, you can import only individual weights by importing for example:

* `css/iransans/sass/iransans-fontface-bold.scss`
* `css/iransans/sass/iransans-fontface-bold-italic.scss`

## Hinting

Some of the included font files have [hinting](http://en.wikipedia.org/wiki/Font_hinting).

| Files    | Hinting |
|----------|---------|
| `.eot`   | ?       |
| `.svg`   | no      |
| `.ttf`   | ?       |
| `.woff`  | yes     |
| `.woff2` | ?       |

## Apperciation

This package is based on the Roboto font face package by [Christian Hoffmeister](http://choffmeister.de/) which you can find [the original package here](https://github.com/choffmeister/roboto-fontface-bower).
