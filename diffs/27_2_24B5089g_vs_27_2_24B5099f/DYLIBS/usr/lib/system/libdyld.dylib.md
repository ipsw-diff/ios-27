## libdyld.dylib

> `/usr/lib/system/libdyld.dylib`

```diff

-27102.0.0.0.0
-  __TEXT.__text: 0x1cf28
+27104.0.0.0.0
+  __TEXT.__text: 0x1da98
   __TEXT.__const: 0x32c
-  __TEXT.__cstring: 0x4d20
+  __TEXT.__cstring: 0x4dd6
   __TEXT.__gcc_except_tab: 0x20
   __TEXT.__unwind_info: 0xda0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__got: 0x30
   __AUTH_CONST.__const: 0x17e8
   __AUTH_CONST.__auth_got: 0x1a0
-  __DATA.__data: 0x10
   __DATA.__crash_info: 0x148
+  __DATA.__data: 0x8
   __DATA.__common: 0x11
   __DATA.__bss: 0x18
   __DATA_DIRTY.__common: 0x28

   - /usr/lib/system/libsystem_pthread.dylib
   - /usr/lib/system/libunwind.dylib
   - /usr/lib/system/libxpc.dylib
-  Functions: 853
+  Functions: 854
   Symbols:   1079
-  CStrings:  548
+  CStrings:  552
 
Symbols:
+ __ZNK6mach_o6Header22parse_dylinker_commandERKNS0_15LoadCommandInfoEPNS_5ErrorE
- __ZZ16get_xprr_versionvE19cached_xprr_version
Functions:
~ __dyld_objc_class_count : 152 -> 176
~ _dyld_program_sdk_at_least : 156 -> 180
~ _dyld_get_active_platform : 152 -> 176
~ _dyld_image_header_containing_address : 156 -> 180
~ __dyld_for_each_objc_class : 160 -> 184
~ __dyld_get_objc_selector : 156 -> 180
~ __dyld_is_memory_immutable : 160 -> 184
~ __dyld_find_protocol_conformance_on_disk : 168 -> 192
~ __dyld_stack_range : 160 -> 184
~ __dyld_find_unwind_sections : 160 -> 184
~ __dyld_find_protocol_conformance : 164 -> 188
~ __dyld_call_with_writable_tpro_memory : 160 -> 184
~ __dyld_shared_cache_real_path : 156 -> 180
~ _dyld_sdk_at_least : 160 -> 184
~ _dyld_get_program_sdk_version_token : 152 -> 176
~ __dyld_get_image_slide : 156 -> 180
~ _dyld_process_is_restricted : 152 -> 176
~ _dyld_version_token_at_least : 160 -> 184
~ _dyld_shared_cache_some_image_overridden : 152 -> 176
~ __dyld_get_prog_image_header : 152 -> 176
~ __dyld_lookup_section_info : 164 -> 188
~ _dyld_image_path_containing_address : 156 -> 180
~ _dlopen : 152 -> 176
~ _dyld_get_base_platform : 156 -> 180
~ __dyld_shared_cache_contains_path : 156 -> 180
~ __dyld_for_each_objc_protocol : 160 -> 184
~ _dlsym : 152 -> 176
~ __dyld_find_pointer_hash_table_entry : 168 -> 192
~ __dyld_find_foreign_type_protocol_conformance : 164 -> 188
~ __NSGetExecutablePath : 152 -> 176
~ _dyld_has_inserted_or_interposing_libraries : 156 -> 188
~ __dyld_lazy_load_internal : 160 -> 184
~ __dyld_get_lib_msg_send_offsets : 152 -> 176
~ __dyld_objc_register_callbacks : 376 -> 400
~ __dyld_get_shared_cache_range : 156 -> 180
~ __dyld_for_objc_header_opt_ro : 152 -> 176
~ __dyld_for_objc_header_opt_rw : 152 -> 176
~ __dyld_has_preoptimized_swift_protocol_conformances : 156 -> 180
~ _NSVersionOfLinkTimeLibrary : 148 -> 172
~ _dladdr : 152 -> 176
~ __dyld_launch_mode : 152 -> 176
~ __dyld_find_foreign_type_protocol_conformance_on_disk : 168 -> 192
~ _dyld_program_minos_at_least : 156 -> 180
~ __dyld_get_image_uuid : 160 -> 184
~ _dlopen_from : 164 -> 188
~ __dyld_get_swift_prespecialized_data : 152 -> 176
~ __dyld_register_for_bulk_image_loads : 156 -> 180
~ __dyld_get_dlopen_image_header : 156 -> 180
~ _dyld_get_program_sdk_version : 152 -> 176
~ __dyld_images_for_addresses : 164 -> 188
~ __tlv_atexit : 128 -> 152
~ __dyld_swift_optimizations_version : 152 -> 176
~ __dyld_get_shared_cache_uuid : 156 -> 180
~ __dyld_register_func_for_add_image : 148 -> 172
~ __dyld_register_func_for_remove_image : 148 -> 172
~ __dyld_image_count : 144 -> 168
~ __dyld_get_image_header : 148 -> 172
~ __dyld_is_preoptimized_objc_image_loaded : 156 -> 180
~ __dyld_get_image_name : 148 -> 172
~ _dlopen_preflight : 148 -> 172
~ _dlclose : 148 -> 172
~ _NSVersionOfRunTimeLibrary : 148 -> 172
~ _dyld_get_image_versions : 160 -> 184
~ __dyld_get_image_vmaddr_slide : 148 -> 172
~ _dlerror : 144 -> 168
~ __dyld_dlsym_blocked : 152 -> 176
~ __dyld_dlopen_atfork_prepare : 152 -> 176
~ __dyld_atfork_prepare : 152 -> 176
~ __dyld_atfork_parent : 152 -> 176
~ __dyld_dlopen_atfork_parent : 152 -> 176
~ __tlv_exit : 120 -> 144
~ _dyld_shared_cache_iterate_text : 232 -> 256
~ _dyld_shared_cache_file_path : 152 -> 176
~ _dyld_shared_cache_find_iterate_text : 256 -> 280
~ __dyld_register_dlsym_notifier : 156 -> 180
~ __dyld_fork_child : 384 -> 400
~ _dyld_get_sdk_version : 156 -> 180
~ _dyld_get_min_os_version : 156 -> 180
~ _dyld_get_program_min_os_version : 152 -> 176
~ _dyld_dynamic_interpose : 100 -> 124
~ __tlv_bootstrap_error : 116 -> 140
~ __dyld_shared_cache_file_path_containing_address : 164 -> 188
~ __dyld_objc_notify_register : 164 -> 188
~ _dyld_is_simulator_platform : 156 -> 180
~ _dyld_minos_at_least : 160 -> 184
~ __dyld_register_for_image_loads : 156 -> 180
~ _dyld_need_closure : 160 -> 184
~ __dyld_shared_cache_optimized : 152 -> 176
~ __dyld_shared_cache_is_locally_built : 152 -> 176
~ __dyld_register_driverkit_main : 156 -> 180
~ __dyld_is_objc_constant : 160 -> 184
~ __dyld_has_fix_for_radar : 156 -> 180
~ _dlopen_audited : 160 -> 184
~ __dyld_visit_objc_classes : 156 -> 180
~ __dyld_objc_uses_large_shared_cache : 152 -> 176
~ __dyld_dlopen_atfork_child : 152 -> 176
~ __dyld_pseudodylib_register_callbacks : 288 -> 312
~ __dyld_pseudodylib_deregister_callbacks : 156 -> 180
~ __dyld_pseudodylib_register : 168 -> 192
~ __dyld_pseudodylib_deregister : 156 -> 180
~ __dyld_register_dlsym_notifier_with_handle : 156 -> 180
~ __dyld_is_pseudodylib : 156 -> 180
~ _dyld_get_program_minos_version_token : 152 -> 176
~ _dyld_version_token_get_platform : 156 -> 180
~ __dyld_for_each_prewarming_range : 156 -> 180
~ __dyld_get_dyld_header : 152 -> 176
~ __dyld_shared_cache_will_check_for_image_overrides : 152 -> 176
~ ___clang_call_terminate : 24 -> 32
~ __ZNK6mach_o6Header19parse_dylib_commandERKNS0_15LoadCommandInfoEPNS_5ErrorE : 292 -> 352
~ __ZNK6mach_o6Header20parse_string_commandERKNS0_15LoadCommandInfoEPNS_5ErrorE : 220 -> 260
~ __ZNK6mach_o6Header27validSemanticsSingleSegmentILb1EEENS_5ErrorERKNS_6PolicyEyNSt3__14spanIKhLm18446744073709551615EEE : 2416 -> 2424
~ __ZNK6mach_o6Header27validSemanticsSingleSegmentILb0EEENS_5ErrorERKNS_6PolicyEyNSt3__14spanIKhLm18446744073709551615EEE : 2380 -> 2388
~ __ZNK6mach_o6Header29stringFromOffsetInLoadCommandERKNS0_15LoadCommandInfoEjPNS_5ErrorE : 284 -> 320
+ __ZNK6mach_o6Header22parse_dylinker_commandERKNS0_15LoadCommandInfoEPNS_5ErrorE
~ ____ZNK6mach_o6Header9dylibInfoEv_block_invoke : 124 -> 148
CStrings:
+ "load command #%d %.*s name offset too small"
+ "load command #%d %.*s not a dylib load command"
+ "load command #%d %.*s path offset too small"
+ "load command #%d string start offset too small"
```
