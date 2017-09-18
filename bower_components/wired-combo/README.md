[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wiredjs/wired-combo)

# \<wired-combo\>

Combobox control - similar to a native browser select element; with a hand-drawn, wireframe like, style.

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-combo.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-combo selected="two">
  <wired-item value="one" text="Number one"></wired-item>
  <wired-item value="two" text="Number two"></wired-item>
  <wired-item value="three" text="Number three"></wired-item>
  <wired-item value="four" text="Number four"></wired-item>
</wired-combo>
<wired-combo selected="one" disabled>
  <wired-item value="one" text="Number one"></wired-item>
  <wired-item value="two" text="Number two"></wired-item>
</wired-combo>
```