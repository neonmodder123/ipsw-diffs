## OBCEngagePlugin

> `/System/Library/ExtensionKit/Extensions/OBCEngagePlugin.appex/OBCEngagePlugin`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-46.0.0.0.0
-  __TEXT.__text: 0x11b58
-  __TEXT.__auth_stubs: 0xea0
+42.0.0.0.0
+  __TEXT.__text: 0x11a88
+  __TEXT.__auth_stubs: 0xe90
   __TEXT.__objc_stubs: 0x220
   __TEXT.__const: 0xca8
   __TEXT.__swift5_entry: 0x8

   __TEXT.__objc_methname: 0x143
   __TEXT.__unwind_info: 0x458
   __TEXT.__eh_frame: 0x9f8
-  __DATA_CONST.__const: 0x7e8
+  __DATA_CONST.__const: 0x7d8
   __DATA_CONST.__objc_classlist: 0x10
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0x758
-  __DATA_CONST.__got: 0x1a0
+  __DATA_CONST.__auth_got: 0x750
+  __DATA_CONST.__got: 0x198
   __DATA_CONST.__auth_ptr: 0x280
   __DATA.__objc_const: 0x190
   __DATA.__objc_selrefs: 0x88

   - /usr/lib/swift/libswiftIntents.dylib
   - /usr/lib/swift/libswiftMLCompute.dylib
   - /usr/lib/swift/libswiftMetal.dylib
-  - /usr/lib/swift/libswiftMetalKit.dylib
-  - /usr/lib/swift/libswiftModelIO.dylib
   - /usr/lib/swift/libswiftNaturalLanguage.dylib
   - /usr/lib/swift/libswiftOSLog.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 300
-  Symbols:   136
+  Symbols:   134
   CStrings:  91
 
Symbols:
+ _swift_retain_x25
- __swift_FORCE_LOAD_$_swiftMetalKit
- __swift_FORCE_LOAD_$_swiftModelIO
- _swift_retain_x27
Functions:
~ sub_100002484 -> sub_1000023f4 : 516 -> 424
~ sub_100002688 -> sub_10000259c : 1360 -> 1256
~ sub_100002cbc -> sub_100002b68 : 252 -> 240
```
