## linkd

> `/usr/libexec/linkd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_mpenum`
- `__DATA_CONST.__const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-301.0.51.1.104
+301.0.51.1.105
   __TEXT.__text: 0x1b96d4
   __TEXT.__auth_stubs: 0x3c40
   __TEXT.__objc_stubs: 0x3b40

   __TEXT.__swift_as_entry: 0xab0
   __TEXT.__swift_as_ret: 0xa64
   __TEXT.__swift_as_cont: 0xc88
-  __TEXT.__oslogstring: 0x658f
+  __TEXT.__oslogstring: 0x659f
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__unwind_info: 0x7838
-  __TEXT.__eh_frame: 0x1569c
+  __TEXT.__unwind_info: 0x7830
+  __TEXT.__eh_frame: 0x15674
   __DATA_CONST.__const: 0x10d10
   __DATA_CONST.__objc_classlist: 0x150
   __DATA_CONST.__objc_protolist: 0x1c0
Symbols:
+ _$s15AppIntentsIndex08MetadataC0V23appShortcutsUnprocessed3forSbSS_tKF
- _$s15AppIntentsIndex08MetadataC0V21appShortcutsProcessedySbSSKF
Functions:
~ sub_10000c0b0 : 12 -> 32
~ sub_100011cfc -> sub_100011d10 : 16 -> 12
~ sub_100011d0c -> sub_100011d1c : 12 -> 20
~ sub_100011d18 -> sub_100011d30 : 20 -> 12
~ sub_100014810 -> sub_100014820 : 36 -> 16
~ sub_100014834 -> sub_100014830 : 32 -> 36
~ sub_100022ad4 : 28 -> 24
~ sub_100161f7c -> sub_100161f78 : 896 -> 900
~ sub_10016255c : 108 -> 104
~ sub_100170f98 -> sub_100170f94 : 24 -> 28
CStrings:
+ "AppShortcuts for %{public}s does not need processing, unblocking"
- "AppShortcuts for %{public}s appear processed, unblocking"
```
