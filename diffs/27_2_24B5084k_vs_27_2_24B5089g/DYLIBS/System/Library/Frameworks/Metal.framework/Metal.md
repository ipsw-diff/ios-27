## Metal

> `/System/Library/Frameworks/Metal.framework/Metal`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-382.5.4.0.0
-  __TEXT.__text: 0x1e87cc
+382.5.6.0.0
+  __TEXT.__text: 0x1e87c8
   __TEXT.__objc_methlist: 0x1ee04
   __TEXT.__cstring: 0x237a7
   __TEXT.__gcc_except_tab: 0xc3c8

   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0xe98
-  __AUTH.__objc_data: 0x4380
+  __AUTH.__objc_data: 0x4010
   __DATA.__objc_ivar: 0x225c
-  __DATA.__data: 0x4498
-  __DATA.__bss: 0x38c
+  __DATA.__data: 0x4490
+  __DATA.__bss: 0x37c
   __DATA.__common: 0x40
-  __DATA_DIRTY.__objc_data: 0x40b0
-  __DATA_DIRTY.__data: 0xc8
-  __DATA_DIRTY.__bss: 0x318
+  __DATA_DIRTY.__objc_data: 0x4420
+  __DATA_DIRTY.__data: 0xd0
+  __DATA_DIRTY.__bss: 0x328
   __DATA_DIRTY.__common: 0x11
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/CoreServices
Functions:
~ -[_MTLBinaryArchive materializeEntryForKey:fileIndex:containsEntry:addEntry:] : 268 -> 264
CStrings:
+ "21:27:55"
+ "Sep 13 2026"
+ "Sep 13 2026 21:27:55"
- "01:16:28"
- "Sep  1 2026"
- "Sep  1 2026 01:16:28"
```
