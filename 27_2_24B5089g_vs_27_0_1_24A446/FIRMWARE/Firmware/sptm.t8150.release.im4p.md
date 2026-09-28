## sptm.t8150.release.im4p

> `Firmware/sptm.t8150.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA.__auth_ptr`

```diff

-820.40.20.0.0
-  __TEXT.__cstring: 0x15db4
+820.0.22.0.0
+  __TEXT.__cstring: 0x15c52
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
-  __DATA_CONST.__const: 0x7c00
-  __LATE_CONST.__late_const: 0x7c890
-  __TEXT_EXEC.__text: 0x61314
+  __DATA_CONST.__const: 0x7bf0
+  __LATE_CONST.__late_const: 0x7c880
+  __TEXT_EXEC.__text: 0x612f4
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __DATA.__bss: 0x60a8
   __DATA.__common: 0x9088
   __BOOTDATA.__data: 0x18000
-  Functions: 406
+  Functions: 405
   Symbols:   1
-  CStrings:  2569
+  CStrings:  2559
 
CStrings:
+ "%s(%s:%d) - fte(%p), new_type(%s), page_flags(%u), read_refcnt(%d)\n"
+ "SPTM-820.0.22|2026-08-08:13:24:32.076410|"
- "%s(%s:%d) - fte(%p), new_type(%s), page_flags(%u), read_refcnt(%d) iommu_read_refcnt(%u)\n"
- "%s: %s: iommu_read_refcnt (0x%hhx) > read_refcnt(0x%x) for FTE %p"
- "%s: unexpected size %u for property '%s'"
- "/chosen/manifest-properties"
- "SPTM-820.40.20|2026-09-13:19:38:35.360456|"
- "VIOLATION_NVME_ILLEGAL_HIBERNATION_QUEUE_LATCH"
- "VIOLATION_T8110_DART_UNGANG_GAPF_RACE"
- "enforce_no_hib_latch"
- "internal-use-only-unit"
- "iuos"
- "sptm_allow_vm_isa_internal_guests"
- "sptm_is_iuou_or_iuos_device"
```
