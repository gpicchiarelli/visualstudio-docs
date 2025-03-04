---
description: "Retrieves the System.Runtime.InteropServices.ComTypes.IEnumVARIANT version of the segments enumerator."
title: "IDiaEnumSegments::get__NewEnum"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaEnumSegments::get__NewEnum method"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaEnumSegments::get__NewEnum

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves the <xref:System.Runtime.InteropServices.ComTypes.IEnumVARIANT> version of this enumerator.

## Syntax

```C++
HRESULT get__NewEnum ( 
   IUnknown** pRetVal
);
```

#### Parameters
 pRetVal

[out] Returns the `IUnknown` interface that represents the <xref:System.Runtime.InteropServices.ComTypes.IEnumVARIANT> version of this enumerator.

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code.

## See also
- [IDiaEnumSegments](../../debugger/debug-interface-access/idiaenumsegments.md)
