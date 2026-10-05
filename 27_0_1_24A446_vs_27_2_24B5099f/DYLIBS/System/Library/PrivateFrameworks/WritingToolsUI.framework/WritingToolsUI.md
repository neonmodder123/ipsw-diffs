## WritingToolsUI

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/WritingToolsUI`

```diff

-149.104.0.0.0
-  __TEXT.__text: 0x6cf40
-  __TEXT.__objc_methlist: 0x4ccc
-  __TEXT.__const: 0x30c4
-  __TEXT.__cstring: 0x3737
-  __TEXT.__oslogstring: 0x1f2d
-  __TEXT.__gcc_except_tab: 0xd6c
+151.1.9.0.0
+  __TEXT.__text: 0x6d61c
+  __TEXT.__objc_methlist: 0x4dcc
+  __TEXT.__const: 0x30b4
+  __TEXT.__cstring: 0x3777
+  __TEXT.__oslogstring: 0x21ed
+  __TEXT.__gcc_except_tab: 0xdc8
   __TEXT.__dlopen_cstrs: 0xb4
-  __TEXT.__swift5_typeref: 0xdf52
-  __TEXT.__swift5_capture: 0x47c
-  __TEXT.__swift5_reflstr: 0xe3c
+  __TEXT.__swift5_typeref: 0xde2c
+  __TEXT.__swift5_capture: 0x45c
+  __TEXT.__swift5_reflstr: 0xe7c
   __TEXT.__swift5_assocty: 0x290
-  __TEXT.__constg_swiftt: 0xfec
-  __TEXT.__swift5_fieldmd: 0xcbc
+  __TEXT.__constg_swiftt: 0x1004
+  __TEXT.__swift5_fieldmd: 0xce0
   __TEXT.__swift5_builtin: 0x104
   __TEXT.__swift5_proto: 0x194
   __TEXT.__swift5_types: 0xc0

   __TEXT.__swift_as_ret: 0x1c
   __TEXT.__swift_as_cont: 0x20
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x1cc0
+  __TEXT.__unwind_info: 0x1d08
   __TEXT.__eh_frame: 0x8c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xe10
+  __DATA_CONST.__const: 0xe48
   __DATA_CONST.__objc_classlist: 0x178
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0xf8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x30d8
+  __DATA_CONST.__objc_selrefs: 0x3180
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0xd0
   __DATA_CONST.__objc_arraydata: 0x70
-  __DATA_CONST.__got: 0xa40
-  __AUTH_CONST.__const: 0x2140
+  __DATA_CONST.__got: 0xa48
+  __AUTH_CONST.__const: 0x2108
   __AUTH_CONST.__cfstring: 0xfe0
-  __AUTH_CONST.__objc_const: 0x69c8
-  __AUTH_CONST.__objc_intobj: 0x570
+  __AUTH_CONST.__objc_const: 0x6a28
+  __AUTH_CONST.__objc_intobj: 0x588
   __AUTH_CONST.__objc_doubleobj: 0x70
   __AUTH_CONST.__objc_arrayobj: 0x60
   __AUTH_CONST.__auth_got: 0xf60
-  __AUTH.__objc_data: 0x14b0
+  __AUTH.__objc_data: 0x14d0
   __AUTH.__data: 0x900
-  __DATA.__objc_ivar: 0x38c
-  __DATA.__data: 0x1f08
+  __DATA.__objc_ivar: 0x390
+  __DATA.__data: 0x1ef0
   __DATA.__bss: 0x3510
-  __DATA.__common: 0x118
+  __DATA.__common: 0x120
   __DATA_DIRTY.__objc_data: 0xf0
   __DATA_DIRTY.__data: 0x8
   __DATA_DIRTY.__bss: 0x90

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3011
-  Symbols:   3210
-  CStrings:  553
+  Functions: 3035
+  Symbols:   3227
+  CStrings:  562
 
Symbols:
+ +[WTFeedbackProxy sendComposeFeedback:range:finished:compositionSessionType:]
+ +[WTUIActionHostToClient actionForPerformRequestedTool:precomputedData:]
+ -[WTFullScreenContainerViewController performRequestedTool:precomputedData:]
+ -[WTMainPopoverViewController adaptivePresentationStyleForPresentationController:traitCollection:]
+ -[WTMainPopoverViewController performRequestedTool:precomputedData:]
+ -[WTSceneHostedInputDashboardViewController performRequestedTool:precomputedData:]
+ -[WTWritingToolsController _targetCanHostInlineEditing]
+ -[WTWritingToolsController _targetIsWebKitTextInput]
+ -[WTWritingToolsController _targetPrefersLimitedUI]
+ -[WTWritingToolsController canPerformRequestedToolOnCurrentSession]
+ -[WTWritingToolsController performRequestedTool:precomputedData:]
+ -[WTWritingToolsController performRequestedToolOnCurrentSession]
+ -[WTWritingToolsController precomputedData]
+ -[WTWritingToolsController rewriteResultApplied]
+ -[WTWritingToolsController setPrecomputedData:]
+ -[WTWritingToolsController setRewriteResultApplied:]
+ -[_WTReplaceTextEffect clipsToDestinationRect]
+ -[_WTReplaceTextEffect setClipsToDestinationRect:]
+ -[_WTTextEffectView hasManagedFrame]
+ -[_WTTextEffectView replaceSourceEffect]
+ -[_WTTextEffectView setHasManagedFrame:]
+ -[_WTTextEffectView setReplaceSourceEffect:]
+ GCC_except_table10
+ GCC_except_table120
+ GCC_except_table126
+ GCC_except_table163
+ GCC_except_table179
+ GCC_except_table182
+ GCC_except_table226
+ GCC_except_table233
+ GCC_except_table235
+ GCC_except_table237
+ GCC_except_table74
+ GCC_except_table82
+ _OBJC_CLASS_$_WTPrecomputedData
+ _OBJC_IVAR_$_WTWritingToolsController._precomputedData
+ _OBJC_IVAR_$_WTWritingToolsController._rewriteResultApplied
+ _OBJC_IVAR_$__WTReplaceTextEffect._clipsToDestinationRect
+ _OBJC_IVAR_$__WTTextEffectView._hasManagedFrame
+ _OBJC_IVAR_$__WTTextEffectView._replaceSourceEffect
+ ___block_descriptor_64_e8_32s40s48bs56w_e5_v8?0lw56l8s32l8s48l8s40l8
+ _keypath_get.30Tm
+ _keypath_get.32Tm
+ _keypath_get.40Tm
+ _keypath_get.52Tm
+ _keypath_set.33Tm
- +[WTFeedbackProxy sendComposeFeedback:range:finished:]
- +[WTFeedbackProxy sendRewriteFeedback:range:finished:]
- GCC_except_table109
- GCC_except_table115
- GCC_except_table152
- GCC_except_table168
- GCC_except_table171
- GCC_except_table212
- GCC_except_table219
- GCC_except_table221
- GCC_except_table223
- GCC_except_table34
- GCC_except_table72
- _OBJC_IVAR_$_WTWritingToolsController._precomputedCitationsJSON
- _OBJC_IVAR_$_WTWritingToolsController._precomputedContentAdvisoriesJSON
- _OBJC_IVAR_$_WTWritingToolsController._precomputedResultReplacesExisting
- _OBJC_IVAR_$_WTWritingToolsController._precomputedResultText
- _OUTLINED_FUNCTION_4
- ___62-[WTMainPopoverViewController setFeedbackHiddenDetentEnabled:]_block_invoke
- ___76-[WTWritingToolsController _presentMainPopoverViewControllerWithCompletion:]_block_invoke_2
- _keypath_get.29Tm
- _keypath_get.31Tm
- _keypath_get.39Tm
- _keypath_get.51Tm
- _keypath_set.32Tm
- _symbolic ___________y_____yABy_____y_____y_____y__________GG______Qo______G_AIQo______y_____GGAAt 7SwiftUI6SpacerV AA15ModifiedContentV AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonH0Rd__lFQO AgAEAHyQrqd__AaIRd__lFQO AA0J0V AA5LabelV AA4TextV AA5ImageV AA010BorderlessjH0V 012WritingToolsB0011ContextMenukH8Modifier33_307A59342D234FEA7D5506526C741E19LLV AA011_ForegroundhS0V AA5ColorV
- _symbolic _____y_____G 7SwiftUI6ButtonV AA5ImageV
- _symbolic _____y___________y___________y_____yAEy_____y_____y_____y__________GG______Qo______G_ALQo______y_____GGADQPGG 7SwiftUI13_VariadicViewO4TreeV AA13_HStackLayoutV AA12TupleContentV AA6SpacerV AA08ModifiedI0V AA0D0PAAE11buttonStyleyQrqd__AA015PrimitiveButtonM0Rd__lFQO AoAEAPyQrqd__AaQRd__lFQO AA0O0V AA5LabelV AA4TextV AA5ImageV AA010BorderlessoM0V 012WritingToolsB0011ContextMenupM8Modifier33_307A59342D234FEA7D5506526C741E19LLV AA011_ForegroundmX0V AA5ColorV
- _symbolic _____y_____yAAy_____y_____y_____y__________GG______Qo______G_AHQo______y_____GG 7SwiftUI15ModifiedContentV AA4ViewPAAE11buttonStyleyQrqd__AA015PrimitiveButtonG0Rd__lFQO AeAEAFyQrqd__AaGRd__lFQO AA0I0V AA5LabelV AA4TextV AA5ImageV AA010BorderlessiG0V 012WritingToolsB0011ContextMenujG8Modifier33_307A59342D234FEA7D5506526C741E19LLV AA011_ForegroundgR0V AA5ColorV
CStrings:
+ "DebugForceUnsafeOutput"
+ "Skipping stale main popover presentation (current=%@, expected=%@)"
+ "didEndWritingToolsSession:accepted: threw: %{public}@"
+ "endWritingToolsWithError: rewriting active → accepted=%d (resultApplied=%d error=%d)"
+ "performRequestedTool: %ld (delegate: %@)"
+ "performRequestedToolOnCurrentSession: delegate did not handle performRequestedTool:precomputedData:"
+ "performRequestedToolOnCurrentSession: not performing on current session (session:%s sessionIsRewrite:%s)"
+ "startWritingTools requestedTool=%ld isWritingToolsActive=%d precomputedLen=%lu replacesExisting=%d"
+ "startupOptions: editable=%d wantsInlineEditing=%d targetPrefersLimitedUI=%d isWebKitView=%d precomputedLen=%lu"
+ "targetPrefersLimitedUI"
+ "writingToolsSession:didReceiveAction: threw: %{public}@"
- "C"
- "startWritingTools"
```
