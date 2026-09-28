## AccessibilityUIService

> `/System/Library/PrivateFrameworks/AccessibilityUIService.framework/AccessibilityUIService`

```diff

-3245.8.2.0.0
-  __TEXT.__text: 0x1ff84
+3240.9.0.0.0
+  __TEXT.__text: 0x1fc60
   __TEXT.__objc_methlist: 0x1c64
-  __TEXT.__const: 0x880
+  __TEXT.__const: 0x868
   __TEXT.__constg_swiftt: 0x184
   __TEXT.__swift5_typeref: 0x1d7
   __TEXT.__swift5_fieldmd: 0x120
   __TEXT.__cstring: 0x1561
   __TEXT.__swift5_types: 0x24
   __TEXT.__swift5_capture: 0x44
-  __TEXT.__oslogstring: 0x1a70
+  __TEXT.__oslogstring: 0x1784
   __TEXT.__swift5_reflstr: 0xb5
   __TEXT.__swift5_assocty: 0x18
   __TEXT.__swift5_proto: 0x48
   __TEXT.__swift_as_entry: 0x10
   __TEXT.__swift_as_ret: 0x10
   __TEXT.__swift_as_cont: 0x20
-  __TEXT.__gcc_except_tab: 0x4bc
+  __TEXT.__gcc_except_tab: 0x4b0
   __TEXT.__unwind_info: 0x8c8
   __TEXT.__eh_frame: 0x408
   __TEXT.__objc_stubs: 0x0

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x928
+  __DATA_CONST.__const: 0x920
   __DATA_CONST.__objc_classlist: 0xd0
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x78
   __DATA_CONST.__objc_arraydata: 0x10
-  __DATA_CONST.__got: 0x518
+  __DATA_CONST.__got: 0x510
   __AUTH_CONST.__const: 0x4b0
   __AUTH_CONST.__cfstring: 0xaa0
   __AUTH_CONST.__objc_const: 0x2880

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 749
-  Symbols:   1489
-  CStrings:  228
+  Symbols:   1488
+  CStrings:  222
 
Symbols:
- _UIFontTextStyleHeadline
Functions:
~ -[AXUIAlertStyleProvider alertBackgroundSizeForType:] : 816 -> 776
~ -[AXUIAlertStyleProvider alertTextFontForType:] : 432 -> 396
~ -[AXUIAlertStyleProvider alertTextColorForType:] : 132 -> 128
~ -[AXUIDisplayManager addContentViewController:withUserInteractionEnabled:forService:forSceneClientIdentifier:context:userInterfaceStyle:forWindowScene:spatialConfiguration:isModal:completion:] : 1272 -> 992
~ -[AXUIDisplayManager waitForSceneAddContentViewController:withUserInteractionEnabled:forService:forSceneClientIdentifier:context:userInterfaceStyle:forWindowScene:spatialConfiguration:isModal:completion:] : 812 -> 788
~ ___204-[AXUIDisplayManager waitForSceneAddContentViewController:withUserInteractionEnabled:forService:forSceneClientIdentifier:context:userInterfaceStyle:forWindowScene:spatialConfiguration:isModal:completion:]_block_invoke : 300 -> 112
~ -[AXUIDisplayManager _windowSceneDisconnected:forSceneClientIdentifier:] : 580 -> 440
~ -[AXUIDisplayManager saveAddContentViewControllerBlock:forObjectKey:forSceneClientIdentifier:] : 388 -> 356
~ -[AXUIDisplayManager removeAddContentViewControllerBlockForObjectKey:] : 588 -> 460
~ -[AXStyleProviderUIAlert initWithType:text:subtitleText:iconImage:styleProvider:userInfo:] : 6444 -> 6488
~ sub_254a28064 -> sub_250e13d28 : 752 -> 744
~ sub_254a2861c -> sub_250e142d8 : 684 -> 688
~ sub_254a2a384 -> sub_250e16044 : 3012 -> 3024
~ sub_254a2b600 -> sub_250e172cc : 96 -> 104
~ sub_254a2b660 -> sub_250e17334 : 96 -> 104
CStrings:
+ "Remove block for objectKey: %@"
+ "Save block for objectKey: %@"
+ "Tried to add %@ before a scene was connected, queuing for later."
- "AXUIDisplayManager was deallocated before queued addContentViewController for %@ sceneClientIdentifier:%@ could run; completion will never fire."
- "No attachable scene for contentVC=%p sceneClientIdentifier:%@; queuing."
- "No queued block found for objectKey: %{public}@; nothing to remove."
- "Remove block for objectKey: %{public}@ sceneClientIdentifier:%{public}@ queueDepth:%lu"
- "Running queued addContentViewController for %@ sceneClientIdentifier:%@"
- "Save block for objectKey: %{public}@ sceneClientIdentifier:%{public}@ queueDepth:%lu"
- "Tried to add %@ before a scene was connected, queuing for later (sceneClientIdentifier:%@, sceneAlreadyRequested=%d)."
- "Window scene disconnected while %lu add-block(s) still queued for sceneClientIdentifier:%{public}@"
- "sceneClientIdentifier:%@ windowScene attachable=%d (activationState=%ld), savedWindowScene attachable=%d (activationState=%ld)"
```
