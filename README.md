# [style-grid]
Library with a grid for the layout based on **Bootstrap**. For easy use and configuration using **webpack**

## How to use

1) Define in webpack.config file default grid variables like this:
```
stylus: {
  define: {
    $grid_columns: 24,
    $grid_gutter_width: 12,
    $screen_xs: 320,
    $screen_sm: 640,
    $screen_md: 960,
    $screen_lg: 1280
  }
}
```

2) Include in your main *.js file this:
```
require('style-grid');
```

3) Now you can use the already known classes. For example:
```
// jade
.container-fluid
  .row
    .col-lg-18
      | This is text inside container

    .col-lg-6
      | This is text inside container
```

## Additionally

Helpers included:
```
.clearfix
.center-block
.pull-right
.pull-left
.hide
.show
.invisible
.text-hide
.hidden
.affix
```