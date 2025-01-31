---
UID: NE:d3d12umddi.D3D12DDI_QUERY_TYPE
title: D3D12DDI_QUERY_TYPE (d3d12umddi.h)
description: Type of a query.
old-location: display\d3d12ddi_query_type.htm
ms.date: 05/24/2022
keywords: ["D3D12DDI_QUERY_TYPE enumeration"]
ms.keywords: D3D12DDI_QUERY_TYPE, D3D12DDI_QUERY_TYPE enumeration [Display Devices], D3D12DDI_QUERY_TYPE_0020_VIDEO_DECODE_STATISTICS, D3D12DDI_QUERY_TYPE_BINARY_OCCLUSION, D3D12DDI_QUERY_TYPE_OCCLUSION, D3D12DDI_QUERY_TYPE_PIPELINE_STATISTICS, D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM0, D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM1, D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM2, D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM3, D3D12DDI_QUERY_TYPE_TIMESTAMP, d3d12umddi/D3D12DDI_QUERY_TYPE, d3d12umddi/D3D12DDI_QUERY_TYPE_0020_VIDEO_DECODE_STATISTICS, d3d12umddi/D3D12DDI_QUERY_TYPE_BINARY_OCCLUSION, d3d12umddi/D3D12DDI_QUERY_TYPE_OCCLUSION, d3d12umddi/D3D12DDI_QUERY_TYPE_PIPELINE_STATISTICS, d3d12umddi/D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM0, d3d12umddi/D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM1, d3d12umddi/D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM2, d3d12umddi/D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM3, d3d12umddi/D3D12DDI_QUERY_TYPE_TIMESTAMP, display.d3d12ddi_query_type
req.header: d3d12umddi.h
req.include-header: D3d12umddi.h
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
tech.root: display
req.typenames: D3D12DDI_QUERY_TYPE
f1_keywords:
 - D3D12DDI_QUERY_TYPE
 - d3d12umddi/D3D12DDI_QUERY_TYPE
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - D3d12umddi.h
api_name:
 - D3D12DDI_QUERY_TYPE
---

# D3D12DDI_QUERY_TYPE enumeration

## -description

A **D3D12DDI_QUERY_TYPE** enum value identifies the type of a query.

## -enum-fields

### -field D3D12DDI_QUERY_TYPE_OCCLUSION:0

Occlusion.

### -field D3D12DDI_QUERY_TYPE_BINARY_OCCLUSION:1

Binary occlusion.

### -field D3D12DDI_QUERY_TYPE_TIMESTAMP:2

Timestamp.

### -field D3D12DDI_QUERY_TYPE_PIPELINE_STATISTICS:3

Pipeline statistics.

### -field D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM0:4

SO statistics for Stream0.

### -field D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM1:5

SO statistics for Stream1.

### -field D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM2:6

SO statistics for Stream2.

### -field D3D12DDI_QUERY_TYPE_SO_STATISTICS_STREAM3:7

SO statistics for Stream3.

### -field D3D12DDI_QUERY_TYPE_0020_VIDEO_DECODE_STATISTICS:8

Video decode statistics.

### -field D3D12DDI_QUERY_TYPE_PIPELINE_STATISTICS1:10

[Pipeline statistics](ns-d3d12umddi-d3d12ddi_query_data_pipeline_statistics1.md).

### -field D3D12DDI_QUERY_TYPE_JPEG_DECODE_EVENT:11

For internal use only.

### -field D3D12DDI_QUERY_TYPE_JPEG_ENCODE_STATISTICS:12

For internal use only.

## -remarks

Queries are used to capture information from the GPU, such as statistics and status codes which can later be consumed directly on the GPU or on CPU.

## -see-also

[**pfnBeginEndQuery**](nc-d3d12umddi-pfnd3d12ddi_begin_end_query.md)

[**pfnResolveQueryData**](nc-d3d12umddi-pfnd3d12ddi_resolve_query_data.md)
