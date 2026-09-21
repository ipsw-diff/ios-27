## apfs_checkseal

> `/System/Library/Filesystems/apfs.fs/apfs_checkseal`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3288.40.13.0.0
-  __TEXT.__text: 0x500dc
+3288.40.14.0.0
+  __TEXT.__text: 0x5022c
   __TEXT.__auth_stubs: 0x760
   __TEXT.__const: 0x4c0
   __TEXT.__cstring: 0x10117
Functions:
~ sub_100020880 : 584 -> 608
~ sub_100042058 -> sub_100042070 : 1028 -> 1044
~ sub_10004245c -> sub_100042484 : 3796 -> 3868
~ sub_1000452ac -> sub_10004531c : 3520 -> 3592
~ sub_10004606c -> sub_100046124 : 3612 -> 3744
~ sub_100049370 -> sub_1000494ac : 68 -> 88
```
