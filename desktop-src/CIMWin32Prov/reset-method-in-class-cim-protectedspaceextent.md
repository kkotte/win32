---
Description: The Reset method of the CIM\_ProtectedSpaceExtent class requests a reset of the logical device.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\markl
ms.assetid: 601e6b0d-4f3c-4a99-aec1-1a769213cf6e
ms.prod: windows-server-dev
ms.technology:
- cimwin32
- windows-management-instrumentation
ms.tgt_platform: multiple
title: Reset method of the CIM\_ProtectedSpaceExtent class
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- CIM_ProtectedSpaceExtent.Reset
api_type: 
- COM
api_location: 
- CIMWin32.dll
---

# Reset method of the CIM\_ProtectedSpaceExtent class

The **Reset** method of the CIM\_ProtectedSpaceExtent class requests a reset of the logical device. This method is inherited from [**CIM\_LogicalDevice**](cim-logicaldevice.md).

> \[!Important\]  
> The DMTF (Distributed Management Task Force) CIM (Common Information Model) classes are the parent classes upon which WMI classes are built. WMI currently supports only the [CIM 2.x version schemas](Http://Go.Microsoft.Com/FWLink/p/?LinkID=309367).

 

## Syntax


```mof
uint32 Reset();
```



## Parameters

This method has no parameters.

## Return value

Returns 0 (zero) if the request was successfully executed, 1 (one) if the request is not supported, and some other value if an error occurred.

## Remarks

This method is currently not implemented by WMI. To use this method, you must implement it in your own provider.

This documentation is derived from the CIM class descriptions published by the DMTF. Microsoft may have made changes to correct minor errors, conform to Microsoft SDK documentation standards, or provide more information.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista<br/>                                                                |
| Minimum supported server<br/> | Windows Server 2008<br/>                                                          |
| Namespace<br/>                | Root\\CIMV2<br/>                                                                  |
| MOF<br/>                      | <dl> <dt>CIMWin32.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>CIMWin32.dll</dt> </dl> |



## See also

<dl> <dt>

[CIM\_ProtectedSpaceExtent](reset-method-in-class-cim-protectedspaceextent.md)
</dt> <dt>

[**CIM\_ProtectedSpaceExtent**](cim-protectedspaceextent.md)
</dt> </dl>

 

 



