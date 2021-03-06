---
title: "IRowsetImpl::m_bCanScrollBack | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: ["cpp-data"]
ms.topic: "reference"
f1_keywords: ["IRowsetImpl::m_bCanScrollBack", "ATL::IRowsetImpl::m_bCanScrollBack", "IRowsetImpl.m_bCanScrollBack", "ATL.IRowsetImpl.m_bCanScrollBack", "m_bCanScrollBack"]
dev_langs: ["C++"]
helpviewer_keywords: ["m_bCanScrollBack"]
ms.assetid: 69de3179-bf56-415e-935f-e98bcb34debe
author: "mikeblome"
ms.author: "mblome"
ms.workload: ["cplusplus", "data-storage"]
---
# IRowsetImpl::m_bCanScrollBack
Indicates whether a provider can have its cursor scroll backwards.  
  
## Syntax  
  
```cpp
unsigned  m_bCanScrollBack:1;  
  
```  
  
## Remarks  
 Linked to the **DBPROP_CANSCROLLBACKWARDS** property in the **DBPROPSET_ROWSET** group. The provider must support **DBPROP_CANSCROLLBACKWARDS** for **m_bCanFetchBackwards** to be true.  
  
## Requirements  
 **Header:** atldb.h  
  
## See Also  
 [IRowsetImpl Class](../../data/oledb/irowsetimpl-class.md)   
 [IRowsetImpl::m_bCanFetchBack](../../data/oledb/irowsetimpl-m-bcanfetchback.md)