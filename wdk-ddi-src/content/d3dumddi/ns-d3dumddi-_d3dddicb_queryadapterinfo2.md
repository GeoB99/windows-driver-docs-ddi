---
UID: NS:d3dumddi._D3DDDICB_QUERYADAPTERINFO2
title: _D3DDDICB_QUERYADAPTERINFO2 (d3dumddi.h)
description: Contains information that describes the graphics adapter.
ms.date: 10/19/2018
keywords: ["D3DDDICB_QUERYADAPTERINFO2 structure"]
ms.keywords: _D3DDDICB_QUERYADAPTERINFO2, D3DDDICB_QUERYADAPTERINFO2,
req.header: d3dumddi.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.ddi-compliance: 
req.unicode-ansi: 
req.max-support: 
req.typenames: D3DDDICB_QUERYADAPTERINFO2
targetos: Windows
tech.root: display
f1_keywords:
 - _D3DDDICB_QUERYADAPTERINFO2
 - d3dumddi/_D3DDDICB_QUERYADAPTERINFO2
 - D3DDDICB_QUERYADAPTERINFO2
 - d3dumddi/D3DDDICB_QUERYADAPTERINFO2
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - d3dumddi.h
api_name:
 - _D3DDDICB_QUERYADAPTERINFO2
 - D3DDDICB_QUERYADAPTERINFO2
product:
 - Windows
---

# _D3DDDICB_QUERYADAPTERINFO2 structure


## -description

Contains information that describes the graphics adapter.

## -struct-fields

### -field QueryType

The type of query.

### -field pPrivateDriverData [out]

A pointer to a buffer that the display miniport driver can fill with information about the graphics adapter.

### -field PrivateDriverDataSize [in/out]

The size, in bytes, of the buffer that <b>pPrivateDriverData</b> points to.

