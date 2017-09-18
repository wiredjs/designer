[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wiredjs/wired-slider)

# \<wired-slider\>

A sketchy slider which allows user to select a value from a range by moving the slider thumb.

Range can be set using the min, max value. Default range is 0-100.

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-slider.html">
    <style is="custom-style">
      wired-slider {
        display: block;
        margin: 5px 0;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-slider></wired-slider>
<wired-slider value="40"></wired-slider>
<wired-slider value="60" disabled></wired-slider>
```

## Styling

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-slider.html">
    <style is="custom-style">
      wired-slider {
        display: block;
        margin: 5px 0;
      }
      .custom {
        width: 400px;
        --wired-slider-knob-color: green;
        --wired-slider-knob-zero-color: red;
        --wired-slider-bar-color: blue;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-slider value="10"></wired-slider>
<wired-slider value="10" min="5" max="15"></wired-slider>
<wired-slider class="custom" value="25"></wired-slider>

<style is="custom-style">
  .custom {
    width: 400px;
    --wired-slider-knob-color: green;
    --wired-slider-knob-zero-color: red;
    --wired-slider-bar-color: blue;
  }
</style>
```