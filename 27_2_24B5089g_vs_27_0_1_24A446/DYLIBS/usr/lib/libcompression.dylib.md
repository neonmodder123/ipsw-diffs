## libcompression.dylib

> `/usr/lib/libcompression.dylib`

```diff

-212.40.2.0.0
-  __TEXT.__text: 0x64688
-  __TEXT.__const: 0x76ec1
+212.0.1.0.0
+  __TEXT.__text: 0x64e0c
+  __TEXT.__const: 0x76e91
   __TEXT.__cstring: 0x2ec
   __TEXT.__unwind_info: 0x710
   __TEXT.__eh_frame: 0x450

   __DATA.__common: 0x1200
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/liblzma.5.dylib
-  Functions: 548
-  Symbols:   720
+  Functions: 547
+  Symbols:   719
   CStrings:  49
 
Symbols:
- _getDecoderTable
Functions:
~ _lzvnDecode : 1132 -> 1136
~ _lzfseDecode : 5040 -> 5032
~ _zlibDecodeBufferSafe : 1824 -> 2596
~ _zlibDecodeBuffer : 1580 -> 2352
~ _readHuffmanTable : 1036 -> 2052
~ _zlib_stream_get_encode_state_size : 48 -> 52
~ _lzbitmap_decode : 2372 -> 2224
~ _lzbitmap_decode_buffer : 60 -> 52
- _getDecoderTable
~ _msh_decode_buffer : 3760 -> 3660
~ _lz24_decode_buffer : 712 -> 696
~ _smb_lznt1_decode_buffer : 516 -> 524
~ _lzfse_decode_buffer_output_size : 500 -> 504
~ _lzfse_decode_buffer_iboot : 2968 -> 2956
~ _lzfse_decode_lzvn_block_iboot : 456 -> 460
~ _smb_lz77h_decode_buffer : 1300 -> 1308
~ _lzbitmap_fast_decode : 1376 -> 1528
~ _lzbitmap_fast_decode_buffer : 60 -> 52
~ _smb_lz77_decode_buffer : 468 -> 476
~ _lzx_decode_buffer : 2300 -> 2292
~ _lzma_stream_end : 60 -> 56
```
