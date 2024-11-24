# nu.cdys

*Nanai's Utility collection for CinDY Script*

(originally, `.cdy` is extension of Cinderella project file)

---

## What is this?

let think yourself.

## Overview

explain details of scripts.

### `drawrule.cdys`

draw a rule with `Listplot`.

*concern. name of plot will duplicate on using multiple times*

#### Declaration

```
drawrule(pos, count, step, options)
```

**returns** `___`

| Parameter | Type    | Limitations              | Description               |
|-----------|---------|--------------------------|---------------------------|
| `pos`     | `list`  | length must be `2`       | top left position of rule |
| `count`   | `list`  | length must be `2`       | number of lines           |
| `step`    | `list`  | length must be `2`       | spacing between lines     |
| `options` | `list`  |                          | options for `Listplot`    |
