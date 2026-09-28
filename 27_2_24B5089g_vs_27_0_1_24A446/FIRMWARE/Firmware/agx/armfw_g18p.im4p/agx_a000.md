## agx_a000

> `Firmware/agx/armfw_g18p.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT._rtk_patchbay`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3cfc8
+  __TEXT.__text: 0x3cfb4
   __TEXT.__gxf_code: 0x4f40
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
-  __TEXT.__const: 0x107d
+  __TEXT.__const: 0x1068
   __TEXT._rtk_tunables: 0x740
   __TEXT._rtk_patchbay: 0x231
   __TEXT.__cstring: 0x2346
Functions:
~ sub_fffffc000000b82c : 332 -> 316
~ sub_fffffc000003434c -> sub_fffffc000003433c : 388 -> 384
~ sub_fffffc000003ce84 -> sub_fffffc000003ce70 : 332 -> 324
CStrings:
+ "Aug 13 2026 21:28:28"
- "Sep 13 2026 21:50:33"
```
