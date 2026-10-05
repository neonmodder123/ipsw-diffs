## mobilerepaird

> `/usr/libexec/mobilerepaird`

### Sections with Same Size but Changed Content

- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__auth_ptr`

```diff

-1307.2.4.0.0
-  __TEXT.__text: 0x1cea4
-  __TEXT.__auth_stubs: 0x980
-  __TEXT.__objc_stubs: 0x3660
-  __TEXT.__objc_methlist: 0x17fc
-  __TEXT.__const: 0x152
-  __TEXT.__gcc_except_tab: 0x988
-  __TEXT.__objc_methname: 0x3f4a
-  __TEXT.__cstring: 0x3de6
-  __TEXT.__oslogstring: 0x2ad9
-  __TEXT.__objc_classname: 0x55f
-  __TEXT.__objc_methtype: 0xce2
+1307.40.64.0.0
+  __TEXT.__text: 0x1fa54
+  __TEXT.__auth_stubs: 0x9b0
+  __TEXT.__objc_stubs: 0x3a40
+  __TEXT.__objc_methlist: 0x1a14
+  __TEXT.__const: 0x172
+  __TEXT.__gcc_except_tab: 0xa08
+  __TEXT.__objc_methname: 0x463e
+  __TEXT.__cstring: 0x40d0
+  __TEXT.__oslogstring: 0x3461
+  __TEXT.__objc_classname: 0x59f
+  __TEXT.__objc_methtype: 0xe41
   __TEXT.__ustring: 0x12a
   __TEXT.__constg_swiftt: 0x38
   __TEXT.__swift5_typeref: 0x3b
   __TEXT.__swift5_fieldmd: 0x10
   __TEXT.__swift5_capture: 0x20
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x718
-  __DATA_CONST.__const: 0xbc0
-  __DATA_CONST.__cfstring: 0x3e40
-  __DATA_CONST.__objc_classlist: 0x160
-  __DATA_CONST.__objc_protolist: 0x58
+  __TEXT.__unwind_info: 0x7e0
+  __DATA_CONST.__const: 0xdb0
+  __DATA_CONST.__cfstring: 0x4060
+  __DATA_CONST.__objc_classlist: 0x168
+  __DATA_CONST.__objc_protolist: 0x60
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x118
+  __DATA_CONST.__objc_superrefs: 0x120
   __DATA_CONST.__objc_intobj: 0x48
-  __DATA_CONST.__auth_got: 0x4d0
-  __DATA_CONST.__got: 0x490
+  __DATA_CONST.__auth_got: 0x4e8
+  __DATA_CONST.__got: 0x4c0
   __DATA_CONST.__auth_ptr: 0x8
-  __DATA.__objc_const: 0x2e28
-  __DATA.__objc_selrefs: 0x1058
-  __DATA.__objc_ivar: 0x12c
-  __DATA.__objc_data: 0xe20
-  __DATA.__data: 0x458
-  __DATA.__bss: 0x210
+  __DATA.__objc_const: 0x3098
+  __DATA.__objc_selrefs: 0x11a0
+  __DATA.__objc_ivar: 0x148
+  __DATA.__objc_data: 0xe70
+  __DATA.__data: 0x4c0
+  __DATA.__bss: 0x258
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/CoreServices
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 594
-  Symbols:   292
-  CStrings:  1549
+  Functions: 668
+  Symbols:   299
+  CStrings:  1664
 
Symbols:
+ _NSClassFromString
+ _OBJC_CLASS_$_CRUtils
+ _OBJC_CLASS_$_NSThread
+ _kCRNetworkRetryDelaySeconds
+ _kCRNetworkRetryMaxAttempts
+ _objc_retain_x6
+ _objc_retain_x9
CStrings:
+ "%@ request failed"
+ "%s: ship-charge-limit state unreadable; treating ship mode as unavailable (will retry)"
+ "%s: ship-status publish not permitted: not in trade-in ship mode (marker=%d viaTradeIn=%d)"
+ "+[CRShipModeHelper mayPublishShipModeStatus]"
+ "-[MRBaseComponentHandler sendFinishRepairNotificationShownAnalytics]_block_invoke"
+ "-[MRComponentHealthHandler sendDailyAnalyticsForModuleType:eventType:]_block_invoke"
+ "@\"<CRShipModeStepProviders>\""
+ "@\"NSData\""
+ "@\"NSError\"40@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32"
+ "@\"NSNumber\""
+ "@20@0:8B16"
+ "@40@0:8@16@24@32"
+ "@48@0:8@16@24@32@40"
+ "@?16@0:8"
+ "Attempt:     %lu/%lu\n"
+ "B56@0:8Q16d24@32@40@?48"
+ "CRShipModeBatteryDischargeDriver: ignoring backend seam on a non-internal build"
+ "CRShipModeDefaultStepProviders"
+ "CRShipModeHelper: cleared ship lock marker (device-error latch reset, pending device-error report activity cancelled)"
+ "CRShipModeHelper: ignoring battery-trust seam on a non-internal build"
+ "CRShipModeHelper: ignoring flags-reader seam on a non-internal build"
+ "CRShipModeHelper: set ship lock marker (viaTradeIn=%d, wasPresent=%d, device-error latch reset=%d)"
+ "CRShipModeNotifyEngine: overrideCertificatePEM set without overrideSignature; ignoring it rather than signing with a NULL key"
+ "CRShipModeNotifyEngine: refusing to install the %{public}s seam outside a test process"
+ "CRShipModeOperationScheduler: DG9 report already delivered this session; skipping for %{public}@"
+ "CRShipModeOperationScheduler: DG9 report for %{public}@ delivered"
+ "CRShipModeOperationScheduler: DG9 report for %{public}@ failed: %{public}@; will retry on the next attempt"
+ "CRShipModeOperationScheduler: cancel disengage of ship-charge limit failed: 0x%08x (%@); lock left engaged"
+ "CRShipModeOperationScheduler: ignoring compliance-cadence seam on a non-internal build"
+ "CRShipModeOperationScheduler: ignoring injected step providers outside a test process"
+ "CRShipModeOperationScheduler: ignoring injected store outside a test process"
+ "CRShipModeOperationScheduler: notify failed for %{public}@; releasing ship-charge limit"
+ "CRShipModeOperationScheduler: notify for %{public}@ abandoned: ship-mode authorization revoked before the POST"
+ "CRShipModeOperationScheduler: refusing DG9 report for %{public}@: operation carries no server notify"
+ "CRShipModeOperationScheduler: released ship-charge limit after failed notify"
+ "CRShipModeOperationScheduler: released ship-charge limit latched by cancelled discharge"
+ "CRShipModeOperationScheduler: reporting DG9 device error for %{public}@ (untrusted battery at lock attempt)"
+ "CRShipModeOperationScheduler: ship-charge limit release failed (ioReturn=0x%08x, error=%{public}@); lock left engaged"
+ "CRShipModeStepProviders"
+ "CoreAnalyticsEvent: ModuleType(%@), EventType(FinishRepairNotificationShown)"
+ "CoreAnalyticsEvent: ModuleType(%{public}@), Event(%{public}@)"
+ "DailyPendingRepair"
+ "FINISH_CAMERA_CONTROL_REPAIR_DESC"
+ "FINISH_CAMERA_CONTROL_REPAIR_TITLE"
+ "FinishRepairNotificationShown"
+ "Non-HTTP response to %@ request"
+ "NotifyServerAbandoned"
+ "NotifyServerFailure"
+ "NotifyServerSuccess"
+ "OperationScheduled_"
+ "PART_CAMERA_CONTROL"
+ "ReachedShipModeOther"
+ "ReachedShipModeTradeIn"
+ "Ship-mode authorization was revoked before the notify POST"
+ "ShipMode"
+ "ShipModeNotify: %{public}@ HTTP %ld"
+ "ShipModeNotify: %{public}@ non-HTTP response"
+ "ShipModeNotify: %{public}@ transport failure on attempt %{public}lu/%{public}lu (code=%{public}ld), retrying in %{public}.0fs"
+ "ShipModeNotify: %{public}@ transport failure: %{private}@"
+ "ShipModeNotify: BAA issuance transport failure on attempt %{public}lu/%{public}lu (code=%{public}ld), retrying in %{public}.0fs: %{private}@"
+ "ShipModeNotify: authorization revoked during BAA issuance; abandoning POST"
+ "StepFailedDischarge"
+ "StepFailedErase"
+ "T@\"<CRShipModeStepProviders>\",&,N,V_providers"
+ "T@\"NSData\",C,N,V_overrideSignature"
+ "T@\"NSError\",C,N,V_overrideCredentialError"
+ "T@\"NSNumber\",C,N,V_internalBuildOverride"
+ "T@\"NSString\",C,N,V_overrideCertificatePEM"
+ "T@?,C,N,V_transport"
+ "TB,N,V_notifyAuthorizedByShipMode"
+ "XCTestCase"
+ "_clearReadyToShipFollowUp"
+ "_dumpRequestIfEnabled:command:attempt:responseBody:httpResponse:transportError:"
+ "_failureForResponse:data:transportError:command:"
+ "_internalBuildOverride"
+ "_issueBAAOnce:certificatePEM:error:"
+ "_issueCredentials:certificatePEM:error:"
+ "_notifyAuthorizedByShipMode"
+ "_overrideCertificatePEM"
+ "_overrideCredentialError"
+ "_overrideSignature"
+ "_parseBodyAndReply:replyOnce:"
+ "_performRequest:baseURL:enabled:deviceError:partnerID:attempt:startedAtClock:replyOnce:"
+ "_performStatusRequest:statusURL:attempt:startedAtClock:replyOnce:"
+ "_postReadyToShipFollowUpViaTradeIn:"
+ "_providers"
+ "_releaseShipChargeLimitForDroppedDischarge"
+ "_releaseShipLockAfterFailedNotifyFor:"
+ "_reportDG9DeviceErrorForFailedLatch:"
+ "_runWithEnabled:deviceError:partnerID:stillAuthorized:replyOnce:"
+ "_scheduleRetryForAttempt:startedAtClock:label:transportError:retry:"
+ "_sendRequest:endpointURL:completion:"
+ "_tearDownDischargeAfterCancel"
+ "_transport"
+ "clearFollowUpItemWithUniqueID:"
+ "getInnermostNSError:"
+ "initWithFileURL:"
+ "initWithStore:providers:"
+ "internalBuildOverride"
+ "mayPublishShipModeStatus"
+ "networkRetryClock"
+ "notifyAuthorizedByShipMode"
+ "overrideCertificatePEM"
+ "overrideCredentialError"
+ "overrideSignature"
+ "performEraseWithCompletion:"
+ "postFollowUpItemWithUniqueID:title:informativeText:"
+ "providers"
+ "resetShipModeAvailabilityCacheForTesting"
+ "sendDailyAnalyticsForModuleType:eventType:"
+ "sendFinishRepairNotificationShownAnalytics"
+ "setBatteryTrustReaderForTesting:"
+ "setComplianceCheckIntervalSecondsForTesting:"
+ "setInternalBuildOverride:"
+ "setNotifyAuthorizedByShipMode:"
+ "setOverrideCertificatePEM:"
+ "setOverrideCredentialError:"
+ "setOverrideSignature:"
+ "setProviders:"
+ "setShipChargeLimitFlagsReaderForTesting:"
+ "setTransport:"
+ "shiplock-eval(daemon-start): marker present but cannot ship (enabled=%d compliant=%d trusted=%d); clearing Ready to Ship followup"
+ "shiplock-eval(daemon-start): scheduling network-gated device-error report"
+ "shiplock-eval: no longer in trade-in ship mode; abandoning the device-error report"
+ "shipmode-%@-%@-attempt%lu.log"
+ "shouldRetryNetworkError:attempt:startedAtClock:"
+ "sleepForTimeInterval:"
+ "submitNotifyWithEnabled:deviceError:partnerID:stillAuthorized:completion:"
+ "submitWithEnabled:deviceError:partnerID:stillAuthorized:completion:"
+ "transport"
+ "v24@0:8@\"NSString\"16"
+ "v24@0:8@?<v@?B@\"NSString\">16"
+ "v32@?0@\"NSData\"8@\"NSHTTPURLResponse\"16@\"NSError\"24"
+ "v48@0:8B16B20@\"NSString\"24@?<B@?>32@?<v@?@\"NSError\">40"
+ "v48@0:8B16B20@24@?32@?40"
+ "v56@0:8@16@24Q32d40@?48"
+ "v64@0:8@16@24Q32@40@48@56"
+ "v72@0:8@16@24B32B36@40Q48d56@?64"
- "%s: IOPSShippingChargeLimitGetState failed (0x%08x); treating ship mode as unavailable (will retry)"
- "-[MRComponentHealthHandler sendDailyAnalyticsForModuleType:]_block_invoke"
- "CRShipModeHelper: cleared ship lock marker"
- "CRShipModeHelper: set ship lock marker (viaTradeIn=%d)"
- "Network request failed"
- "Non-HTTP response"
- "Non-HTTP response to status request"
- "ShipModeNotify: HTTP %ld"
- "ShipModeNotify: status HTTP %ld"
- "ShipModeNotify: status transport failure: %{private}@"
- "ShipModeNotify: transport failure: %{private}@"
- "Status request failed"
- "T@\"CRShipModeNotifyEngine\",R,N,V_engine"
- "_dumpRequestIfEnabled:command:responseBody:httpResponse:transportError:"
- "_performRequest:baseURL:enabled:deviceError:partnerID:replyOnce:"
- "_performStatusRequest:statusURL:replyOnce:"
- "_runWithEnabled:deviceError:partnerID:replyOnce:"
- "engine"
- "sendDailyAnalyticsForModuleType:"
- "shiplock-eval(daemon-start): marker present but cannot ship (enabled=%d compliant=%d trusted=%d); clearing Ready to Ship followup and scheduling network-gated device-error report"
- "submitWithEnabled:deviceError:partnerID:completion:"
- "v56@0:8@16@24@32@40@48"
- "v56@0:8@16@24B32B36@40@?48"
```
