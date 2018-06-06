---
Description: The TakeOwnerShip WMI class method obtains ownership of the logical file specified in the object path.
audience: developer
author: REDMOND\\markl
manager: REDMOND\\markl
ms.assetid: c8fa0706-1f7e-4e68-aea6-694ba24c16c3
ms.prod: windows-server-dev
ms.technology:
- cimwin32
- windows-management-instrumentation
ms.tgt_platform: multiple
title: TakeOwnerShip method of the Win32\_CodecFile class
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# TakeOwnerShip method of the Win32\_CodecFile class

The **TakeOwnerShip** [WMI class](https://msdn.microsoft.com/library/aa393244) method obtains ownership of the logical file specified in the object path. If the logical file is actually a directory, then **TakeOwnerShip** acts recursively, taking ownership of all of the files and subdirectories the directory contains.

This topic uses Managed Object Format (MOF) syntax. For more information about using this method, see [Calling a Method](https://msdn.microsoft.com/library/aa384832).

## Syntax


```mof
uint32 TakeOwnerShip();
```



## Parameters

This method has no parameters.

## Return value

Returns one of the following integer values.

<dl> <dt>

**0**
</dt> <dd>

The request was successful.

</dd> <dt>

**2**
</dt> <dd>

Access was denied.

</dd> <dt>

**8**
</dt> <dd>

An unspecified failure occurred.

</dd> <dt>

**9**
</dt> <dd>

The name specified was not valid.

</dd> <dt>

**10**
</dt> <dd>

The object specified already exists.

</dd> <dt>

**11**
</dt> <dd>

The file system is not NTFS.

</dd> <dt>

**12**
</dt> <dd>

The platform is not Windows.

</dd> <dt>

**13**
</dt> <dd>

The drive is not the same.

</dd> <dt>

**14**
</dt> <dd>

The directory is not empty.

</dd> <dt>

**15**
</dt> <dd>

There has been a sharing violation.

</dd> <dt>

**16**
</dt> <dd>

The start file specified was not valid.

</dd> <dt>

**17**
</dt> <dd>

A privilege required for the operation is not held.

</dd> <dt>

**21**
</dt> <dd>

A parameter specified is not valid.

</dd> </dl>

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

[Operating System Classes](https://msdn.microsoft.com/library/aa392727)
</dt> <dt>

[**Win32\_CodecFile**](win32-codecfile.md)
</dt> </dl>

 

 



