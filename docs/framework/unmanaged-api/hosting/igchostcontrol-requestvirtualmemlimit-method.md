---
title: "IGCHostControl::RequestVirtualMemLimit 方法"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-clr
ms.tgt_pltfrm: 
ms.topic: reference
api_name: IGCHostControl.RequestVirtualMemLimit
api_location: mscoree.dll
api_type: COM
f1_keywords: RequestVirtualMemLimit
helpviewer_keywords:
- IGCHostControl::RequestVirtualMemLimit method [.NET Framework hosting]
- RequestVirtualMemLimit method [.NET Framework hosting]
ms.assetid: f4984a8c-4c0e-4460-9aa1-d022b3621228
topic_type: apiref
caps.latest.revision: "6"
author: rpetrusha
ms.author: ronpet
manager: wpickett
ms.openlocfilehash: 4892cf5dc3a3663f1bccc95d1975bfe96277faa5
ms.sourcegitcommit: bd1ef61f4bb794b25383d3d72e71041a5ced172e
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2017
---
# <a name="igchostcontrolrequestvirtualmemlimit-method"></a><span data-ttu-id="fe14a-102">IGCHostControl::RequestVirtualMemLimit 方法</span><span class="sxs-lookup"><span data-stu-id="fe14a-102">IGCHostControl::RequestVirtualMemLimit Method</span></span>
<span data-ttu-id="fe14a-103">请求主机后，若要更改的虚拟内存限制。</span><span class="sxs-lookup"><span data-stu-id="fe14a-103">Requests the host to change the limits of virtual memory.</span></span>  
  
## <a name="syntax"></a><span data-ttu-id="fe14a-104">语法</span><span class="sxs-lookup"><span data-stu-id="fe14a-104">Syntax</span></span>  
  
```  
HRESULT RequestVirtualMemLimit (  
    [in] SIZE_T       sztMaxVirtualMemMB,  
    [in, out] SIZE_T* psztNewMaxVirtualMemMB  
);  
```  
  
#### <a name="parameters"></a><span data-ttu-id="fe14a-105">参数</span><span class="sxs-lookup"><span data-stu-id="fe14a-105">Parameters</span></span>  
 `sztMaxVirtualMemMB`  
 <span data-ttu-id="fe14a-106">[in]要分配的内存请求的大小。</span><span class="sxs-lookup"><span data-stu-id="fe14a-106">[in] The requested size of memory to be allocated.</span></span>  
  
 `psztNewMaxVirtualMemMB`  
 <span data-ttu-id="fe14a-107">[在中，out]指向分配的内存的实际大小的指针。</span><span class="sxs-lookup"><span data-stu-id="fe14a-107">[in, out] A pointer to the actual size of memory allocated.</span></span>  
  
## <a name="requirements"></a><span data-ttu-id="fe14a-108">要求</span><span class="sxs-lookup"><span data-stu-id="fe14a-108">Requirements</span></span>  
 <span data-ttu-id="fe14a-109">**平台：**请参阅[系统要求](../../../../docs/framework/get-started/system-requirements.md)。</span><span class="sxs-lookup"><span data-stu-id="fe14a-109">**Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).</span></span>  
  
 <span data-ttu-id="fe14a-110">**标头：** MSCorEE.h</span><span class="sxs-lookup"><span data-stu-id="fe14a-110">**Header:** MSCorEE.h</span></span>  
  
 <span data-ttu-id="fe14a-111">**库：**作为 MSCorEE.dll 中的资源</span><span class="sxs-lookup"><span data-stu-id="fe14a-111">**Library:** Included as a resource in MSCorEE.dll</span></span>  
  
 <span data-ttu-id="fe14a-112">**.NET framework 版本：**[!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]</span><span class="sxs-lookup"><span data-stu-id="fe14a-112">**.NET Framework Versions:** [!INCLUDE[net_current_v20plus](../../../../includes/net-current-v20plus-md.md)]</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="fe14a-113">另请参阅</span><span class="sxs-lookup"><span data-stu-id="fe14a-113">See Also</span></span>  
 [<span data-ttu-id="fe14a-114">IGCHostControl 接口</span><span class="sxs-lookup"><span data-stu-id="fe14a-114">IGCHostControl Interface</span></span>](../../../../docs/framework/unmanaged-api/hosting/igchostcontrol-interface.md)