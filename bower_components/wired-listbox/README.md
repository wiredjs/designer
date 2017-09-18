[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wiredjs/wired-listbox)

# \<wired-listbox\>

A listbox control with Wired hand-drawn styling. The selected item is highlighted. Can be vertical (default) or horizontal.

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../wired-item/wired-item.html">
    <link rel="import" href="wired-listbox.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-listbox>
  <wired-item value="one" text="No. one"></wired-item>
  <wired-item value="two" text="No. two"></wired-item>
  <wired-item value="three" text="No. three"></wired-item>
  <wired-item value="four" text="No. four"></wired-item>
</wired-listbox>
```

## Customizing listbox

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../wired-item/wired-item.html">
    <link rel="import" href="wired-listbox.html">
    <style is="custom-style">
      .custonListBox {
        --wired-combo-item-selected-bg: #fff59d;
        --wired-combo-item-hover-bg: #9df59d;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-listbox horizontal class="custonListBox" selected="two">
  <wired-item value="one" text="No. one"></wired-item>
  <wired-item value="two" text="No. two"></wired-item>
  <wired-item value="three" text="No. three"></wired-item>
  <wired-item value="four" text="No. four"></wired-item>
</wired-listbox>

<style is="custom-style">
  .custonListBox {
    --wired-combo-item-selected-bg: #fff59d;
    --wired-combo-item-hover-bg: #9df59d;
  }
</style>
```