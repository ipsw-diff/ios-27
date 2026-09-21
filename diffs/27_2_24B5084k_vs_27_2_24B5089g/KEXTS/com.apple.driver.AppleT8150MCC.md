## com.apple.driver.AppleT8150MCC

> `com.apple.driver.AppleT8150MCC`

```diff

-127.40.4.0.0
+127.40.5.0.0
   __TEXT.__const: 0x50
-  __TEXT.__cstring: 0x5d0f
-  __TEXT.__os_log: 0x26ff
-  __TEXT_EXEC.__text: 0x1708c
+  __TEXT.__cstring: 0x5d7b
+  __TEXT.__os_log: 0x275b
+  __TEXT_EXEC.__text: 0x171b0
   __TEXT_EXEC.__auth_stubs: 0x5b0
   __DATA.__data: 0x9130
   __DATA.__common: 0x1f0

   __DATA_CONST.__got: 0xc0
   Functions: 569
   Symbols:   0
-  CStrings:  939
+  CStrings:  943
 
Functions:
~ sub_fffffe00098e7798 -> sub_fffffe00098e9208 : 304 -> 340
~ ____ZN25AppleMemCacheControllerV230getDataCollectionMemDescriptorEv_block_invoke : 248 -> 404
~ __ZN20AppleMCCUserClientV219clientMemoryForTypeEjPjPP18IOMemoryDescriptor : 600 -> 700
CStrings:
+ "%s:%d: Failed to create mem descriptor for shared data queue\n\n"
+ "%s:%d: No data collection buffer available\n\n"
+ "Failed to create mem descriptor for shared data queue\n"
+ "No data collection buffer available\n"
```
