## BiometricKitUI

> `/System/Library/PrivateFrameworks/BiometricKitUI.framework/BiometricKitUI`

```diff

-685.1.2.0.0
-  __TEXT.__text: 0x70e88
-  __TEXT.__objc_methlist: 0x7300
+684.100.0.0.0
+  __TEXT.__text: 0x70b1c
+  __TEXT.__objc_methlist: 0x72e0
   __TEXT.__const: 0xd44
   __TEXT.__gcc_except_tab: 0xde4
-  __TEXT.__cstring: 0x3036
-  __TEXT.__oslogstring: 0x6a83
+  __TEXT.__cstring: 0x3026
+  __TEXT.__oslogstring: 0x6963
   __TEXT.__dlopen_cstrs: 0x292
   __TEXT.__swift5_typeref: 0x2c2
   __TEXT.__swift5_capture: 0x114

   __DATA_CONST.__objc_protolist: 0x160
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4928
+  __DATA_CONST.__objc_selrefs: 0x4918
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x198
   __DATA_CONST.__objc_arraydata: 0x188
   __DATA_CONST.__got: 0x880
   __AUTH_CONST.__const: 0xc50
-  __AUTH_CONST.__cfstring: 0x3440
+  __AUTH_CONST.__cfstring: 0x3400
   __AUTH_CONST.__objc_const: 0x10720
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0xc0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2878
-  Symbols:   4586
-  CStrings:  1083
+  Functions: 2875
+  Symbols:   4582
+  CStrings:  1078
 
Symbols:
+ GCC_except_table71
+ GCC_except_table95
+ ___61-[BKUIPearlJindoEnrollViewController nextStateButtonPressed:]_block_invoke_2
- -[BKUIHostedDynamicallySizedJindoPresentable _sweepStalePresentablesFromBannerSource:]
- -[BKUIPearlEnrollView _resetPreviewLayerBlur]
- -[BKUIPearlJindoEnrollViewController endEnrollFlowWithError:]
- GCC_except_table20
- GCC_except_table34
- GCC_except_table72
- GCC_except_table96
Functions:
- -[BKUIPearlJindoEnrollViewController endEnrollFlowWithError:]
~ -[BKUIPearlJindoEnrollViewController _postBannerToDestinationWithInitialStateCollapsed:enrollViewStateConfiguration:] : 708 -> 664
~ -[BKUIPearlJindoEnrollViewController nextStateButtonPressed:] : 524 -> 480
~ ___61-[BKUIPearlJindoEnrollViewController nextStateButtonPressed:]_block_invoke : 308 -> 116
~ -[BKUIPearlMovieLoopView selfPortrait] : 260 -> 284
~ -[BKUIPearlEnrollViewController _updateLeftBarButtonItem] : 1120 -> 1072
~ -[BKUIPearlEnrollViewController returnToEnroll] : 196 -> 76
~ -[BKUIPearlEnrollView preEnrollActivate] : 92 -> 40
~ -[BKUIPearlEnrollView _endAndCleanupEnrollSessionIfNeeded] : 156 -> 148
- -[BKUIPearlEnrollView _resetPreviewLayerBlur]
~ -[BKUIFingerPrintEnrollTutorialViewController _contentViewTopOffset] : 64 -> 304
~ -[BKUIHostedDynamicallySizedJindoPresentable revoke] : 336 -> 300
- -[BKUIHostedDynamicallySizedJindoPresentable _sweepStalePresentablesFromBannerSource:]
CStrings:
+ "-[BKUIPearlMovieLoopView selfPortrait]"
+ "BKUIPearlMovieLoopView.m"
+ "false"
- "Error revoking presentables %{public}@"
- "Pearl: skipping Jindo banner post as enrollment is no longer active"
- "Resetting preview layer blur"
- "Returning to enroll from partial capture, target state %i"
- "Revoking current presentable"
- "Swept %{public}lu orphaned presentable(s) after a stale request identifier"
- "com.apple.biometrickitui.revoke"
- "com.apple.biometrickitui.staleIdentifierSweep"
```
