## Diagnostic-8276

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8276.appex/Diagnostic-8276`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
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
-  __TEXT.__text: 0x21e48
+60.0.0.0.0
+  __TEXT.__text: 0x1c1e8
   __TEXT.__auth_stubs: 0xb20
   __TEXT.__objc_stubs: 0x1c00
   __TEXT.__objc_methlist: 0x8a4
-  __TEXT.__gcc_except_tab: 0x3b14
-  __TEXT.__const: 0x140
+  __TEXT.__gcc_except_tab: 0x2e74
+  __TEXT.__const: 0x123
   __TEXT.__objc_methname: 0x229b
-  __TEXT.__cstring: 0x44c1
+  __TEXT.__cstring: 0x472c
   __TEXT.__objc_classname: 0xb4
   __TEXT.__objc_methtype: 0xa12
-  __TEXT.__oslogstring: 0x3d3
-  __TEXT.__unwind_info: 0x820
-  __DATA_CONST.__const: 0x640
-  __DATA_CONST.__cfstring: 0x3520
+  __TEXT.__oslogstring: 0x11d
+  __TEXT.__unwind_info: 0x828
+  __DATA_CONST.__const: 0x608
+  __DATA_CONST.__cfstring: 0x3660
   __DATA_CONST.__objc_classlist: 0x30
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8

   - /usr/lib/libobjc.A.dylib
   Functions: 354
   Symbols:   467
-  CStrings:  1082
+  CStrings:  1081
 
Symbols:
+ _NSLog
+ _objc_retain_x24
- __os_log_error_impl
- _objc_retain_x26
Functions:
~ __Z18ecDisplayPipeStatsv : 1324 -> 1088
~ __Z14logMainResultsP12NSDictionaryii : 2060 -> 1276
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
~ sub_1000182b4 -> sub_100012e24 : 944 -> 812
~ sub_10001ed90 -> sub_10001987c : 3120 -> 2068
~ sub_100021378 -> sub_10001ba48 : 432 -> 180
~ sub_100022410 -> sub_10001c9e4 : 1180 -> 616
CStrings:
+ "JasperCalibDiag %s"
+ "addToReducedLog %s"
+ "validateAndInitializeParameters: _sceneErrorTimeOut=%d"
+ "validateAndInitializeParameters: _sceneErrorTimeOut=%f"
+ "validateAndInitializeParameters: _userNotMovingTimeout=%d"
+ "validateAndInitializeParameters: key=%@"
+ "validateAndInitializeParameters: received skipSummaryScreen parameter, skipSummaryScreen=%d"
+ "validateAndInitializeParameters: sessionTimeOut=%d"
- "%{public}s"
- "JasperCalibDiag %{public}s"
- "addToReducedLog %{public}s"
- "validateAndInitializeParameters: _sceneErrorTimeOut=%{public}d"
- "validateAndInitializeParameters: _sceneErrorTimeOut=%{public}f"
- "validateAndInitializeParameters: _userNotMovingTimeout=%{public}d"
- "validateAndInitializeParameters: key=%{public}@"
- "validateAndInitializeParameters: received skipSummaryScreen parameter, skipSummaryScreen=%{public}d"
- "validateAndInitializeParameters: sessionTimeOut=%{public}d"
```
