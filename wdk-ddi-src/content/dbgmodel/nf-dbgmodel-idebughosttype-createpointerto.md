---
UID: NF:dbgmodel.IDebugHostType.CreatePointerTo
title: IDebugHostType::CreatePointerTo
author: windows-driver-content
description: TBD
ms.assetid: 7809e00f-93db-4ddd-80d0-6259cea77382
ms.author: windowsdriverdev
ms.date: 08/22/2018
ms.topic: method
ms.keywords: IDebugHostType::CreatePointerTo, CreatePointerTo, IDebugHostType.CreatePointerTo, IDebugHostType::CreatePointerTo, IDebugHostType.CreatePointerTo
req.header: dbgmodel.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.irql: 
req.ddi-compliance:
req.unicode-ansi:
req.idl:
req.max-support:
req.namespace:
req.assembly:
req.type-library: 
topic_type: 
-	apiref
api_type: 
-	COM
api_location: 
-	dbgmodel.h
api_name: 
-	IDebugHostType.CreatePointerTo
product: Windows
targetos: Windows


---

# IDebugHostType::CreatePointerTo


## -description

For any given type, this returns a new IDebugHostType which is a pointer to this type.
The kind of pointer is supplied by the "kind" argument.

## -parameters

### -param kind

### -param newType


## -returns
This method returns HRESULT that indicates success or failure.

## -remarks

## -see-also

[IDebugHostType interface](nn-dbgmodel-idebughosttype.md)