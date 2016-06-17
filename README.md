# Media Object #

The media object is an improved version of [@stubbornella's](https://twitter.com/stubbornella) media object.


### Installation ###

```
npm install --save iotacss-media
```


### Dependencies ###

* [Settings.Default](https://github.com/iotacss/settings.default)
* [Tools.Mixins](https://github.com/iotacss/tools.mixins)


### Options ###

```
$iota-media-gutter-default : 10px  !default;
$iota-media-gutter-extra   : ()    !default;
$iota-media--rev           : false !default;  // Enables reverse mode
$iota-media--res           : false !default;  // Enables responsive mode
$iota-media-collapse-at    : 767px !default;  // Text is positioned under image until breakpoint reaches this value. Responsive mode must be enabled for this to work.
$iota-media--table         : false !default;  // Allows vertical positioning of the text. Can be also used with [Align Utility](https://github.com/iotacss/utilities.align).
```


### Classes ###

```
.o-media
  .o-media__fixed
  .o-media__fluid

  // .o-media__image and .o-media__body still supported, but please use o-media__fixed and o-media__fluid instead


// Modifiers

.o-media--rev
.o-media--res
.o-media--table


// Extra gutter sizes

$iota-media-gutter-extra   : (
  small: 5px;
  large: 20px;
);

.o-list--small
.o-list--large
```
