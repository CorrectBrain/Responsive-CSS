# Chapter 7: Flexible Media: Images, Art Direction, & Scalable Graphics

This chapter contains 31 questions and 77 paired LuaLaTeX/PDF visualizations.

## Questions

### Q01: Architecturally, what defines the "intrinsic dimensions" of an image asset, and why do raw binary images violently override CSS Layout Tracks by default if left unconstrained?

- Example 1: [LuaLaTeX](q01-intrinsic-image-dimensions/diagram-01.tex) · [PDF](q01-intrinsic-image-dimensions/diagram-01.pdf)
- Example 2: [LuaLaTeX](q01-intrinsic-image-dimensions/diagram-02.tex) · [PDF](q01-intrinsic-image-dimensions/diagram-02.pdf)
- Example 3: [LuaLaTeX](q01-intrinsic-image-dimensions/diagram-03.tex) · [PDF](q01-intrinsic-image-dimensions/diagram-03.pdf)

### Q02: Why does applying `width: 100%` mathematically force a low-resolution image to upscale and heavily pixelate if placed inside a container larger than its native file size?

- Example 1: [LuaLaTeX](q02-width-100-upscaling/diagram-01.tex) · [PDF](q02-width-100-upscaling/diagram-01.pdf)
- Example 2: [LuaLaTeX](q02-width-100-upscaling/diagram-02.tex) · [PDF](q02-width-100-upscaling/diagram-02.pdf)
- Example 3: [LuaLaTeX](q02-width-100-upscaling/diagram-03.tex) · [PDF](q02-width-100-upscaling/diagram-03.pdf)

### Q03: Conversely, how does `max-width: 100%` structurally set an algorithmic ceiling, allowing the image to dynamically scale down within tight columns but mathematically refuse to stretch beyond its physical source resolution?

- Example 1: [LuaLaTeX](q03-max-width-100/diagram-01.tex) · [PDF](q03-max-width-100/diagram-01.pdf)
- Example 2: [LuaLaTeX](q03-max-width-100/diagram-02.tex) · [PDF](q03-max-width-100/diagram-02.pdf)

### Q04: How does the universal pairing of `height: auto` dynamically recalculate the bounding box's Y-axis on the fly to permanently preserve the geometric aspect ratio during fluid scaling?

- Example 1: [LuaLaTeX](q04-height-auto-aspect-ratio/diagram-01.tex) · [PDF](q04-height-auto-aspect-ratio/diagram-01.pdf)
- Example 2: [LuaLaTeX](q04-height-auto-aspect-ratio/diagram-02.tex) · [PDF](q04-height-auto-aspect-ratio/diagram-02.pdf)
- Example 3: [LuaLaTeX](q04-height-auto-aspect-ratio/diagram-03.tex) · [PDF](q04-height-auto-aspect-ratio/diagram-03.pdf)

### Q05: Historically, before modern CSS specs, why did flexible responsive images intrinsically trigger brutal layout thrashing (Cumulative Layout Shift) upon downloading?

- Example 1: [LuaLaTeX](q05-cumulative-layout-shift/diagram-01.tex) · [PDF](q05-cumulative-layout-shift/diagram-01.pdf)
- Example 2: [LuaLaTeX](q05-cumulative-layout-shift/diagram-02.tex) · [PDF](q05-cumulative-layout-shift/diagram-02.pdf)
- Example 3: [LuaLaTeX](q05-cumulative-layout-shift/diagram-03.tex) · [PDF](q05-cumulative-layout-shift/diagram-03.pdf)

### Q06: Mathematically, how did the infamous "padding-bottom hack" (`padding-bottom: 56.25%`) create pure geometric scaffolding to fake a 16:9 box model structure before the image even requested a server payload?

- Example 1: [LuaLaTeX](q06-padding-bottom-hack/diagram-01.tex) · [PDF](q06-padding-bottom-hack/diagram-01.pdf)
- Example 2: [LuaLaTeX](q06-padding-bottom-hack/diagram-02.tex) · [PDF](q06-padding-bottom-hack/diagram-02.pdf)
- Example 3: [LuaLaTeX](q06-padding-bottom-hack/diagram-03.tex) · [PDF](q06-padding-bottom-hack/diagram-03.pdf)

### Q07: How does passing hard-coded HTML width and height attributes (`<img width="800" height="400">`) now allow the browser's User Agent pre-parser to conceptually calculate the proportional fraction and block out empty layout space milliseconds before CSS execution?

- Example 1: [LuaLaTeX](q07-html-width-height-attributes/diagram-01.tex) · [PDF](q07-html-width-height-attributes/diagram-01.pdf)
- Example 2: [LuaLaTeX](q07-html-width-height-attributes/diagram-02.tex) · [PDF](q07-html-width-height-attributes/diagram-02.pdf)
- Example 3: [LuaLaTeX](q07-html-width-height-attributes/diagram-03.tex) · [PDF](q07-html-width-height-attributes/diagram-03.pdf)

### Q08: Mechanically, how does the modern CSS `aspect-ratio: 16 / 9` specification supersede legacy attributes by algorithmically decoupling structural height behavior from physical image dimension limitations?

- Example 1: [LuaLaTeX](q08-css-aspect-ratio/diagram-01.tex) · [PDF](q08-css-aspect-ratio/diagram-01.pdf)
- Example 2: [LuaLaTeX](q08-css-aspect-ratio/diagram-02.tex) · [PDF](q08-css-aspect-ratio/diagram-02.pdf)
- Example 3: [LuaLaTeX](q08-css-aspect-ratio/diagram-03.tex) · [PDF](q08-css-aspect-ratio/diagram-03.pdf)

### Q09: Architecturally, how does `object-fit: cover` entirely sever the relationship between the actual HTML `<img/>` box model container and the rendered graphical payload within it?

- Example 1: [LuaLaTeX](q09-object-fit-cover/diagram-01.tex) · [PDF](q09-object-fit-cover/diagram-01.pdf)
- Example 2: [LuaLaTeX](q09-object-fit-cover/diagram-02.tex) · [PDF](q09-object-fit-cover/diagram-02.pdf)
- Example 3: [LuaLaTeX](q09-object-fit-cover/diagram-03.tex) · [PDF](q09-object-fit-cover/diagram-03.pdf)

### Q10: Mathematically, how does the `object-fit: contain` engine evaluate the disparate dimensional X and Y variables between the graphical image and the CSS layout container, explicitly pausing interpolation the moment either boundary edge is touched?

- Example 1: [LuaLaTeX](q10-object-fit-contain/diagram-01.tex) · [PDF](q10-object-fit-contain/diagram-01.pdf)
- Example 2: [LuaLaTeX](q10-object-fit-contain/diagram-02.tex) · [PDF](q10-object-fit-contain/diagram-02.pdf)
- Example 3: [LuaLaTeX](q10-object-fit-contain/diagram-03.tex) · [PDF](q10-object-fit-contain/diagram-03.pdf)

### Q11: If `object-fit: cover` inherently enforces a structural "crop," conceptually, how does adjusting coordinate values in `object-position: 50% 20%` map internal offsets, allowing developers to mathematically pin an algorithmic focus-point (e.g., locking a person's face into view) as a responsive grid stretches wildly around it?

- Example 1: [LuaLaTeX](q11-object-position/diagram-01.tex) · [PDF](q11-object-position/diagram-01.pdf)
- Example 2: [LuaLaTeX](q11-object-position/diagram-02.tex) · [PDF](q11-object-position/diagram-02.pdf)

### Q12: Conceptually, why does executing responsive resolution switching entirely within CSS `@media` queries (`background-image`) create a critical render-blocking paradox for mobile latency?

- Example 1: [LuaLaTeX](q12-css-media-query-image-switching/diagram-01.tex) · [PDF](q12-css-media-query-image-switching/diagram-01.pdf)
- Example 2: [LuaLaTeX](q12-css-media-query-image-switching/diagram-02.tex) · [PDF](q12-css-media-query-image-switching/diagram-02.pdf)

### Q13: How does shifting algorithmic payload decisions into the HTML layer using `srcset` natively unlock the browser’s multi-threaded "speculative pre-parser," completely bypassing the wait for the CSS Object Model tree generation?

- Example 1: [LuaLaTeX](q13-srcset-speculative-parser/diagram-01.tex) · [PDF](q13-srcset-speculative-parser/diagram-01.pdf)
- Example 2: [LuaLaTeX](q13-srcset-speculative-parser/diagram-02.tex) · [PDF](q13-srcset-speculative-parser/diagram-02.pdf)

### Q14: When an `<img>` tag leverages density multipliers (e.g., `srcset="image-1x.jpg 1x, image-2x.jpg 2x"`), how does this strictly command the rendering engine to evaluate *hardware density grid metrics* completely irrespective of the fluid layout width of the actual webpage?

- Example 1: [LuaLaTeX](q14-srcset-density-descriptors/diagram-01.tex) · [PDF](q14-srcset-density-descriptors/diagram-01.pdf)
- Example 2: [LuaLaTeX](q14-srcset-density-descriptors/diagram-02.tex) · [PDF](q14-srcset-density-descriptors/diagram-02.pdf)

### Q15: Mathematically, why does supplying purely `x`-based resolutions mathematically fail and lead to enormous, wasteful payload downloads when placing highly dynamic images inside wildly stretching CSS Grid components?

- Example 1: [LuaLaTeX](q15-density-descriptor-limitations/diagram-01.tex) · [PDF](q15-density-descriptor-limitations/diagram-01.pdf)
- Example 2: [LuaLaTeX](q15-density-descriptor-limitations/diagram-02.tex) · [PDF](q15-density-descriptor-limitations/diagram-02.pdf)

### Q16: How do Width descriptors (e.g., `800w`, `1200w`) conceptually document the actual native width of the asset within the `srcset`, completely divorcing the data array from specific hardware pixel-ratio commands?

- Example 1: [LuaLaTeX](q16-srcset-width-descriptors/diagram-01.tex) · [PDF](q16-srcset-width-descriptors/diagram-01.pdf)
- Example 2: [LuaLaTeX](q16-srcset-width-descriptors/diagram-02.tex) · [PDF](q16-srcset-width-descriptors/diagram-02.pdf)
- Example 3: [LuaLaTeX](q16-srcset-width-descriptors/diagram-03.tex) · [PDF](q16-srcset-width-descriptors/diagram-03.pdf)

### Q17: Architecturally, why is an array of `w` values entirely useless and mathematically blinding to the browser without the paired deployment of the `sizes` attribute?

- Example 1: [LuaLaTeX](q17-sizes-attribute-requirement/diagram-01.tex) · [PDF](q17-sizes-attribute-requirement/diagram-01.pdf)
- Example 2: [LuaLaTeX](q17-sizes-attribute-requirement/diagram-02.tex) · [PDF](q17-sizes-attribute-requirement/diagram-02.pdf)
- Example 3: [LuaLaTeX](q17-sizes-attribute-requirement/diagram-03.tex) · [PDF](q17-sizes-attribute-requirement/diagram-03.pdf)

### Q18: In the structural command `sizes="(max-width: 600px) 100vw, 33vw"`, how are you explicitly forecasting your CSS geometry directly into the HTML engine?

- Example 1: [LuaLaTeX](q18-sizes-viewport-forecast/diagram-01.tex) · [PDF](q18-sizes-viewport-forecast/diagram-01.pdf)
- Example 2: [LuaLaTeX](q18-sizes-viewport-forecast/diagram-02.tex) · [PDF](q18-sizes-viewport-forecast/diagram-02.pdf)
- Example 3: [LuaLaTeX](q18-sizes-viewport-forecast/diagram-03.tex) · [PDF](q18-sizes-viewport-forecast/diagram-03.pdf)

### Q19: How does the rendering engine mathematically calculate your spatial `sizes` prediction, multiply it by the physical screen's hardware Device Pixel Ratio, compare that dynamic mathematical number against the `srcset` list, and logically download the single closest optimized image?

- Example 1: [LuaLaTeX](q19-srcset-selection-calculation/diagram-01.tex) · [PDF](q19-srcset-selection-calculation/diagram-01.pdf)
- Example 2: [LuaLaTeX](q19-srcset-selection-calculation/diagram-02.tex) · [PDF](q19-srcset-selection-calculation/diagram-02.pdf)

### Q20: Conceptually, what is the strict separation of intent between "Resolution Switching" (maintaining the identical image while serving differing file dimensions) versus true "Art Direction" (providing radically cropped or contextually differing graphical layouts based on viewport availability)?

- Example 1: [LuaLaTeX](q20-resolution-switching-vs-art-direction/diagram-01.tex) · [PDF](q20-resolution-switching-vs-art-direction/diagram-01.pdf)
- Example 2: [LuaLaTeX](q20-resolution-switching-vs-art-direction/diagram-02.tex) · [PDF](q20-resolution-switching-vs-art-direction/diagram-02.pdf)

### Q21: Why is standard `srcset` strictly an *advisory* mechanic to the browser engine, whereas the `<picture>` wrapper strictly establishes hard, unignorable execution parameters?

- Example 1: [LuaLaTeX](q21-srcset-vs-picture/diagram-01.tex) · [PDF](q21-srcset-vs-picture/diagram-01.pdf)
- Example 2: [LuaLaTeX](q21-srcset-vs-picture/diagram-02.tex) · [PDF](q21-srcset-vs-picture/diagram-02.pdf)
- Example 3: [LuaLaTeX](q21-srcset-vs-picture/diagram-03.tex) · [PDF](q21-srcset-vs-picture/diagram-03.pdf)

### Q22: How does `<source media="(max-width: 600px)" srcset="tight-crop.jpg">` mechanically sever the standard pre-parsing algorithms and mathematically force the browser to only render specific framing boundaries on smaller mobile endpoints?

- Example 1: [LuaLaTeX](q22-picture-media-art-direction/diagram-01.tex) · [PDF](q22-picture-media-art-direction/diagram-01.pdf)
- Example 2: [LuaLaTeX](q22-picture-media-art-direction/diagram-02.tex) · [PDF](q22-picture-media-art-direction/diagram-02.pdf)

### Q23: Logically, how does the sequential source-order DOM parsing of a `<picture>` tag act as a truth-finding cascading waterfall, immediately executing and ceasing network requests upon the very first successful media query match?

- Example 1: [LuaLaTeX](q23-picture-source-order/diagram-01.tex) · [PDF](q23-picture-source-order/diagram-01.pdf)
- Example 2: [LuaLaTeX](q23-picture-source-order/diagram-02.tex) · [PDF](q23-picture-source-order/diagram-02.pdf)

### Q24: By incorporating `type="image/avif"` or `type="image/webp"` inside `<source>` nodes alongside spatial Art Direction, how does this inherently set up conditional capability algorithms based on software versions?

- Example 1: [LuaLaTeX](q24-modern-image-format-selection/diagram-01.tex) · [PDF](q24-modern-image-format-selection/diagram-01.pdf)
- Example 2: [LuaLaTeX](q24-modern-image-format-selection/diagram-02.tex) · [PDF](q24-modern-image-format-selection/diagram-02.pdf)

### Q25: How does the cascading logic fall all the way down to a standard baseline `<img src="fallback.jpg">`, guaranteeing structural preservation without Javascript polyfills for legacy, un-updated devices parsing highly modern formats?

- Example 1: [LuaLaTeX](q25-picture-fallback-image/diagram-01.tex) · [PDF](q25-picture-fallback-image/diagram-01.pdf)
- Example 2: [LuaLaTeX](q25-picture-fallback-image/diagram-02.tex) · [PDF](q25-picture-fallback-image/diagram-02.pdf)

### Q26: Within an SVG layout context, how does the `viewBox="0 0 100 100"` logic map a mathematical infinity plane filled with geometric paths explicitly into fluid fractional variables recognized by the CSS bounding engine?

- Example 1: [LuaLaTeX](q26-svg-viewbox/diagram-01.tex) · [PDF](q26-svg-viewbox/diagram-01.pdf)
- Example 2: [LuaLaTeX](q26-svg-viewbox/diagram-02.tex) · [PDF](q26-svg-viewbox/diagram-02.pdf)

### Q27: If you apply extreme horizontal stretching to an SVG in CSS, how does the SVG attribute `preserveAspectRatio="xMidYMid slice"` structurally act identical to CSS `object-fit: cover` purely utilizing embedded coordinate interpolation math?

- Example 1: [LuaLaTeX](q27-svg-preserve-aspect-ratio/diagram-01.tex) · [PDF](q27-svg-preserve-aspect-ratio/diagram-01.pdf)
- Example 2: [LuaLaTeX](q27-svg-preserve-aspect-ratio/diagram-02.tex) · [PDF](q27-svg-preserve-aspect-ratio/diagram-02.pdf)

### Q28: Architecturally, why does importing an SVG graphically via `<img>` or `background-image` build a structural encapsulation wall (Shadow DOM barrier) that completely isolates internal paths from being dynamically restyled (e.g., color changing on `:hover`) via the global CSSOM?

- Example 1: [LuaLaTeX](q28-external-svg-css-isolation/diagram-01.tex) · [PDF](q28-external-svg-css-isolation/diagram-01.pdf)
- Example 2: [LuaLaTeX](q28-external-svg-css-isolation/diagram-02.tex) · [PDF](q28-external-svg-css-isolation/diagram-02.pdf)
- Example 3: [LuaLaTeX](q28-external-svg-css-isolation/diagram-03.tex) · [PDF](q28-external-svg-css-isolation/diagram-03.pdf)

### Q29: How does parsing an SVG "inline" directly into the DOM tree structure allow deep topological targeting utilizing CSS Custom Variables and complex CSS pseudo-class states mapped directly onto geometric `<path>` fills?

- Example 1: [LuaLaTeX](q29-inline-svg-styling/diagram-01.tex) · [PDF](q29-inline-svg-styling/diagram-01.pdf)
- Example 2: [LuaLaTeX](q29-inline-svg-styling/diagram-02.tex) · [PDF](q29-inline-svg-styling/diagram-02.pdf)
- Example 3: [LuaLaTeX](q29-inline-svg-styling/diagram-03.tex) · [PDF](q29-inline-svg-styling/diagram-03.pdf)

### Q30: Logically, how is it mathematically possible for an independent `.svg` asset sitting on a CDN to contain an internally isolated `<style>` block running its *own* embedded `@media` query layout engines?

- Example 1: [LuaLaTeX](q30-svg-internal-media-queries/diagram-01.tex) · [PDF](q30-svg-internal-media-queries/diagram-01.pdf)
- Example 2: [LuaLaTeX](q30-svg-internal-media-queries/diagram-02.tex) · [PDF](q30-svg-internal-media-queries/diagram-02.pdf)
- Example 3: [LuaLaTeX](q30-svg-internal-media-queries/diagram-03.tex) · [PDF](q30-svg-internal-media-queries/diagram-03.pdf)

### Q31: How does injecting modern `@container` query logic explicitly into a self-contained SVG node empower developers to create infinitely responsive vector elements (e.g., displaying heavy detailed data-graphs on desktops that instantly mutate into minimal icons inside tight sidebars) independent of application state frameworks?

- Example 1: [LuaLaTeX](q31-svg-container-queries/diagram-01.tex) · [PDF](q31-svg-container-queries/diagram-01.pdf)

## Licensing

- LuaLaTeX source files are licensed under the MIT License.
- Questions, documentation, and PDFs are licensed under CC BY 4.0.

See the license files in the repository root.
