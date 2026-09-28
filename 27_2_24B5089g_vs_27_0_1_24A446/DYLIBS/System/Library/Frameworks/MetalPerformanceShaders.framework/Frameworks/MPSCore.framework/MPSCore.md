## MPSCore

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSCore.framework/MPSCore`

```diff

-130.1.1.0.0
-  __TEXT.__text: 0x94eac
+130.0.19.0.0
+  __TEXT.__text: 0x96a4c
   __TEXT.__objc_methlist: 0x27fc
   __TEXT.__const: 0x2974
-  __TEXT.__cstring: 0xa85d
+  __TEXT.__cstring: 0xa812
   __TEXT.__oslogstring: 0x7f
-  __TEXT.__gcc_except_tab: 0x4da4
+  __TEXT.__gcc_except_tab: 0x4dd8
   __TEXT.__unwind_info: 0x1e60
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH_CONST.__objc_const: 0x52c8
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__auth_got: 0x4d8
+  __AUTH.__objc_data: 0x1e0
   __DATA.__objc_ivar: 0x32c
-  __DATA.__data: 0x400
+  __DATA.__data: 0x9a8
   __DATA.__common: 0x28
   __DATA.__bss: 0x30
   __DATA_DIRTY.__objc_ivar: 0x64
-  __DATA_DIRTY.__objc_data: 0xff0
-  __DATA_DIRTY.__data: 0x5a8
+  __DATA_DIRTY.__objc_data: 0xe10
   __DATA_DIRTY.__bss: 0x230
   __DATA_DIRTY.__common: 0x20
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libobjc.A.dylib
   Functions: 1732
   Symbols:   800
-  CStrings:  901
+  CStrings:  893
 
Functions:
~ __ZN12MPSKernelDAG25appendConversionFunctionsEPU21objcproto10MTLLibrary11objc_objectP14NSMutableArrayIPU22objcproto11MTLFunction11objc_objectEPb : 4596 -> 7304
~ sub_24e7b7ebc -> sub_24abf9998 : 1312 -> 1088
~ __ZN12MPSKernelDAG13getDAGAndHashEPU21objcproto10MTLLibrary11objc_objectP14MPSDAGKernelOpP19NSMutableDictionaryIP8NSStringPU22objcproto11MTLFunction11objc_objectEP14NSMutableArrayIS6_ERDv4_yPb : 11968 -> 16092
~ __ZN12MPSKernelDAG6castOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1304 -> 1248
~ __ZN12MPSKernelDAG10exponentOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG15exponentBase2OpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG16exponentBase10OpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG11logarithmOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG16logarithmBase2OpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG17logarithmBase10OpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG8squareOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG12squareRootOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG19reverseSquareRootOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG12reciprocalOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG10absoluteOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG10negativeOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG6signOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG9signbitOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG6ceilOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG7floorOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG7roundOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG6rintOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG5sinOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1492 -> 1436
~ __ZN12MPSKernelDAG5cosOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1492 -> 1436
~ __ZN12MPSKernelDAG5tanOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1492 -> 1436
~ __ZN12MPSKernelDAG6sinhOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG6coshOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG6tanhOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG6asinOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG6acosOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG6atanOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG7asinhOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG7acoshOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG7atanhOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG5notOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1492 -> 1436
~ __ZN12MPSKernelDAG12isInfiniteOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG10isFiniteOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG7isNaNOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1492 -> 1436
~ __ZN12MPSKernelDAG5erfOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1484 -> 1428
~ __ZN12MPSKernelDAG11broadcastOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG12bitwiseNOTOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG17bitwisePopcountOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG10realPartOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG10imagPartOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG11conjugateOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1504 -> 1448
~ __ZN12MPSKernelDAG11absSquareOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1504 -> 1448
~ __ZN12MPSKernelDAG12dequantizeOpEP10BaseTensorRKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1608 -> 1552
~ __ZN12MPSKernelDAG13intAdditionOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1512 -> 1456
~ __ZN12MPSKernelDAG10additionOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1504 -> 1448
~ __ZN12MPSKernelDAG13subtractionOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1512 -> 1456
~ __ZN12MPSKernelDAG16multiplicationOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1508 -> 1452
~ __ZN12MPSKernelDAG10divisionOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1504 -> 1448
~ __ZN12MPSKernelDAG8moduloOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1504 -> 1448
~ __ZN12MPSKernelDAG7powerOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG9minimumOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1508 -> 1452
~ __ZN12MPSKernelDAG9maximumOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1508 -> 1452
~ __ZN12MPSKernelDAG9isEqualOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1508 -> 1452
~ __ZN12MPSKernelDAG12isNotEqualOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1508 -> 1452
~ __ZN12MPSKernelDAG10lessThanOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1504 -> 1448
~ __ZN12MPSKernelDAG17lessThanEqualToOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1508 -> 1452
~ __ZN12MPSKernelDAG13greaterThanOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1512 -> 1456
~ __ZN12MPSKernelDAG20greaterThanEqualToOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1508 -> 1452
~ __ZN12MPSKernelDAG5andOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1492 -> 1436
~ __ZN12MPSKernelDAG4orOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1492 -> 1436
~ __ZN12MPSKernelDAG6nandOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG5norOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1492 -> 1436
~ __ZN12MPSKernelDAG5xorOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1492 -> 1436
~ __ZN12MPSKernelDAG6xnorOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1496 -> 1440
~ __ZN12MPSKernelDAG7atan2OpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG12bitwiseANDOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1508 -> 1452
~ __ZN12MPSKernelDAG11bitwiseOROpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1504 -> 1448
~ __ZN12MPSKernelDAG12bitwiseXOROpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1508 -> 1452
~ __ZN12MPSKernelDAG18bitwiseLeftShiftOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1500 -> 1444
~ __ZN12MPSKernelDAG19bitwiseRightShiftOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1504 -> 1448
~ __ZN12MPSKernelDAG15complexCreateOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1508 -> 1452
~ __ZN12MPSKernelDAG14complexScaleOpEP10BaseTensorS1_RKNSt3__16vectorIlNS2_9allocatorIlEEEE11MPSDataTypePKc : 1512 -> 1456
~ __ZN21MPSKernelMiddlefixDAG13getDAGAndHashEPU21objcproto10MTLLibrary11objc_objectP14MPSDAGKernelOpP19NSMutableDictionaryIP8NSStringPU22objcproto11MTLFunction11objc_objectEP14NSMutableArrayIS6_ERDv4_yPb : 11592 -> 16960
~ sub_24e819154 -> sub_24ac5c06c : 2596 -> 2560
~ sub_24e81ba24 -> sub_24ac5e918 : 4328 -> 3564
~ __ZNK9MPSDevice19isDataTypeSupportedE11MPSDataType : 432 -> 416
CStrings:
+ "130.0.19"
- "130.1.1"
- "_2xf8e4m3"
- "_2xf8e5m2"
- "_3xf8e4m3"
- "_3xf8e5m2"
- "_4xf8e4m3"
- "_4xf8e5m2"
- "_f8e4m3"
- "_f8e5m2"
```
