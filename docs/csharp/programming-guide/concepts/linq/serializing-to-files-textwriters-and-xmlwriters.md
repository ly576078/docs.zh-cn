---
title: 序列化为文件、TextWriter 和 XmlWriter1
ms.date: 07/20/2015
ms.assetid: bd3ea6f7-895b-4ff4-a625-fe2bb55b1886
ms.openlocfilehash: 903e6f5b6a8cd88c140e6759136301a6305cee2d
ms.sourcegitcommit: 3d5d33f384eeba41b2dff79d096f47ccc8d8f03d
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/04/2018
---
# <a name="serializing-to-files-textwriters-and-xmlwriters"></a>序列化为文件、TextWriter 和 XmlWriter
可以将 XML 树序列化为 <xref:System.IO.File>、<xref:System.IO.TextWriter> 或 <xref:System.Xml.XmlWriter>。  
  
 可以使用 <xref:System.Xml.Linq.XDocument> 方法，将任何 XML 组件（包括 <xref:System.Xml.Linq.XElement> 和 `ToString`）序列化为一个字符串。  
  
 在序列化为字符串时，如果要禁止格式化，可以使用 <xref:System.Xml.Linq.XNode.ToString%2A?displayProperty=nameWithType> 方法。  
  
 序列化为文件时，默认行为是格式化（缩进）生成的 XML 文档。 缩进时，不会保留 XML 树中无意义的空白。 若要使用格式化方式进行序列化，请使用不将 <xref:System.Xml.Linq.SaveOptions> 作为参数的以下方法的重载之一：  
  
-   <xref:System.Xml.Linq.XDocument.Save%2A?displayProperty=nameWithType>  
  
-   <xref:System.Xml.Linq.XElement.Save%2A?displayProperty=nameWithType>  
  
 如果要选择不在 XML 树中缩进，并保留无意义空白，请使用将 <xref:System.Xml.Linq.SaveOptions> 作为参数的以下方法的重载之一：  
  
-   <xref:System.Xml.Linq.XDocument.Save%2A?displayProperty=nameWithType>  
  
-   <xref:System.Xml.Linq.XElement.Save%2A?displayProperty=nameWithType>  
  
 有关示例，请参见相应的参考主题。  
  
## <a name="see-also"></a>请参阅  
 [序列化 XML 树 (C#)](../../../../csharp/programming-guide/concepts/linq/serializing-xml-trees.md)
