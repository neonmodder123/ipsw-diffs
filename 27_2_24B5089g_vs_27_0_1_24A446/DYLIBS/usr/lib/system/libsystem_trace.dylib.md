## libsystem_trace.dylib

> `/usr/lib/system/libsystem_trace.dylib`

```diff

-1966.40.15.0.2
-  __TEXT.__text: 0x1bb64
+1966.2.1.0.0
+  __TEXT.__text: 0x1b7e4
   __TEXT.__delay_stubs: 0x180
   __TEXT.__delay_helper: 0xa4
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0xf4
-  __TEXT.__const: 0x2c0
-  __TEXT.__cstring: 0x1d32
+  __TEXT.__const: 0x2b0
+  __TEXT.__cstring: 0x1c6b
   __TEXT.__gcc_except_tab: 0x64
   __TEXT.__oslogstring: 0x137
   __TEXT.__unwind_info: 0x530

   - /usr/lib/system/libxpc.dylib
   Functions: 382
   Symbols:   862
-  CStrings:  424
+  CStrings:  420
 
Functions:
~ __os_log_impl_flatten_and_send : 8580 -> 8572
~ _os_metric_dimensions_create : 128 -> 124
~ __os_metric_create_impl : 596 -> 312
~ __os_metric_uint64_op_impl : 844 -> 696
~ __os_metric_int64_op_impl : 864 -> 708
~ __os_metric_double_op_impl : 896 -> 716
~ __os_metric_reset_data : 284 -> 228
~ __os_metric_emit_value_impl : 1200 -> 1140
CStrings:
- "BUG IN CLIENT OF LIBTRACE: custom histogram cannot have greater than (128 / 2) bins."
- "_os_metric_get_bin_count"
- "md->type == _OS_METRIC_TYPE_HISTOGRAM"
- "metric->metadata.type == _OS_METRIC_TYPE_HISTOGRAM"
```
