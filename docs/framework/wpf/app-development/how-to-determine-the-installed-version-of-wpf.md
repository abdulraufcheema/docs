---
title: Determine Installed Version of WPF
titleSuffix: ""
ms.date: "03/30/2017"
helpviewer_keywords: 
  - "version [WPF], finding"
ms.assetid: 99971cef-e218-4f9f-a4c1-350332741860
---
# How to: Determine the Installed Version of WPF
The version number for the current installed version of [!INCLUDE[TLA#tla_winclient](../../../../includes/tlasharptla-winclient-md.md)] is located in the **Registry**.  
  
 To find the version number:  
  
1. On the **Start** menu, click **Run**.  
  
2. In **Open**, type **regedit.exe**.  
  
3. Open the following key:  
  
 `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\NET Framework Setup\NDP\v3.0\Setup\Windows Presentation Foundation`  
  
 The [!INCLUDE[TLA2#tla_winclient](../../../../includes/tla2sharptla-winclient-md.md)] version number is stored in the **Version** value.
