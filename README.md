# px-flexbox-design

The Predix UI Flexbox module creates layout classes to give elements sizes and dynamically put elements in the right place. The `px-flexbox-design` module is a wrapper around all of CSS flexbox's non-unit-based properties. For more information about flexbox, take a look at the excellent CSS-Tricks [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).

## Dependencies

The `px-flexbox-design` module depends on the following modules (automatically included with Bower install):

* [px-functions-design](https://github.com/PredixDev/px-functions-design)

## Installation

Install this module and its dependencies using bower:

    bower install --save px-flexbox-design

Once installed, `@import` into your project's Sass file in its Base layer:

    @import "px-flexbox-design/_base.flexbox.scss";

## Usage

The following variables are available for use in the module:

    $inuit-flexbox-namespace

## Options

The flexbox module exposes many features available in flexbox layouts with simple, easy-to-use classes.

For a full, interactive demo of the available classes and enhanced documentation, take a look at the [flexbox module documentation on the Predix UI catalog](https://predixdev.github.io/predix-ui/?show=px-flexbox-design&type=css).

### Classes for flex containers

#### flex (container)

*Class to set a container to use flexbox. Required to use any of the modifier classes below.*

`.flex` Sets a container to use flex for layout

`.inline--flex` Sets a container to use inline-flex for layout

#### flex-direction

*Classes to change the direction children flow.*

`.flex--row` Lays children out horizontally from right-to-left

`.flex--row--rev` Lays children out horizontally in the reverse direction (from left-to-right). [must be applied with class *.flex--row*]

`.flex--col` Lays children out vertically from top-to-bottom

`.flex--col--rev` Lays children out vertically in the reverse direction (from bottom-to-top) [must be applied with class *.flex--col*]

#### flex-wrap

*Classes to change the wrapping behavior of children.*

`.flex--nowrap` All children will appear on one line

`.flex--wrap` Children will wrap onto multiple lines, from top to bottom

`.flex--wrap--rev` Children will wrap onto multiple lines, from bottom to top

#### justify-content

*Classes to change how children position themsleves within the container's available space. Children will position themselves along the axis you specify with flex-direction.*

`.flex--left` Children are packed at the start of the container. [sets *justify-content: flex-start*]

`.flex--center` Children are packed in the middle the container. [sets *justify-content: center*]

`.flex--right` Children are packed at the end of the container. [sets *justify-content: flex-end*]

`.flex--justify` Children are distributed throughout the container. [sets *justify-content: space-between*]

`.flex--spaced` Children are equally distributed by space around them. [sets *justify-content: space-around*]

#### align-items

*Classes to change how children stick to or fill the container's available space. Children will set or expand themselves across (not along) the axis you specify with flex-direction.*

`.flex--top` Children start at the beginning of the container. [sets *align-items: flex-start*]

`.flex--middle` Children are centered in the container. [sets *align-items: center*]

`.flex--bottom` Children end at the end of the container. [sets *align-items: flex-end*]

`.flex--stretch` Children stretch to fill the container. [sets *align-items: stretch*]

`.flex--baseline` Children align along their baselines. [sets *align-items: baseline*]

#### align-content

*Classes to align children when there is extra space across (not along) the axis you specify with flex-direction. Useful when you have multiple rows or columns of children.*

`.flex--top--multi` Children align themselves at the beginning of the container. [sets *align-content: flex-start*]

`.flex--middle--multi` Children align themselves in the center in the container. [sets *align-content: center*]

`.flex--bottom--multi` Children align themselves at the end of the container. [sets *align-content: flex-end*]

`.flex--stretch--multi` Children stretch themselves to fill the container. [sets *align-content: stretch*]

`.flex--justify--multi` Children distribute themselves throughout the container. [sets *align-content: space-between*]

`.flex--spaced--multi` Children distribute themselves equally throughout the container. [sets *align-content: space-around*]

View the full API [here](http://predixdev.github.io/px-flexbox-design/).

