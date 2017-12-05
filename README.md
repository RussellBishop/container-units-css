v1.0.0
# Container Units
Take measurements from your container - any depth, any combination.

## How to:
All of the (simple) calculations and variable set ups are at the top.

Change these two variables...

```
:root {
    --ColumnCount: 12;
    --ColumnDecimal: .07;
}
```

And you're ready to build from them with the code that follows.

Every combination can - and _should_ - be adapted for use with:

* margins
* padding
* top
* right
* bottom
* left...

---

## Next releases:

SCSS functions, e.g. `width: colspan(6)`.

Utility builders from SCSS maps, e.g. `$colspanUtilites: (2, 4, 6, 9, 12);`

