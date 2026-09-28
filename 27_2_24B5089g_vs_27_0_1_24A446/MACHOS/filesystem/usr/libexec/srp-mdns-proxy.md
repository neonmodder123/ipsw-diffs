## srp-mdns-proxy

> `/usr/libexec/srp-mdns-proxy`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-3111.40.42.0.0
-  __TEXT.__text: 0x8b630
+3111.0.5.0.1
+  __TEXT.__text: 0x8b500
   __TEXT.__auth_stubs: 0x15f0
   __TEXT.__objc_stubs: 0x180
   __TEXT.__objc_methlist: 0x22c
   __TEXT.__const: 0x2e5
-  __TEXT.__cstring: 0x8f27
-  __TEXT.__oslogstring: 0x1423e
+  __TEXT.__cstring: 0x8e75
+  __TEXT.__oslogstring: 0x141ca
   __TEXT.__objc_methname: 0x506
   __TEXT.__objc_classname: 0x35
   __TEXT.__objc_methtype: 0x237
-  __TEXT.__unwind_info: 0x630
+  __TEXT.__unwind_info: 0x638
   __TEXT.__eh_frame: 0x7c
   __DATA_CONST.__const: 0x958
   __DATA_CONST.__cfstring: 0x140

   - /usr/lib/libsqlite3.dylib
   Functions: 489
   Symbols:   1184
-  CStrings:  2705
+  CStrings:  2700
 
Symbols:
+ _thread_service_note
- _thread_service_note_function
Functions:
~ _dnssd_client_action_probing : 3000 -> 2984
~ _dnssd_client_service_unpublish : 88 -> 80
~ _thread_service_note_function -> _thread_service_note : 1132 -> 1168
~ _adv_ctl_start_thread_shutdown : 620 -> 604
~ _service_tracker_callback : 3000 -> 2972
~ _service_tracker_services_are_awaiting_removal : 264 -> 256
~ _srp_mdns_cancel_previous_instance : 536 -> 524
~ _prepare_update : 22056 -> 22068
~ _register_instance : 1684 -> 1680
~ _instance_vec_txns_forget : 576 -> 368
~ _service_publisher_have_competing_unicast_service : 512 -> 484
~ _service_publisher_anycast_service_present : 144 -> 132
~ _service_publisher_stale_service_present : 264 -> 248
~ _service_publisher_queue_run : 1448 -> 1440
~ _service_publisher_update_callback : 1648 -> 1660
CStrings:
+ "%{public}s: service TLV value must be at least 6 bytes long (was %u bytes long)"
+ "18:55:30"
+ "Aug  8 2026"
+ "thread_service_note"
- "%{public}s: could not parse u32 (%u bytes were available)"
- "%{public}s: forgetting previous sdref %p on %{public}s %p %{private, mask.hash}s instance %{private, mask.hash}s . %{private, mask.hash}s"
- "08:59:03"
- "Sep 12 2026"
- "dnssd_client_service_unpublish"
- "service_publisher_anycast_service_present"
- "service_publisher_have_competing_unicast_service"
- "service_publisher_stale_service_present"
- "service_tracker_thread_service_note"
```
