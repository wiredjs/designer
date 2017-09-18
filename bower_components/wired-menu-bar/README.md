[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wiredjs/wired-menu-bar)

# \<wired-menu-bar\>

A simple menu bar with hand drawn look and feel. 
Use with [wired-menu-item](https://www.webcomponents.org/element/wiredjs/wired-menu-item)

Only supports one level of menu item nesting

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../wired-menu-item/wired-menu-item.html">
    <link rel="import" href="wired-menu-bar.html">
    <style is="custom-style">
      wired-menu-bar {
        margin-bottom: 110px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-menu-bar>
  <wired-menu-item text="File">
    <wired-menu-item text="New"></wired-menu-item>
    <wired-menu-item text="Save"></wired-menu-item>
    <wired-menu-item text="Quit"></wired-menu-item>
  </wired-menu-item>
  <wired-menu-item text="Edit">
    <wired-menu-item text="Cut"></wired-menu-item>
    <wired-menu-item text="Copy"></wired-menu-item>
    <wired-menu-item text="Paste"></wired-menu-item>
  </wired-menu-item>
  <wired-menu-item text="Window"></wired-menu-item>
  <wired-menu-item text="Help"></wired-menu-item>
  <wired-menu-item disabled text="Disabled"></wired-menu-item>
</wired-menu-bar>
```