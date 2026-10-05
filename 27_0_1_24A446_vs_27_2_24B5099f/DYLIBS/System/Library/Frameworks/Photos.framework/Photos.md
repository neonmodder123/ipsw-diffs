## Photos

> `/System/Library/Frameworks/Photos.framework/Photos`

```diff

-912.1.131.0.0
-  __TEXT.__text: 0x2e3c10
-  __TEXT.__objc_methlist: 0x26f6c
-  __TEXT.__const: 0x17e0
+916.51.202.0.0
+  __TEXT.__text: 0x2e7d10
+  __TEXT.__objc_methlist: 0x271fc
+  __TEXT.__const: 0x1868
   __TEXT.__dlopen_cstrs: 0x280
-  __TEXT.__constg_swiftt: 0x67c
-  __TEXT.__swift5_typeref: 0x547
+  __TEXT.__constg_swiftt: 0x660
+  __TEXT.__swift5_typeref: 0x5ab
   __TEXT.__swift5_builtin: 0x3c
-  __TEXT.__swift5_reflstr: 0x191
-  __TEXT.__swift5_fieldmd: 0x23c
-  __TEXT.__swift5_assocty: 0xd0
-  __TEXT.__swift5_proto: 0x4c
-  __TEXT.__swift5_types: 0x44
+  __TEXT.__swift5_reflstr: 0x1a1
+  __TEXT.__swift5_fieldmd: 0x220
+  __TEXT.__swift5_assocty: 0x108
+  __TEXT.__swift5_proto: 0x48
+  __TEXT.__swift5_types: 0x40
   __TEXT.__swift5_capture: 0x198
-  __TEXT.__cstring: 0x33122
+  __TEXT.__cstring: 0x33c05
   __TEXT.__swift_as_entry: 0x10
   __TEXT.__swift_as_ret: 0x10
   __TEXT.__swift_as_cont: 0x18
-  __TEXT.__oslogstring: 0x24831
+  __TEXT.__oslogstring: 0x250b6
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__gcc_except_tab: 0x985c
+  __TEXT.__gcc_except_tab: 0x9804
   __TEXT.__ustring: 0x1e
-  __TEXT.__unwind_info: 0x97e0
+  __TEXT.__unwind_info: 0x98f8
   __TEXT.__eh_frame: 0x4d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x90f0
-  __DATA_CONST.__objc_classlist: 0xf40
+  __DATA_CONST.__const: 0x9140
+  __DATA_CONST.__objc_classlist: 0xf60
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x300
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x14900
+  __DATA_CONST.__objc_selrefs: 0x14aa0
   __DATA_CONST.__objc_protorefs: 0x40
-  __DATA_CONST.__objc_superrefs: 0xc60
+  __DATA_CONST.__objc_superrefs: 0xc78
   __DATA_CONST.__objc_arraydata: 0x940
-  __DATA_CONST.__got: 0x2a40
-  __AUTH_CONST.__const: 0x4778
-  __AUTH_CONST.__cfstring: 0x2da60
-  __AUTH_CONST.__objc_const: 0x42728
-  __AUTH_CONST.__objc_intobj: 0x24f0
+  __DATA_CONST.__got: 0x2ac0
+  __AUTH_CONST.__const: 0x4770
+  __AUTH_CONST.__cfstring: 0x2db40
+  __AUTH_CONST.__objc_const: 0x42d70
+  __AUTH_CONST.__objc_intobj: 0x2508
   __AUTH_CONST.__objc_arrayobj: 0x7b0
-  __AUTH_CONST.__objc_doubleobj: 0x140
+  __AUTH_CONST.__objc_doubleobj: 0x150
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x1918
-  __AUTH.__objc_data: 0x7e38
+  __AUTH_CONST.__auth_got: 0x1948
+  __AUTH.__objc_data: 0x78e8
   __AUTH.__data: 0x3c0
-  __DATA.__objc_ivar: 0x3638
-  __DATA.__data: 0x2c18
+  __DATA.__objc_ivar: 0x3670
+  __DATA.__data: 0x2c28
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x1a68
+  __DATA.__bss: 0x1a08
   __DATA.__common: 0x55
-  __DATA_DIRTY.__objc_data: 0x1a60
+  __DATA_DIRTY.__objc_data: 0x20f0
   __DATA_DIRTY.__data: 0x148
-  __DATA_DIRTY.__bss: 0x120
+  __DATA_DIRTY.__bss: 0x100
   - /System/Library/Frameworks/AVFAudio.framework/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/AVFoundation
   - /System/Library/Frameworks/Accounts.framework/Accounts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 15026
-  Symbols:   26084
-  CStrings:  8957
+  Functions: 15116
+  Symbols:   26211
+  CStrings:  9004
 
Symbols:
+ +[PHAssetCreationRequest _originalResourceTypeFromAdjustedResourceType:sourceAssetIsLoopingVideo:sourceAssetIsVideo:flattenLivePhoto:]
+ +[PHAssetExportRequest _provenanceRenderURLToShareForAsset:options:fileURLs:]
+ +[PHAssetExportRequest _shouldCombineProvenanceIntoRenderForAsset:options:fileURLs:]
+ +[PHAssetResource _publicMediaDerivativeResourcesFromResources:]
+ +[PHAssetResource assetResourcesForAsset:resourceTypeGroups:]
+ +[PHAssetResource fetchAssetResourcesForAssets:resourceTypeGroups:]
+ +[PHAssetResource fetchAssetResourcesForAssetsArray:resourceTypeGroups:]
+ +[PHAssetResource resources:matchingTypeGroups:]
+ +[PHAssetResourceFetchResult fetchResultWithAssets:resourceTypeGroups:]
+ +[PHCloudFeedEntry fetchEntriesInCollectionShare:filter:earliestDate:options:]
+ +[PHPerson(VisionService) cancelPersonSuggestionsOperationWithId:inPhotoLibrary:]
+ +[PHPhotoLibrary angelPhotoLibrary]
+ +[PHPhotoLibrary setAngelPhotoLibrary:error:]
+ +[PHQuery queryForEntriesInCollectionShare:filter:earliestDate:options:]
+ +[PHResourceLocalAvailabilityRequest _shouldAddOriginalAsProvenanceSourceForAsset:shouldStripProvenance:]
+ +[PHSearch ocrTextLinesForAssetUUID:inPhotoLibrary:includeLowConfidenceText:]
+ +[PHSensitiveContentAnalysisUtility sensitiveContentStateForAsset:]
+ +[PHShareCommentChangeRequest changeRequestForShareComment:]
+ -[PHAsset fetchProcessedProvenanceReplacementWithOptions:]
+ -[PHAssetCreationRequest _creationOptionsPreservingOriginalProvenanceFilenameForResource:]
+ -[PHAssetCreationRequest _shouldCopyLocationDataFromSourceAsset]
+ -[PHAssetCreationRequestBridge _shouldStashCameraJobs]
+ -[PHAssetCreationRequestBridge _stashBatchCameraJobIfNeeded:]
+ -[PHAssetCreationRequestBridge _stashCameraJobIfNeeded:]
+ -[PHAssetCreationRequestPlaceholderSupport _directUploadShareAssetAfterResourceDownloadInPhotoLibrary:]
+ -[PHAssetCreationRequestPlaceholderSupport _retrieveSharedStreamResourcesForSourceAsset:photoLibrary:]
+ -[PHAssetCreationRequestPlaceholderSupport _updateManagedAssetAfterResourceDownload:preservePlaceholderForRetry:]
+ -[PHAssetExportRequestOptions forceRatingMetadataBaking]
+ -[PHAssetExportRequestOptions setForceRatingMetadataBaking:]
+ -[PHAssetExportRequestOptions setShouldExportTitle:]
+ -[PHAssetExportRequestOptions setShouldStripRating:]
+ -[PHAssetExportRequestOptions shouldExportTitle]
+ -[PHAssetExportRequestOptions shouldStripRating]
+ -[PHAssetResource prefetchedMediaMetadata]
+ -[PHAssetResource setPrefetchedMediaMetadata:]
+ -[PHAssetResourceFetchResult initWithAssets:resourceTypeGroups:]
+ -[PHAssetResourceFetchResult typeGroups]
+ -[PHCollectionShare _updateAccessRequestForParticipant:toAcceptanceStatus:completion:]
+ -[PHCollectionShare approveAccessRequestForParticipant:completion:]
+ -[PHCollectionShare blockAccessRequestForParticipant:completion:]
+ -[PHCollectionShare denyAccessRequestForParticipant:completion:]
+ -[PHCollectionShare unblockAccessRequestForParticipant:completion:]
+ -[PHFindQueryContext fetchLexemeIDs]
+ -[PHImportAsset rating]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator .cxx_destruct]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator _initializeCPLStatus]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator _processCPLStatusDidChange]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator _publishCloudStatusUpdate:]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator _resetCPLStatus]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator _setupLazyCPLStatusIfNecessary]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator _startObservingCloudPauseNotificationIfNecessary]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator _stopObservingCloudPauseNotification]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator dealloc]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator getCloudStatusWithCompletionHandler:]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator initWithPhotoLibrary:]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator invalidate]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator isWalrusEnabled]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator registerObserver:]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator reset]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator statusDidChange:]
+ -[PHPhotoLibraryCloudStatusObserverCoordinator unregisterObserver:]
+ -[PHPrefetchedMediaMetadata .cxx_destruct]
+ -[PHPrefetchedMediaMetadata data]
+ -[PHPrefetchedMediaMetadata initWithData:type:]
+ -[PHPrefetchedMediaMetadata type]
+ -[PHResourceChooserListResourceInfo isNonRawImage]
+ -[PHResourceRequestReplyGuard deliverOnce:]
+ -[PHResourceRequestReplyGuard hasDelivered]
+ -[PHServerResourceRequestRunner _newProgressWithReplyOnCancellation:]
+ -[PHShareComment isEdited]
+ -[PHShareComment lastEditedDate]
+ -[PHShareCommentChangeRequest .cxx_destruct]
+ -[PHShareCommentChangeRequest applyMutationsToManagedObject:photoLibrary:error:]
+ -[PHShareCommentChangeRequest commentText]
+ -[PHShareCommentChangeRequest encodeToXPCDict:]
+ -[PHShareCommentChangeRequest initWithUUID:objectID:]
+ -[PHShareCommentChangeRequest initWithXPCDict:request:clientAuthorization:]
+ -[PHShareCommentChangeRequest managedEntityName]
+ -[PHShareCommentChangeRequest setCommentText:]
+ -[PHShareParticipantChangeRequest setAcceptanceStatusForTesting:]
+ -[PHSharePost isEdited]
+ -[PHSharePost lastEditedDate]
+ -[PHSharePostChangeRequest applyMutationsToManagedObject:photoLibrary:error:]
+ GCC_except_table10053
+ GCC_except_table1009
+ GCC_except_table10144
+ GCC_except_table10266
+ GCC_except_table10276
+ GCC_except_table10290
+ GCC_except_table10291
+ GCC_except_table10331
+ GCC_except_table10341
+ GCC_except_table10417
+ GCC_except_table10418
+ GCC_except_table10419
+ GCC_except_table10420
+ GCC_except_table10421
+ GCC_except_table10422
+ GCC_except_table10423
+ GCC_except_table10424
+ GCC_except_table10425
+ GCC_except_table10426
+ GCC_except_table10427
+ GCC_except_table10428
+ GCC_except_table10429
+ GCC_except_table10430
+ GCC_except_table10431
+ GCC_except_table10432
+ GCC_except_table10433
+ GCC_except_table10434
+ GCC_except_table10435
+ GCC_except_table10436
+ GCC_except_table10437
+ GCC_except_table10438
+ GCC_except_table10439
+ GCC_except_table10440
+ GCC_except_table10441
+ GCC_except_table10442
+ GCC_except_table10562
+ GCC_except_table10563
+ GCC_except_table10564
+ GCC_except_table10565
+ GCC_except_table10566
+ GCC_except_table10567
+ GCC_except_table10568
+ GCC_except_table10579
+ GCC_except_table10597
+ GCC_except_table1061
+ GCC_except_table10630
+ GCC_except_table10631
+ GCC_except_table10632
+ GCC_except_table10633
+ GCC_except_table10634
+ GCC_except_table10662
+ GCC_except_table10663
+ GCC_except_table10664
+ GCC_except_table10665
+ GCC_except_table10666
+ GCC_except_table10667
+ GCC_except_table10668
+ GCC_except_table10669
+ GCC_except_table10670
+ GCC_except_table10671
+ GCC_except_table10708
+ GCC_except_table10709
+ GCC_except_table10713
+ GCC_except_table10733
+ GCC_except_table10738
+ GCC_except_table10820
+ GCC_except_table1088
+ GCC_except_table10913
+ GCC_except_table1092
+ GCC_except_table1101
+ GCC_except_table1103
+ GCC_except_table11081
+ GCC_except_table11100
+ GCC_except_table11104
+ GCC_except_table11130
+ GCC_except_table11132
+ GCC_except_table11222
+ GCC_except_table11250
+ GCC_except_table11784
+ GCC_except_table11944
+ GCC_except_table11950
+ GCC_except_table11958
+ GCC_except_table11962
+ GCC_except_table11964
+ GCC_except_table11968
+ GCC_except_table11974
+ GCC_except_table12080
+ GCC_except_table12100
+ GCC_except_table12102
+ GCC_except_table12104
+ GCC_except_table12106
+ GCC_except_table12141
+ GCC_except_table12190
+ GCC_except_table12197
+ GCC_except_table12199
+ GCC_except_table12201
+ GCC_except_table12207
+ GCC_except_table12244
+ GCC_except_table1237
+ GCC_except_table12375
+ GCC_except_table12401
+ GCC_except_table12413
+ GCC_except_table12455
+ GCC_except_table12457
+ GCC_except_table12470
+ GCC_except_table1253
+ GCC_except_table12575
+ GCC_except_table12579
+ GCC_except_table12620
+ GCC_except_table12624
+ GCC_except_table12633
+ GCC_except_table12634
+ GCC_except_table12641
+ GCC_except_table12679
+ GCC_except_table12686
+ GCC_except_table12698
+ GCC_except_table12703
+ GCC_except_table12753
+ GCC_except_table1280
+ GCC_except_table12845
+ GCC_except_table12848
+ GCC_except_table12854
+ GCC_except_table12856
+ GCC_except_table12896
+ GCC_except_table12915
+ GCC_except_table12926
+ GCC_except_table12988
+ GCC_except_table12991
+ GCC_except_table12999
+ GCC_except_table13005
+ GCC_except_table13007
+ GCC_except_table13072
+ GCC_except_table13150
+ GCC_except_table13154
+ GCC_except_table13158
+ GCC_except_table13195
+ GCC_except_table13220
+ GCC_except_table13227
+ GCC_except_table13367
+ GCC_except_table13380
+ GCC_except_table13474
+ GCC_except_table13541
+ GCC_except_table13747
+ GCC_except_table13826
+ GCC_except_table13868
+ GCC_except_table1389
+ GCC_except_table13927
+ GCC_except_table13947
+ GCC_except_table13990
+ GCC_except_table13992
+ GCC_except_table14005
+ GCC_except_table14007
+ GCC_except_table14009
+ GCC_except_table14028
+ GCC_except_table14174
+ GCC_except_table14185
+ GCC_except_table14212
+ GCC_except_table14218
+ GCC_except_table14234
+ GCC_except_table14304
+ GCC_except_table14306
+ GCC_except_table14352
+ GCC_except_table14354
+ GCC_except_table14381
+ GCC_except_table14385
+ GCC_except_table14386
+ GCC_except_table14398
+ GCC_except_table14415
+ GCC_except_table14418
+ GCC_except_table14572
+ GCC_except_table1478
+ GCC_except_table1570
+ GCC_except_table1595
+ GCC_except_table1641
+ GCC_except_table1716
+ GCC_except_table1814
+ GCC_except_table1915
+ GCC_except_table1919
+ GCC_except_table1939
+ GCC_except_table1944
+ GCC_except_table1948
+ GCC_except_table1958
+ GCC_except_table2149
+ GCC_except_table2153
+ GCC_except_table2155
+ GCC_except_table2157
+ GCC_except_table2159
+ GCC_except_table2161
+ GCC_except_table2163
+ GCC_except_table2166
+ GCC_except_table2173
+ GCC_except_table2175
+ GCC_except_table2177
+ GCC_except_table2189
+ GCC_except_table2221
+ GCC_except_table2223
+ GCC_except_table2225
+ GCC_except_table2227
+ GCC_except_table2229
+ GCC_except_table2231
+ GCC_except_table2233
+ GCC_except_table2245
+ GCC_except_table2247
+ GCC_except_table2249
+ GCC_except_table2254
+ GCC_except_table2256
+ GCC_except_table2258
+ GCC_except_table2260
+ GCC_except_table2262
+ GCC_except_table2265
+ GCC_except_table2267
+ GCC_except_table2270
+ GCC_except_table2272
+ GCC_except_table2274
+ GCC_except_table2302
+ GCC_except_table2304
+ GCC_except_table2307
+ GCC_except_table2310
+ GCC_except_table2419
+ GCC_except_table2424
+ GCC_except_table2439
+ GCC_except_table2451
+ GCC_except_table2489
+ GCC_except_table2660
+ GCC_except_table2673
+ GCC_except_table2701
+ GCC_except_table2716
+ GCC_except_table2735
+ GCC_except_table2745
+ GCC_except_table2783
+ GCC_except_table2788
+ GCC_except_table2850
+ GCC_except_table2953
+ GCC_except_table2964
+ GCC_except_table2966
+ GCC_except_table2972
+ GCC_except_table2980
+ GCC_except_table3012
+ GCC_except_table3090
+ GCC_except_table3095
+ GCC_except_table3103
+ GCC_except_table3112
+ GCC_except_table3124
+ GCC_except_table3130
+ GCC_except_table3135
+ GCC_except_table3258
+ GCC_except_table3262
+ GCC_except_table3265
+ GCC_except_table3332
+ GCC_except_table3340
+ GCC_except_table3375
+ GCC_except_table3379
+ GCC_except_table3384
+ GCC_except_table3512
+ GCC_except_table3549
+ GCC_except_table3555
+ GCC_except_table3558
+ GCC_except_table3572
+ GCC_except_table3578
+ GCC_except_table3581
+ GCC_except_table3586
+ GCC_except_table3590
+ GCC_except_table3601
+ GCC_except_table3606
+ GCC_except_table3617
+ GCC_except_table3618
+ GCC_except_table3635
+ GCC_except_table3644
+ GCC_except_table3741
+ GCC_except_table3747
+ GCC_except_table3768
+ GCC_except_table3770
+ GCC_except_table3772
+ GCC_except_table3819
+ GCC_except_table3847
+ GCC_except_table3880
+ GCC_except_table3898
+ GCC_except_table3900
+ GCC_except_table3903
+ GCC_except_table4066
+ GCC_except_table4100
+ GCC_except_table4110
+ GCC_except_table4125
+ GCC_except_table4128
+ GCC_except_table4130
+ GCC_except_table4163
+ GCC_except_table4168
+ GCC_except_table4169
+ GCC_except_table4436
+ GCC_except_table4443
+ GCC_except_table4474
+ GCC_except_table4500
+ GCC_except_table4505
+ GCC_except_table4510
+ GCC_except_table4521
+ GCC_except_table4525
+ GCC_except_table4547
+ GCC_except_table4560
+ GCC_except_table4561
+ GCC_except_table4621
+ GCC_except_table4946
+ GCC_except_table4956
+ GCC_except_table5018
+ GCC_except_table5020
+ GCC_except_table5024
+ GCC_except_table5026
+ GCC_except_table5029
+ GCC_except_table5099
+ GCC_except_table5104
+ GCC_except_table5134
+ GCC_except_table5264
+ GCC_except_table5268
+ GCC_except_table5625
+ GCC_except_table5657
+ GCC_except_table5704
+ GCC_except_table5723
+ GCC_except_table5729
+ GCC_except_table5735
+ GCC_except_table5749
+ GCC_except_table5775
+ GCC_except_table5783
+ GCC_except_table5785
+ GCC_except_table5792
+ GCC_except_table5801
+ GCC_except_table5805
+ GCC_except_table5814
+ GCC_except_table5818
+ GCC_except_table5890
+ GCC_except_table5895
+ GCC_except_table5919
+ GCC_except_table5923
+ GCC_except_table5927
+ GCC_except_table5949
+ GCC_except_table5957
+ GCC_except_table5971
+ GCC_except_table5974
+ GCC_except_table5977
+ GCC_except_table6000
+ GCC_except_table6050
+ GCC_except_table6059
+ GCC_except_table6101
+ GCC_except_table6133
+ GCC_except_table6136
+ GCC_except_table6142
+ GCC_except_table6146
+ GCC_except_table6157
+ GCC_except_table6188
+ GCC_except_table6217
+ GCC_except_table6244
+ GCC_except_table6246
+ GCC_except_table6260
+ GCC_except_table6330
+ GCC_except_table6408
+ GCC_except_table6413
+ GCC_except_table6418
+ GCC_except_table6576
+ GCC_except_table6579
+ GCC_except_table6593
+ GCC_except_table6618
+ GCC_except_table6628
+ GCC_except_table6631
+ GCC_except_table6670
+ GCC_except_table6707
+ GCC_except_table6709
+ GCC_except_table7109
+ GCC_except_table7129
+ GCC_except_table7142
+ GCC_except_table7174
+ GCC_except_table7205
+ GCC_except_table7208
+ GCC_except_table7210
+ GCC_except_table7212
+ GCC_except_table7214
+ GCC_except_table7223
+ GCC_except_table7271
+ GCC_except_table7285
+ GCC_except_table7323
+ GCC_except_table7325
+ GCC_except_table7364
+ GCC_except_table7617
+ GCC_except_table7620
+ GCC_except_table7642
+ GCC_except_table7667
+ GCC_except_table7668
+ GCC_except_table7669
+ GCC_except_table7670
+ GCC_except_table7671
+ GCC_except_table7672
+ GCC_except_table7683
+ GCC_except_table7684
+ GCC_except_table7685
+ GCC_except_table7842
+ GCC_except_table8061
+ GCC_except_table8124
+ GCC_except_table8125
+ GCC_except_table814
+ GCC_except_table815
+ GCC_except_table816
+ GCC_except_table817
+ GCC_except_table818
+ GCC_except_table8185
+ GCC_except_table820
+ GCC_except_table8207
+ GCC_except_table8211
+ GCC_except_table8218
+ GCC_except_table8272
+ GCC_except_table8478
+ GCC_except_table8480
+ GCC_except_table8527
+ GCC_except_table8571
+ GCC_except_table8573
+ GCC_except_table8575
+ GCC_except_table8587
+ GCC_except_table8592
+ GCC_except_table8632
+ GCC_except_table8660
+ GCC_except_table8702
+ GCC_except_table8796
+ GCC_except_table8854
+ GCC_except_table8874
+ GCC_except_table8877
+ GCC_except_table8896
+ GCC_except_table8955
+ GCC_except_table8963
+ GCC_except_table8964
+ GCC_except_table8965
+ GCC_except_table8966
+ GCC_except_table8967
+ GCC_except_table8969
+ GCC_except_table8971
+ GCC_except_table8975
+ GCC_except_table8986
+ GCC_except_table8989
+ GCC_except_table9010
+ GCC_except_table9054
+ GCC_except_table907
+ GCC_except_table9121
+ GCC_except_table9278
+ GCC_except_table9319
+ GCC_except_table9325
+ GCC_except_table9328
+ GCC_except_table9588
+ GCC_except_table9592
+ GCC_except_table9596
+ GCC_except_table9616
+ GCC_except_table9617
+ GCC_except_table9713
+ GCC_except_table9723
+ GCC_except_table9756
+ GCC_except_table9808
+ GCC_except_table9853
+ GCC_except_table9899
+ GCC_except_table9927
+ GCC_except_table9960
+ GCC_except_table9962
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _CFNotificationCenterRemoveObserver
+ _OBJC_CLASS_$_PHPhotoLibraryCloudStatusObserverCoordinator
+ _OBJC_CLASS_$_PHPrefetchedMediaMetadata
+ _OBJC_CLASS_$_PHResourceRequestReplyGuard
+ _OBJC_CLASS_$_PHShareCommentChangeRequest
+ _OBJC_CLASS_$_PLMediaMetadataVirtualResource
+ _OBJC_IVAR_$_PHAssetExportRequestOptions._forceRatingMetadataBaking
+ _OBJC_IVAR_$_PHAssetExportRequestOptions._shouldExportTitle
+ _OBJC_IVAR_$_PHAssetExportRequestOptions._shouldStripRating
+ _OBJC_IVAR_$_PHAssetResource._prefetchedMediaMetadata
+ _OBJC_IVAR_$_PHAssetResourceFetchResult._typeGroups
+ _OBJC_IVAR_$_PHPhotoLibrary._cloudStatusObserverCoordinator
+ _OBJC_IVAR_$_PHPhotoLibraryCloudStatusObserverCoordinator._cloudStatusHandlerQueue
+ _OBJC_IVAR_$_PHPhotoLibraryCloudStatusObserverCoordinator._cplStatusDelegateQueue
+ _OBJC_IVAR_$_PHPhotoLibraryCloudStatusObserverCoordinator._lazyCPLStatus
+ _OBJC_IVAR_$_PHPhotoLibraryCloudStatusObserverCoordinator._observerRegistrar
+ _OBJC_IVAR_$_PHPhotoLibraryCloudStatusObserverCoordinator._pauseLock
+ _OBJC_IVAR_$_PHPhotoLibraryCloudStatusObserverCoordinator._pauseLock_isObservingCloudPauseNotification
+ _OBJC_IVAR_$_PHPhotoLibraryCloudStatusObserverCoordinator._photoLibrary
+ _OBJC_IVAR_$_PHPrefetchedMediaMetadata._data
+ _OBJC_IVAR_$_PHPrefetchedMediaMetadata._type
+ _OBJC_IVAR_$_PHResourceRequestReplyGuard._delivered
+ _OBJC_IVAR_$_PHServerResourceRequestRunner._replyGuard
+ _OBJC_IVAR_$_PHShareComment._lastEditedDate
+ _OBJC_IVAR_$_PHShareCommentChangeRequest._commentText
+ _OBJC_IVAR_$_PHShareCommentChangeRequest._didSetCommentText
+ _OBJC_IVAR_$_PHSharePost._lastEditedDate
+ _OBJC_METACLASS_$_PHPhotoLibraryCloudStatusObserverCoordinator
+ _OBJC_METACLASS_$_PHPrefetchedMediaMetadata
+ _OBJC_METACLASS_$_PHResourceRequestReplyGuard
+ _OBJC_METACLASS_$_PHShareCommentChangeRequest
+ _PAMediaConversionErrorIsProvenanceProcessingError
+ _PFIsLockScreenCamera
+ _PHAssetExportRequestStarRatingMetadataOperationForAssetWithOptions
+ _PHAssetExportRequestTitleMetadataOperationForAssetWithOptions
+ _PHAssetOriginalStarRatingForAsset
+ _PHAssetOriginalTitleForAsset
+ _PHAssetResourceTypeGroupsIncludesTargetGroups
+ _PLCameraBundleId
+ _PLCloudPhotoLibraryPauseDidChangeNotification
+ _PLIsMediaanalysisd
+ __OBJC_$_CLASS_METHODS_PHShareCommentChangeRequest
+ __OBJC_$_CLASS_PROP_LIST_PHShareCommentChangeRequest
+ __OBJC_$_INSTANCE_METHODS_PHPhotoLibraryCloudStatusObserverCoordinator
+ __OBJC_$_INSTANCE_METHODS_PHPrefetchedMediaMetadata
+ __OBJC_$_INSTANCE_METHODS_PHResourceRequestReplyGuard
+ __OBJC_$_INSTANCE_METHODS_PHShareCommentChangeRequest
+ __OBJC_$_INSTANCE_VARIABLES_PHPhotoLibraryCloudStatusObserverCoordinator
+ __OBJC_$_INSTANCE_VARIABLES_PHPrefetchedMediaMetadata
+ __OBJC_$_INSTANCE_VARIABLES_PHResourceRequestReplyGuard
+ __OBJC_$_INSTANCE_VARIABLES_PHShareCommentChangeRequest
+ __OBJC_$_PROP_LIST_PHPhotoLibraryCloudStatusObserverCoordinator
+ __OBJC_$_PROP_LIST_PHPrefetchedMediaMetadata
+ __OBJC_$_PROP_LIST_PHResourceRequestReplyGuard
+ __OBJC_$_PROP_LIST_PHShareCommentChangeRequest
+ __OBJC_CLASS_PROTOCOLS_$_PHPhotoLibraryCloudStatusObserverCoordinator
+ __OBJC_CLASS_PROTOCOLS_$_PHShareCommentChangeRequest
+ __OBJC_CLASS_RO_$_PHPhotoLibraryCloudStatusObserverCoordinator
+ __OBJC_CLASS_RO_$_PHPrefetchedMediaMetadata
+ __OBJC_CLASS_RO_$_PHResourceRequestReplyGuard
+ __OBJC_CLASS_RO_$_PHShareCommentChangeRequest
+ __OBJC_METACLASS_RO_$_PHPhotoLibraryCloudStatusObserverCoordinator
+ __OBJC_METACLASS_RO_$_PHPrefetchedMediaMetadata
+ __OBJC_METACLASS_RO_$_PHResourceRequestReplyGuard
+ __OBJC_METACLASS_RO_$_PHShareCommentChangeRequest
+ __PLSafeEntityForNameInManagedObjectContext
+ ___102-[PHAssetCreationRequestPlaceholderSupport _retrieveSharedStreamResourcesForSourceAsset:photoLibrary:]_block_invoke
+ ___103-[PHAssetCreationRequestPlaceholderSupport _directUploadShareAssetAfterResourceDownloadInPhotoLibrary:]_block_invoke
+ ___103-[PHAssetCreationRequestPlaceholderSupport _directUploadShareAssetAfterResourceDownloadInPhotoLibrary:]_block_invoke_2
+ ___113-[PHAssetCreationRequestPlaceholderSupport _updateManagedAssetAfterResourceDownload:preservePlaceholderForRetry:]_block_invoke
+ ___142-[PHCloudSharedAssetExportRequest _requestFileURLsForAsset:withOptions:networkAccessAllowed:progressHandler:resultHandler:resultHandlerQueue:]_block_invoke
+ ___23-[PHImportAsset rating]_block_invoke
+ ___35+[PHPhotoLibrary angelPhotoLibrary]_block_invoke
+ ___45+[PHPhotoLibrary setAngelPhotoLibrary:error:]_block_invoke
+ ___53-[PHPhotoLibraryCloudStatusObserverCoordinator reset]_block_invoke
+ ___53-[PHPhotoLibraryCloudStatusObserverCoordinator reset]_block_invoke_2
+ ___58-[PHPhotoLibraryCloudStatusObserverCoordinator invalidate]_block_invoke
+ ___65-[PHPhotoLibraryCloudStatusObserverCoordinator registerObserver:]_block_invoke
+ ___69-[PHPhotoLibraryCloudStatusObserverCoordinator initWithPhotoLibrary:]_block_invoke
+ ___69-[PHPhotoLibraryCloudStatusObserverCoordinator initWithPhotoLibrary:]_block_invoke_2
+ ___69-[PHServerResourceRequestRunner _newProgressWithReplyOnCancellation:]_block_invoke
+ ___74-[PHPhotoLibraryCloudStatusObserverCoordinator _processCPLStatusDidChange]_block_invoke
+ ___74-[PHPhotoLibraryCloudStatusObserverCoordinator _publishCloudStatusUpdate:]_block_invoke
+ ___77+[PHSearch ocrTextLinesForAssetUUID:inPhotoLibrary:includeLowConfidenceText:]_block_invoke
+ ___77+[PHSearch ocrTextLinesForAssetUUID:inPhotoLibrary:includeLowConfidenceText:]_block_invoke_2
+ ___78+[PHCloudFeedEntry fetchEntriesInCollectionShare:filter:earliestDate:options:]_block_invoke
+ ___84-[PHPhotoLibraryCloudStatusObserverCoordinator _stopObservingCloudPauseNotification]_block_invoke
+ ___84-[PHPhotoLibraryCloudStatusObserverCoordinator getCloudStatusWithCompletionHandler:]_block_invoke
+ ___84-[PHPhotoLibraryCloudStatusObserverCoordinator getCloudStatusWithCompletionHandler:]_block_invoke_2
+ ___84-[PHPhotoLibraryCloudStatusObserverCoordinator getCloudStatusWithCompletionHandler:]_block_invoke_3
+ ___84-[PHPhotoLibraryCloudStatusObserverCoordinator getCloudStatusWithCompletionHandler:]_block_invoke_4
+ ___84-[PHPhotoLibraryCloudStatusObserverCoordinator getCloudStatusWithCompletionHandler:]_block_invoke_5
+ ___86-[PHCollectionShare _updateAccessRequestForParticipant:toAcceptanceStatus:completion:]_block_invoke
+ ___96-[PHPhotoLibraryCloudStatusObserverCoordinator _startObservingCloudPauseNotificationIfNecessary]_block_invoke
+ ___block_descriptor_40_e8_32w_e39_v24?0"PLCPLClientStatus"8"NSError"16lw32l8
+ ___block_descriptor_48_e8_32s40bs_e39_v24?0"PLCPLClientStatus"8"NSError"16ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48s_e20_v20?0i8"NSError"12ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56r_e17_v16?0"NSError"8ls32l8r56l8s40l8s48l8
+ ___block_descriptor_81_e8_32s40s48r56r64r72r_e5_v8?0lr48l8s32l8s40l8r56l8r64l8r72l8
+ ___block_descriptor_96_e8_32s40s48s56s64s72s80r88r_e24_v16?0"PLPhotoLibrary"8ls32l8r80l8s40l8r88l8s48l8s56l8s64l8s72l8
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ __cloudPauseDidChange
+ __fetchTypeForAssetCollectionLocalIdentifierCode.pl_once_object_36
+ __fetchTypeForAssetCollectionLocalIdentifierCode.pl_once_token_36
+ __simpleDeleteValidatorsWithManagedObjectContext:.pl_once_object_16
+ __simpleDeleteValidatorsWithManagedObjectContext:.pl_once_token_16
+ _allowedEntities.pl_once_object_81
+ _allowedEntities.pl_once_object_82
+ _allowedEntities.pl_once_token_81
+ _allowedEntities.pl_once_token_82
+ _analyticsPropertiesToFetch.pl_once_object_15
+ _analyticsPropertiesToFetch.pl_once_token_15
+ _angelPhotoLibrary
+ _angelPhotoLibraryLock
+ _associated conformance So26PHAssetResourceFetchResultCSl6Photos11SubSequenceSl_Sl
+ _associated conformance So26PHAssetResourceFetchResultCSl6Photos5IndexSl_SL
+ _associated conformance So26PHAssetResourceFetchResultCSl6Photos7IndicesSl_Sl
+ _associated conformance So26PHAssetResourceFetchResultCSl6PhotosST
+ _corePropertiesToFetch.pl_once_object_15
+ _corePropertiesToFetch.pl_once_token_15
+ _dateRangeTitleGenerator.pl_once_object_17
+ _dateRangeTitleGenerator.pl_once_token_17
+ _entityKeyMap.pl_once_object_15
+ _entityKeyMap.pl_once_object_16
+ _entityKeyMap.pl_once_token_15
+ _entityKeyMap.pl_once_token_16
+ _handleUnsupportedAssetCollectionFetchTypeForLocalIdentifier.pl_once_object_49
+ _handleUnsupportedAssetCollectionFetchTypeForLocalIdentifier.pl_once_token_49
+ _kPLImageWriterBatchImageDictionaries
+ _kPLImageWriterJobCompletionBlock
+ _kPLImageWriterJobTypeBatchImage
+ _kPLImageWriterPhotoDestinationPath
+ _kPLImageWriterPhotoIrisAssetUUID
+ _kPLImageWriterPreviewImageRef
+ _kPLImageWriterReplayedCameraJob
+ _kPLImageWriterVideoDestinationPath
+ _propertiesToFetch.pl_once_object_19
+ _propertiesToFetch.pl_once_object_23
+ _propertiesToFetch.pl_once_object_28
+ _propertiesToFetch.pl_once_token_19
+ _propertiesToFetch.pl_once_token_23
+ _propertiesToFetch.pl_once_token_28
+ _propertiesToFetchWithHint:.pl_once_object_15
+ _propertiesToFetchWithHint:.pl_once_token_15
+ _publicPHObjectChangeClasses.pl_once_object_29
+ _publicPHObjectChangeClasses.pl_once_token_29
+ _sharedLazyPhotoLibraryForCMM.pl_once_object_55
+ _sharedLazyPhotoLibraryForCMM.pl_once_token_55
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _symbolic $sSl
+ _symbolic SIySo26PHAssetResourceFetchResultCG
+ _symbolic _____ySo26PHAssetResourceFetchResultCG s5SliceV
+ _uniqueObjectIDCache.pl_once_object_80
+ _uniqueObjectIDCache.pl_once_token_80
- +[PHAssetCreationRequest _originalResourceTypeFromAdjustedResourceType:sourceAssetIsLoopingVideo:sourceAssetIsVideo:]
- +[PHAssetExportRequest _adjustedProvenanceRenderURLToShareForAsset:options:fileURLs:]
- +[PHAssetExportRequest _shouldCombineEditedProvenanceIntoRenderForAsset:options:fileURLs:]
- +[PHAssetResource resources:matchingTypeGroup:]
- +[PHAssetResourceFetchResult fetchResultWithAssets:resourceTypeGroup:]
- +[PHCloudFeedEntry fetchEntriesInCollectionShare:filter:options:]
- +[PHImportAsset scanAssetsForProvenanceData:atEnd:]
- +[PHPhotoLibrary imagePickerPhotoLibrary]
- +[PHPhotoLibrary setImagePickerPhotoLibrary:error:]
- +[PHQuery queryForEntriesInCollectionShare:filter:options:]
- +[PHResourceLocalAvailabilityRequest _shouldAddOriginalProvenanceResourceToResourcesToShareForAsset:shouldStripProvenance:]
- -[PHAssetCreationRequestPlaceholderSupport _updateManagedAssetAfterResourceDownload:]
- -[PHAssetResourceFetchResult initWithAssets:resourceTypeGroup:]
- -[PHAssetResourceFetchResult typeGroup]
- -[PHFindQueryContext fetchedLexemeIDs]
- -[PHImportAsset hasProvenanceMetadata]
- -[PHPhotoLibrary _addCloudStatusObservers:authorizationStatus:]
- -[PHPhotoLibrary _cachedCloudStatus]
- -[PHPhotoLibrary _initializeCPLStatus]
- -[PHPhotoLibrary _processCPLStatusDidChange]
- -[PHPhotoLibrary _publishCloudStatusUpdate:]
- -[PHPhotoLibrary _removeCloudStatusObserver:]
- -[PHPhotoLibrary _setCachedCloudStatus:]
- -[PHPhotoLibrary _setupLazyCPLStatusIfNecessary]
- -[PHPhotoLibrary statusDidChange:]
- -[PHServerResourceRequestRunner _safeReply:]
- -[PHShareParticipantChangeRequest approveAccessRequest]
- -[PHShareParticipantChangeRequest blockAccessRequest]
- -[PHShareParticipantChangeRequest denyAccessRequest]
- -[PHShareParticipantChangeRequest unblockAccessRequest]
- -[PHSharePost lastModifiedDate]
- GCC_except_table10027
- GCC_except_table10118
- GCC_except_table10240
- GCC_except_table10250
- GCC_except_table10264
- GCC_except_table10265
- GCC_except_table10272
- GCC_except_table10275
- GCC_except_table10299
- GCC_except_table10300
- GCC_except_table10302
- GCC_except_table10303
- GCC_except_table10304
- GCC_except_table10305
- GCC_except_table10308
- GCC_except_table10309
- GCC_except_table10310
- GCC_except_table10311
- GCC_except_table10312
- GCC_except_table10313
- GCC_except_table10314
- GCC_except_table10315
- GCC_except_table10317
- GCC_except_table10318
- GCC_except_table10319
- GCC_except_table10320
- GCC_except_table10321
- GCC_except_table10322
- GCC_except_table10323
- GCC_except_table10332
- GCC_except_table10333
- GCC_except_table10342
- GCC_except_table10357
- GCC_except_table10367
- GCC_except_table1044
- GCC_except_table10527
- GCC_except_table10536
- GCC_except_table10537
- GCC_except_table10538
- GCC_except_table10539
- GCC_except_table10540
- GCC_except_table10541
- GCC_except_table10542
- GCC_except_table10571
- GCC_except_table10604
- GCC_except_table10605
- GCC_except_table10606
- GCC_except_table10607
- GCC_except_table10608
- GCC_except_table10618
- GCC_except_table10636
- GCC_except_table10637
- GCC_except_table10638
- GCC_except_table10639
- GCC_except_table10640
- GCC_except_table10641
- GCC_except_table10642
- GCC_except_table10643
- GCC_except_table10645
- GCC_except_table10682
- GCC_except_table10683
- GCC_except_table10687
- GCC_except_table10706
- GCC_except_table1071
- GCC_except_table10711
- GCC_except_table1075
- GCC_except_table10793
- GCC_except_table1084
- GCC_except_table1086
- GCC_except_table10886
- GCC_except_table11054
- GCC_except_table11073
- GCC_except_table11076
- GCC_except_table11077
- GCC_except_table11105
- GCC_except_table11195
- GCC_except_table11223
- GCC_except_table11757
- GCC_except_table11914
- GCC_except_table11917
- GCC_except_table11923
- GCC_except_table11931
- GCC_except_table11935
- GCC_except_table11937
- GCC_except_table11947
- GCC_except_table12053
- GCC_except_table12073
- GCC_except_table12075
- GCC_except_table12077
- GCC_except_table12079
- GCC_except_table12114
- GCC_except_table12163
- GCC_except_table12170
- GCC_except_table12172
- GCC_except_table12174
- GCC_except_table12180
- GCC_except_table1220
- GCC_except_table12217
- GCC_except_table12348
- GCC_except_table1236
- GCC_except_table12374
- GCC_except_table12386
- GCC_except_table12428
- GCC_except_table12430
- GCC_except_table12443
- GCC_except_table12548
- GCC_except_table12552
- GCC_except_table12593
- GCC_except_table12597
- GCC_except_table12606
- GCC_except_table12607
- GCC_except_table12614
- GCC_except_table1263
- GCC_except_table12652
- GCC_except_table12659
- GCC_except_table12671
- GCC_except_table12676
- GCC_except_table12726
- GCC_except_table12818
- GCC_except_table12821
- GCC_except_table12827
- GCC_except_table12829
- GCC_except_table12869
- GCC_except_table12888
- GCC_except_table12899
- GCC_except_table12961
- GCC_except_table12964
- GCC_except_table12972
- GCC_except_table12978
- GCC_except_table12980
- GCC_except_table13045
- GCC_except_table13123
- GCC_except_table13127
- GCC_except_table13131
- GCC_except_table13168
- GCC_except_table13192
- GCC_except_table13199
- GCC_except_table13338
- GCC_except_table13350
- GCC_except_table13444
- GCC_except_table13511
- GCC_except_table1355
- GCC_except_table13717
- GCC_except_table13796
- GCC_except_table13838
- GCC_except_table13887
- GCC_except_table13897
- GCC_except_table13932
- GCC_except_table13960
- GCC_except_table13975
- GCC_except_table13977
- GCC_except_table13979
- GCC_except_table13998
- GCC_except_table14144
- GCC_except_table14155
- GCC_except_table14182
- GCC_except_table14188
- GCC_except_table14204
- GCC_except_table14274
- GCC_except_table14276
- GCC_except_table14322
- GCC_except_table14324
- GCC_except_table14348
- GCC_except_table14351
- GCC_except_table14505
- GCC_except_table1461
- GCC_except_table1553
- GCC_except_table1578
- GCC_except_table1624
- GCC_except_table1699
- GCC_except_table1797
- GCC_except_table1898
- GCC_except_table1902
- GCC_except_table1922
- GCC_except_table1927
- GCC_except_table1931
- GCC_except_table1941
- GCC_except_table2130
- GCC_except_table2134
- GCC_except_table2136
- GCC_except_table2138
- GCC_except_table2140
- GCC_except_table2142
- GCC_except_table2144
- GCC_except_table2154
- GCC_except_table2156
- GCC_except_table2158
- GCC_except_table2170
- GCC_except_table2202
- GCC_except_table2204
- GCC_except_table2206
- GCC_except_table2208
- GCC_except_table2210
- GCC_except_table2212
- GCC_except_table2214
- GCC_except_table2216
- GCC_except_table2218
- GCC_except_table2220
- GCC_except_table2222
- GCC_except_table2224
- GCC_except_table2226
- GCC_except_table2228
- GCC_except_table2230
- GCC_except_table2232
- GCC_except_table2246
- GCC_except_table2248
- GCC_except_table2253
- GCC_except_table2255
- GCC_except_table2284
- GCC_except_table2286
- GCC_except_table2289
- GCC_except_table2292
- GCC_except_table2332
- GCC_except_table2400
- GCC_except_table2405
- GCC_except_table2416
- GCC_except_table2428
- GCC_except_table2466
- GCC_except_table2637
- GCC_except_table2650
- GCC_except_table2678
- GCC_except_table2693
- GCC_except_table2712
- GCC_except_table2722
- GCC_except_table2759
- GCC_except_table2764
- GCC_except_table2826
- GCC_except_table2929
- GCC_except_table2940
- GCC_except_table2942
- GCC_except_table2948
- GCC_except_table2956
- GCC_except_table2988
- GCC_except_table3064
- GCC_except_table3069
- GCC_except_table3074
- GCC_except_table3077
- GCC_except_table3087
- GCC_except_table3098
- GCC_except_table3100
- GCC_except_table3107
- GCC_except_table3234
- GCC_except_table3238
- GCC_except_table3241
- GCC_except_table3308
- GCC_except_table3316
- GCC_except_table3351
- GCC_except_table3355
- GCC_except_table3360
- GCC_except_table3490
- GCC_except_table3527
- GCC_except_table3533
- GCC_except_table3536
- GCC_except_table3546
- GCC_except_table3550
- GCC_except_table3556
- GCC_except_table3559
- GCC_except_table3564
- GCC_except_table3579
- GCC_except_table3584
- GCC_except_table3595
- GCC_except_table3596
- GCC_except_table3613
- GCC_except_table3622
- GCC_except_table3719
- GCC_except_table3725
- GCC_except_table3746
- GCC_except_table3748
- GCC_except_table3750
- GCC_except_table3797
- GCC_except_table3825
- GCC_except_table3856
- GCC_except_table3858
- GCC_except_table3876
- GCC_except_table3881
- GCC_except_table4044
- GCC_except_table4078
- GCC_except_table4086
- GCC_except_table4088
- GCC_except_table4103
- GCC_except_table4106
- GCC_except_table4141
- GCC_except_table4146
- GCC_except_table4147
- GCC_except_table4414
- GCC_except_table4421
- GCC_except_table4451
- GCC_except_table4475
- GCC_except_table4477
- GCC_except_table4482
- GCC_except_table4487
- GCC_except_table4502
- GCC_except_table4523
- GCC_except_table4536
- GCC_except_table4537
- GCC_except_table4597
- GCC_except_table4922
- GCC_except_table4932
- GCC_except_table4991
- GCC_except_table4993
- GCC_except_table4997
- GCC_except_table4999
- GCC_except_table5002
- GCC_except_table5072
- GCC_except_table5077
- GCC_except_table5107
- GCC_except_table5237
- GCC_except_table5241
- GCC_except_table5589
- GCC_except_table5620
- GCC_except_table5666
- GCC_except_table5685
- GCC_except_table5691
- GCC_except_table5697
- GCC_except_table5709
- GCC_except_table5711
- GCC_except_table5737
- GCC_except_table5742
- GCC_except_table5745
- GCC_except_table5754
- GCC_except_table5763
- GCC_except_table5767
- GCC_except_table5776
- GCC_except_table5819
- GCC_except_table5852
- GCC_except_table5881
- GCC_except_table5885
- GCC_except_table5889
- GCC_except_table5911
- GCC_except_table5917
- GCC_except_table5921
- GCC_except_table5935
- GCC_except_table5938
- GCC_except_table5941
- GCC_except_table5964
- GCC_except_table5998
- GCC_except_table6019
- GCC_except_table6028
- GCC_except_table6067
- GCC_except_table6079
- GCC_except_table6113
- GCC_except_table6116
- GCC_except_table6122
- GCC_except_table6126
- GCC_except_table6138
- GCC_except_table6171
- GCC_except_table6200
- GCC_except_table6227
- GCC_except_table6229
- GCC_except_table6243
- GCC_except_table6312
- GCC_except_table6390
- GCC_except_table6395
- GCC_except_table6400
- GCC_except_table6558
- GCC_except_table6561
- GCC_except_table6574
- GCC_except_table6599
- GCC_except_table6609
- GCC_except_table6612
- GCC_except_table6651
- GCC_except_table6688
- GCC_except_table6690
- GCC_except_table7090
- GCC_except_table7110
- GCC_except_table7123
- GCC_except_table7136
- GCC_except_table7186
- GCC_except_table7189
- GCC_except_table7191
- GCC_except_table7193
- GCC_except_table7195
- GCC_except_table7204
- GCC_except_table7252
- GCC_except_table7266
- GCC_except_table7304
- GCC_except_table7306
- GCC_except_table7345
- GCC_except_table7598
- GCC_except_table7601
- GCC_except_table7623
- GCC_except_table7630
- GCC_except_table7646
- GCC_except_table7648
- GCC_except_table7650
- GCC_except_table7651
- GCC_except_table7652
- GCC_except_table7653
- GCC_except_table7664
- GCC_except_table7666
- GCC_except_table7823
- GCC_except_table802
- GCC_except_table8042
- GCC_except_table805
- GCC_except_table806
- GCC_except_table807
- GCC_except_table808
- GCC_except_table8087
- GCC_except_table809
- GCC_except_table8105
- GCC_except_table8166
- GCC_except_table8188
- GCC_except_table8192
- GCC_except_table8199
- GCC_except_table8253
- GCC_except_table8453
- GCC_except_table8455
- GCC_except_table8502
- GCC_except_table8542
- GCC_except_table8546
- GCC_except_table8548
- GCC_except_table8550
- GCC_except_table8562
- GCC_except_table8607
- GCC_except_table8635
- GCC_except_table8677
- GCC_except_table8769
- GCC_except_table8827
- GCC_except_table8847
- GCC_except_table8850
- GCC_except_table8869
- GCC_except_table889
- GCC_except_table8928
- GCC_except_table8932
- GCC_except_table8936
- GCC_except_table8937
- GCC_except_table8938
- GCC_except_table8939
- GCC_except_table8940
- GCC_except_table8942
- GCC_except_table8944
- GCC_except_table8948
- GCC_except_table8962
- GCC_except_table8983
- GCC_except_table9027
- GCC_except_table9092
- GCC_except_table9249
- GCC_except_table9290
- GCC_except_table9296
- GCC_except_table9299
- GCC_except_table9562
- GCC_except_table9566
- GCC_except_table9570
- GCC_except_table9590
- GCC_except_table9591
- GCC_except_table9687
- GCC_except_table9697
- GCC_except_table9730
- GCC_except_table9782
- GCC_except_table9827
- GCC_except_table9847
- GCC_except_table9901
- GCC_except_table9934
- GCC_except_table9936
- GCC_except_table994
- _NSFilePosixPermissions
- _OBJC_IVAR_$_PHAssetResourceFetchResult._typeGroup
- _OBJC_IVAR_$_PHPhotoLibrary._cachedCloudStatus
- _OBJC_IVAR_$_PHPhotoLibrary._cloudStatusHandlerQueue
- _OBJC_IVAR_$_PHPhotoLibrary._cloudStatusObserverRegistrar
- _OBJC_IVAR_$_PHPhotoLibrary._cplStatusDelegateQueue
- _OBJC_IVAR_$_PHPhotoLibrary._lazyCPLStatus
- _OBJC_IVAR_$_PHSharePost._lastModifiedDate
- _PHIsImageAssetResourceType
- _PHIsVideoAssetResourceType
- _PLGatekeeperXPCGetLog
- _PLIsCamera
- _PLIsSharedCollectionsFeatureEnabled
- _PLSafeEntityForNameInManagedObjectContext
- ___151-[PHAssetExportRequest _processResourcesAtFileURLs:forAsset:withOptions:progress:processingUnitCount:replacementLivePhotoPairingIdentifier:completion:]_block_invoke_4
- ___151-[PHAssetExportRequest _processResourcesAtFileURLs:forAsset:withOptions:progress:processingUnitCount:replacementLivePhotoPairingIdentifier:completion:]_block_invoke_5
- ___151-[PHAssetExportRequest _processResourcesAtFileURLs:forAsset:withOptions:progress:processingUnitCount:replacementLivePhotoPairingIdentifier:completion:]_block_invoke_6
- ___151-[PHAssetExportRequest _processResourcesAtFileURLs:forAsset:withOptions:progress:processingUnitCount:replacementLivePhotoPairingIdentifier:completion:]_block_invoke_7
- ___151-[PHAssetExportRequest _processResourcesAtFileURLs:forAsset:withOptions:progress:processingUnitCount:replacementLivePhotoPairingIdentifier:completion:]_block_invoke_8
- ___151-[PHAssetExportRequest _processResourcesAtFileURLs:forAsset:withOptions:progress:processingUnitCount:replacementLivePhotoPairingIdentifier:completion:]_block_invoke_9
- ___36-[PHPhotoLibrary _resetCachedValues]_block_invoke
- ___36-[PHPhotoLibrary _resetCachedValues]_block_invoke_2
- ___36-[PHPhotoLibrary _resetCachedValues]_block_invoke_3
- ___41+[PHPhotoLibrary imagePickerPhotoLibrary]_block_invoke
- ___44-[PHPhotoLibrary _processCPLStatusDidChange]_block_invoke
- ___44-[PHPhotoLibrary _publishCloudStatusUpdate:]_block_invoke
- ___46-[PHPhotoLibrary registerCloudStatusObserver:]_block_invoke
- ___50-[PHPhotoLibrary _invalidateEverythingWithReason:]_block_invoke_2
- ___51+[PHImportAsset scanAssetsForProvenanceData:atEnd:]_block_invoke
- ___51+[PHImportAsset scanAssetsForProvenanceData:atEnd:]_block_invoke_2
- ___51+[PHPhotoLibrary setImagePickerPhotoLibrary:error:]_block_invoke
- ___52+[PHSearch ocrTextLinesForAssetUUID:inPhotoLibrary:]_block_invoke
- ___52+[PHSearch ocrTextLinesForAssetUUID:inPhotoLibrary:]_block_invoke_2
- ___54-[PHPhotoLibrary getCloudStatusWithCompletionHandler:]_block_invoke
- ___54-[PHPhotoLibrary getCloudStatusWithCompletionHandler:]_block_invoke_2
- ___65+[PHCloudFeedEntry fetchEntriesInCollectionShare:filter:options:]_block_invoke
- ___85-[PHAssetCreationRequestPlaceholderSupport _updateManagedAssetAfterResourceDownload:]_block_invoke
- ___85-[PHServerResourceRequestRunner chooseVideoWithRequest:library:clientBundleID:reply:]_block_invoke_3
- ___block_descriptor_104_e8_32s40s48s56s64s72s80s88r96r_e5_v8?0ls32l8s40l8r88l8s48l8r96l8s56l8s64l8s72l8s80l8
- ___block_descriptor_48_e8_32bs40w_e39_v24?0"PLCPLClientStatus"8"NSError"16ls32l8w40l8
- ___block_descriptor_48_e8_32s40s_e20_v20?0i8"NSError"12ls32l8s40l8
- ___block_descriptor_48_e8_32s40w_e39_v24?0"PLCPLClientStatus"8"NSError"16lw40l8s32l8
- __fetchTypeForAssetCollectionLocalIdentifierCode.pl_once_object_25
- __fetchTypeForAssetCollectionLocalIdentifierCode.pl_once_token_25
- __simpleDeleteValidatorsWithManagedObjectContext:.pl_once_object_5
- __simpleDeleteValidatorsWithManagedObjectContext:.pl_once_token_5
- _allowedEntities.pl_once_object_74
- _allowedEntities.pl_once_object_75
- _allowedEntities.pl_once_token_74
- _allowedEntities.pl_once_token_75
- _analyticsPropertiesToFetch.pl_once_object_4
- _analyticsPropertiesToFetch.pl_once_token_4
- _associated conformance So26PHAssetResourceFetchResultC6PhotosE5IndexVSLACSQ
- _corePropertiesToFetch.pl_once_object_4
- _corePropertiesToFetch.pl_once_token_4
- _dateRangeTitleGenerator.pl_once_object_6
- _dateRangeTitleGenerator.pl_once_token_6
- _entityKeyMap.pl_once_object_4
- _entityKeyMap.pl_once_object_5
- _entityKeyMap.pl_once_token_4
- _entityKeyMap.pl_once_token_5
- _handleUnsupportedAssetCollectionFetchTypeForLocalIdentifier.pl_once_object_38
- _handleUnsupportedAssetCollectionFetchTypeForLocalIdentifier.pl_once_token_38
- _imagePickerPhotoLibrary
- _imagePickerPhotoLibraryLock
- _propertiesToFetch.pl_once_object_12
- _propertiesToFetch.pl_once_object_17
- _propertiesToFetch.pl_once_object_8
- _propertiesToFetch.pl_once_token_12
- _propertiesToFetch.pl_once_token_17
- _propertiesToFetch.pl_once_token_8
- _propertiesToFetchWithHint:.pl_once_object_4
- _propertiesToFetchWithHint:.pl_once_token_4
- _publicPHObjectChangeClasses.pl_once_object_18
- _publicPHObjectChangeClasses.pl_once_token_18
- _sharedLazyPhotoLibraryForCMM.pl_once_object_46
- _sharedLazyPhotoLibraryForCMM.pl_once_token_46
- _symbolic _____ So26PHAssetResourceFetchResultC6PhotosE5IndexV
- _type_layout_string So26PHAssetResourceFetchResultC6PhotosE5IndexV
- _uniqueObjectIDCache.pl_once_object_73
- _uniqueObjectIDCache.pl_once_token_73
CStrings:
+ "%@ %p initWithPhotoLibrary:%p"
+ "%{public}@ %p closing (irreversible), reason: %{public}@ / %ld, deallocating=%d"
+ "%{public}@ %p invalidating everything (irreversible), reason: %{public}@ / %ld, wellKnownIdentifier=%td"
+ "+[PHObject objectIDsMatchingEntityFromObjectIDs:context:]"
+ "+[PHQuery combinedFetchRequestForQueries:]"
+ "-[PHAssetCollectionChangeRequest applyMutationsToManagedObject:photoLibrary:error:]"
+ "-[PHAssetCreationRequestPlaceholderSupport _directUploadShareAssetAfterResourceDownloadInPhotoLibrary:]_block_invoke"
+ "-[PHAssetCreationRequestPlaceholderSupport _retrieveSharedStreamResourcesForSourceAsset:photoLibrary:]_block_invoke"
+ "-[PHAssetExportRequest _processResourcesAtFileURLs:forAsset:withOptions:progress:processingUnitCount:replacementLivePhotoPairingIdentifier:completion:]"
+ "-[PHChange _propagatePropertyNamesToSubentityNames:moc:]"
+ "-[PHChangeRequestHelper allowMutationToManagedObject:propertyKey:error:]"
+ "-[PHChangeValidationController _prepare]"
+ "-[PHCollectionListChangeRequest applyMutationsToManagedObject:photoLibrary:error:]"
+ "-[PHMemoryChangeRequest applyMutationsToManagedObject:photoLibrary:error:]"
+ "-[PHObjectDeleteValidator initWithEntityName:managedObjectContext:]"
+ "-[PHQuery _createFetchRequestIncludingBasePredicate:]"
+ "-[PHQuery effectivePredicateForPHClass:includingBasePredicate:]"
+ "-[PHShareAssetChangeRequestHelper addAssetsToCPLShare:creationOptionsPerAsset:withMomentSharePreview:withBatchCommentText:outKeyAssetIdentifier:outContainsEPPAssets:outCreatedSharePostPlaceholder:skipSharePost:]"
+ "-[PHSmartAlbumChangeRequest applyMutationsToManagedObject:photoLibrary:error:]"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Photos/Projects/PhotoKit/Sources/PHAssetExportRequest.m"
+ "<%@: %p, variant: \"%@\", livePhotoAsStill: %d, allowRaw: %d, flattenSlomo: %d, stripLocation: %d, stripProvenance: %d, stripCaption: %d, stripAXDescription: %d, stripKeywords: %d, stripRating: %d, exportTitle: %d, assetBundle: %d, disableMetadataCorrections: %d, unmodifiedOriginals: %d>"
+ "Asset playback style is unsupported for export."
+ "AssetResourceUploadJobConfiguration is not in correct state."
+ "Download finished for source asset %@ (error: %@), going to call _updateManagedAssetAfterResourceDownload: for placeholder asset %@"
+ "Edited provenance asset has no full-size render to combine its provenance into"
+ "Exceeded permitted number of AssetResourceUploadJobs."
+ "Failed to fetch face crops because the photo library was invalidated"
+ "Failed to retrieve shared stream resource for source asset %{public}@: %@"
+ "Failed to update placeholder asset %{public}@ after source resources download: %@"
+ "Found no shared stream resources to retrieve for source asset %{public}@, copy of placeholder asset %{public}@ will fail"
+ "Keeping placeholder asset %{public}@ - source resources never landed, so a later pass can still complete the copy"
+ "No AssetResourceUploadJobConfiguration is set for this change request."
+ "No PLPhotoLibrary for current queue (wellKnownIdentifier=%td, isSystemPhotoLibrary=%d, mainThread=%d, qos=%@)"
+ "No primary resource in the resource bag. Cannot create asset."
+ "No resources left to copy from asset %@ (flattenLivePhoto=%d, bakeInAdjustments=%d)"
+ "Not direct uploading Share asset %@ after resource download - asset is missing or was not fully copied"
+ "PHAssetExportRequestMetadataOperation PHAssetExportRequestAccessibilityDescriptionMetadataOperationForAssetWithOptions(PHAsset *__strong _Nonnull, PHAssetExportRequestOptions *__strong _Nonnull, PFMetadata *__strong _Nullable, NSString * _Nullable __autoreleasing * _Nullable)"
+ "PHAssetExportRequestMetadataOperation PHAssetExportRequestStarRatingMetadataOperationForAssetWithOptions(PHAsset *__strong _Nonnull, PHAssetExportRequestOptions *__strong _Nonnull, PFMetadata *__strong _Nullable, NSNumber * _Nullable __autoreleasing * _Nullable)"
+ "PHAssetExportRequestMetadataOperation PHAssetExportRequestTitleMetadataOperationForAssetWithOptions(PHAsset *__strong _Nonnull, PHAssetExportRequestOptions *__strong _Nonnull, PFMetadata *__strong _Nullable, NSString * _Nullable __autoreleasing * _Nullable)"
+ "PHFetchResult init with no fetch request; fetchError from %{public}s: %@\n\tself: %@"
+ "PHFindQueryContext: queryId: %lld, photoLibrary: %td, leo: %p, queryEmbeddingsCount: %tu, findOptions: %@, leoOptions: %@, embeddingRelevanceScoresByUUID: %@, lexemesForQueryByLexemeId: %@>"
+ "PHPhotosErrorCollectionShareNotEnabled"
+ "PHPhotosErrorShareNeedsToRequestAccess"
+ "PLImageWriterStashCameraJob"
+ "PhotoKit Ingest Bridge: %{public}@ Unhandled job type %{public}@ for UUID: %{public}@"
+ "PhotoKit Ingest Bridge: Not stashing %{public}@, no asset UUID in job dictionary"
+ "PhotoKit Ingest Bridge: Not stashing burst job, no camera avalanche UUID in job dictionary"
+ "PlaceholderSharedStreamRetrieval-%@"
+ "Provenance asset needs a full-size render to carry its original's provenance, but none was selected"
+ "Publish cloud status update: %@"
+ "Share participant has no UUID"
+ "Source resource download for placeholder asset %{public}@ finished with error: %@"
+ "The angel photo library URL must match the system photo library URL"
+ "[PHAssetExportRequest] Adjusted processed provenance asset %{public}@ missing original or full-size photo URL."
+ "[PHAssetExportRequest] Asset %{public}@ is unprocessed provenance but we are missing the original photo."
+ "[PHAssetExportRequest] Cancelled while processing resources of asset: %{public}@"
+ "[PHAssetExportRequest] Changing state from \"%{public}@\" to \"%{public}@\" for asset: %{public}@"
+ "[PHAssetExportRequest] Error while processing resources of asset %{public}@: %@"
+ "[PHAssetExportRequest] Export request processing required for asset %{public}@: %{BOOL}d (metadataOperationLocation=%{public}@, metadataOperationProvenance=%{public}@, metadataOperationCaption=%{public}@, metadataOperationCaptionAccessibilityDescription=%{public}@, metadataOperationKeywords=%{public}@, metadataOperationStarRating=%{public}@, metadataOperationTitle=%{public}@, metadataChangeCustomDate=%{private}@, livePhotoMetadataFixup=%{BOOL}d producingNewFilesForExport=%{BOOL}d, options.variant=%{public}@, requiresSloMoFlattening=%{BOOL}d, videoExportPreset=%{public}@, type = %{public}@, needsReplacementLivePhotoIdentifier = %{BOOL}d %{public}@"
+ "[PHAssetExportRequest] Low disk space error while processing resources of asset %{public}@: %@"
+ "[PHAssetExportRequest] Performing additional processing of image resource of asset %{public}@"
+ "[PHAssetExportRequest] Performing additional processing of video resource of asset %{public}@"
+ "[PHAssetExportRequest] Performing slomo flattening of video resource of asset %{public}@"
+ "[PHAssetExportRequest] Performing video to GIF conversion of video resource of asset %{public}@"
+ "[PHAssetExportRequest] Processing retrieved file urls for compatibility and/or metadata corrections for asset: %{public}@"
+ "[PHAssetExportRequest] Returning provenanceMetadataOperation: %ld. Asset provenance state: %hi for asset %{public}@"
+ "[PHAssetExportRequest] Unable to create asset bundle at directory '%@' due to following error '%@'"
+ "[PHAssetExportRequest] Unable to create live photo bundle at '%@' due to following error '%@'"
+ "[PHAssetExportRequest] We processed fileURLs for asset %{public}@: %@.\nRemoving the DNG and remained with these fileURLs to share: %@"
+ "[PHAssetExportRequest][ContentProvenance] Provenance processing error while processing resources of asset %{public}@: %@"
+ "[PHCloudSharedAssetExportRequest] Unsupported playback style %ld, cannot export asset: %@"
+ "[PHResourceLocalAvailabilityRequest] Provenance asset needs its original carried into a full-size render, but none was selected for asset: %@, resources: %@, options: %@"
+ "[PHResourceLocalAvailabilityRequest] Routing provenance render to FullSizePhotoURLKey (keeping original in PhotoURLKey) for asset:%@"
+ "[RM] %@ Media metadata with version: %ld has no type string"
+ "[RM] %{public}@ video request was cancelled before library perform"
+ "_processCPLStatusDidChange nil assetsd client"
+ "com.apple.camera.lockscreen"
+ "lastEditedDate"
+ "live library unavailability"
+ "nil assetsd client"
+ "openAndWaitWithUpgrade short-circuiting on cached open failure %@; this PHPhotoLibrary instance will never reopen"
+ "photoLibraryForCurrentQueueQoS nil (mainThread=%d, qos=%@, invalidated/valid: main=%d/%d userInitiated=%d/%d background=%d/%d)"
+ "previously-recorded bundle nil-library reason"
+ "star rating"
+ "typeGroups != 0"
+ "void PHAssetExportRequestPerformMediaConversion(PHMediaFormatConversionSource *__strong, BOOL, BOOL, UTType * _Nullable __strong, PHAssetExportRequestMetadataOperation, CLLocation * _Nullable __strong, NSDate * _Nullable __strong, NSTimeZone * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSArray<NSString *> * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSNumber * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSURL *__strong, NSURL *__strong, NSURL *__strong, NSURL *__strong, BOOL, NSString * _Nullable __strong, NSProgress *__strong, int64_t, NSURL *__strong, BOOL, NSString *__strong, NSString * _Nullable __strong, void (^__strong)(NSURL * _Nullable __strong, NSError * _Nullable __strong))"
+ "void PHAssetExportRequestPerformSlomoFlattening(NSURL *__strong, NSURL *__strong, NSProgress *__strong, int64_t, NSURL *__strong, NSString *__strong, NSString *__strong, NSString *__strong, BOOL, PHAssetExportRequestMetadataOperation, CLLocation * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSArray<NSString *> * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSNumber * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, void (^__strong)(NSURL * _Nullable __strong, NSError * _Nullable __strong))"
- "%@ %p _invalidateEverythingWithReason:%@"
- "%K == nil OR %K >= %K"
- "%K > %@ AND %K.%K == NO"
- "+[PHAssetCreationRequest creationRequestForAssetCopyFromAsset:options:] API does not support copying cloud shared assets to non-share destinations"
- "<%@: %p, variant: \"%@\", livePhotoAsStill: %d, allowRaw: %d, flattenSlomo: %d, stripLocation: %d, stripProvenance: %d, stripCaption: %d, stripAXDescription: %d, stripKeywords: %d, assetBundle: %d, disableMetadataCorrections: %d, unmodifiedOriginals: %d>"
- "Cloud status changed: %@"
- "Configuration is not in correct state."
- "Download finished for source asset %@, going to call _updateManagedAssetAfterResourceDownload: for placeholder asset %@"
- "Edited provenance asset selected its original as a provenance source but has no full-size render to carry it"
- "Failed to update placeholder asset %@ after source resources download: %@"
- "Lemonade"
- "PHAssetExportRequestMetadataOperation PHAssetExportRequestAccessibilityDescriptionMetadataOperationForAssetWithOptions(PHAsset *__strong, PHAssetExportRequestOptions *__strong, PFMetadata *__strong, NSString * _Nullable __autoreleasing * _Nullable)"
- "PHFetchResult init with no fetch request, library not available, setting fetchError to %@\n\tself: %@"
- "PHFindQueryContext: queryId: %lld, photoLibrary: %td, leo: %p, queryEmbeddingsCount: %tu, findOptions: %@, leoOptions: %@, embeddingRelevanceScoresByUUID: %@, lexemesForQueryByLexemeId: %@, fetchedLexemeIDs: %@>"
- "PXFeedAssetContainerList"
- "PXFeedAssetsSectionInfo"
- "PXFeedCommentsSectionInfo"
- "PXFeedSubscriptionSectionInfo"
- "PhotoKit Ingest Bridge: Skipping Camera preview image job due to duplicate job from nebulad"
- "The image picker photo library URL must match the system photo library URL"
- "Too many jobs."
- "Unable to create asset bundle at directory '%@' due to following error '%@'"
- "Unable to create live photo bundle at '%@' due to following error '%@'"
- "Unable to make read-only imported file writeable with error: %@"
- "Unable to read file attributes at import downloaded file url, error: %@"
- "[PHAssetExportRequest] Adjusted processed provenance asset missing original or full-size photo URL."
- "[PHAssetExportRequest] Asset is unprocessed provenance but we are missing the original photo. "
- "[PHAssetExportRequest] Cancelled while processing resources"
- "[PHAssetExportRequest] Changing state from \"%{public}@\" to \"%{public}@\""
- "[PHAssetExportRequest] Error while processing resources: %@"
- "[PHAssetExportRequest] Export request processing required for asset %{public}@: %{BOOL}d (metadataOperationLocation=%{public}@, metadataOperationProvenance=%{public}@, metadataOperationCaption=%{public}@, metadataOperationCaptionAccessibilityDescription=%{public}@, metadataOperationKeywords=%{public}@, metadataChangeCustomDate=%{private}@, livePhotoMetadataFixup=%{BOOL}d producingNewFilesForExport=%{BOOL}d, options.variant=%{public}@, requiresSloMoFlattening=%{BOOL}d, videoExportPreset=%{public}@, type = %{public}@, needsReplacementLivePhotoIdentifier = %{BOOL}d %{public}@"
- "[PHAssetExportRequest] Low disk space error while processing resources: %@"
- "[PHAssetExportRequest] Processing retrieved file urls for compatibility and/or metadata corrections"
- "[PHAssetExportRequest] Returning provenanceMetadataOperation: %ld. Asset state: %hi"
- "[PHAssetExportRequest] We processed fileURLs %@. Removing the DNG and remained with these fileURLs to share: %@"
- "[PHResourceLocalAvailabilityRequest] Routing edited provenance render to FullSizePhotoURLKey (keeping original in PhotoURLKey) for asset:%@"
- "[PHResourceLocalAvailabilityRequest] Selected original as provenance source but no full-size render is available to carry it for asset: %@, resources: %@, options: %@"
- "nil library"
- "void PHAssetExportRequestPerformMediaConversion(PHMediaFormatConversionSource *__strong, BOOL, BOOL, UTType * _Nullable __strong, PHAssetExportRequestMetadataOperation, CLLocation * _Nullable __strong, NSDate * _Nullable __strong, NSTimeZone * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSArray<NSString *> * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSURL *__strong, NSURL *__strong, NSURL *__strong, NSURL *__strong, BOOL, NSString * _Nullable __strong, NSProgress *__strong, int64_t, NSURL *__strong, BOOL, NSString *__strong, NSString * _Nullable __strong, void (^__strong)(NSURL * _Nullable __strong, NSError * _Nullable __strong))"
- "void PHAssetExportRequestPerformSlomoFlattening(NSURL *__strong, NSURL *__strong, NSProgress *__strong, int64_t, NSURL *__strong, NSString *__strong, NSString *__strong, NSString *__strong, BOOL, PHAssetExportRequestMetadataOperation, CLLocation * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSString * _Nullable __strong, PHAssetExportRequestMetadataOperation, NSArray<NSString *> * _Nullable __strong, void (^__strong)(NSURL * _Nullable __strong, NSError * _Nullable __strong))"
```
