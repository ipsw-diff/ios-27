## apfs_vol_converter

> `/System/Library/Filesystems/apfs.fs/apfs_vol_converter`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3288.40.13.0.0
-  __TEXT.__text: 0x5ab8c
+3288.40.14.0.0
+  __TEXT.__text: 0x5acdc
   __TEXT.__auth_stubs: 0xa10
   __TEXT.__init_offsets: 0x4
   __TEXT.__const: 0x750
Functions:
~ sub_100034930 : 584 -> 608
~ sub_10004ce44 -> sub_10004ce5c : 1028 -> 1044
~ sub_10004d248 -> sub_10004d270 : 3796 -> 3868
~ sub_100050098 -> sub_100050108 : 3520 -> 3592
~ sub_100050e58 -> sub_100050f10 : 3612 -> 3744
~ sub_10005415c -> sub_100054298 : 68 -> 88
CStrings:
+ "3288.40.14"
- "3288.40.13"
```
