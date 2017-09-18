[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wiredjs/wired-icon-button)

# \<wired-icon-button\>

This is a round button with an image placed at the center. Image could also be in icon, more specifically an icon as as [iron-icon](https://www.webcomponents.org/element/PolymerElements/iron-icon).

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../iron-icons/iron-icons.html">
    <link rel="import" href="wired-icon-button.html">
    <style is="custom-style">
      wired-icon-button {
        margin: 0 10px;
      }

      .big {
        width: 60px;
        height: 60px;
      }

      .red {
        color: red;
      }

      .pinkbg {
        color: red;
        --wired-icon-bg-color: pink;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-icon-button icon="favorite"></wired-icon-button>
<wired-icon-button class="red" icon="favorite"></wired-icon-button>
<wired-icon-button class="pinkbg" icon="favorite"></wired-icon-button>
<wired-icon-button class="big" icon="favorite"></wired-icon-button>
<wired-icon-button icon="favorite" disabled></wired-icon-button>
```