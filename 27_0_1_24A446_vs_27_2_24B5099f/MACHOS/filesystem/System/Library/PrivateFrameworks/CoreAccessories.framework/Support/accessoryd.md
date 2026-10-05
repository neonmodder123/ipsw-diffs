## accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1216.2.2.0.0
-  __TEXT.__text: 0x19fdb0
+1219.40.10.502.1
+  __TEXT.__text: 0x1a1614
   __TEXT.__auth_stubs: 0x1890
-  __TEXT.__objc_stubs: 0x95c0
-  __TEXT.__objc_methlist: 0x6eac
-  __TEXT.__const: 0x2110
+  __TEXT.__objc_stubs: 0x9620
+  __TEXT.__objc_methlist: 0x6edc
+  __TEXT.__const: 0x2120
   __TEXT.__gcc_except_tab: 0x2110
   __TEXT.__objc_classname: 0xfd3
-  __TEXT.__objc_methname: 0xfed6
-  __TEXT.__objc_methtype: 0x324c
-  __TEXT.__cstring: 0xe5f5
-  __TEXT.__oslogstring: 0x390eb
+  __TEXT.__objc_methname: 0xff4a
+  __TEXT.__objc_methtype: 0x3259
+  __TEXT.__cstring: 0xe838
+  __TEXT.__oslogstring: 0x3956b
   __TEXT.__ustring: 0x232
-  __TEXT.__unwind_info: 0x4830
-  __DATA_CONST.__const: 0xa2d8
-  __DATA_CONST.__cfstring: 0x73c0
+  __TEXT.__unwind_info: 0x4870
+  __DATA_CONST.__const: 0xa448
+  __DATA_CONST.__cfstring: 0x74e0
   __DATA_CONST.__objc_classlist: 0x318
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x178

   __DATA_CONST.__objc_arrayobj: 0xd8
   __DATA_CONST.__objc_intobj: 0x108
   __DATA_CONST.__auth_got: 0xc58
-  __DATA_CONST.__got: 0xef8
+  __DATA_CONST.__got: 0xf10
   __DATA_CONST.__auth_ptr: 0x98
-  __DATA.__objc_const: 0xb080
-  __DATA.__objc_selrefs: 0x33c0
-  __DATA.__objc_ivar: 0x7a0
+  __DATA.__objc_const: 0xb0b0
+  __DATA.__objc_selrefs: 0x33d8
+  __DATA.__objc_ivar: 0x7a4
   __DATA.__objc_data: 0x1ef0
   __DATA.__data: 0x1940
-  __DATA.__bss: 0x1618
+  __DATA.__bss: 0x1648
   __DATA.__common: 0x28
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libsysdiagnose.dylib
-  Functions: 8706
-  Symbols:   11697
-  CStrings:  8722
+  Functions: 8734
+  Symbols:   11731
+  CStrings:  8756
 
Symbols:
+ -[ACCExternalAccessory EAPPIDVersionUID]
+ -[ACCTransportServer isConnectionEntitled:]
+ -[ACCTransportServer shouldAcceptConnection:]
+ -[NSXPCConnection(Entitlements) hasBooleanEntitlement:]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(acc_internal_settings.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-436d1ea6c3a19c17f6f0983b010948ba.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-8c862eb9e04f263684b888877d5ccd36.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-41a6aae24b077b09d9c7548534ea7027.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-cd95a48574a8a10eba009eb24deeddae.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-198f49740f9edd2d7d0f4cf7c80f3e76.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-35af36af9a45dafc5d708585bc4e6e31.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-bebd62eda10a6c778af7ea4059512008.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-6f2b564630f5c588b9f4704f368834a7.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-41271b4ba0cae25e6d8252f533c891c1.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-7a080c038086d236fc6420a7012300ab.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-bae5001ccd16d1cce118e8e63ff0e002.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-05fad12aeafe57f2cea0ddaf381f9188.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-103a4bc011970530e324f84f8e79b594.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-a0fd5a20da8e9dc88ae8ccc432cb9178.o)
+ OBJC_IVAR_$_ACCExternalAccessory._EAPPIDVersionUID
+ ____genericMFi_appLaunch_setDialogActive_block_invoke
+ ____genericMFi_appLaunch_setDialogActive_block_invoke_2
+ ____isProxima_block_invoke
+ ____performAfterDelay_block_invoke
+ ____performAfterDelay_block_invoke_2
+ ____performAfterDelay_block_invoke_3
+ ____releaseCarPlayAvailabilityAfterGap_block_invoke
+ ___acc_internalSettings_isInternalBuild_block_invoke
+ ___releaseCarPlayAvailabilityAfterGap_block_invoke
+ __createError
+ __genericMFi_appLaunch_setDialogActive
+ __performAfterDelay
+ __releaseCarPlayAvailabilityAfterGap
+ __startFeature
+ _acc_internalSettings_boolForKey
+ _createFeature.sInstanceID
+ _iap2_deviceNotifications_holdCarPlayAvailability
+ _kACCExternalAccessoryPPIDVersionUIDKey
+ _kCFACCInfo_PPIDVersionUID
+ _kCFACCUserDefaultsKey_AllowACCAuthProtocolOnAllTransport
+ _kCFACCUserDefaultsKey_AllowMFi4DevCertsOnProdDevice
+ _kCFACCUserDefaultsKey_DisableACCAuthProtocolOnInductive
+ _kCFACCUserDefaultsKey_EnableACCAuthProtocolOnNFC
+ _kCFErrorUnderlyingErrorKey
+ _objc_msgSend$EAPPIDVersionUID
+ _objc_msgSend$hasBooleanEntitlement:
+ _objc_msgSend$isConnectionEntitled:
+ _performAfterDelay
+ _startFeature
+ acc_internalSettings_boolForKey
+ acc_internalSettings_isInternalBuild.isInternalBuild
+ acc_internalSettings_isInternalBuild.onceToken
+ acc_internal_settings.c
+ iap2_deviceNotifications_wirelessCarPlayAvailabilityDidChangeHandler
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-019ae603d8dc1916f3f174dbee15c627.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-9e7ae0279713610c45dd45353c559a7e.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-3ddfda8a63119859f5b14b3f1b605f6c.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-b63500f7e934b6af4db0708ea018a493.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-80c32cc5c01954b7c782c8d4a2058b8f.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-19ad6d8be147053e768386ae23119c7a.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-6ab91b4ee8a78c8edf57750bf9d931d4.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-85618de6e74bd8ca5a62508d02e09c6a.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-f463c0553cb4abcbc5e87cd3c4e2078d.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-21bd53e832b4d5d2c14dc98f2899be5f.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-f0c64433c05768d694ca1414363320cd.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-8c74001941e320c1fd60df76badb29da.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-a4e2ec8b55a562dca16e81f81fcd042e.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-4fecf7636e482b76ad79003cfdd0d64e.o)
- _ACCUserDefaultsKey_AllowACCAuthProtocolOnAllTransport
- _ACCUserDefaultsKey_AllowMFi4DevCertsOnProdDevice
- _ACCUserDefaultsKey_DisableACCAuthProtocolOnInductive
- _ACCUserDefaultsKey_EnableACCAuthProtocolOnNFC
- ____genericMFi_appLaunch_RequestUserForAppLaunch_block_invoke_2
- ____genericMFi_appLaunch_RequestUserForAppLaunch_block_invoke_3
CStrings:
+ "%s: !sendOutgoingHandler"
+ "%s: %@ is not installed - no dialog to present"
+ "%s: %@, requestAppLaunch: unknown launchMethod %d - treating as WithUserAlert"
+ "%s: No connection for endpoint %@ - dialogActive not updated"
+ "%s: No dialog presented for %@ (appName %@) - clearing dialogActive"
+ "%s: authSession(%d), keepOpen %d, error %d"
+ "(user approved)"
+ "Adding accessory info: name %@, model %@, manufacturer %@, serial %@, firmware revision (active) %@, firmware revision (pending) %@, hardware revision %@, ppid %@, ppidVersionUID: %@, regionCode %@, hideFromUI: %s"
+ "B32@?0^v8^{iAP2Msg_t_st=*III**^?^vB^?}16^^{__CFError}24"
+ "Deferring Device Notifications start by %d ms (endpoint %@)"
+ "EAPPIDVersionUID"
+ "Holding CarPlayAvailability until after the first WirelessCarPlay update (endpoint %@)"
+ "PPIDVersionUID"
+ "Releasing CarPlayAvailability hold (held: %d, endpoint %@)"
+ "T@\"NSString\",R,N,V_EAPPIDVersionUID"
+ "Unentitled XPC connection from pid %d! (Missing entitlement: '%@')! (API: ACCTransportClient / acc_transport_client)"
+ "WifiChipset"
+ "_EAPPIDVersionUID"
+ "_genericMFi_appLaunch_setDialogActive"
+ "acc_internalSettings: internal-only setting %{public}@ active"
+ "authSetupStart: initMessage_RequestAuthSetup failed: %d"
+ "com.apple.mfi4Auth.decrypt"
+ "com.apple.mfi4Auth.encrypt"
+ "com.apple.mfi4Auth.process"
+ "com.apple.mfi4Auth.protocol"
+ "com.apple.mfi4Auth.receive"
+ "com.apple.mfi4Auth.send"
+ "com.apple.private.accessories.transport-client"
+ "decryptIncomingData: decryptPayload rc=%d"
+ "decryptIncomingData: failed: %d"
+ "encryptOutgoingData: encryptPayload rc=%d"
+ "failed to handle refresh access state response"
+ "hasBooleanEntitlement:"
+ "isConnectionEntitled:"
+ "mfi4Auth_protocol_handle_AuthCert: Accessory did NOT provide PrivacyPrefix!"
+ "mfi4Auth_protocol_processIncomingMessage: error: %d"
+ "mfi4Auth_protocol_processIncomingMessageExtra: error: %d"
+ "processIncomingMessageExtra: non-Extra message id 0x%04x — falling through to relay"
+ "processIncomingMessageRelay: error: %d"
+ "processIncomingMessageRelay: non-relay message id 0x%04x — no relay action"
+ "processOutgoingSecureTunnelDataForClient: sendOutgoingData failed"
+ "proxima"
+ "receiveIncomingData: sendOutgoingData failed"
+ "v24@?0^v8B16i20"
+ "v24@?0^{?=^{ACCEndpoint2_s}^{__CFString}^{__CFString}^{dispatch_queue_s}BB^{iAP2LinkRunLoop_st}{iAP2PacketSYNData_st=CCCCSSSCCS[5C][5C]C[5C][5{?=CCCB}]}iB^{iAP2Packet_st}^{iAP2MsgParser_st}{iAP2Msg_t_st=*III**^?^vB^?}*[29^v]^vB^vd}8^{?=BBBBBIBB^{__CFDictionary}}16"
+ "v32@0:8^{?=^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFArray}^{__CFNumber}^{__CFNumber}^{__CFNumber}{_opaque_pthread_mutex_t=q[56c]}}16Q24"
- "%s: authSession(%d), keepOpen %d"
- "Adding accessory info: name %@, model %@, manufacturer %@, serial %@, firmware revision (active) %@, firmware revision (pending) %@, hardware revision %@, ppid %@, regionCode %@, hideFromUI: %s"
- "Data not passed in"
- "decryptIncomingData: failed"
- "encryptOutgoingData: encryptPayload: error: %d"
- "failed to handle auth failed"
- "mfi4Auth_protocol_processIncomingMessage: error"
- "mfi4Auth_protocol_processIncomingMessageExtra: error"
- "processIncomingMessageRelay: error"
- "v20@?0^v8B16"
- "v24@?0^v8^{iAP2Msg_t_st=*III**^?^vB^?}16"
- "v32@0:8^{?=^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFString}^{__CFArray}^{__CFNumber}^{__CFNumber}^{__CFNumber}{_opaque_pthread_mutex_t=q[56c]}}16Q24"
```
