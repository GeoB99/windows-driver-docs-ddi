---
UID: NI:ntddsysenv.IOCTL_SYSENV_QUERY_VARIABLE_INFO
title: IOCTL_SYSENV_QUERY_VARIABLE_INFO (ntddsysenv.h)
description: IOCTL_SYSENV_QUERY_VARIABLE_INFO returns information about system environment variables using SysEnv device.
old-location: kernel\ioctl_ioctl_sysenv_query_variable_info.htm
tech.root: kernel
ms.date: 04/30/2018
keywords: ["IOCTL_SYSENV_QUERY_VARIABLE_INFO IOCTL"]
ms.keywords: IOCTL_SYSENV_QUERY_VARIABLE_INFO, IOCTL_SYSENV_QUERY_VARIABLE_INFO control, IOCTL_SYSENV_QUERY_VARIABLE_INFO control code [Kernel-Mode Driver Architecture], kernel.ioctl_ioctl_sysenv_query_variable_info, ntddsysenv/IOCTL_SYSENV_QUERY_VARIABLE_INFO
req.header: ntddsysenv.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
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
req.typenames: 
f1_keywords:
 - IOCTL_SYSENV_QUERY_VARIABLE_INFO
 - ntddsysenv/IOCTL_SYSENV_QUERY_VARIABLE_INFO
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - Ntddsysenv.h
api_name:
 - IOCTL_SYSENV_QUERY_VARIABLE_INFO
---

# IOCTL_SYSENV_QUERY_VARIABLE_INFO IOCTL


## -description

Returns information about system environment variables using
    SysEnv device.

## -ioctlparameters

### -input-buffer

A pointer to a ULONG variable that contains the attributes of the system environment variable.

### -input-buffer-length

Size of ULONG.

### -output-buffer

A pointer to a <a href="/windows-hardware/drivers/ddi/ntddsysenv/ns-ntddsysenv-_sysenv_variable_info">SYSENV_VARIABLE_INFO</a> structure that contains variable information.

### -output-buffer-length

The size of the <a href="/windows-hardware/drivers/ddi/ntddsysenv/ns-ntddsysenv-_sysenv_variable_info">SYSENV_VARIABLE_INFO</a> structure.

### -in-out-buffer

### -inout-buffer-length

### -status-block

<b>Irp->IoStatus.Status</b> is set to STATUS_SUCCESS if the request is successful. Otherwise, <b>Status</b> to the appropriate error condition as a <a href="/windows-hardware/drivers/kernel/ntstatus-values">NTSTATUS</a> code.

## -see-also

<a href="/windows-hardware/drivers/kernel/creating-ioctl-requests-in-drivers">Creating IOCTL Requests in Drivers</a>



<a href="/windows-hardware/drivers/ddi/wdfiotarget/nf-wdfiotarget-wdfiotargetsendinternalioctlotherssynchronously">WdfIoTargetSendInternalIoctlOthersSynchronously</a>



<a href="/windows-hardware/drivers/ddi/wdfiotarget/nf-wdfiotarget-wdfiotargetsendinternalioctlsynchronously">WdfIoTargetSendInternalIoctlSynchronously</a>



<a href="/windows-hardware/drivers/ddi/wdfiotarget/nf-wdfiotarget-wdfiotargetsendioctlsynchronously">WdfIoTargetSendIoctlSynchronously</a>
