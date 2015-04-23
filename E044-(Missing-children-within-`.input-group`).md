# E044

## `.input-group` must have a `.form-control` and either `.input-group-addon` or `.input-group-btn`.

`.input-group`s are meant to contain both a `.form-control` and at least one addon such as `.input-group-addon` or `.input-group-btn`. Omitting the addon can cause the `.form-control` to lose styling. Omitting the control doesn't make sense and causes some styles to be lost. Ensure you have all the required element with the correct classes within an `.input-group`.

Wrong:

```html
<div class="input-group">
  <input type="text" class="form-control" placeholder="Username" aria-describedby="basic-addon1">
</div>

<div class="input-group">
  <span class="input-group-addon" id="basic-addon1">@</span>
</div>
```

Right:

```html
<div class="input-group">
  <span class="input-group-addon" id="basic-addon1">@</span>
  <input type="text" class="form-control" placeholder="Username" aria-describedby="basic-addon1">          
</div>

<div class="input-group">
  <input type="text" class="form-control" placeholder="Search for...">
  <span class="input-group-btn">
    <button class="btn btn-default" type="button">Go!</button>
  </span>
</div>
```