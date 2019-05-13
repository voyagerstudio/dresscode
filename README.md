# Dress-code
An experimental (meaning: do _not_ use this) mixin-supported alternative to the BEM naming convention.

Use Case:
turns typical BEM classes like this:
```html
<!-- Typical BEM -->
<div class="header--signed-out__logo--dark-mode">
```

into this:
```html
<!-- Dress Code -->
<div class="header~signed-out:logo~dark-mode">
```


examples:
* `<div class="parent">`
* `<div class="parent:child">`
* `<div class="parent~variant:child">`
* `<div class="parent:child~variant">`
* `<div class="parent~variant:child~variant">`
