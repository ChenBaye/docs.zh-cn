---
title: ICorDebugVariableHome：： GetLocationType 方法
ms.date: 03/30/2017
api_name:
- ICorDebugVariableHome.GetLocationType
api_location:
- mscordbi.dll
api_type:
- COM
f1_keywords:
- ICorDebugVariableHome::GetLocationType
helpviewer_keywords:
- ICorDebugVariableHome::GetLocationType method [.NET Framework debugging]
- GetLocationType method, ICorDebugVariableHome interface [.NET Framework debugging]
ms.assetid: 88027c55-8ec6-4f1e-a55b-7eefdbbc3515
topic_type:
- apiref
ms.openlocfilehash: 8874deede8b46b93df0e298fb3970fa153b51415
ms.sourcegitcommit: 046a9c22487551360e20ec39fc21eef99820a254
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/14/2020
ms.locfileid: "83396564"
---
# <a name="icordebugvariablehomegetlocationtype-method"></a>ICorDebugVariableHome：： GetLocationType 方法
获取变量的本机位置的类型。  
  
## <a name="syntax"></a>语法  
  
```cpp  
HRESULT GetLocationType(  
    [out] VariableLocationType *pLocationType  
);  
```  
  
## <a name="parameters"></a>参数  
 `pLocationType`  
 弄指向变量的本机位置的类型的指针。  有关详细信息，请参阅[VariableLocationType](variablelocationtype-enumeration.md)枚举。  
  
## <a name="requirements"></a>要求  
 **平台：** 请参阅[系统要求](../../get-started/system-requirements.md)。  
  
 **标头**：CorDebug.idl、CorDebug.h  
  
 **库：** CorGuids.lib  
  
 **.NET Framework 版本：**[!INCLUDE[net_current_v462plus](../../../../includes/net-current-v462plus-md.md)]  
  
## <a name="see-also"></a>请参阅

- [ICorDebugVariableHome 接口](icordebugvariablehome-interface.md)
- [VariableLocationType 枚举](variablelocationtype-enumeration.md)
