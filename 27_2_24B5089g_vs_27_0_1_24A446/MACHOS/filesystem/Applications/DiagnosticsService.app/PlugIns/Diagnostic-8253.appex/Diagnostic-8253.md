## Diagnostic-8253

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8253.appex/Diagnostic-8253`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-62.0.0.0.0
-  __TEXT.__text: 0x19d90
-  __TEXT.__auth_stubs: 0x730
+60.0.0.0.0
+  __TEXT.__text: 0x13820
+  __TEXT.__auth_stubs: 0x710
   __TEXT.__objc_stubs: 0x860
   __TEXT.__objc_methlist: 0xf8
-  __TEXT.__const: 0x60
-  __TEXT.__gcc_except_tab: 0x30fc
+  __TEXT.__gcc_except_tab: 0x2358
+  __TEXT.__const: 0x58
   __TEXT.__cstring: 0x3f1c
-  __TEXT.__oslogstring: 0xb
   __TEXT.__objc_classname: 0x1c
   __TEXT.__objc_methname: 0x633
   __TEXT.__objc_methtype: 0x7d1
-  __TEXT.__unwind_info: 0x628
-  __DATA_CONST.__const: 0x550
+  __TEXT.__unwind_info: 0x630
+  __DATA_CONST.__const: 0x518
   __DATA_CONST.__cfstring: 0x33a0
   __DATA_CONST.__objc_classlist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_intobj: 0x120
   __DATA_CONST.__objc_arraydata: 0x40
   __DATA_CONST.__objc_dictobj: 0xa0
-  __DATA_CONST.__auth_got: 0x3a8
-  __DATA_CONST.__got: 0x330
+  __DATA_CONST.__auth_got: 0x398
+  __DATA_CONST.__got: 0x328
   __DATA.__objc_const: 0x278
   __DATA.__objc_selrefs: 0x240
   __DATA.__objc_ivar: 0x3c

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 217
-  Symbols:   364
-  CStrings:  584
+  Symbols:   361
+  CStrings:  583
 
Symbols:
+ _NSLog
- __os_log_default
- __os_log_error_impl
- __os_log_impl
- _os_log_type_enabled
Functions:
~ __ZN23JasDiagnosticInteractor37pointCloudHxISPFrameAvailableCallbackEP10__CVBuffer6CMTime16StreamIdentifier : 764 -> 648
~ sub_100001cd8 -> sub_100001c14 : 1752 -> 1328
~ sub_1000023f8 -> sub_10000218c : 440 -> 320
~ sub_100002774 -> sub_100002490 : 412 -> 296
~ sub_100002910 -> sub_1000025b8 : 640 -> 416
~ sub_100002b90 -> sub_100002758 : 640 -> 416
~ sub_100002e14 -> sub_1000028fc : 420 -> 300
~ sub_100002fb8 -> sub_100002a28 : 2256 -> 2128
~ sub_100003b74 -> sub_100003564 : 7304 -> 4812
~ sub_100005990 -> sub_1000049c4 : 532 -> 428
~ sub_100005ba4 -> sub_100004b70 : 2480 -> 2228
~ __ZN17DeviceCMInterface38initAndActivateCaptureDeviceControllerEv : 484 -> 348
~ __ZN17DeviceCMInterface19setRgbConfigurationEiRK19RGBCamConfiguration : 5244 -> 3760
~ __ZN17DeviceCMInterface20enableJasperRgbVideoEv : 900 -> 576
~ __ZN17DeviceCMInterface26enableRGBOutputForStreamIdEi : 480 -> 356
~ __ZN17DeviceCMInterface28enableJasperPointCloudOutputEv : 784 -> 512
~ __ZN17DeviceCMInterface26configJasperRgbMultiStreamERK19JasperConfiguration : 2432 -> 1640
~ __ZN17DeviceCMInterface31setJasperMultiOutModeByStreamIdEjb : 1056 -> 624
~ __ZN17DeviceCMInterface18configJasperDeviceERK19JasperConfiguration : 4712 -> 3172
~ __ZN17DeviceCMInterface17enableSWRGBOutputEv : 340 -> 212
~ __ZN17DeviceCMInterface23requestControlOfStreamsEbj : 2100 -> 1344
~ __ZN17DeviceCMInterface23releaseControlOfStreamsEv : 620 -> 384
~ __ZN17DeviceCMInterface23enumerateStreamsIndicesEv : 1340 -> 960
~ __ZN17DeviceCMInterface30setPearlMultiOutModeByStreamIdEjb : 1044 -> 612
~ __ZN17DeviceCMInterface17setStreamPropertyEjPK10__CFStringPK12NSDictionary : 736 -> 460
~ __ZN17DeviceCMInterface19enablePearlIROutputEv : 1016 -> 748
~ __ZN17DeviceCMInterface20enablePearlRGBOutputEv : 340 -> 212
~ __ZN17DeviceCMInterface22setPearlIrCofigurationE20PearlProjectorIRType : 2940 -> 1940
~ __ZN17DeviceCMInterface26setPearlDepthConfigurationEyyb18PearlPdeOutputMode : 1120 -> 844
~ __ZN17DeviceCMInterface14startRgbStreamEi : 1780 -> 1052
~ __ZN17DeviceCMInterface17startJasperStreamEv : 2556 -> 1688
~ __ZN17DeviceCMInterface16stopJasperStreamEv : 916 -> 524
~ __ZN17DeviceCMInterface18startPearlIrStreamEv : 1496 -> 928
~ __ZN17DeviceCMInterface17stopPearlIrStreamEv : 916 -> 524
~ __ZN17DeviceCMInterface13stopRgbStreamEi : 904 -> 516
~ __ZN17DeviceCMInterface22validateJasperFwStatusEPj : 476 -> 344
~ __ZN17DeviceCMInterface18validateIrFwStatusEPj : 1004 -> 628
~ __ZN17DeviceCMInterface24enableDefaultDepthStreamEv : 412 -> 224
~ __ZN17DeviceCMInterface26getPearlProjectorHWVersionEPi -> __ZN17DeviceCMInterface16setPearlMultiCamEv : 620 -> 960
~ __ZN17DeviceCMInterface16setPearlMultiCamEv -> __ZN17DeviceCMInterface30enableSyncForEnumeratedStreamsEi : 1504 -> 560
~ __ZN17DeviceCMInterface30enableSyncForEnumeratedStreamsEi -> __ZN17DeviceCMInterface17setPearlSyncSlaveEii : 856 -> 780
~ __ZN17DeviceCMInterface17setPearlSyncSlaveEii -> __ZN17DeviceCMInterface21setPearlIRAsSyncSlaveEi : 1192 -> 12
~ __ZN17DeviceCMInterface22setPearlRgbAsSyncSlaveEi -> __ZN17DeviceCMInterface20disablePearlSyncModeEi : 12 -> 316
~ __ZN17DeviceCMInterface20disablePearlSyncModeEi -> __ZN17DeviceCMInterface19setPearlFormatIndexEii : 436 -> 100
~ __ZN17DeviceCMInterface19setPearlFormatIndexEii -> __ZN17DeviceCMInterface17configPearlDeviceERK18PearlConfiguration : 100 -> 2736
~ __ZN17DeviceCMInterface17configPearlDeviceERK18PearlConfiguration -> __ZN17DeviceCMInterface26getPearlProjectorHWVersionEPi : 4652 -> 432
~ __ZNK17DeviceCMInterface30getPearlConfigurationStringKeyEPK18PearlConfiguration : 340 -> 476
~ __ZN17DeviceCMInterface22isPDECaliobrationValidEPb : 624 -> 388
~ __ZN17DeviceCMInterface23getJasperProjectorFaultEPyPU15__autoreleasingP12NSDictionary : 556 -> 436
~ __ZN17DeviceCMInterface27getJasperProjectorWillFaultEPy : 736 -> 476
~ __ZN17DeviceCMInterface19getJasperResistanceEPy : 736 -> 476
~ __ZN17DeviceCMInterface27getPearlFloodProjectorFaultEPy : 956 -> 624
~ __ZN17DeviceCMInterface27getStructuredProjectorFaultEPy : 700 -> 492
~ __ZN17DeviceCMInterface20getAntliaFaultStatusEPy : 700 -> 492
~ __ZN17DeviceCMInterface28getProjectorCalibratedValuesEPU15__autoreleasingP12NSDictionary : 692 -> 452
~ __ZN17DeviceCMInterface19getDiagnosticReportEPU15__autoreleasingP12NSDictionary : 1024 -> 648
~ __ZN17DeviceCMInterface13releaseDeviceEv : 340 -> 224
~ __ZN17DeviceCMInterface13getRgbjReportERiS0_S0_S0_S0_ : 880 -> 528
~ __ZN17DeviceCMInterface24forceSaveWideJasperCalibEv : 408 -> 280
~ __ZN17DeviceCMInterface20setRgbjConfigurationEjjj : 620 -> 492
~ __ZN17DeviceCMInterface23setWideJasperExtrinsicsEffffff : 796 -> 668
~ __ZN17DeviceCMInterface15getPearlPleUUIDEPh : 624 -> 436
~ __ZN17DeviceCMInterface25getPearlRigelSerialNumberEPU15__autoreleasingP8NSString : 664 -> 440
~ __ZN17DeviceCMInterface23getPearlRigelOtpVersionEPi : 632 -> 444
~ __ZN17DeviceCMInterface18getGuadalupeValuesEPxS0_S0_PiS0_ : 1664 -> 1084
~ __Z18ecDisplayPipeStatsv : 1324 -> 1088
~ __Z14logMainResultsP12NSDictionaryii : 2060 -> 1276
CStrings:
- "%{public}s"
```
