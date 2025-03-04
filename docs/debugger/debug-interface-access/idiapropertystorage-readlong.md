---
description: "Reads LONG values in a property set."
title: "IDiaPropertyStorage::ReadLONG"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaPropertyStorage::ReadLONG"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaPropertyStorage::ReadLONG

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Reads `LONG` values in a property set.

## Syntax

```C++
HRESULT ReadDLONG ( 
   PROPID id,
   LONG*  pValue
);
```

#### Parameters
 `id`

[in] Identifier of the property to be read (`PROPID` is defined in WTypes.h as a `ULONG`).

 `pValue`

[out] Returns the property value.

## Return Value
 If successful, returns `S_OK`; otherwise returns an error code. Returns `E_INVALIDARG` if the property is not of type `LONG`.

## Remarks
 A `LONG` is defined by Windows as a 32-bit signed integer.

## See also
- [IDiaPropertyStorage](../../debugger/debug-interface-access/idiapropertystorage.md)
