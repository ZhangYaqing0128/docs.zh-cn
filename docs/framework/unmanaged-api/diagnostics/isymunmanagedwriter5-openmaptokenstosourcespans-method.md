---
title: "ISymUnmanagedWriter5::OpenMapTokensToSourceSpans 方法"
ms.custom: 
ms.date: 03/30/2017
ms.prod: .net-framework
ms.reviewer: 
ms.suite: 
ms.technology: dotnet-clr
ms.tgt_pltfrm: 
ms.topic: reference
ms.assetid: 93ad2517-b0dc-464c-8688-a58a30eda18d
caps.latest.revision: "4"
author: rpetrusha
ms.author: ronpet
manager: wpickett
ms.openlocfilehash: f226a71ac6381c8ca04093beb1d9772d6e6c75e3
ms.sourcegitcommit: bd1ef61f4bb794b25383d3d72e71041a5ced172e
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/18/2017
---
# <a name="isymunmanagedwriter5openmaptokenstosourcespans-method"></a><span data-ttu-id="f75f3-102">ISymUnmanagedWriter5::OpenMapTokensToSourceSpans 方法</span><span class="sxs-lookup"><span data-stu-id="f75f3-102">ISymUnmanagedWriter5::OpenMapTokensToSourceSpans Method</span></span>
<span data-ttu-id="f75f3-103">打开一个特殊的自定义数据部分，以便发出令牌源范围映射到的信息。</span><span class="sxs-lookup"><span data-stu-id="f75f3-103">Open a special custom data section to emit token-to-source span mapping information into.</span></span> <span data-ttu-id="f75f3-104">方法已打开，或反之，是一个错误时，请打开此部分。</span><span class="sxs-lookup"><span data-stu-id="f75f3-104">Opening this section when a method is already open, or vice versa, is an error.</span></span>  
  
## <a name="syntax"></a><span data-ttu-id="f75f3-105">语法</span><span class="sxs-lookup"><span data-stu-id="f75f3-105">Syntax</span></span>  
  
```idl  
HRESULT OpenMapTokensToSourceSpans();  
```  
  
## <a name="return-value"></a><span data-ttu-id="f75f3-106">返回值</span><span class="sxs-lookup"><span data-stu-id="f75f3-106">Return Value</span></span>  
 <span data-ttu-id="f75f3-107">返回 `HRESULT`。</span><span class="sxs-lookup"><span data-stu-id="f75f3-107">Returns `HRESULT`.</span></span>  
  
## <a name="requirements"></a><span data-ttu-id="f75f3-108">要求</span><span class="sxs-lookup"><span data-stu-id="f75f3-108">Requirements</span></span>  
 <span data-ttu-id="f75f3-109">**标头：** CorSym.idl、 CorSym.h</span><span class="sxs-lookup"><span data-stu-id="f75f3-109">**Header:** CorSym.idl, CorSym.h</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="f75f3-110">另请参阅</span><span class="sxs-lookup"><span data-stu-id="f75f3-110">See Also</span></span>  
 [<span data-ttu-id="f75f3-111">ISymUnmanagedWriter5 接口</span><span class="sxs-lookup"><span data-stu-id="f75f3-111">ISymUnmanagedWriter5 Interface</span></span>](../../../../docs/framework/unmanaged-api/diagnostics/isymunmanagedwriter5-interface.md)