---
description: "Retrieves the symbol ID from which the pointer is based."
title: "IDiaSymbol::get_baseSymbolId"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaSymbol::get_baseSymbolId

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves the symbol ID from which the pointer is based.

## Syntax

```C++
HRESULT get_baseSymbolId(
   DWORD *pRetVal);
```

#### Parameters
 `pRetVal`

[out] A pointer to a `DWORD` that holds the symbol ID from which the pointer is based.

## Return Value
 If successful, returns `S_OK`; otherwise, returns `S_FALSE` or an error code.

## See also
- [IDiaSymbol](../../debugger/debug-interface-access/idiasymbol.md)
- [IDiaSymbol::get_baseSymbol](../../debugger/debug-interface-access/idiasymbol-get-basesymbol.md)
