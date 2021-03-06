---
title: 自定义工作流设计体验
ms.date: 03/30/2017
helpviewer_keywords:
- extending [WF], Workflow Designer
ms.assetid: 98135077-0f5d-4d16-9337-01094e843537
ms.openlocfilehash: 3deb29af353752389f77e0971a64dd3d1b4d1273
ms.sourcegitcommit: 3d5d33f384eeba41b2dff79d096f47ccc8d8f03d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/04/2018
---
# <a name="customizing-the-workflow-design-experience"></a>自定义工作流设计体验
在 [!INCLUDE[wfd1](../../../includes/wfd1-md.md)] 中，已经对用于设计自定义活动以及重新承载 [!INCLUDE[netfx40_short](../../../includes/netfx40-short-md.md)] 的方案进行了大量简化。 现在，开发和部署工作变得更轻松、更灵活。 主要的基础更改是由新的活动设计器编程模型构建的 Windows Presentation Foundation (WPF) 时。 这使您能够以声明方式定义活动设计器，并且可以相当轻松地在其他应用程序中重新承载 [!INCLUDE[wfd2](../../../includes/wfd2-md.md)]。 在重新承载时，可以开发自定义表达式编辑器来支持 IntelliSense 或简化的表达式域。 Windows Communication Foundation (WCF) 的集成已变得更加无缝通过使用工作流服务。 可使用自定义活动设计器和模型项树来增强重新承载的工作流设计器中的设计时体验。  
  
## <a name="in-this-section"></a>本节内容  
 [使用自定义活动设计器和模板](../../../docs/framework/windows-workflow-foundation/using-custom-activity-designers-and-templates.md)  
 介绍如何创建新的自定义活动设计器和模板。  
  
 [重新托管工作流设计器](../../../docs/framework/windows-workflow-foundation/rehosting-the-workflow-designer.md)  
 介绍如何重新托管[!INCLUDE[wfd1](../../../includes/wfd1-md.md)]之外 Visual Studio 以及如何显示验证错误。  
  
 [使用自定义表达式编辑器](../../../docs/framework/windows-workflow-foundation/using-a-custom-expression-editor.md)  
 介绍如何实现自定义表达式编辑器以用于在 [!INCLUDE[vs2010](../../../includes/vs2010-md.md)] 外部重新承载的工作流设计器。  
  
## <a name="reference"></a>参考  
 <xref:System.Activities.Presentation.ActivityDesigner>  
  
## <a name="see-also"></a>请参阅  
 [扩展 Windows Workflow Foundation](../../../docs/framework/windows-workflow-foundation/extend.md)  
 [设计器](../../../docs/framework/windows-workflow-foundation/samples/designer.md)  
 [自定义活动设计器](../../../docs/framework/windows-workflow-foundation/samples/custom-activity-designers.md)  
 [重新承载设计器](../../../docs/framework/windows-workflow-foundation/samples/designer-rehosting.md)
