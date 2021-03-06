---
title: 用 COM 互操作对数据进行封送处理
ms.date: 09/07/2017
helpviewer_keywords:
- COM interop, data marshaling
- marshaling data, COM interop
author: rpetrusha
ms.author: ronpet
ms.openlocfilehash: d0d94223223568efe921af3a340815a966cc6c6f
ms.sourcegitcommit: 3d5d33f384eeba41b2dff79d096f47ccc8d8f03d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/04/2018
---
# <a name="marshaling-data-with-com-interop"></a>用 COM 互操作对数据进行封送处理
COM 互操作同时对在托管代码中使用 COM 对象和向 COM 公开托管对象提供支持。 对于将数据封送到 COM 和从 COM 中封送数据的支持是广泛的，并几乎总是提供正确的封送行为。  
  
 [!INCLUDE[winsdklong](../../../includes/winsdklong-md.md)] 包括以下 COM 互操作工具：  
  
-   [类型库导入程序 (Tlbimp.exe)](../../../docs/framework/tools/tlbimp-exe-type-library-importer.md)，它将 COM 类型库转换为互操作程序集。 从该程序集中，互操作封送处理服务生成包装器，该包装器在托管内存和非托管内存之间执行数据封送。  
  
-   [类型库导出程序 (Tlbexp.exe)](../../../docs/framework/tools/tlbexp-exe-type-library-exporter.md)，它从程序集产生 COM 类型库，并生成在方法调用期间执行封送的包装器。  
  
 下列各节将介绍能够 （或必须） 为封送处理程序提供附加类型信息时自定义互操作包装器的进程的主题的链接。  
  
## <a name="in-this-section"></a>本节内容  
[如何： 手动创建包装器](how-to-create-wrappers-manually.md)   
描述如何在托管的源代码中手动创建 COM 包装器。 
 
 [如何：将托管代码 DCOM 迁移到 WCF](../../../docs/framework/interop/how-to-migrate-managed-code-dcom-to-wcf.md)  
 描述如何将托管的 DCOM 代码迁移到 WCF，最安全的解决方案。  
  
## <a name="related-sections"></a>相关章节  
 [COM 数据类型](https://msdn.microsoft.com/library/sak564ww(v=vs.100).aspx)  
 提供相应的托管和非托管数据类型。  
  
 [自定义 COM 可调用包装器](https://msdn.microsoft.com/library/3bwc828w(v=vs.100).aspx)  
 描述如何显式封送数据类型使用<xref:System.Runtime.InteropServices.MarshalAsAttribute>在设计时属性。  
  
 [自定义运行时可调用包装器](https://msdn.microsoft.com/library/e753eftz(v=vs.100).aspx)  
 描述如何调整互操作程序集中类型的封送行为以及如何以手动方式定义 COM 类型。  
  
 [高级 COM 互操作性](https://msdn.microsoft.com/library/bd9cdfyx(v=vs.100).aspx)  
 提供一些链接，指向关于将 COM 组件并入 .NET Framework 应用程序中的详细信息。  
  
 [有关从程序集转换到类型库的摘要](https://msdn.microsoft.com/library/xk1120c3(v=vs.100).aspx)  
 描述从程序集到类型库的导出转换过程。  
  
 [有关从类型库转换到程序集的摘要](https://msdn.microsoft.com/library/k83zzh38(v=vs.100).aspx)  
 描述从类型库到程序集的导入转换过程。  
  
 [使用泛型类型进行交互操作](https://msdn.microsoft.com/library/ms229590(v=vs.100).aspx)  
 描述在使用用于 COM 互操作性的泛型类型时，哪些操作受支持。
