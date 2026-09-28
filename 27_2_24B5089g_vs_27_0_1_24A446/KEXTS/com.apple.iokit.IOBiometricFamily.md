## com.apple.iokit.IOBiometricFamily

> `com.apple.iokit.IOBiometricFamily`

```diff

-578.40.7.0.0
+577.0.0.0.0
   __TEXT.__os_log: 0x125b
-  __TEXT.__cstring: 0x129b
+  __TEXT.__cstring: 0x1297
   __TEXT.__const: 0x20
-  __TEXT_EXEC.__text: 0xf7d8
+  __TEXT_EXEC.__text: 0xfa30
   __TEXT_EXEC.__auth_stubs: 0x400
   __DATA.__data: 0xcc
-  __DATA.__common: 0x330
-  __DATA.__bss: 0x20
+  __DATA.__common: 0x3c0
   __DATA_CONST.__mod_init_func: 0x48
   __DATA_CONST.__mod_term_func: 0x48
   __DATA_CONST.__const: 0x3200
Functions:
~ __ZN15MCDataMessaging15initWithServiceEP9IOService : 216 -> 232
~ __ZN15MCDataMessagingD2Ev : 200 -> 216
~ sub_fffffe000a064450 -> sub_fffffe0009f93ec0 : 200 -> 216
~ __ZN15MCDataMessaging14messageClientsEjjPvmS0_y : 788 -> 804
~ __ZN15MCDataMessaging11enqueueDataEP12MCDataStructm : 376 -> 400
~ __ZN15MCDataMessaging15pullMessageDataEyP18IOMemoryDescriptorPj : 592 -> 656
~ __ZN10IOBioUtils16writeBytesToIOMDEP18IOMemoryDescriptorPKvmPj : 568 -> 588
~ __ZN20IOBioSEPSharedBuffer4initE11OSSharedPtrI9IOBioPoolEP20kern_allocation_namemS0_I23AppleSEPGenericTransferE : 748 -> 764
~ __ZN20IOBioSEPSharedBuffer4freeEv : 392 -> 412
~ __ZN27IOBioSEPSharedBufferFactory4initEP20kern_allocation_namem11OSSharedPtrI23AppleSEPGenericTransferE : 340 -> 356
~ __ZN30IOBioSharedMemoryTransferQueue13enqueueObjectE11OSSharedPtrI26IOBioShareableMemoryObjectEb : 404 -> 400
~ __ZN30IOBioSharedMemoryTransferQueue28dequeueShareableMemoryObjectEb : 408 -> 452
~ __ZN30IOBioSharedMemoryTransferQueue14releaseObjectsEjj : 280 -> 296
~ ____ZN30IOBioSharedMemoryTransferQueue14releaseObjectsEjj_block_invoke : 356 -> 376
~ ____ZN30IOBioSharedMemoryTransferQueue17releaseAllObjectsEj_block_invoke : 292 -> 312
~ __ZN30IOBioSharedMemoryTransferQueue10osLogQueueEj : 364 -> 384
~ __ZN30IOBioSharedMemoryTransferQueue11osLogObjectEP26IOBioShareableMemoryObjectj : 92 -> 112
~ __ZN15IOBioArrayQueue4initEPKcjbb : 412 -> 428
~ __ZN15IOBioArrayQueue4freeEv : 220 -> 236
~ __ZN15IOBioArrayQueue13enqueueObjectE11OSSharedPtrI8OSObjectEb : 748 -> 768
~ __ZN15IOBioArrayQueue10osLogQueueEv : 348 -> 376
~ __ZN15IOBioArrayQueue14releaseObjectsEj : 220 -> 236
~ __ZN15IOBioArrayQueue19removeObjectAtIndexEjb : 444 -> 472
~ __ZN15IOBioArrayQueue17releaseAllObjectsEv : 208 -> 228
~ __ZN15IOBioArrayQueue22releaseMatchingObjectsEU13block_pointerFbP8OSObjectPbEb : 592 -> 616
~ __ZN15IOBioArrayQueue11osLogObjectEP8OSObject : 160 -> 180
~ __ZN21IOBiometricUserClient4freeEv : 364 -> 388
~ __ZN21IOBiometricUserClient19clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 692 -> 720
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: BiometricKit-577~9296, %s file: %s, line: %d\n"
- "AssertMacros: %s (value = 0x%lx), version: BiometricKit-578.40.7~162, %s file: %s, line: %d\n"
```
