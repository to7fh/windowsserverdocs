---
title: Use at least SMB protocol version 3.0 configured for continuous availability on file shares that store files for virtual machines
description: " "
ms.prod: windows-server-threshold
ms.service: na
manager: timlt
ms.technology: 
  - hyper-v
  - techgroup-compute
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: a1fa5cf9-8a48-4f63-bb57-d81e63e77b30
author: KBDAzure
---
# Use at least SMB protocol version 3.0 configured for continuous availability on file shares that store files for virtual machines

>Applies To: Windows Server Technical Preview

[This information is preliminary and subject to change.]  
  
For more information about best practices and scans, see [Run Best Practices Analyzer Scans and Manage Scan Results](http://go.microsoft.com/fwlink/p/?LinkID=223177).  
  
|Property|Details|  
|-|-|  
|**Operating System**|Windows Server 2016 Technical Preview|  
|**Product/Feature**|Hyper-V|  
|**Severity**|Warning|  
|**Category**|Configuration|  
  
In the following sections, italics indicates UI text that appears in the Best Practices Analyzer tool for this issue.  
  
## **Issue**  
*Virtual machine files or virtual hard disk files are stored on a network file share that is not configured with the continuous availability feature of SMB protocol version 3.0.*  
  
## **Impact**  
*Microsoft does not recommend this configuration because it might impact the availability of the virtual machines using the server. This impacts the following virtual machines:*  
  
\<list of virtual machines>  
  
## **Resolution**  
Do one of the following:  
  
-   Move the files to an SMB 3.0 file share that is configured for continuous availability.  
  
-   Reconfigure the current file share to provide continuous availability.  
  

