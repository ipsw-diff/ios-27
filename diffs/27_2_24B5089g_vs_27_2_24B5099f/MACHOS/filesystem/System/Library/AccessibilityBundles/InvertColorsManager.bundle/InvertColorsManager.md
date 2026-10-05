## InvertColorsManager

> `/System/Library/AccessibilityBundles/InvertColorsManager.bundle/InvertColorsManager`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3245.8.2.0.0
-  __TEXT.__text: 0x20898
+3245.8.4.2.0
+  __TEXT.__text: 0x20b20
   __TEXT.__auth_stubs: 0x7f0
   __TEXT.__objc_stubs: 0x28c0
   __TEXT.__objc_methlist: 0x779c
-  __TEXT.__const: 0xc8
+  __TEXT.__const: 0xd0
   __TEXT.__dlopen_cstrs: 0x6a
   __TEXT.__gcc_except_tab: 0x1d8
   __TEXT.__objc_classname: 0xa17e
   __TEXT.__cstring: 0x8cc4
   __TEXT.__objc_methname: 0x2cfb
   __TEXT.__objc_methtype: 0x334
-  __TEXT.__oslogstring: 0xb76
-  __TEXT.__unwind_info: 0xf60
+  __TEXT.__oslogstring: 0xdb4
+  __TEXT.__unwind_info: 0xf70
   __DATA_CONST.__const: 0x818
   __DATA_CONST.__cfstring: 0x8d00
   __DATA_CONST.__objc_classlist: 0x1aa8

   - /usr/lib/libobjc.A.dylib
   Functions: 1917
   Symbols:   1893
-  CStrings:  2137
+  CStrings:  2142
 
Functions:
~ sub_11d68 : 116 -> 308
~ sub_11ddc -> sub_11e9c : 116 -> 212
~ sub_193ec -> sub_1950c : 116 -> 264
~ sub_19460 -> sub_19614 : 180 -> 392
CStrings:
+ "CAMSecureWindow: isInHostedDarkWindow=YES window=%@"
+ "CAMSecureWindow: locked + dark — opting OUT of own window-level dark invert, deferring to SB counter-invert. window=%@"
+ "CAMSecureWindow: supportsDarkWindowInvert=YES (screenLocked=%d darkModeActive=%d) window=%@"
+ "SBDeviceApplicationSceneView: _accessibilityLoadInvertColors shouldCounter=%d window=%@ windowClass=%@ invertColorsEnabled=%d isDarkWindow=%d supportsDarkWindowInvert=%d sceneView=%@"
+ "SBDeviceApplicationSceneView: _axShouldCounterCoverSheetDarkWindowInvert=%d globalSmartInvertDrivesDisplayFilter=%d window=%@"
```
