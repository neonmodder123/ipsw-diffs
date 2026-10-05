## CoreSpeech

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/CoreSpeech`

```diff

-3600.70.47.11.1
-  __TEXT.__text: 0x14d1ec
+3605.31.3.0.0
+  __TEXT.__text: 0x14be74
   __TEXT.__lazy_helpers: 0x54
-  __TEXT.__objc_methlist: 0x1508c
+  __TEXT.__objc_methlist: 0x14fcc
   __TEXT.__const: 0x42c
   __TEXT.__dlopen_cstrs: 0x1e0
-  __TEXT.__gcc_except_tab: 0x3230
-  __TEXT.__cstring: 0x28ec2
-  __TEXT.__oslogstring: 0x20308
-  __TEXT.__unwind_info: 0x5010
+  __TEXT.__gcc_except_tab: 0x32e8
+  __TEXT.__cstring: 0x28ef4
+  __TEXT.__oslogstring: 0x2047d
+  __TEXT.__unwind_info: 0x4ff8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4258
-  __DATA_CONST.__objc_classlist: 0x868
+  __DATA_CONST.__const: 0x4300
+  __DATA_CONST.__objc_classlist: 0x860
   __DATA_CONST.__objc_catlist: 0x40
-  __DATA_CONST.__objc_protolist: 0x4e8
+  __DATA_CONST.__objc_protolist: 0x4e0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xaea8
-  __DATA_CONST.__objc_protorefs: 0xa0
-  __DATA_CONST.__objc_superrefs: 0x6a0
-  __DATA_CONST.__objc_arraydata: 0x3e8
-  __DATA_CONST.__got: 0x1b40
-  __AUTH_CONST.__const: 0x1f60
-  __AUTH_CONST.__cfstring: 0x96c0
-  __AUTH_CONST.__objc_const: 0x21458
+  __DATA_CONST.__objc_selrefs: 0xaee8
+  __DATA_CONST.__objc_protorefs: 0x98
+  __DATA_CONST.__objc_superrefs: 0x698
+  __DATA_CONST.__objc_arraydata: 0x3f0
+  __DATA_CONST.__got: 0x1b48
+  __AUTH_CONST.__const: 0x1e20
+  __AUTH_CONST.__cfstring: 0x9640
+  __AUTH_CONST.__objc_const: 0x214f8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__lazy_load_got: 0x8
   __AUTH_CONST.__objc_intobj: 0x9a8
   __AUTH_CONST.__objc_doubleobj: 0xb0
   __AUTH_CONST.__objc_dictobj: 0x3c0
   __AUTH_CONST.__objc_floatobj: 0x4f0
-  __AUTH_CONST.__objc_arrayobj: 0x108
-  __AUTH_CONST.__auth_got: 0xda8
-  __AUTH.__objc_data: 0x3ca0
-  __DATA.__objc_ivar: 0x1998
-  __DATA.__data: 0x3a74
+  __AUTH_CONST.__objc_arrayobj: 0x120
+  __AUTH_CONST.__auth_got: 0xda0
+  __AUTH.__objc_data: 0x3c50
+  __DATA.__objc_ivar: 0x19bc
+  __DATA.__data: 0x3a14
   __DATA.__bss: 0x660
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x1770
   __DATA_DIRTY.__data: 0xc0
-  __DATA_DIRTY.__bss: 0x158
+  __DATA_DIRTY.__bss: 0x150
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/Accelerate.framework/Accelerate

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 8197
-  Symbols:   14246
-  CStrings:  5613
+  Functions: 8182
+  Symbols:   14234
+  CStrings:  5612
 
Symbols:
+ -[CSAttSiriAudioSessionStateClient dispatchStateChangedFrom:to:hostTime:]
+ -[CSAttSiriAudioSessionStateClient setTtsEndHostTime:]
+ -[CSAttSiriAudioSessionStateClient ttsEndHostTime]
+ -[CSAttSiriMitigationAssetProvider getMitigationAssetWithCompletion:]
+ -[CSEndpointDelayReporter analytics]
+ -[CSEndpointDelayReporter selfLoggingStream]
+ -[CSEndpointDelayReporter setAnalytics:]
+ -[CSEndpointDelayReporter setSelfLoggingStream:]
+ -[CSSiriAudioActivationInfo myriadElectionIdentity]
+ -[CSSiriSpeechRecorder _playStopAlertWithError:]
+ -[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]
+ -[CSSiriSpeechRecorder electionLedger]
+ -[CSSiriSpeechRecorder setElectionLedger:]
+ -[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]
+ -[CSSpeechController _invalidateRecordSessionActivationState]
+ -[CSSpeechController _noteAudioSessionActivatedForRecord:]
+ -[CSSpeechController _notifyDelegateDidStartRecordingSuccessfully:error:]
+ -[CSSpeechController didActivateAudioSessionForRecord]
+ -[CSSpeechController prefetchedAudioDeviceInfo]
+ -[CSSpeechController setDidActivateAudioSessionForRecord:]
+ -[CSSpeechController setPrefetchedAudioDeviceInfo:]
+ -[CSVoiceIdXPCConnection delegate]
+ -[CSVoiceIdXPCConnection setDelegate:]
+ -[CSVoiceTriggerAPModeSuspendPolicyIOS _isHearstRouted]
+ -[CSVoiceTriggerAPModeSuspendPolicyIOS _isPhoneCallActive]
+ -[CSVoiceTriggerAssetHandlerMac _handleTriggerAssetRefresh]
+ -[CSVoiceTriggerAssetHandlerMac compileAndUpdateDeviceCachesWithAsset:assetType:endpointId:]
+ -[CSVoiceTriggerSecondPass requestExclaveAudio]
+ -[CSVoiceTriggerSecondPass setRequestExclaveAudio:]
+ -[CSXPCClient _sendMessageAndReplySync:reply:error:]
+ -[CSXPCClient activateAudioSessionWithReason:dynamicAttribute:bundleID:audioDeviceInfo:error:]
+ GCC_except_table1274
+ GCC_except_table1286
+ GCC_except_table1492
+ GCC_except_table1564
+ GCC_except_table1607
+ GCC_except_table1621
+ GCC_except_table1649
+ GCC_except_table1665
+ GCC_except_table1668
+ GCC_except_table1698
+ GCC_except_table178
+ GCC_except_table1798
+ GCC_except_table1800
+ GCC_except_table1806
+ GCC_except_table1866
+ GCC_except_table1892
+ GCC_except_table1898
+ GCC_except_table1979
+ GCC_except_table1999
+ GCC_except_table202
+ GCC_except_table2115
+ GCC_except_table2264
+ GCC_except_table2294
+ GCC_except_table2297
+ GCC_except_table2300
+ GCC_except_table2305
+ GCC_except_table2317
+ GCC_except_table2322
+ GCC_except_table2325
+ GCC_except_table2417
+ GCC_except_table2423
+ GCC_except_table246
+ GCC_except_table2463
+ GCC_except_table2470
+ GCC_except_table2488
+ GCC_except_table2521
+ GCC_except_table254
+ GCC_except_table2624
+ GCC_except_table267
+ GCC_except_table2683
+ GCC_except_table2695
+ GCC_except_table270
+ GCC_except_table2726
+ GCC_except_table2751
+ GCC_except_table2762
+ GCC_except_table2797
+ GCC_except_table2798
+ GCC_except_table2799
+ GCC_except_table2804
+ GCC_except_table2814
+ GCC_except_table2815
+ GCC_except_table2824
+ GCC_except_table2830
+ GCC_except_table2832
+ GCC_except_table2833
+ GCC_except_table2903
+ GCC_except_table3173
+ GCC_except_table3252
+ GCC_except_table3305
+ GCC_except_table3327
+ GCC_except_table3330
+ GCC_except_table3333
+ GCC_except_table3364
+ GCC_except_table3424
+ GCC_except_table3597
+ GCC_except_table3623
+ GCC_except_table3651
+ GCC_except_table3686
+ GCC_except_table3687
+ GCC_except_table3689
+ GCC_except_table3691
+ GCC_except_table3707
+ GCC_except_table3709
+ GCC_except_table3711
+ GCC_except_table3713
+ GCC_except_table3715
+ GCC_except_table3717
+ GCC_except_table3719
+ GCC_except_table3722
+ GCC_except_table3739
+ GCC_except_table3741
+ GCC_except_table3743
+ GCC_except_table3745
+ GCC_except_table3747
+ GCC_except_table3749
+ GCC_except_table3750
+ GCC_except_table3752
+ GCC_except_table3754
+ GCC_except_table3756
+ GCC_except_table376
+ GCC_except_table3760
+ GCC_except_table3762
+ GCC_except_table3765
+ GCC_except_table3768
+ GCC_except_table3769
+ GCC_except_table3782
+ GCC_except_table3784
+ GCC_except_table3926
+ GCC_except_table3950
+ GCC_except_table4016
+ GCC_except_table4032
+ GCC_except_table4053
+ GCC_except_table4145
+ GCC_except_table4397
+ GCC_except_table4468
+ GCC_except_table4469
+ GCC_except_table4473
+ GCC_except_table4476
+ GCC_except_table4480
+ GCC_except_table449
+ GCC_except_table4505
+ GCC_except_table4508
+ GCC_except_table4561
+ GCC_except_table4567
+ GCC_except_table4637
+ GCC_except_table4842
+ GCC_except_table4849
+ GCC_except_table4856
+ GCC_except_table4862
+ GCC_except_table4945
+ GCC_except_table5105
+ GCC_except_table5115
+ GCC_except_table5139
+ GCC_except_table5159
+ GCC_except_table5242
+ GCC_except_table5256
+ GCC_except_table5265
+ GCC_except_table5272
+ GCC_except_table5278
+ GCC_except_table5280
+ GCC_except_table5283
+ GCC_except_table5291
+ GCC_except_table5293
+ GCC_except_table5297
+ GCC_except_table5299
+ GCC_except_table5310
+ GCC_except_table5316
+ GCC_except_table5323
+ GCC_except_table5328
+ GCC_except_table5334
+ GCC_except_table5335
+ GCC_except_table5337
+ GCC_except_table5339
+ GCC_except_table5340
+ GCC_except_table5341
+ GCC_except_table5342
+ GCC_except_table5343
+ GCC_except_table5345
+ GCC_except_table5346
+ GCC_except_table5347
+ GCC_except_table5364
+ GCC_except_table5395
+ GCC_except_table5452
+ GCC_except_table5456
+ GCC_except_table547
+ GCC_except_table5510
+ GCC_except_table5540
+ GCC_except_table5543
+ GCC_except_table5633
+ GCC_except_table5647
+ GCC_except_table5654
+ GCC_except_table5666
+ GCC_except_table5670
+ GCC_except_table5680
+ GCC_except_table572
+ GCC_except_table578
+ GCC_except_table579
+ GCC_except_table583
+ GCC_except_table5909
+ GCC_except_table5942
+ GCC_except_table5947
+ GCC_except_table5984
+ GCC_except_table5993
+ GCC_except_table604
+ GCC_except_table605
+ GCC_except_table6097
+ GCC_except_table611
+ GCC_except_table6239
+ GCC_except_table6344
+ GCC_except_table6352
+ GCC_except_table637
+ GCC_except_table6372
+ GCC_except_table6377
+ GCC_except_table6483
+ GCC_except_table6538
+ GCC_except_table6618
+ GCC_except_table6640
+ GCC_except_table6641
+ GCC_except_table6651
+ GCC_except_table6652
+ GCC_except_table6664
+ GCC_except_table6706
+ GCC_except_table6711
+ GCC_except_table6716
+ GCC_except_table6744
+ GCC_except_table6816
+ GCC_except_table6828
+ GCC_except_table6851
+ GCC_except_table6862
+ GCC_except_table6865
+ GCC_except_table6888
+ GCC_except_table690
+ GCC_except_table6900
+ GCC_except_table6947
+ GCC_except_table710
+ GCC_except_table7197
+ GCC_except_table7233
+ GCC_except_table7306
+ GCC_except_table7360
+ GCC_except_table7383
+ GCC_except_table7419
+ GCC_except_table7438
+ GCC_except_table7449
+ GCC_except_table7593
+ GCC_except_table7601
+ GCC_except_table768
+ GCC_except_table7717
+ GCC_except_table7718
+ GCC_except_table7719
+ GCC_except_table772
+ GCC_except_table7720
+ GCC_except_table7721
+ GCC_except_table7726
+ GCC_except_table777
+ GCC_except_table7789
+ GCC_except_table7835
+ GCC_except_table7843
+ GCC_except_table7849
+ GCC_except_table7874
+ GCC_except_table7880
+ GCC_except_table7886
+ GCC_except_table8024
+ GCC_except_table943
+ GCC_except_table955
+ GCC_except_table958
+ _OBJC_CLASS_$_CSFModelConfigDecoder
+ _OBJC_CLASS_$_SCDAElectionLedger
+ _OBJC_IVAR_$_CSAttSiriAudioSessionStateClient._ttsEndHostTime
+ _OBJC_IVAR_$_CSEndpointDelayReporter._analytics
+ _OBJC_IVAR_$_CSEndpointDelayReporter._selfLoggingStream
+ _OBJC_IVAR_$_CSSiriAudioActivationInfo._myriadElectionIdentity
+ _OBJC_IVAR_$_CSSiriSpeechRecorder._electionLedgerOverride
+ _OBJC_IVAR_$_CSSiriSpeechRecordingContext._electionIdentity
+ _OBJC_IVAR_$_CSSpeechController._didActivateAudioSessionForRecord
+ _OBJC_IVAR_$_CSSpeechController._prefetchedAudioDeviceInfo
+ _OBJC_IVAR_$_CSVoiceIdXPCConnection._delegate
+ _OBJC_IVAR_$_CSVoiceTriggerSecondPass._requestExclaveAudio
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CSAudioSessionProviding
+ ___41-[CSSpeechController releaseAudioSession]_block_invoke_2
+ ___42-[CSSpeechController releaseAudioSession:]_block_invoke_2
+ ___52-[CSXPCClient _sendMessageAndReplySync:reply:error:]_block_invoke
+ ___58-[CSSpeechController _noteAudioSessionActivatedForRecord:]_block_invoke
+ ___59-[CSVoiceTriggerAssetHandlerMac _handleTriggerAssetRefresh]_block_invoke
+ ___69-[CSAttSiriMitigationAssetProvider getMitigationAssetWithCompletion:]_block_invoke
+ ___70-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]_block_invoke
+ ___70-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]_block_invoke_2
+ ___79-[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]_block_invoke
+ ___79-[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]_block_invoke_2
+ ___79-[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]_block_invoke_3
+ ___block_descriptor_40_e8_32bs_e32_v20?0B8"SCDAElectionOutcome"12ls32l8
+ ___block_descriptor_40_e8_32bs_e8_v12?0B8ls32l8
+ ___block_descriptor_41_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32s40w_e8_v12?0B8ls32l8w40l8
+ ___block_descriptor_49_e8_32s40w_e8_v12?0B8lw40l8s32l8
+ ___block_descriptor_59_e8_32s40r_e20_v20?0B8"NSError"12ls32l8r40l8
+ ___block_descriptor_64_e8_32s40s48r56w_e29_v24?0"CSAsset"8"NSError"16lw56l8s32l8s40l8r48l8
+ ___block_descriptor_68_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
- +[SpeechModelTrainingClient initialize]
- -[CSAttSiriAudioSessionStateClient dispatchStateChangedFrom:to:]
- -[CSVoiceTriggerAPModeSuspendPolicyIOS _isHearstRoutedAndWithNoPhoneCall]
- -[SpeechModelTrainingClient .cxx_destruct]
- -[SpeechModelTrainingClient _serviceProxyWithErrorHandler:]
- -[SpeechModelTrainingClient buildPhoneticMatchWithLanguage:saveIntermediateFsts:completion:]
- -[SpeechModelTrainingClient buildSpeechProfileForLanguage:]
- -[SpeechModelTrainingClient dealloc]
- -[SpeechModelTrainingClient extractBundledOovs:appLmDataFileSandboxExtension:appBundleId:completion:]
- -[SpeechModelTrainingClient generateAudioWithTexts:language:completion:]
- -[SpeechModelTrainingClient generateConfusionPairsWithUUID:parameters:language:task:samplingRate:recognizedNbest:recognizedText:correctedText:selectedAlternatives:completion:]
- -[SpeechModelTrainingClient generateConfusionPairsWithUUID:parameters:language:task:samplingRate:recognizedTokens:recognizedText:correctedText:selectedAlternatives:completion:]
- -[SpeechModelTrainingClient initWithServiceName:]
- -[SpeechModelTrainingClient init]
- -[SpeechModelTrainingClient invalidate]
- -[SpeechModelTrainingClient trainAllAppLMWithLanguage:]
- -[SpeechModelTrainingClient trainAllAppLMWithLanguage:completion:]
- -[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmDataFileSandboxExtension:]
- -[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmDataFileSandboxExtension:completion:]
- -[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmModelFile:appLmDataFileSandboxExtension:]
- -[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmModelFile:appLmDataFileSandboxExtension:completion:]
- -[SpeechModelTrainingClient trainGlobalNNLMwithFidesSessionURL:completion:]
- -[SpeechModelTrainingClient trainPartialAllAppLMWithLanguage:]
- -[SpeechModelTrainingClient trainPartialAllAppLMWithLanguage:completion:]
- -[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:asset:directory:completion:]
- -[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:asset:fides:activity:completion:]
- -[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:fides:activity:completion:]
- -[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:directory:completion:]
- -[SpeechModelTrainingClient upperCaseString:completion:]
- -[SpeechModelTrainingClient wakeUpWithCompletion:]
- -[SpeechModelTrainingClient xpcExitClean]
- GCC_except_table1272
- GCC_except_table1284
- GCC_except_table1490
- GCC_except_table1562
- GCC_except_table1617
- GCC_except_table1641
- GCC_except_table1661
- GCC_except_table1664
- GCC_except_table1694
- GCC_except_table176
- GCC_except_table1792
- GCC_except_table1794
- GCC_except_table1802
- GCC_except_table1862
- GCC_except_table1888
- GCC_except_table1894
- GCC_except_table1975
- GCC_except_table1995
- GCC_except_table200
- GCC_except_table2111
- GCC_except_table2260
- GCC_except_table2290
- GCC_except_table2293
- GCC_except_table2296
- GCC_except_table2301
- GCC_except_table2313
- GCC_except_table2318
- GCC_except_table2321
- GCC_except_table2413
- GCC_except_table2419
- GCC_except_table244
- GCC_except_table2459
- GCC_except_table2462
- GCC_except_table2484
- GCC_except_table2517
- GCC_except_table252
- GCC_except_table2620
- GCC_except_table265
- GCC_except_table2679
- GCC_except_table268
- GCC_except_table2691
- GCC_except_table2722
- GCC_except_table2747
- GCC_except_table2758
- GCC_except_table2792
- GCC_except_table2793
- GCC_except_table2794
- GCC_except_table2795
- GCC_except_table2803
- GCC_except_table2806
- GCC_except_table2820
- GCC_except_table2826
- GCC_except_table2828
- GCC_except_table2829
- GCC_except_table2899
- GCC_except_table3165
- GCC_except_table3243
- GCC_except_table3280
- GCC_except_table3313
- GCC_except_table3316
- GCC_except_table3319
- GCC_except_table3350
- GCC_except_table3410
- GCC_except_table3642
- GCC_except_table3668
- GCC_except_table3696
- GCC_except_table3731
- GCC_except_table3735
- GCC_except_table374
- GCC_except_table3753
- GCC_except_table3757
- GCC_except_table3774
- GCC_except_table3787
- GCC_except_table3789
- GCC_except_table3791
- GCC_except_table3793
- GCC_except_table3794
- GCC_except_table3795
- GCC_except_table3796
- GCC_except_table3798
- GCC_except_table3799
- GCC_except_table3800
- GCC_except_table3803
- GCC_except_table3804
- GCC_except_table3805
- GCC_except_table3806
- GCC_except_table3807
- GCC_except_table3808
- GCC_except_table3809
- GCC_except_table3811
- GCC_except_table3812
- GCC_except_table3820
- GCC_except_table3825
- GCC_except_table3826
- GCC_except_table3827
- GCC_except_table3828
- GCC_except_table3969
- GCC_except_table3993
- GCC_except_table4059
- GCC_except_table4075
- GCC_except_table4096
- GCC_except_table4188
- GCC_except_table4440
- GCC_except_table447
- GCC_except_table4511
- GCC_except_table4512
- GCC_except_table4516
- GCC_except_table4519
- GCC_except_table4523
- GCC_except_table4548
- GCC_except_table4601
- GCC_except_table4607
- GCC_except_table4677
- GCC_except_table4881
- GCC_except_table4888
- GCC_except_table4895
- GCC_except_table4901
- GCC_except_table4984
- GCC_except_table5144
- GCC_except_table5154
- GCC_except_table5178
- GCC_except_table5198
- GCC_except_table5281
- GCC_except_table5295
- GCC_except_table5304
- GCC_except_table5317
- GCC_except_table5319
- GCC_except_table5322
- GCC_except_table5338
- GCC_except_table5350
- GCC_except_table5355
- GCC_except_table5362
- GCC_except_table5367
- GCC_except_table5369
- GCC_except_table5371
- GCC_except_table5373
- GCC_except_table5374
- GCC_except_table5375
- GCC_except_table5376
- GCC_except_table5378
- GCC_except_table5379
- GCC_except_table5380
- GCC_except_table5381
- GCC_except_table5382
- GCC_except_table5384
- GCC_except_table5385
- GCC_except_table5386
- GCC_except_table5388
- GCC_except_table5403
- GCC_except_table5434
- GCC_except_table545
- GCC_except_table5491
- GCC_except_table5495
- GCC_except_table5549
- GCC_except_table5579
- GCC_except_table5582
- GCC_except_table5672
- GCC_except_table5686
- GCC_except_table5693
- GCC_except_table570
- GCC_except_table5705
- GCC_except_table5709
- GCC_except_table5719
- GCC_except_table575
- GCC_except_table576
- GCC_except_table581
- GCC_except_table5948
- GCC_except_table5981
- GCC_except_table5986
- GCC_except_table601
- GCC_except_table602
- GCC_except_table6032
- GCC_except_table6062
- GCC_except_table609
- GCC_except_table6130
- GCC_except_table6272
- GCC_except_table635
- GCC_except_table6375
- GCC_except_table6383
- GCC_except_table6403
- GCC_except_table6408
- GCC_except_table6514
- GCC_except_table6569
- GCC_except_table6649
- GCC_except_table6671
- GCC_except_table6672
- GCC_except_table6682
- GCC_except_table6683
- GCC_except_table6726
- GCC_except_table6737
- GCC_except_table6742
- GCC_except_table6747
- GCC_except_table6775
- GCC_except_table6847
- GCC_except_table6859
- GCC_except_table688
- GCC_except_table6882
- GCC_except_table6893
- GCC_except_table6896
- GCC_except_table6919
- GCC_except_table6931
- GCC_except_table6978
- GCC_except_table708
- GCC_except_table7226
- GCC_except_table7262
- GCC_except_table7335
- GCC_except_table7389
- GCC_except_table7412
- GCC_except_table7453
- GCC_except_table7464
- GCC_except_table7608
- GCC_except_table7616
- GCC_except_table764
- GCC_except_table770
- GCC_except_table7732
- GCC_except_table7733
- GCC_except_table7734
- GCC_except_table7735
- GCC_except_table7736
- GCC_except_table7741
- GCC_except_table775
- GCC_except_table7804
- GCC_except_table7850
- GCC_except_table7858
- GCC_except_table7864
- GCC_except_table7889
- GCC_except_table7895
- GCC_except_table7901
- GCC_except_table8039
- GCC_except_table941
- GCC_except_table953
- GCC_except_table956
- _NSSearchPathForDirectoriesInDomains
- _OBJC_CLASS_$_SpeechModelTrainingClient
- _OBJC_IVAR_$_SpeechModelTrainingClient._smtConnection
- _OBJC_METACLASS_$_SpeechModelTrainingClient
- _SpeechModelTrainingGetInterface
- __OBJC_$_CLASS_METHODS_SpeechModelTrainingClient
- __OBJC_$_INSTANCE_METHODS_SpeechModelTrainingClient
- __OBJC_$_INSTANCE_VARIABLES_SpeechModelTrainingClient
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_SpeechModelTrainingProtocol
- __OBJC_$_PROTOCOL_METHOD_TYPES_SpeechModelTrainingProtocol
- __OBJC_CLASS_RO_$_SpeechModelTrainingClient
- __OBJC_LABEL_PROTOCOL_$_SpeechModelTrainingProtocol
- __OBJC_METACLASS_RO_$_SpeechModelTrainingClient
- __OBJC_PROTOCOL_$_SpeechModelTrainingProtocol
- __OBJC_PROTOCOL_REFERENCE_$_SpeechModelTrainingProtocol
- ___101-[SpeechModelTrainingClient extractBundledOovs:appLmDataFileSandboxExtension:appBundleId:completion:]_block_invoke
- ___101-[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:fides:activity:completion:]_block_invoke
- ___101-[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:fides:activity:completion:]_block_invoke_2
- ___102-[SpeechModelTrainingClient trainPersonalizedLMWithLanguage:configuration:asset:directory:completion:]_block_invoke
- ___122-[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmDataFileSandboxExtension:]_block_invoke
- ___133-[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmDataFileSandboxExtension:completion:]_block_invoke
- ___137-[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmModelFile:appLmDataFileSandboxExtension:]_block_invoke
- ___148-[SpeechModelTrainingClient trainAppLMWithLanguage:configuration:appBundleId:appLmDataFile:appLmModelFile:appLmDataFileSandboxExtension:completion:]_block_invoke
- ___175-[SpeechModelTrainingClient generateConfusionPairsWithUUID:parameters:language:task:samplingRate:recognizedNbest:recognizedText:correctedText:selectedAlternatives:completion:]_block_invoke
- ___176-[SpeechModelTrainingClient generateConfusionPairsWithUUID:parameters:language:task:samplingRate:recognizedTokens:recognizedText:correctedText:selectedAlternatives:completion:]_block_invoke
- ___33-[SpeechModelTrainingClient init]_block_invoke
- ___41-[SpeechModelTrainingClient xpcExitClean]_block_invoke
- ___45-[CSXPCClient sendMessageAndReplySync:error:]_block_invoke
- ___50-[SpeechModelTrainingClient wakeUpWithCompletion:]_block_invoke
- ___55-[SpeechModelTrainingClient trainAllAppLMWithLanguage:]_block_invoke
- ___56-[SpeechModelTrainingClient upperCaseString:completion:]_block_invoke
- ___56-[SpeechModelTrainingClient upperCaseString:completion:]_block_invoke_2
- ___56-[SpeechModelTrainingClient upperCaseString:completion:]_block_invoke_3
- ___58-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequired]_block_invoke
- ___59-[SpeechModelTrainingClient buildSpeechProfileForLanguage:]_block_invoke
- ___62-[SpeechModelTrainingClient trainPartialAllAppLMWithLanguage:]_block_invoke
- ___66-[SpeechModelTrainingClient trainAllAppLMWithLanguage:completion:]_block_invoke
- ___72-[SpeechModelTrainingClient generateAudioWithTexts:language:completion:]_block_invoke
- ___73-[SpeechModelTrainingClient trainPartialAllAppLMWithLanguage:completion:]_block_invoke
- ___75-[SpeechModelTrainingClient trainGlobalNNLMwithFidesSessionURL:completion:]_block_invoke
- ___92-[SpeechModelTrainingClient buildPhoneticMatchWithLanguage:saveIntermediateFsts:completion:]_block_invoke
- ___92-[SpeechModelTrainingClient buildPhoneticMatchWithLanguage:saveIntermediateFsts:completion:]_block_invoke_2
- ___block_descriptor_40_e8_32bs_e30_v24?0"NSString"8"NSError"16ls32l8
- ___block_descriptor_40_e8_32bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8
- ___block_descriptor_58_e8_32s40r_e20_v20?0B8"NSError"12ls32l8r40l8
- ___block_descriptor_67_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
- _sLog
CStrings:
+ "%s Audio session activated for record, audioDeviceInfo = %{public}@"
+ "%s Audio session was already activated for record, skipping activation in startRecording"
+ "%s Audio stream failed to start after reporting didStartRecording early, will report didStop : %{public}@"
+ "%s Audio stream started, didStartRecording was already reported early"
+ "%s BTLE Myriad loss; not playing speech stop alert"
+ "%s BTLE recorder is gone; not playing speech stop alert"
+ "%s BTLE request was cancelled; not playing speech stop alert"
+ "%s BTLE speech controller began waiting for Myriad decision (identity %@)"
+ "%s Client %{public}p connection disconnected, notifying xpc listener"
+ "%s Failed to get audio stream handle ID : %{public}@"
+ "%s Invalidating cached record session activation state"
+ "%s Report unexpectedly long launch latency %{public}.3f"
+ "%s Report unexpectedly long launch latency %{public}.3f AudioTimeConverter: %@"
+ "%s Reporting didStartRecording early, ahead of the audio stream start"
+ "%s Sending client speechControllerDidStartRecording successfully? %{public}@"
+ "%s Sending client speechControllerDidStartRecording successfully? %{public}@, audioDeviceInfo = %{public}@"
+ "%s fromState:%llu, toState:%llu, hostTime:%llu"
+ "%s isSiriMode=%d, speechEvent=%ld, wasRequestCancelled=%d, shouldSuppressAlert=%d, recordRoute=%@"
+ "%s reporting request completion with %s:%llu"
+ "%s stop alert: didWin=%d, withError=%d, recordRoute=%@"
+ "%s tts Finished:%u isRequestCompleted:%u ttsEndHostTime:%llu currentHostTime:%llu"
+ "-[CSAttSiriAudioSessionStateClient dispatchStateChangedFrom:to:hostTime:]"
+ "-[CSSiriSpeechRecorder _playStopAlertWithError:]"
+ "-[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]_block_invoke"
+ "-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]_block_invoke"
+ "-[CSSpeechController _invalidateRecordSessionActivationState]"
+ "-[CSSpeechController _noteAudioSessionActivatedForRecord:]_block_invoke"
+ "-[CSSpeechController _notifyDelegateDidStartRecordingSuccessfully:error:]"
+ "-[CSVoiceTriggerAssetHandlerMac _handleTriggerAssetRefresh]_block_invoke"
+ "CSVoiceTriggerAssetHandlerMac.m"
+ "Nil asset"
+ "Recording stop alert"
+ "requestAudioDeviceInfo"
+ "ttsEndHostTime"
+ "v20@?0B8@\"SCDAElectionOutcome\"12"
+ "\xa5"
+ "\xf03"
- "%@"
- "%@ Interrupted"
- "%@ Invalidated"
- "%s BTLE Myriad Not explicitly playing speech stop alert"
- "%s BTLE speech controller began waiting for Myriad decision"
- "%s Client %{public}p connection disconnected, noticing xpc listener"
- "%s Disable FF since this is Exclave hardware without Siri DSP"
- "%s Failed to get audio stream handle ID : %{publid}@"
- "%s Report unexpectedly long launch latency %{publlic}.3f"
- "%s Report unexpectedly long launch latency %{publlic}.3f AudioTimeConverter: %@"
- "%s Sending client speechControllerDidStartRecording successfully? %{pubic}@"
- "%s Sending client speechControllerDidStartRecording successfully? %{pubic}@, audioDeviceInfo = %{public}@"
- "%s fromState:%llu, toState:%llu"
- "%s isSiriMode=%d, speechEvent=%ld, wasRequestCancelled=%d, shouldSuppressAlert=%d, isMonitoringMyriadEvents=%d, didMyriadWin=%d, recordRoute=%@"
- "%s tts Finished:%u isRequestCompleted:%u"
- "-[CSAttSiriAudioSessionStateClient dispatchStateChangedFrom:to:]"
- "-[CSEndpointAnalyzerBase getHybridEndpointerConfigForAsset:]"
- "-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequired]"
- "-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequired]_block_invoke"
- "Assistant/SpeechPersonalizedLM"
- "Assistant/SpeechPersonalizedLM_Fides"
- "Client is 24-hour job"
- "Client is DictationPersonalizationFidesPlugin"
- "Client is PersonalizedLmFidesPlugin"
- "Dealloc-ing"
- "Input directory path(%@) does not match expected path"
- "Invalidating"
- "Received Error %@"
- "Received an error while accessing %@ service: %@"
- "SpeechModelTrainingClient"
- "buildSpeechProfile is unavailable when siri_vocabulary_speech_profile feature flag is enabled."
- "com.apple.corespeech.speechmodeltraining.xpc"
- "com.apple.siri.speechmodeltraining"
- "com.apple.speech.speechmodeltraining"
- "personalizedLMPath=%@ fidesPersonalizedLMPath=%@"
- "siri_vocabulary_speech_profile"
- "\xa3"
- "\xf0#"
```
