---
title: INapComponentInfo GetFriendlyName method (NapCommon.h)
description: Is used by the NAP System to get the friendly name of a health client.
ms.assetid: 28614f06-a250-4f92-abf2-422675efd8a0
keywords:
- GetFriendlyName method NAP
- GetFriendlyName method NAP , INapComponentInfo interface
- INapComponentInfo interface NAP , GetFriendlyName method
topic_type:
- apiref
api_name:
- INapComponentInfo.GetFriendlyName
api_location:
- NapCommon.h
api_type:
- COM
ms.topic: reference
ms.date: 05/31/2018
---

# INapComponentInfo::GetFriendlyName method

> [!Note]  
> The Network Access Protection platform is not available starting with Windows 10

 

The **INapComponentInfo::GetFriendlyName** callback method is used by the NAP System to get the friendly name of a health client.

## Syntax


```C++
HRESULT GetFriendlyName(
  [out] MessageId *friendlyName
);
```



## Parameters

<dl> <dt>

*friendlyName* \[out\]
</dt> <dd>

A pointer to a [**MessageId**](nap-datatypes.md) that contains the resource ID of the friendly name.

</dd> </dl>

## Return value

Return one of these error codes based on the result of this operation.



| Return code                                                                                     | Description                                                        |
|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------|
| <dl> <dt>**S\_OK** </dt> </dl>           | The operation is successful.<br/>                            |
| <dl> <dt>**E\_ACCESSDENIED** </dt> </dl> | Permissions error, access denied.<br/>                       |
| <dl> <dt>**E\_OUTOFMEMORY** </dt> </dl>  | System resource limit, could not perform the operation.<br/> |



 

## Requirements



|                                     |                                                                                          |
|-------------------------------------|------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                           |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps only\]<br/>                                     |
| Header<br/>                   | <dl> <dt>NapCommon.h</dt> </dl>   |
| IDL<br/>                      | <dl> <dt>NapCommon.idl</dt> </dl> |



## See also

<dl> <dt>


</dt> <dt>

[**INapComponentInfo**](inapcomponentinfo.md)
</dt> </dl>

 

 





