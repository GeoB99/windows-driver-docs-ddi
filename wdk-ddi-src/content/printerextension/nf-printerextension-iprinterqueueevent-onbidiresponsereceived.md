---
UID: NF:printerextension.IPrinterQueueEvent.OnBidiResponseReceived
title: IPrinterQueueEvent::OnBidiResponseReceived (printerextension.h)
description: Called when a bidi response is received.
old-location: print\iprinterqueueevent_onbidiresponsereceived.htm
tech.root: print
ms.date: 04/20/2018
keywords: ["IPrinterQueueEvent::OnBidiResponseReceived"]
ms.keywords: IPrinterQueueEvent interface [Print Devices],OnBidiResponseReceived method, IPrinterQueueEvent.OnBidiResponseReceived, IPrinterQueueEvent::OnBidiResponseReceived, OnBidiResponseReceived, OnBidiResponseReceived method [Print Devices], OnBidiResponseReceived method [Print Devices],IPrinterQueueEvent interface, print.iprinterqueueevent_onbidiresponsereceived, printerextension/IPrinterQueueEvent::OnBidiResponseReceived
req.header: printerextension.h
req.include-header: 
req.target-type: Desktop
req.target-min-winverclnt: Windows 8
req.target-min-winversvr: Windows Server 2012
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
req.typenames: 
f1_keywords:
 - IPrinterQueueEvent::OnBidiResponseReceived
 - printerextension/IPrinterQueueEvent::OnBidiResponseReceived
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Printerextension.h
api_name:
 - IPrinterQueueEvent::OnBidiResponseReceived
---

# IPrinterQueueEvent::OnBidiResponseReceived


## -description

Called when a bidi response  is received.

## -parameters

### -param bstrResponse [in]


The received response.

### -param hrStatus [in]


An HRESULT value.

## -returns

This method returns an <b>HRESULT</b> value.

## -remarks

The <i>bstrResponse</i> parameter is formatted according to the schema that is described in <a href="/previous-versions/dd183368(v=vs.85)">Bidi Request and Response Schemas</a>.

## -see-also

<a href="/previous-versions/dd183368(v=vs.85)">Bidi Request and Response Schemas</a>



<a href="/windows-hardware/drivers/ddi/printerextension/nn-printerextension-iprinterqueue">IPrinterQueue</a>



<a href="/windows-hardware/drivers/ddi/printerextension/nf-printerextension-iprinterqueue-sendbidiquery">IPrinterQueue::SendBidiQuery</a>



<a href="/windows-hardware/drivers/ddi/printerextension/nn-printerextension-iprinterqueueevent">IPrinterQueueEvent</a>

