# Flexbox

The Predix Experience Flexbox module assigns classes to each of the non-unit properties currently available in Flexbox. These properties are referenced from CSS-Tricks' [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## Sass Documentation

You can review Sass Documentation here: https://github.build.ge.com/pages/PXd/px-flexbox-design/sassdoc

## Dependency

Px's Flexbox module depends on one other Px module:

* [px-functions-design](https://github.build.ge.com/PXd/px-functions-design)

## Upstream dependency

The Flexbox module is also an upstream dependency in this meta kit:

* [px-starter-kit-design](https://github.build.ge.com/PXd/px-starter-kit-design)

## Installation

Install this module and its dependency using bower:

    bower install --save https://github.build.ge.com/PXd/px-flexbox-design.git

Once installed, `@import` into your project's Sass file in its Base layer:

    @import "px-flexbox-design/_base.flexbox.scss";