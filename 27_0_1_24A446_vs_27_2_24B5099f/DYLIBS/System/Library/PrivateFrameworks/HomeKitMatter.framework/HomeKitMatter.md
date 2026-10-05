## HomeKitMatter

> `/System/Library/PrivateFrameworks/HomeKitMatter.framework/HomeKitMatter`

```diff

-1493.1.5.1.1
-  __TEXT.__text: 0x1813cc
-  __TEXT.__objc_methlist: 0xad0c
-  __TEXT.__const: 0x298
+1520.2.3.0.2
+  __TEXT.__text: 0x185390
+  __TEXT.__objc_methlist: 0xaf1c
+  __TEXT.__const: 0x2c8
   __TEXT.__dlopen_cstrs: 0x58
-  __TEXT.__gcc_except_tab: 0x302c
-  __TEXT.__cstring: 0x6ed0
-  __TEXT.__oslogstring: 0x4f542
+  __TEXT.__gcc_except_tab: 0x30b0
+  __TEXT.__cstring: 0x704f
+  __TEXT.__oslogstring: 0x50502
   __TEXT.__ustring: 0x68
-  __TEXT.__unwind_info: 0x3160
+  __TEXT.__unwind_info: 0x31d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x48f0
-  __DATA_CONST.__objc_classlist: 0x458
+  __DATA_CONST.__const: 0x4938
+  __DATA_CONST.__objc_classlist: 0x460
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x138
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7098
+  __DATA_CONST.__objc_selrefs: 0x71c8
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x310
+  __DATA_CONST.__objc_superrefs: 0x318
   __DATA_CONST.__objc_arraydata: 0x240
-  __DATA_CONST.__got: 0x9f8
-  __AUTH_CONST.__const: 0x1140
-  __AUTH_CONST.__cfstring: 0x6d20
-  __AUTH_CONST.__objc_const: 0x10238
+  __DATA_CONST.__got: 0xa08
+  __AUTH_CONST.__const: 0x1180
+  __AUTH_CONST.__cfstring: 0x6ee0
+  __AUTH_CONST.__objc_const: 0x10640
   __AUTH_CONST.__objc_intobj: 0x1740
   __AUTH_CONST.__objc_arrayobj: 0x168
   __AUTH_CONST.__objc_doubleobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x1e50
-  __DATA.__objc_ivar: 0xb64
+  __AUTH.__objc_data: 0x1ea0
+  __DATA.__objc_ivar: 0xbac
   __DATA.__data: 0xea0
-  __DATA.__bss: 0x478
+  __DATA.__bss: 0x498
   __DATA_DIRTY.__objc_data: 0xd20
-  __DATA_DIRTY.__bss: 0xc0
+  __DATA_DIRTY.__bss: 0xb0
   - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation

   - /System/Library/PrivateFrameworks/UARPKit.framework/UARPKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 4477
-  Symbols:   7338
-  CStrings:  5772
+  Functions: 4537
+  Symbols:   7430
+  CStrings:  5832
 
Symbols:
+ +[HMMTRAsyncMutex logCategory]
+ +[HMMTRMultiFabricDataStoreQuery v2FabricDataItemPreferenceComparator]
+ +[HMMTRProtocolMap mapTargetAirPurifierState:]
+ -[HMMTRAccessoryServer _deviceStorageDataSourceForCurrentNode]
+ -[HMMTRAccessoryServer _endPairingMode]
+ -[HMMTRAccessoryServer _enqueueResumeFinalizeAttempt]
+ -[HMMTRAccessoryServer _invalidateFinalizeRetry]
+ -[HMMTRAccessoryServer _persistThreadWEDInfoToStorage]
+ -[HMMTRAccessoryServer _readCharacteristicValueFromCacheAfterConfirmingBridgedAccessoryReachabilityWithCharacteristic:responseHandler:]
+ -[HMMTRAccessoryServer _resumeFinalizePairing]
+ -[HMMTRAccessoryServer _scheduleFinalizeRetry]
+ -[HMMTRAccessoryServer finalizeRetryAttempt]
+ -[HMMTRAccessoryServer finalizeRetryTimer]
+ -[HMMTRAccessoryServer pendingReenumerationCompletionHandlers]
+ -[HMMTRAccessoryServer pendingServiceReenumeration]
+ -[HMMTRAccessoryServer removeNode:withPrivilege:fromExistingAclEntries:]
+ -[HMMTRAccessoryServer resumeFinalizeForCommissionedAccessoryWithOnboardingURL:]
+ -[HMMTRAccessoryServer setFinalizeRetryAttempt:]
+ -[HMMTRAccessoryServer setFinalizeRetryTimer:]
+ -[HMMTRAccessoryServer setPendingServiceReenumeration:]
+ -[HMMTRAccessoryServerBrowser _makeAccessoryServerFactory]
+ -[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]
+ -[HMMTRAccessoryServerBrowser discoveredAccessoryServersAsyncMutex]
+ -[HMMTRAccessoryServerBrowser fetchPreferredThreadCredentialsUsingFabricUUID:systemCommissionerFabric:withCompletion:]
+ -[HMMTRAccessoryServerBrowser hasPresentCommissionableNodeMatchingOnboardingURL:]
+ -[HMMTRAccessoryServerBrowser updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]
+ -[HMMTRAccessoryServerBrowser workQueueFactory]
+ -[HMMTRAccessoryServerFactory workQueueFactory]
+ -[HMMTRAsyncMutex .cxx_destruct]
+ -[HMMTRAsyncMutex initWithQueue:]
+ -[HMMTRAsyncMutex lockWithCompletion:]
+ -[HMMTRAsyncMutex locked]
+ -[HMMTRAsyncMutex pendingCompletions]
+ -[HMMTRAsyncMutex queue]
+ -[HMMTRAsyncMutex setLocked:]
+ -[HMMTRAsyncMutex unlock]
+ -[HMMTRControllerFactory workQueueFactory]
+ -[HMMTRControllerFactoryStorage initWithWorkQueueFactory:]
+ -[HMMTRControllerFactoryStorage workQueueFactory]
+ -[HMMTRDescriptorClusterManager workQueueFactory]
+ -[HMMTRExclusiveServerActionQueue workQueueFactory]
+ -[HMMTRFirmwareUpdateStatus workQueueFactory]
+ -[HMMTRSyncClusterWindowCovering _targetPositionDictionary:fallingBackToCurrentPositionLift:params:]
+ -[HMMTRSystemCommissionerControllerParams workQueueFactory]
+ -[HMMTRThreadRadioManager eMACAddressOfPairingAccessory]
+ -[HMMTRThreadRadioManager setEMACAddressOfPairingAccessory:]
+ -[HMMTRThreadRadioManager workQueueFactory]
+ GCC_except_table1056
+ GCC_except_table1060
+ GCC_except_table1062
+ GCC_except_table1184
+ GCC_except_table1244
+ GCC_except_table1290
+ GCC_except_table1298
+ GCC_except_table1349
+ GCC_except_table1357
+ GCC_except_table1394
+ GCC_except_table1432
+ GCC_except_table1459
+ GCC_except_table1656
+ GCC_except_table1697
+ GCC_except_table1849
+ GCC_except_table1850
+ GCC_except_table1851
+ GCC_except_table1874
+ GCC_except_table1875
+ GCC_except_table1876
+ GCC_except_table1877
+ GCC_except_table1878
+ GCC_except_table1881
+ GCC_except_table1884
+ GCC_except_table1885
+ GCC_except_table1886
+ GCC_except_table1887
+ GCC_except_table1888
+ GCC_except_table1889
+ GCC_except_table1890
+ GCC_except_table1949
+ GCC_except_table1955
+ GCC_except_table1993
+ GCC_except_table2076
+ GCC_except_table2192
+ GCC_except_table2194
+ GCC_except_table2225
+ GCC_except_table2234
+ GCC_except_table2236
+ GCC_except_table2285
+ GCC_except_table2322
+ GCC_except_table2346
+ GCC_except_table2412
+ GCC_except_table2691
+ GCC_except_table2693
+ GCC_except_table2695
+ GCC_except_table2699
+ GCC_except_table2760
+ GCC_except_table2801
+ GCC_except_table2881
+ GCC_except_table2882
+ GCC_except_table2883
+ GCC_except_table2905
+ GCC_except_table2906
+ GCC_except_table2907
+ GCC_except_table2908
+ GCC_except_table2909
+ GCC_except_table2910
+ GCC_except_table2911
+ GCC_except_table2912
+ GCC_except_table2922
+ GCC_except_table2924
+ GCC_except_table2936
+ GCC_except_table2955
+ GCC_except_table2971
+ GCC_except_table2977
+ GCC_except_table2990
+ GCC_except_table2993
+ GCC_except_table2997
+ GCC_except_table3012
+ GCC_except_table3015
+ GCC_except_table3019
+ GCC_except_table3021
+ GCC_except_table3051
+ GCC_except_table3060
+ GCC_except_table3065
+ GCC_except_table3077
+ GCC_except_table3129
+ GCC_except_table3130
+ GCC_except_table3520
+ GCC_except_table3546
+ GCC_except_table3547
+ GCC_except_table3551
+ GCC_except_table3556
+ GCC_except_table3559
+ GCC_except_table3575
+ GCC_except_table3590
+ GCC_except_table3659
+ GCC_except_table3667
+ GCC_except_table3669
+ GCC_except_table3676
+ GCC_except_table3677
+ GCC_except_table3710
+ GCC_except_table3719
+ GCC_except_table3723
+ GCC_except_table3757
+ GCC_except_table3760
+ GCC_except_table3768
+ GCC_except_table3790
+ GCC_except_table3794
+ GCC_except_table3833
+ GCC_except_table3835
+ GCC_except_table3837
+ GCC_except_table3854
+ GCC_except_table3856
+ GCC_except_table3874
+ GCC_except_table3951
+ GCC_except_table4016
+ GCC_except_table4039
+ GCC_except_table4043
+ GCC_except_table4058
+ GCC_except_table4059
+ GCC_except_table4060
+ GCC_except_table4066
+ GCC_except_table4073
+ GCC_except_table4078
+ GCC_except_table4133
+ GCC_except_table4155
+ GCC_except_table4197
+ GCC_except_table4202
+ GCC_except_table4205
+ GCC_except_table4290
+ GCC_except_table4346
+ GCC_except_table4349
+ GCC_except_table4411
+ GCC_except_table4473
+ GCC_except_table4477
+ GCC_except_table4481
+ GCC_except_table4484
+ GCC_except_table4517
+ GCC_except_table572
+ GCC_except_table576
+ GCC_except_table578
+ GCC_except_table580
+ GCC_except_table753
+ GCC_except_table754
+ GCC_except_table811
+ GCC_except_table812
+ GCC_except_table813
+ GCC_except_table886
+ GCC_except_table928
+ GCC_except_table978
+ GCC_except_table982
+ GCC_except_table984
+ GCC_except_table986
+ GCC_except_table988
+ GCC_except_table992
+ _HAPWorkQueueFactoryOrDefault
+ _HMErrorDomain
+ _HMMTRAccessoryServerDeferredMatterCommissioningErrorKey
+ _HMMTRAccessoryServerDeferredMatterCommissioningNodeIDKey
+ _HMMTRAccessoryServerDidBeginDeferredMatterCommissioningNotification
+ _HMMTRAccessoryServerDidFailDeferredMatterCommissioningNotification
+ _HMMTRIsSecondPartyProduct
+ _OBJC_CLASS_$_HMMTRAsyncMutex
+ _OBJC_IVAR_$_HMMTRAccessoryServer._finalizeRetryAttempt
+ _OBJC_IVAR_$_HMMTRAccessoryServer._finalizeRetryTimer
+ _OBJC_IVAR_$_HMMTRAccessoryServer._pendingReenumerationCompletionHandlers
+ _OBJC_IVAR_$_HMMTRAccessoryServer._pendingServiceReenumeration
+ _OBJC_IVAR_$_HMMTRAccessoryServerBrowser._discoveredAccessoryServersAsyncMutex
+ _OBJC_IVAR_$_HMMTRAccessoryServerBrowser._workQueueFactory
+ _OBJC_IVAR_$_HMMTRAccessoryServerFactory._workQueueFactory
+ _OBJC_IVAR_$_HMMTRAsyncMutex._locked
+ _OBJC_IVAR_$_HMMTRAsyncMutex._pendingCompletions
+ _OBJC_IVAR_$_HMMTRAsyncMutex._queue
+ _OBJC_IVAR_$_HMMTRControllerFactory._workQueueFactory
+ _OBJC_IVAR_$_HMMTRControllerFactoryStorage._workQueueFactory
+ _OBJC_IVAR_$_HMMTRDescriptorClusterManager._workQueueFactory
+ _OBJC_IVAR_$_HMMTRExclusiveServerActionQueue._workQueueFactory
+ _OBJC_IVAR_$_HMMTRFirmwareUpdateStatus._workQueueFactory
+ _OBJC_IVAR_$_HMMTRSystemCommissionerControllerParams._workQueueFactory
+ _OBJC_IVAR_$_HMMTRThreadRadioManager._eMACAddressOfPairingAccessory
+ _OBJC_IVAR_$_HMMTRThreadRadioManager._workQueueFactory
+ _OBJC_METACLASS_$_HMMTRAsyncMutex
+ __OBJC_$_CLASS_METHODS_HMMTRAsyncMutex
+ __OBJC_$_INSTANCE_METHODS_HMMTRAsyncMutex
+ __OBJC_$_INSTANCE_VARIABLES_HMMTRAsyncMutex
+ __OBJC_$_PROP_LIST_HMMTRAsyncMutex
+ __OBJC_CLASS_RO_$_HMMTRAsyncMutex
+ __OBJC_METACLASS_RO_$_HMMTRAsyncMutex
+ ___118-[HMMTRAccessoryServerBrowser fetchPreferredThreadCredentialsUsingFabricUUID:systemCommissionerFabric:withCompletion:]_block_invoke
+ ___139-[HMMTRAccessoryServer scheduleOrExecuteOTAProviderAnnouncement:initiatorType:immediateAnnouncement:endpoint:delayCounter:isUserTriggered:]_block_invoke_2
+ ___177-[HMMTRAccessoryServerBrowser setOperationalFabricData:operationalCertIssuer:storageDataSource:allTargetFabricUUIDs:entityIdentifier:accessoryServerNodeIDs:forTargetFabricUUID:]_block_invoke_2
+ ___25-[HMMTRAsyncMutex unlock]_block_invoke
+ ___30+[HMMTRAsyncMutex logCategory]_block_invoke
+ ___38-[HMMTRAsyncMutex lockWithCompletion:]_block_invoke
+ ___39-[HMMTRAccessoryServer _endPairingMode]_block_invoke
+ ___40-[HMMTRAccessoryServer _finalizePairing]_block_invoke_3
+ ___46-[HMMTRAccessoryServer _resumeFinalizePairing]_block_invoke
+ ___53-[HMMTRAccessoryServer _enqueueResumeFinalizeAttempt]_block_invoke
+ ___54-[HMMTRAccessoryServer _persistThreadWEDInfoToStorage]_block_invoke
+ ___70+[HMMTRMultiFabricDataStoreQuery v2FabricDataItemPreferenceComparator]_block_invoke
+ ___80-[HMMTRAccessoryServer resumeFinalizeForCommissionedAccessoryWithOnboardingURL:]_block_invoke
+ ___95-[HMMTRAccessoryServerBrowser updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]_block_invoke
+ ___96-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]_block_invoke
+ ___96-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]_block_invoke_2
+ ___block_descriptor_32_e111_q24?0"<HMMTRMultiFabricDataStoreQueryV2FabricDataItem>"8"<HMMTRMultiFabricDataStoreQueryV2FabricDataItem>"16l
+ ___block_descriptor_57_e8_32s40s48bs_e46_v24?0"HAPThreadNetworkMetadata"8"NSError"16ls32l8s48l8s40l8
+ ___block_descriptor_57_e8_32s40s48bs_e5_v8?0ls32l8s48l8s40l8
+ _defaultFeatures._hmf_once_t9
+ _defaultFeatures._hmf_once_v10
+ _logCategory._hmf_once_t135
+ _logCategory._hmf_once_t136
+ _logCategory._hmf_once_t1419
+ _logCategory._hmf_once_t180
+ _logCategory._hmf_once_t24
+ _logCategory._hmf_once_t32
+ _logCategory._hmf_once_t346
+ _logCategory._hmf_once_t492
+ _logCategory._hmf_once_t50
+ _logCategory._hmf_once_t786
+ _logCategory._hmf_once_v136
+ _logCategory._hmf_once_v137
+ _logCategory._hmf_once_v1420
+ _logCategory._hmf_once_v181
+ _logCategory._hmf_once_v25
+ _logCategory._hmf_once_v33
+ _logCategory._hmf_once_v347
+ _logCategory._hmf_once_v493
+ _logCategory._hmf_once_v51
+ _logCategory._hmf_once_v787
+ _secondPartyProducts
- +[HMMTRProtocolMap mapTargetAirPuriferState:]
- -[HMMTRAccessoryServer _readCharacteristicValueFromCacheAfterConfirmingBridgedAccessroyReachabilityWithCharacteristic:responseHandler:]
- -[HMMTRAccessoryServer removeNode:withPrivilge:fromExistingAclEntries:]
- -[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:]
- -[HMMTRProtocolMap isRequiresOptionalMatterAttributeForCharacteristic:]
- GCC_except_table1041
- GCC_except_table1045
- GCC_except_table1047
- GCC_except_table1169
- GCC_except_table1229
- GCC_except_table1275
- GCC_except_table1283
- GCC_except_table1332
- GCC_except_table1340
- GCC_except_table1377
- GCC_except_table1414
- GCC_except_table1441
- GCC_except_table1635
- GCC_except_table1676
- GCC_except_table1828
- GCC_except_table1829
- GCC_except_table1830
- GCC_except_table1833
- GCC_except_table1853
- GCC_except_table1855
- GCC_except_table1856
- GCC_except_table1857
- GCC_except_table1860
- GCC_except_table1863
- GCC_except_table1864
- GCC_except_table1865
- GCC_except_table1866
- GCC_except_table1867
- GCC_except_table1868
- GCC_except_table1869
- GCC_except_table1928
- GCC_except_table1934
- GCC_except_table1972
- GCC_except_table2055
- GCC_except_table2168
- GCC_except_table2170
- GCC_except_table2200
- GCC_except_table2208
- GCC_except_table2210
- GCC_except_table2259
- GCC_except_table2296
- GCC_except_table2320
- GCC_except_table2385
- GCC_except_table2662
- GCC_except_table2664
- GCC_except_table2666
- GCC_except_table2670
- GCC_except_table2728
- GCC_except_table2769
- GCC_except_table2815
- GCC_except_table2817
- GCC_except_table2849
- GCC_except_table2872
- GCC_except_table2873
- GCC_except_table2874
- GCC_except_table2875
- GCC_except_table2876
- GCC_except_table2877
- GCC_except_table2878
- GCC_except_table2879
- GCC_except_table2889
- GCC_except_table2891
- GCC_except_table2902
- GCC_except_table2921
- GCC_except_table2937
- GCC_except_table2943
- GCC_except_table2956
- GCC_except_table2959
- GCC_except_table2963
- GCC_except_table2978
- GCC_except_table2981
- GCC_except_table2985
- GCC_except_table2987
- GCC_except_table3014
- GCC_except_table3023
- GCC_except_table3028
- GCC_except_table3040
- GCC_except_table3091
- GCC_except_table3092
- GCC_except_table3475
- GCC_except_table3500
- GCC_except_table3501
- GCC_except_table3502
- GCC_except_table3506
- GCC_except_table3511
- GCC_except_table3514
- GCC_except_table3530
- GCC_except_table3614
- GCC_except_table3622
- GCC_except_table3624
- GCC_except_table3631
- GCC_except_table3632
- GCC_except_table3661
- GCC_except_table3668
- GCC_except_table3700
- GCC_except_table3703
- GCC_except_table3711
- GCC_except_table3731
- GCC_except_table3734
- GCC_except_table3772
- GCC_except_table3774
- GCC_except_table3776
- GCC_except_table3793
- GCC_except_table3795
- GCC_except_table3813
- GCC_except_table3890
- GCC_except_table3937
- GCC_except_table3955
- GCC_except_table3978
- GCC_except_table3982
- GCC_except_table3997
- GCC_except_table3999
- GCC_except_table4005
- GCC_except_table4012
- GCC_except_table4017
- GCC_except_table4072
- GCC_except_table4094
- GCC_except_table4137
- GCC_except_table4142
- GCC_except_table4145
- GCC_except_table4229
- GCC_except_table4230
- GCC_except_table4286
- GCC_except_table4351
- GCC_except_table4413
- GCC_except_table4417
- GCC_except_table4421
- GCC_except_table4424
- GCC_except_table4457
- GCC_except_table571
- GCC_except_table575
- GCC_except_table577
- GCC_except_table579
- GCC_except_table739
- GCC_except_table740
- GCC_except_table797
- GCC_except_table798
- GCC_except_table799
- GCC_except_table872
- GCC_except_table914
- GCC_except_table963
- GCC_except_table967
- GCC_except_table969
- GCC_except_table971
- GCC_except_table973
- GCC_except_table977
- ___84-[HMMTRAccessoryServerBrowser updateDiscoveredAccessoryServersWithNodes:fabricUUID:]_block_invoke
- ___85-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:]_block_invoke
- ___85-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSArray"8ls32l8s40l8s48l8
- ___block_descriptor_57_e8_32s40s48bs_e5_v8?0ls32l8s40l8s48l8
- _defaultFeatures._hmf_once_t2
- _defaultFeatures._hmf_once_v3
- _dispatch_queue_create_with_target$V2
- _logCategory._hmf_once_t119
- _logCategory._hmf_once_t129
- _logCategory._hmf_once_t1361
- _logCategory._hmf_once_t178
- _logCategory._hmf_once_t18
- _logCategory._hmf_once_t29
- _logCategory._hmf_once_t345
- _logCategory._hmf_once_t491
- _logCategory._hmf_once_t749
- _logCategory._hmf_once_v120
- _logCategory._hmf_once_v130
- _logCategory._hmf_once_v1362
- _logCategory._hmf_once_v179
- _logCategory._hmf_once_v19
- _logCategory._hmf_once_v30
- _logCategory._hmf_once_v346
- _logCategory._hmf_once_v492
- _logCategory._hmf_once_v750
CStrings:
+ "<unknown>"
+ "Accessory for nodeID %@ is not network-commissioning-ready; skipping"
+ "Cannot parse Matter onboarding payload for commissionable-node presence check: %{public}@"
+ "Commissionable-node powered check: discriminator=%{public}@ vendorID=%{public}@ productID=%{public}@ matchingNodePresent=%{public}d (%lu present)"
+ "Connecting pending fabric: %@"
+ "Deferred Matter commissioning not allowed on this controller device; leaving nodeID %@ pending"
+ "Deferred service re-enumeration complete with error domain: %{public}@ code: %ld"
+ "Delegate does not support fabric-scoped Thread credential retrieval"
+ "Element data array missing from array type %@"
+ "FATAL Error: Failed to generate operational cert for fabric ID %@. error: %@"
+ "Failed to fetch Preferred Thread Credentials from owner, error domain: %{public}@ code: %ld"
+ "Failed to persist HomeMatterFabricCommissioningDone state, error domain: %{public}@ code: %ld"
+ "Failed to persist WED support from commissionee info: %@"
+ "Failed to persist eMAC from commissionee info: %@"
+ "Finalize already complete; skipping resume and releasing exclusive slot"
+ "Finalize failed after Matter commissioning completed; scheduling finalize retry with backoff"
+ "Finalize retry already scheduled; not stacking another"
+ "Finalize retry timer fired; enqueuing resume attempt"
+ "Firmware update connection attempt for an accessory with nodeID %@, error = %@"
+ "FirstTimePairing"
+ "HMMTRAccessoryServerDeferredMatterCommissioningErrorKey"
+ "HMMTRAccessoryServerDeferredMatterCommissioningNodeIDKey"
+ "HMMTRAccessoryServerDidBeginDeferredMatterCommissioningNotification"
+ "HMMTRAccessoryServerDidFailDeferredMatterCommissioningNotification"
+ "Lock acquired"
+ "Lock handed to next waiter (pending=%lu)"
+ "Lock is held; queued waiter (pending=%lu)"
+ "Lock released"
+ "No %{public}@ cluster in any of %lu endpoints"
+ "No device storage data source; cannot persist WED info for nodeID %@"
+ "No endpoints available for diagnostic clusters for accessory %{public}@ %{private}@"
+ "Node %@ completed Matter fabric commissioning but not finalize; resuming finalize"
+ "ProxPairing"
+ "Read color control attribute colorCapabilities supportsColorTempFeature: %@ accessoryRange: [%@ : %@] allowedRange: [%@ : %@]"
+ "Refusing to commission vendor %@ product %@: pairing this accessory is not supported"
+ "Resuming finalize (attempt %lu)"
+ "Resuming finalize for already-commissioned deferred Matter accessory with onboarding URL %{private}@"
+ "Scheduling finalize retry #%lu in %.0f seconds"
+ "Skipping resume finalize: accessory server is disabled, has no controller, or the browser has died"
+ "Target Position reported null; falling back to Current Position"
+ "Thread StopAccessoryPairing completed, error domain: %{public}@ code: %ld"
+ "Thread credential fabric %{public}@ does not match current browser fabric %{public}@"
+ "Unlock called while not locked; ignoring"
+ "[%{public}@] Accessory for nodeID %@ is not network-commissioning-ready; skipping"
+ "[%{public}@] Cannot parse Matter onboarding payload for commissionable-node presence check: %{public}@"
+ "[%{public}@] Commissionable-node powered check: discriminator=%{public}@ vendorID=%{public}@ productID=%{public}@ matchingNodePresent=%{public}d (%lu present)"
+ "[%{public}@] Connecting pending fabric: %@"
+ "[%{public}@] Deferred Matter commissioning not allowed on this controller device; leaving nodeID %@ pending"
+ "[%{public}@] Deferred service re-enumeration complete with error domain: %{public}@ code: %ld"
+ "[%{public}@] Delegate does not support fabric-scoped Thread credential retrieval"
+ "[%{public}@] Element data array missing from array type %@"
+ "[%{public}@] FATAL Error: Failed to generate operational cert for fabric ID %@. error: %@"
+ "[%{public}@] Failed to fetch Preferred Thread Credentials from owner, error domain: %{public}@ code: %ld"
+ "[%{public}@] Failed to persist HomeMatterFabricCommissioningDone state, error domain: %{public}@ code: %ld"
+ "[%{public}@] Failed to persist WED support from commissionee info: %@"
+ "[%{public}@] Failed to persist eMAC from commissionee info: %@"
+ "[%{public}@] Finalize already complete; skipping resume and releasing exclusive slot"
+ "[%{public}@] Finalize failed after Matter commissioning completed; scheduling finalize retry with backoff"
+ "[%{public}@] Finalize retry already scheduled; not stacking another"
+ "[%{public}@] Finalize retry timer fired; enqueuing resume attempt"
+ "[%{public}@] Firmware update connection attempt for an accessory with nodeID %@, error = %@"
+ "[%{public}@] Lock acquired"
+ "[%{public}@] Lock handed to next waiter (pending=%lu)"
+ "[%{public}@] Lock is held; queued waiter (pending=%lu)"
+ "[%{public}@] Lock released"
+ "[%{public}@] No %{public}@ cluster in any of %lu endpoints"
+ "[%{public}@] No device storage data source; cannot persist WED info for nodeID %@"
+ "[%{public}@] No endpoints available for diagnostic clusters for accessory %{public}@ %{private}@"
+ "[%{public}@] Node %@ completed Matter fabric commissioning but not finalize; resuming finalize"
+ "[%{public}@] Read color control attribute colorCapabilities supportsColorTempFeature: %@ accessoryRange: [%@ : %@] allowedRange: [%@ : %@]"
+ "[%{public}@] Refusing to commission vendor %@ product %@: pairing this accessory is not supported"
+ "[%{public}@] Resuming finalize (attempt %lu)"
+ "[%{public}@] Resuming finalize for already-commissioned deferred Matter accessory with onboarding URL %{private}@"
+ "[%{public}@] Scheduling finalize retry #%lu in %.0f seconds"
+ "[%{public}@] Skipping resume finalize: accessory server is disabled, has no controller, or the browser has died"
+ "[%{public}@] Target Position reported null; falling back to Current Position"
+ "[%{public}@] Thread StopAccessoryPairing completed, error domain: %{public}@ code: %ld"
+ "[%{public}@] Thread credential fabric %{public}@ does not match current browser fabric %{public}@"
+ "[%{public}@] Unlock called while not locked; ignoring"
+ "[%{public}@] _connectPendingFabricConnectionsForTargetFabricUUID for - %@"
+ "[%{public}@] resumeFinalizeForCommissionedAccessoryWithOnboardingURL called but already resuming; ignoring"
+ "[%{public}@] verifyHAPCharacteristicSupportWithRequiredAttributeValuesAtCHIPEndpoint shortCharacteristicKey = %@, clusterClassName = %@, hapServicesToCheckForRequiredAttributeValues = %@, hapCharacteristicsToCheckForRequiredAttributeValues = %@, curHAPCharacteristicAttributesToCheck = %@"
+ "_connectPendingFabricConnectionsForTargetFabricUUID for - %@"
+ "hmmtr.asyncmutex"
+ "q24@?0@\"<HMMTRMultiFabricDataStoreQueryV2FabricDataItem>\"8@\"<HMMTRMultiFabricDataStoreQueryV2FabricDataItem>\"16"
+ "resumeFinalizeForCommissionedAccessoryWithOnboardingURL called but already resuming; ignoring"
+ "verifyHAPCharacteristicSupportWithRequiredAttributeValuesAtCHIPEndpoint shortCharacteristicKey = %@, clusterClassName = %@, hapServicesToCheckForRequiredAttributeValues = %@, hapCharacteristicsToCheckForRequiredAttributeValues = %@, curHAPCharacteristicAttributesToCheck = %@"
+ "\xf0\xd2\xf0\xf0\xf0A\xf0\x81"
- "Accessory for nodeID %@ is not user configuration ready; skipping"
- "Connecting pending fabric fabric: %@"
- "Element data data array missing from array type %@"
- "FATAL Error: Failed to generate ooperational cert for fabric ID %@. error: %@"
- "Firmware update connection attempt for a accessory with nodeID %@, error = %@"
- "No %@ cluster in any endpoints %@."
- "No endpoints available for diagnostic clusters for HAPAccessory: %@"
- "Notifying matter petric pairing step %@"
- "Optional characteristic %@ on endpoint %@ of node %@ requires an additional Optional Matter attribute check"
- "Read color control attribute colorCapabilities supportsColorTempFeature: %@ accessoryRange: [%@ : %@]  allowedRange: [%@ : %@]"
- "RequiresOptionalMatterAttribute"
- "Thread StopAccessoryPairing completed, error: %@"
- "[%{public}@] Accessory for nodeID %@ is not user configuration ready; skipping"
- "[%{public}@] Connecting pending fabric fabric: %@"
- "[%{public}@] Element data data array missing from array type %@"
- "[%{public}@] FATAL Error: Failed to generate ooperational cert for fabric ID %@. error: %@"
- "[%{public}@] Firmware update connection attempt for a accessory with nodeID %@, error = %@"
- "[%{public}@] No %@ cluster in any endpoints %@."
- "[%{public}@] No endpoints available for diagnostic clusters for HAPAccessory: %@"
- "[%{public}@] Notifying matter petric pairing step %@"
- "[%{public}@] Optional characteristic %@ on endpoint %@ of node %@ requires an additional Optional Matter attribute check"
- "[%{public}@] Read color control attribute colorCapabilities supportsColorTempFeature: %@ accessoryRange: [%@ : %@]  allowedRange: [%@ : %@]"
- "[%{public}@] Thread StopAccessoryPairing completed, error: %@"
- "[%{public}@] _connectPendingFabricConnectionsForTargetFabricUUIDID for - %@"
- "[%{public}@] verifyHAPCharacteristicSupportWithRequiredAttributeValuesAtCHIPEndpoint shortCharacteristicKey = %@, clusterClassName = %@,  hapServicesToCheckForRequiredAttributeValues = %@, hapCharacteristicsToCheckForRequiredAttributeValues = %@, curHAPCharacteristicAttributesToCheck = %@"
- "_connectPendingFabricConnectionsForTargetFabricUUIDID for - %@"
- "verifyHAPCharacteristicSupportWithRequiredAttributeValuesAtCHIPEndpoint shortCharacteristicKey = %@, clusterClassName = %@,  hapServicesToCheckForRequiredAttributeValues = %@, hapCharacteristicsToCheckForRequiredAttributeValues = %@, curHAPCharacteristicAttributesToCheck = %@"
- "\xf0\xd2\xf0\xf0\xf01\xf0a"
```
