---
description: "Retrieves a flag that indicates whether the function contains debug information that is specific for optimized code."
title: "IDiaSymbol::get_optimizedCodeDebugInfo"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaSymbol::get_optimizedCodeDebugInfo method"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaSymbol::get_optimizedCodeDebugInfo

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves a flag that indicates whether the function contains debug information that is specific for optimized code.

## Syntax

```C++
HRESULT get_optimizedCodeDebugInfo(
   BOOL *pFlag
);
```

#### Parameters
 `pFlag`

[out] Returns `TRUE` if the optimized function or label contains debugging information; otherwise, returns `FALSE`.

## Return Value
 If successful, returns `S_OK`; otherwise, returns `S_FALSE` or an error code.

> [!NOTE]
> A return value of `S_FALSE` means the property is not available for the symbol.

## Requirements

|Requirement|Description|
|-----------------|-----------------|
|Header:|dia2.h|

## See also
- [IDiaSymbol](../../debugger/debug-interface-access/idiasymbol.md)
