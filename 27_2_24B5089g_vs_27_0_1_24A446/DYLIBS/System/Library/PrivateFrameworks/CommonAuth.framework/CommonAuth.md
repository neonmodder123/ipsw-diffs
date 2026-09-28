## CommonAuth

> `/System/Library/PrivateFrameworks/CommonAuth.framework/CommonAuth`

```diff

-725.40.6.0.0
+725.0.12.0.0
   __TEXT.__text: 0x6664
   __TEXT.__const: 0x15c
   __TEXT.__cstring: 0x76f

   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0xb0
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__data: 0x2a
-  __DATA_DIRTY.__data: 0x750
+  __DATA.__data: 0x77a
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libheimdal-asn1.dylib
   - /usr/lib/libicucore.A.dylib
Functions:
~ _heim_ntlm_unparse_flags -> _heim_ntlm_free_buf : 44 -> 48
~ _heim_ntlm_free_buf -> _heim_ntlm_free_targetinfo : 48 -> 108
~ _heim_ntlm_free_targetinfo -> _heim_ntlm_encode_targetinfo : 108 -> 536
~ _heim_ntlm_encode_targetinfo -> _encode_ti_string : 536 -> 120
~ _encode_ti_string -> _heim_ntlm_decode_targetinfo : 120 -> 496
~ _heim_ntlm_decode_targetinfo -> sub_258f2fbd0 : 496 -> 44
```
