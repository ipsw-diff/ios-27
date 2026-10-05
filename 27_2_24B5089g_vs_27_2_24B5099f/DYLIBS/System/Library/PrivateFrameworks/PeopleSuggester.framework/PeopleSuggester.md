## PeopleSuggester

> `/System/Library/PrivateFrameworks/PeopleSuggester.framework/PeopleSuggester`

```diff

-1975.0.0.0.0
-  __TEXT.__text: 0x1291b4
+1976.0.0.0.0
+  __TEXT.__text: 0x1292c0
   __TEXT.__objc_methlist: 0xaedc
   __TEXT.__const: 0x988
   __TEXT.__gcc_except_tab: 0x4a90

   __AUTH_CONST.__objc_arrayobj: 0x11d60
   __AUTH_CONST.__objc_doubleobj: 0xe0
   __AUTH_CONST.__objc_dictobj: 0x22858
-  __AUTH_CONST.__auth_got: 0x800
-  __AUTH.__objc_data: 0x1db0
+  __AUTH_CONST.__auth_got: 0x808
   __DATA.__objc_ivar: 0xf34
-  __DATA.__data: 0x428
   __DATA.__bss: 0xb48
-  __DATA_DIRTY.__objc_data: 0x1950
+  __DATA_DIRTY.__objc_data: 0x3700
+  __DATA_DIRTY.__data: 0x428
   __DATA_DIRTY.__bss: 0x520
   - /System/Library/Frameworks/CoreData.framework/CoreData
   - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

   - /usr/lib/libarchive.2.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 5368
-  Symbols:   7993
+  Symbols:   7994
   CStrings:  17939
 
Symbols:
+ __CDStringByConvertingPhoneNumberStringToASCII
Functions:
~ -[_PSContactCache getContactForHandle:handleType:] : 1136 -> 1156
~ -[_PSEnsembleModel suggestionsFromSuggestionProxies:supportedBundleIDs:contactKeysToFetch:meContactIdentifier:maxSuggestions:predictionContext:] : 15060 -> 15156
~ -[_PSEnsembleModel psr_suggestionsFromSuggestionProxies:interactionsStatistics:maxSuggestions:predictionContext:] : 1960 -> 1988
~ ___37-[_PSFamilyRecommender currentFamily]_block_invoke : 1444 -> 1472
~ -[_PSContactResolver resolveContactIdentifier:] : 812 -> 828
~ -[_PSContactResolver resolveContactIfPossibleFromContactIdentifierString:pickFirstOfMultiple:] : 280 -> 308
~ +[_PSContactResolver normalizedHandlesDictionaryFromHandles:] : 416 -> 448
~ -[_PSContactCatalog resolveVisualIdentifiersForHandles:catalogContactData:keepGoing:] : 8932 -> 8952
```
