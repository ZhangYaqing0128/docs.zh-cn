---
title: 如何：将控件添加到选项卡页
ms.date: 03/30/2017
dev_langs:
- csharp
- vb
- cpp
helpviewer_keywords:
- TabPage control
- tab controls [Windows Forms], tab order
- tab pages [Windows Forms], adding controls
ms.assetid: b092532e-7346-469f-b9a1-897f9bea4fb7
ms.openlocfilehash: 1bb2233cf9e288ae89ebb8cab3df4f6451dc8eed
ms.sourcegitcommit: 3d5d33f384eeba41b2dff79d096f47ccc8d8f03d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/04/2018
ms.locfileid: "33526691"
---
# <a name="how-to-add-a-control-to-a-tab-page"></a>如何：将控件添加到选项卡页
你可以使用 Windows 窗体<xref:System.Windows.Forms.TabControl>若要在以组织方式中显示其他控件。 以下过程说明如何将按钮添加到第一个选项卡。有关将图标添加到选项卡页的标签部分的信息，请参阅[如何： 更改 Windows 窗体 TabControl 的外观](../../../../docs/framework/winforms/controls/how-to-change-the-appearance-of-the-windows-forms-tabcontrol.md)。  
  
### <a name="to-add-a-control-programmatically"></a>以编程方式添加控件  
  
1.  使用<xref:System.Windows.Forms.Control.ControlCollection.Add%2A>方法返回的集合<xref:System.Windows.Forms.Control.Controls%2A>属性<xref:System.Windows.Forms.TabPage>:  
  
     [!code-cpp[TabPageControlCollectionHowToAdd#1](../../../../samples/snippets/cpp/VS_Snippets_Winforms/tabpagecontrolcollectionhowtoadd/cpp/add.cpp#1)]
     [!code-csharp[TabPageControlCollectionHowToAdd#1](../../../../samples/snippets/csharp/VS_Snippets_Winforms/tabpagecontrolcollectionhowtoadd/cs/add.cs#1)]
     [!code-vb[TabPageControlCollectionHowToAdd#1](../../../../samples/snippets/visualbasic/VS_Snippets_Winforms/tabpagecontrolcollectionhowtoadd/vb/add.vb#1)]  
  
## <a name="see-also"></a>请参阅  
 [TabControl 控件](../../../../docs/framework/winforms/controls/tabcontrol-control-windows-forms.md)  
 [TabControl 控件概述](../../../../docs/framework/winforms/controls/tabcontrol-control-overview-windows-forms.md)  
 [如何：更改 Windows 窗体 TabControl 控件的外观](../../../../docs/framework/winforms/controls/how-to-change-the-appearance-of-the-windows-forms-tabcontrol.md)  
 [如何：禁用选项卡页](../../../../docs/framework/winforms/controls/how-to-disable-tab-pages.md)  
 [如何：使用 Windows 窗体 TabControl 控件添加和删除选项卡](../../../../docs/framework/winforms/controls/how-to-add-and-remove-tabs-with-the-windows-forms-tabcontrol.md)
