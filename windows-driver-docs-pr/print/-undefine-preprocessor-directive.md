---
title: '#Undefine Preprocessor Directive'
author: windows-driver-content
description: '#Undefine Preprocessor Directive'
ms.assetid: 78f6a895-2c30-4a6f-8916-4c18e22e4e70
keywords:
- preprocessor directives WDK GDL , keywords
- keywords WDK GDL
- reserved keywords WDK
- Undefine directive WDK GDL
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
ms.localizationpriority: medium
---

# \#Undefine Preprocessor Directive


```
#Undefine: symbol
```

The \#Undefine directive removes the *symbol* value from the preprocessor symbol dictionary. If the symbol has been defined multiple times, only the most recent definition of *symbol* is removed.

The *symbol* value is optional. If you omit this value, the most recently defined symbol is removed. However, the delimiting colon (:) is still required.

 

 




