## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8150.RELEASE.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__mod_init_func`
- `__PDATA.__data`
- `__PDATA.__shared_cache`

```diff

-1777.40.28.0.2
-  __TEXT.__text: 0xe95634
+1777.40.34.0.0
+  __TEXT.__text: 0xe9c5e0
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0xb1971
-  __TEXT.__const: 0x1ba214
-  __TEXT.__swift5_typeref: 0x30690
-  __TEXT.__swift5_reflstr: 0x44788
-  __TEXT.__swift5_assocty: 0xfe80
-  __TEXT.__swift5_fieldmd: 0x6a874
-  __TEXT.__constg_swiftt: 0x6eefc
+  __TEXT.__cstring: 0xb2081
+  __TEXT.__const: 0x1ba554
+  __TEXT.__swift5_typeref: 0x30720
+  __TEXT.__swift5_reflstr: 0x44968
+  __TEXT.__swift5_assocty: 0xfe98
+  __TEXT.__swift5_fieldmd: 0x6aa08
+  __TEXT.__constg_swiftt: 0x6f080
   __TEXT.__swift5_protos: 0x14bc
-  __TEXT.__swift5_proto: 0xb30c
-  __TEXT.__swift5_types: 0x6fb0
+  __TEXT.__swift5_proto: 0xb324
+  __TEXT.__swift5_types: 0x6fc4
   __TEXT.__swift5_types2: 0xc4
   __TEXT.__swift5_builtin: 0x2bc0
-  __TEXT.__swift5_capture: 0x375c
-  __TEXT.__objc_methtype: 0x556
+  __TEXT.__swift5_capture: 0x377c
+  __TEXT.__objc_methtype: 0x576
   __TEXT.__swift5_mpenum: 0xdc4
-  __TEXT.__swift_as_entry: 0x1670
-  __TEXT.__swift_as_ret: 0x1880
-  __TEXT.__swift_as_cont: 0x2f58
-  __TEXT.__oslogstring: 0x7085
+  __TEXT.__swift_as_entry: 0x1684
+  __TEXT.__swift_as_ret: 0x18a4
+  __TEXT.__swift_as_cont: 0x2f94
+  __TEXT.__oslogstring: 0x70e5
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x140
-  __TEXT.__eh_frame: 0x82be0
+  __TEXT.__eh_frame: 0x82fd4
   __DATA.__TIGHTBEAM_VT: 0x1530
   __DATA.__TIGHTBEAM: 0x590
-  __DATA.__const: 0x105dc0
-  __DATA.__data: 0x59e58
+  __DATA.__const: 0x106128
+  __DATA.__data: 0x59fe0
   __DATA.__mod_init_func: 0x40
-  __DATA.__ENDPOINTS: 0x1bbd0
-  __DATA.__auth_ptr: 0x90d0
+  __DATA.__ENDPOINTS: 0x1bcd7
+  __DATA.__auth_ptr: 0x90e8
   __DATA.__DEVICETREE: 0x30
   __DATA.__shared_cache: 0x3b8
   __DATA.__DARTS: 0x93f

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0x24fd0
-  __DATA.__common: 0x31a9
+  __DATA.__bss: 0x24fe0
+  __DATA.__common: 0x3199
   __PDATA.__auth_ptr: 0x280
   __PDATA.__const: 0x6810
   __PDATA.__objc_imageinfo: 0x8

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 50828
+  Functions: 50909
   Symbols:   1
-  CStrings:  16468
+  CStrings:  16514
 
CStrings:
+ " DisplayManager is not configured!"
+ " but a session is already active!"
+ " but startTimestampUS is nil!"
+ " deferrals(hwBusy)="
+ " deferrals(pipelineBusy)="
+ " for Storage exclave"
+ " gateEarlyRejects="
+ " gateExemptedBuffers="
+ " is not a valid integer: "
+ " opted into prefers-waiting-through-sleep, blocking: "
+ " parked request(s) with mappers disabled; they will submit against unmapped DART state"
+ " parking until sleep cycle completes, parked: "
+ " rejected before IO prep. SleepCycle: "
+ "), deferring DART unmap"
+ "430.40.6"
+ ": panicking to prevent MTE tag brute-forcing"
+ "; using no-op control"
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Mon Sep 28 22:45:47 PDT 2026; root:AppleImage4_exclavecore-374~19125/ExclaveImage4/RELEASE_ARM64E"
+ "ANEExclave version: ANEExclave_exclavecore-13.102.1"
+ "Applying MTE backoff of "
+ "Build Date: Mon Sep 28 22:24:15 PDT 2026"
+ "Builtin.Borrow is not supported in runtime type lookup"
+ "Bundle metadata for "
+ "Conclave MTE tag check fault: esr="
+ "Could not start storage: "
+ "ENABLED via driver opt-in"
+ "Empty value of bundle metadata "
+ "ExclaveOS Image4 Framework Version 7.0.0: Mon Sep 28 22:45:47 PDT 2026; root:AppleImage4_exclavecore-374~19125/ExclaveImage4/RELEASE_ARM64E"
+ "In-flight HW or pipeline requests present (pipeline: "
+ "Initialized count must be in 0 ... unsafeUninitializedCapacity."
+ "Invalid log level "
+ "MTE tag check fault #"
+ "Mon Sep 28 23:19:17 PDT 2026"
+ "Park-through-sleep "
+ "ParkThroughSleep enabled: "
+ "SEP power control wired but SoC type is unknown; disabling SEP reset lockout"
+ "SEP reset lockout not supported on "
+ "SEP reset protection "
+ "SEP reset protection enabled: "
+ "SEP reset protection requested but no SEP control is wired on this part"
+ "SetLogLevelFromBundle()"
+ "SleepCycle parked requests: "
+ "SleepCycle pipeline count: "
+ "SleepCycle totals: parks="
+ "Storage not ready"
+ "StorageExclaveComponent/XRTBundleResources.swift"
+ "[SecureM3Handler] ERROR firmware load failed"
+ "[SecureM3Handler] MCPU power "
+ "[SecureM3Handler] MCPU power %ld -> %ld"
+ "disabled (default)"
+ "getBundleMetadata(_:)"
+ "ns before launch"
+ "ns before next launch"
+ "releasePipelineReservation not called with workLoop Gate held!"
+ "sharedmem_framemap_getPhysicalAddress"
+ "sharedmem_framemap_setMapped_delta"
+ "takePipelineReservation called twice for request "
+ "takePipelineReservation not called with workLoop Gate held!"
+ "v24@?0{sharedmem_pagerange=QQ}8"
+ "waitForSleepCycleCompletion not called with workLoop Gate held!"
+ "writeFileInternal(client:catInfo:name:offset:length:encrypted:inputBuffer:)"
- " opted into prefers-waiting-through-sleep; option accepted but not yet implemented"
- "430.40.5"
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Sat Sep 12 05:10:17 PDT 2026; root:AppleImage4_exclavecore-374~18509/ExclaveImage4/RELEASE_ARM64E"
- "ANEExclave version: ANEExclave_exclavecore-13.101.1"
- "Build Date: Sat Sep 12 04:43:50 PDT 2026"
- "ExclaveOS Image4 Framework Version 7.0.0: Sat Sep 12 05:10:17 PDT 2026; root:AppleImage4_exclavecore-374~18509/ExclaveImage4/RELEASE_ARM64E"
- "In-flight HW requests present, deferring DART unmap"
- "Initialized count set to greater than specified capacity."
- "Tue Sep 15 12:41:02 PDT 2026"
- "[SecurePairingCoreComponent]: Could not start storage: "
- "localmap_map(%zx): localmap() remap with changed PA (%llx != %llx)\n"
- "sharedmem_framemap_getPhysicalAddresses"
- "sharedmem_framemap_setMapped"
- "storage not ready"
- "writeFileInternal(client:catInfo:name:offset:length:encrypted:)"
```
