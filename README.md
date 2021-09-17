# SCSS-Arrow

```scss
$arrow-size: .35em;

.arrow {
    display: inline-flex;
    border: currentColor solid $arrow-size;
}

.arrow-up {
    border-top: 0;
    border-right-color: transparent;
    border-left-color: transparent;
    vertical-align: calc(#{$arrow-size} / 2);
}

.arrow-down {
    border-bottom: 0;
    border-right-color: transparent;
    border-left-color: transparent;
    vertical-align: calc(#{$arrow-size} / 2);
}

.arrow-left {
    border-left: 0;
    border-top-color: transparent;
    border-bottom-color: transparent;
    vertical-align: baseline;
}

.arrow-right {
    border-right: 0;
    border-top-color: transparent;
    border-bottom-color: transparent;
    vertical-align: baseline;
}
```
