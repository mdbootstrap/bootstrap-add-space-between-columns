# How to add space between columns in Bootstrap?

To add space between columns in Bootstrap use gutter classes. With gutters you can add horizontal or vertical space or even specify how big space should be on different screen size.

### How they work

* **Gutters are the gaps between column content, created by horizontal** `padding`. We set `padding-right` and `padding-left` on each column, and use negative `margin` to offset that at the start and end of each row to align content.
* **Gutters start at** `1.5rem` (`24px`) **wide**. This allows us to match our grid to the [padding and margin](https://mdbootstrap.com/docs/standard/utilities/spacing/) spacers scale.
* Gutters can be responsively adjusted. Use breakpoint-specific gutter classes to modify horizontal gutters, vertical gutters, and all gutters.

## Horizontal gutters

`.gx-*` classes can be used to control the horizontal gutter widths. The `.container` or `.container-fluid` parent may need to be adjusted if larger gutters are used too to avoid unwanted overflow, using a matching padding utility.

```html
<div class="container px-4">
  <div class="row gx-5">
    <div class="col">
      <div class="p-3">Custom column padding</div>
    </div>
    <div class="col">
      <div class="p-3">Custom column padding</div>
    </div>
  </div>
</div>
```
#### Much more examples and a detailed description can be found at [📄 Documentation page](https://mdbootstrap.com/how-to/bootstrap/columns-space/)



