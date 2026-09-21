## com.apple.filesystems.apfs

> `com.apple.filesystems.apfs`

```diff

-3288.40.13.0.0
+3288.40.14.0.0
   __TEXT.__const: 0x94c
-  __TEXT.__cstring: 0x4ff4b
-  __TEXT_EXEC.__text: 0x1539a8
+  __TEXT.__cstring: 0x4ffa5
+  __TEXT_EXEC.__text: 0x153b3c
   __TEXT_EXEC.__auth_stubs: 0x2360
   __DATA.__data: 0x75c
   __DATA.__bss: 0xcf8
   __DATA_CONST.__mod_init_func: 0x10
   __DATA_CONST.__mod_term_func: 0x10
-  __DATA_CONST.__const: 0x6890
+  __DATA_CONST.__const: 0x6898
   __DATA_CONST.__kalloc_type: 0x5440
   __DATA_CONST.__kalloc_var: 0x2bc0
   __DATA_CONST.__assert: 0x14

   __DATA_CONST.__auth_ptr: 0x8
   Functions: 2395
   Symbols:   0
-  CStrings:  6955
+  CStrings:  6956
 
Functions:
~ sub_fffffe000aa1e764 -> sub_fffffe000aa21944 : 948 -> 976
~ sub_fffffe000aa1eb18 -> sub_fffffe000aa21d14 : 384 -> 388
~ sub_fffffe000aa2efb8 -> sub_fffffe000aa321b8 : 3448 -> 3552
~ sub_fffffe000aaa6464 -> sub_fffffe000aaa96cc : 3332 -> 3392
~ sub_fffffe000aab2df4 -> sub_fffffe000aab6098 : 2268 -> 2272
~ sub_fffffe000aabdcec -> sub_fffffe000aac0f94 : 656 -> 680
~ sub_fffffe000ab2805c -> sub_fffffe000ab2b31c : 3832 -> 3888
~ sub_fffffe000ab2996c -> sub_fffffe000ab2cc64 : 6384 -> 6396
~ sub_fffffe000ab2c2cc -> sub_fffffe000ab2f5d0 : 2520 -> 2528
~ sub_fffffe000ab2cca4 -> sub_fffffe000ab2ffb0 : 4344 -> 4376
~ sub_fffffe000ab30a34 -> sub_fffffe000ab33d60 : 3736 -> 3808
CStrings:
+ "%s:%d: %s Defrag run time %llu.%03llumSec, reallocated %llu blocks in %llu extents across %llu dstreams, finished with error %d\n"
+ "12111112122212121111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111"
+ "12111112122212121112111222222222222222221111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111121111111111111111111111111111111111111111111111111111111111111111111111111111111111111111112"
+ "19:33:45"
+ "2026/09/13"
+ "3288.40.14"
+ "FX defrag: Number of dstreams with at least one reallocated extent"
+ "Sep 13 2026"
+ "apfs-3288.40.14"
- "%s:%d: %s Defrag run time %llu.%03llumSec, reallocated %llu blocks in %llu extents, finished with error %d\n"
- "1211111212221212111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111"
- "1211111212221212111211122222222222222222111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111112111111111111111111111111111111111111111111111111111111111111111111111111111111111111111112"
- "2026/09/04"
- "23:03:37"
- "3288.40.13"
- "Sep  4 2026"
- "apfs-3288.40.13"
```
