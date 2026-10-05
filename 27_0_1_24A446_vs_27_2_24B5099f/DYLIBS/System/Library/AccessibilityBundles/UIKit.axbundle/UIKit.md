## UIKit

> `/System/Library/AccessibilityBundles/UIKit.axbundle/UIKit`

```diff

-3048.0.0.0.0
-  __TEXT.__text: 0x15b3b8
-  __TEXT.__objc_methlist: 0xfc24
+3050.3.5.0.0
+  __TEXT.__text: 0x15fd54
+  __TEXT.__objc_methlist: 0xfdd4
   __TEXT.__dlopen_cstrs: 0xb8
-  __TEXT.__const: 0x1c0
-  __TEXT.__gcc_except_tab: 0x35c8
-  __TEXT.__cstring: 0x19451
-  __TEXT.__oslogstring: 0x2712
+  __TEXT.__const: 0x1c8
+  __TEXT.__gcc_except_tab: 0x3608
+  __TEXT.__cstring: 0x19574
+  __TEXT.__oslogstring: 0x2869
   __TEXT.__ustring: 0x78
-  __TEXT.__unwind_info: 0x4308
+  __TEXT.__unwind_info: 0x43a0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1ee8
-  __DATA_CONST.__objc_classlist: 0x1b70
+  __DATA_CONST.__const: 0x1f58
+  __DATA_CONST.__objc_classlist: 0x1b90
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5d88
+  __DATA_CONST.__objc_selrefs: 0x5e48
   __DATA_CONST.__objc_protorefs: 0x48
-  __DATA_CONST.__objc_superrefs: 0xa90
+  __DATA_CONST.__objc_superrefs: 0xab0
   __DATA_CONST.__objc_arraydata: 0x160
-  __DATA_CONST.__got: 0xfd8
-  __AUTH_CONST.__const: 0x17c0
-  __AUTH_CONST.__cfstring: 0x1e0e0
-  __AUTH_CONST.__objc_const: 0x20980
+  __DATA_CONST.__got: 0xfe0
+  __AUTH_CONST.__const: 0x17e0
+  __AUTH_CONST.__cfstring: 0x1e1c0
+  __AUTH_CONST.__objc_const: 0x20bc0
   __AUTH_CONST.__objc_intobj: 0x210
   __AUTH_CONST.__objc_dictobj: 0x140
   __AUTH_CONST.__objc_arrayobj: 0x18

   __AUTH.__objc_data: 0xc80
   __DATA.__objc_ivar: 0x130
   __DATA.__data: 0x6a0
-  __DATA.__bss: 0x408
-  __DATA_DIRTY.__objc_data: 0x105e0
+  __DATA.__bss: 0x400
+  __DATA_DIRTY.__objc_data: 0x10720
   __DATA_DIRTY.__common: 0x8
-  __DATA_DIRTY.__bss: 0x1ea
+  __DATA_DIRTY.__bss: 0x1f2
   - /System/Library/Frameworks/Accelerate.framework/Accelerate
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 5998
-  Symbols:   11930
-  CStrings:  4215
+  Functions: 6053
+  Symbols:   12009
+  CStrings:  4225
 
Symbols:
+ +[UIKeyboardModeSwitcherViewAccessibility _accessibilityPerformValidations:]
+ +[UIKeyboardModeSwitcherViewAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[UIKeyboardModeSwitcherViewAccessibility(SafeCategory) safeCategoryTargetClassName]
+ +[_UINavigationItemProxyAccessibility _accessibilityPerformValidations:]
+ +[_UINavigationItemProxyAccessibility(SafeCategory) safeCategoryBaseClass]
+ +[_UINavigationItemProxyAccessibility(SafeCategory) safeCategoryTargetClassName]
+ -[UIAccessibilityElementMockView accessibilitySupportsTextSelection]
+ -[UIApplicationAccessibility _accessibilityElementsForStatusBar:sorted:]
+ -[UIApplicationAccessibility _accessibilityStatusBarElements:sorted:forWindowScene:]
+ -[UIApplicationAccessibility _axFirstVisibleAccessibleElementInContainer:]
+ -[UIApplicationAccessibility _axShouldDeferOffscreenFirstFocusForElement:]
+ -[UICollectionViewAccessibility _accessibilityViewChildrenWithOptions:]
+ -[UICollectionViewCellAccessibilityElement accessibilitySupportsTextSelection]
+ -[UIDropShadowViewAccessibility _axSheetDimmingViewIsModal]
+ -[UIDropShadowViewAccessibility accessibilityViewIsModal]
+ -[UIFocusRingManagerAccessibility _axCircularFocusRingClipForView:]
+ -[UIIndexBarAccessoryViewAccessibility _axLabelForEntry:lowercaseTitle:]
+ -[UIKeyboardModeSwitcherViewAccessibility accessibilityLabel]
+ -[UIKeyboardModeSwitcherViewAccessibility accessibilityTraits]
+ -[UIKeyboardModeSwitcherViewAccessibility isAccessibilityElement]
+ -[UIResponderAccessibility _axFKAArrowKeysAdjustingValue]
+ -[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]
+ -[UIScrollViewAccessibility accessibilityApplyScrollContentOverride:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]
+ -[UISegmentAccessibility accessibilityFrame]
+ -[UITableViewCellAccessibilityElement accessibilitySupportsTextSelection]
+ -[UITextViewAccessibility accessibilitySupportsTextSelection]
+ -[UITransitionViewAccessibility _accessibilityDimmingViewObscuresScreen]
+ -[_AXUITextViewParagraphElement accessibilitySupportsTextSelection]
+ -[_UIButtonBarButtonAccessibility _axHitTestReachesSelfAtPoint:]
+ -[_UIButtonBarButtonAccessibility accessibilityActivationPoint]
+ -[_UIButtonBarButtonAccessibility accessibilityCustomActions]
+ -[_UIContextMenuUIControllerAccessibility _axModalPresentedByMenuActionOwnsFocusForTriggerElement:]
+ -[_UIInterfaceActionCustomViewRepresentationViewAccessibility accessibilityActivate]
+ -[_UIModernBarButtonAccessibility _accessibilityOwningButtonBarButton]
+ -[_UIModernBarButtonAccessibility accessibilityLabel]
+ -[_UINavigationItemProxyAccessibility initWithDestinationNavigationItem:sourceNavigationItem:]
+ -[_UINavigationItemProxyAccessibility navigationItemUpdatedTitleContent:animated:]
+ -[_UIScenePresentationViewAccessibility _accessibilityHitTest:withEvent:]
+ -[_UITabButtonAccessibility _accessibilityUpdatesOnActivationAfterDelay]
+ GCC_except_table1114
+ GCC_except_table1121
+ GCC_except_table1122
+ GCC_except_table1161
+ GCC_except_table1206
+ GCC_except_table1234
+ GCC_except_table1249
+ GCC_except_table1283
+ GCC_except_table1315
+ GCC_except_table1319
+ GCC_except_table1335
+ GCC_except_table1347
+ GCC_except_table136
+ GCC_except_table1365
+ GCC_except_table1376
+ GCC_except_table1513
+ GCC_except_table1533
+ GCC_except_table1535
+ GCC_except_table1549
+ GCC_except_table1577
+ GCC_except_table1580
+ GCC_except_table1583
+ GCC_except_table1604
+ GCC_except_table1653
+ GCC_except_table1682
+ GCC_except_table1683
+ GCC_except_table171
+ GCC_except_table1779
+ GCC_except_table1790
+ GCC_except_table1801
+ GCC_except_table1802
+ GCC_except_table1806
+ GCC_except_table1809
+ GCC_except_table1811
+ GCC_except_table1818
+ GCC_except_table1840
+ GCC_except_table1869
+ GCC_except_table1872
+ GCC_except_table1921
+ GCC_except_table1927
+ GCC_except_table1947
+ GCC_except_table1961
+ GCC_except_table1972
+ GCC_except_table2019
+ GCC_except_table206
+ GCC_except_table2113
+ GCC_except_table2116
+ GCC_except_table2165
+ GCC_except_table2187
+ GCC_except_table2271
+ GCC_except_table2301
+ GCC_except_table2306
+ GCC_except_table2314
+ GCC_except_table2333
+ GCC_except_table2350
+ GCC_except_table2406
+ GCC_except_table2434
+ GCC_except_table2444
+ GCC_except_table2452
+ GCC_except_table2468
+ GCC_except_table2487
+ GCC_except_table2583
+ GCC_except_table262
+ GCC_except_table2667
+ GCC_except_table2723
+ GCC_except_table2797
+ GCC_except_table2801
+ GCC_except_table2819
+ GCC_except_table2838
+ GCC_except_table2955
+ GCC_except_table2989
+ GCC_except_table3041
+ GCC_except_table3065
+ GCC_except_table3119
+ GCC_except_table3203
+ GCC_except_table3209
+ GCC_except_table3262
+ GCC_except_table3275
+ GCC_except_table3406
+ GCC_except_table3407
+ GCC_except_table3463
+ GCC_except_table3523
+ GCC_except_table3660
+ GCC_except_table3733
+ GCC_except_table3752
+ GCC_except_table3771
+ GCC_except_table3887
+ GCC_except_table3918
+ GCC_except_table3955
+ GCC_except_table3957
+ GCC_except_table3991
+ GCC_except_table3993
+ GCC_except_table4007
+ GCC_except_table4015
+ GCC_except_table402
+ GCC_except_table4029
+ GCC_except_table4030
+ GCC_except_table4056
+ GCC_except_table4061
+ GCC_except_table4091
+ GCC_except_table4111
+ GCC_except_table4116
+ GCC_except_table4124
+ GCC_except_table4126
+ GCC_except_table4142
+ GCC_except_table4156
+ GCC_except_table4195
+ GCC_except_table4213
+ GCC_except_table4219
+ GCC_except_table4231
+ GCC_except_table4253
+ GCC_except_table4260
+ GCC_except_table4399
+ GCC_except_table447
+ GCC_except_table4515
+ GCC_except_table459
+ GCC_except_table4704
+ GCC_except_table4707
+ GCC_except_table4708
+ GCC_except_table4730
+ GCC_except_table4764
+ GCC_except_table4769
+ GCC_except_table4771
+ GCC_except_table4780
+ GCC_except_table4784
+ GCC_except_table4785
+ GCC_except_table4786
+ GCC_except_table4792
+ GCC_except_table4793
+ GCC_except_table4796
+ GCC_except_table4802
+ GCC_except_table4818
+ GCC_except_table4834
+ GCC_except_table4851
+ GCC_except_table4921
+ GCC_except_table497
+ GCC_except_table4980
+ GCC_except_table507
+ GCC_except_table5093
+ GCC_except_table5104
+ GCC_except_table5120
+ GCC_except_table5145
+ GCC_except_table5147
+ GCC_except_table5152
+ GCC_except_table519
+ GCC_except_table5319
+ GCC_except_table5453
+ GCC_except_table5550
+ GCC_except_table556
+ GCC_except_table5646
+ GCC_except_table5674
+ GCC_except_table5719
+ GCC_except_table5739
+ GCC_except_table5845
+ GCC_except_table5851
+ GCC_except_table5866
+ GCC_except_table5882
+ GCC_except_table5903
+ GCC_except_table5915
+ GCC_except_table5932
+ GCC_except_table594
+ GCC_except_table606
+ GCC_except_table608
+ GCC_except_table618
+ GCC_except_table624
+ GCC_except_table655
+ GCC_except_table662
+ GCC_except_table763
+ GCC_except_table765
+ GCC_except_table766
+ GCC_except_table772
+ GCC_except_table774
+ GCC_except_table775
+ GCC_except_table777
+ GCC_except_table805
+ GCC_except_table819
+ GCC_except_table841
+ GCC_except_table914
+ _AXIsHostedScene
+ _AXLocalizationForLocale
+ _AXScrollViewTotalPages
+ _OBJC_CLASS_$_UIKeyboardModeSwitcherViewAccessibility
+ _OBJC_CLASS_$__UINavigationItemProxyAccessibility
+ _OBJC_CLASS_$___UIKeyboardModeSwitcherViewAccessibility_super
+ _OBJC_CLASS_$____UINavigationItemProxyAccessibility_super
+ _OBJC_METACLASS_$_UIKeyboardModeSwitcherViewAccessibility
+ _OBJC_METACLASS_$__UINavigationItemProxyAccessibility
+ _OBJC_METACLASS_$___UIKeyboardModeSwitcherViewAccessibility_super
+ _OBJC_METACLASS_$____UINavigationItemProxyAccessibility_super
+ __AXSBrailleScreenInputEnabled
+ __AXTransferNavigationItemAccessibilityLabel
+ __OBJC_$_CLASS_METHODS_UIKeyboardModeSwitcherViewAccessibility(SafeCategory)
+ __OBJC_$_CLASS_METHODS__UINavigationItemProxyAccessibility(SafeCategory)
+ __OBJC_$_INSTANCE_METHODS_UIKeyboardModeSwitcherViewAccessibility
+ __OBJC_$_INSTANCE_METHODS__UINavigationItemProxyAccessibility
+ __OBJC_CLASS_RO_$_UIKeyboardModeSwitcherViewAccessibility
+ __OBJC_CLASS_RO_$__UINavigationItemProxyAccessibility
+ __OBJC_CLASS_RO_$___UIKeyboardModeSwitcherViewAccessibility_super
+ __OBJC_CLASS_RO_$____UINavigationItemProxyAccessibility_super
+ __OBJC_METACLASS_RO_$_UIKeyboardModeSwitcherViewAccessibility
+ __OBJC_METACLASS_RO_$__UINavigationItemProxyAccessibility
+ __OBJC_METACLASS_RO_$___UIKeyboardModeSwitcherViewAccessibility_super
+ __OBJC_METACLASS_RO_$____UINavigationItemProxyAccessibility_super
+ ___102-[UITableViewAccessibility _accessibilitySortedElementsWithinPreservingFloatingHeader:sortedElements:]_block_invoke_2
+ ___141-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]_block_invoke
+ ___141-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]_block_invoke_2
+ ___141-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]_block_invoke_3
+ ___141-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:]_block_invoke_4
+ ___152-[UIKeyboardLayoutStarAccessibility continueFromInternationalActionForTouchUp:withActions:timestamp:interval:didLongPress:prevActions:executionContext:]_block_invoke_2
+ ___71-[UIKeyboardLayoutStarAccessibility _accessibilityCreateElementForKey:]_block_invoke_2
+ ___74-[UIApplicationAccessibility _axFirstVisibleAccessibleElementInContainer:]_block_invoke
+ ___74-[UIApplicationAccessibility _axShouldDeferOffscreenFirstFocusForElement:]_block_invoke
+ ___84-[_UIInterfaceActionCustomViewRepresentationViewAccessibility accessibilityActivate]_block_invoke
+ ___87-[_UINavigationBarTitleControlAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke_2
+ ___block_descriptor_40_e16_B16?0"UIView"8lu32l8
+ ___block_descriptor_40_e8_32r_e12_v24?08^B16lr32l8
+ ___block_descriptor_48_e8_32w40w_e15_"NSString"8?0lw32l8w40l8
+ ___os_log_helper_16_3_2_8_65_8_65
+ _accessibilityLocalizedStringForLanguage
+ _axLanguageOverridingAllContainedElements
+ _fmodf
- GCC_except_table1109
- GCC_except_table1116
- GCC_except_table1117
- GCC_except_table1156
- GCC_except_table1201
- GCC_except_table1229
- GCC_except_table1244
- GCC_except_table1278
- GCC_except_table1308
- GCC_except_table1321
- GCC_except_table1334
- GCC_except_table135
- GCC_except_table1350
- GCC_except_table1352
- GCC_except_table1500
- GCC_except_table1520
- GCC_except_table1522
- GCC_except_table1536
- GCC_except_table1563
- GCC_except_table1566
- GCC_except_table1569
- GCC_except_table1590
- GCC_except_table1639
- GCC_except_table1668
- GCC_except_table1669
- GCC_except_table170
- GCC_except_table1764
- GCC_except_table1775
- GCC_except_table1786
- GCC_except_table1787
- GCC_except_table1791
- GCC_except_table1794
- GCC_except_table1796
- GCC_except_table1803
- GCC_except_table1825
- GCC_except_table1854
- GCC_except_table1857
- GCC_except_table1906
- GCC_except_table1912
- GCC_except_table1932
- GCC_except_table1946
- GCC_except_table1956
- GCC_except_table2002
- GCC_except_table205
- GCC_except_table2096
- GCC_except_table2099
- GCC_except_table2147
- GCC_except_table2169
- GCC_except_table2253
- GCC_except_table2277
- GCC_except_table2282
- GCC_except_table2290
- GCC_except_table2309
- GCC_except_table2326
- GCC_except_table2382
- GCC_except_table2410
- GCC_except_table2420
- GCC_except_table2427
- GCC_except_table2443
- GCC_except_table2462
- GCC_except_table2555
- GCC_except_table261
- GCC_except_table2639
- GCC_except_table2695
- GCC_except_table2763
- GCC_except_table2767
- GCC_except_table2785
- GCC_except_table2804
- GCC_except_table2921
- GCC_except_table2954
- GCC_except_table3005
- GCC_except_table3028
- GCC_except_table3080
- GCC_except_table3164
- GCC_except_table3170
- GCC_except_table3223
- GCC_except_table3236
- GCC_except_table3365
- GCC_except_table3366
- GCC_except_table3422
- GCC_except_table3482
- GCC_except_table3619
- GCC_except_table3692
- GCC_except_table3711
- GCC_except_table3730
- GCC_except_table3846
- GCC_except_table3877
- GCC_except_table3914
- GCC_except_table3916
- GCC_except_table3949
- GCC_except_table3951
- GCC_except_table3965
- GCC_except_table3973
- GCC_except_table3987
- GCC_except_table3988
- GCC_except_table401
- GCC_except_table4014
- GCC_except_table4019
- GCC_except_table4040
- GCC_except_table4049
- GCC_except_table4069
- GCC_except_table4074
- GCC_except_table4084
- GCC_except_table4100
- GCC_except_table4114
- GCC_except_table4153
- GCC_except_table4171
- GCC_except_table4177
- GCC_except_table4189
- GCC_except_table4211
- GCC_except_table4218
- GCC_except_table4356
- GCC_except_table446
- GCC_except_table4472
- GCC_except_table458
- GCC_except_table4661
- GCC_except_table4664
- GCC_except_table4665
- GCC_except_table4687
- GCC_except_table4721
- GCC_except_table4726
- GCC_except_table4728
- GCC_except_table4737
- GCC_except_table4741
- GCC_except_table4742
- GCC_except_table4743
- GCC_except_table4749
- GCC_except_table4750
- GCC_except_table4753
- GCC_except_table4759
- GCC_except_table4775
- GCC_except_table4790
- GCC_except_table4807
- GCC_except_table4876
- GCC_except_table4934
- GCC_except_table494
- GCC_except_table504
- GCC_except_table5047
- GCC_except_table5058
- GCC_except_table5074
- GCC_except_table5099
- GCC_except_table5101
- GCC_except_table5106
- GCC_except_table515
- GCC_except_table5273
- GCC_except_table5401
- GCC_except_table5496
- GCC_except_table552
- GCC_except_table5592
- GCC_except_table5620
- GCC_except_table5665
- GCC_except_table5684
- GCC_except_table5790
- GCC_except_table5796
- GCC_except_table5811
- GCC_except_table5827
- GCC_except_table5848
- GCC_except_table5860
- GCC_except_table5877
- GCC_except_table590
- GCC_except_table602
- GCC_except_table604
- GCC_except_table610
- GCC_except_table620
- GCC_except_table651
- GCC_except_table658
- GCC_except_table759
- GCC_except_table761
- GCC_except_table762
- GCC_except_table764
- GCC_except_table770
- GCC_except_table771
- GCC_except_table773
- GCC_except_table801
- GCC_except_table815
- GCC_except_table837
- GCC_except_table910
- ___113-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:]_block_invoke
- ___113-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:]_block_invoke_2
- ___113-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:]_block_invoke_3
- ___113-[UIScrollViewAccessibility accessibilityApplyScrollContent:sendScrollStatus:animateWithDuration:animationCurve:]_block_invoke_4
CStrings:
+ "AXProxyDestinationNavigationItem"
+ "No local children for remote %{private}@, fell back to remote first/last %{private}@"
+ "UIKeyboardModeSwitcherView"
+ "UIKeyboardModeSwitcherViewAccessibility"
+ "_UINavigationItemProxy"
+ "_UINavigationItemProxyAccessibility"
+ "_accessibilityPreferredFocusedWindow"
+ "dimmingView"
+ "initWithDestinationNavigationItem:sourceNavigationItem:"
+ "keyboardModeSwitcherView"
+ "navigationItemUpdatedTitleContent:animated:"
+ "rdar://179296860 First-focus deferred off-screen element %{private}@ to visible %{private}@ in a pre-scrolled container"
+ "rdar://179296860 First-focus resolved to an off-screen element inside a scrolled-away container (expected a visible element): %{private}@"
- "_imageButton"
- "_titleButton"
- "traitCollection"
```
