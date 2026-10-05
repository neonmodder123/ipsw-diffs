## promotedcontentd

> `/usr/libexec/promotedcontentd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_arrayobj`

```diff

-557.1.33.0.0
-  __TEXT.__text: 0x3db4b4
-  __TEXT.__auth_stubs: 0x5d50
-  __TEXT.__objc_stubs: 0x1a1e0
+557.2.13.0.0
+  __TEXT.__text: 0x3da0c4
+  __TEXT.__auth_stubs: 0x5db0
+  __TEXT.__objc_stubs: 0x1a220
   __TEXT.__objc_methlist: 0x151f8
-  __TEXT.__const: 0x2b1da
+  __TEXT.__const: 0x2b4ba
   __TEXT.__gcc_except_tab: 0x1348
-  __TEXT.__cstring: 0x15e05
-  __TEXT.__objc_methname: 0x2701d
-  __TEXT.__oslogstring: 0x1123c
-  __TEXT.__objc_classname: 0x4c07
-  __TEXT.__objc_methtype: 0x513d
-  __TEXT.__constg_swiftt: 0x6420
-  __TEXT.__swift5_typeref: 0x4366
-  __TEXT.__swift5_reflstr: 0x3706
-  __TEXT.__swift5_fieldmd: 0x49d8
+  __TEXT.__cstring: 0x15d35
+  __TEXT.__objc_methname: 0x2711d
+  __TEXT.__oslogstring: 0x113ac
+  __TEXT.__objc_classname: 0x4db7
+  __TEXT.__objc_methtype: 0x518d
+  __TEXT.__constg_swiftt: 0x65d0
+  __TEXT.__swift5_typeref: 0x43ca
+  __TEXT.__swift5_reflstr: 0x3846
+  __TEXT.__swift5_fieldmd: 0x4b50
   __TEXT.__swift5_builtin: 0x168
   __TEXT.__swift5_assocty: 0x3d8
-  __TEXT.__swift5_proto: 0x850
-  __TEXT.__swift5_types: 0x5c8
+  __TEXT.__swift5_proto: 0x874
+  __TEXT.__swift5_types: 0x5e0
   __TEXT.__swift5_capture: 0x1078
-  __TEXT.__swift5_protos: 0x124
+  __TEXT.__swift5_protos: 0x128
   __TEXT.__swift_as_entry: 0xd8
-  __TEXT.__swift_as_ret: 0x108
-  __TEXT.__swift_as_cont: 0x258
+  __TEXT.__swift_as_ret: 0x104
+  __TEXT.__swift_as_cont: 0x254
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x70a0
-  __TEXT.__eh_frame: 0x48ec
-  __DATA_CONST.__const: 0x1c400
+  __TEXT.__unwind_info: 0x70c8
+  __TEXT.__eh_frame: 0x486c
+  __DATA_CONST.__const: 0x1c3b8
   __DATA_CONST.__cfstring: 0xf800
-  __DATA_CONST.__objc_classlist: 0xfe8
+  __DATA_CONST.__objc_classlist: 0x1018
   __DATA_CONST.__objc_catlist: 0xb8
   __DATA_CONST.__objc_protolist: 0x300
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_dictobj: 0xa50
   __DATA_CONST.__objc_arrayobj: 0x108
   __DATA_CONST.__objc_doubleobj: 0x20
-  __DATA_CONST.__auth_got: 0x2eb8
-  __DATA_CONST.__got: 0x18d8
-  __DATA_CONST.__auth_ptr: 0x1618
-  __DATA.__objc_const: 0x2b398
-  __DATA.__objc_selrefs: 0x9480
+  __DATA_CONST.__auth_got: 0x2ee8
+  __DATA_CONST.__got: 0x18e8
+  __DATA_CONST.__auth_ptr: 0x1610
+  __DATA.__objc_const: 0x2b7e0
+  __DATA.__objc_selrefs: 0x9490
   __DATA.__objc_ivar: 0x1458
-  __DATA.__objc_data: 0x9848
-  __DATA.__data: 0xe578
+  __DATA.__objc_data: 0x9908
+  __DATA.__data: 0xe998
   __DATA.__common: 0xd70
-  __DATA.__bss: 0xdec0
+  __DATA.__bss: 0xe0c0
   - /AppleInternal/Library/Frameworks/TestHookService.framework/TestHookService
   - /AppleInternal/Library/Frameworks/TestHookShared.framework/TestHookShared
   - /System/Library/Frameworks/AdServices.framework/AdServices

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11744
-  Symbols:   2298
-  CStrings:  11663
+  Functions: 11756
+  Symbols:   2300
+  CStrings:  11682
 
Symbols:
+ _APSimulateCrashNoKillProcessWithoutABCReport
+ _AnalyticsSendEventLazy
CStrings:
+ "@\"NSDictionary\"8@?0"
+ "DELETE FROM Metric WHERE batch_id IS NOT NULL AND NOT EXISTS (SELECT 1 FROM Metric AS x WHERE x.batch_id = Metric.batch_id AND x.create_time >= ?) RETURNING rowid"
+ "Database config saved to UserDefaults. busyTimeout: %ld, coreAnalyticsThresholdMs: %ld"
+ "Database config saved to UserDefaults. busyTimeout: %ld, coreAnalyticsThresholdMs: %ld, slowQueryThresholdMs: %ld"
+ "Database.CoreAnalyticsThresholdMs"
+ "Database.SlowQueryThresholdMs"
+ "Depositing age noising application diagnostic sample %s"
+ "Error: Config download failed"
+ "Error: Config extraction failed"
+ "SELECT rowid, * FROM Metric WHERE purpose = ? ORDER BY batch_id ASC, rowid ASC"
+ "Triaging age noising application diagnostics for actual birth year: %{sensitive}s, noised birth year: %{sensitive}s, eligibility: %s"
+ "[SLPFlagCheck] Captured incrementalityAppStoreSLP=%{public}d at request time"
+ "_TtC16promotedcontentd20DatabaseConfigSyncer"
+ "_TtC16promotedcontentd39TracingAgeNoisingApplicationDiagnostics"
+ "_TtC16promotedcontentd40NullAgeNoisingApplicationDiagnosticDepot"
+ "_TtC16promotedcontentd42DepositingAgeNoisingApplicationDiagnostics"
+ "_TtC16promotedcontentd43TracingAgeNoisingApplicationDiagnosticDepot"
+ "_TtC16promotedcontentd49CoreAnalyticsAgeNoisingApplicationDiagnosticDepot"
+ "_TtC16promotedcontentd51PredeterminedAgeNoisingQualifierConfigurationSource"
+ "_TtC7Metrics32EmptyObservabilitySignalDatabase"
+ "accountInfo"
+ "ageNoisingApplicationDiagnosticDepot"
+ "ageNoisingConfiguration"
+ "depot"
+ "incrementalityAppStoreSLPEnabled"
+ "isInternalBuild"
+ "promotedcontentd.DatabaseConfigSyncer"
+ "randomGenerator"
+ "setFlagEnabledAtRequest:"
+ "tracedDepot"
+ "tracedDiagnostics"
- "DELETE FROM Metric WHERE batch_id IS NOT NULL AND NOT EXISTS (SELECT 1 FROM Metric AS x WHERE x.batch_id = Metric.batch_id AND x.create_time >= CAST(strftime('%s','now') AS INTEGER) - ?)"
- "Database busy timeout saved to UserDefaults: %ld"
- "INSERT INTO ObservabilitySignalsStore(timestamp,signal,report,param1,param2,param3) VALUES (?,?,?,?,?,?)"
- "Off"
- "On"
- "SELECT COUNT(*) FROM Metric WHERE batch_id IS NOT NULL AND NOT EXISTS (SELECT 1 FROM Metric AS x WHERE x.batch_id = Metric.batch_id AND x.create_time >= CAST(strftime('%s','now') AS INTEGER) - ?)"
- "SELECT rowid, * FROM Metric WHERE purpose = ? ORDER BY COALESCE(batch_id, '') ASC, rowid ASC"
- "Sending CoreAnalytics event '%s' with payload: %s"
- "_TtC16promotedcontentd25DatabaseBusyTimeoutSyncer"
- "_TtC16promotedcontentd45DefaultAgeNoisingQualifierConfigurationSource"
- "promotedcontentd.DatabaseBusyTimeoutSyncer"
- "storefrontIDSource"
```
