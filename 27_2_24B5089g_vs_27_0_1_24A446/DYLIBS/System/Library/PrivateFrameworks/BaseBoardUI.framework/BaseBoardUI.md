## BaseBoardUI

> `/System/Library/PrivateFrameworks/BaseBoardUI.framework/BaseBoardUI`

```diff

-827.2.1.1.0
-  __TEXT.__text: 0x18fdc
+827.0.0.0.0
+  __TEXT.__text: 0x18f38
   __TEXT.__objc_methlist: 0x198c
-  __TEXT.__const: 0x3f8
-  __TEXT.__gcc_except_tab: 0x2ea4
+  __TEXT.__const: 0x3e0
+  __TEXT.__gcc_except_tab: 0x2e78
   __TEXT.__cstring: 0x11e9
-  __TEXT.__oslogstring: 0x7b0
+  __TEXT.__oslogstring: 0x778
   __TEXT.__unwind_info: 0xe58
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 528
-  Symbols:   1321
-  CStrings:  184
+  Symbols:   1319
+  CStrings:  183
 
Symbols:
- ___error
- _strerror_r
Functions:
~ -[BSUIMappedImageCacheRegistry tmpPath] : 1188 -> 1024
CStrings:
+ "BSUIMappedImageCache failed to get relative tmpDir from dirhelper for %@ : falling back to NSTemporaryDirectory=%@"
- "BSUIMappedImageCache failed to get relative tmpDir from dirhelper with errno=%i (%{public}s) for %@"
- "BSUIMappedImageCache is falling back to NSTemporaryDirectory=%@ for %@"
```
