---
title: "Run the Data Quality Client Application"
description: "Run the Data Quality Client Application"
author: swinarko
ms.author: sawinark
ms.date: "03/01/2017"
ms.service: sql
ms.subservice: data-quality-services
ms.topic: conceptual
f1_keywords:
  - "sql13.dqs.browseforservers.f1"
  - "sql13.dqs.connecttoserver.f1"
---
# Run the Data Quality Client Application

[!INCLUDE [SQL Server - Windows only ASDBMI](../includes/applies-to-version/sqlserver.md)]

  Run [!INCLUDE[ssDQSClient](../includes/ssdqsclient-md.md)], and log on to a [!INCLUDE[ssDQSServer](../includes/ssdqsserver-md.md)].  
  
##  <a name="BeforeYouBegin"></a> Before You Begin  
  
###  <a name="Prerequisites"></a> Prerequisites  
 You must have completed the [!INCLUDE[ssDQSServer](../includes/ssdqsserver-md.md)] installation by running the DQSInstaller.exe file. For more information, see [Run DQSInstaller.exe to Complete Data Quality Server Installation](../data-quality-services/install-windows/run-dqsinstaller-exe-to-complete-data-quality-server-installation.md).  
  
###  <a name="Security"></a> Security  
  
####  <a name="Permissions"></a> Permissions  
 You must have one of the three DQS roles (dqs_administrator, dqs_kb_editor, or dqs_kb_operator) granted on the DQS_MAIN database to be able to log on to [!INCLUDE[ssDQSServer](../includes/ssdqsserver-md.md)].  
  
##  <a name="Run"></a> Run Data Quality Client  
 To run [!INCLUDE[ssDQSClient](../includes/ssdqsclient-md.md)] on the computer where you have installed it:  
  
1.  In the **Start** menu, select the **[!INCLUDE[ssnoversion](../includes/ssnoversion-md.md)]** **Data Quality Client**.  
  
2.  In the **Connect to Server** dialog box:  
  
    1.  Specify the server that you want to connect the [!INCLUDE[ssDQSClient](../includes/ssdqsclient-md.md)] application to. Select **(LOCAL)** to connect to [!INCLUDE[ssDQSServer](../includes/ssdqsserver-md.md)] on the local computer. You can also click the down arrow and select **\<Browse network for more servers>** to connect to a different server (or to connect to the local server by name). The **Browse for Servers** dialog box will be displayed. You can select a server in the **Local Servers** tab or in the **Network Servers** tab.  
  
    2.  To encrypt data transfer between [!INCLUDE[ssDQSServer](../includes/ssdqsserver-md.md)] and [!INCLUDE[ssDQSClient](../includes/ssdqsclient-md.md)], click **Options**, and then select the **Encrypt Connection** check box.  
  
3.  Click **Connect**.  
  
 The [!INCLUDE[ssDQSClient](../includes/ssdqsclient-md.md)] home screen appears. For more information, see [Data Quality Client Home Screen](../data-quality-services/data-quality-client-home-screen.md).  
  
  
