[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wiredjs/wired-progress)

# \<wired-progress\>

A progress indicator control with a hand-drawn wireframe look.

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-progress.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-progress value="25"></wired-progress>
<wired-progress value="10" min="5" max="15"></wired-progress>
```

## Customizing wired-progress

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-progress.html">
    <style is="custom-style">
      .coloredProgress {
        --wired-progress-color: rgba(220, 0, 50, 0.1);
        --wired-progress-label-color: green;
        --wired-progress-font-size: 24px;
        width: 300px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-progress value="65" percentage></wired-progress>
<wired-progress class="coloredProgress" value="30"></wired-progress>

<style is="custom-style">
  .coloredProgress {
    --wired-progress-color: rgba(220, 0, 50, 0.1);
    --wired-progress-label-color: green;
    --wired-progress-font-size: 24px;
    width: 300px;
  }
</style>
```