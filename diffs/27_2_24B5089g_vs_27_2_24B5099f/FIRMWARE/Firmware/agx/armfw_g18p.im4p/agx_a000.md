## agx_a000

> `Firmware/agx/armfw_g18p.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3cfc8
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x3d05c
+  __TEXT.__gxf_code: 0x4f50
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x107d
Functions:
~ sub_fffffc0000038df8 : 432 -> 468
~ sub_fffffc0000038fa8 -> sub_fffffc0000038fcc : 428 -> 540
CStrings:
+ "Sep 27 2026 20:36:05"
- "Sep 13 2026 21:50:33"
```
