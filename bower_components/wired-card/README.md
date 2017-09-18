# \<wired-card\>

wired-card is s a container for other web elements - with a hand-drawn, wireframe like, look.

<!--
```
<custom-element-demo>
  <template>
    <link href="https://fonts.googleapis.com/css?family=Shadows+Into+Light" rel="stylesheet">
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../wired-input/wired-input.html">
    <link rel="import" href="../wired-radio-group/wired-radio-group.html">
    <link rel="import" href="../wired-radio/wired-radio.html">
    <link rel="import" href="wired-card.html">
    <style is="custom-style">
    wired-card {
        max-width: 500px;
        padding: 10px;
        margin: 5px 0;
      }

      .form {
        font-family: 'Shadows Into Light', sans-serif;
        font-weight: 400;
      }

      wired-input {
        width: 400px;
        margin: 5px 0;
      }

      wired-radio {
        display: inline-block;
        margin: 5px;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-card class="form">
  <h3>Form Title</h3>
  <div>
    <wired-input placeholder="full name"></wired-input>
  </div>
  <div>
    <wired-input placeholder="location"></wired-input>
  </div>
  <wired-radio-group>
    <wired-radio name="male" text="male"></wired-radio>
    <wired-radio name="female" text="female"></wired-radio>
  </wired-radio-group>
</wired-card>
```

## Card elevation

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="wired-card.html">
    <style is="custom-style">
    wired-card {
        max-width: 500px;
        padding: 10px;
        margin: 5px 0;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<wired-card>
  <h3>Elevation: 1 (default)</h3>
</wired-card>
<br/>
<wired-card elevation="2">
  <h3>Elevation: 2</h3>
</wired-card>
<br/>
<wired-card elevation="5">
  <h3>Elevation: 5 (max)</h3>
</wired-card>
```