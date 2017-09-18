# \<wired-tooltip\>

Tooltip with text that appears on hover over an element. It will be centered to an anchor element specified in the 'for' attribute, or, if that doesn't exist, centered to the parent node containing it.

```html
<div class="container">
  <div class="inline">
    <button>Click me!</button>
    <wired-tooltip text="Below"></wired-tooltip>
  </div>
  <button id="btn">Click me!</button>
  <wired-tooltip position="top" for="btn" text="Above"></wired-tooltip>
  <button id="lb">Click me!</button>
  <wired-tooltip position="left" for="lb" text="Left"></wired-tooltip>
  <button id="rb">Click me!</button>
  <wired-tooltip position="right" for="rb" text="Right"></wired-tooltip>
</div>
```


## Styling tooltip

```html
<div class="container">
  <div class="inline">
    <button>Click me!</button>
    <wired-tooltip class="colored" text="Fancy tooltip"></wired-tooltip>
  </div>
</div>
```