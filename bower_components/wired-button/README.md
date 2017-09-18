[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/wiredjs/wired-button)

# \<wired-button\>

Hand drawn Button component

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-button.html">
    <style is="custom-style">
      .blue {
        color: #0d47a1;
      }
      .big {
        padding: 20px;
      }
      .yellowbg {
        background: #fff59d;
      }
      wired-button {
        margin: 0 5px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-button text="Button One"></wired-button>
<wired-button class="blue big" text="Button Two"></wired-button>
<wired-button class="yellowbg" text="Button Three"></wired-button>
<wired-button disabled text="Disabled"></wired-button>
```

## Button elevation

Default elevation: 1
Max elevation: 5

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-button.html">
    <style is="custom-style">
      wired-button {
        margin: 0 5px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-button text="Elevation 1"></wired-button>
<wired-button elevation="2" text="Elevation 2"></wired-button>
<wired-button elevation="3" text="Elevation 3"></wired-button>
<wired-button elevation="4" text="Elevation 4"></wired-button>
<wired-button elevation="5" text="Elevation 5"></wired-button>
```
