## managedappsd

> `/usr/libexec/managedappsd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_entry`
- `__TEXT.__eh_frame`
- `__DATA.__objc_selrefs`

```diff

-113.40.17.0.0
-  __TEXT.__text: 0x1364
-  __TEXT.__auth_stubs: 0x360
+113.2.5.0.0
+  __TEXT.__text: 0x11a0
+  __TEXT.__auth_stubs: 0x300
   __TEXT.__objc_stubs: 0x60
-  __TEXT.__const: 0x62
-  __TEXT.__oslogstring: 0x93
-  __TEXT.__swift5_typeref: 0x15
+  __TEXT.__const: 0x52
+  __TEXT.__oslogstring: 0x63
   __TEXT.__swift5_entry: 0x8
+  __TEXT.__swift5_typeref: 0xd
   __TEXT.__cstring: 0x16
   __TEXT.__objc_methname: 0x37
-  __TEXT.__unwind_info: 0xa0
+  __TEXT.__unwind_info: 0x98
   __TEXT.__eh_frame: 0x48
   __DATA_CONST.__const: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__auth_got: 0x1b8
-  __DATA_CONST.__got: 0x30
-  __DATA_CONST.__auth_ptr: 0x20
+  __DATA_CONST.__auth_got: 0x188
+  __DATA_CONST.__got: 0x28
+  __DATA_CONST.__auth_ptr: 0x18
   __DATA.__objc_selrefs: 0x18
-  __DATA.__data: 0x18
+  __DATA.__data: 0x10
   __DATA.__common: 0x60
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   Functions: 16
-  Symbols:   76
-  CStrings:  9
+  Symbols:   68
+  CStrings:  8
 
Symbols:
+ _swift_errorInMain
- _$sSS10describingSSx_tclufC
- _$sSo13os_log_type_ta0A0E5faultABvgZ
- _$ss5ErrorMp
- _$sypN
- _exit
- _objc_release_x26
- _swift_arrayDestroy
- _swift_errorRelease
- _swift_errorRetain
Functions:
~ sub_100000d60 : 2244 -> 1792
~ sub_100001ed0 -> sub_100001d0c : 84 -> 68
~ sub_100001f24 -> sub_100001d50 : 68 -> 84
CStrings:
- "%s failed to set up services: %{public}s"
```
