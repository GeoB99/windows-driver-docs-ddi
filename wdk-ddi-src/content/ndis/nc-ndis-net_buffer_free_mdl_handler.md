---
UID: NC:ndis.NET_BUFFER_FREE_MDL_HANDLER
title: NET_BUFFER_FREE_MDL_HANDLER (ndis.h)
description: The NetFreeMdl function frees an MDL that was previously allocated by the NetAllocateMdl function.
old-location: netvista\netfreemdl.htm
tech.root: netvista
ms.date: 05/02/2018
keywords: ["NET_BUFFER_FREE_MDL_HANDLER callback function"]
ms.keywords: NET_BUFFER_FREE_MDL_HANDLER, NET_BUFFER_FREE_MDL_HANDLER callback, NetFreeMdl, NetFreeMdl callback function [Network Drivers Starting with Windows Vista], ndis/NetFreeMdl, ndis_netbuf_functions_ref_a005ffba-5557-4d9b-a647-63e9e06fa8ef.xml, netvista.netfreemdl
req.header: ndis.h
req.include-header: Ndis.h
req.target-type: Windows
req.target-min-winverclnt: Supported in NDIS 6.0 and later.
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
req.irql: <= DISPATCH_LEVEL
targetos: Windows
req.typenames: 
f1_keywords:
 - NET_BUFFER_FREE_MDL_HANDLER
 - ndis/NET_BUFFER_FREE_MDL_HANDLER
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - UserDefined
api_location:
 - Ndis.h
api_name:
 - NET_BUFFER_FREE_MDL_HANDLER
---

# NET_BUFFER_FREE_MDL_HANDLER callback function


## -description

The 
  <i>NetFreeMdl</i> function frees an MDL that was previously allocated by the 
  <a href="/windows-hardware/drivers/ddi/nblapi/nc-nblapi-net_buffer_allocate_mdl">NetAllocateMdl</a> function.

## -parameters

### -param Mdl [in]


A pointer to the MDL that is to be freed.

## -remarks

If the NDIS driver specifies an entry point for the 
    <i>NetFreeMdl</i> function at the 
    <i>FreeMdl</i> parameter of the 
    <a href="/windows-hardware/drivers/ddi/ndis/nf-ndis-ndisadvancenetbufferdatastart">
    NdisAdvanceNetBufferDataStart</a> function, NDIS calls 
    <i>NetFreeMdl</i> to free an MDL and memory.

<i>NetFreeMdl</i> frees the MDL and memory that were allocated by the 
    <a href="/windows-hardware/drivers/ddi/nblapi/nc-nblapi-net_buffer_allocate_mdl">NetAllocateMdl</a> function.

When 
    <i>NetFreeMdl</i> frees the memory, it should use the same memory management mechanism that was used in 
    <i>NetAllocateMdl</i> to allocate the memory.

NDIS calls 
    <i>NetFreeMdl</i> at IRQL <= DISPATCH_LEVEL.

## -see-also

<a href="/windows-hardware/drivers/ddi/ndis/nf-ndis-ndisadvancenetbufferdatastart">
   NdisAdvanceNetBufferDataStart</a>



<a href="/windows-hardware/drivers/ddi/nblapi/nc-nblapi-net_buffer_allocate_mdl">NetAllocateMdl</a>

