# SCSS-Arrow

```scss
$arrow-size: .35em;

@mixin arrow {
    display: inline-flex;
    border: currentColor solid $arrow-size;
}

.arrow-up {
    @include arrow;
    border-top: 0;
    border-right-color: transparent;
    border-left-color: transparent;
    vertical-align: calc(#{$arrow-size} / 2);
}

.arrow-down {
    @include arrow;
    border-bottom: 0;
    border-right-color: transparent;
    border-left-color: transparent;
    vertical-align: calc(#{$arrow-size} / 2);
}

.arrow-left {
    @include arrow;
    border-left: 0;
    border-top-color: transparent;
    border-bottom-color: transparent;
    vertical-align: baseline;
}

.arrow-right {
    @include arrow;
    border-right: 0;
    border-top-color: transparent;
    border-bottom-color: transparent;
    vertical-align: baseline;
}
```
