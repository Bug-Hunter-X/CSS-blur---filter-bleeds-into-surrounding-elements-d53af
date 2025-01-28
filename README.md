# CSS blur() bleed-out bug

This repository demonstrates a bug where the CSS `filter: blur()` property unexpectedly affects surrounding elements.  The blur effect bleeds out of the targeted element's boundaries, causing visual artifacts in certain browsers and situations.  The solution shows a workaround to contain the blur effect.

**Bug:** The blur applied to the inner div visually bleeds into the outer container. 

**Solution:** Using a wrapper element with `overflow: hidden;` effectively clips the blurred content, preventing bleed-out. 