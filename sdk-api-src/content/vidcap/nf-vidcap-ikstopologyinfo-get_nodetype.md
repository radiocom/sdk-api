---
UID: NF:vidcap.IKsTopologyInfo.get_NodeType
title: IKsTopologyInfo::get_NodeType (vidcap.h)
description: The get_NodeType method returns the node type for a given node.
helpviewer_keywords: ["IKsTopologyInfo interface [DirectShow]","get_NodeType method","IKsTopologyInfo.get_NodeType","IKsTopologyInfo::get_NodeType","IKsTopologyInfoget_NodeType","dshow.ikstopologyinfo_get_nodetype","get_NodeType","get_NodeType method [DirectShow]","get_NodeType method [DirectShow]","IKsTopologyInfo interface","vidcap/IKsTopologyInfo::get_NodeType"]
old-location: dshow\ikstopologyinfo_get_nodetype.htm
tech.root: dshow
ms.assetid: 6606d563-6a35-4595-8bb2-6cf74f7af4e7
ms.date: 4/26/2023
ms.keywords: IKsTopologyInfo interface [DirectShow],get_NodeType method, IKsTopologyInfo.get_NodeType, IKsTopologyInfo::get_NodeType, IKsTopologyInfoget_NodeType, dshow.ikstopologyinfo_get_nodetype, get_NodeType, get_NodeType method [DirectShow], get_NodeType method [DirectShow],IKsTopologyInfo interface, vidcap/IKsTopologyInfo::get_NodeType
req.header: vidcap.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 R2 [desktop apps only]
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
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IKsTopologyInfo::get_NodeType
 - vidcap/IKsTopologyInfo::get_NodeType
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Vidcap.h
api_name:
 - IKsTopologyInfo.get_NodeType
---

# IKsTopologyInfo::get_NodeType


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer), [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine), and [Audio/Video Capture in Media Foundation](/windows/win32/medfound/audio-video-capture-in-media-foundation). Those features have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer**, **IMFMediaEngine** and **Audio/Video Capture in Media Foundation** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>get_NodeType</code> method returns the node type for a given node.

## -parameters

### -param dwNodeId [in]

Index of the node. To find the number of nodes, call the <a href="/windows/desktop/api/vidcap/nf-vidcap-ikstopologyinfo-get_numnodes">IKsTopologyInfo::get_NumNodes</a> method.

### -param pNodeType [out]

Receives a GUID that defines the node type. For a list of node types, see <a href="/windows/desktop/DirectShow/ks-node-types">KS Node Types</a>.

## -returns

The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
</table>

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/previous-versions/ms785846(v=vs.85)">IKsTopologyInfo Interface</a>