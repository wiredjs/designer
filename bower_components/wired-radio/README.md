[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wiredjs/wired-radio)

# \<wired-radio\>

Radio button with hand-drawn look

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-radio.html">
    <style is="custom-style">
      .blue {
        color: #0d47a1;
      }

      .prplgrn {
        color: green;
        --wired-radio-icon-color: purple;
      }
      wired-radio {
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
<wired-radio text="Radio One"></wired-radio>
<wired-radio text="Radio Two" checked></wired-radio>
<wired-radio text="Disabled" disabled></wired-radio>
<wired-radio text="Radio Three" class="blue"></wired-radio>
<wired-radio text="Purple Green" class="prplgrn"></wired-radio>
```

View wired-radio-group to see the case where only one radio is selected.