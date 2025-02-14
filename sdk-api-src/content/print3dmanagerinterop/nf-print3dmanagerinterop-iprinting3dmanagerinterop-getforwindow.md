---
UID: NF:print3dmanagerinterop.IPrinting3DManagerInterop.GetForWindow
tech.root: winrt
title: IPrinting3DManagerInterop::GetForWindow
ms.date: 04/16/2021
targetos: Windows
description: Gets an [Print3DManager](/uwp/api/windows.graphics.printing3d.print3dmanager) object for the window of the active application.
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: print3dmanagerinterop.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - COM
api_location:
 - print3dmanagerinterop.h
api_name:
 - IPrinting3DManagerInterop::GetForWindow
f1_keywords:
 - IPrinting3DManagerInterop::GetForWindow
 - print3dmanagerinterop/IPrinting3DManagerInterop::GetForWindow
dev_langs:
 - c++
---

## -description

Gets an [Print3DManager](/uwp/api/windows.graphics.printing3d.print3dmanager) object for the window of the active application.

## -parameters

### -param appWindow

Handle to the window of the active application.

### -param riid

The GUID for the resource interface.

The REFIID, or GUID, of the interface to the resource can be obtained by using the __uuidof() macro. For example: 

`__uuidof(Print3DManager)` 

### -param printManager

Address of a pointer to a [Print3DManager](/uwp/api/windows.graphics.printing3d.print3dmanager) object.


## -returns

If this function succeeds, it returns S_OK. Otherwise, it returns an HRESULT error code.


## -remarks

## -see-also

[Print3DManager](/uwp/api/windows.graphics.printing3d.print3dmanager)

