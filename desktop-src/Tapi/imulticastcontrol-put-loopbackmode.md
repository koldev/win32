---
Description: The put\_LoopbackMode sets the multicast loopback mode.
ms.assetid: 38b28529-224f-4624-bb5e-22fee500e8e6
title: IMulticastControl::put\_LoopbackMode method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# IMulticastControl::put\_LoopbackMode method

\[**put\_LoopbackMode** is not available for use in Windows Vista, Windows Server 2008, and subsequent versions of the operating system. The RTC Client API provides similar functionality.\]

The **put\_LoopbackMode** sets the multicast loopback mode.

## Syntax


```C++
);
```



## Parameters

<dl> <dt>

*mode* \[in\]
</dt> <dd>

[**MULTICAST\_LOOPBACK\_MODE**](multicast-loopback-mode.md) descriptor of the new loopback mode.

</dd> </dl>

## Return value

This method can return one of these values.



| Return code                                                                                  | Description                                   |
|----------------------------------------------------------------------------------------------|-----------------------------------------------|
| <dl> <dt>**S\_OK**</dt> </dl>         | Method succeeded.<br/>                  |
| <dl> <dt>**E\_INVALIDARG**</dt> </dl> | The *mode* parameter is not valid.<br/> |



 

## Requirements



|                         |                                                                                       |
|-------------------------|---------------------------------------------------------------------------------------|
| TAPI version<br/> | Requires TAPI 3.0 or later<br/>                                                 |
| Header<br/>       | <dl> <dt>Confpriv.h</dt> </dl> |
| Library<br/>      | <dl> <dt>Uuid.lib</dt> </dl>   |
| DLL<br/>          | <dl> <dt>Tapi3.dll</dt> </dl>  |



## See also

<dl> <dt>

[**IMulticastControl**](imulticastcontrol.md)
</dt> </dl>

 

 



