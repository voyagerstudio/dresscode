# Dresscode
An experimental (meaning: do _not_ use this) mixin-supported alternative to the BEM naming convention.


![Gif of Jeff Goldblum in Jurrassic Park with the quote "Your scientists were so preoccupied with whether or not they could, they never stopped to think if they should"](https://media.giphy.com/media/mCClSS6xbi8us/giphy.gif)

[Demo of Dresscode in use, from the example case included in the repo.](https://codepen.io/taurean/pen/LobYWv?editors=1100)

---

Use Case:
turns typical BEM classes like this:
```html
<!-- Typical BEM -->
<div class="header--signed-out__logo--dark-mode">
```

into this:
```html
<!-- Dresscode -->
<div class="header~signed-out:logo~dark-mode">
```


examples:
* `<div class="parent">`
* `<div class="parent:child">`
* `<div class="parent~variant:child">`
* `<div class="parent:child~variant">`
* `<div class="parent~variant:child~variant">`

