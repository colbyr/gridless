# Gridless

A lightweight, 12-column grid in [Less CSS](http://lesscss.org).
Based on [1140 CSS Grid](http://cssgrid.net/) and [Inuit CSS](http://csswizardry.com/inuitcss).

## Basic Usage

```html
...
<body class="container">
  <div class="row">
    <div class="col-3">
      Three columns
    </div>
    <div class="col-6">
      Six columns
    </div>
    <div class="col-3">
      Three columns
    </div>
  </div>
</body>
...
```

## Things to Note:

1. Keep the `.container` class on `<body>` where possible.
2. Notice unlike many other grids, gridless does use a `.last` class (kudos [csswizardry](http://csswizardry.com)).
3. Elements that overflow into a new row simply wrap into a new one.
4. Configuration options can be set in `grid-config.less`.

