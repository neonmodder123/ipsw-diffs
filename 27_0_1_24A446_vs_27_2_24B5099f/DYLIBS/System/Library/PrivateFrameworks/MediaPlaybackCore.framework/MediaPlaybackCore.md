## MediaPlaybackCore

> `/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/MediaPlaybackCore`

```diff

-26110.26.31.301.0
-  __TEXT.__text: 0x4a197c
-  __TEXT.__objc_methlist: 0x17e10
+26200.26.39.301.0
+  __TEXT.__text: 0x4ac608
+  __TEXT.__objc_methlist: 0x17f58
   __TEXT.__dlopen_cstrs: 0x114
-  __TEXT.__const: 0x10870
-  __TEXT.__oslogstring: 0x4c598
-  __TEXT.__cstring: 0x25ad1
-  __TEXT.__swift5_typeref: 0x547a
-  __TEXT.__swift5_capture: 0xaee4
-  __TEXT.__constg_swiftt: 0x7b40
-  __TEXT.__swift5_reflstr: 0x5a02
-  __TEXT.__swift5_fieldmd: 0x569c
+  __TEXT.__const: 0x10a80
+  __TEXT.__oslogstring: 0x4d037
+  __TEXT.__cstring: 0x26068
+  __TEXT.__swift5_typeref: 0x54c2
+  __TEXT.__swift5_capture: 0xb1bc
+  __TEXT.__constg_swiftt: 0x7bd4
+  __TEXT.__swift5_reflstr: 0x5af2
+  __TEXT.__swift5_fieldmd: 0x5718
   __TEXT.__swift5_builtin: 0x6f4
-  __TEXT.__swift5_mpenum: 0xf0
+  __TEXT.__swift5_mpenum: 0x130
   __TEXT.__swift5_assocty: 0xbc0
-  __TEXT.__swift5_proto: 0x92c
-  __TEXT.__swift5_types: 0x564
-  __TEXT.__swift_as_entry: 0x4a4
-  __TEXT.__swift_as_ret: 0x5bc
-  __TEXT.__swift_as_cont: 0xe14
+  __TEXT.__swift5_proto: 0x934
+  __TEXT.__swift5_types: 0x568
+  __TEXT.__swift_as_entry: 0x4b0
+  __TEXT.__swift_as_ret: 0x5d8
+  __TEXT.__swift_as_cont: 0xe44
   __TEXT.__swift5_protos: 0xd8
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x5988
+  __TEXT.__gcc_except_tab: 0x5a6c
   __TEXT.__ustring: 0x4dc
-  __TEXT.__unwind_info: 0xdd78
-  __TEXT.__eh_frame: 0x10284
+  __TEXT.__unwind_info: 0xda60
+  __TEXT.__eh_frame: 0x10438
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9380
+  __DATA_CONST.__const: 0x9498
   __DATA_CONST.__objc_classlist: 0xd30
   __DATA_CONST.__objc_catlist: 0x298
   __DATA_CONST.__objc_protolist: 0x7f0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xcb40
+  __DATA_CONST.__objc_selrefs: 0xcc08
   __DATA_CONST.__objc_protorefs: 0x3a0
-  __DATA_CONST.__objc_superrefs: 0x6d0
+  __DATA_CONST.__objc_superrefs: 0x6d8
   __DATA_CONST.__objc_arraydata: 0x290
-  __DATA_CONST.__got: 0x3458
-  __AUTH_CONST.__const: 0x23858
-  __AUTH_CONST.__cfstring: 0x1ea00
-  __AUTH_CONST.__objc_const: 0x34770
-  __AUTH_CONST.__objc_intobj: 0x888
-  __AUTH_CONST.__objc_arrayobj: 0x288
+  __DATA_CONST.__got: 0x3460
+  __AUTH_CONST.__const: 0x24018
+  __AUTH_CONST.__cfstring: 0x1ee00
+  __AUTH_CONST.__objc_const: 0x349c0
+  __AUTH_CONST.__objc_intobj: 0x8a0
+  __AUTH_CONST.__objc_arrayobj: 0x270
   __AUTH_CONST.__objc_dictobj: 0xc8
-  __AUTH_CONST.__objc_doubleobj: 0x70
-  __AUTH_CONST.__auth_got: 0x3448
+  __AUTH_CONST.__objc_doubleobj: 0x60
+  __AUTH_CONST.__auth_got: 0x3458
   __AUTH.__objc_data: 0x5a40
-  __AUTH.__data: 0x40b0
-  __DATA.__objc_ivar: 0x1ac4
-  __DATA.__data: 0x72b0
-  __DATA.__bss: 0xf438
+  __AUTH.__data: 0x40f0
+  __DATA.__objc_ivar: 0x1adc
+  __DATA.__data: 0x7330
+  __DATA.__bss: 0xf538
   __DATA.__common: 0x240
   __DATA_DIRTY.__objc_data: 0x3590
-  __DATA_DIRTY.__data: 0x4548
+  __DATA_DIRTY.__data: 0x45d8
   __DATA_DIRTY.__bss: 0x1328
   __DATA_DIRTY.__common: 0xc8
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 24465
-  Symbols:   18657
-  CStrings:  8247
+  Functions: 24708
+  Symbols:   18709
+  CStrings:  8298
 
Symbols:
+ +[_MPCVideoViewControllerMediaFoundationImplementation keyPathsForValuesAffectingCustomControlItems]
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:completionHandler:]
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:error:]
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSMetadataItemInMetadata:]
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSSessionMetadataItemWithTimeout:completionHandler:]
+ -[MPCAudioAssetTypeSelector descriptionForExpectedAlbumAvailableDateTime:]
+ -[MPCAudioAssetTypeSelector preferredAudioAssetTypeForSongWithTrait:isStartItem:applyJitterTreatment:expectedAlbumAvailableDateTime:]
+ -[MPCAudioAssetTypeSelector stereoAssetTypeWithIsStartItem:applyJitterTreatment:explanation:]
+ -[MPCFuture _removeInvalidHandler:]
+ -[MPCFuture invalidHandlers]
+ -[MPCFutureInvalidationToken dealloc]
+ -[MPCFutureInvalidationToken handler]
+ -[MPCFutureInvalidationToken setHandler:]
+ -[MPCModelGenericAVItem _albumForPreReleaseTreatment]
+ -[MPCModelGenericAVItem _hasPendingDeferredLeaseAcquisition]
+ -[MPCModelGenericAVItem _setHasPendingDeferredLeaseAcquisition:]
+ -[MPCModelGenericAVItem expectedAlbumAvailableDateTime]
+ -[MPCModelGenericAVItem leaseAcquisitionJitterTime]
+ -[MPCModelGenericAVItem shouldApplyJitterTreatment]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) _sharedKeySegmentDurationFromHLSSessionDataOfAsset:completionHandler:]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) keyDeliveryJitterTimeWithCompletionHandler:]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) sharedKeySegmentDurationWithCompletionHandler:]
+ -[MPCModelStorePlaybackItemsRequest setVersionHashesByStoreID:]
+ -[MPCModelStorePlaybackItemsRequest versionHashesByStoreID]
+ -[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]
+ -[MPCPlaybackErrorController playbackDidSucceedForItem:]
+ -[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSAudioAssetMetadataDictionary:]
+ -[_MPCControllerPropertyProxy .cxx_destruct]
+ -[_MPCControllerPropertyProxy customControlItems]
+ -[_MPCControllerPropertyProxy setCustomControlItems:]
+ -[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:account:]
+ -[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:account:]
+ -[_MPCPlaybackEnginePlayer _logTimeJumpForItem:fromTime:fromPrimaryTime:toTime:toPrimaryTime:userInitiated:timeStamp:]
+ -[_MPCPlaybackEnginePlayer _playbackDidStopForItem:source:reason:time:primaryTime:timeStamp:]
+ -[_MPCPlaybackEnginePlayer userSeekCompletedForItem:fromTime:fromPrimaryTime:toTime:toPrimaryTime:timeStamp:]
+ -[_MPCVideoViewControllerMediaFoundationImplementation customControlItems]
+ -[_MPCVideoViewControllerMediaFoundationImplementation setCustomControlItems:]
+ GCC_except_table1001
+ GCC_except_table1004
+ GCC_except_table1195
+ GCC_except_table1197
+ GCC_except_table1365
+ GCC_except_table1367
+ GCC_except_table1414
+ GCC_except_table1425
+ GCC_except_table1432
+ GCC_except_table1439
+ GCC_except_table1476
+ GCC_except_table1488
+ GCC_except_table1497
+ GCC_except_table1540
+ GCC_except_table1713
+ GCC_except_table1715
+ GCC_except_table1728
+ GCC_except_table1733
+ GCC_except_table1803
+ GCC_except_table1889
+ GCC_except_table1890
+ GCC_except_table2001
+ GCC_except_table2021
+ GCC_except_table2023
+ GCC_except_table2051
+ GCC_except_table2060
+ GCC_except_table2065
+ GCC_except_table2067
+ GCC_except_table2070
+ GCC_except_table2081
+ GCC_except_table2091
+ GCC_except_table2206
+ GCC_except_table2261
+ GCC_except_table2264
+ GCC_except_table2290
+ GCC_except_table2314
+ GCC_except_table2346
+ GCC_except_table2426
+ GCC_except_table2613
+ GCC_except_table2641
+ GCC_except_table2668
+ GCC_except_table2813
+ GCC_except_table2834
+ GCC_except_table2841
+ GCC_except_table2842
+ GCC_except_table2867
+ GCC_except_table2869
+ GCC_except_table2880
+ GCC_except_table2882
+ GCC_except_table2884
+ GCC_except_table2887
+ GCC_except_table2913
+ GCC_except_table2922
+ GCC_except_table2927
+ GCC_except_table2929
+ GCC_except_table2933
+ GCC_except_table2938
+ GCC_except_table2944
+ GCC_except_table2947
+ GCC_except_table2950
+ GCC_except_table2978
+ GCC_except_table3021
+ GCC_except_table3107
+ GCC_except_table3111
+ GCC_except_table3122
+ GCC_except_table3123
+ GCC_except_table3155
+ GCC_except_table3196
+ GCC_except_table3197
+ GCC_except_table3213
+ GCC_except_table3270
+ GCC_except_table3288
+ GCC_except_table3297
+ GCC_except_table3339
+ GCC_except_table3341
+ GCC_except_table3348
+ GCC_except_table3359
+ GCC_except_table3363
+ GCC_except_table3407
+ GCC_except_table3452
+ GCC_except_table3457
+ GCC_except_table354
+ GCC_except_table356
+ GCC_except_table3589
+ GCC_except_table3610
+ GCC_except_table3617
+ GCC_except_table3642
+ GCC_except_table3646
+ GCC_except_table3656
+ GCC_except_table3713
+ GCC_except_table3718
+ GCC_except_table3722
+ GCC_except_table3792
+ GCC_except_table3889
+ GCC_except_table3893
+ GCC_except_table3904
+ GCC_except_table3920
+ GCC_except_table3926
+ GCC_except_table3935
+ GCC_except_table402
+ GCC_except_table4063
+ GCC_except_table410
+ GCC_except_table4108
+ GCC_except_table4110
+ GCC_except_table4129
+ GCC_except_table4138
+ GCC_except_table4156
+ GCC_except_table4161
+ GCC_except_table4163
+ GCC_except_table4177
+ GCC_except_table418
+ GCC_except_table4200
+ GCC_except_table4211
+ GCC_except_table427
+ GCC_except_table4300
+ GCC_except_table4319
+ GCC_except_table4332
+ GCC_except_table4343
+ GCC_except_table4374
+ GCC_except_table4545
+ GCC_except_table4546
+ GCC_except_table4724
+ GCC_except_table4759
+ GCC_except_table4761
+ GCC_except_table4769
+ GCC_except_table4777
+ GCC_except_table4792
+ GCC_except_table4800
+ GCC_except_table4808
+ GCC_except_table4818
+ GCC_except_table4833
+ GCC_except_table4877
+ GCC_except_table4907
+ GCC_except_table4910
+ GCC_except_table4916
+ GCC_except_table4968
+ GCC_except_table5006
+ GCC_except_table5094
+ GCC_except_table511
+ GCC_except_table5195
+ GCC_except_table527
+ GCC_except_table528
+ GCC_except_table5438
+ GCC_except_table5439
+ GCC_except_table544
+ GCC_except_table545
+ GCC_except_table5515
+ GCC_except_table5607
+ GCC_except_table5759
+ GCC_except_table5784
+ GCC_except_table5901
+ GCC_except_table5982
+ GCC_except_table5990
+ GCC_except_table5991
+ GCC_except_table6055
+ GCC_except_table6080
+ GCC_except_table6115
+ GCC_except_table6118
+ GCC_except_table6121
+ GCC_except_table6207
+ GCC_except_table6424
+ GCC_except_table6441
+ GCC_except_table6489
+ GCC_except_table6502
+ GCC_except_table7018
+ GCC_except_table7352
+ GCC_except_table7367
+ GCC_except_table7461
+ GCC_except_table7470
+ GCC_except_table7559
+ GCC_except_table7566
+ GCC_except_table7584
+ GCC_except_table7635
+ GCC_except_table7636
+ GCC_except_table7639
+ GCC_except_table7644
+ GCC_except_table7660
+ GCC_except_table796
+ GCC_except_table852
+ GCC_except_table928
+ GCC_except_table959
+ GCC_except_table962
+ GCC_except_table964
+ GCC_except_table969
+ GCC_except_table971
+ GCC_except_table988
+ GCC_except_table998
+ _MPCHLSAudioAssetMetadataDictionaryKey
+ _MPCPlaybackEngineEventPayloadKeyInterstitialPrimaryPosition
+ _MPCPlaybackEngineEventPayloadKeyItemPrimaryEndPosition
+ _MPCPlaybackEngineEventPayloadKeyItemPrimaryStartPosition
+ _MPCPlaybackEngineEventPayloadKeyVideoRenderingModeDidChangePosition
+ _MPCPlaybackEngineEventPayloadKeyVideoRenderingModeDidChangePrimaryPosition
+ _MPHomeMonitorCurrentHomeDidChangeNotification
+ _MPHomeMonitorHomeUsersDidChangeNotification
+ _MPModelPropertyAlbumExpectedReleaseDateComponents
+ _OBJC_CLASS_$_NSPointerArray
+ _OBJC_IVAR_$_MPCFuture._invalidHandlers
+ _OBJC_IVAR_$_MPCFutureInvalidationToken._handler
+ _OBJC_IVAR_$_MPCModelStorePlaybackItemsRequest._versionHashesByStoreID
+ _OBJC_IVAR_$_MPCPlaybackAccountManager._accountsUpdateQueue
+ _OBJC_IVAR_$__MPCControllerPropertyProxy._customControlItems
+ _OBJC_IVAR_$__MPCMediaRemotePublisher._hostingSharedSessionIDInitialized
+ _OBJC_IVAR_$__MPCModelStorePlaybackItemsRequestAccumulator_Legacy._hasHandledStoreResponse
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:account:]_block_invoke
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:account:]_block_invoke_2
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:account:]_block_invoke_3
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern _locked_progressiveSectionWithoutVersionHash:]_block_invoke
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:account:]_block_invoke
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:account:]_block_invoke_2
+ ___101-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:account:]_block_invoke_3
+ ___115-[MPCModelGenericAVItem(KeyDeliveryDeferral) _sharedKeySegmentDurationFromHLSSessionDataOfAsset:completionHandler:]_block_invoke
+ ___119-[MPCAssistantRemoteControlDestination resolveWithRouteIdentifiers:allowedPlaybackTargets:audioRoutingInfo:completion:]_block_invoke_2
+ ___140-[MPCModelGenericAVItem(KeyDeliveryDeferral) shouldPerformKeyDeliveryRequestForKey:isPrefetchKey:isPersistable:isRenewal:completionHandler:]_block_invoke_4
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke_2
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke_3
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke_4
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke_5
+ ___175-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:serverObjectDatabase:libraryObjectDatabase:performanceMetrics:]_block_invoke_6
+ ___35-[MPCFuture _removeInvalidHandler:]_block_invoke
+ ___36+[MPCPlaybackEngine preheatPlayback]_block_invoke_2
+ ___57-[MPCPlaybackAccountManager performAfterLoadingAccounts:]_block_invoke
+ ___58-[MPCModelGenericAVItem prepareForRate:completionHandler:]_block_invoke_4
+ ___58-[MPCModelGenericAVItem prepareForRate:completionHandler:]_block_invoke_5
+ ___86-[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:error:]_block_invoke
+ ___88-[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSAudioAssetMetadataDictionary:]_block_invoke
+ ___89-[AVURLAsset(MPCHLSSessionData) mpc_HLSSessionMetadataItemWithTimeout:completionHandler:]_block_invoke
+ ___89-[MPCModelGenericAVItem(KeyDeliveryDeferral) keyDeliveryJitterTimeWithCompletionHandler:]_block_invoke
+ ___98-[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:completionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e36_v24?0"AVMetadataItem"8"NSError"16ls40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e8_v16?0d8ls40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e8_v16?0q8ls32l8s40l8
+ ___block_descriptor_48_e8_32s40bs_e9_v16?0^v8ls32l8s40l8
+ ___block_descriptor_49_e8_32s40s_e18_16?0"NSString"8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40r48r_e34_v24?0"NSDictionary"8"NSError"16lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32s40s48bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls48l8s32l8s40l8
+ ___block_descriptor_61_e8_32s40s48s_e49_v16?0"MPIdentifierSet<MPMutableIdentifierSet>"8ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48r56r_e5_v8?0ls32l8s40l8r48l8r56l8
+ ___swift_closure_destructor.70Tm
+ _arc4random
+ _associated conformance 17MediaPlaybackCore23AudioSignatureProcessorV10SliceRange33_70D6E225C33896E6E4196C32A146759DLLVSHAASQ
+ _symbolic Sb7success_______pSg4itemSdSg9startTimeAE012primaryStartD0Sd03endD0AE0e3EndD0SS10identifierSb7passive_____9timeStampt 17MediaPlaybackCore10PlayerItemP AA9EventTimeC
+ _symbolic _____ 17MediaPlaybackCore23AudioSignatureProcessorV10SliceRange33_70D6E225C33896E6E4196C32A146759DLLV
+ _symbolic _____Iegr_ 17MediaPlaybackCore12PlayingStateC
+ _symbolic _____ySDy_____So11SHSignatureCGG 2os21OSAllocatedUnfairLockV 17MediaPlaybackCore23AudioSignatureProcessorV10SliceRange33_70D6E225C33896E6E4196C32A146759DLLV
+ _type_layout_string SNySdG
- -[AVURLAsset(MPCHLSSessionData) mpc_HLSAVMetadataItemInMetadata:]
- -[AVURLAsset(MPCHLSSessionData) mpc_synchronousHLSSessionDataWithTimeout:error:]
- -[MPCAudioAssetTypeSelector preferredAudioAssetTypeForSongWithTrait:isStartItem:]
- -[MPCAudioAssetTypeSelector stereoAssetTypeWithIsStartItem:explanation:]
- -[MPCFuture invalidBlocks]
- -[MPCModelGenericAVItem(KeyDeliveryDeferral) keyDeliveryJitterTime]
- -[MPCModelGenericAVItem(KeyDeliveryDeferral) sharedKeySegmentDuration]
- -[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]
- -[MPCPlayerItemConfigurator _HLSMetadataForAsset:error:]
- -[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSMetadata:]
- -[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:]
- -[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:]
- -[_MPCPlaybackEnginePlayer _logTimeJumpForItem:fromTime:toTime:userInitiated:timeStamp:]
- -[_MPCPlaybackEnginePlayer _playbackDidStopForItem:source:reason:time:timeStamp:]
- -[_MPCPlaybackEnginePlayer userSeekCompletedForItem:fromTime:toTime:timeStamp:]
- GCC_except_table1000
- GCC_except_table1187
- GCC_except_table1193
- GCC_except_table1361
- GCC_except_table1363
- GCC_except_table1410
- GCC_except_table1421
- GCC_except_table1428
- GCC_except_table1435
- GCC_except_table1472
- GCC_except_table1484
- GCC_except_table1493
- GCC_except_table1536
- GCC_except_table1709
- GCC_except_table1711
- GCC_except_table1724
- GCC_except_table1729
- GCC_except_table1799
- GCC_except_table1885
- GCC_except_table1886
- GCC_except_table1997
- GCC_except_table2017
- GCC_except_table2019
- GCC_except_table2047
- GCC_except_table2056
- GCC_except_table2061
- GCC_except_table2063
- GCC_except_table2066
- GCC_except_table2077
- GCC_except_table2087
- GCC_except_table2202
- GCC_except_table2253
- GCC_except_table2260
- GCC_except_table2286
- GCC_except_table2310
- GCC_except_table2342
- GCC_except_table2422
- GCC_except_table2609
- GCC_except_table2637
- GCC_except_table2664
- GCC_except_table2807
- GCC_except_table2828
- GCC_except_table2835
- GCC_except_table2836
- GCC_except_table2861
- GCC_except_table2863
- GCC_except_table2868
- GCC_except_table2872
- GCC_except_table2876
- GCC_except_table2881
- GCC_except_table2907
- GCC_except_table2914
- GCC_except_table2919
- GCC_except_table2921
- GCC_except_table2925
- GCC_except_table2930
- GCC_except_table2931
- GCC_except_table2936
- GCC_except_table2942
- GCC_except_table2962
- GCC_except_table3013
- GCC_except_table3099
- GCC_except_table3103
- GCC_except_table3114
- GCC_except_table3115
- GCC_except_table3139
- GCC_except_table3188
- GCC_except_table3189
- GCC_except_table3205
- GCC_except_table3262
- GCC_except_table3280
- GCC_except_table3287
- GCC_except_table3329
- GCC_except_table3331
- GCC_except_table3338
- GCC_except_table3349
- GCC_except_table3353
- GCC_except_table3391
- GCC_except_table3436
- GCC_except_table3441
- GCC_except_table351
- GCC_except_table353
- GCC_except_table3569
- GCC_except_table3590
- GCC_except_table3597
- GCC_except_table3622
- GCC_except_table3626
- GCC_except_table3636
- GCC_except_table3693
- GCC_except_table3698
- GCC_except_table3702
- GCC_except_table3772
- GCC_except_table3869
- GCC_except_table3873
- GCC_except_table3884
- GCC_except_table3900
- GCC_except_table3906
- GCC_except_table3915
- GCC_except_table399
- GCC_except_table4043
- GCC_except_table407
- GCC_except_table4087
- GCC_except_table4088
- GCC_except_table4089
- GCC_except_table4118
- GCC_except_table4136
- GCC_except_table4141
- GCC_except_table4143
- GCC_except_table415
- GCC_except_table4157
- GCC_except_table4180
- GCC_except_table4191
- GCC_except_table424
- GCC_except_table4280
- GCC_except_table4299
- GCC_except_table4312
- GCC_except_table4323
- GCC_except_table4354
- GCC_except_table4525
- GCC_except_table4526
- GCC_except_table4704
- GCC_except_table4739
- GCC_except_table4741
- GCC_except_table4749
- GCC_except_table4757
- GCC_except_table4772
- GCC_except_table4780
- GCC_except_table4788
- GCC_except_table4798
- GCC_except_table4813
- GCC_except_table4857
- GCC_except_table4872
- GCC_except_table4888
- GCC_except_table4897
- GCC_except_table4949
- GCC_except_table4987
- GCC_except_table507
- GCC_except_table5074
- GCC_except_table5175
- GCC_except_table523
- GCC_except_table524
- GCC_except_table540
- GCC_except_table541
- GCC_except_table5413
- GCC_except_table5414
- GCC_except_table5489
- GCC_except_table5580
- GCC_except_table5732
- GCC_except_table5757
- GCC_except_table5874
- GCC_except_table5955
- GCC_except_table5963
- GCC_except_table5964
- GCC_except_table6028
- GCC_except_table6053
- GCC_except_table6088
- GCC_except_table6091
- GCC_except_table6094
- GCC_except_table6180
- GCC_except_table6397
- GCC_except_table6414
- GCC_except_table6462
- GCC_except_table6475
- GCC_except_table6991
- GCC_except_table7325
- GCC_except_table7335
- GCC_except_table7428
- GCC_except_table7437
- GCC_except_table7521
- GCC_except_table7528
- GCC_except_table7546
- GCC_except_table7597
- GCC_except_table7598
- GCC_except_table7601
- GCC_except_table7606
- GCC_except_table7622
- GCC_except_table792
- GCC_except_table848
- GCC_except_table924
- GCC_except_table955
- GCC_except_table958
- GCC_except_table960
- GCC_except_table965
- GCC_except_table967
- GCC_except_table980
- GCC_except_table990
- GCC_except_table997
- _OBJC_IVAR_$_MPCFuture._invalidBlocks
- _OUTLINED_FUNCTION_620
- ___114-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy _locked_resolveContentDescriptorsUsingServerObjectDatabase]_block_invoke_3
- ___114-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy _locked_resolveContentDescriptorsUsingServerObjectDatabase]_block_invoke_4
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke_2
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke_3
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke_4
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke_5
- ___154-[MPCModelStorePlaybackItemsRequestAccumulation initWithProgressiveResults:properties:personalizationProperties:libraryObjectDatabase:performanceMetrics:]_block_invoke_6
- ___68-[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSMetadata:]_block_invoke
- ___80-[AVURLAsset(MPCHLSSessionData) mpc_synchronousHLSSessionDataWithTimeout:error:]_block_invoke
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:]_block_invoke
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:]_block_invoke_2
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Legacy initWithRequest:serverObjectDatabase:]_block_invoke_3
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:]_block_invoke
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:]_block_invoke_2
- ___93-[_MPCModelStorePlaybackItemsRequestAccumulator_Modern initWithRequest:serverObjectDatabase:]_block_invoke_3
- ___block_descriptor_41_e8_32s_e18_16?0"NSString"8ls32l8
- ___block_descriptor_53_e8_32s40s_e49_v16?0"MPIdentifierSet<MPMutableIdentifierSet>"8ls32l8s40l8
- ___block_descriptor_56_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
- ___block_descriptor_64_e8_32s40s48r56r_e5_v8?0lr48l8s32l8r56l8s40l8
- ___swift_memcpy72_8
- ___swift_memcpy73_8
- _kMXSessionProperty_HostProcessAttribution
- _kMXSession_HostProcessAttributionKey_AuditToken
- _kMXSession_HostProcessAttributionKey_BundleID
- _objc_release_x10
- _swift_retain_x11
- _symbolic Sb7success_______pSg4itemSdSg9startTimeSd03endD0SS10identifierSb7passive_____9timeStampt 17MediaPlaybackCore10PlayerItemP AA9EventTimeC
- _symbolic yt______pIgrzo_ s5ErrorP
CStrings:
+ " versionHashesByStoreID=%@"
+ "4.AlbumAvailability"
+ "AccumulationSectionPromotionUnsupported"
+ "Cannot promote items to sections for a request using sectionedModelObjects: %@"
+ "FIRST-SEGMENT-DURATION"
+ "Failed to decode HLS session data - Asset:%@"
+ "Failed to load HLS session metadata - Asset:%@"
+ "Forcing HLS to apply jitter treatment"
+ "Future has accumulated %lu invalidation handlers: %{public}@"
+ "HLSSessionDataDecodingFailed"
+ "HLSSessionDataFetchTimedOut"
+ "HLSSessionDataUnavailable"
+ "MPCModelGenericAVItem+KeyDeliveryDeferral.m"
+ "MPCModelStorePlaybackItemsRequestVersionHashesByStoreID"
+ "No HLS session data available - Asset:%@"
+ "Playback queue superseded before response; re-requesting"
+ "PreheatPlayback"
+ "SEED"
+ "SHARED-KEY-SEGMENT-COUNT"
+ "Timed out retrieving HLS session metadata - Asset:%@"
+ "Unable to load queue, all items blocked by content restrictions."
+ "Unexpected nil urlAsset"
+ "Update: %{public}@<%{public}@> Falling back to watch due to error=%@. Connect Device Dialog Imminent"
+ "XL-Accumulator-VersionHashLess"
+ "[%{public}@]-MPCPlayerItemConfigurator %p - [AP] - Deferring Alchemy configuration [start item, transitions disabled, audio accessory]: %{public}@"
+ "[%{public}@]-❗️MPCErrorControllerImplementation %p <%{public}@> - Ending playback [Item failed repeatedly]"
+ "[BMUS:%{public}@:%{public}@] _addPlaybackContext: | disabling auto play [%{public}@]"
+ "[Chapter/ContentItem] Unable to convert chapter %{private,mask.hash}s to content item without a duration."
+ "[Chapters/%{private,mask.hash}s] Normalizing %{private,mask.hash}ld chapters with duration %{private,mask.hash}s."
+ "[Chapters/%{private,mask.hash}s] Segments changed, re-normalizing chapters with duration %{private,mask.hash}f."
+ "[Chapters/%{private,mask.hash}s] Unable to get duration for episode with %{private,mask.hash}s."
+ "[Chapters/%{private,mask.hash}s] Unable to get duration for episode with error %s."
+ "[Chapters] Finished chapter durations for minimum threshold."
+ "[Chapters] Removing chapter %{private,mask.hash}s."
+ "[Chapters] Verifying chapter durations for minimum threshold %f."
+ "[PIA] %p container has no children with any versionHash [empty, not a versionHash mismatch] identifier=%{public}@ versionHash=%{public}@"
+ "[PIA] %p failing request [section promotion unsupported for sectionedModelObjects] indexPaths=%{public}@"
+ "[PIA] %p store resolved a different versionHash than requested [using store version] identifier=%{public}@ requestedVersionHash=%{public}@"
+ "[PL:%{public}s] STACK PROCESSING: setQueueWithInitialItem [new start item %{public}s] - isResend:%{bool,public}d - capturedIntent:%{bool,public}d - shouldPlay:%{bool,public}d"
+ "[PL:%{public}s] TRANSITION: Skipping transition setup - a seek/jump is in flight [caller: %{public}s] - will re-evaluate on seek completion"
+ "[SPIR:%{sonic:fourCC}u] execute | finished with placeholders [prioritized batch reported complete]"
+ "[SPIR:%{sonic:fourCC}u] execute | finished with placeholders [prioritized batch reported complete] unpersonalizedContentDescriptors=%{public}@"
+ "[SPIR:%{sonic:fourCC}u] execute | loadPage [firstPage]"
+ "[SPIR:%{sonic:fourCC}u] populateSection:sectionIndex: | populated section [store resolved a different versionHash than requested; using store version] progressiveSection=%{public}@ requestedVersionHash=%{public}@ relatedProgressiveResults.count=%ld"
+ "_controllerPropertyProxy.customControlItems"
+ "assetQueueDidChange(state:)"
+ "com.apple.mediaplaybackcore.accountmanager.update"
+ "data source unsupported"
+ "guest account unsupported"
+ "internalController.customControlItems"
+ "interstitial-primary-position"
+ "item-primary-end-position"
+ "item-primary-start-position"
+ "key-delivery-jitter-window"
+ "lease-acquisition"
+ "primaryStartTime"
+ "restoreCurrentTransitionIfNeeded()"
+ "sendOverlappedPlaybackDidEndForOngoingTransition()"
+ "setupNextPlayerItemTransition(_:caller:)"
+ "success item startTime primaryStartTime endTime primaryEndTime identifier passive timeStamp "
+ "v24@?0@\"AVMetadataItem\"8@\"NSError\"16"
+ "video-rendering-mode-did-change-position"
+ "video-rendering-mode-did-change-primary-position"
+ "|%{public}@ %{public}@ %2i %{public}@  │ primaryEnd: %0.2f"
+ "|%{public}@ %{public}@ %2i %{public}@  │ primaryStart: %0.2f"
+ "|%{public}@ %{public}@ %2i %{public}@  ╰ primaryPosition: %0.2f"
- "\nc"
- "MPC_LIVE_LINK_UNABLE_TO_SHAREPLAY_ALERT_ACTION"
- "MPC_LIVE_LINK_UNABLE_TO_SHAREPLAY_ALERT_TITLE"
- "UniversalQueue"
- "[%{public}@]-MPCErrorControllerImplementation %p <%{public}@> - Playback has succeeded for at least one item [Ignoring queue failure]"
- "[%{public}@]-MPCPlayerItemConfigurator %p - [AL] - Error decoding HLS metadata [Clearing audioFormatsDictionary] - Error:%{public}@"
- "[%{public}@]-❗️MPCErrorControllerImplementation %p <%{public}@> - Ending playback [Entire queue failure]"
- "[BMUS:%{public}@:%{public}@] _addPlaybackContext: | disabling auto play [data source unsupported]"
- "[Chapters/%{private,mask.hash}s] Segments changed, re-normalizing chapters with duration %f."
- "[PL:%{public}s] STACK PROCESSING: setQueueWithInitialItem [new start item %{public}s]"
- "[SPIR%{sonic:fourCC}u] execute | loadPage [firstPage]"
- "[SPIR:%{sonic:fourCC}u] execute | finished with placeholders [prioritized IDs loaded]"
- "[SPIR:%{sonic:fourCC}u] execute | finished with placeholders [prioritized IDs loaded] unpersonalizedContentDescriptors=%{public}@"
- "success item startTime endTime identifier passive timeStamp "
- "\xe1"
```
