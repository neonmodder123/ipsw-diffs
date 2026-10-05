## PhotoLibraryServicesCore

> `/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/PhotoLibraryServicesCore`

```diff

-912.1.131.0.0
-  __TEXT.__text: 0xcbe58
-  __TEXT.__objc_methlist: 0x834c
+916.51.202.0.0
+  __TEXT.__text: 0xce04c
+  __TEXT.__objc_methlist: 0x83d4
   __TEXT.__const: 0x23cc
   __TEXT.__dlopen_cstrs: 0x19c
-  __TEXT.__gcc_except_tab: 0x5710
-  __TEXT.__cstring: 0x161df
-  __TEXT.__oslogstring: 0xb26b
+  __TEXT.__gcc_except_tab: 0x5860
+  __TEXT.__cstring: 0x16311
+  __TEXT.__oslogstring: 0xb4d5
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x3488
+  __TEXT.__unwind_info: 0x3518
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3cb0
+  __DATA_CONST.__const: 0x3ca8
   __DATA_CONST.__objc_classlist: 0x408
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x160
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4ca8
+  __DATA_CONST.__objc_selrefs: 0x4d18
   __DATA_CONST.__objc_protorefs: 0xc8
   __DATA_CONST.__objc_superrefs: 0x268
-  __DATA_CONST.__objc_arraydata: 0x420
-  __DATA_CONST.__got: 0xa48
-  __AUTH_CONST.__const: 0x35e8
-  __AUTH_CONST.__cfstring: 0x122e0
-  __AUTH_CONST.__objc_const: 0xaa08
-  __AUTH_CONST.__objc_intobj: 0x918
+  __DATA_CONST.__objc_arraydata: 0x428
+  __DATA_CONST.__got: 0xa58
+  __AUTH_CONST.__const: 0x36d0
+  __AUTH_CONST.__cfstring: 0x12380
+  __AUTH_CONST.__objc_const: 0xaa50
+  __AUTH_CONST.__objc_intobj: 0x930
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__objc_arrayobj: 0x288
-  __AUTH_CONST.__auth_got: 0xe48
-  __AUTH.__objc_data: 0x370
-  __DATA.__objc_ivar: 0x678
+  __AUTH_CONST.__objc_arrayobj: 0x2a0
+  __AUTH_CONST.__auth_got: 0xe58
+  __AUTH.__objc_data: 0xa0
+  __DATA.__objc_ivar: 0x67c
   __DATA.__data: 0x10e0
-  __DATA.__bss: 0xdc0
-  __DATA_DIRTY.__objc_data: 0x24e0
+  __DATA.__bss: 0xe38
+  __DATA_DIRTY.__objc_data: 0x27b0
   __DATA_DIRTY.__data: 0x8
-  __DATA_DIRTY.__bss: 0x408
+  __DATA_DIRTY.__bss: 0x3a0
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

   - /System/Library/Frameworks/VideoToolbox.framework/VideoToolbox
   - /System/Library/Frameworks/_LocationEssentials.framework/_LocationEssentials
   - /System/Library/PrivateFrameworks/AppSupport.framework/AppSupport
+  - /System/Library/PrivateFrameworks/AuthKit.framework/AuthKit
   - /System/Library/PrivateFrameworks/CMPhoto.framework/CMPhoto
   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics
   - /System/Library/PrivateFrameworks/PhotoFoundation.framework/PhotoFoundation

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libperfcheck.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 3976
-  Symbols:   7916
-  CStrings:  3697
+  Functions: 4006
+  Symbols:   7956
+  CStrings:  3713
 
Symbols:
+ +[PLAppPrivateData _isOptedIntoLibraryPrivateDataCreationTracking]
+ +[PLFileUtilities addOwnerWritePermissionIfNecessaryToFileAtPath:]
+ +[PLSecurity isEntitledForPrivatePhotosTCCForToken:]
+ -[PLAppPrivateData clearWasCreatedFlag]
+ -[PLAppPrivateData setWasNewlyCreated:]
+ -[PLAppPrivateData wasCreated]
+ -[PLAppPrivateData wasNewlyCreated]
+ -[PLAssetsdCloudInternalClient updateAccessRequestForParticipantWithUUID:toAcceptanceStatus:inCollectionShareWithIdentifier:completionHandler:]
+ -[PLAssetsdLibraryInternalClient getSearchDonationProgressShouldCompute:shouldReport:completionHandler:]
+ -[PLAssetsdLibraryInternalClient migrateLimitedLibraryAccessFromApplication:toApplication:completionHandler:]
+ -[PLAssetsdLibraryInternalClient transferAssetsWithUuids:fromLibraryURL:transferOptions:completionHandler:]
+ -[PLAssetsdLibraryInternalClient transferPersonsWithUuids:fromLibraryURL:transferOptions:completionHandler:]
+ -[PLAssetsdNonBindingDebugClient stateCaptureDictionary]
+ -[PLLazyObject isValid]
+ -[PLLazyObject wasInvalidated]
+ GCC_except_table1014
+ GCC_except_table1054
+ GCC_except_table1118
+ GCC_except_table1121
+ GCC_except_table1454
+ GCC_except_table1469
+ GCC_except_table1478
+ GCC_except_table1595
+ GCC_except_table1618
+ GCC_except_table1623
+ GCC_except_table1660
+ GCC_except_table1676
+ GCC_except_table1702
+ GCC_except_table1704
+ GCC_except_table1711
+ GCC_except_table1714
+ GCC_except_table1717
+ GCC_except_table1720
+ GCC_except_table1723
+ GCC_except_table1726
+ GCC_except_table1729
+ GCC_except_table1732
+ GCC_except_table1738
+ GCC_except_table1742
+ GCC_except_table1745
+ GCC_except_table1748
+ GCC_except_table1759
+ GCC_except_table1762
+ GCC_except_table1765
+ GCC_except_table1768
+ GCC_except_table1771
+ GCC_except_table1774
+ GCC_except_table1777
+ GCC_except_table1780
+ GCC_except_table1783
+ GCC_except_table1786
+ GCC_except_table1793
+ GCC_except_table1797
+ GCC_except_table1800
+ GCC_except_table1803
+ GCC_except_table1817
+ GCC_except_table1820
+ GCC_except_table1823
+ GCC_except_table1826
+ GCC_except_table1836
+ GCC_except_table1844
+ GCC_except_table1852
+ GCC_except_table1953
+ GCC_except_table1972
+ GCC_except_table1976
+ GCC_except_table2131
+ GCC_except_table2139
+ GCC_except_table2189
+ GCC_except_table2194
+ GCC_except_table2195
+ GCC_except_table2197
+ GCC_except_table2200
+ GCC_except_table2340
+ GCC_except_table2429
+ GCC_except_table2469
+ GCC_except_table2503
+ GCC_except_table2526
+ GCC_except_table2529
+ GCC_except_table2532
+ GCC_except_table2535
+ GCC_except_table2538
+ GCC_except_table2552
+ GCC_except_table2559
+ GCC_except_table259
+ GCC_except_table2599
+ GCC_except_table2603
+ GCC_except_table2606
+ GCC_except_table2611
+ GCC_except_table2614
+ GCC_except_table2617
+ GCC_except_table2621
+ GCC_except_table2625
+ GCC_except_table2629
+ GCC_except_table2632
+ GCC_except_table264
+ GCC_except_table2678
+ GCC_except_table2682
+ GCC_except_table2686
+ GCC_except_table2690
+ GCC_except_table2694
+ GCC_except_table2705
+ GCC_except_table2709
+ GCC_except_table272
+ GCC_except_table2724
+ GCC_except_table2727
+ GCC_except_table2730
+ GCC_except_table2753
+ GCC_except_table2761
+ GCC_except_table2772
+ GCC_except_table2779
+ GCC_except_table278
+ GCC_except_table2782
+ GCC_except_table2785
+ GCC_except_table2791
+ GCC_except_table2794
+ GCC_except_table2797
+ GCC_except_table2800
+ GCC_except_table2803
+ GCC_except_table2806
+ GCC_except_table2809
+ GCC_except_table281
+ GCC_except_table2815
+ GCC_except_table2818
+ GCC_except_table2821
+ GCC_except_table2824
+ GCC_except_table2827
+ GCC_except_table2830
+ GCC_except_table2832
+ GCC_except_table286
+ GCC_except_table2888
+ GCC_except_table289
+ GCC_except_table294
+ GCC_except_table2955
+ GCC_except_table2958
+ GCC_except_table297
+ GCC_except_table300
+ GCC_except_table3015
+ GCC_except_table3069
+ GCC_except_table3080
+ GCC_except_table3082
+ GCC_except_table3086
+ GCC_except_table3088
+ GCC_except_table309
+ GCC_except_table3107
+ GCC_except_table3115
+ GCC_except_table315
+ GCC_except_table321
+ GCC_except_table324
+ GCC_except_table3268
+ GCC_except_table327
+ GCC_except_table3272
+ GCC_except_table3277
+ GCC_except_table3281
+ GCC_except_table3284
+ GCC_except_table3287
+ GCC_except_table3290
+ GCC_except_table3293
+ GCC_except_table3296
+ GCC_except_table330
+ GCC_except_table333
+ GCC_except_table3348
+ GCC_except_table3350
+ GCC_except_table3385
+ GCC_except_table3509
+ GCC_except_table3575
+ GCC_except_table3579
+ GCC_except_table3586
+ GCC_except_table3639
+ GCC_except_table3642
+ GCC_except_table3651
+ GCC_except_table3654
+ GCC_except_table3657
+ GCC_except_table3663
+ GCC_except_table3669
+ GCC_except_table3673
+ GCC_except_table3677
+ GCC_except_table3685
+ GCC_except_table3709
+ GCC_except_table3718
+ GCC_except_table3731
+ GCC_except_table3759
+ GCC_except_table3768
+ GCC_except_table3779
+ GCC_except_table3782
+ GCC_except_table3785
+ GCC_except_table3789
+ GCC_except_table3792
+ GCC_except_table3802
+ GCC_except_table3805
+ GCC_except_table3808
+ GCC_except_table381
+ GCC_except_table3812
+ GCC_except_table3815
+ GCC_except_table3818
+ GCC_except_table382
+ GCC_except_table3828
+ GCC_except_table3832
+ GCC_except_table3846
+ GCC_except_table3849
+ GCC_except_table3918
+ GCC_except_table3919
+ GCC_except_table3920
+ GCC_except_table3922
+ GCC_except_table3924
+ GCC_except_table3926
+ GCC_except_table3927
+ GCC_except_table3929
+ GCC_except_table3932
+ GCC_except_table3958
+ GCC_except_table3963
+ GCC_except_table3970
+ GCC_except_table3975
+ GCC_except_table402
+ GCC_except_table406
+ GCC_except_table415
+ GCC_except_table428
+ GCC_except_table484
+ GCC_except_table489
+ GCC_except_table492
+ GCC_except_table495
+ GCC_except_table498
+ GCC_except_table501
+ GCC_except_table504
+ GCC_except_table507
+ GCC_except_table510
+ GCC_except_table513
+ GCC_except_table517
+ GCC_except_table521
+ GCC_except_table524
+ GCC_except_table528
+ GCC_except_table532
+ GCC_except_table538
+ GCC_except_table541
+ GCC_except_table549
+ GCC_except_table552
+ GCC_except_table555
+ GCC_except_table562
+ GCC_except_table618
+ GCC_except_table680
+ GCC_except_table712
+ GCC_except_table717
+ GCC_except_table729
+ GCC_except_table742
+ GCC_except_table778
+ GCC_except_table783
+ GCC_except_table787
+ GCC_except_table820
+ GCC_except_table848
+ GCC_except_table852
+ GCC_except_table893
+ GCC_except_table895
+ GCC_except_table912
+ GCC_except_table934
+ GCC_except_table938
+ GCC_except_table955
+ _OBJC_CLASS_$_AKAccountManager
+ _OBJC_IVAR_$_PLAppPrivateData._wasNewlyCreated
+ _OBJC_IVAR_$_PLLazyObject._invalidated
+ _PLGetSandboxExtensionTokenCanonical
+ _PLGetSandboxExtensionTokenForProcessCanonical
+ _PLIsChinaAccount
+ _PLIsErrorOrUnderlyingErrorDatalessMaterializationPrevented
+ _PLNoFollowPath
+ _PLPlatformBackgroundSearchIndexingSupported
+ _PLPlatformVisualIntelligenceSyncSupported
+ _PLVettedResourcePath
+ _SANDBOX_EXTENSION_CANONICAL
+ ___104-[PLAssetsdLibraryInternalClient getSearchDonationProgressShouldCompute:shouldReport:completionHandler:]_block_invoke
+ ___107-[PLAssetsdLibraryInternalClient transferAssetsWithUuids:fromLibraryURL:transferOptions:completionHandler:]_block_invoke
+ ___108-[PLAssetsdLibraryInternalClient transferPersonsWithUuids:fromLibraryURL:transferOptions:completionHandler:]_block_invoke
+ ___109-[PLAssetsdLibraryInternalClient migrateLimitedLibraryAccessFromApplication:toApplication:completionHandler:]_block_invoke
+ ___109-[PLAssetsdLibraryInternalClient migrateLimitedLibraryAccessFromApplication:toApplication:completionHandler:]_block_invoke_2
+ ___143-[PLAssetsdCloudInternalClient updateAccessRequestForParticipantWithUUID:toAcceptanceStatus:inCollectionShareWithIdentifier:completionHandler:]_block_invoke
+ ___23-[PLLazyObject isValid]_block_invoke
+ ___30-[PLLazyObject wasInvalidated]_block_invoke
+ ___39-[PLLibraryServicesStateNode terminate]_block_invoke
+ ___52+[PLSecurity isEntitledForPrivatePhotosTCCForToken:]_block_invoke
+ ___56-[PLAssetsdNonBindingDebugClient stateCaptureDictionary]_block_invoke
+ ___block_descriptor_112_e8_32s40s48bs56n18_8_8_t0w1_s8_t16w32_e51_v16?0"<PLAssetsdLibraryInternalServiceProtocol>"8l
+ ___block_descriptor_120_e8_32s40s48bs56n18_8_8_t0w1_s8_t16w32_e49_v16?0"<PLAssetsdCloudInternalServiceProtocol>"8l
+ ___block_descriptor_98_e8_32bs40n18_8_8_t0w1_s8_t16w32_e51_v16?0"<PLAssetsdLibraryInternalServiceProtocol>"8l
+ _fchmodat
+ _sLibraryURLsCreatedThisLaunch
+ _sLibraryURLsCreatedThisLaunchLock
+ _sandbox_check_by_audit_token
- -[PLAssetsdLibraryClient transferAssetsWithUuids:fromLibraryURL:transferOptions:completionHandler:]
- -[PLAssetsdLibraryClient transferPersonsWithUuids:fromLibraryURL:transferOptions:completionHandler:]
- -[PLPhotoLibraryPathManagerCore assetUUIDRecoveryMappingPath]
- -[PLPhotoLibraryPathManagerCore postInit]
- -[PLPhotoLibraryPathManagerCore setAssetUUIDRecoveryMappingPath:]
- GCC_except_table1017
- GCC_except_table1053
- GCC_except_table1117
- GCC_except_table1119
- GCC_except_table1453
- GCC_except_table1468
- GCC_except_table1477
- GCC_except_table1594
- GCC_except_table1617
- GCC_except_table1622
- GCC_except_table1659
- GCC_except_table1675
- GCC_except_table1701
- GCC_except_table1709
- GCC_except_table1712
- GCC_except_table1715
- GCC_except_table1718
- GCC_except_table1721
- GCC_except_table1724
- GCC_except_table1727
- GCC_except_table1730
- GCC_except_table1733
- GCC_except_table1737
- GCC_except_table1743
- GCC_except_table1746
- GCC_except_table1749
- GCC_except_table1760
- GCC_except_table1763
- GCC_except_table1766
- GCC_except_table1769
- GCC_except_table1772
- GCC_except_table1775
- GCC_except_table1778
- GCC_except_table1781
- GCC_except_table1785
- GCC_except_table1792
- GCC_except_table1795
- GCC_except_table1798
- GCC_except_table1801
- GCC_except_table1804
- GCC_except_table1825
- GCC_except_table1833
- GCC_except_table1841
- GCC_except_table1942
- GCC_except_table1961
- GCC_except_table1965
- GCC_except_table2125
- GCC_except_table2175
- GCC_except_table2180
- GCC_except_table2181
- GCC_except_table2183
- GCC_except_table2186
- GCC_except_table2326
- GCC_except_table2414
- GCC_except_table2454
- GCC_except_table2488
- GCC_except_table2493
- GCC_except_table2496
- GCC_except_table2499
- GCC_except_table2502
- GCC_except_table2505
- GCC_except_table2537
- GCC_except_table2544
- GCC_except_table257
- GCC_except_table2579
- GCC_except_table2583
- GCC_except_table2587
- GCC_except_table2590
- GCC_except_table2598
- GCC_except_table2601
- GCC_except_table2605
- GCC_except_table2609
- GCC_except_table2613
- GCC_except_table2616
- GCC_except_table2618
- GCC_except_table262
- GCC_except_table2622
- GCC_except_table2626
- GCC_except_table2630
- GCC_except_table265
- GCC_except_table2677
- GCC_except_table2681
- GCC_except_table2685
- GCC_except_table2689
- GCC_except_table269
- GCC_except_table2693
- GCC_except_table2704
- GCC_except_table2707
- GCC_except_table2710
- GCC_except_table2725
- GCC_except_table2729
- GCC_except_table274
- GCC_except_table2752
- GCC_except_table2754
- GCC_except_table2759
- GCC_except_table2760
- GCC_except_table2762
- GCC_except_table2771
- GCC_except_table2783
- GCC_except_table2786
- GCC_except_table2792
- GCC_except_table2795
- GCC_except_table2798
- GCC_except_table280
- GCC_except_table2801
- GCC_except_table2804
- GCC_except_table2807
- GCC_except_table2810
- GCC_except_table283
- GCC_except_table2868
- GCC_except_table288
- GCC_except_table291
- GCC_except_table2935
- GCC_except_table2938
- GCC_except_table296
- GCC_except_table299
- GCC_except_table2995
- GCC_except_table302
- GCC_except_table3049
- GCC_except_table3060
- GCC_except_table3062
- GCC_except_table3066
- GCC_except_table3068
- GCC_except_table3087
- GCC_except_table3095
- GCC_except_table311
- GCC_except_table317
- GCC_except_table323
- GCC_except_table3248
- GCC_except_table3250
- GCC_except_table3252
- GCC_except_table3256
- GCC_except_table326
- GCC_except_table3261
- GCC_except_table3264
- GCC_except_table3267
- GCC_except_table3273
- GCC_except_table329
- GCC_except_table332
- GCC_except_table335
- GCC_except_table3358
- GCC_except_table3483
- GCC_except_table3550
- GCC_except_table3554
- GCC_except_table3561
- GCC_except_table3614
- GCC_except_table3617
- GCC_except_table3623
- GCC_except_table3626
- GCC_except_table3629
- GCC_except_table3632
- GCC_except_table3638
- GCC_except_table3644
- GCC_except_table3652
- GCC_except_table3656
- GCC_except_table3660
- GCC_except_table3684
- GCC_except_table3693
- GCC_except_table3724
- GCC_except_table3732
- GCC_except_table3734
- GCC_except_table3739
- GCC_except_table3743
- GCC_except_table3754
- GCC_except_table3760
- GCC_except_table3767
- GCC_except_table3777
- GCC_except_table3780
- GCC_except_table3783
- GCC_except_table3787
- GCC_except_table3790
- GCC_except_table3793
- GCC_except_table3796
- GCC_except_table3803
- GCC_except_table3807
- GCC_except_table383
- GCC_except_table384
- GCC_except_table3868
- GCC_except_table3891
- GCC_except_table3892
- GCC_except_table3895
- GCC_except_table3897
- GCC_except_table3899
- GCC_except_table3900
- GCC_except_table3902
- GCC_except_table3905
- GCC_except_table3906
- GCC_except_table3915
- GCC_except_table3928
- GCC_except_table3940
- GCC_except_table404
- GCC_except_table408
- GCC_except_table417
- GCC_except_table430
- GCC_except_table486
- GCC_except_table491
- GCC_except_table494
- GCC_except_table497
- GCC_except_table500
- GCC_except_table503
- GCC_except_table506
- GCC_except_table509
- GCC_except_table512
- GCC_except_table515
- GCC_except_table519
- GCC_except_table523
- GCC_except_table526
- GCC_except_table530
- GCC_except_table534
- GCC_except_table540
- GCC_except_table543
- GCC_except_table551
- GCC_except_table554
- GCC_except_table557
- GCC_except_table565
- GCC_except_table621
- GCC_except_table683
- GCC_except_table715
- GCC_except_table726
- GCC_except_table744
- GCC_except_table748
- GCC_except_table781
- GCC_except_table786
- GCC_except_table817
- GCC_except_table847
- GCC_except_table851
- GCC_except_table894
- GCC_except_table896
- GCC_except_table913
- GCC_except_table933
- GCC_except_table937
- GCC_except_table956
- GCC_except_table958
- _OBJC_IVAR_$_PLPhotoLibraryPathManagerCore._assetUUIDRecoveryMappingPath
- _PLAssetUUIDRecoveryMappingFileName
- _PLIsSharedCollectionsFeatureEnabled
- _PUTGetCurrentAccess
- ___100-[PLAssetsdLibraryClient transferPersonsWithUuids:fromLibraryURL:transferOptions:completionHandler:]_block_invoke
- ___62+[PLSecurity isEntitledForPhotoKitOrPrivatePhotosTCCForToken:]_block_invoke
- ___99-[PLAssetsdLibraryClient transferAssetsWithUuids:fromLibraryURL:transferOptions:completionHandler:]_block_invoke
CStrings:
+ "-[PLAssetsdLibraryInternalClient getSearchDonationProgressShouldCompute:shouldReport:completionHandler:]_block_invoke"
+ "-[PLAssetsdNonBindingDebugClient stateCaptureDictionary]_block_invoke"
+ "/.nofollow"
+ "Added owner read and write permission to %@ (was %o)"
+ "CN"
+ "Failed to add owner read and write permission to %@ (%{public}s)."
+ "PLFileBackedLogger: Failed to open log file at %@. Error: %@"
+ "PLFileBackedLogger: close url backed logger: %@"
+ "PLFileBackedLogger: open url backed logger: %@"
+ "PLFileBackedLogger: open url found a corrupt log file. Attempting repair for: %@"
+ "PLPhotosErrorCollectionShareNotEnabled"
+ "PLXPC Client: getSearchDonationProgressShouldCompute:shouldReport:completionHandler:"
+ "PLXPC Client: migrateLimitedLibraryAccessFromApplication:toApplication:completionHandler:"
+ "PLXPC Client: stateCaptureDictionary"
+ "PLXPC Client: updateAccessRequestForParticipantWithUUID:toAcceptanceStatus:inCollectionShareWithIdentifier:completionHandler:"
+ "Refusing to change permissions of symlink %@"
+ "Refusing to map '%@': redirected or non-regular."
+ "Unable to open file %@ to save extended attributes (%{public}s)."
+ "Unable to update access request (%@)"
+ "Unable to update access request for participant in collection share with identifier: %@. (%@)"
+ "XCTestCase"
+ "newBundleIdentifier"
+ "oldBundleIdentifier"
+ "\x86"
- "PLFileBackedLogger: Failed to open log file. Error: %@"
- "PLFileBackedLogger: close url backed logger: %{public}@"
- "PLFileBackedLogger: open url backed logger: %{public}@"
- "PLFileBackedLogger: open url found a corrupt log file. Attempting repair for: %{public}@"
- "Unable to open file to save extended attributes (%{public}s)."
- "XCTestProbe"
- "assetUUIDForPath.plist"
- "\x87"
```
