---
title: "View the SQL Server error log (SSMS)"
description: Learn about the SQL Server error log, which contains user-defined events and certain system events you can use for troubleshooting.
ms.prod: sql
ms.technology: performance
ms.topic: conceptual
helpviewer_keywords: 
  - "viewing logs"
  - "displaying logs"
  - "errors [SQL Server], logs"
  - "logs [SQL Server], SQL Server error logs"
  - "logs [SQL Server], viewing"
author: WilliamDAssafMSFT
ms.author: wiassaf
ms.reviewer: ""
ms.custom: seo-dt-2019, FY21Q2Fresh
ms.date: "10/21/2021"
---
# View the SQL Server error log in SQL Server Management Studio (SSMS)

 [!INCLUDE [SQL Server](../../includes/applies-to-version/sqlserver.md)]
The [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] error log contains user-defined events and certain system events you can use for troubleshooting. 

## View the logs

1. In SQL Server Management Studio, select **Object Explorer**. To open **Object Explorer**, select F8. Or on the top menu, select **View**, and then select **Object Explorer**:
    
    :::image type="content" source="../../relational-databases/performance/media/object-explorer.png" alt-text="Object Explorer in the SSMS menu" lightbox="../../relational-databases/performance/media/object-explorer.png":::

2. In **Object Explorer**, connect to an instance of SQL Server, and then expand that instance.
  
3. Find and expand the **Management** section (assuming you have permissions to see it).

4. Right-click **SQL Server Logs**, select **View**, and then choose **SQL Server Log**.

    :::image type="content" source="../../relational-databases/performance/media/view-sqlserver-log-ssms.png" alt-text="View the SQL Server Log in SSMS" lightbox="../../relational-databases/performance/media/view-sqlserver-log-ssms.png":::
 
5. The **Log File Viewer** appears (it might take a moment) with a list of logs for you to view.

## Next steps

  For more information, see [MSSQLTips.com's](https://www.mssqltips.com/) helpful post [Identify location of the SQL Server Error Log file](https://www.mssqltips.com/sqlservertip/2506/identify-location-of-the-sql-server-error-log-file/).

