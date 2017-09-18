[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wiredjs/wired-checkbox)

# \<wired-checkbox\>

Checkbox webcomponent with hand-drawn sketchy look.

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-checkbox.html">
    <style is="custom-style">
      wired-checkbox {
        margin: 5px 0;
        font-family: "Roboto", sans-serif;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-checkbox text="Cheddar"></wired-checkbox>
<wired-checkbox text="Swiss cheese" checked></wired-checkbox>
<wired-checkbox disabled text="Disabled"></wired-checkbox>
```

## Styling

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-checkbox.html">
    <style is="custom-style">
      wired-checkbox {
        margin: 5px 0;
        font-family: "Roboto", sans-serif;
      }
      .blue {
        color: #0d47a1;
      }
      .redgreen {
        color: green;
        --wired-checkbox-icon-color: red;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-checkbox class="blue" text="Blue checkbox"></wired-checkbox>
<wired-checkbox class="redgreen" text="Red + Green"></wired-checkbox>
<style is="custom-style">
  .blue {
    color: #0d47a1;
  }
  .redgreen {
    color: green;
    --wired-checkbox-icon-color: red;
  }
</style>
```