### Install bootstrap css

Add the link inside head tag in a required html file.

```html
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
  rel="stylesheet"
  integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
  crossorigin="anonymous"
/>
```

### Creating grid/row/col in bootstrap

To create css grid using bootstrap we need a row and column inside the row.
Following code shows 1x3 grid

```html
<!-- (.row .col) -->
<div class="row">
  <div class="col">this is colum</div>
  <div class="col">this is colum</div>
  <div class="col">this is colum</div>
</div>
```

### Creating button using bootstraps css

- bootstrap has primary, secondary, sucess, info, danger, warn button
- Three size of button: small(sm), medium(md), large(lg)
- Outline button has only line around it. `btn-outline-primary`
- To make button round add class: `rounded-1`. Radius 1 to 5

```html
<!-- example primary button(button.btn.btn-primary) -->
<button class="btn btn-primary">click me</button>
<!-- example large button -->
<button classs="" btn btn-primary btn-lg>login</button>
<!-- example outline danger button(button.btn.btn-outline-danger) -->
<button classs="" btn btn-outline-danger>login</button>
```
