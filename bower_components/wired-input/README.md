[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wiredjs/wired-input)

# \<wired-input\>

A single-line text field with hand-drawn, wireframe like, look. 

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-input.html">
    <style is="custom-style">
      wired-input {
        margin: 5px 0;
        display: block;
      }
      .wider {
        width: 400px;
        padding: 10px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-input></wired-input>
<wired-input placeholder="placeholder" class="wider"></wired-input>
<wired-input type="password" placeholder="Password"></wired-input>
<wired-input disabled placeholder="disabled input"></wired-input>

<style is="custom-style">
  .wider {
    width: 400px;
    padding: 10px;
  }
</style>
```
