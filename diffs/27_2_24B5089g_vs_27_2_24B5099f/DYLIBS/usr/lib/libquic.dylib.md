## libquic.dylib

> `/usr/lib/libquic.dylib`

```diff

-6681.40.82.0.0
-  __TEXT.__text: 0xd0a68
+6681.40.95.0.6
+  __TEXT.__text: 0xd116c
   __TEXT.__objc_methlist: 0x244
   __TEXT.__const: 0x3b5
-  __TEXT.__cstring: 0x88b5
-  __TEXT.__oslogstring: 0x1260d
+  __TEXT.__cstring: 0x8907
+  __TEXT.__oslogstring: 0x12684
   __TEXT.__unwind_info: 0xd18
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH_CONST.__const: 0xcd0
   __AUTH_CONST.__cfstring: 0x1320
   __AUTH_CONST.__objc_const: 0xf8
-  __AUTH_CONST.__auth_got: 0xdc8
-  __AUTH.__objc_data: 0x50
+  __AUTH_CONST.__auth_got: 0xdd0
+  __AUTH.__objc_data: 0x28
   __AUTH.__data: 0x118
   __DATA.__objc_ivar: 0xc
   __DATA.__data: 0x6c
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x520
-  __DATA_DIRTY.__data: 0x1c
-  __DATA_DIRTY.__bss: 0x660
+  __DATA_DIRTY.__objc_data: 0x28
+  __DATA_DIRTY.__data: 0x18
+  __DATA_DIRTY.__bss: 0x690
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Foundation
   - /System/Library/Frameworks/Network.framework/Network
   - /System/Library/Frameworks/Security.framework/Security
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1157
-  Symbols:   1659
-  CStrings:  2618
+  Functions: 1160
+  Symbols:   1663
+  CStrings:  2623
 
Symbols:
+ _nw_quic_connection_get_path_recovery_timeout
+ _quic_migration_pulse_applies
+ _quic_migration_pulse_fire_now
+ _quic_migration_pulse_stop
Functions:
~ _quic_conn_handle_start_inner : 3512 -> 3508
~ _quic_conn_process_sh : 1152 -> 1148
~ ___quic_conn_outbound_stopping_block_invoke : 804 -> 800
~ _quic_stream_send_create : 3132 -> 3136
~ ___quic_conn_inbound_starting_block_invoke : 1284 -> 1280
~ _quic_stream_deallocate : 2860 -> 2856
~ ___quic_conn_inbound_stopping_block_invoke : 1372 -> 1368
~ _quic_path_assign_dcid : 968 -> 964
~ _quic_conn_process_lh : 4648 -> 4644
~ _quic_conn_initialize_inner : 5584 -> 5596
~ _quic_conn_handle_stop_inner : 1920 -> 1916
~ ___quic_migration_path_event_block_invoke : 2964 -> 2960
~ _quic_migration_path_established : 3944 -> 3940
~ ___quic_conn_outbound_data_pending_block_invoke : 772 -> 768
~ _quic_migration_evaluate : 6748 -> 6512
~ ___quic_migration_connected_block_invoke : 292 -> 288
~ ___quic_timer_run_block_invoke : 692 -> 688
~ _quic_conn_keepalive_handler : 6632 -> 6624
~ _quic_conn_drain : 2604 -> 2600
~ _quic_conn_close : 2040 -> 2036
~ ___quic_conn_traffic_mgmt_block_invoke : 1644 -> 1640
~ _quic_migration_probe_path : 4464 -> 4468
~ _quic_conn_unknown_dcid : 4600 -> 4596
~ _quic_migration_received_challenge : 2836 -> 2832
~ _quic_migration_received_response : 3436 -> 3432
~ _quic_conn_migrate_to_path : 4428 -> 4412
~ _quic_recovery_pto : 5816 -> 5812
~ ___quic_migration_fallback_event_block_invoke : 740 -> 736
~ _quic_recovery_find_lost_packets : 2208 -> 2204
~ _quic_migration_timer : 1080 -> 1128
~ _quic_migration_pulse_start : 204 -> 952
+ _quic_migration_pulse_applies
+ _quic_migration_pulse_stop
+ _quic_migration_pulse_fire_now
~ ___quic_frame_process_DATAGRAM_block_invoke : 180 -> 184
~ _quic_stream_compute_datagram_usable_frame_size : 1924 -> 1744
~ ___quic_conn_set_mss_block_invoke.87 : 72 -> 80
~ _quic_conn_refresh_stateless_reset_token : 1348 -> 1344
~ _quic_conn_probe_connectivity_internal : 3452 -> 3448
~ ___quic_conn_link_advisory_block_invoke : 2368 -> 2364
~ _quic_conn_handle_error_inner : 2540 -> 2536
CStrings:
+ "%{public}s %{public}s [%{public}s-%{public}s] arming pulse timer (%llu ms)"
+ "%{public}s %{public}s [%{public}s-%{public}s] cancelling pulse timer"
+ "%{public}s %{public}s [%{public}s-%{public}s] nothing left to try, reporting failure now rather than waiting"
+ "%{public}s not arming pulse timer on companion path; expecting connectivity to resume"
+ "quic_migration_pulse_applies"
+ "quic_migration_pulse_start"
+ "quic_migration_pulse_stop"
- "%{public}s %{public}s [%{public}s-%{public}s] cancelling pulse timer; current path is still usable"
- "%{public}s %{public}s [%{public}s-%{public}s] not arming pulse timer on companion path; expecting connectivity to resume"
```
