## Lint Problem ID Index for v.0.x

### Warnings

Warnings represents *potential* errors. **They may have false-positives.**

* [[W001]] (`<meta charset="UTF-8">`)
* [[W002]] (X-UA-Compatible)
* [[W003]] (`<meta name="viewport">`)
* [[W004]] (deprecated remote modal)
* [[W005]] (jQuery)
* [[W006]] (disabled tooltip or popover)
* [[W007]] (`<button>` missing `type` attribute)
* [[W008]] (tooltip/popover in `.btn-group` requires `container: 'body'`)
* [[W009]] (empty spacer column)
* [[W010]] (`.pull-left` or `.pull-right` in `.media`)
* [[W011]] (Reserved for #188 / #189)
* [[W012]] (navbar missing inner container)
* [[W013]] (Outdated version of Bootstrap)
* [[W014]] (Incorrect carousel targets)
* [[W015]] (Unreleased major version of Bootstrap)
* [[W016]] (Perhaps you meant to use the `[disabled]` attribute instead of the `.disabled` class on a `.btn`)
* [[W017]] (`<input>` missing `type` attribute)
* [[W018]] (`.col-*-12` classes used alone are not useful)

### Errors

Errors represent definite errors. Under the assumptions explained in [the "Caveats" section of the README](https://github.com/twbs/bootlint/blob/master/README.md#caveats), they should never have any false-positives.

* [[E001]] (HTML5 `DOCTYPE` required)
* [[E002]] (Bootstrap v2 grid)
* [[E003]] (misplaced `.row`)
* [[E004]] (nested containers)
* [[E005]] (`.row.col-*-*`)
* [[E006]] (non-`<input>` `.form-control` within `.input-group`)
* [[E007]] (`bootstrap.js` & `bootstrap.min.js`)
* E008 was replaced by [[W008]]
* [[E009]] (forgot about `input-group-sm`/`input-group-lg`)
* [[E010]] (input group with multiple `.form-control`s)
* [[E011]] (`.form-group.input-group`)
* [[E012]] (`.input-group.col-*-*`)
* [[E013]] (row children must be columns)
* [[E014]] (column parent must be a row)
* [[E015]] (multiple add-ons on a single side of an input group)
* [[E016]] (dropdown within button group)
* [[E017]] (`.checkbox`)
* [[E018]] (`.radio`)
* [[E019]] (`.checkbox-inline`)
* [[E020]] (`.radio-inline`)
* [[E021]] (`.active` & `[checked]`)
* [[E022]] (modal within another component)
* [[E023]] (wrong `.panel-body` parent)
* [[E024]] (wrong `.panel-heading` parent)
* [[E025]] (wrong `.panel-footer` parent)
* [[E026]] (wrong `.panel-title` parent)
* [[E027]] (`table.table-responsive`)
* [[E028]] (`.form-control-feedback` missing `.has-feedback`)
* [[E029]] (redundant grid column classes)
* [[E030]] (`.glyphicon-*` without `.glyphicon`)
* [[E031]] (`.glyphicon` on element with content or children)
* [[E032]] (incorrectly structured modal markup)
* [[E033]] (`.alert` with dismiss button missing `.alert-dismissible`)
* [[E034]] (`.close` button is present but isn't first element in `.alert`)
* [[E035]] (`.form-horizontal` or `.form-inline` on `.form-group`)
* ~~[[E036]] (Multiple `.btn`s or `.dropdown-menu`s in one `.input-group-btn`)~~
* [[E037]] (`.col-*-0` classes)
* [[E038]] (`.media-left`/`.media-right` outside of `.media`)
* [[E039]] (`.navbar-left`/`.navbar-right` outside of `.navbar`)
* [[E040]] (`.modal.hide`)
* [[E041]] (incorrectly structured carousel markup)
* [[E042]] (`.form-control` on wrong element or `<input>` of wrong `type`)
* [[E043]] (btn classes on `<a>`s within `.navbar-nav`s)
* [[E044]] (`.input-group` must have a `.form-control` and either an add-on or a btn)
* [[E045]] (`.img-responsive` on non-`<img>`)
* [[E046]] (`.modal` missing `[tabindex]`)
* [[E047]] (Used `.btn` on something other than an `<a>`/`<button>`/`<input>`/`<label>`)
* [[E048]] (`.modal` missing `[role="dialog"]`)
* [[E049]] (`.modal-dialog` missing `[role="document"]`)
* [[E050]](`.form-group`s cannot be nested)
* [[E051]](`.pull-right` and `.pull-left` classes, and manual style attributes with `float: left` or `float: right` are not allowed on `.col-*-*` elements)
* [[E052]](`.pull-right` and `.pull-left` classes, and manual `style` attributes with `float: left` or `float: right` are not allowed on `.row` elements)


## Lint Problem ID Index for v.1.x (Bootlint for Bootstrap v4 and newer)

### Warnings

Warnings represents *potential* errors. **They may have false-positives.**

* [[W001]] (`<meta charset="UTF-8">`)
* ~~[[W002]] (X-UA-Compatible)~~
* [[W003]] (`<meta name="viewport">`)
* ~~[[W004]] (deprecated remote modal)~~
* [[W005]] (jQuery)
* [[W006]] (disabled tooltip or popover)
* [[W007]] (`<button>` missing `type` attribute)
* [[W008]] (tooltip/popover in `.btn-group` requires `container: 'body'`)
* [[W009]] (empty spacer column)
* ~~[[W010]] (`.pull-left` or `.pull-right` in `.media`)~~
* [[W011]] (Reserved for #188 / #189)
* [[W012]] (navbar missing inner container)
* [[W013]] (Outdated version of Bootstrap)
* [[W014]] (Incorrect carousel targets)
* ~~[[W015]] (Unreleased major version of Bootstrap)~~
* [[W016]] (Perhaps you meant to use the `[disabled]` attribute instead of the `.disabled` class on a `.btn`)
* [[W017]] (`<input>` missing `type` attribute)
* [[W018]] (`.col-*-12` classes used alone are not useful)

### Errors

Errors represent definite errors. Under the assumptions explained in [the "Caveats" section of the README](https://github.com/twbs/bootlint/blob/master/README.md#caveats), they should never have any false-positives.

* [[E001]] (HTML5 `DOCTYPE` required)
* ~~[[E002]] (Bootstrap v2 grid)~~
* [[E003]] (misplaced `.row`)
* ~~[[E004]] (nested containers)~~
* [[E005]] (`.row.col-*-*`)
* [[E006]] (non-`<input>` `.form-control` within `.input-group`)
* [[E007]] (`bootstrap.js` & `bootstrap.min.js`)
* [[E009]] (forgot about `input-group-sm`/`input-group-lg`)
* [[E010]] (input group with multiple `.form-control`s)
* [[E011]] (`.form-group.input-group`)
* [[E012]] (`.input-group.col-*-*`)
* [[E013]] (row children must be columns)
* [[E014]] (column parent must be a row)
* [[E015]] (multiple add-ons on a single side of an input group)
* [[E016]] (dropdown within button group)
* [[E017]] (`.checkbox`)
* [[E018]] (`.radio`)
* [[E019]] (`.checkbox-inline`)
* [[E020]] (`.radio-inline`)
* [[E021]] (`.active` & `[checked]`)
* [[E022]] (modal within another component)
* [[E023]] (wrong `.panel-body` parent)
* [[E024]] (wrong `.panel-heading` parent)
* [[E025]] (wrong `.panel-footer` parent)
* [[E026]] (wrong `.panel-title` parent)
* [[E027]] (`table.table-responsive`)
* [[E028]] (`.form-control-feedback` missing `.has-feedback`)
* [[E029]] (redundant grid column classes)
* ~~[[E030]] (`.glyphicon-*` without `.glyphicon`)~~
* ~~[[E031]] (`.glyphicon` on element with content or children)~~
* [[E032]] (incorrectly structured modal markup)
* [[E033]] (`.alert` with dismiss button missing `.alert-dismissible`)
* [[E034]] (`.close` button is present but isn't first element in `.alert`)
* [[E035]] (`.form-horizontal` or `.form-inline` on `.form-group`)
* [[E037]] (`.col-*-0` classes)
* ~~[[E038]] (`.media-left`/`.media-right` outside of `.media`)~~
* [[E039]] (`.navbar-left`/`.navbar-right` outside of `.navbar`)
* ~~[[E040]] (`.modal.hide`)~~
* [[E041]] (incorrectly structured carousel markup)
* [[E042]] (`.form-control` on wrong element or `<input>` of wrong `type`)
* [[E043]] (btn classes on `<a>`s within `.navbar-nav`s)
* [[E044]] (`.input-group` must have a `.form-control` and either an add-on or a btn)
* [[E045]] (`.img-responsive` on non-`<img>`)
* [[E046]] (`.modal` missing `[tabindex]`)
* [[E047]] (Used `.btn` on something other than an `<a>`/`<button>`/`<input>`/`<label>`)
* [[E048]] (`.modal` missing `[role="dialog"]`)
* [[E049]] (`.modal-dialog` missing `[role="document"]`)
* [[E050]](`.form-group`s cannot be nested)
* [[E051]](`.pull-right` and `.pull-left` classes, and manual style attributes with `float: left` or `float: right` are not allowed on `.col-*-*` elements)
* [[E052]](`.pull-right` and `.pull-left` classes, and manual `style` attributes with `float: left` or `float: right` are not allowed on `.row` elements)