---
description: "Specifies the stack frame type."
title: "StackFrameTypeEnum"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "StackFrameTypeEnum enumeration"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
---
# StackFrameTypeEnum

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Specifies the stack frame type.

## Syntax

```C++
enum StackFrameTypeEnum {
    FrameTypeFPO,
    FrameTypeTrap,
    FrameTypeTSS,
    FrameTypeStandard,
    FrameTypeFrameData,
    FrameTypeUnknown = -1
};
```

## Elements
`FrameTypeFPO`
Frame pointer omitted; FPO info available.

`FrameTypeTrap`
Kernel Trap frame.

`FrameTypeTSS`
Kernel Trap frame.

`FrameTypeStandard`
Standard EBP stack frame.

`FrameTypeFrameData`
Frame pointer omitted; Frame data info available.

`FrameTypeUnknown`
Frame that does not have any debug info.

## Remarks
The values in this enumeration are returned by a call to the [IDiaStackFrame::get_type](../../debugger/debug-interface-access/idiastackframe-get-type.md) method.

## Requirements
Header: cvconst.h

## See also
- [Enumerations and Structures](../../debugger/debug-interface-access/enumerations-and-structures.md)
- [IDiaStackFrame::get_type](../../debugger/debug-interface-access/idiastackframe-get-type.md)
