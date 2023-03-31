---
"@finsweet/tsconfig": patch
---

Roll back to `moduleResolution="node"` because it seems that many libraries still don't support the new `bundler` option.
