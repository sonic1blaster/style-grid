# grid
Micro css lib for grid system like bootstrap used. Work only with **webpack**-based apps and only with **stylus**

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
    },
```

2) Include in your main *.js file this: 
```
require('grid');
```

3) Profit!
