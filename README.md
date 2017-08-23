# less-mq
A LESS mixin for media queries

## Examples
```
.mq(phone; {
    background-color: indigo;
});

.mq(from; tablet; {
    background-color: khaki;
});

.mq(to; tablet-wide; {
    background-color: tomato;
});

.mq(from; desktop; to; desktop-wide; {
    background-color: magenta;
});
