---
title: C Runtime Error R6018 | Microsoft Docs
ms.custom: 
ms.date: 11/04/2016
ms.reviewer: 
ms.suite: 
ms.technology:
- devlang-cpp
ms.tgt_pltfrm: 
ms.topic: error-reference
f1_keywords:
- R6018
dev_langs:
- C++
helpviewer_keywords:
- R6018
ms.assetid: f6dd40d1-a119-4d8b-b39e-97350ea23349
caps.latest.revision: 7
author: corob-msft
ms.author: corob
manager: ghogen
translation.priority.ht:
- de-de
- es-es
- fr-fr
- it-it
- ja-jp
- ko-kr
- ru-ru
- zh-cn
- zh-tw
translation.priority.mt:
- cs-cz
- pl-pl
- pt-br
- tr-tr
translationtype: Machine Translation
ms.sourcegitcommit: 6cad5222fb0d97594d5b13b5cf8903eb2934ee88
ms.openlocfilehash: 07aa2d06b990f0eed1f089b677e55c4d2e78a01e

---
# C Runtime Error R6018
unexpected heap error  
  
> [!NOTE]
>  If you encounter this error message while running an app, the app was shut down because it has an internal problem. There are several possible reasons for this error, but often it's caused by a defect in the app's code.  
>   
>  You can try these steps to fix this error:  
>   
>  -   Use the **Apps and Features** or **Programs and Features** page in the **Control Panel** to repair or reinstall the program.  
> -   Check **Windows Update** in the **Control Panel** for software updates.  
> -   Check for an updated version of the app. Contact the app vendor if the problem persists.  
  
 **Information for Programmers**  
  
 The program encountered an unexpected error while performing a memory-management operation.  
  
 This error usually occurs if the program inadvertently alters the run-time heap data. However, it can also be caused by an internal error in the runtime or operating-system code.  
  
 To fix this issue, check for heap corruption bugs in your code. For more information and examples, see [CRT Debug Heap Details](/visualstudio/debugger/crt-debug-heap-details). Next, check that you are using the latest redistributables for your app deployment. For information, see [Deployment in Visual C++](../../ide/deployment-in-visual-cpp.md).


<!--HONumber=Jan17_HO2-->

