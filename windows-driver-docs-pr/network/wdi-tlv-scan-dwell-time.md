---
title: WDI_TLV_SCAN_DWELL_TIME
author: windows-driver-content
description: WDI_TLV_SCAN_DWELL_TIME is a TLV that contains scanning dwell time settings.
ms.assetid: A0C597E7-879C-43CC-BB86-4908AC31828F
ms.author: windowsdriverdev 
ms.date: 07/18/2017 
ms.topic: article 
ms.prod: windows-hardware 
ms.technology: windows-devices 
keywords:
 - WDI_TLV_SCAN_DWELL_TIME Network Drivers Starting with Windows Vista
---

# WDI\_TLV\_SCAN\_DWELL\_TIME


WDI\_TLV\_SCAN\_DWELL\_TIME is a TLV that contains scanning dwell time settings.

## TLV Type


0x7

## Length


The sum (in bytes) of the sizes of all contained elements.

## Values


| Type   | Description                                                                                                                                                                           |
|--------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| UINT32 | Specifies the time in milliseconds to dwell on active channels. This is a hint and if the adapter decides to use its own dwell time, it must meet the Maximum Scan Time requirement.  |
| UINT32 | Specifies the time in milliseconds to dwell on passive channels. This is a hint and if the adapter decides to use its own dwell time, it must meet the Maximum Scan Time requirement. |
| UINT32 | Specifies the time in milliseconds for total scan. If the adapter limits its dwell times to below the values specified above, it can ignore the Maximum Scan Time parameter.          |

 

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Minimum supported client</p></td>
<td><p>Windows 10</p></td>
</tr>
<tr class="even">
<td><p>Minimum supported server</p></td>
<td><p>Windows Server 2016</p></td>
</tr>
<tr class="odd">
<td><p>Header</p></td>
<td>Wditypes.hpp</td>
</tr>
</tbody>
</table>

 

 


--------------------
[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bnetvista\netvista%5D:%20WDI_TLV_SCAN_DWELL_TIME%20%20RELEASE:%20%287/10/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")


