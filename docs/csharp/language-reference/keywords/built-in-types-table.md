---
title: 内置类型表（C# 参考）
ms.date: 07/20/2015
helpviewer_keywords:
- types [C#], built-in
- built-in C# types
ms.assetid: 54f901f2-bf2f-472c-ae8d-73e8ecfc57fe
ms.openlocfilehash: 7407d18c58dd3d12337c6845627d83f02eaf7fa0
ms.sourcegitcommit: 3d5d33f384eeba41b2dff79d096f47ccc8d8f03d
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/04/2018
---
# <a name="built-in-types-table-c-reference"></a>内置类型表（C# 参考）
下表显示内置 C# 类型的关键字，即 <xref:System> 命名空间中预定义类型的别名。  
  
|C# 类型|.NET Framework 类型|  
|--------------|-------------------------|  
|[bool](../../../csharp/language-reference/keywords/bool.md)|`System.Boolean`|  
|[byte](../../../csharp/language-reference/keywords/byte.md)|`System.Byte`|  
|[sbyte](../../../csharp/language-reference/keywords/sbyte.md)|`System.SByte`|  
|[char](../../../csharp/language-reference/keywords/char.md)|`System.Char`|  
|[decimal](../../../csharp/language-reference/keywords/decimal.md)|`System.Decimal`|  
|[double](../../../csharp/language-reference/keywords/double.md)|`System.Double`|  
|[float](../../../csharp/language-reference/keywords/float.md)|`System.Single`|  
|[int](../../../csharp/language-reference/keywords/int.md)|`System.Int32`|  
|[uint](../../../csharp/language-reference/keywords/uint.md)|`System.UInt32`|  
|[long](../../../csharp/language-reference/keywords/long.md)|`System.Int64`|  
|[ulong](../../../csharp/language-reference/keywords/ulong.md)|`System.UInt64`|  
|[object](../../../csharp/language-reference/keywords/object.md)|`System.Object`|  
|[short](../../../csharp/language-reference/keywords/short.md)|`System.Int16`|  
|[ushort](../../../csharp/language-reference/keywords/ushort.md)|`System.UInt16`|  
|[string](../../../csharp/language-reference/keywords/string.md)|`System.String`|  
  
## <a name="remarks"></a>备注  
 此表中的所有类型，除 `object` 和 `string` 外，皆被称为简单类型。  
  
 C# 类型关键字及其别名可互换。 例如，可通过使用以下任意一个声明来声明整型变量：  
  
```  
int x = 123;  
System.Int32 x = 123;  
```  
  
 要显示任何 C# 类型的实际类型，请使用系统方法 `GetType()`。 例如，如下语句显示表示 `myVariable` 类型的系统别名：  
  
```  
Console.WriteLine(myVariable.GetType());  
```  
  
 也可使用 [typeof](../../../csharp/language-reference/keywords/typeof.md) 运算符。  
  
## <a name="see-also"></a>请参阅  
 [C# 参考](../../../csharp/language-reference/index.md)  
 [C# 编程指南](../../../csharp/programming-guide/index.md)  
 [C# 关键字](../../../csharp/language-reference/keywords/index.md)  
 [值类型](../../../csharp/language-reference/keywords/value-types.md)  
 [默认值表](../../../csharp/language-reference/keywords/default-values-table.md)  
 [设置数值结果表的格式](../../../csharp/language-reference/keywords/formatting-numeric-results-table.md)  
 [dynamic](../../../csharp/language-reference/keywords/dynamic.md)  
 [类型参考表](../../../csharp/language-reference/keywords/reference-tables-for-types.md)
