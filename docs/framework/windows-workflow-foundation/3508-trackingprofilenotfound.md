---
title: 3508 - TrackingProfileNotFound
ms.date: 03/30/2017
ms.assetid: 4cee3c4a-0490-4c94-aa19-ef7ce7287c02
ms.openlocfilehash: 94c7ce231df241778f7c6ec5fe5998eae364750d
ms.sourcegitcommit: 3d5d33f384eeba41b2dff79d096f47ccc8d8f03d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/04/2018
---
# <a name="3508---trackingprofilenotfound"></a>3508 - TrackingProfileNotFound
## <a name="properties"></a>属性  
  
|||  
|-|-|  
|ID|3508|  
|关键字|WFServices|  
|级别|详细|  
|通道|Microsoft-Windows-应用程序服务器-应用程序/分析|  
  
## <a name="description"></a>描述  
 指示在配置文件中找不到 TrackingProfile，或 ActivityDefinitionId 与配置文件不匹配。  
  
## <a name="message"></a>消息  
 未找到 ActivityDefinitionId“%2”的 TrackingProfile“%1”。 在配置文件中找不到 TrackingProfile，或 ActivityDefinitionId 不匹配。  
  
## <a name="details"></a>详细信息  
  
|数据项名称|数据项类型|描述|  
|--------------------|--------------------|-----------------|  
|TrackingProfile|xs:string|跟踪配置文件的名称。|  
|ActivityDefinitionId|xs:string|活动定义 ID。|  
|AppDomain|xs:string|由 AppDomain.CurrentDomain.FriendlyName 返回的字符串。|
