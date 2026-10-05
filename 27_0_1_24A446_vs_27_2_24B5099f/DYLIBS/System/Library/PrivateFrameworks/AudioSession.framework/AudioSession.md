## AudioSession

> `/System/Library/PrivateFrameworks/AudioSession.framework/AudioSession`

```diff

-449.107.0.0.0
+449.204.0.0.0
   __TEXT.__text: 0x4f098
   __TEXT.__realtime: 0x178
   __TEXT.__objc_methlist: 0x2364
   __TEXT.__gcc_except_tab: 0x9010
   __TEXT.__cstring: 0x3a4f
   __TEXT.__const: 0x207
-  __TEXT.__oslogstring: 0x47f4
+  __TEXT.__oslogstring: 0x4878
   __TEXT.__unwind_info: 0x2fa0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_floatobj: 0x40
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x550
+  __AUTH.__objc_data: 0x500
   __DATA.__objc_ivar: 0x130
   __DATA.__data: 0x4e8
   __DATA.__common: 0x1
   __DATA.__bss: 0x100
-  __DATA_DIRTY.__objc_data: 0x500
+  __DATA_DIRTY.__objc_data: 0x550
   __DATA_DIRTY.__data: 0x60
   __DATA_DIRTY.__bss: 0x3b0
   - /System/Library/Frameworks/AVRouting.framework/AVRouting
CStrings:
+ "%25s:%-5d __delegate_identifier__:Performance Diagnostics__:::____message__:This method can lead to UI unresponsiveness if called on the main thread while the audio session is active."
+ "%25s:%-5d __delegate_identifier__:Performance Diagnostics__:::____message__:This method can lead to UI unresponsiveness if called on the main thread. Consider using the asynchronous activate/deactivate API instead for calls from the main thread."
- "%25s:%-5d This method can lead to UI unresponsiveness if called on the main thread while the audio session is active."
- "%25s:%-5d This method can lead to UI unresponsiveness if called on the main thread. Consider using the asynchronous activate/deactivate API instead for calls from the main thread."
```
