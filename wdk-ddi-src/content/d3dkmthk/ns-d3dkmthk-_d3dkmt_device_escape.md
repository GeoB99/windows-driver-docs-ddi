---
UID: NS:d3dkmthk._D3DKMT_DEVICE_ESCAPE
title: _D3DKMT_DEVICE_ESCAPE (d3dkmthk.h)
description: Do not use the D3DKMT_DEVICE_ESCAPE structure or D3DKMT_DEVICEESCAPE_TYPE enumeration. They are for testing purposes only. The D3DKMT_DEVICE_ESCAPE structure describes how to control the display device in a call to the D3DKMTEscape function.
old-location: display\d3dkmt_device_escape.htm
ms.date: 05/10/2018
keywords: ["D3DKMT_DEVICE_ESCAPE structure"]
ms.keywords: D3DKMT_DEVICE_ESCAPE, D3DKMT_DEVICE_ESCAPE structure [Display Devices], OpenGL_Structs_38febe04-ae75-475a-ab69-81995acb567b.xml, _D3DKMT_DEVICE_ESCAPE, d3dkmthk/D3DKMT_DEVICE_ESCAPE, display.d3dkmt_device_escape
req.header: d3dkmthk.h
req.include-header: D3dkmthk.h
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
req.typenames: D3DKMT_DEVICE_ESCAPE
f1_keywords:
 - _D3DKMT_DEVICE_ESCAPE
 - d3dkmthk/_D3DKMT_DEVICE_ESCAPE
 - D3DKMT_DEVICE_ESCAPE
 - d3dkmthk/D3DKMT_DEVICE_ESCAPE
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - d3dkmthk.h
api_name:
 - _D3DKMT_DEVICE_ESCAPE
 - D3DKMT_DEVICE_ESCAPE
---

# _D3DKMT_DEVICE_ESCAPE structure


## -description

   Do not use the D3DKMT_DEVICE_ESCAPE structure or D3DKMT_DEVICEESCAPE_TYPE enumeration. They are for testing purposes only.
   

The D3DKMT_DEVICE_ESCAPE structure describes how to control the display device in a call to the <a href="/windows-hardware/drivers/ddi/d3dkmthk/nf-d3dkmthk-d3dkmtescape">D3DKMTEscape</a> function.

## -struct-fields

### -field Type

### -field VidPnFromAllocation

### -field VidPnFromAllocation.hPrimaryAllocation [in]

The primary allocation handle.

### -field VidPnFromAllocation.VidPnSourceId [out]

The VidPN source ID of the primary allocation.

## -see-also

<a href="/windows-hardware/drivers/ddi/d3dkmthk/nf-d3dkmthk-d3dkmtescape">D3DKMTEscape</a>



<a href="/windows-hardware/drivers/ddi/d3dkmthk/ns-d3dkmthk-_d3dkmt_escape">D3DKMT_ESCAPE</a>

