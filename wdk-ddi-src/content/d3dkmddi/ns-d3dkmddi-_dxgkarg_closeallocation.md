---
UID: NS:d3dkmddi._DXGKARG_CLOSEALLOCATION
title: _DXGKARG_CLOSEALLOCATION (d3dkmddi.h)
description: The DXGKARG_CLOSEALLOCATION structure describes allocations that the display miniport driver should close.
old-location: display\dxgkarg_closeallocation.htm
ms.date: 05/10/2018
keywords: ["DXGKARG_CLOSEALLOCATION structure"]
ms.keywords: DXGKARG_CLOSEALLOCATION, DXGKARG_CLOSEALLOCATION structure [Display Devices], DmStructs_0d76b996-7ce8-4471-894f-585cc9f3f225.xml, _DXGKARG_CLOSEALLOCATION, d3dkmddi/DXGKARG_CLOSEALLOCATION, display.dxgkarg_closeallocation
req.header: d3dkmddi.h
req.include-header: D3dkmddi.h
req.target-type: Windows
req.target-min-winverclnt: Available in Windows Vista and later versions of the Windows operating systems.
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
tech.root: display
req.typenames: DXGKARG_CLOSEALLOCATION
f1_keywords:
 - _DXGKARG_CLOSEALLOCATION
 - d3dkmddi/_DXGKARG_CLOSEALLOCATION
 - DXGKARG_CLOSEALLOCATION
 - d3dkmddi/DXGKARG_CLOSEALLOCATION
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - d3dkmddi.h
api_name:
 - _DXGKARG_CLOSEALLOCATION
 - DXGKARG_CLOSEALLOCATION
---

# _DXGKARG_CLOSEALLOCATION structure


## -description

The DXGKARG_CLOSEALLOCATION structure describes allocations that the display miniport driver should close.

## -struct-fields

### -field NumAllocations [in]

The number of elements in the array that <b>pOpenHandleList</b> specifies.

### -field pOpenHandleList [in]

An array of handles to device-specific allocations to close.

## -see-also

<a href="/windows-hardware/drivers/ddi/d3dkmddi/nc-d3dkmddi-dxgkddi_closeallocation">DxgkDdiCloseAllocation</a>

