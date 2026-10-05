## CoreSpeechFoundation

> `/System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/CoreSpeechFoundation`

```diff

-3600.70.47.11.1
-  __TEXT.__text: 0xcbfc4
-  __TEXT.__objc_methlist: 0xd9e8
-  __TEXT.__const: 0xfe8
+3605.31.3.0.0
+  __TEXT.__text: 0xcf004
+  __TEXT.__objc_methlist: 0xdcb0
+  __TEXT.__const: 0xff8
   __TEXT.__dlopen_cstrs: 0x24a
   __TEXT.__constg_swiftt: 0x2cc
   __TEXT.__swift5_typeref: 0x1dc
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_types: 0x30
-  __TEXT.__cstring: 0x1685c
+  __TEXT.__cstring: 0x16c54
   __TEXT.__swift5_reflstr: 0x278
   __TEXT.__swift5_assocty: 0x78
   __TEXT.__swift5_fieldmd: 0x250
   __TEXT.__swift5_proto: 0x74
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__gcc_except_tab: 0x3cec
-  __TEXT.__oslogstring: 0x11a3e
-  __TEXT.__unwind_info: 0x3e08
+  __TEXT.__gcc_except_tab: 0x3d30
+  __TEXT.__oslogstring: 0x11e8b
+  __TEXT.__unwind_info: 0x3ed0
   __TEXT.__eh_frame: 0x270
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2840
-  __DATA_CONST.__objc_classlist: 0x748
+  __DATA_CONST.__const: 0x2920
+  __DATA_CONST.__objc_classlist: 0x758
   __DATA_CONST.__objc_catlist: 0x58
-  __DATA_CONST.__objc_protolist: 0x220
+  __DATA_CONST.__objc_protolist: 0x228
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x18
-  __DATA_CONST.__objc_selrefs: 0x7508
+  __DATA_CONST.__objc_selrefs: 0x7680
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0x568
+  __DATA_CONST.__objc_superrefs: 0x578
   __DATA_CONST.__objc_arraydata: 0x1c8
-  __DATA_CONST.__got: 0x1038
-  __AUTH_CONST.__const: 0x1ae0
-  __AUTH_CONST.__cfstring: 0x95e0
-  __AUTH_CONST.__objc_const: 0x14e50
+  __DATA_CONST.__got: 0x1048
+  __AUTH_CONST.__const: 0x1b40
+  __AUTH_CONST.__cfstring: 0x9a80
+  __AUTH_CONST.__objc_const: 0x15270
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_dictobj: 0x1e0
   __AUTH_CONST.__objc_intobj: 0x4b0
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_floatobj: 0x1a0
-  __AUTH_CONST.__auth_got: 0xfc0
-  __AUTH.__objc_data: 0x1c8
-  __DATA.__objc_ivar: 0xd9c
-  __DATA.__data: 0x1a00
-  __DATA.__bss: 0x1580
-  __DATA_DIRTY.__objc_data: 0x47c0
+  __AUTH_CONST.__auth_got: 0xfc8
+  __AUTH.__objc_data: 0x218
+  __DATA.__objc_ivar: 0xdd4
+  __DATA.__data: 0x1a60
+  __DATA.__bss: 0x1570
+  __DATA_DIRTY.__objc_data: 0x4810
   __DATA_DIRTY.__data: 0x2e8
-  __DATA_DIRTY.__bss: 0x608
+  __DATA_DIRTY.__bss: 0x660
   __DATA_DIRTY.__common: 0x70
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/Accelerate.framework/Accelerate

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5244
-  Symbols:   9844
-  CStrings:  3751
+  Functions: 5311
+  Symbols:   9961
+  CStrings:  3810
 
Symbols:
+ +[CSAudioConsumingStateMonitor sharedInstance]
+ +[CSAudioStartStreamOption getRecordingStartTime:useMachContinuousTime:]
+ +[CSAudioStartStreamOption getRecordingStartTime:useMachContinuousTime:isVoiceTriggered:voiceTriggerInfo:useVoiceTriggerStartTime:]
+ +[CSAudioStreamHoldRequestOption defaultOptionWithTimeout:requestExclaveAudio:]
+ +[CSConfig inputRecordingDurationInSecsAttentive]
+ +[CSFModelConfigDecoder purgeCachedConfigs]
+ +[CSFModelConfigDecoder(Test) cachedConfigPathsForTesting]
+ +[CSUtils allowAttentiveRingBufferSize]
+ +[CSUtils isAudioBufferPoolEnabled]
+ +[CSUtils isBargeInDisabled]
+ +[CSUtils isContinuousConversationDisabledInSiriX]
+ +[CSUtils isPerceptionBasedSpeakerChangeDetectionEnabled]
+ +[CSUtils supportEarlyRecordingStartNotification]
+ +[CSUtils(AudioDevice) isCarPlayRecordRoute:]
+ +[CSUtils(Directory) _clearLogFilesInDirectory:matchingPatterns:exceedNumber:outError:]
+ +[CSUtils(Directory) clearLogFilesInDirectory:matchingPatterns:exceedNumber:]
+ +[CSUtils(Directory) clearLogFilesInDirectorySync:matchingPatterns:exceedNumber:outError:]
+ -[CSAudioConsumingStateMonitor _setAudioConsumingActive:]
+ -[CSAudioConsumingStateMonitor _startMonitoringWithQueue:]
+ -[CSAudioConsumingStateMonitor _stopMonitoring]
+ -[CSAudioConsumingStateMonitor backdateSessionStartBySeconds:]
+ -[CSAudioConsumingStateMonitor init]
+ -[CSAudioConsumingStateMonitor isAudioConsumingSessionActive]
+ -[CSAudioConsumingStateMonitor notifyAudioConsumingSessionDidStart]
+ -[CSAudioConsumingStateMonitor notifyAudioConsumingSessionDidStop]
+ -[CSAudioProvider _acquirePowerMeterLockFrom:option:needsBoost12dB:]
+ -[CSAudioProvider _anyPowerMeterLockNeedsBoost12dB]
+ -[CSAudioProvider _clientIdentityQualifiesForPowerMeter:]
+ -[CSAudioProvider _forceReleaseAllPowerMeterLocks]
+ -[CSAudioProvider _forceReleasePowerMeterLockFrom:]
+ -[CSAudioProvider _setStreamStateStreamingForTesting]
+ -[CSAudioProvider exfiltratingStreamHolderCountLock]
+ -[CSAudioProvider exfiltratingStreamHolderCount]
+ -[CSAudioProvider hasPowerMeterLock]
+ -[CSAudioProvider isLinwoodEnabledForPowerMeter]
+ -[CSAudioProvider powerMeterLocks]
+ -[CSAudioProvider powerMeterNeedsBoost12dB]
+ -[CSAudioProvider setExfiltratingStreamHolderCount:]
+ -[CSAudioProvider setExfiltratingStreamHolderCountLock:]
+ -[CSAudioProvider setHasPowerMeterLock:]
+ -[CSAudioProvider setIsLinwoodEnabledForPowerMeter:]
+ -[CSAudioProvider setPowerMeterLocks:]
+ -[CSAudioProvider setPowerMeterNeedsBoost12dB:]
+ -[CSAudioProviderPowerMeterLock initWithClientIdentity:needsBoost12dB:]
+ -[CSAudioProviderPowerMeterLock needsBoost12dB]
+ -[CSAudioRecordContext canCreateContinuousConversationProfile]
+ -[CSAudioRecordContext isInitialRequest]
+ -[CSAudioSpectralMeter setNormalizationEnabled:]
+ -[CSAudioStreamHoldRequestOption initWithTimeout:clientIdentity:requireRecordModeLock:requireListeningMicIndicatorLock:requestExclaveAudio:]
+ -[CSAudioStreamHoldRequestOption requestExclaveAudio]
+ -[CSAudioStreamHolding initWithName:clientIdentity:requestExclaveAudio:]
+ -[CSAudioStreamHolding requestExclaveAudio]
+ -[CSEventMonitor _removeObserverOnQueue:]
+ -[CSExclaveRecordClient skipProcessingRaiseToSpeakAOE:]
+ GCC_except_table1356
+ GCC_except_table1387
+ GCC_except_table1468
+ GCC_except_table1473
+ GCC_except_table1474
+ GCC_except_table1477
+ GCC_except_table1478
+ GCC_except_table1479
+ GCC_except_table1480
+ GCC_except_table1492
+ GCC_except_table1497
+ GCC_except_table1499
+ GCC_except_table1500
+ GCC_except_table1503
+ GCC_except_table1504
+ GCC_except_table1505
+ GCC_except_table1511
+ GCC_except_table1523
+ GCC_except_table1918
+ GCC_except_table1919
+ GCC_except_table1920
+ GCC_except_table1922
+ GCC_except_table1926
+ GCC_except_table1929
+ GCC_except_table1932
+ GCC_except_table1938
+ GCC_except_table1945
+ GCC_except_table1947
+ GCC_except_table1948
+ GCC_except_table1963
+ GCC_except_table1969
+ GCC_except_table2057
+ GCC_except_table2062
+ GCC_except_table2125
+ GCC_except_table2137
+ GCC_except_table2179
+ GCC_except_table2180
+ GCC_except_table2182
+ GCC_except_table2183
+ GCC_except_table2189
+ GCC_except_table2200
+ GCC_except_table2207
+ GCC_except_table2250
+ GCC_except_table2268
+ GCC_except_table2349
+ GCC_except_table2461
+ GCC_except_table2496
+ GCC_except_table262
+ GCC_except_table2667
+ GCC_except_table2671
+ GCC_except_table274
+ GCC_except_table2750
+ GCC_except_table2761
+ GCC_except_table2763
+ GCC_except_table2768
+ GCC_except_table2770
+ GCC_except_table2783
+ GCC_except_table2792
+ GCC_except_table2810
+ GCC_except_table2831
+ GCC_except_table2877
+ GCC_except_table2934
+ GCC_except_table2936
+ GCC_except_table2937
+ GCC_except_table306
+ GCC_except_table3099
+ GCC_except_table3240
+ GCC_except_table3248
+ GCC_except_table3256
+ GCC_except_table3270
+ GCC_except_table3272
+ GCC_except_table3273
+ GCC_except_table328
+ GCC_except_table330
+ GCC_except_table3309
+ GCC_except_table331
+ GCC_except_table3315
+ GCC_except_table337
+ GCC_except_table3376
+ GCC_except_table3380
+ GCC_except_table340
+ GCC_except_table3435
+ GCC_except_table3447
+ GCC_except_table3451
+ GCC_except_table3458
+ GCC_except_table3470
+ GCC_except_table3494
+ GCC_except_table3495
+ GCC_except_table3496
+ GCC_except_table3497
+ GCC_except_table3522
+ GCC_except_table3535
+ GCC_except_table3705
+ GCC_except_table3765
+ GCC_except_table3779
+ GCC_except_table3821
+ GCC_except_table3822
+ GCC_except_table3851
+ GCC_except_table3852
+ GCC_except_table3857
+ GCC_except_table3858
+ GCC_except_table3859
+ GCC_except_table3882
+ GCC_except_table3884
+ GCC_except_table3888
+ GCC_except_table3889
+ GCC_except_table3890
+ GCC_except_table3895
+ GCC_except_table3947
+ GCC_except_table3968
+ GCC_except_table398
+ GCC_except_table3988
+ GCC_except_table3989
+ GCC_except_table399
+ GCC_except_table3990
+ GCC_except_table3991
+ GCC_except_table400
+ GCC_except_table4001
+ GCC_except_table401
+ GCC_except_table402
+ GCC_except_table4102
+ GCC_except_table4104
+ GCC_except_table4105
+ GCC_except_table4106
+ GCC_except_table4107
+ GCC_except_table4110
+ GCC_except_table4111
+ GCC_except_table4114
+ GCC_except_table4115
+ GCC_except_table4116
+ GCC_except_table4117
+ GCC_except_table4118
+ GCC_except_table4119
+ GCC_except_table4120
+ GCC_except_table4121
+ GCC_except_table4122
+ GCC_except_table4125
+ GCC_except_table4126
+ GCC_except_table4132
+ GCC_except_table4133
+ GCC_except_table4135
+ GCC_except_table4137
+ GCC_except_table4138
+ GCC_except_table4140
+ GCC_except_table4141
+ GCC_except_table4144
+ GCC_except_table4145
+ GCC_except_table4148
+ GCC_except_table4149
+ GCC_except_table4150
+ GCC_except_table4152
+ GCC_except_table4153
+ GCC_except_table4154
+ GCC_except_table4156
+ GCC_except_table4157
+ GCC_except_table4159
+ GCC_except_table4160
+ GCC_except_table4161
+ GCC_except_table4162
+ GCC_except_table4190
+ GCC_except_table4240
+ GCC_except_table4244
+ GCC_except_table4295
+ GCC_except_table4296
+ GCC_except_table4306
+ GCC_except_table4308
+ GCC_except_table4330
+ GCC_except_table4332
+ GCC_except_table4333
+ GCC_except_table4336
+ GCC_except_table4337
+ GCC_except_table4338
+ GCC_except_table4339
+ GCC_except_table4340
+ GCC_except_table4341
+ GCC_except_table4342
+ GCC_except_table4343
+ GCC_except_table4366
+ GCC_except_table4367
+ GCC_except_table4370
+ GCC_except_table4371
+ GCC_except_table4372
+ GCC_except_table4374
+ GCC_except_table4376
+ GCC_except_table4377
+ GCC_except_table4378
+ GCC_except_table4379
+ GCC_except_table4380
+ GCC_except_table4381
+ GCC_except_table4383
+ GCC_except_table4385
+ GCC_except_table4386
+ GCC_except_table4388
+ GCC_except_table4390
+ GCC_except_table4392
+ GCC_except_table4394
+ GCC_except_table4401
+ GCC_except_table4414
+ GCC_except_table4415
+ GCC_except_table4417
+ GCC_except_table4418
+ GCC_except_table4420
+ GCC_except_table4422
+ GCC_except_table4423
+ GCC_except_table4424
+ GCC_except_table4429
+ GCC_except_table4431
+ GCC_except_table4435
+ GCC_except_table4436
+ GCC_except_table4466
+ GCC_except_table4578
+ GCC_except_table4585
+ GCC_except_table4745
+ GCC_except_table4801
+ GCC_except_table4802
+ GCC_except_table4803
+ GCC_except_table4805
+ GCC_except_table4806
+ GCC_except_table4807
+ GCC_except_table4808
+ GCC_except_table4809
+ GCC_except_table4810
+ GCC_except_table4812
+ GCC_except_table4813
+ GCC_except_table4815
+ GCC_except_table4817
+ GCC_except_table4818
+ GCC_except_table4820
+ GCC_except_table4856
+ GCC_except_table4922
+ GCC_except_table4927
+ GCC_except_table4968
+ GCC_except_table5034
+ GCC_except_table507
+ GCC_except_table508
+ GCC_except_table541
+ GCC_except_table578
+ GCC_except_table586
+ GCC_except_table604
+ GCC_except_table672
+ GCC_except_table681
+ GCC_except_table683
+ GCC_except_table846
+ GCC_except_table853
+ GCC_except_table916
+ GCC_except_table917
+ GCC_except_table924
+ GCC_except_table939
+ GCC_except_table945
+ GCC_except_table949
+ GCC_except_table958
+ GCC_except_table960
+ GCC_except_table961
+ GCC_except_table962
+ GCC_except_table976
+ _CSAudioPoolCleanup
+ _CSAudioPoolDataWithBytes
+ _CSSupportsCompanionRuntime
+ _OBJC_CLASS_$_CSAudioConsumingStateMonitor
+ _OBJC_CLASS_$_CSAudioProviderPowerMeterLock
+ _OBJC_IVAR_$_CSAudioConsumingStateMonitor._audioConsumingActive
+ _OBJC_IVAR_$_CSAudioConsumingStateMonitor._audioConsumingStartHostTime
+ _OBJC_IVAR_$_CSAudioConsumingStateMonitor._lock
+ _OBJC_IVAR_$_CSAudioPowerProvider._cachedSelfTapIOBufferDurationOverride
+ _OBJC_IVAR_$_CSAudioPowerProvider._spectralNormalizationEnabled
+ _OBJC_IVAR_$_CSAudioProvider._exfiltratingStreamHolderCount
+ _OBJC_IVAR_$_CSAudioProvider._exfiltratingStreamHolderCountLock
+ _OBJC_IVAR_$_CSAudioProvider._hasPowerMeterLock
+ _OBJC_IVAR_$_CSAudioProvider._isLinwoodEnabledForPowerMeter
+ _OBJC_IVAR_$_CSAudioProvider._powerMeterLocks
+ _OBJC_IVAR_$_CSAudioProvider._powerMeterNeedsBoost12dB
+ _OBJC_IVAR_$_CSAudioProviderPowerMeterLock._needsBoost12dB
+ _OBJC_IVAR_$_CSAudioStreamHoldRequestOption._requestExclaveAudio
+ _OBJC_IVAR_$_CSAudioStreamHolding._requestExclaveAudio
+ _OBJC_METACLASS_$_CSAudioConsumingStateMonitor
+ _OBJC_METACLASS_$_CSAudioProviderPowerMeterLock
+ __OBJC_$_CLASS_METHODS_CSAudioConsumingStateMonitor
+ __OBJC_$_CLASS_METHODS_CSFModelConfigDecoder(Test)
+ __OBJC_$_INSTANCE_METHODS_CSAudioConsumingStateMonitor
+ __OBJC_$_INSTANCE_METHODS_CSAudioProviderPowerMeterLock
+ __OBJC_$_INSTANCE_VARIABLES_CSAudioConsumingStateMonitor
+ __OBJC_$_INSTANCE_VARIABLES_CSAudioProviderPowerMeterLock
+ __OBJC_$_PROP_LIST_CSAudioConsumingStateMonitor
+ __OBJC_$_PROP_LIST_CSAudioProviderPowerMeterLock
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSAudioConsumingStateMonitorProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CSAudioSessionProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSAudioConsumingStateMonitorProviding
+ __OBJC_$_PROTOCOL_REFS_CSAudioConsumingStateMonitorProviding
+ __OBJC_CLASS_PROTOCOLS_$_CSAudioConsumingStateMonitor
+ __OBJC_CLASS_RO_$_CSAudioConsumingStateMonitor
+ __OBJC_CLASS_RO_$_CSAudioProviderPowerMeterLock
+ __OBJC_LABEL_PROTOCOL_$_CSAudioConsumingStateMonitorProviding
+ __OBJC_METACLASS_RO_$_CSAudioConsumingStateMonitor
+ __OBJC_METACLASS_RO_$_CSAudioProviderPowerMeterLock
+ __OBJC_PROTOCOL_$_CSAudioConsumingStateMonitorProviding
+ __ZN24CSAudioSpectralMeterImpl14_processWindowEPf
+ __ZN24CSAudioSpectralMeterImpl18resetNormalizationEv
+ __ZN24CSAudioSpectralMeterImpl23setNormalizationEnabledEb
+ ___46+[CSAudioConsumingStateMonitor sharedInstance]_block_invoke
+ ___50+[CSUtils isContinuousConversationDisabledInSiriX]_block_invoke
+ ___50-[CSAudioProvider _forceReleaseAllPowerMeterLocks]_block_invoke
+ ___51-[CSAudioProvider _forceReleasePowerMeterLockFrom:]_block_invoke
+ ___57-[CSAudioConsumingStateMonitor _setAudioConsumingActive:]_block_invoke
+ ___68-[CSAudioProvider _acquirePowerMeterLockFrom:option:needsBoost12dB:]_block_invoke
+ ___77+[CSUtils(Directory) clearLogFilesInDirectory:matchingPatterns:exceedNumber:]_block_invoke
+ ___87+[CSUtils(Directory) _clearLogFilesInDirectory:matchingPatterns:exceedNumber:outError:]_block_invoke
+ ___87+[CSUtils(Directory) _clearLogFilesInDirectory:matchingPatterns:exceedNumber:outError:]_block_invoke_2
+ ____ensurePools_block_invoke
+ ___block_descriptor_40_e8_32s_e25_q24?0"NSURL"8"NSURL"16ls32l8
+ ___block_descriptor_42_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_51_e8_32s40s_e5_v8?0ls32l8s40l8
+ __ensurePools.onceToken
+ _isContinuousConversationDisabledInSiriX.onceToken
+ _kCSDiagnosticReporterAudioConsumingSessionStale
+ _kCSEventMonitorQueueKey
+ _sConfigCache
+ _sConfigCacheLock
+ _sConfigStamp
+ _sLargePool
+ _sSmallPool
+ _stat
- +[CSUtils isSiriDSPTurnedOn]
- +[CSUtils(Directory) clearLogFilesInDirectory:matchingPattern:exceedNumber:]
- GCC_except_table1343
- GCC_except_table1374
- GCC_except_table1453
- GCC_except_table1457
- GCC_except_table1458
- GCC_except_table1459
- GCC_except_table1460
- GCC_except_table1461
- GCC_except_table1462
- GCC_except_table1463
- GCC_except_table1464
- GCC_except_table1465
- GCC_except_table1481
- GCC_except_table1483
- GCC_except_table1484
- GCC_except_table1487
- GCC_except_table1489
- GCC_except_table1495
- GCC_except_table1901
- GCC_except_table1902
- GCC_except_table1903
- GCC_except_table1904
- GCC_except_table1905
- GCC_except_table1909
- GCC_except_table1912
- GCC_except_table1913
- GCC_except_table1915
- GCC_except_table1928
- GCC_except_table1931
- GCC_except_table1946
- GCC_except_table1952
- GCC_except_table2040
- GCC_except_table2045
- GCC_except_table2105
- GCC_except_table2115
- GCC_except_table2157
- GCC_except_table2158
- GCC_except_table2160
- GCC_except_table2161
- GCC_except_table2167
- GCC_except_table2178
- GCC_except_table2185
- GCC_except_table2228
- GCC_except_table2246
- GCC_except_table2325
- GCC_except_table2435
- GCC_except_table2470
- GCC_except_table260
- GCC_except_table2626
- GCC_except_table2630
- GCC_except_table2709
- GCC_except_table272
- GCC_except_table2720
- GCC_except_table2722
- GCC_except_table2727
- GCC_except_table2729
- GCC_except_table2742
- GCC_except_table2749
- GCC_except_table2751
- GCC_except_table2769
- GCC_except_table2828
- GCC_except_table2885
- GCC_except_table2887
- GCC_except_table2888
- GCC_except_table302
- GCC_except_table3050
- GCC_except_table3191
- GCC_except_table3199
- GCC_except_table3207
- GCC_except_table3217
- GCC_except_table322
- GCC_except_table3221
- GCC_except_table3223
- GCC_except_table3224
- GCC_except_table324
- GCC_except_table325
- GCC_except_table3260
- GCC_except_table327
- GCC_except_table3327
- GCC_except_table3331
- GCC_except_table335
- GCC_except_table3386
- GCC_except_table3398
- GCC_except_table3402
- GCC_except_table3409
- GCC_except_table3418
- GCC_except_table3441
- GCC_except_table3442
- GCC_except_table3443
- GCC_except_table3444
- GCC_except_table3469
- GCC_except_table3482
- GCC_except_table3641
- GCC_except_table3701
- GCC_except_table3715
- GCC_except_table3757
- GCC_except_table3758
- GCC_except_table3787
- GCC_except_table3788
- GCC_except_table3790
- GCC_except_table3793
- GCC_except_table3794
- GCC_except_table3795
- GCC_except_table3818
- GCC_except_table3820
- GCC_except_table3824
- GCC_except_table3825
- GCC_except_table3826
- GCC_except_table3829
- GCC_except_table3880
- GCC_except_table389
- GCC_except_table3901
- GCC_except_table3922
- GCC_except_table3923
- GCC_except_table3924
- GCC_except_table393
- GCC_except_table3934
- GCC_except_table395
- GCC_except_table396
- GCC_except_table397
- GCC_except_table4025
- GCC_except_table4026
- GCC_except_table4035
- GCC_except_table4037
- GCC_except_table4038
- GCC_except_table4039
- GCC_except_table4040
- GCC_except_table4043
- GCC_except_table4044
- GCC_except_table4047
- GCC_except_table4048
- GCC_except_table4049
- GCC_except_table4050
- GCC_except_table4051
- GCC_except_table4052
- GCC_except_table4053
- GCC_except_table4054
- GCC_except_table4055
- GCC_except_table4058
- GCC_except_table4059
- GCC_except_table4065
- GCC_except_table4066
- GCC_except_table4068
- GCC_except_table4070
- GCC_except_table4071
- GCC_except_table4073
- GCC_except_table4074
- GCC_except_table4077
- GCC_except_table4078
- GCC_except_table4081
- GCC_except_table4082
- GCC_except_table4083
- GCC_except_table4085
- GCC_except_table4086
- GCC_except_table4087
- GCC_except_table4089
- GCC_except_table4090
- GCC_except_table4094
- GCC_except_table4095
- GCC_except_table4123
- GCC_except_table4173
- GCC_except_table4177
- GCC_except_table4228
- GCC_except_table4229
- GCC_except_table4236
- GCC_except_table4237
- GCC_except_table4238
- GCC_except_table4239
- GCC_except_table4241
- GCC_except_table4242
- GCC_except_table4263
- GCC_except_table4265
- GCC_except_table4266
- GCC_except_table4267
- GCC_except_table4269
- GCC_except_table4270
- GCC_except_table4271
- GCC_except_table4272
- GCC_except_table4273
- GCC_except_table4274
- GCC_except_table4275
- GCC_except_table4276
- GCC_except_table4288
- GCC_except_table4297
- GCC_except_table4299
- GCC_except_table4300
- GCC_except_table4301
- GCC_except_table4302
- GCC_except_table4307
- GCC_except_table4310
- GCC_except_table4311
- GCC_except_table4312
- GCC_except_table4313
- GCC_except_table4314
- GCC_except_table4316
- GCC_except_table4318
- GCC_except_table4319
- GCC_except_table4321
- GCC_except_table4323
- GCC_except_table4325
- GCC_except_table4327
- GCC_except_table4347
- GCC_except_table4348
- GCC_except_table4350
- GCC_except_table4351
- GCC_except_table4353
- GCC_except_table4356
- GCC_except_table4357
- GCC_except_table4362
- GCC_except_table4399
- GCC_except_table4511
- GCC_except_table4518
- GCC_except_table4601
- GCC_except_table4678
- GCC_except_table4734
- GCC_except_table4736
- GCC_except_table4738
- GCC_except_table4739
- GCC_except_table4740
- GCC_except_table4741
- GCC_except_table4742
- GCC_except_table4743
- GCC_except_table4746
- GCC_except_table4748
- GCC_except_table4750
- GCC_except_table4751
- GCC_except_table4789
- GCC_except_table4855
- GCC_except_table4860
- GCC_except_table4901
- GCC_except_table4967
- GCC_except_table502
- GCC_except_table503
- GCC_except_table536
- GCC_except_table573
- GCC_except_table576
- GCC_except_table599
- GCC_except_table667
- GCC_except_table671
- GCC_except_table678
- GCC_except_table841
- GCC_except_table848
- GCC_except_table911
- GCC_except_table912
- GCC_except_table919
- GCC_except_table934
- GCC_except_table935
- GCC_except_table936
- GCC_except_table942
- GCC_except_table943
- GCC_except_table944
- GCC_except_table955
- GCC_except_table971
- __OBJC_$_CLASS_METHODS_CSFModelConfigDecoder
- ___76+[CSUtils(Directory) clearLogFilesInDirectory:matchingPattern:exceedNumber:]_block_invoke
- _isAudioStreamProvidingEnabled.result
CStrings:
+ "%ld.%09ld:%lld"
+ "%s #output_stream Failed to connect source node to main mixer: %@"
+ "%s Acquiring listening mic indicator lock from : %{public}@ %@"
+ "%s Acquiring power meter lock from : %{public}@ %@"
+ "%s Acquiring recordModeLock from : %{public}@"
+ "%s Audio consuming session active for %.1fs with no stop notification; resetting stale state"
+ "%s CSAudioProvider[%{public}@]:%{public}@ ask for audio hold stream from %{public}@ for %{public}.2f secs, requestExclaveAudio = %{public}s"
+ "%s CSAudioProvider[%{public}@]:Remaining audio stream holder requesting audio exfiltration: %{public}lu stream holders"
+ "%s Cached decoded model config %{public}@ (%{public}lu top-level keys, %{public}lu cached)"
+ "%s Clearing listening mic indicator lock property, locks = %tu"
+ "%s Could not read directory %{public}@: %{public}@"
+ "%s ERR: could not decode model config %{public}@: %{public}@"
+ "%s ERR: could not read model config %{public}@"
+ "%s ERR: model config %{public}@ is %{public}@, expected a dictionary"
+ "%s Force releasing all %tu listening mic indicator locks"
+ "%s Force releasing all %tu power meter locks"
+ "%s Purged %{public}lu cached model config(s)"
+ "%s RecordSettings received from AVVC: %@"
+ "%s Releasing listening mic indicator lock from : %{public}@"
+ "%s Releasing listening mic indicator lock from : %{public}@ UUID = %@"
+ "%s Releasing listening mic indicator lock from = %{public}@"
+ "%s Releasing power meter lock from : %{public}@"
+ "%s Releasing recordModeLock from : %{public}@"
+ "%s Releasing recordModeLock from : %{public}@ UUID = %@"
+ "%s Setting listening mic indicator lock property, locks = %tu"
+ "%s Spectral meter normalization enabled (CarPlay path)"
+ "%s Updating audio device info : recordRoute[%{public}@] deviceId[%{public}@] isRemoteDevice[%d]"
+ "+[CSFModelConfigDecoder purgeCachedConfigs]"
+ "+[CSUtils(Directory) _clearLogFilesInDirectory:matchingPatterns:exceedNumber:outError:]"
+ "-[CSAudioConsumingStateMonitor isAudioConsumingSessionActive]"
+ "-[CSAudioProvider _acquirePowerMeterLockFrom:option:needsBoost12dB:]"
+ "-[CSAudioProvider _forceReleaseAllListeningMicIndicatorLocks]"
+ "-[CSAudioProvider _forceReleaseAllPowerMeterLocks]"
+ "-[CSAudioProvider _forceReleasePowerMeterLockFrom:]"
+ "-[CSAudioRecorder recordSettingsWithStreamHandleId:]"
+ "IntutiveConvAudioCapture"
+ "IntutiveConvAudioCaptureHolding"
+ "LOCALE_ACW_SA"
+ "LOCALE_AFB_AE"
+ "LOCALE_AJP_JO"
+ "LOCALE_AJP_PS"
+ "LOCALE_APC_LB"
+ "LOCALE_APC_SY"
+ "LOCALE_ARS_SA"
+ "LOCALE_ARZ_EG"
+ "LOCALE_AZ_AZ"
+ "LOCALE_BE_BY"
+ "LOCALE_BG_BG"
+ "LOCALE_BN_IN"
+ "LOCALE_ET_EE"
+ "LOCALE_GU_IN"
+ "LOCALE_HI_LATN"
+ "LOCALE_IS_IS"
+ "LOCALE_KN_IN"
+ "LOCALE_ML_IN"
+ "LOCALE_MR_IN"
+ "LOCALE_PA_IN"
+ "LOCALE_SL_SI"
+ "LOCALE_SR_RS"
+ "LOCALE_TA_IN"
+ "LOCALE_TE_IN"
+ "LOCALE_UR_IN"
+ "LOCALE_UZ_UZ"
+ "LocalAttendingInitiator"
+ "LocalAttendingInitiatorHolding"
+ "NotHeld"
+ "OpportuneSpeakListener"
+ "OpportuneSpeakListenerHolding"
+ "SiriHolding"
+ "SiriRecordStartAlert"
+ "VoiceTriggerTraining"
+ "audioConsumingSessionStale"
+ "startAlertBehavior=%ld"
+ "\xf0\"1"
- "%s Acquiring listening mic indicator lock from : %d %@"
- "%s Acquiring recordModeLock from : %d"
- "%s CSAudioProvider[%{public}@]:%{public}@ ask for audio hold stream for %{public}f"
- "%s Clearing listening mic indicator lock property"
- "%s ERR: metaData is nil, defaulting to NO for %{public}@"
- "%s ERR: read metafile %{public}@ failed with %{public}@ - defaulting to NO"
- "%s Releasing listening mic indicator lock UUID = %@"
- "%s Releasing listening mic indicator lock from : %d"
- "%s Releasing listening mic indicator lock from = %d"
- "%s Releasing recordModeLock from : %d"
- "%s Releasing recordModeLock lock UUID = %@"
- "%s Setting listening mic indicator lock property"
- "Conclaves"
- "com_apple_audiomxd_conclave"
- "support_audio_streaming"
```
