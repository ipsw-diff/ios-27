## libswift_Concurrency.dylib

> `/usr/lib/swift/libswift_Concurrency.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-6.4.0.34.1
-  __TEXT.__text: 0x75e1c
+6.4.2.1.7
+  __TEXT.__text: 0x75dec
   __TEXT.__init_offsets: 0xc
   __TEXT.__const: 0x30aa
   __TEXT.__cstring: 0x2266

   __TEXT.__swift_as_entry: 0x2b4
   __TEXT.__swift_as_ret: 0x34c
   __TEXT.__swift_as_cont: 0x500
-  __TEXT.__unwind_info: 0x2c18
+  __TEXT.__unwind_info: 0x2c10
   __TEXT.__eh_frame: 0x6608
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __AUTH_CONST.__auth_got: 0x8b0
   __AUTH.__data: 0xa70
   __DATA.__data: 0xf0
-  __DATA.__bss: 0x43a0
+  __DATA.__bss: 0x4380
   __DATA.__common: 0x88
-  __DATA_DIRTY.__data: 0x470
+  __DATA_DIRTY.__data: 0x468
   __DATA_DIRTY.__bss: 0x19d0
   __DATA_DIRTY.__common: 0x70
   - /usr/lib/libSystem.B.dylib

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/system/libdispatch.dylib
-  Functions: 3046
-  Symbols:   5829
+  Functions: 3045
+  Symbols:   5827
   CStrings:  217
 
Symbols:
- __ZL19dispatchEnqueueFunc
- __ZL29initializeDispatchEnqueueFuncP16dispatch_queue_sPv11qos_class_t
Functions:
~ _swift_dispatchEnqueueGlobal : 180 -> 172
~ _swift_dispatchEnqueueMain : 32 -> 24
- __ZL29initializeDispatchEnqueueFuncP16dispatch_queue_sPv11qos_class_t
~ _swift_task_enqueueOnDispatchQueue : 32 -> 24
CStrings:
+ "Initialized count must be in 0 ... unsafeUninitializedCapacity."
- "Initialized count set to greater than specified capacity."
```
