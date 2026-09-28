## SiriUICore

> `/System/Library/PrivateFrameworks/SiriUICore.framework/SiriUICore`

```diff

-3605.4.1.0.0
-  __TEXT.__text: 0x2b9e4
+3600.9.2.0.0
+  __TEXT.__text: 0x2b95c
   __TEXT.__objc_methlist: 0x3448
-  __TEXT.__const: 0x68972
-  __TEXT.__cstring: 0x885b
-  __TEXT.__oslogstring: 0xd80
+  __TEXT.__const: 0x7f172
+  __TEXT.__cstring: 0x87ea
+  __TEXT.__oslogstring: 0xd3d
   __TEXT.__gcc_except_tab: 0x380
   __TEXT.__dlopen_cstrs: 0x5a
   __TEXT.__ustring: 0x14

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1152
+  Functions: 1151
   Symbols:   2548
-  CStrings:  377
+  CStrings:  374
 
Symbols:
+ _precalcSUICILNoise3DTexture
- _precalcSUICILNoise3DTextureASTC5x5
Functions:
~ +[SUICIntelligentLightLayer createNoiseTextureWithDevice:commandQueue:] : 496 -> 428
+ +[SUICFlamesViewMetal _supportsAdaptiveFramerate].cold.1
- +[SUICFlamesViewMetal _supportsAdaptiveFramerate].cold.1
- -[SUICFlamesViewMetal _initMetalAndSetupDisplayLink:].cold.2
CStrings:
- "!\"ASTC5x5 3D texture failed to allocate\""
- "%s Failed to create compressed noise texture. Requires Apple3 GPU."
- "+[SUICIntelligentLightLayer createNoiseTextureWithDevice:commandQueue:]"
```
