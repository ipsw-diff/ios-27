## IOMFB_FDR_Loader

> `/usr/bin/IOMFB_FDR_Loader`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-700.50.104.1.0
-  __TEXT.__text: 0x34b08
+700.50.108.0.0
+  __TEXT.__text: 0x34b58
   __TEXT.__auth_stubs: 0x720
   __TEXT.__gcc_except_tab: 0x3e0
   __TEXT.__const: 0x1c00
-  __TEXT.__cstring: 0x8fa2
+  __TEXT.__cstring: 0x8fea
   __TEXT.__unwind_info: 0x5f0
   __DATA_CONST.__const: 0x2b40
   __DATA_CONST.__cfstring: 0x4a0
Functions:
~ sub_100008534 : 100 -> 144
~ sub_100022eb4 -> sub_100022ee0 : 240 -> 276
CStrings:
+ "Parser SetBlock failed with ret=0x%x, pbt=%d, data=%p, block_size=%u, indexes=%p, nindex=%u"
+ "Parser e: failed to set PTUC TLS RR LUT dbv_nits=%d, attempt %u/%u\n"
- "Parser SetBlock failed with 0x%x"
- "Parser e: failed to set PTUC TLS RR LUT brightness %d\n"
```
