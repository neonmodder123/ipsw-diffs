## HomeDeviceSetup

> `/System/Library/PrivateFrameworks/HomeDeviceSetup.framework/HomeDeviceSetup`

```diff

-405.0.11.0.0
-  __TEXT.__text: 0x72af8
-  __TEXT.__objc_methlist: 0x345c
-  __TEXT.__const: 0x478
-  __TEXT.__cstring: 0x1ab54
+405.10.34.1.1
+  __TEXT.__text: 0x72de0
+  __TEXT.__objc_methlist: 0x3494
+  __TEXT.__const: 0x488
+  __TEXT.__cstring: 0x1aac4
   __TEXT.__oslogstring: 0x81d
-  __TEXT.__gcc_except_tab: 0x294
+  __TEXT.__gcc_except_tab: 0x2b8
   __TEXT.__constg_swiftt: 0xe0
-  __TEXT.__swift5_typeref: 0xcb
+  __TEXT.__swift5_typeref: 0xd3
   __TEXT.__swift5_reflstr: 0x8b
   __TEXT.__swift5_fieldmd: 0x84
   __TEXT.__swift5_types: 0xc

   __TEXT.__swift_as_entry: 0x1c
   __TEXT.__swift_as_ret: 0x24
   __TEXT.__swift_as_cont: 0x28
-  __TEXT.__unwind_info: 0x1870
+  __TEXT.__unwind_info: 0x18a0
   __TEXT.__eh_frame: 0x468
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1978
+  __DATA_CONST.__const: 0x19d8
   __DATA_CONST.__objc_classlist: 0xa0
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2db0
+  __DATA_CONST.__objc_selrefs: 0x2e10
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x70
   __DATA_CONST.__objc_arraydata: 0x230
-  __DATA_CONST.__got: 0x410
-  __AUTH_CONST.__const: 0xc38
-  __AUTH_CONST.__cfstring: 0x55a0
-  __AUTH_CONST.__objc_const: 0x78b8
+  __DATA_CONST.__got: 0x418
+  __AUTH_CONST.__const: 0xc58
+  __AUTH_CONST.__cfstring: 0x5600
+  __AUTH_CONST.__objc_const: 0x78a8
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x3c0
   __AUTH_CONST.__objc_intobj: 0x1e0
-  __AUTH_CONST.__auth_got: 0x848
+  __AUTH_CONST.__auth_got: 0x850
   __AUTH.__objc_data: 0x778
   __AUTH.__data: 0x328
-  __DATA.__objc_ivar: 0xa50
-  __DATA.__data: 0xb70
+  __DATA.__objc_ivar: 0xa4c
+  __DATA.__data: 0xb78
   __DATA.__common: 0x40
-  __DATA.__bss: 0x7d0
+  __DATA.__bss: 0x7e0
   - /System/Library/Frameworks/Accounts.framework/Accounts
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/CoreServices

   - /usr/lib/swift/libswiftCoreFoundation.dylib
   - /usr/lib/swift/libswiftCoreLocation.dylib
   - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftIntents.dylib
   - /usr/lib/swift/libswiftMetal.dylib
   - /usr/lib/swift/libswiftOSLog.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3082
-  Symbols:   3338
-  CStrings:  3124
+  Functions: 3080
+  Symbols:   3348
+  CStrings:  3127
 
Symbols:
+ +[HDSDefaults getOptionalBoolForKey:]
+ -[HDSSetupService _applySetupTimeIfClockImplausible:]
+ -[HDSSetupSession _runFinishComplete]
+ -[HDSSetupSession _shouldTransferLoggingProfile]
+ -[HDSSetupSession _stereoCounterpartExpectedModelPrefix]
+ GCC_except_table311
+ GCC_except_table374
+ GCC_except_table379
+ GCC_except_table429
+ _OBJC_CLASS_$_NSDateFormatter
+ __HDSBuildDateFloor.sFloor
+ __HDSBuildDateFloor.sOnce
+ ___37-[HDSSetupSession _runFinishComplete]_block_invoke
+ ___53-[HDSSetupSession _startSysDropLoggingProfileRequest]_block_invoke_6
+ ___53-[HDSSetupSession _startSysDropLoggingProfileRequest]_block_invoke_7
+ ____HDSBuildDateFloor_block_invoke
+ ___block_descriptor_48_e8_32s40r_e17_v16?0"NSError"8ls32l8r40l8
+ ___block_descriptor_56_e8_32s40r48r_e5_v8?0lr40l8s32l8r48l8
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
+ __swift_FORCE_LOAD_$_swiftIntents
+ __swift_FORCE_LOAD_$_swiftIntents_$_HomeDeviceSetup
+ _symbolic _____Sg 12FindMyLocate12ClientTargetV
- -[HDSDeviceOperationHomeKitSetup _idsIdentifiersForAccessories:companionLinkClient:]
- -[HDSDeviceOperationHomeKitSetup companionLinkClient]
- -[HDSDeviceOperationHomeKitSetup modelForStereoPairVersion:]
- -[HDSDeviceOperationHomeKitSetup setCompanionLinkClient:]
- GCC_except_table310
- GCC_except_table372
- GCC_except_table424
- _OBJC_IVAR_$_HDSDeviceOperationHomeKitSetup._companionLinkClient
- ___44-[HDSSetupSession _runFinishResponse:error:]_block_invoke
- ___84-[HDSDeviceOperationHomeKitSetup _idsIdentifiersForAccessories:companionLinkClient:]_block_invoke
- ___84-[HDSDeviceOperationHomeKitSetup _idsIdentifiersForAccessories:companionLinkClient:]_block_invoke_2
- ___block_descriptor_32_e38_B32?0"RPCompanionLinkDevice"8Q16^B24l
CStrings:
+ "  "
+ "-[HDSSetupService _applySetupTimeIfClockImplausible:]"
+ "-[HDSSetupSession _runFinishComplete]"
+ "-[HDSSetupSession _runFinishComplete]_block_invoke"
+ "-[HDSSetupSession _startSysDropLoggingProfileRequest]_block_invoke_4"
+ "-[HDSSetupSession _startSysDropLoggingProfileRequest]_block_invoke_7"
+ "Clock %@ predates build, applying setup time %@ (%@)\n"
+ "Ignoring color from %@ (model %@), setting up model code %d\n"
+ "Ignoring setup time %@, predates build floor %@\n"
+ "Logging Profile install failed, logging will stay disabled\n"
+ "Logging Profile unreadable at %@, logging will stay disabled\n"
+ "Logging profile transfer timed out"
+ "MMM d yyyy"
+ "No build date floor, not applying setup time %@\n"
+ "Sep 30 2026"
+ "_startSysDropLoggingProfileRequest timed out after %g s\n"
+ "_startSysDropLoggingProfileRequest timeout fired but transfer state is %d, ignoring\n"
+ "en_US_POSIX"
+ "sysDropBuildMode: Seed path + profile -> %s\n"
- "### _idsIdentifiersForAccessories: %@ has no IDS identifier\n"
- "### _idsIdentifiersForAccessories: %@ not found in Rapport\n"
- "### _idsIdentifiersForAccessories: nil accessories or client\n"
- "### _idsIdentifiersForAccessories: no active devices\n"
- "### _idsIdentifiersForAccessories: unregistered device has no IDS identifier\n"
- "-[HDSDeviceOperationHomeKitSetup _idsIdentifiersForAccessories:companionLinkClient:]"
- "-[HDSSetupSession _runFinishResponse:error:]_block_invoke"
- "-[HDSSetupSession _startSysDropLoggingProfileRequest]_block_invoke_5"
- "AudioAccessory6,1"
- "_idsIdentifiersForAccessories: %@ -> IDS: %@ (matched as unregistered device, model: %@)\n"
- "_idsIdentifiersForAccessories: %@ -> IDS: %@ (matched by HomeKit UUID)\n"
- "_idsIdentifiersForAccessories: %@ not found by HomeKit UUID, checking for unregistered device\n"
- "_idsIdentifiersForAccessories: activeDevices count=%lu\n"
- "sysDropBuildMode: internal build + sysDropEnabled -> %s\n"
- "sysDropBuildMode: no path matched -> %s\n"
- "sysDropBuildMode: prod + profile installed -> %s\n"
```
