## Bom

> `/System/Library/PrivateFrameworks/Bom.framework/Bom`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-279.2.0.0.0
-  __TEXT.__text: 0x5b4f0
+280.0.0.0.0
+  __TEXT.__text: 0x5bae0
   __TEXT.__cstring: 0x129e3
   __TEXT.__const: 0x1728
   __TEXT.__oslogstring: 0x103e

   __AUTH_CONST.__const: 0x180
   __AUTH_CONST.__cfstring: 0x11c0
   __AUTH_CONST.__auth_got: 0xc68
-  __AUTH.__data: 0x160
   __DATA.__data: 0x168
   __DATA.__bss: 0x8dc
+  __DATA_DIRTY.__data: 0x160
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/PrivateFrameworks/AppleFSCompression.framework/AppleFSCompression
   - /usr/lib/libAppleArchive.dylib
Symbols:
+ _BOMStreamWriteUInt64
- __copyDataFork
CStrings:
+ "Sep 26 2026"
- "Sep 12 2026"
```
