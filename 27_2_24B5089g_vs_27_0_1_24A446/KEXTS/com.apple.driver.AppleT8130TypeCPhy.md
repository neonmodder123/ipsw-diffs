## com.apple.driver.AppleT8130TypeCPhy

> `com.apple.driver.AppleT8130TypeCPhy`

```diff

-317.40.3.0.0
+317.0.1.0.0
   __TEXT.__const: 0x48
-  __TEXT.__cstring: 0x9afa
-  __TEXT.__os_log: 0xfb0b
-  __TEXT_EXEC.__text: 0x4c1e8
+  __TEXT.__cstring: 0x9b80
+  __TEXT.__os_log: 0xfb65
+  __TEXT_EXEC.__text: 0x4c5f0
   __TEXT_EXEC.__auth_stubs: 0x260
   __DATA.__data: 0x2d8
   __DATA.__common: 0x58

   __DATA_CONST.__got: 0x60
   Functions: 131
   Symbols:   0
-  CStrings:  506
+  CStrings:  511
 
Functions:
~ __ZN18AppleT8130TypeCPhy5startEP9IOService : 7808 -> 8064
~ sub_fffffe0009adc0a0 -> sub_fffffe0009a0dac0 : 484 -> 524
~ __ZN18AppleT8130TypeCPhy13eusb2phy_initEbb : 9292 -> 9944
~ sub_fffffe0009ae9010 -> sub_fffffe0009a1ace4 : 2352 -> 2436
CStrings:
+ "%s@%s: %s::%s: failed to configure usb-repeater %s\n"
+ "%s@%s: %s::%s: found usb-repeater %s\n"
+ "121111121222121211111112121212121112111122122222222222222222222222221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221111211"
+ "IOService"
+ "usb-repeater"
+ "usb-repeater-options"
- "121111121222121211111111212121212111211112212222222222222222222222222112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122112211221122111121"
```
