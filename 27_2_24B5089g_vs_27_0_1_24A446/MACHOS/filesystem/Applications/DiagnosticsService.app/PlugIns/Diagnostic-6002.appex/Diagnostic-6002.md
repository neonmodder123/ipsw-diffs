## Diagnostic-6002

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-6002.appex/Diagnostic-6002`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__auth_got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-62.0.0.0.0
-  __TEXT.__text: 0x233cc
+60.0.0.0.0
+  __TEXT.__text: 0x1d004
   __TEXT.__auth_stubs: 0xb30
   __TEXT.__objc_stubs: 0x1dc0
   __TEXT.__objc_methlist: 0x8e4
-  __TEXT.__gcc_except_tab: 0x3f08
+  __TEXT.__gcc_except_tab: 0x3154
   __TEXT.__const: 0x123
   __TEXT.__objc_methname: 0x2419
   __TEXT.__cstring: 0x49e5
   __TEXT.__objc_classname: 0xaa
   __TEXT.__objc_methtype: 0xa81
-  __TEXT.__oslogstring: 0x41
-  __TEXT.__unwind_info: 0x848
-  __DATA_CONST.__const: 0x640
+  __TEXT.__oslogstring: 0x26
+  __TEXT.__unwind_info: 0x850
+  __DATA_CONST.__const: 0x608
   __DATA_CONST.__cfstring: 0x37e0
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_protolist: 0x18

   - /usr/lib/libobjc.A.dylib
   Functions: 359
   Symbols:   470
-  CStrings:  1109
+  CStrings:  1108
 
Symbols:
+ _NSLog
+ _objc_retain_x24
- __os_log_error_impl
- _objc_retain_x23
Functions:
~ __Z18ecDisplayPipeStatsv : 1324 -> 1088
~ __Z14logMainResultsP12NSDictionaryii : 2060 -> 1276
~ sub_1000060c4 -> sub_100005cc8 : 3544 -> 2024
~ sub_100007208 -> sub_10000681c : 3208 -> 2516
~ sub_100007e90 -> sub_1000071f0 : 412 -> 284
~ sub_10000802c -> sub_10000730c : 628 -> 508
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
~ sub_10001a6a8 -> sub_10001487c : 944 -> 812
~ sub_100021184 -> sub_10001b2d4 : 3120 -> 2068
~ sub_10002376c -> sub_10001d4a0 : 432 -> 180
CStrings:
+ "JasperCalibDiag %s"
+ "addToReducedLog %s"
- "%{public}s"
- "JasperCalibDiag %{public}s"
- "addToReducedLog %{public}s"
```
