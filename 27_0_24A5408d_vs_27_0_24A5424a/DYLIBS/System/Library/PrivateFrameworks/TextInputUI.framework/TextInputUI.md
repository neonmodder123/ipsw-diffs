## TextInputUI

> `/System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI`

```diff

-9127.0.84.1.901
-  __TEXT.__text: 0x134df0
-  __TEXT.__objc_methlist: 0xfebc
+9127.0.84.1.113
+  __TEXT.__text: 0x135a5c
+  __TEXT.__objc_methlist: 0xfeac
   __TEXT.__dlopen_cstrs: 0x3f1
   __TEXT.__const: 0x368e
-  __TEXT.__swift5_typeref: 0x196a
-  __TEXT.__swift5_capture: 0x4e4
-  __TEXT.__cstring: 0xd80d
-  __TEXT.__constg_swiftt: 0x17d8
+  __TEXT.__swift5_typeref: 0x198c
+  __TEXT.__swift5_capture: 0x4f8
+  __TEXT.__cstring: 0xd835
+  __TEXT.__constg_swiftt: 0x17c8
   __TEXT.__swift5_reflstr: 0xca5
   __TEXT.__swift5_assocty: 0x2f0
   __TEXT.__swift5_fieldmd: 0xcd4
   __TEXT.__swift5_builtin: 0x154
-  __TEXT.__oslogstring: 0x6081
+  __TEXT.__oslogstring: 0x618c
   __TEXT.__swift5_proto: 0x150
   __TEXT.__swift5_types: 0x128
   __TEXT.__swift_as_entry: 0x60

   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_mpenum: 0x1c
   __TEXT.__ustring: 0x258
-  __TEXT.__unwind_info: 0x4228
+  __TEXT.__unwind_info: 0x4230
   __TEXT.__eh_frame: 0x1884
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x7a58
+  __DATA_CONST.__const: 0x7a98
   __DATA_CONST.__objc_classlist: 0x708
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x278
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa330
+  __DATA_CONST.__objc_selrefs: 0xa358
   __DATA_CONST.__objc_protorefs: 0x80
   __DATA_CONST.__objc_superrefs: 0x470
-  __DATA_CONST.__objc_arraydata: 0xad0
+  __DATA_CONST.__objc_arraydata: 0xae0
   __DATA_CONST.__got: 0x14d0
-  __AUTH_CONST.__const: 0x2be0
-  __AUTH_CONST.__cfstring: 0xeac0
-  __AUTH_CONST.__objc_const: 0x197f8
+  __AUTH_CONST.__const: 0x2c30
+  __AUTH_CONST.__cfstring: 0xeb00
+  __AUTH_CONST.__objc_const: 0x197f0
   __AUTH_CONST.__objc_intobj: 0x3d8
-  __AUTH_CONST.__objc_arrayobj: 0x270
+  __AUTH_CONST.__objc_arrayobj: 0x288
   __AUTH_CONST.__objc_doubleobj: 0x170
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_floatobj: 0xe0
   __AUTH_CONST.__auth_got: 0x1bd0
-  __AUTH.__objc_data: 0x39e0
+  __AUTH.__objc_data: 0x39d0
   __AUTH.__data: 0x990
   __DATA.__objc_ivar: 0x1218
   __DATA.__data: 0x28f8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6865
-  Symbols:   15146
-  CStrings:  2727
+  Functions: 6872
+  Symbols:   15159
+  CStrings:  2732
 
Symbols:
+ +[TUIKeyplane maxRowsPerKey:variantSelectorType:]
+ +[TUIKeyplane maxVariantsPerRowForKey:layoutStyle:rowLimit:maxRows:]
+ +[TUIKeyplane variantRowLimitForKey:layoutStyle:variantSelectorType:]
+ -[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]
+ -[TUIKey updateVariantOrderForMultilineSelectorWithKeyStartingPosition:rowLimit:maxVariantsPerRow:variantCount:]
+ -[TUIVariantSelectorView keyDisplaysNarrowVariants:]
+ ___112-[TUIKey updateVariantOrderForMultilineSelectorWithKeyStartingPosition:rowLimit:maxVariantsPerRow:variantCount:]_block_invoke
+ ___112-[TUIKey updateVariantOrderForMultilineSelectorWithKeyStartingPosition:rowLimit:maxVariantsPerRow:variantCount:]_block_invoke_2
+ ___92-[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke
+ ___92-[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke_2
+ ___block_descriptor_48_e8_q16?0q8l
+ ___block_descriptor_56_e8_q16?0q8l
+ _objc_msgSend$keyDisplaysNarrowVariants:
+ _objc_msgSend$listWithCorrections:
+ _objc_msgSend$maxRowsPerKey:variantSelectorType:
+ _objc_msgSend$maxVariantsPerRowForKey:layoutStyle:rowLimit:maxRows:
+ _objc_msgSend$setObject:atIndexedSubscript:
+ _objc_msgSend$setWithCandidates:proactiveTriggers:
+ _objc_msgSend$updateVariantOrderForMultilineSelectorWithKeyStartingPosition:rowLimit:maxVariantsPerRow:variantCount:
+ _objc_msgSend$variantRowLimitForKey:layoutStyle:variantSelectorType:
+ _symbolic So28TIKeyboardCandidateResultSetC
- +[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]
- -[TUIKeyplane variantRowLimitForLayoutWithKey:variantSelectorType:]
- __OBJC_$_CLASS_METHODS_TUIInputSession
- ___92+[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke
- ___92+[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke_2
- _objc_msgSend$hideInputCandidateView
- _objc_msgSend$isViewLoaded
- _objc_msgSend$variantRowLimitForLayoutWithKey:variantSelectorType:
CStrings:
+ "Autocorrection list contains candidates to be redacted.  Unsupported selector `redactedList`.  Sending empty autocorrection list instead."
+ "Candidate result set contains candidates to be redacted.  Unsupported selector `redactedSet`.  Sending empty result set instead."
+ "Syriac-Diacritics"
+ "Thai-Accents"
+ "q16@?0q8"
```
