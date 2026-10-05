## apfs_condenser

> `/System/Library/Filesystems/apfs.fs/apfs_condenser`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3288.40.14.0.0
-  __TEXT.__text: 0x4d3e8
+3288.40.17.0.0
+  __TEXT.__text: 0x4d3c8
   __TEXT.__auth_stubs: 0x780
   __TEXT.__cstring: 0xf7c5
   __TEXT.__const: 0x220
-  __TEXT.__unwind_info: 0x830
+  __TEXT.__unwind_info: 0x840
   __DATA_CONST.__const: 0x8f8
   __DATA_CONST.__cfstring: 0x120
   __DATA_CONST.__auth_got: 0x3c0
CStrings:
+ "3288.40.17"
- "3288.40.14"
```
