## com.apple.security.sandbox

> `com.apple.security.sandbox`

```diff

-3051.40.70.0.0
-  __TEXT.__os_log: 0x1d8e
-  __TEXT.__const: 0x1f18d1
+3051.40.80.0.0
+  __TEXT.__os_log: 0x1d90
+  __TEXT.__const: 0x1f2991
   __TEXT.__cstring: 0x6f21
-  __TEXT_EXEC.__text: 0x39a60
+  __TEXT_EXEC.__text: 0x39aac
   __TEXT_EXEC.__auth_stubs: 0x1080
   __DATA.__data: 0x220
   __DATA.__bss: 0x1531c
Functions:
~ sub_fffffe000a9afd1c -> sub_fffffe000a935e5c : 420 -> 444
~ _hook_mount_notify_mount : 1228 -> 1264
~ _eval : 13844 -> 13848
~ sub_fffffe000a9c6508 -> sub_fffffe000a94c688 : 720 -> 704
~ _re_cache_init : 496 -> 504
~ _collection_init : 1008 -> 1028
CStrings:
+ "%s set rootless flags on %s with flags=0x%lx"
- "%s set rootless flags on %s with flags=%lu"
```
