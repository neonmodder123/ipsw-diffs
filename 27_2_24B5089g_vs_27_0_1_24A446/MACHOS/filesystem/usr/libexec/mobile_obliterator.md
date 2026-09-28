## mobile_obliterator

> `/usr/libexec/mobile_obliterator`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-402.40.2.0.0
-  __TEXT.__text: 0x1bc88
+402.0.0.0.0
+  __TEXT.__text: 0x1bc18
   __TEXT.__auth_stubs: 0x1540
   __TEXT.__objc_stubs: 0x920
   __TEXT.__objc_methlist: 0x1fc

   __DATA.__objc_data: 0xf0
   __DATA.__data: 0x248
   __DATA.__common: 0x200
-  __DATA.__bss: 0x2af8
+  __DATA.__bss: 0x2ae0
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
   - /System/Library/Frameworks/Foundation.framework/Foundation
Functions:
~ sub_100014954 : 304 -> 252
~ sub_100014a84 -> sub_100014a50 : 336 -> 388
~ sub_100014bd4 : 552 -> 444
~ sub_100015154 -> sub_1000150e8 : 1180 -> 1176
```
