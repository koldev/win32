---
title: IVMHardDiskConnectionCollection interface
description: Defines the collection of hard disk connections within the virtual machine. To obtain an IVMHardDiskConnectionCollection object, use the IVMVirtualMachine HardDiskConnections property.
ms.assetid: 3440318c-45f4-4d24-9609-dbe5ca59b005
keywords:
- IVMHardDiskConnectionCollection interface Virtual PC
- IVMHardDiskConnectionCollection interface Virtual PC , described
topic_type:
- apiref
api_name:
- IVMHardDiskConnectionCollection
api_location:
- VPCCOMInterfaces.h
api_type:
- COM
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: interface
ms.date: 05/31/2018
---

# IVMHardDiskConnectionCollection interface

\[Windows Virtual PC is no longer available for use as of Windows 8. Instead, use the [Hyper-V WMI provider (V2)](https://msdn.microsoft.com/library/windows/desktop/hh850319).\]

Defines the collection of hard disk connections within the virtual machine. To obtain an **IVMHardDiskConnectionCollection** object, use the [**IVMVirtualMachine::HardDiskConnections**](ivmvirtualmachine-harddiskconnections.md) property.

## Members

The **IVMHardDiskConnectionCollection** interface inherits from the [**IDispatch**](https://msdn.microsoft.com/windows/desktop/ebbff4bc-36b2-4861-9efa-ffa45e013eb5) interface. **IVMHardDiskConnectionCollection** also has these types of members:

-   [Properties](#properties)

### Properties

The **IVMHardDiskConnectionCollection** interface has these properties.



| Property                                                                 | Access type          | Description                                                                         |
|:-------------------------------------------------------------------------|:---------------------|:------------------------------------------------------------------------------------|
| [**\_NewEnum**](ivmharddiskconnectioncollection--newenum.md)<br/> | Read-only<br/> | An enumerator for the collection.<br/>                                        |
| [**Count**](ivmharddiskconnectioncollection-count.md)<br/>        | Read-only<br/> | The number of hard disk connections in this collection.<br/>                  |
| [**Item**](ivmharddiskconnectioncollection-item.md)<br/>          | Read-only<br/> | The hard disk connection object that corresponds to the specified index.<br/> |



 

## Requirements



|                                     |                                                                                                    |
|-------------------------------------|----------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 7 \[desktop apps only\]<br/>                                                         |
| Minimum supported server<br/> | None supported<br/>                                                                          |
| End of client support<br/>    | Windows 7<br/>                                                                               |
| Product<br/>                  | Windows Virtual PC<br/>                                                                      |
| Header<br/>                   | <dl> <dt>VPCCOMInterfaces.h</dt> </dl>      |
| IID<br/>                      | IID\_IVMHardDiskconnectionCollection is defined as b9f2caf4-0aeb-4085-b105-ceddb90dbf62<br/> |



## See also

<dl> <dt>

[**IVMHardDiskConnection**](ivmharddiskconnection.md)
</dt> <dt>

[**IVMVirtualMachine::HardDiskConnections**](ivmvirtualmachine-harddiskconnections.md)
</dt> </dl>

 

 




