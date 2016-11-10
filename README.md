# Media Object #

The media object is an improved version of [@stubbornella's](https://twitter.com/stubbornella) media object.


### Installation ###

```
npm install --save iotacss-obj-media
```


### Options ###

```sass
$iota-obj-media-namespace         : 'media' !default;
$iota-obj-media-fixed-name        : 'fixed' !default;
$iota-obj-media-fluid-name        : 'fluid' !default;
$iota-obj-media-reversed-name     : 'rev' !default;
$iota-obj-media-align-middle-name : 'middle' !default;
$iota-obj-media-align-bottom-name : 'bottom' !default;
$iota-obj-media-responsive-name   : 'res' !default;

$iota-obj-media-gutter-default    : $iota-global-gutter-default !default;
$iota-obj-media-gutter-extra      : () !default;

$iota-obj-media-rev               : false !default;

$iota-obj-media-align             : false !default;

$iota-obj-media-flex              : $iota-global-flex !default;

$iota-obj-media-res               : false !default;
$iota-obj-media-collapse-at       : 767px !default;
```


### Classes ###

```sass
.o-media
  .o-media__fixed
  .o-media__fluid


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
