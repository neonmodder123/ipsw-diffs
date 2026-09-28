## CoreUI

> `/System/Library/PrivateFrameworks/CoreUI.framework/CoreUI`

```diff

-1011.2.0.0.0
-  __TEXT.__text: 0xe6420
+1010.0.0.0.0
+  __TEXT.__text: 0xe6104
   __TEXT.__delay_stubs: 0x40
   __TEXT.__delay_helper: 0xa4
   __TEXT.__objc_methlist: 0xa420
   __TEXT.__const: 0x64d8
   __TEXT.__gcc_except_tab: 0x2c7c
-  __TEXT.__cstring: 0x25f71
+  __TEXT.__cstring: 0x25d27
   __TEXT.__oslogstring: 0x200
   __TEXT.__constg_swiftt: 0x2fc
   __TEXT.__swift5_typeref: 0x38e

   __DATA_CONST.__objc_superrefs: 0x4b0
   __DATA_CONST.__objc_arraydata: 0xbe0
   __DATA_CONST.__got: 0xa48
-  __AUTH_CONST.__const: 0x3680
-  __AUTH_CONST.__cfstring: 0x12580
+  __AUTH_CONST.__const: 0x3660
+  __AUTH_CONST.__cfstring: 0x12540
   __AUTH_CONST.__objc_const: 0xf298
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x300

   __DATA.__objc_ivar: 0xc34
   __DATA.__data: 0x79c
   __DATA.__common: 0x8
-  __DATA.__bss: 0x7c8
+  __DATA.__bss: 0x7b8
   __DATA_DIRTY.__objc_data: 0xff0
   __DATA_DIRTY.__crash_info: 0x148
   __DATA_DIRTY.__bss: 0x538

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5830
-  Symbols:   9211
-  CStrings:  5513
+  Functions: 5828
+  Symbols:   9208
+  CStrings:  5504
 
Symbols:
- _____preferredLocalization_block_invoke
- ___preferredLocalization.__preferredLocalizationCache
- ___preferredLocalization.__preferredLocalizationOnce
Functions:
~ __ReadFreeList : 420 -> 472
~ _OUTLINED_FUNCTION_1 : 44 -> 24
~ -[CUICatalog _setPreferredLocalization:] : 600 -> 400
~ -[_CUIThemePixelRendition _initWithCSIHeader:version:] : 3160 -> 3084
~ -[_CUIThemePixelRendition newImageFromCSIDataSlice:ofBitmap:usingColorspace:] : 1832 -> 1776
~ -[_CSIRenditionBlockData expandCSIBitmapData:fromSlice:makeReadOnly:] : 1716 -> 1708
~ _CUIUncompressDeepmap2ImageData : 1040 -> 1032
~ -[CUIVectorGlyphLayerDrawAttachmentStore initFromSVGString:attachmentData:] : 1308 -> 1316
~ -[CUIVectorGlyphLayerDrawAttachmentStore computeCapacity:numAttachments:withScanner:usingAttachmentDelimiter:fieldDelimiter:digits:] : 392 -> 388
~ _pk_decompressData : 456 -> 248
~ ___decompressRLE8 : 352 -> 300
~ ___decompressRLE16 : 352 -> 296
~ ___decompressRLE32 : 360 -> 296
- _____preferredLocalization_block_invoke
+ __BOMFatalException
- __BOMFatalException
- __BOMFileInit.cold.2
CStrings:
+ "_ReadFreeList: tring to read count of freelist table."
- "%@:%@"
- "CoreUI: CSI bitmap data starts past the end of the rendition data"
- "CoreUI: CSI image index %u (offset %u) is outside the rendition data: '%@'"
- "CoreUI: Invalid chunk rows of %lu in image of height %lu (rows already decoded: %lu)"
- "CoreUI: raw image slice needs %zu bytes at offset %zu but only %zu bytes of bitmap data are available (rowbytes %zu)"
- "com.apple.coreui-preferred-localization-cache"
- "decompressData: %zu byte block too small to hold the row index for rows %d..%d\n"
- "decompressData: invalid region %d,%d %dx%d\n"
- "decompressData: row %d offset %u lies outside the %zu byte block\n"
- "decompressData: truncated scanline %d in the %zu byte block\n"
```
