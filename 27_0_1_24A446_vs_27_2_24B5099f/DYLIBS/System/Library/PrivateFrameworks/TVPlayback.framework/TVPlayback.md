## TVPlayback

> `/System/Library/PrivateFrameworks/TVPlayback.framework/TVPlayback`

```diff

-635.0.7.0.0
-  __TEXT.__text: 0x68e2c
-  __TEXT.__objc_methlist: 0x5fb0
+635.10.14.0.0
+  __TEXT.__text: 0x6adf0
+  __TEXT.__objc_methlist: 0x61b0
   __TEXT.__const: 0x268
-  __TEXT.__cstring: 0x6b1f
-  __TEXT.__oslogstring: 0x7016
+  __TEXT.__cstring: 0x6bed
+  __TEXT.__oslogstring: 0x725f
   __TEXT.__gcc_except_tab: 0x1fd8
-  __TEXT.__unwind_info: 0x16d8
+  __TEXT.__unwind_info: 0x1738
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x24e0
-  __DATA_CONST.__objc_classlist: 0x1f8
-  __DATA_CONST.__objc_catlist: 0x80
+  __DATA_CONST.__objc_classlist: 0x200
+  __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3e08
+  __DATA_CONST.__objc_selrefs: 0x3f10
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x170
+  __DATA_CONST.__objc_superrefs: 0x178
   __DATA_CONST.__objc_arraydata: 0x10
-  __DATA_CONST.__got: 0x8d8
-  __AUTH_CONST.__const: 0x680
-  __AUTH_CONST.__cfstring: 0x6c80
-  __AUTH_CONST.__objc_const: 0x9aa8
+  __DATA_CONST.__got: 0x8f8
+  __AUTH_CONST.__const: 0x6a0
+  __AUTH_CONST.__cfstring: 0x6da0
+  __AUTH_CONST.__objc_const: 0x9d40
   __AUTH_CONST.__objc_intobj: 0x480
   __AUTH_CONST.__objc_arrayobj: 0x30
-  __AUTH_CONST.__auth_got: 0x430
-  __AUTH.__objc_data: 0x870
-  __DATA.__objc_ivar: 0x7cc
+  __AUTH_CONST.__auth_got: 0x450
+  __AUTH.__objc_data: 0x8c0
+  __DATA.__objc_ivar: 0x7e8
   __DATA.__data: 0xae0
-  __DATA.__bss: 0xa8
+  __DATA.__bss: 0xb8
   __DATA_DIRTY.__objc_data: 0xb40
   __DATA_DIRTY.__bss: 0x230
   __DATA_DIRTY.__common: 0x8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2276
-  Symbols:   4204
-  CStrings:  1449
+  Functions: 2326
+  Symbols:   4278
+  CStrings:  1469
 
Symbols:
+ +[AVMediaSelectionGroup(TVPSignLanguageAdditions) tvp_signLanguageOptionMatchingLanguage:inOptions:]
+ +[TVPPlayer _downloadedOptionsInGroup:ofAsset:]
+ +[TVPPlayer _updateVideoSelectionCriteriaForAVQueuePlayer:isInterstitialPlayer:preferredSignLanguage:]
+ +[TVPPlayer savedPreferredSignLanguage]
+ -[AVMediaSelectionGroup(TVPSignLanguageAdditions) tvp_signLanguageDownloadOption]
+ -[AVQueuePlayer(TVPAdditions) setTvp_cachedVideoSelectionCriteria:]
+ -[AVQueuePlayer(TVPAdditions) tvp_cachedVideoSelectionCriteria]
+ -[TVPPlayer _downloadedSignLanguageOptions]
+ -[TVPPlayer _effectiveSignLanguage]
+ -[TVPPlayer _nextChapterInDirection:]
+ -[TVPPlayer _signLanguageForSelectionCriteria]
+ -[TVPPlayer _updateVideoSelectionCriteria]
+ -[TVPPlayer allowsSignLanguageSelection]
+ -[TVPPlayer cachedSelectedVideoOption]
+ -[TVPPlayer canSkipToNextChapterInDirection:]
+ -[TVPPlayer preferredSignLanguage]
+ -[TVPPlayer selectedVideoOption]
+ -[TVPPlayer setAllowsSignLanguageSelection:]
+ -[TVPPlayer setCachedSelectedVideoOption:]
+ -[TVPPlayer setPreferredSignLanguage:]
+ -[TVPPlayer setSelectedVideoOption:]
+ -[TVPPlayer setSignLanguageChosenByViewer:]
+ -[TVPPlayer signLanguageChosenByViewer]
+ -[TVPPlayer videoOptions]
+ -[TVPVideoOption .cxx_destruct]
+ -[TVPVideoOption avMediaSelectionOption]
+ -[TVPVideoOption description]
+ -[TVPVideoOption extendedLanguageCode]
+ -[TVPVideoOption hasMediaCharacteristic:]
+ -[TVPVideoOption hasSignLanguage]
+ -[TVPVideoOption hash]
+ -[TVPVideoOption initWithOption:isDefault:isDownloaded:]
+ -[TVPVideoOption isDefault]
+ -[TVPVideoOption isDownloaded]
+ -[TVPVideoOption isEqual:]
+ -[TVPVideoOption localizedDisplayString]
+ -[TVPVideoOption mediaCharacteristics]
+ -[TVPVideoOption setAvMediaSelectionOption:]
+ -[TVPVideoOption setIsDefault:]
+ -[TVPVideoOption setIsDownloaded:]
+ GCC_except_table136
+ GCC_except_table241
+ GCC_except_table251
+ GCC_except_table254
+ GCC_except_table303
+ GCC_except_table333
+ GCC_except_table349
+ GCC_except_table371
+ GCC_except_table375
+ GCC_except_table384
+ GCC_except_table395
+ GCC_except_table421
+ GCC_except_table422
+ GCC_except_table424
+ GCC_except_table427
+ GCC_except_table430
+ GCC_except_table431
+ GCC_except_table433
+ GCC_except_table434
+ GCC_except_table439
+ GCC_except_table442
+ GCC_except_table455
+ GCC_except_table460
+ GCC_except_table462
+ GCC_except_table464
+ GCC_except_table489
+ GCC_except_table491
+ GCC_except_table493
+ GCC_except_table496
+ GCC_except_table502
+ GCC_except_table509
+ GCC_except_table511
+ GCC_except_table513
+ GCC_except_table518
+ GCC_except_table528
+ GCC_except_table536
+ GCC_except_table551
+ GCC_except_table553
+ GCC_except_table556
+ GCC_except_table560
+ _AVMediaCharacteristicSignLanguageInterpretationForAccessibility
+ _AVMediaCharacteristicVisual
+ _CFPreferencesAppSynchronize
+ _CFPreferencesCopyAppValue
+ _CFPreferencesSetAppValue
+ _NSLocaleCountryCode
+ _OBJC_CLASS_$_TVPVideoOption
+ _OBJC_IVAR_$_TVPPlayer._allowsSignLanguageSelection
+ _OBJC_IVAR_$_TVPPlayer._cachedSelectedVideoOption
+ _OBJC_IVAR_$_TVPPlayer._preferredSignLanguage
+ _OBJC_IVAR_$_TVPPlayer._signLanguageChosenByViewer
+ _OBJC_IVAR_$_TVPVideoOption._avMediaSelectionOption
+ _OBJC_IVAR_$_TVPVideoOption._isDefault
+ _OBJC_IVAR_$_TVPVideoOption._isDownloaded
+ _OBJC_METACLASS_$_TVPVideoOption
+ _TVPSignLanguageCopyPreference
+ _TVPSignLanguageDefaultLanguageCode
+ _TVPSignLanguageDefaultLanguageCode.onceToken
+ _TVPSignLanguageDefaultLanguageCode.sDefaultLanguageCode
+ _TVPSignLanguageDownloadLanguage
+ _TVPSignLanguagePreferredLanguage
+ _TVPSignLanguageSetPreferredLanguage
+ _TVPSignLanguageSettingEnabled
+ __OBJC_$_CATEGORY_AVMediaSelectionGroup_$_TVPSignLanguageAdditions
+ __OBJC_$_CATEGORY_CLASS_METHODS_AVMediaSelectionGroup_$_TVPSignLanguageAdditions
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_AVMediaSelectionGroup_$_TVPSignLanguageAdditions
+ __OBJC_$_INSTANCE_METHODS_TVPVideoOption
+ __OBJC_$_INSTANCE_VARIABLES_TVPVideoOption
+ __OBJC_$_PROP_LIST_AVMediaSelectionGroup_$_TVPSignLanguageAdditions
+ __OBJC_$_PROP_LIST_TVPVideoOption
+ __OBJC_CLASS_RO_$_TVPVideoOption
+ __OBJC_METACLASS_RO_$_TVPVideoOption
+ ___TVPSignLanguageDefaultLanguageCode_block_invoke
+ _notify_post
- GCC_except_table134
- GCC_except_table234
- GCC_except_table240
- GCC_except_table244
- GCC_except_table295
- GCC_except_table325
- GCC_except_table335
- GCC_except_table357
- GCC_except_table361
- GCC_except_table370
- GCC_except_table381
- GCC_except_table400
- GCC_except_table407
- GCC_except_table408
- GCC_except_table410
- GCC_except_table411
- GCC_except_table413
- GCC_except_table416
- GCC_except_table417
- GCC_except_table419
- GCC_except_table420
- GCC_except_table432
- GCC_except_table436
- GCC_except_table441
- GCC_except_table448
- GCC_except_table475
- GCC_except_table477
- GCC_except_table479
- GCC_except_table482
- GCC_except_table488
- GCC_except_table495
- GCC_except_table497
- GCC_except_table499
- GCC_except_table504
- GCC_except_table508
- GCC_except_table514
- GCC_except_table525
- GCC_except_table537
- GCC_except_table542
- GCC_except_table546
CStrings:
+ "%@ isDefault: %@ isDownloaded: %@"
+ "GB"
+ "Not the same show; clearing the preferred sign language"
+ "Performing automatic re-selection of video for player item %@ in player %@"
+ "PreferredSignLanguage"
+ "PreferredSignLanguageDownload"
+ "Replacing default media selection with sign-language selection for %@"
+ "Selected video option: %@"
+ "Selecting video media option: %@"
+ "Setting cached video option from active player item %@ to %@."
+ "Setting visual media selection criteria on %@ (is interstitial player: %@) to %@"
+ "Unable to load visual media selection group due to error %@"
+ "Video selection option is nil, not selecting"
+ "Will perform automatic re-selection of video for player item %@ in player %@"
+ "ase"
+ "bfi"
+ "com.apple.AppleTV.signLanguageSettingDidChange"
+ "com.apple.videos-preferences"
+ "selectedVideoOption"
+ "videoOptions"
```
