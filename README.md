# eslint-plugin-simple-import-sort issue

1. Clone this repo
2. `npm ci`
3. `npm test`
4. `git diff`

Result:

```
diff --git a/test.js b/test.js
index 9b2896a..1139a7c 100644
--- a/test.js
+++ b/test.js
@@ -1 +1 @@
-import { TestBed, async } from '@angular/core/testing';
+import { async,TestBed } from '@angular/core/testing';
```
