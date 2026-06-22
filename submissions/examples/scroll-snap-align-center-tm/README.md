# scroll-snap-align-center-tm

## What does this do?
Adds utility classes to control scroll-snap-align for child elements inside a scroll snap container, with center, start, and end variants.

## How is it used?
```html
<div style="scroll-snap-type: x mandatory; overflow-x: scroll; display: flex;">
  <div class="scroll-snap-align-center">Card 1</div>
  <div class="scroll-snap-align-center">Card 2</div>
</div>
```

## Why is it useful?
Centered snap alignment is essential for image carousels and media galleries where items should snap to center. Fills a gap in EaseMotion's scroll utility suite with human-readable class names.
