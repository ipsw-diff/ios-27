## softposreaderd

> `/usr/libexec/softposreaderd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__DATA_CONST.__const`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-51.4.0.0.0
-  __TEXT.__text: 0x41cb58
+51.5.0.0.0
+  __TEXT.__text: 0x41cc68
   __TEXT.__auth_stubs: 0x42c0
   __TEXT.__objc_stubs: 0x2080
   __TEXT.__objc_methlist: 0xe7c

   __TEXT.__swift5_typeref: 0x24cc
   __TEXT.__cstring: 0x11b7b
   __TEXT.__objc_methtype: 0x1525
-  __TEXT.__oslogstring: 0xd12e
+  __TEXT.__oslogstring: 0xd11e
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constg_swiftt: 0x7984
   __TEXT.__swift5_proto: 0xcdc

   __TEXT.__swift_as_ret: 0x18c
   __TEXT.__swift_as_cont: 0x3bc
   __TEXT.__swift5_protos: 0x138
-  __TEXT.__unwind_info: 0x4e78
-  __TEXT.__eh_frame: 0xcb80
+  __TEXT.__unwind_info: 0x4e80
+  __TEXT.__eh_frame: 0xcbd8
   __DATA_CONST.__const: 0x18198
   __DATA_CONST.__objc_classlist: 0x390
   __DATA_CONST.__objc_protolist: 0x1b0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6169
+  Functions: 6171
   Symbols:   1692
   CStrings:  3606
 
CStrings:
+ "%s.%s: no controllerInfo (XPC failure)"
- "%s.%s: no controllerInfo; assuming antenna present"
```
