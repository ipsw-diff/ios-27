## CoreGraphics

> `/System/Library/Frameworks/CoreGraphics.framework/CoreGraphics`

```diff

-2050.1.4.0.0
-  __TEXT.__text: 0x568918
+2050.1.5.0.0
+  __TEXT.__text: 0x569d68
   __TEXT.__resolver_help: 0xd8
   __TEXT.__delay_helper: 0x1f4
   __TEXT.__objc_methlist: 0x42a0
-  __TEXT.__const: 0x1e0020
+  __TEXT.__const: 0x1dffa0
   __TEXT.__cstring: 0x4393f
   __TEXT.__dlopen_cstrs: 0xd5
   __TEXT.__constg_swiftt: 0x1918

   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__auth_got: 0x26b0
   __AUTH.__objc_data: 0x17c0
-  __AUTH.__data: 0x330
+  __AUTH.__data: 0x298
   __DATA.__objc_ivar: 0x594
   __DATA.__data: 0x1b0c
-  __DATA.__bss: 0x7b30
+  __DATA.__bss: 0x7b10
   __DATA.__common: 0x245
   __DATA_DIRTY.__la_resolver: 0x10
-  __DATA_DIRTY.__data: 0xfb8
+  __DATA_DIRTY.__data: 0x1050
   __DATA_DIRTY.__crash_info: 0x148
-  __DATA_DIRTY.__bss: 0x2748
+  __DATA_DIRTY.__bss: 0x2770
   __DATA_DIRTY.__common: 0x8
   - /System/Library/Frameworks/Accelerate.framework/Accelerate
   - /System/Library/Frameworks/CFNetwork.framework/CFNetwork
Functions:
~ _ripc_AcquireRIPImageData : 1832 -> 1764
~ _img_data_lock : 10036 -> 10052
~ _initialize_skipping_conditional_var : 272 -> 276
~ _RIPLayerBltImage : 1172 -> 1188
~ __blt_image_initialize : 2044 -> 2056
~ _argb32_sample_argb32 : 1688 -> 1684
~ _A8_sample_ALPHA8 : 1844 -> 1868
~ _ripc_EndLayer : 1320 -> 1264
~ _GRAYA8_sample_GRAYA8 : 2108 -> 2120
~ _build_tile : 4140 -> 4148
~ _rgba64_sample_CMYK64 : 2248 -> 2296
~ _rgba64_sample_rgb48 : 1308 -> 1332
~ _rgba64_sample_w16 : 1604 -> 1652
~ _rgb555_sample_W8 : 1588 -> 1636
~ _rgb555_sample_RGB555 : 2108 -> 2112
~ _rgb555_sample_rgb555 : 2124 -> 2144
~ _rgb555_sample_RGB24 : 1444 -> 1468
~ _rgb555_sample_RGBA32 : 1276 -> 1300
~ _rgb555_sample_rgba32 : 1252 -> 1276
~ _rgb555_sample_ARGB32 : 1268 -> 1292
~ _rgb555_sample_argb32 : 1244 -> 1268
~ _rgb555_sample_CMYK32 : 1716 -> 1768
~ _rgb555_sample_cmyk32 : 1688 -> 1740
~ _rips_DrawDisplayList : 2672 -> 2616
~ _Wf_sample_W8 : 1632 -> 1680
~ _Wf_sample_W16 : 1744 -> 1792
~ _Wf_sample_w16 : 1660 -> 1708
~ __ZL18Wf_sample_WF_innerPK6_ImgOplli : 2032 -> 2028
~ __ZL18Wf_sample_Wf_innerPK6_ImgOplli : 1908 -> 1932
~ _Wf_sample_RGBF : 1348 -> 1372
~ _Wf_sample_RGBf : 1272 -> 1296
~ _Wf_sample_RGBAF : 1424 -> 1448
~ _Wf_sample_RGBAf : 1328 -> 1352
~ _Wf_sample_CMYKF : 1600 -> 1648
~ _Wf_sample_CMYKf : 1536 -> 1584
~ _cmyk32_sample_W8 : 1616 -> 1664
~ _cmyk32_sample_RGB555 : 1732 -> 1784
~ _cmyk32_sample_rgb555 : 1676 -> 1728
~ _cmyk32_sample_RGB24 : 1448 -> 1472
~ _cmyk32_sample_RGBA32 : 1312 -> 1336
~ _cmyk32_sample_rgba32 : 1288 -> 1312
~ _cmyk32_sample_ARGB32 : 1380 -> 1404
~ _cmyk32_sample_argb32 : 1368 -> 1392
~ _cmyk32_sample_CMYK32 : 2048 -> 2064
~ _cmyk32_sample_cmyk32 : 2100 -> 2124
~ _cmyk32_sample_CMYK64 : 2228 -> 2276
~ _cmyk32_sample_cmyk64 : 1776 -> 1824
~ _cmyk32_sample_CMYKF : 1684 -> 1724
~ _cmyk32_sample_CMYKf : 1620 -> 1660
~ _RGBAf_sample_RGB24 : 1436 -> 1460
~ _RGBAf_sample_RGBA32 : 1304 -> 1328
~ _RGBAf_sample_rgba32 : 1292 -> 1316
~ _RGBAf_sample_ARGB32 : 1304 -> 1320
~ _RGBAf_sample_argb32 : 1280 -> 1296
~ _RGBAf_sample_RGB48 : 1644 -> 1668
~ _RGBAf_sample_rgb48 : 1448 -> 1472
~ _RGBAf_sample_RGBA64 : 1744 -> 1772
~ _RGBAf_sample_rgba64 : 1368 -> 1396
~ _RGBAf_sample_WF : 1532 -> 1576
~ _RGBAf_sample_Wf : 1444 -> 1488
~ _RGBAf_sample_RGBF : 1312 -> 1324
~ _RGBAf_sample_RGBf : 1244 -> 1268
~ __ZL24RGBAf_sample_RGBAF_innerPK6_ImgOplli : 1824 -> 1836
~ __ZL24RGBAf_sample_RGBAf_innerPK6_ImgOplli : 1700 -> 1712
~ _RGBAf_sample_CMYKF : 1648 -> 1708
~ _RGBAf_sample_CMYKf : 1560 -> 1620
~ __ZL26GRAYA8_sample_RGBA32_innerPK6_ImgOplli : 2508 -> 2552
~ __ZL22GRAYA8_sample_W8_innerPK6_ImgOplli : 1720 -> 1768
~ _GRAYA8_sample_RGB24 : 1684 -> 1700
~ __ZL26GRAYA8_sample_CMYK32_innerPK6_ImgOplli : 2372 -> 2420
~ _CMYKf16_sample_Wf16 : 1792 -> 1840
~ __ZL25CMYKf16_sample_RGBf_innerPK6_ImgOplli : 4808 -> 4884
~ __ZL26CMYKf16_sample_RGBAf_innerPK6_ImgOplli : 5704 -> 5780
~ __ZL26CMYKf16_sample_CMYKf_innerPK6_ImgOplli : 2352 -> 2296
~ _w16_sample_W8 : 1600 -> 1648
~ _w16_sample_W16 : 2128 -> 2212
~ _w16_sample_w16 : 2068 -> 2148
~ _w16_sample_RGB48 : 1504 -> 1528
~ _w16_sample_rgb48 : 1308 -> 1332
~ _w16_sample_RGBA64 : 1664 -> 1688
~ _w16_sample_rgba64 : 1252 -> 1276
~ _w16_sample_CMYK64 : 2280 -> 2328
~ _w16_sample_cmyk64 : 1836 -> 1884
~ _w16_sample_WF : 1596 -> 1644
~ _w16_sample_Wf : 1516 -> 1564
~ _cmyk64_sample_CMYK32 : 1680 -> 1708
~ _cmyk64_sample_cmyk32 : 1652 -> 1680
~ _cmyk64_sample_W16 : 1708 -> 1756
~ _cmyk64_sample_w16 : 1624 -> 1672
~ _cmyk64_sample_RGB48 : 1568 -> 1592
~ _cmyk64_sample_rgb48 : 1372 -> 1396
~ _cmyk64_sample_RGBA64 : 1696 -> 1740
~ _cmyk64_sample_rgba64 : 1292 -> 1320
~ _cmyk64_sample_CMYK64 : 2644 -> 2672
~ _cmyk64_sample_cmyk64 : 2176 -> 2224
~ _cmyk64_sample_CMYKF : 1684 -> 1724
~ _cmyk64_sample_CMYKf : 1620 -> 1660
~ _argb32_sample_W8 : 1600 -> 1648
~ _argb32_sample_RGB555 : 1672 -> 1720
~ _argb32_sample_rgb555 : 1616 -> 1664
~ _argb32_sample_RGB24 : 1384 -> 1416
~ _argb32_sample_RGBA32 : 1272 -> 1296
~ _argb32_sample_rgba32 : 1248 -> 1272
~ _argb32_sample_ARGB32 : 1716 -> 1712
~ _argb32_sample_CMYK32 : 1716 -> 1768
~ _argb32_sample_cmyk32 : 1688 -> 1740
~ _argb32_sample_RGB48 : 1504 -> 1528
~ _argb32_sample_rgb48 : 1308 -> 1332
~ _argb32_sample_RGBA64 : 1664 -> 1688
~ _argb32_sample_rgba64 : 1240 -> 1268
~ _argb32_sample_RGBF : 1428 -> 1436
~ _argb32_sample_RGBf : 1360 -> 1368
~ _argb32_sample_RGBAF : 1528 -> 1552
~ _argb32_sample_RGBAf : 1416 -> 1440
~ _rgba64_sample_RGB24 : 1424 -> 1448
~ _rgba64_sample_RGBA32 : 1288 -> 1312
~ _rgba64_sample_rgba32 : 1264 -> 1288
~ _rgba64_sample_ARGB32 : 1288 -> 1316
~ _rgba64_sample_argb32 : 1264 -> 1292
~ _rgba64_sample_W16 : 1696 -> 1744
~ _rgba64_sample_RGB48 : 1496 -> 1520
~ _rgba64_sample_rgba64 : 1688 -> 1684
~ _rgba64_sample_cmyk64 : 1796 -> 1844
~ _rgba64_sample_RGBF : 1428 -> 1436
~ _rgba64_sample_RGBf : 1360 -> 1368
~ _rgba64_sample_RGBAF : 1528 -> 1552
~ _rgba64_sample_RGBAf : 1416 -> 1440
~ _W8_sample_W8 : 2104 -> 2128
~ _W8_sample_RGB555 : 1676 -> 1724
~ _W8_sample_rgb555 : 1620 -> 1668
~ _W8_sample_RGB24 : 1396 -> 1420
~ _W8_sample_RGBA32 : 1268 -> 1296
~ _W8_sample_rgba32 : 1244 -> 1272
~ _W8_sample_ARGB32 : 1272 -> 1296
~ _W8_sample_argb32 : 1248 -> 1272
~ _W8_sample_CMYK32 : 1716 -> 1768
~ _W8_sample_cmyk32 : 1688 -> 1740
~ _W8_sample_W16 : 1668 -> 1716
~ _W8_sample_w16 : 1584 -> 1632
~ _W8_sample_WF : 1580 -> 1628
~ _W8_sample_Wf : 1496 -> 1544
~ _rips_cm_Draw : 1228 -> 1168
~ _RIPLayerConvertLayer : 540 -> 476
~ _rips_gb_Draw : 1488 -> 1392
~ _CMYKf_sample_CMYK32 : 1720 -> 1768
~ _CMYKf_sample_cmyk32 : 1692 -> 1740
~ _CMYKf_sample_CMYK64 : 2324 -> 2372
~ _CMYKf_sample_cmyk64 : 1900 -> 1948
~ _CMYKf_sample_WF : 1548 -> 1592
~ _CMYKf_sample_Wf : 1452 -> 1492
~ _CMYKf_sample_RGBF : 1324 -> 1348
~ _CMYKf_sample_RGBf : 1260 -> 1284
~ _CMYKf_sample_RGBAF : 1400 -> 1424
~ _CMYKf_sample_RGBAf : 1304 -> 1328
~ __ZL24CMYKf_sample_CMYKF_innerPK6_ImgOplli : 2008 -> 2016
~ __ZL24CMYKf_sample_CMYKf_innerPK6_ImgOplli : 1948 -> 1952
~ _A8_sample_ALPHA16 : 1908 -> 1924
~ _A8_sample_alpha16 : 1852 -> 1876
~ _A8_sample_ALPHAF : 1784 -> 1804
~ _A8_sample_ALPHAf : 1728 -> 1748
~ _A8_sample_ALPHAf16 : 1768 -> 1788
~ _rgba32_sample_W8 : 1616 -> 1664
~ _rgba32_sample_RGB555 : 1668 -> 1716
~ _rgba32_sample_rgb555 : 1612 -> 1660
~ _rgba32_sample_RGB24 : 1384 -> 1408
~ _rgba32_sample_RGBA32 : 1716 -> 1708
~ _rgba32_sample_rgba32 : 1688 -> 1680
~ _rgba32_sample_ARGB32 : 1276 -> 1300
~ _rgba32_sample_argb32 : 1252 -> 1276
~ _rgba32_sample_CMYK32 : 1720 -> 1768
~ _rgba32_sample_cmyk32 : 1692 -> 1740
~ _rgba32_sample_RGB48 : 1504 -> 1528
~ _rgba32_sample_rgb48 : 1308 -> 1332
~ _rgba32_sample_RGBA64 : 1664 -> 1688
~ _rgba32_sample_rgba64 : 1252 -> 1276
~ _rgba32_sample_RGBF : 1428 -> 1436
~ _rgba32_sample_RGBf : 1360 -> 1368
~ _rgba32_sample_RGBAF : 1528 -> 1552
~ _rgba32_sample_RGBAf : 1416 -> 1440
~ _RGBAf16_sample_Wf16 : 1752 -> 1800
~ _RGBAf16_sample_RGBf16 : 1532 -> 1556
~ _RGBAf16_sample_CMYKf16 : 1864 -> 1912
~ __ZL20Wf16_sample_Wf_innerPK6_ImgOplli : 2268 -> 2248
~ __ZL22Wf16_sample_RGBf_innerPK6_ImgOplli : 1596 -> 1620
~ __ZL23Wf16_sample_RGBAf_innerPK6_ImgOplli : 2016 -> 2040
~ _Wf16_sample_CMYKf16 : 1884 -> 1932
~ __Z24CIF10_sample_CIF10_innerPK6_ImgOplli : 1608 -> 1656
~ _CIF10_sample_RGBAf16 : 1464 -> 1488
```
