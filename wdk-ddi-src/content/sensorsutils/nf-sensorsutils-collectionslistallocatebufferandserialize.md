---
UID: NF:sensorsutils.CollectionsListAllocateBufferAndSerialize
title: CollectionsListAllocateBufferAndSerialize function (sensorsutils.h)
description: This routine allocates a buffer and then serializes a sensor collection list to it.
ms.date: 08/07/2018
keywords: ["CollectionsListAllocateBufferAndSerialize function"]
tech.root: sensors
ms.keywords: CollectionsListAllocateBufferAndSerialize
req.header: sensorsutils.h
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
targetos: Windows
ms.custom: RS5
f1_keywords:
 - CollectionsListAllocateBufferAndSerialize
 - sensorsutils/CollectionsListAllocateBufferAndSerialize
topic_type:
 - apiref
api_type:
 - LibDef
api_location:
 - sensorsutils.h
api_name:
 - CollectionsListAllocateBufferAndSerialize
product:
 - Windows
---

# CollectionsListAllocateBufferAndSerialize function


## -description

This routine allocates a buffer and then serializes a sensor collection list to it. On success, callers must use [SerializationBufferFree](nf-sensorsutils-serializationbufferfree.md) to free the buffer.

## -parameters

### -param SourceCollection [in]

Pointer to a collection list.

### -param pTargetBufferSizeInBytes [out]

The allocated buffer size (in bytes).

### -param pTargetBuffer [out]

Pointer to the allocated buffer, to hold the serialized data.

## -returns

This function returns NTSTATUS.

## -remarks

## -see-also

