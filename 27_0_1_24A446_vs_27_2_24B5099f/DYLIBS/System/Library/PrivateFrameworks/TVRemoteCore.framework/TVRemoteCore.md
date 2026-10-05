## TVRemoteCore

> `/System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_imageinfo`

```diff

-627.0.28.0.0
-  __TEXT.__text: 0x48670
-  __TEXT.__lazy_helpers: 0x580
-  __TEXT.__objc_methlist: 0x64d0
-  __TEXT.__const: 0x240
-  __TEXT.__oslogstring: 0x6b90
-  __TEXT.__cstring: 0x372c
-  __TEXT.__gcc_except_tab: 0xb14
-  __TEXT.__unwind_info: 0x1210
+627.10.51.0.0
+  __TEXT.__text: 0x48ec0
+  __TEXT.__lazy_helpers: 0x5d4
+  __TEXT.__objc_methlist: 0x6840
+  __TEXT.__const: 0x252
+  __TEXT.__oslogstring: 0x6db4
+  __TEXT.__cstring: 0x3752
+  __TEXT.__gcc_except_tab: 0xb60
+  __TEXT.__unwind_info: 0x1238
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1638
+  __DATA_CONST.__const: 0x16b8
   __DATA_CONST.__objc_classlist: 0x290
   __DATA_CONST.__objc_catlist: 0x10
-  __DATA_CONST.__objc_protolist: 0xd8
+  __DATA_CONST.__objc_protolist: 0xe0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3090
+  __DATA_CONST.__objc_selrefs: 0x3310
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x210
   __DATA_CONST.__objc_arraydata: 0x110
   __DATA_CONST.__got: 0x470
   __AUTH_CONST.__const: 0x480
-  __AUTH_CONST.__cfstring: 0x4a60
-  __AUTH_CONST.__objc_const: 0x9f88
-  __AUTH_CONST.__lazy_load_got: 0x80
+  __AUTH_CONST.__cfstring: 0x4ac0
+  __AUTH_CONST.__objc_const: 0xa208
+  __AUTH_CONST.__lazy_load_got: 0x88
   __AUTH_CONST.__objc_intobj: 0x288
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__objc_doubleobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x1860
-  __DATA.__objc_ivar: 0x698
-  __DATA.__data: 0xa34
+  __DATA.__objc_ivar: 0x6a0
+  __DATA.__data: 0xa94
   __DATA_DIRTY.__objc_data: 0x140
   __DATA_DIRTY.__bss: 0x170
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2139
-  Symbols:   3704
-  CStrings:  1299
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  Functions: 2150
+  Symbols:   3741
+  CStrings:  1309
 
Symbols:
+ -[TVRCHMHomeObserver _isAtHome]
+ -[TVRCHMHomeObserver homeDidUpdateHomeLocationStatus:]
+ -[TVRCRPCompanionLinkClientWrapper _finishInvalidatingWithCompletionHandler:]
+ -[TVRCRPCompanionLinkClientWrapper _updateFindMyRemoteSupport]
+ -[TVRCRPCompanionLinkClientWrapper activating]
+ -[TVRCRPCompanionLinkClientWrapper setActivating:]
+ -[TVRCSiriRemoteInfo productID]
+ -[TVRCSiriRemoteInfo setProductID:]
+ -[TVRCXPCClient _beginDeviceQueryWithResponse:]
+ GCC_except_table100
+ GCC_except_table106
+ GCC_except_table116
+ GCC_except_table121
+ GCC_except_table126
+ GCC_except_table132
+ GCC_except_table136
+ GCC_except_table143
+ GCC_except_table148
+ GCC_except_table15
+ GCC_except_table20
+ GCC_except_table33
+ GCC_except_table37
+ GCC_except_table45
+ GCC_except_table46
+ GCC_except_table52
+ GCC_except_table82
+ GCC_except_table84
+ GCC_except_table86
+ GCC_except_table88
+ GCC_except_table96
+ GCC_except_table98
+ _GestaltGetDeviceClass
+ _HMStringFromHomeLocation
+ _HMStringFromHomeLocation$lazyAuthGOT_IA_ad_0
+ _HMStringFromHomeLocation$lazyLoadStub
+ _OBJC_IVAR_$_TVRCRPCompanionLinkClientWrapper._activating
+ _OBJC_IVAR_$_TVRCSiriRemoteInfo._productID
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HMHomeDelegatePrivate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HMHomeDelegatePrivate
+ __OBJC_$_PROTOCOL_REFS_HMHomeDelegatePrivate
+ __OBJC_LABEL_PROTOCOL_$_HMHomeDelegatePrivate
+ __OBJC_PROTOCOL_$_HMHomeDelegatePrivate
+ ___47-[TVRCXPCClient _beginDeviceQueryWithResponse:]_block_invoke
+ ___47-[TVRCXPCClient _beginDeviceQueryWithResponse:]_block_invoke_2
+ ___block_descriptor_48_e8_32bs40r_e8_v12?0B8lr40l8s32l8
+ ___block_descriptor_48_e8_32w40w_e5_v8?0lw32l8w40l8
+ ___swift_reflection_version
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreFoundation_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftDispatch_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftFoundation_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftObjectiveC_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swiftXPC_$_TVRemoteCore
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swift_Builtin_float_$_TVRemoteCore
- GCC_except_table103
- GCC_except_table113
- GCC_except_table118
- GCC_except_table123
- GCC_except_table129
- GCC_except_table133
- GCC_except_table140
- GCC_except_table145
- GCC_except_table16
- GCC_except_table31
- GCC_except_table35
- GCC_except_table40
- GCC_except_table43
- GCC_except_table50
- GCC_except_table79
- GCC_except_table81
- GCC_except_table83
- GCC_except_table85
- GCC_except_table87
- GCC_except_table95
- GCC_except_table97
- ___46-[TVRCXPCClient beginDeviceQueryWithResponse:]_block_invoke_2
CStrings:
+ "CompanionClient is already activating %@"
+ "CompanionLinkClient is currently invalidating. Queuing request until after invalidation %@"
+ "Executing queued connection request %@"
+ "Find my remote support level for %@: %@, device capability: %{bool}d, paired remote support: %{bool}d, paired remote productID: %@"
+ "HomeKit informed us that the home location status for home %{public}@ is now %{public}@"
+ "Ignoring activation from a replaced companionLinkClient. Error - %@ %@"
+ "Ignoring invalidation from a replaced companionLinkClient %@"
+ "Ignoring location status update for a home we are not observing"
+ "Keyboard RemoteTextInput send operation - insert length:%lu deleteBackward:%lu forwardDelete:%lu"
+ "Skipping accessory %{public}@ because we are away from home"
+ "activating"
+ "isInvalidating"
+ "productID"
- "Executing queued connection request"
- "Find my remote support level for %@: %@, device capability: %{bool}d, paired remote support: %{bool}d"
- "Keyboard RemoteTextInput send payload string length: %lu"
```
