---
title: 如何：确定安装的 WPF 的版本
ms.date: 03/30/2017
helpviewer_keywords:
- version [WPF], finding
ms.assetid: 99971cef-e218-4f9f-a4c1-350332741860
ms.openlocfilehash: c59fa0d0a4d94c6e6a2ab72a4cd7a3c066649fb8
ms.sourcegitcommit: 3d5d33f384eeba41b2dff79d096f47ccc8d8f03d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/04/2018
---
# <a name="how-to-determine-the-installed-version-of-wpf"></a>如何：确定安装的 WPF 的版本
当前安装的版本的版本号[!INCLUDE[TLA#tla_winclient](../../../../includes/tlasharptla-winclient-md.md)]位于**注册表**。  
  
 若要查找的版本号：  
  
1.  在“开始”  菜单上，单击“运行” 。  
  
2.  在**打开**，类型**regedit.exe**。  
  
3.  打开以下项：  
  
 `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\NET Framework Setup\NDP\v3.0\Setup\Windows Presentation Foundation`  
  
 [!INCLUDE[TLA2#tla_winclient](../../../../includes/tla2sharptla-winclient-md.md)]版本号存储在**版本**值。
