## AppleThunderboltSAT

> `/System/Library/Extensions/AppleThunderboltSAT.kext/AppleThunderboltSAT`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`

```diff

-120.0.0.502.1
-  __TEXT.__cstring: 0x11736
+121.0.0.0.0
+  __TEXT.__cstring: 0x11741
   __TEXT.__os_log: 0x277
   __TEXT.__const: 0xc0
-  __TEXT_EXEC.__text: 0x26ed4
+  __TEXT_EXEC.__text: 0x26e48
   __TEXT_EXEC.__auth_stubs: 0x670
   __DATA.__data: 0x7f0
-  __DATA.__common: 0x601
+  __DATA.__common: 0x5f9
   __DATA.__bss: 0x70
   __DATA_CONST.__mod_init_func: 0x90
   __DATA_CONST.__mod_term_func: 0x90

   __DATA_CONST.__kalloc_var: 0x2d0
   __DATA_CONST.__auth_got: 0x338
   __DATA_CONST.__got: 0x110
-  Functions: 641
-  Symbols:   1268
-  CStrings:  1066
+  Functions: 640
+  Symbols:   1267
+  CStrings:  1064
 
Symbols:
+ __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_802
+ __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_876
- __ZL31getDefaultClientDataQueueLengthv
- __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_822
- __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_886
CStrings:
+ "1.0.105"
+ "121"
+ "19:54:07"
+ "AppleThunderboltSATGlobals() sat-vsa is %s"
+ "LinkDevice: routerID %d portID %d - remote ring mask is invalid, looks like VSA mode is not active on the capturing side (sat-vsa=0 or unsupported build)"
+ "SATLinkDevice::start - VSA mode disabled (sat-vsa=0 boot-arg set), skipping initialization\n"
+ "SATLinkDevice<%p>::activateInternal WARNING: remote ring mask is invalid - looks like VSA mode is not active on the capturing side (sat-vsa=0 or unsupported build). routerID %d, portID %d, remote_tx_mask=%u, remote_rx_mask=%u"
+ "Sep 13 2026"
- "1.0.104"
- "120.0.0.502.1"
- "20:44:28"
- "AppleThunderboltSATGlobals() sat-vsa is enabled"
- "LinkDevice: routerID %d portID %d - remote ring mask is invalid, looks like sat-vsa=1 boot-arg missing on the capturing side"
- "SATLinkDevice::start - VSA mode disabled (sat-vsa boot-arg not set), skipping initialization\n"
- "SATLinkDevice<%p>::activateInternal WARNING: looks like sat-vsa=1 boot-arg missing on the capturing side. routerID %d, portID %d, remote_tx_mask=%u, remote_rx_mask=%u"
- "Sep  9 2026"
- "default data queue len is 10"
- "default data queue len is 4096"
```
