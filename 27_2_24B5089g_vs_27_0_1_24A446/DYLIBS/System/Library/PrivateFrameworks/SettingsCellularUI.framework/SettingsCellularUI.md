## SettingsCellularUI

> `/System/Library/PrivateFrameworks/SettingsCellularUI.framework/SettingsCellularUI`

```diff

-756.0.0.0.0
-  __TEXT.__text: 0x944d8
+752.0.0.0.0
+  __TEXT.__text: 0x94480
   __TEXT.__objc_methlist: 0x9cbc
   __TEXT.__const: 0x498
   __TEXT.__dlopen_cstrs: 0x6a1

   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0xf0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x56a0
+  __DATA_CONST.__objc_selrefs: 0x56a8
   __DATA_CONST.__objc_superrefs: 0x440
   __DATA_CONST.__objc_arraydata: 0x1b8
   __DATA_CONST.__got: 0xad8
Symbols:
+ -[PSUIDataUsageCategorySpecifier initWithAppType:usageType:subSpecifiers:]
- -[PSUIDataUsageCategorySpecifier initWithAppType:usageType:subSpecifiers:statisticsCache:]
Functions:
~ -[PSUIAppsAndCategoriesDataUsageSubgroup specifiersWithSortComparator:] : 392 -> 388
~ -[PSUIAppsAndCategoriesDataUsageSubgroup addDataUsageCategorySpecifierToSpecifiers:appType:] : 272 -> 264
~ ___40-[PSUITopAppUsageGroup createSpecifiers]_block_invoke : 2820 -> 2816
~ -[PSUIDataUsageCategoryListController shouldShowSpinner] : 228 -> 172
~ -[PSUIDataUsageCategorySpecifier initWithAppType:usageType:subSpecifiers:statisticsCache:] -> -[PSUIDataUsageCategorySpecifier initWithAppType:usageType:subSpecifiers:] : 664 -> 668
~ -[PSUICellularPlanAddOnPlanTableCell _setupView:] : 1652 -> 1632
```
