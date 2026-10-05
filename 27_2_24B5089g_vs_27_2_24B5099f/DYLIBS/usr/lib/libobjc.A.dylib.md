## libobjc.A.dylib

> `/usr/lib/libobjc.A.dylib`

```diff

 973.1.0.0.0
-  __TEXT.__text: 0x3ca30
+  __TEXT.__text: 0x3ca50
   __TEXT.__lazy_helpers: 0xa8
   __TEXT.__objc_methlist: 0x5ec
   __TEXT.__const: 0x4130

   __DATA_CONST.__objc_selrefs: 0x1d0
   __DATA_CONST.__objc_scoffs: 0x28
   __DATA_CONST.__got: 0x60
-  __AUTH_CONST.__const: 0x578
+  __AUTH_CONST.__const: 0x590
   __AUTH_CONST.__objc_const: 0x468
   __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__auth_got: 0x400

   __DATA.__objc_ivar: 0x8
   __DATA.__data: 0xb8
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x9dd
+  __DATA.__bss: 0x79d
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x140
-  __DATA_DIRTY.__data: 0x8e0
-  __DATA_DIRTY.__bss: 0x11c0
+  __DATA_DIRTY.__data: 0x8d8
+  __DATA_DIRTY.__bss: 0x1400
   __DATA_DIRTY.__common: 0x28
   - /usr/lib/libRosetta.dylib
   - /usr/lib/libSystem.B.dylib

   - /usr/lib/libobjc-env.dylib
   - /usr/lib/objc/libobjcMsgSend.dylib
   Functions: 867
-  Symbols:   1426
+  Symbols:   1425
   CStrings:  480
 
Symbols:
- __ZZ16get_xprr_versionvE19cached_xprr_version
Functions:
~ _object_setClass : 668 -> 680
~ -[NSObject init] : 4 -> 8
~ __ZN19AutoreleasePoolPage12releaseUntilEPP11objc_object : 312 -> 308
~ __ZN19AutoreleasePoolPage3addEP11objc_object : 356 -> 360
~ __ZL38objc_destructInstance_nonnull_realizedP11objc_object : 168 -> 164
~ __ZN4objc12DenseMapBaseINS_8DenseMapI12DisguisedPtrIK11objc_objectEmN12_GLOBAL__N_125RefcountMapValuePurgeableENS_12DenseMapInfoIS5_EENS_6detail12DenseMapPairIS5_mEEEES5_mS7_S9_SC_E4findERKS5_ : 112 -> 116
~ _objc_autoreleaseReturnValue : 336 -> 332
~ -[NSObject dealloc] : 4 -> 8
~ _objc_loadWeakRetained : 676 -> 688
~ __objc_rootDealloc : 96 -> 100
~ _objc_alloc_init : 92 -> 88
~ _weak_register_no_lock : 404 -> 408
~ _objc_storeWeak : 588 -> 600
~ _weak_unregister_no_lock : 512 -> 500
~ __ZL23callSetWeaklyReferencedP11objc_object : 324 -> 320
~ __ZL17weak_entry_insertP12weak_table_tP12weak_entry_t : 212 -> 200
~ __ZNK4objc12DenseMapBaseINS_8DenseMapIPK8method_tPvNS_17DenseMapValueInfoIS5_EENS_12DenseMapInfoIS4_EENS_6detail12DenseMapPairIS4_S5_EEEES4_S5_S7_S9_SC_E15LookupBucketForIS4_EEbRKT_RPKSC_ : 260 -> 256
~ -[NSObject mutableCopy] : 24 -> 28
~ __ZN13list_array_ttIm15protocol_list_t6RawPtrE12iteratorImplILb0EEC2ENS2_12ListIteratorES5_ : 392 -> 404
~ -[NSObject copy] : 24 -> 28
~ __ZNK10class_rw_t2roEv : 144 -> 140
~ -[NSObject autorelease] : 8 -> 12
~ -[NSObject isProxy] : 20 -> 16
~ +[NSObject allocWithZone:] : 8 -> 12
~ _lookUpImpOrNilTryCache : 276 -> 272
~ +[NSObject resolveInstanceMethod:] : 20 -> 8
~ _objc_copyWeak : 76 -> 88
~ __ZL15append_referrerP12weak_entry_tPP11objc_object : 392 -> 396
~ _objc_destroyWeak : 276 -> 272
~ _weak_clear_no_lock : 400 -> 404
~ -[NSObject hash] : 8 -> 4
~ __ZL20grow_refs_and_insertP12weak_entry_tPP11objc_object : 288 -> 292
~ _objc_getAssociatedObject : 396 -> 392
~ __ZN11objc_object16rootAutorelease2Ev : 144 -> 132
~ __ZL19namedClassTableHashPKc : 156 -> 152
~ +[NSObject isSubclassOfClass:] : 96 -> 100
~ _sel_registerName : 24 -> 20
~ +[NSObject self] : 16 -> 4
~ _class_respondsToSelector : 12 -> 24
~ +[NSObject isProxy] : 12 -> 16
~ _objc_opt_new : 112 -> 108
~ +[NSObject class] : 4 -> 8
~ _objc_opt_class : 204 -> 200
~ __ZNK11objc_object24sidetable_isDeallocatingEv : 148 -> 136
~ __ZN4objc12DenseMapBaseINS_8DenseMapI12DisguisedPtrIK11objc_objectEmN12_GLOBAL__N_125RefcountMapValuePurgeableENS_12DenseMapInfoIS5_EENS_6detail12DenseMapPairIS5_mEEEES5_mS7_S9_SC_E20InsertIntoBucketImplIS5_EEPSC_RKS5_RKT_SG_ : 204 -> 200
~ __ZNK11objc_object14sidetable_lockEv : 64 -> 68
~ -[NSObject methodForSelector:] : 80 -> 92
~ +[NSObject instanceMethodForSelector:] : 60 -> 64
~ _objc_sync_nil : 16 -> 12
~ +[NSObject instancesRespondToSelector:] : 16 -> 20
~ __method_getImplementationAndName : 248 -> 244
~ +[NSObject isEqual:] : 12 -> 16
~ _sel_hash : 12 -> 8
~ +[NSObject hash] : 16 -> 4
~ _sel_getUid : 20 -> 16
~ __ZN19AutoreleasePoolPage19autoreleaseFullPageEP11objc_objectPS_ : 204 -> 208
~ _objc_opt_isKindOfClass : 296 -> 292
~ -[NSObject retainCount] : 8 -> 12
~ __ZN7cache_t13collectNolockEb : 488 -> 500
~ +[NSObject isMemberOfClass:] : 28 -> 32
~ _protocol_getName : 32 -> 24
~ __ZN10protocol_t13demangledNameEv : 132 -> 124
~ __ZL13SkipFirstTypePKc : 212 -> 208
~ __ZL11static_initv : 232 -> 236
~ _map_images_nolock : 8352 -> 8384
~ __ZNK11header_info9classlistEPm : 152 -> 148
~ __ZL24hasSignedClassROPointersPK14mach_header_64P29_dyld_section_location_info_s : 88 -> 92
~ __ZL12allocBucketsj : 88 -> 96
~ __ZL9protocolsv : 192 -> 200
~ _objc_opt_self : 48 -> 44
~ __ZL11weak_resizeP12weak_table_tm : 196 -> 200
~ _CALLING_SOME_+initialize_METHOD : 36 -> 32
~ +[NSObject initialize] : 16 -> 4
~ ____ZL17addMethods_finishP10objc_classP13method_list_t_block_invoke : 44 -> 56
~ +[NSObject resolveClassMethod:] : 8 -> 12
~ __ZN4objc7Scanner13isSwiftObjectEP10objc_class : 128 -> 124
~ +[NSObject retain] : 12 -> 16
~ _objc_getClass : 12 -> 24
~ +[NSObject superclass] : 64 -> 68
~ __ZN11objc_object21rootRelease_underflowEb : 624 -> 616
~ __ZL11getProtocolPKc : 148 -> 140
~ _method_getReturnType : 204 -> 200
~ +[NSObject respondsToSelector:] : 24 -> 28
~ __ZL33objc_initializeClassPair_internalP10objc_classPKcS0_S0_ : 1796 -> 1792
~ __ZL27_allocateTrampolinesAndDatav : 660 -> 664
~ __ZNK4objc12DenseMapBaseINS_8DenseMapIPK8method_tP23objc_method_descriptionNS_17DenseMapValueInfoIS6_EENS_12DenseMapInfoIS4_EENS_6detail12DenseMapPairIS4_S6_EEEES4_S6_S8_SA_SD_E15LookupBucketForIS4_EEbRKT_RPKSD_ : 260 -> 256
~ +[NSObject isKindOfClass:] : 104 -> 108
~ __ZNK4objc12DenseMapBaseINS_8DenseMapI12DisguisedPtrI10objc_classES4_NS_17DenseMapValueInfoIS4_EENS_12DenseMapInfoIS4_EENS_6detail12DenseMapPairIS4_S4_EEEES4_S4_S6_S8_SB_E15LookupBucketForIS4_EEbRKT_RPKSB_ : 244 -> 256
~ +[NSObject new] : 92 -> 80
~ __ZNSt3__118__stable_sort_moveINS_17_ClassicAlgPolicyERN8method_t16SortBySELAddressEPNS2_9bigSignedEEEvT1_S7_T0_NS_15iterator_traitsIS7_E15difference_typeEPNSA_10value_typeE : 1276 -> 1288
~ +[NSObject performSelector:] : 80 -> 84
~ ____ZZL16attachCategoriesP10objc_classPK21locstamped_category_tjS0_iENK3$_0clEPZL16attachCategoriesS0_S3_jS0_iE5Listsb_block_invoke : 52 -> 48
~ +[NSObject release] : 16 -> 4
~ __ZL13remapClassRefPP10objc_classjbU13block_pointerFvjE : 476 -> 492
~ __ZN10objc_class37installMangledNameForLazilyNamedClassEv : 436 -> 448
~ __ZL25pageAndIndexContainingIMPPFvvEPm : 308 -> 312
~ -[NSObject debugDescription] : 20 -> 12
~ __ZL13fixupProtocolP10protocol_tjbU13block_pointerFvjE : 1256 -> 1264
~ __ZL23fixupProtocolMethodListP10protocol_tP13method_list_tbbbPPP13objc_selector : 660 -> 656
~ +[NSObject performSelector:withObject:] : 108 -> 96
~ _protocol_copyProtocolList : 420 -> 416
~ +[NSObject copyWithZone:] : 12 -> 16
~ _NXMapKeyCopyingInsert : 268 -> 264
~ __headerForAddress : 188 -> 192
~ _property_getAttributes : 8 -> 20
~ __ZNK19AutoreleasePoolPage10busted_dieEv : 40 -> 44
~ _objc_addLoadImageFunc : 316 -> 312
~ _objc_weak_error : 16 -> 4
~ __ZL13weakTableScanv : 356 -> 352
~ _objc_autoreleaseNoPool : 16 -> 4
~ _objc_autoreleasePoolInvalid : 12 -> 8
~ __ZNK11objc_object21sidetable_retainCountEv : 232 -> 220
~ -[__NSUnrecognizedTaggedPointer autorelease] : 4 -> 16
~ +[NSObject forwardInvocation:] : 88 -> 92
~ -[NSObject forwardInvocation:] : 96 -> 92
~ +[NSObject description] : 8 -> 12
~ -[NSObject description] : 12 -> 8
~ __ZNK19AutoreleasePoolPage6bustedIPFvPKczEEEvT_ : 148 -> 152
~ __ZNK4objc12DenseMapBaseINS_13SmallDenseMapIPKvNS_15ObjcAssociationELj1ENS_17DenseMapValueInfoIS4_EENS_12DenseMapInfoIS3_EENS_6detail12DenseMapPairIS3_S4_EEEES3_S4_S6_S8_SB_E22FatalCorruptHashTablesEPKSB_j : 96 -> 92
~ __ZL22defaultBadAllocHandlerP10objc_class : 36 -> 40
~ __ZL18startWeakTableScanv : 132 -> 128
~ +[NSObject doesNotRecognizeSelector:] : 80 -> 68
~ -[NSObject doesNotRecognizeSelector:] : 80 -> 76
~ +[NSObject methodSignatureForSelector:] : 24 -> 28
```
