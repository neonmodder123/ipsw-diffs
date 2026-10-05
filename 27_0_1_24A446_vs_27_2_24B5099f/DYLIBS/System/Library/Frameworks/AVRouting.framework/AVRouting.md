## AVRouting

> `/System/Library/Frameworks/AVRouting.framework/AVRouting`

```diff

-360.75.1.4.0
-  __TEXT.__text: 0x4cc60
+385.10.1.0.0
+  __TEXT.__text: 0x4ce20
   __TEXT.__objc_methlist: 0x6770
   __TEXT.__const: 0x104
   __TEXT.__gcc_except_tab: 0x5fc
-  __TEXT.__cstring: 0xa3f2
+  __TEXT.__cstring: 0xa4da
   __TEXT.__oslogstring: 0x6dd9
   __TEXT.__dlopen_cstrs: 0x56
   __TEXT.__unwind_info: 0x17c8

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1230
+  __DATA_CONST.__const: 0x1258
   __DATA_CONST.__objc_classlist: 0x3b8
   __DATA_CONST.__objc_protolist: 0xf0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_selrefs: 0x2018
   __DATA_CONST.__objc_superrefs: 0x2f8
   __DATA_CONST.__got: 0x1108
-  __AUTH_CONST.__const: 0x410
-  __AUTH_CONST.__cfstring: 0x46e0
+  __AUTH_CONST.__const: 0x430
+  __AUTH_CONST.__cfstring: 0x47a0
   __AUTH_CONST.__objc_const: 0xc170
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x1810
   __DATA.__objc_ivar: 0x5a0
   __DATA.__data: 0xb70
-  __DATA.__bss: 0xd8
+  __DATA.__bss: 0xf0
   __DATA.__common: 0xe0
-  __DATA_DIRTY.__objc_data: 0xd20
+  __DATA_DIRTY.__objc_data: 0x2530
   __DATA_DIRTY.__common: 0x100
-  __DATA_DIRTY.__bss: 0xb0
+  __DATA_DIRTY.__bss: 0x98
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox
   - /System/Library/Frameworks/CoreAudio.framework/CoreAudio

   - /System/Library/PrivateFrameworks/SoftLinking.framework/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2496
-  Symbols:   4653
-  CStrings:  1196
+  Functions: 2497
+  Symbols:   4659
+  CStrings:  1202
 
Symbols:
+ _AVOutputDeviceCarPlayScreenBeginFadeInNotification
+ _AVOutputDeviceCarPlayScreenBeginFadeOutNotification
+ _AVOutputDeviceCarPlayScreenFadeDurationKey
+ _AVOutputDevicePostCarPlayScreenFadeNotification
+ _TEMP_kFigEndpointCentralNotification_CarPlayScreenBeginFadeIn
+ _TEMP_kFigEndpointCentralNotification_CarPlayScreenBeginFadeOut
Functions:
~ -[AVFigRouteDescriptorOutputDeviceImpl _handleRouteDescriptionEvent:payload:] : 608 -> 708
~ ___AVOutputDeviceNotificationFromFigNotification_block_invoke : 560 -> 628
~ -[AVFigEndpointOutputDeviceImpl _handleFigEndpointEvent:payload:] : 608 -> 708
+ _AVOutputDevicePostCarPlayScreenFadeNotification
CStrings:
+ "AVOutputDeviceCarPlayScreenBeginFadeInNotification"
+ "AVOutputDeviceCarPlayScreenBeginFadeOutNotification"
+ "AVOutputDeviceCarPlayScreenFadeDurationKey"
+ "CarPlayScreenBeginFadeIn"
+ "CarPlayScreenBeginFadeOut"
+ "CarPlayScreenFadeDurationInSeconds"
```
