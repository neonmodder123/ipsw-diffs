## com.apple.driver.AppleARMPlatform

> `com.apple.driver.AppleARMPlatform`

```diff

-1150.40.4.0.0
+1150.0.1.0.0
   __TEXT.__const: 0x1ae0
-  __TEXT.__os_log: 0x1553
-  __TEXT.__cstring: 0xd2a4
-  __TEXT_EXEC.__text: 0x56c2c
+  __TEXT.__os_log: 0x14f7
+  __TEXT.__cstring: 0xd238
+  __TEXT_EXEC.__text: 0x56b0c
   __TEXT_EXEC.__auth_stubs: 0xd60
   __DATA.__data: 0x6c8
   __DATA.__common: 0xcd8

   __DATA_CONST.__got: 0x1f8
   Functions: 2238
   Symbols:   0
-  CStrings:  1751
+  CStrings:  1747
 
Functions:
~ __ZN18AppleMCCUserClient19clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 700 -> 600
~ sub_fffffe00086b5b64 -> sub_fffffe0008681230 : 340 -> 308
~ ____ZN23AppleMemCacheController30getDataCollectionMemDescriptorEv_block_invoke : 404 -> 248
CStrings:
- "%s:%d: Failed to create mem descriptor for shared data queue\n\n"
- "%s:%d: No data collection buffer available\n\n"
- "Failed to create mem descriptor for shared data queue\n"
- "No data collection buffer available\n"
```
