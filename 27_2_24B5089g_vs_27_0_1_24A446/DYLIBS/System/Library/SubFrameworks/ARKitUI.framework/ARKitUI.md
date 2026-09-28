## ARKitUI

> `/System/Library/SubFrameworks/ARKitUI.framework/ARKitUI`

```diff

-781.40.3.0.0
-  __TEXT.__text: 0x2bdcc
+781.0.7.0.0
+  __TEXT.__text: 0x2b9b4
   __TEXT.__objc_methlist: 0x2988
-  __TEXT.__const: 0x958
-  __TEXT.__oslogstring: 0x1b1f
-  __TEXT.__cstring: 0xdf2
+  __TEXT.__const: 0x948
+  __TEXT.__oslogstring: 0x192e
+  __TEXT.__cstring: 0xdcf
   __TEXT.__gcc_except_tab: 0xcd8
   __TEXT.__unwind_info: 0xc20
   __TEXT.__objc_stubs: 0x0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 987
-  Symbols:   2154
-  CStrings:  241
+  Symbols:   2153
+  CStrings:  235
 
Symbols:
- _NSStringFromCGSize
Functions:
~ -[ARSCNCompositor setCurrentSize:] : 232 -> 236
~ -[ARSCNCompositor orientedVerticesWithResolution:] : 344 -> 360
~ -[ARSCNView _assignViewLayerToSessionOnMainThread] : 380 -> 164
~ -[ARSCNView _viewRotationAngleDidChange:] : 416 -> 276
~ -[ARSCNView session:didChangeViewRotationAngle:] : 308 -> 420
~ -[ARSCNView _applyPreviewRotationFromAngle:hasOldAngle:toAngle:] : 892 -> 588
~ -[ARSCNView _publishOrientationSwapAtAngle:fromAngle:] : 1640 -> 1360
~ -[ARSCNView didMoveToWindow] : 576 -> 336
CStrings:
+ "%{public}@ <%p>: viewRotationAngle updated to %.0f"
+ "viewRotationAngle updated to %.0f"
- "%{public}@ <%p>: Assigned viewLayer to session <%p>. window=%d, bounds=%@, sessionAngle=%.0f"
- "%{public}@ <%p>: Counter-rotating %.0f -> %.0f: oldDelta=%.1f, duration=%.3f"
- "%{public}@ <%p>: No previous angle; skipping counter-rotation for %.0f."
- "%{public}@ <%p>: Publishing orientation swap %ld -> %ld (angle %.0f -> %.0f). baseline=%@ (has=%d), pendingRotationBaselineSize=%@, snapshotState=%ld"
- "%{public}@ <%p>: didMoveToWindow: window=%d, bounds=%@, viewRotationAngle=%.0f, hasBaselineBounds=%d"
- "%{public}@ <%p>: viewRotationAngle updated to %.0f (from %.0f, hasBaselineBounds %d, %s)"
- "adopting silently"
- "counter-rotating"
```
