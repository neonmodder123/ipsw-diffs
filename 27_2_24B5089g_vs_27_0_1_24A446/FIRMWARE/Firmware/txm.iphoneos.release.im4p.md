## txm.iphoneos.release.im4p

> `Firmware/txm.iphoneos.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__auth_ptr`
- `__TEXT_BOOT_EXEC.__bootcode`
- `__DATA.__data`

```diff

   __TEXT.__const: 0x12338
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
-  __DATA_CONST.__const: 0xd5c8
+  __DATA_CONST.__const: 0xd5a0
   __DATA_CONST.__auth_ptr: 0x70
-  __TEXT_EXEC.__text: 0x49c38
+  __TEXT_EXEC.__text: 0x49a90
   __TEXT_EXEC.__exc: 0x8a0
   __TEXT_BOOT_EXEC.__text: 0x4060
   __TEXT_BOOT_EXEC.__bootcode: 0x278
Functions:
~ sub_fffffff01703e9f0 : 1872 -> 1868
~ sub_fffffff01703f75c -> sub_fffffff01703f758 : 3008 -> 2824
~ sub_fffffff01704f0d0 -> sub_fffffff01704f014 : 572 -> 524
~ sub_fffffff01704f30c -> sub_fffffff01704f220 : 916 -> 800
~ sub_fffffff017050d14 -> sub_fffffff017050bb4 : 160 -> 144
~ sub_fffffff0170511e4 -> sub_fffffff017051074 : 156 -> 152
~ sub_fffffff0170513fc -> sub_fffffff017051288 : 144 -> 160
~ sub_fffffff01705148c -> sub_fffffff017051328 : 808 -> 764
~ sub_fffffff0170631ec -> sub_fffffff01706305c : 204 -> 200
~ sub_fffffff017064f10 -> sub_fffffff017064d7c : 504 -> 492
~ sub_fffffff017076558 -> sub_fffffff0170763b8 : 256 -> 252
~ sub_fffffff017076908 -> sub_fffffff017076764 : 244 -> 240
~ sub_fffffff017077578 -> sub_fffffff0170773d0 : 264 -> 268
~ sub_fffffff017077928 -> sub_fffffff017077784 : 180 -> 176
CStrings:
+ "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Sat Aug  8 13:15:17 PDT 2026; root:AppleImage4_txm-374~7022/libimage4_TXM/RELEASE_ARM64E"
+ "Code Signing Monitor Image4 Module Version 7.0.0: Sat Aug  8 13:15:17 PDT 2026; root:AppleImage4_txm-374~7022/libimage4_TXM/RELEASE_ARM64E"
- "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Sat Sep 12 03:03:29 PDT 2026; root:AppleImage4_txm-374~8103/libimage4_TXM/RELEASE_ARM64E"
- "Code Signing Monitor Image4 Module Version 7.0.0: Sat Sep 12 03:03:29 PDT 2026; root:AppleImage4_txm-374~8103/libimage4_TXM/RELEASE_ARM64E"
```
