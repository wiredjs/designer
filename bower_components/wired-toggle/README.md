[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wiredjs/wired-toggle)

# \<wired-toggle\>

A toggle button webcomponent  with a sketchy hand drawn look

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-toggle.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-toggle></wired-toggle>
<wired-toggle checked></wired-toggle>
<wired-toggle disabled></wired-toggle>
```

## Customization styles

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-toggle.html">
    <style is="custom-style">
      .customColors {
        --wired-toggle-off-color: red;
        --wired-toggle-on-color: green;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-toggle class="customColors"></wired-toggle>

<style is="custom-style">
  .customColors {
    --wired-toggle-off-color: black;
    --wired-toggle-on-color: red;
  }
</style>
```