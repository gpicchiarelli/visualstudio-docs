---
description: "Creates an enumerator that contains the same enumeration state as the current section contributions enumerator."
title: "IDiaEnumSectionContribs::Clone"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaEnumSectionContribs::Clone method"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# IDiaEnumSectionContribs::Clone

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Creates an enumerator that contains the same enumeration state as the current enumerator.

## Syntax

```C++
HRESULT Clone( 
   IDiaEnumSectionContrib** ppenum
);
```

#### Parameters
 ppenum

[out] Returns an [IDiaEnumSectionContribs](../../debugger/debug-interface-access/idiaenumsectioncontribs.md) object that contains a duplicate of the enumerator. The section contributions are not duplicated, only the enumerator.

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code.

## See also
- [IDiaEnumSectionContribs](../../debugger/debug-interface-access/idiaenumsectioncontribs.md)
