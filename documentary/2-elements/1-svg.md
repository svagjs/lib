```### svg => string
[
  ["options", "SVGOption"]
]
```

Generate an `svg` element with given content and dimensions.

%TYPEDEF types/elements/svg.xml SVGOptions%

%EXAMPLE: example/elements/svg.js, ../../src => @svag/lib%

%FORK-svg example example/elements/svg%

To generate an `svg` which will not adjust its size to the viewport, the `stretch` option needs to be set to `false`.

%EXAMPLE: example/elements/svg-fixed.js, ../../src => @svag/lib%

%FORK-svg example example/elements/svg-fixed%

%~ width="15"%