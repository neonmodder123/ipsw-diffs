## libncurses.5.4.dylib

> `/usr/lib/libncurses.5.4.dylib`

```diff

-85.0.0.0.0
-  __TEXT.__text: 0x30794
+81.0.0.0.0
+  __TEXT.__text: 0x30710
   __TEXT.__const: 0x72e4
-  __TEXT.__cstring: 0x3c8e
+  __TEXT.__cstring: 0x3c60
   __TEXT.__unwind_info: 0x778
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0x2f10
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x40
-  __AUTH_CONST.__auth_got: 0x2f0
+  __AUTH_CONST.__auth_got: 0x2e8
   __AUTH.__data: 0x18
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_data: 0x4

   __DATA_DIRTY.__bss: 0x8
   __DATA_DIRTY.__common: 0x308
   - /usr/lib/libSystem.B.dylib
-  Functions: 1015
-  Symbols:   1044
-  CStrings:  1682
+  Functions: 1014
+  Symbols:   1042
+  CStrings:  1681
 
Symbols:
+ _fopen
+ _select
- __nc_env_access
- _fopen$DARWIN_EXTSN
- _issetugid
- _select$DARWIN_EXTSN
Functions:
- __nc_env_access
~ __nc_tic_dir : 144 -> 124
~ __nc_first_db : 1000 -> 968
~ __nc_home_terminfo : 140 -> 124
~ __nc_read_termcap_entry : 864 -> 844
~ __nc_set_writedir : 252 -> 240
CStrings:
- "/usr/share/terminfo:/usr/local/share/terminfo"
```
