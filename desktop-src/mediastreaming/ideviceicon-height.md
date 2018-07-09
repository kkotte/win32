---
title: IDeviceIcon Height method
description: Retrieves the height of the icon in pixels.
ms.assetid: 06E1B3AD-FF49-4BC9-AC67-E2E00954475F
keywords:
- Height method Media Streaming API
- Height method Media Streaming API , IDeviceIcon interface
- IDeviceIcon interface Media Streaming API , Height method
topic_type:
- apiref
api_name:
- IDeviceIcon.Height
api_type:
- COM
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
api_location: 
---

# IDeviceIcon::Height method

Retrieves the height of the icon in pixels.

## Syntax


```C++
HRESULT Height(
  [out] UINT32 *value
);
```



## Parameters

<dl> <dt>

*value* \[out\]
</dt> <dd>

Receives a pointer to the height of the icon in pixels.

</dd> </dl>

## Return value

The method returns an **HRESULT**. Possible values include, but are not limited to, those in the following table.



| Return code                                                                          | Description                      |
|--------------------------------------------------------------------------------------|----------------------------------|
| <dl> <dt>**S\_OK**</dt> </dl> | The method succeeded.<br/> |



 

## See also

<dl> <dt>

[**IDeviceIcon**](https://msdn.microsoft.com/en-us/library/Hh828909(v=VS.85).aspx)
</dt> </dl>

 

 




