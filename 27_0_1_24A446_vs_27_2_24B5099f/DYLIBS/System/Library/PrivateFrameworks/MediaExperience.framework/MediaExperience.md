## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience`

```diff

-360.75.1.4.0
-  __TEXT.__text: 0x2548d8
+385.10.1.0.0
+  __TEXT.__text: 0x259da8
   __TEXT.__delay_helper: 0x304
   __TEXT.__lazy_helpers: 0xfc
-  __TEXT.__objc_methlist: 0x88d0
-  __TEXT.__cstring: 0x38f4b
-  __TEXT.__const: 0x1d08
-  __TEXT.__gcc_except_tab: 0x4eb4
-  __TEXT.__oslogstring: 0x50325
+  __TEXT.__objc_methlist: 0x8a80
+  __TEXT.__cstring: 0x39659
+  __TEXT.__const: 0x1d20
+  __TEXT.__gcc_except_tab: 0x4ef8
+  __TEXT.__oslogstring: 0x51d97
   __TEXT.__dlopen_cstrs: 0x613
-  __TEXT.__unwind_info: 0x5f98
+  __TEXT.__unwind_info: 0x6048
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x7248
-  __DATA_CONST.__objc_classlist: 0x310
+  __DATA_CONST.__const: 0x7340
+  __DATA_CONST.__objc_classlist: 0x320
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x54c8
+  __DATA_CONST.__objc_selrefs: 0x55d8
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x2e0
+  __DATA_CONST.__objc_superrefs: 0x2f0
   __DATA_CONST.__objc_arraydata: 0xf8
-  __DATA_CONST.__got: 0xd10
-  __AUTH_CONST.__const: 0x4988
-  __AUTH_CONST.__cfstring: 0x1c080
-  __AUTH_CONST.__objc_const: 0xcf28
+  __DATA_CONST.__got: 0xd28
+  __AUTH_CONST.__const: 0x49c8
+  __AUTH_CONST.__cfstring: 0x1c300
+  __AUTH_CONST.__objc_const: 0xd2a8
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x78

   __AUTH_CONST.__objc_dictobj: 0x118
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x1d10
-  __AUTH.__data: 0x5f0
-  __DATA.__objc_ivar: 0xc78
-  __DATA.__data: 0x1410
-  __DATA.__bss: 0x1380
+  __AUTH.__objc_data: 0x1810
+  __AUTH.__data: 0x630
+  __DATA.__objc_ivar: 0xcbc
+  __DATA.__data: 0x1450
+  __DATA.__bss: 0x1398
   __DATA.__common: 0x5d0
-  __DATA_DIRTY.__objc_data: 0x190
+  __DATA_DIRTY.__objc_data: 0x730
   __DATA_DIRTY.__bss: 0xce8
   __DATA_DIRTY.__common: 0x60
   - /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 10089
-  Symbols:   13525
-  CStrings:  9899
+  Functions: 10175
+  Symbols:   13635
+  CStrings:  10015
 
Symbols:
+ +[MXSessionManager donateMatchRingtoneVolumeDisabledSignal]
+ +[MXSessionManager(Utilities) sendVolumeFollowingToggleSnapshotTelemetry]
+ +[MXSessionResumptionContext canExcludeSessionFromActiveSessionList:forResumingSession:]
+ -[MXBiomeStreams donateDiscoverabilitySignalWithContentIdentifier:context:userInfo:]
+ -[MXCoreSessionBase getPreferredOutputSampleRatePointer]
+ -[MXCoreSessionBase preferredOutputSampleRate]
+ -[MXCoreSessionBase setPreferredOutputSampleRate:]
+ -[MXCoreSessionBase setSampleRateAndBufferSizeForOnDemandVAD]
+ -[MXCustomEndpointCache clearCachedEndpointsForProtocol:]
+ -[MXMDEExtensionRequest .cxx_destruct]
+ -[MXMDEExtensionRequest completeWithReplyError:result:]
+ -[MXMDEExtensionRequest dealloc]
+ -[MXMDEExtensionRequest failUnresponsiveWithError:]
+ -[MXMDEExtensionRequest initWithOperation:instance:timeoutNsec:completion:]
+ -[MXMDEExtensionRequest remoteProxyForConnection:]
+ -[MXMDEExtensionRequest resolveUnresponsive:error:result:]
+ -[MXMDEPendingExtensionRequest completeWithError:result:]
+ -[MXMDEPendingExtensionRequest completeWithError:result:beforeSendingResult:]
+ -[MXMDEPendingExtensionRequest dealloc]
+ -[MXMDEPendingExtensionRequest initWithClientConnection:objectID:resultOpCode:requestID:]
+ -[MXSessionManager alarmVolumeChangedOnPersonalRoute]
+ -[MXSessionManager populatePrimaryRouteConfig:routesInfo:systemAudioContextUUID:volumeButtonClientSession:]
+ -[MXSessionManager ringtoneVolumeChangedOnPersonalRoute]
+ -[MXSessionManager setAlarmVolumeChangedOnPersonalRoute:]
+ -[MXSessionManager setRingtoneVolumeChangedOnPersonalRoute:]
+ -[MXSessionManager(Utilities) canSessionsCoexistDueToSharePlay:victim:]
+ -[MXSessionManager(Utilities) updateSampleRateAndBufferSizeForOnDemandVADIfNeeded:]
+ -[MXSystemCastingExtensionInstance noteUnresponsiveExtensionForOperation:error:]
+ -[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]
+ -[MXSystemCastingExtensionManager copyMirroringSystemCastingInstance]
+ -[MXSystemController hasEntitlementForRemoteDeviceControlByConversationApp]
+ -[MXSystemController setHasEntitlementForRemoteDeviceControlByConversationApp:]
+ -[MXSystemMediaCastingController_Client flushPendingHandlersWithError:]
+ -[MXSystemMediaCastingController_Client handleAsyncResult:]
+ -[MXSystemMediaCastingController_Client registerPendingHandler:]
+ -[MXSystemMediaCastingController_Client takePendingHandlerForRequestID:]
+ GCC_except_table105
+ GCC_except_table109
+ GCC_except_table118
+ GCC_except_table125
+ GCC_except_table138
+ GCC_except_table145
+ GCC_except_table146
+ GCC_except_table77
+ GCC_except_table83
+ GCC_except_table85
+ GCC_except_table90
+ _AVSystemController_MatchRingtoneVolumeToggleDidChangeNotification
+ _AVSystemController_MatchRingtoneVolumeToggleDidChangeNotificationParameter_AudioCategory
+ _AVSystemController_MatchRingtoneVolumeToggleDidChangeNotificationParameter_Enabled
+ _AVSystemController_RemoteDeviceControlIsAllowedDidChangeNotification
+ _AVSystemController_RemoteDeviceControlIsAllowedDidChangeNotificationParameter_Reason
+ _CMSMNotificationUtility_PostMatchRingtoneVolumeToggleDidChange
+ _CMSMVAUtility_IsPersonalAudioDeviceOrCarKitInUse
+ _FigCFArrayGetFirstIndexOfValue
+ _FigStarkModeSanitizeVideoFadeDuration
+ _MX_FeatureFlags_IsAdditiveRoutingSessionFormatEnabled
+ _MX_FeatureFlags_IsAdditiveRoutingSessionFormatEnabled.onceToken
+ _MX_FeatureFlags_IsAdditiveRoutingSessionFormatEnabled.sIsAdditiveRoutingSessionFormatEnabled
+ _OBJC_CLASS_$_MXMDEExtensionRequest
+ _OBJC_CLASS_$_MXMDEPendingExtensionRequest
+ _OBJC_IVAR_$_MXCoreSessionBase._preferredOutputSampleRate
+ _OBJC_IVAR_$_MXMDEExtensionRequest._completion
+ _OBJC_IVAR_$_MXMDEExtensionRequest._done
+ _OBJC_IVAR_$_MXMDEExtensionRequest._instance
+ _OBJC_IVAR_$_MXMDEExtensionRequest._lock
+ _OBJC_IVAR_$_MXMDEExtensionRequest._operation
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._clientConnection
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._done
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._lock
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._objectID
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._requestID
+ _OBJC_IVAR_$_MXMDEPendingExtensionRequest._resultOpCode
+ _OBJC_IVAR_$_MXSessionManager._alarmVolumeChangedOnPersonalRoute
+ _OBJC_IVAR_$_MXSessionManager._ringtoneVolumeChangedOnPersonalRoute
+ _OBJC_IVAR_$_MXSystemController._hasEntitlementForRemoteDeviceControlByConversationApp
+ _OBJC_IVAR_$_MXSystemMediaCastingController_Client.nextRequestID
+ _OBJC_IVAR_$_MXSystemMediaCastingController_Client.pendingHandlers
+ _OBJC_IVAR_$_MXSystemMediaCastingController_Client.pendingLock
+ _OBJC_METACLASS_$_MXMDEExtensionRequest
+ _OBJC_METACLASS_$_MXMDEPendingExtensionRequest
+ _OUTLINED_FUNCTION_162
+ _OUTLINED_FUNCTION_163
+ _OUTLINED_FUNCTION_164
+ _OUTLINED_FUNCTION_165
+ _OUTLINED_FUNCTION_166
+ _PVMGetMappedRouteIdentifier
+ _TEMP_kFigEndpointCentralNotification_CarPlayScreenBeginFadeIn
+ _TEMP_kFigEndpointCentralNotification_CarPlayScreenBeginFadeOut
+ __OBJC_$_CLASS_METHODS_MXSessionManager(InterruptionActionMapper|DuckingUtilities|CameraAttributionInformationUtilities|MXSessionManagerContinuityScreenOutputPortUtilities|PickableRoutes|Common|VAUtilities|OnHeadBluetoothAccessoryPortUtilities|Utilities|ActivationUtilities)
+ __OBJC_$_CLASS_METHODS_MXSessionResumptionContext
+ __OBJC_$_INSTANCE_METHODS_MXMDEExtensionRequest
+ __OBJC_$_INSTANCE_METHODS_MXMDEPendingExtensionRequest
+ __OBJC_$_INSTANCE_VARIABLES_MXMDEExtensionRequest
+ __OBJC_$_INSTANCE_VARIABLES_MXMDEPendingExtensionRequest
+ __OBJC_CLASS_RO_$_MXMDEExtensionRequest
+ __OBJC_CLASS_RO_$_MXMDEPendingExtensionRequest
+ __OBJC_METACLASS_RO_$_MXMDEExtensionRequest
+ __OBJC_METACLASS_RO_$_MXMDEPendingExtensionRequest
+ ___112-[MXSystemCastingExtensionInstance activateDeviceWithDescription:withNWEndpoints:isMirroring:completionHandler:]_block_invoke_2
+ ___50-[MXMDEExtensionRequest remoteProxyForConnection:]_block_invoke
+ ___75-[MXMDEExtensionRequest initWithOperation:instance:timeoutNsec:completion:]_block_invoke
+ ___82-[MXSystemMediaCastingController_Client mediaSourceDataForKeys:completionHandler:]_block_invoke
+ ___84-[MXBiomeStreams donateDiscoverabilitySignalWithContentIdentifier:context:userInfo:]_block_invoke
+ ___89-[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]_block_invoke
+ ___89-[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]_block_invoke_2
+ ___89-[MXSystemMediaCastingController_Client sendData:forApplicationID:withCompletionHandler:]_block_invoke
+ ___92-[MXSystemMediaCastingController_Client sendApplicationLaunchMessage:withCompletionHandler:]_block_invoke
+ ___MX_FeatureFlags_IsAdditiveRoutingSessionFormatEnabled_block_invoke
+ ___block_descriptor_137_e8_32b_e5_v8?0ls32l8
+ ___block_descriptor_194_e5_v8?0l
+ ___block_descriptor_40_e8_32b_e34_v24?0"NSError"8"NSDictionary"16ls32l8
+ ___block_descriptor_40_e8_32o_e20_v24?0"NSError"816ls32l8
+ ___block_descriptor_40_e8_32o_e22_v16?0"NSDictionary"8ls32l8
+ ___block_descriptor_40_e8_32o_e34_v24?0"NSError"8"NSDictionary"16ls32l8
+ ___block_descriptor_40_e8_32o_e62_v24?0"<MediaDeviceServerInterface>"8?<v?"NSDictionary">16ls32l8
+ ___block_descriptor_44_e8_32o_e62_v24?0"<MediaDeviceServerInterface>"8?<v?"NSDictionary">16ls32l8
+ ___block_descriptor_48_e8_32o40b_e34_v24?0"NSError"8"NSDictionary"16ls40l8s32l8
+ ___block_descriptor_48_e8_32o40o_e34_v24?0"NSError"8"NSDictionary"16ls32l8s40l8
+ ___block_descriptor_48_e8_32o_e62_v24?0"<MediaDeviceServerInterface>"8?<v?"NSDictionary">16ls32l8
+ ___block_descriptor_81_e8_32r_e5_v8?0lr32l8
+ ___fsm_beginVideoCrossfadeForScreenTransition_block_invoke
+ ___getBMDiscoverabilitySignalsClass_block_invoke
+ _dispatch_suspend
+ _fsm_postCarPlayShellFadeNotification
+ _fsm_postStateChangedOnAllHandlers
+ _getBMDiscoverabilitySignalsClass.softClass
+ _kMXDiscoverabilitySignal_MatchRingtoneVolumeDisabledContentIdentifier
+ _kMXSessionAudioCategory_HomeDeviceCriticalAlert
+ _kMXSystemControllerNotificationKey_MatchRingtoneVolumeToggleDidChange_AudioCategory
+ _kMXSystemControllerNotificationKey_MatchRingtoneVolumeToggleDidChange_Enabled
+ _kMXSystemControllerNotificationKey_RemoteDeviceControlIsAllowedDidChange_Reason
+ _kMXSystemControllerNotification_MatchRingtoneVolumeToggleDidChange
+ _kMXSystemControllerNotification_RemoteDeviceControlIsAllowedDidChange
+ _kMXSystemMediaCastingControllerMsgParam_RequestID
+ _kMXSystemMediaCastingControllerReplyParam_ErrorCode
+ _kMXSystemMediaCastingControllerReplyParam_Result
+ _mxsmccs_CopyActiveClient
+ _xpc_retain
- +[MXSessionManager sendTelemetryForMatchRingtoneVolumeToggleChange]
- -[MXCoreSession getPreferredOutputSampleRatePointer]
- -[MXCoreSession preferredOutputSampleRate]
- -[MXCoreSession setPreferredOutputSampleRate:]
- GCC_except_table115
- GCC_except_table120
- GCC_except_table126
- GCC_except_table128
- GCC_except_table137
- GCC_except_table143
- GCC_except_table144
- GCC_except_table239
- GCC_except_table62
- GCC_except_table64
- GCC_except_table76
- _FigRoutingContextUtilities_CopyPredictedEndpoints
- _OBJC_IVAR_$_MXCoreSession._preferredOutputSampleRate
- __OBJC_$_CLASS_METHODS_MXSessionManager
- ___FigRoutingContextUtilities_CopyPredictedEndpoints_block_invoke
- ___block_descriptor_129_e8_32b_e5_v8?0ls32l8
- ___block_descriptor_40_e8_32b_e20_v24?0"NSError"816ls32l8
- ___block_descriptor_40_e8_32b_e22_v16?0"NSDictionary"8ls32l8
- ___block_descriptor_48_e8_32o40b_e22_v16?0"NSDictionary"8ls40l8s32l8
- ___block_descriptor_48_e8_32o40o_e20_v24?0"NSError"816ls32l8s40l8
- ___block_descriptor_48_e8_32o40r_e22_v16?0"NSDictionary"8lr40l8s32l8
- ___block_descriptor_56_e8_32o40o48r_e22_v16?0"NSDictionary"8lr48l8s32l8s40l8
- ___block_descriptor_57_e8_32r_e5_v8?0lr32l8
- _customEndpoint_getFeaturesFromModelID.audioAndScreenModelIDs
- _vaemConvertToScalarInVAD
CStrings:
+ "%u='%c%c%c%c'"
+ "+[MXSessionResumptionContext canExcludeSessionFromActiveSessionList:forResumingSession:]"
+ "-CMSMNotificationUtilities- %s: Not posting MatchRingtoneVolumeToggleDidChange notification; audioCategory is NULL"
+ "-CMSMNotificationUtilities- %s: Posting MatchRingtoneVolumeToggleDidChange notification for category '%{public}@' with %{BOOL}u"
+ "-CMSSleep- %s: Failed to create playback assertion for %{public}@"
+ "-CMSessionMgr- %s: %{public}@ volume-sync override set on this personal audio route"
+ "-CMSessionMgr- %s: Could not find BT A2DP Port from portsArray. PortsArray = %{public}@. VA-reported port types: [%{public}@]"
+ "-CMSessionMgr- %s: Could not find a BT A2DP Port from portsArray since portsArray is nil"
+ "-CMVAEndpoint- %s: Queried VA for partners of port=%u (type='%{public}.4s'), VA returned partners=%{public}@"
+ "-CMVAEndptMgr- %s: Clearing the Ringtone and Alarm volume-sync overrides (Ringtone = %{BOOL}u, Alarm = %{BOOL}u) because no personal audio device or CarKit is in use anymore"
+ "-CMVAEndptMgr- %s: Clearing the Ringtone and Alarm volume-sync overrides (Ringtone = %{BOOL}u, Alarm = %{BOOL}u) because the active route moved to a different personal audio device. Old route %{public}@~%{public}@, new route %{public}@~%{public}@"
+ "-CMVAEndptUtl- %s: Connected wireless ports=%{public}@, supporting multiple connections=%{public}@"
+ "-CMVAEndptUtl- %s: Port %u is BTManaged but not in-ear, filtering out"
+ "-FigCustomEndpointManager- %s: Protocol %{public}@ no longer installed; clearing cache instead of saving"
+ "-FigCustomEndpointManager- %s: Skipping cached endpoint %{private}@, creation failed with err=%d"
+ "-FigEndpointUIAgentHelper- %s: Setting new endpointUIAgent, current cached (%p) "
+ "-FigRouteDiscoveryManager- %s: Non-preset predicted route discovery finished after %.3f sec: %{public}s. routeUIDs = %{public}@"
+ "-FigRouteDiscoveryManager- %s: Resolved non-preset predicted endpoint[%ld]: routeUID=%{public}@, endpoint=[%p], isDissociated=%{BOOL}u, isActivated=%{BOOL}u"
+ "-FigRouteDiscoveryManager- %s: Resolved only %ld of %lu requested non-preset predicted routeUIDs — the missing ones are either unavailable or were filtered as dissociated. Requested: %{public}@"
+ "-FigRouteDiscoveryManager- %s: Skipping endpoint with ID='%{public}@', Name='%{public}@' because it is dissociated"
+ "-FigRouteDiscoveryManager- %s: Skipping endpoint with ID='%{public}@', Name='%{public}@' for requested routeUID='%{public}@' isLocalDevice=%{BOOL}u: isRemoteControlOnly=%{BOOL}u, isWHAGroupable=%{BOOL}u"
+ "-FigRoutingContext- %s: Returning %lu predicted route descriptors to client (requested %lu UIDs), origin=%ld, descriptors=%{private}@"
+ "-FigRoutingManager- %s: Adding a DISSOCIATED endpoint to the aggregate — activation is expected to fail with kFigEndpointError_Dissociated: routeUID=%{public}@, name=%{public}@, endpoint=[%p], routingContextUUID=%{public}@"
+ "-FigRoutingManager- %s: Adding endpoint to the aggregate: routeUID=%{public}@, name=%{public}@, endpoint=[%p], isDissociated=NO, routingContextUUID=%{public}@"
+ "-FigRoutingManager_iOSEndpointHelpers- %s: This is a 3P Casting endpoint type"
+ "-MXAirPlayPredictedRoutesRegistry- %s: Ignoring predicted route descriptor of unexpected class %{public}@, expected a dictionary"
+ "-MXAirPlayPredictedRoutesRegistry- %s: routeUID is nil or not a string"
+ "-MXAirPlayPredictedRouting- %s: Predicted routing failed with kFigEndpointError_Dissociated (%d) for endpointName=%{public}@, routeUID=%{public}@ — a dissociated endpoint reached activation, falling back to the local route. See <rdar://154123401>."
+ "-MXBiomeStreams- %s: Donating Discoverability.Signals event '%{public}@' (context %{public}@)"
+ "-MXBiomeStreams- %s: donateDiscoverabilitySignal called with nil/empty contentIdentifier"
+ "-MXCustomEndpointCache- %s: Cleared cached endpoints for uninstalled protocol '%{public}@'"
+ "-MXCustomEndpointCache- %s: No cached endpoints found for protocol '%{public}@'"
+ "-MXSessionContext- %s: Client '%{public}@' is not added to active session list as it is the CarSession reclaiming mainAudio for '%{public}@' AirPlay Video playback"
+ "-MXSessionManagerDuckingUtilities- %s: [%p] '%{public}@' currentVolume = %.4f (%.2f dB); defaultDuckToLevelDB = %.4f, recomputedDuckToLevelDB = %.4f, setByClient = %{public}@; recomputedDuckVolume = %.4f"
+ "-MXSessionManagerDuckingUtilities- %s: [%p] '%{public}@' currentVolume = %.4f (%.2f dB); duckToLevelDB = %.4f; recomputedDuckVolume = %.4f"
+ "-MXSessionManagerUtilities- %s: Interruptor '%{public}@' and victim '%{public}@' can coexist due to SharePlay rules."
+ "-MXSessionManagerUtilities- %s: Resumption context diverged, but no interruptor session found"
+ "-MXSessionManagerUtilities- %s: Skipping volume sync for %{public}@ because user has changed the volume on this personal audio route"
+ "-MXSystemMediaCasting- %s: <%{public}@> extension did not respond to '%{public}@': %{public}@"
+ "-MXSystemMediaCasting- %s: <%{public}@> terminating unresponsive extension after '%{public}@' timed out"
+ "-MXSystemMediaCasting- %s: No extension connection available for '%{public}@'; failing the request"
+ "-MXSystemMediaCastingController_Client- %s: No pending handler for requestID %llu"
+ "-MXSystemMediaCastingController_Server- %s: Ignoring StopApplication from non-active casting client; leaving the active app running."
+ "-MXSystemMediaCastingController_Server- %s: No active casting client; dropping media-source update."
+ "-MXSystemMediaCastingController_Server- %s: No active casting client; dropping received data."
+ "-MXSystemMediaCastingController_Server- %s: Sent media-source update to active casting client."
+ "-MXSystemMediaCastingController_Server- %s: Sent received data to active casting client."
+ "-MXSystemMediaCastingController_Server- %s: err %d when making DidReceiveMediaSourceUpdate message, %llu"
+ "-MXSystemMediaCastingController_Server- %s: err %d when making ReportDataReceived message, %llu"
+ "-MXSystemSounds- %s: JBL Sound will not play to System Local VAD, returning 1.0 to SSS (volume for this sound is applied on the VAD itself, not in software)"
+ "-MX_FeatureFlags- %s: MediaExperience/AdditiveRoutingSessionFormat feature is %{public}@"
+ "-[MXBiomeStreams donateDiscoverabilitySignalWithContentIdentifier:context:userInfo:]"
+ "-[MXBiomeStreams donateDiscoverabilitySignalWithContentIdentifier:context:userInfo:]_block_invoke"
+ "-[MXCustomEndpointCache clearCachedEndpointsForProtocol:]"
+ "-[MXMDEExtensionRequest remoteProxyForConnection:]"
+ "-[MXSessionManager populatePrimaryRouteConfig:routesInfo:systemAudioContextUUID:volumeButtonClientSession:]"
+ "-[MXSessionManager(Utilities) canSessionsCoexistDueToSharePlay:victim:]"
+ "-[MXSystemCastingExtensionInstance noteUnresponsiveExtensionForOperation:error:]"
+ "-[MXSystemCastingExtensionInstance sendVolumeRequestForOperation:completionHandler:send:]_block_invoke_2"
+ "-[MXSystemMediaCastingController_Client handleAsyncResult:]"
+ "-stark mode- %s: Calling send command for stark modes changed, dictionary %{public}@"
+ "-stark mode- %s: CarPlay video fade decision: targets=%{public}s duration=%f supported=%{BOOL}u -> %{public}s"
+ "-stark mode- %s: Clamping head-unit fade duration %f to %f"
+ "-stark mode- %s: Extended mode change queue hold to %.3f s: a second video crossfade engaged while one was already held (targets=%{public}s)"
+ "-stark mode- %s: Failed to send videoPlaybackFadeOut trigger to head unit, err=%d"
+ "-stark mode- %s: Finalizing FigStarkModeController for client with PID %d"
+ "-stark mode- %s: Held mode change queue for %.3f s video crossfade (targets=%{public}s)"
+ "-stark mode- %s: Ignoring negative head-unit fade duration %f"
+ "-stark mode- %s: Ignoring non-finite head-unit fade duration %f"
+ "-stark mode- %s: List of borrowers = %{public}@"
+ "-stark mode- %s: Mode change request (async) waited %.3f s to be scheduled (video crossfade or queue contention): %{public}s"
+ "-stark mode- %s: Mode change request waited %.3f s to be scheduled (video crossfade or queue contention): %{public}s"
+ "-stark mode- %s: Posted CarPlayScreenFade%{public}s notification to the Shell with duration:%f"
+ "-stark mode- %s: Posting state changed for token %p"
+ "-stark mode- %s: Released mode change queue during teardown: torn down mid video crossfade"
+ "-stark mode- %s: Released mode change queue: video crossfade window complete"
+ "-stark mode- %s: Returned with err=%d"
+ "-stark mode- %s: Sent videoPlaybackFadeOut trigger to head unit"
+ "-stark mode- %s: Skipping deferred (faded) modesChanged broadcast: superseded by a newer mode change"
+ "-stark mode- %s: Unexpected error: No session active over CarPlay Video"
+ "-stark mode- %s: called"
+ "-stark mode- %s: carPlayEndpoint is NULL"
+ "-stark mode- %s: carPlayEndpoint is NULL; cannot send videoPlaybackFadeOut trigger"
+ "-stark mode- %s: carPlayEndpoint or currentExtendedEndpoint is NULL"
+ "-stark mode- %s: controller is NULL"
+ "20:44:01"
+ "<no reason>"
+ "AdditiveRoutingSessionFormat"
+ "BMDiscoverabilitySignals"
+ "CMSMNotificationUtility_PostMatchRingtoneVolumeToggleDidChange"
+ "CMSMVAUtility_CopyWirelessPortsSupportingMultipleConnections"
+ "CMSMVAUtility_IsAnyRouteBTManagedAndInEar"
+ "CarPlay video route to car"
+ "CarPlay video route to phone"
+ "CarPlayScreenBeginFadeIn"
+ "CarPlayScreenBeginFadeOut"
+ "CarPlayScreenFadeDurationInSeconds"
+ "ENGAGED"
+ "Extension was unresponsive to a request"
+ "FigRoutingManagerAddEndpointToAggregate"
+ "FigStarkModeSanitizeVideoFadeDuration"
+ "HomeDeviceCriticalAlert"
+ "In"
+ "MX_FeatureFlags_IsAdditiveRoutingSessionFormatEnabled_block_invoke"
+ "MatchRingtoneVolumeToggleDidChange"
+ "Out"
+ "RemoteDeviceControlIsAllowedDidChange"
+ "RequestID"
+ "Result"
+ "SKIPPED"
+ "Sep 27 2026"
+ "TIMED OUT waiting for discovery (endpoints may have changed underneath us)"
+ "VideoPlaybackOverlayBannerPressed"
+ "VideoPlayback_PlayerEvent"
+ "activateDevice"
+ "cmsmGetMaxVoiceOverVolumeOnVADUID"
+ "com.apple.MediaExperience.matchRingtoneVolumeDisabled"
+ "com.apple.mediaexperience.SystemCastingExtension"
+ "deactivateDevice"
+ "decreaseVolume"
+ "fsm_beginVideoCrossfadeForScreenTransition"
+ "fsm_beginVideoCrossfadeForScreenTransition_block_invoke"
+ "fsm_postCarPlayShellFadeNotification"
+ "fsm_requestResourceModeChangeUnborrow"
+ "fsm_sendVideoFadeOutTriggerToHeadUnit"
+ "fsm_stateFinalize"
+ "fsmcontroller_RequestModeChangeAsync_block_invoke"
+ "fsmcontroller_RequestModeChange_block_invoke"
+ "getVolume"
+ "headUnitFadeOut"
+ "headUnitFadeOut+shellFadeIn"
+ "increaseVolume"
+ "mediaSourceData"
+ "sendData"
+ "setVolume"
+ "shellFadeOut"
+ "signalled by discovery"
+ "startApplication"
+ "v24@?0@\"<MediaDeviceServerInterface>\"8@?<v@?@\"NSDictionary\">16"
+ "v24@?0@\"NSError\"8@\"NSDictionary\"16"
+ "videoPlaybackFadeOut"
+ "\xf0\xf0\xf0\xf0\xa1"
- "-CMSessionMgr- %s: Could not find BT A2DP Port from portsArray. PortsArray = %{public}@"
- "-CMVAEndptMgr- %s: AudioObjectGetPropertyData(kAudioDevicePropertyVolumeDecibelsToScalar) failed with err = %d = %{public}.4s"
- "-FigEndpointUIAgentHelper- %s: Setting new endpointUIAgent (%p) old (%p) "
- "-MXAirPlayPredictedRoutesRegistry- %s: routeUID is nil"
- "-MXSessionManagerDuckingUtilities- %s: [%p] '%{public}@' currentVolume = %.4f; defaultDuckToLevelDB = %.4f, recomputedDuckToLevelDB = %.4f, setByClient = %{public}@; duckToLevelLinear = %.4f; recomputedDuckVolume = %.4f"
- "-MXSessionManagerDuckingUtilities- %s: [%p] '%{public}@' currentVolume = %.4f; duckToLevelDB = %.4f, duckToLevelLinear = %.4f; recomputedDuckVolume = %.4f"
- "-MXSessionManagerUtilities- %s: Resumption context diverged by interruptor but no interruptor session found"
- "-MXSystemMediaCastingController_Server- %s: Sent message to connection."
- "-MXSystemMediaCastingController_Server- %s: Timeout waiting for completion handler"
- "-MXSystemMediaCastingController_Server- %s: Timeout waiting for sendData completion handler"
- "-MXSystemSounds- %s: JBL Sound will not play to System Local VAD, returning 1.0 to SSS"
- "-[MXSystemCastingExtensionInstance decreaseVolumeByCount:forDevice:completionHandler:]_block_invoke"
- "-[MXSystemCastingExtensionInstance getVolumeForDevice:completionHandler:]_block_invoke"
- "-[MXSystemCastingExtensionInstance increaseVolumeByCount:forDevice:completionHandler:]_block_invoke"
- "-[MXSystemCastingExtensionInstance setVolume:forDevice:completionHandler:]_block_invoke"
- "21:49:51"
- "CMSystemSoundMgrGetMaxVoiceOverVolumeOnSystemLocalVAD"
- "FigRoutingContextUtilities_CopyPredictedEndpoints"
- "SemaphoreTimedOut"
- "Send data operation failed"
- "Sep 23 2026"
- "dataLength"
- "result"
- "success"
- "vaemConvertToScalarInVAD"
- "\xf0\xf0\xf0\xf0\xb1"
```
