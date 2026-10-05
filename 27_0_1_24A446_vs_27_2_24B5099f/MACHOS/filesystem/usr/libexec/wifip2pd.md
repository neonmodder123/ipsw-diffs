## wifip2pd

> `/usr/libexec/wifip2pd`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`

```diff

-885.85.4.1.0
-  __TEXT.__text: 0x5e52f8
-  __TEXT.__auth_stubs: 0x5240
-  __TEXT.__objc_stubs: 0x4720
-  __TEXT.__objc_methlist: 0x1bf4
-  __TEXT.__const: 0x404b0
-  __TEXT.__swift5_typeref: 0xd367
+887.9.0.0.0
+  __TEXT.__text: 0x5e74a0
+  __TEXT.__auth_stubs: 0x51d0
+  __TEXT.__objc_stubs: 0x4740
+  __TEXT.__objc_methlist: 0x1bfc
+  __TEXT.__const: 0x40510
+  __TEXT.__swift5_typeref: 0xd389
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__cstring: 0xfa28
-  __TEXT.__oslogstring: 0x226bc
-  __TEXT.__constg_swiftt: 0x103f4
-  __TEXT.__swift5_fieldmd: 0x169d8
+  __TEXT.__cstring: 0xfa2a
+  __TEXT.__oslogstring: 0x227ec
+  __TEXT.__constg_swiftt: 0x1041c
+  __TEXT.__swift5_fieldmd: 0x169f0
   __TEXT.__swift5_types: 0x12e0
   __TEXT.__swift5_builtin: 0x1748
-  __TEXT.__swift5_reflstr: 0x14bd9
+  __TEXT.__swift5_reflstr: 0x14be9
   __TEXT.__swift5_assocty: 0x2d78
   __TEXT.__swift5_proto: 0x3074
   __TEXT.__objc_classname: 0x10f7
   __TEXT.__objc_methtype: 0x2347
   __TEXT.__swift5_protos: 0x108
-  __TEXT.__swift5_capture: 0x7fc8
-  __TEXT.__objc_methname: 0xa305
+  __TEXT.__swift5_capture: 0x804c
+  __TEXT.__objc_methname: 0xa3a5
   __TEXT.__swift5_mpenum: 0x1a8
-  __TEXT.__swift_as_entry: 0x204
-  __TEXT.__swift_as_ret: 0x168
-  __TEXT.__swift_as_cont: 0x5f4
-  __TEXT.__unwind_info: 0x107e8
-  __TEXT.__eh_frame: 0x1e664
-  __DATA_CONST.__const: 0x39f28
+  __TEXT.__swift_as_entry: 0x20c
+  __TEXT.__swift_as_ret: 0x174
+  __TEXT.__swift_as_cont: 0x608
+  __TEXT.__unwind_info: 0x108a8
+  __TEXT.__eh_frame: 0x1e8cc
+  __DATA_CONST.__const: 0x3a048
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_classlist: 0x1e0
   __DATA_CONST.__objc_protolist: 0x2f0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x178
-  __DATA_CONST.__auth_got: 0x2928
+  __DATA_CONST.__auth_got: 0x28f0
   __DATA_CONST.__got: 0x1030
   __DATA_CONST.__auth_ptr: 0x7950
-  __DATA.__objc_const: 0xac90
-  __DATA.__objc_selrefs: 0x16e0
+  __DATA.__objc_const: 0xacd8
+  __DATA.__objc_selrefs: 0x16e8
   __DATA.__objc_data: 0x1920
-  __DATA.__data: 0x15068
+  __DATA.__data: 0x150a8
   __DATA.__bss: 0x5e2d0
-  __DATA.__common: 0xb88
+  __DATA.__common: 0xba0
   - /System/Library/Frameworks/Combine.framework/Combine
   - /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 24922
-  Symbols:   2319
-  CStrings:  5523
+  Functions: 24977
+  Symbols:   2310
+  CStrings:  5533
 
Symbols:
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
+ _$s7Network10NWEndpointO20customMetadataForKey3key10Foundation4DataVSgSS_tF
+ _$s7Network10NWEndpointO23setCustomMetadataForKey3key8metadataySS_10Foundation4DataVSgtF
- _$s7Network10NWEndpointO9txtRecordAA11NWTXTRecordVSgvg
- _$s7Network11NWTXTRecordV5EntryO4data10Foundation4DataVSgvg
- _$s7Network11NWTXTRecordV5EntryOMa
- _$s7Network11NWTXTRecordV5EntryOMn
- _$s7Network11NWTXTRecordV8getEntry3forAC0D0OSgSS_tF
- _$s7Network11NWTXTRecordVMa
- _$s7Network11NWTXTRecordVMn
- _nw_endpoint_copy_txt_record
- _nw_endpoint_set_txt_record
- _nw_txt_record_create_dictionary
- _nw_txt_record_remove_key
- _nw_txt_record_set_key
CStrings:
+ "%s APPLE80211_M_DRIVER_AVAILABLE available: %d reason: %d"
+ "%s APPLE80211_M_DRIVER_AVAILABLE with powerOn false"
+ "AWDL did wake"
+ "AWDL interface was re-created (system awake: %{bool}d)"
+ "AWDL will sleep"
+ "Infra did wake"
+ "Infra will sleep"
+ "NAN interface was re-created (system awake: %{bool}d)"
+ "Stamping system wake time during interface recovery (missed didWake)"
+ "WiFiP2P-887.9 Sep 26 2026 08:09:15"
+ "_inFlightDPSetupCount"
+ "b2a9724a150c527354f3e3f5a6249fb186fc03933f36e86d43817ab85b6914d4"
+ "com.apple.tvairplayd"
+ "dynamicSDB clearing switch on termination (%s)"
+ "e970cf1833739614a611d3ee15d1303435ce15bf52fd475bed5c53472761f00f"
+ "updatedNANDPInProgress:"
+ "{\n  \"WiFiAwareAllowedBundleIds\": {\n    \"c81d98e153fb5137f8f25aebe0bf0571260375f84788ab5c10360c98c2e49466\": {\n      \"WiFiAwareServices\": {\n        \"b21e0ab672d07208de165bc82205af92c1b8f96cf25a03c39f501c68ce76e5c8\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"cb4ad2594c789a9c803878f38cd79805c085111ec5fba47d6018fb2b7b78b59a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"b3e90e7d667b3ca24b7ec42dc38dd74ba94998d0d7477e14145bbe71d2133029\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"39d7ff35796c959f40be69d866cd446669459bc37db4978d08c3e4ab0150f0b5\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"d4f3c40a97b5bc5adbb555acce20d468262d5ef04c1655b575062b09b0c7de43\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"4213bd05eb8a19fc6dd67355a54f5a03058e877a3ad7da6b60e26249b0e88bbb\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"fbf009d5cbd2aff7097ee83e5f1ada9803dd0c21c050541e800bbde66b6a2c4a\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"c4d52c9951114ce7779324494136dc075267db17fff168f6c20d5f34d200dc4c\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"bf45d0be7829cc9b24d32bfc396a9151c765298c0c0a2ba96267743627c4a8bf\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"5d58ccdf42941fd6d6a01eca26e6c213b93579d80aee66844f700c86d1269297\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"80ea59fd272eb5ad6fde2bb3f9fdd56018c581a21750fead1aef2e65a3ae8bcc\": {\n      \"WiFiAwareServices\": {\n        \"214e19037521aff47c4805c069317c9038341cb0a2895546c073e8302c5fcb7f\": {\n          \"Publishable\": {}\n        }\n      }\n    },\n    \"1561dd31ad7a847eb9201a2b25f610ab8f82d7296daeaa220ed895051ab1ae57\": {\n      \"WiFiAwareServices\": {\n        \"89c3633d9e3e3df106df980354fa703d416c7f8a4e9059e0f304ddde86b89acc\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"c8a4e227d4424b7e83b1b336828343b57f9ad905a1bcdcf59085cb1108a12e45\": {\n      \"WiFiAwareServices\": {\n        \"659b225ce33d4c8faef59ecc83005f69ffeafbe1e37276a02d44115ca7c884b1\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"d3c0133a61e1e3dc394b033fe32d7f503540f71a6bfffd9746fcf162faa9dd74\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"b5b6d001d29d7de8baf787c37b1c2bcdbe8c062c4ccf0c8b7da333eb5916ebf3\": {\n      \"WiFiAwareServices\": {\n        \"214e19037521aff47c4805c069317c9038341cb0a2895546c073e8302c5fcb7f\": {\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"33d3a0db93ac0d0d9303781d8e91bb202a8d032a6ce2826b5adcca1195e06e72\": {\n      \"WiFiAwareServices\": {\n        \"89c3633d9e3e3df106df980354fa703d416c7f8a4e9059e0f304ddde86b89acc\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    }\n  }\n}"
+ "{\n  \"b5755de6d1a8cdadc6212a3f3b1239ecbce177ff25ea37edf510b9bc8d2ec869\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASKAdvertiser\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"2f9ab90ded6f119986bde17ff9cb7be396740d016b9ddfae25f5ce80554506ac\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"5e1c789a9320d938f0bf04c95148e9503fe218f013c5843dc033e2f5bea219e4\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"macOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"a43614cc75e7f50878ba7adf0d89cbd860a4e81b432ce2c020d6362d44fc3438\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASK\",\n        \"DDUI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"d2202a4e8bce2f787fff8c422d824d3bbc6ae8b8a4344bf34bea303dbe0cc48c\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Timeout\": 120,\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    }\n  },\n  \"65eed2ed4a2e1bf7e7f13d984fe5c1afff16dda8e8d9d5b28d53369b4ddadc6e\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"MARS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"54f2d96aeb42a4bc9be195a663c9faa1c3fdce6af76111a7690ac4ce79a90e0d\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\"\n      ],\n      \"ClientID\": [\n        \"CLI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"TDS\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    }\n  },\n  \"11ded26a6f7d3f5fc2a2ed49824e24286b25dce1b6abee355b13e9b4f583c16f\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"visionOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"visionOS\"\n      ]\n    }\n  },\n  \"3b4c1a2ccfd83a2ccf648e914143f217128fb1a71efbfac83cb555b68bb7fcfc\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"Timeout\": 120\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"ceb3fd4042786246a4382f4273856fa09d3865e08b3c3efc3e4ac21327546b11\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Terminus\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"ca9ff9bda2e540b5b3b4fe88fd703521d07c2af89d9d042b017dc8423a180907\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"2a1caca02565bbfa2a31b708b905a5c308fc04068f3982d607e7f19dca953089\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"539b8702cffe6f6619203036420f6948b71f6aff615e978a59ea1d3eca49ee04\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"Migration\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  }\n}"
+ "ℹ️ No %s configured for %s policy: %s"
- "3bdd21e5283593aefb6605925afdc83dfd5b1b86494fe5595b25629f16bf114b"
- "Driver interface was re-created"
- "RSSI: %s"
- "WiFiP2P-885.85.4.1 Sep 18 2026 22:09:14"
- "a2d35bf8101ed72be57b26e20beada1f77f72fac75b8acf8fed3e6a78fe7db1d"
- "nan_event: %s APPLE80211_M_DRIVER_AVAILABLE with powerOn false %d"
- "setTXTRecordEntry failed: NWEndpoint(nw) returned nil, endpoint may be in inconsistent state"
- "{\n  \"6c3c55d5c3cbc7beef912af640ec26c0ff0e7ca1537b2884a2d36ae9f7d5ad64\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASKAdvertiser\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"23d79b2b14c5d7c164ab376c55dc74781fcdaa6f18adcac259491f5ff47726d1\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"8f2c214eb2c91b8e85f7944bb91f2e2273f6fc53b477f8a82385640c2be65a9c\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"macOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"79179b50a1708698ce727049487d30e97b648d1e5147bcc6bb1449b5f663b1b4\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASK\",\n        \"DDUI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"b2ddb00c18aaa1576a154184e0cae512c383a57f4e7188e624f3d067c68f81dd\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    }\n  },\n  \"c991fce9a203487b967289177e9f414e4f455617c03aa844def3d0e047dc14bb\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"MARS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"8f9547ecc9cd27e39443a29bc9ba027a93d357e4a2fb12ece1642ff85b7cae8f\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\"\n      ],\n      \"ClientID\": [\n        \"CLI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"TDS\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    }\n  },\n  \"21e9279e206ccce2c5235a1ab2ad88ef45c662913af19e657f1c312869307a2d\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"visionOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"visionOS\"\n      ]\n    }\n  },\n  \"62187df34191d9b44b8630cf3dd2d0318823a8a672628d337c880edeebef5233\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"cd7db2fc26f9d1f825b3763a131435bf4d2056f28e177d9ddc9443c3a258f15e\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Terminus\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"56ec178ffb9fe3da83b332e17bb5df97a99c3cb1e586afc6b0e853a11523324b\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"a07a62568168d811a9f74316d922f715dfa2ecfc9fdf0b4c0ff3d20c26940cef\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"47179cf9dc95ccaf274c6e5a9bf70e23d37d411e52c9150b0f5950f9cc57bb8c\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"Migration\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  }\n}"
- "{\n  \"WiFiAwareAllowedBundleIds\": {\n    \"79eb1900e9034bfdca1042eaa7861c54bff4f2b3e1fae032d0969ff9052b3852\": {\n      \"WiFiAwareServices\": {\n        \"19fbbaf83462bd64ac78d3eabdff5f0a19bc515b789bc8d1a527e07e2a34c32a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"3a14143bd72674547e1b3bb43632a9836056dc8a0d57c0587356f00a96e25b4f\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"a8378af38cec6de49457be39b57cb31abd034c882cd906f576b51ca32e58628a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"cb23e818e52c370b7b149d672708a3f10379a5d8e1baa2686d6a84796a6e3608\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"6c68fed2056d97f3273bf8b7b1fd9ae7ed0f3af8fb507446d60ce003581bf5a3\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"188002802b007094ad3e15c13e6742101aafa3ea8feba49f2d18bad3ab390c0c\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"7ad7cf1f9066fdb09f73da2c1f8c32662e2670a2f6e83ca9551560cdd1c81348\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"0b13651e0aea4aa69ce89350378253bb603314eadbd35956a3a620949cebcaf3\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"ac4bc5449689c62096fca6f165611682e9b3b6972fe15902db3b6c4079abbe15\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"e92d8b213635e2f7162460279b196e82450ac6fdd1538619c2f222e235ea5756\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"155f716be8a708513031f1364c4d8273727c1adb9ddf830948ac58522624680f\": {\n      \"WiFiAwareServices\": {\n        \"381c7d43f9a070771237c5abd2f082963747c262beaef9987e11b37e35c5be4f\": {\n          \"Publishable\": {}\n        }\n      }\n    },\n    \"f36dc0f71e5615bf4abf2a29cd20408d3d5bb0a72fc47ca9f5503c79d69aa3d9\": {\n      \"WiFiAwareServices\": {\n        \"3ea312a1fe319a22cff8b4846d8b5f83403090df00f17da1dfcaa8da5597838a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"210048c6fa7af27f73831ea6e1e5ebd3fc5c5bb6a9c8d2eca3a4beb5a2b108e2\": {\n      \"WiFiAwareServices\": {\n        \"f20ff891907cfcfe3505a12c7600d6ad6641cd8ab28dca7fd21b51326cd614ac\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"bf678a91199689052b08d303c699a42b27c8c1e55894edfaf8536a26ba1d4ab6\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"eb8cd1c93f30b2c637b979f0d2a0fb0dd2e17d6d1b4c048c466a9fcd03eaa6c9\": {\n      \"WiFiAwareServices\": {\n        \"381c7d43f9a070771237c5abd2f082963747c262beaef9987e11b37e35c5be4f\": {\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"d65289bbf4d109eda2319a62894afc6aa4c2f3a55a8cd077f8e1e33f4dc7192c\": {\n      \"WiFiAwareServices\": {\n        \"3ea312a1fe319a22cff8b4846d8b5f83403090df00f17da1dfcaa8da5597838a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    }\n  }\n}"
```
