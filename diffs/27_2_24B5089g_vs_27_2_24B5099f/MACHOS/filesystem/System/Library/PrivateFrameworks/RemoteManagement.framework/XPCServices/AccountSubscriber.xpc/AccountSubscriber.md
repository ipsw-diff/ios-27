## AccountSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/AccountSubscriber.xpc/AccountSubscriber`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-624.40.13.0.0
-  __TEXT.__text: 0x14824
+624.40.15.0.0
+  __TEXT.__text: 0x14c80
   __TEXT.__auth_stubs: 0x3a0
-  __TEXT.__objc_stubs: 0x2380
+  __TEXT.__objc_stubs: 0x23a0
   __TEXT.__objc_methlist: 0x894
   __TEXT.__const: 0x88
   __TEXT.__gcc_except_tab: 0x290
-  __TEXT.__cstring: 0x11e9
+  __TEXT.__cstring: 0x120e
   __TEXT.__objc_classname: 0x419
-  __TEXT.__objc_methname: 0x1fad
+  __TEXT.__objc_methname: 0x1fca
   __TEXT.__objc_methtype: 0x2f1
   __TEXT.__oslogstring: 0x10fa
   __TEXT.__unwind_info: 0x420
-  __DATA_CONST.__const: 0x940
-  __DATA_CONST.__cfstring: 0xdc0
+  __DATA_CONST.__const: 0x948
+  __DATA_CONST.__cfstring: 0xde0
   __DATA_CONST.__objc_classlist: 0xa0
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0x58
   __DATA_CONST.__auth_got: 0x1e0
-  __DATA_CONST.__got: 0x440
+  __DATA_CONST.__got: 0x450
   __DATA.__objc_const: 0xfd0
-  __DATA.__objc_selrefs: 0xa08
+  __DATA.__objc_selrefs: 0xa10
   __DATA.__objc_ivar: 0x10
   __DATA.__objc_data: 0x640
   __DATA.__data: 0x120

   - /System/Library/PrivateFrameworks/DMCUtilities.framework/DMCUtilities
   - /System/Library/PrivateFrameworks/DataAccess.framework/DataAccess
   - /System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DALDAP.framework/DALDAP
+  - /System/Library/PrivateFrameworks/ExchangeSync.framework/Frameworks/DAEAS.framework/DAEAS
   - /System/Library/PrivateFrameworks/ExchangeSyncExpress.framework/ExchangeSyncExpress
   - /System/Library/PrivateFrameworks/MDMClientLibrary.framework/MDMClientLibrary
   - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 311
-  Symbols:   318
-  CStrings:  582
+  Symbols:   321
+  CStrings:  584
 
Symbols:
+ _AccountPropertyRemoteManagementExchangeProtocolType
+ _kASEncryptionIdentityPersistentReference
+ _kASSigningIdentityPersistentReference
Functions:
~ sub_100005698 -> sub_100005710 : 680 -> 728
~ sub_100007310 -> sub_1000073b8 : 1600 -> 1640
~ sub_10000b504 -> sub_10000b5d4 : 5332 -> 5768
~ sub_10000cc48 -> sub_10000cecc : 2736 -> 2788
~ sub_1000108ec -> sub_100010ba4 : 3692 -> 4108
~ sub_100011810 -> sub_100011c68 : 2024 -> 2040
~ sub_100011ff8 -> sub_100012460 : 2120 -> 2188
~ sub_100012840 -> sub_100012cec : 716 -> 756
CStrings:
+ "RemoteManagementExchangeProtocolType"
+ "removeAccountPropertyForKey:"
```
