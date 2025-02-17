---
description: "Getting Started with System-Versioned Temporal Tables"
title: "Getting Started with System-Versioned Temporal Tables | Microsoft Docs"
ms.custom:
  - intro-get-started
ms.date: "03/28/2016"
ms.prod: sql
ms.prod_service: "database-engine, sql-database"
ms.reviewer: ""
ms.technology: table-view-index
ms.topic: conceptual
ms.assetid: d431f216-82cf-4d97-825e-bb35d3d53a45
author: markingmyname
ms.author: maghan
monikerRange: "=azuresqldb-current||>=sql-server-2016||>=sql-server-linux-2017||=azuresqldb-mi-current"
---
# Getting Started with system-versioned temporal tables


[!INCLUDE [sqlserver2016-asdb-asdbmi](../../includes/applies-to-version/sqlserver2016-asdb-asdbmi.md)]


Depending on your scenario, you can either create new system-versioned temporal tables or modify existing ones by adding temporal attributes to the existing table schema. When the data in temporal table is modified, the system builds version history transparently to applications and end users. As a result, working with system-versioned temporal tables does not require any change to the way table is modified or how the latest (actual) state of the data is queried.

In addition to regular DML and querying, temporal also provides convenient and easy ways to get insights from data history through extended Transact-SQL syntax. Every system-versioned table has a history table assigned but it is completely transparent for the users unless they want to optimize workload performance or storage footprint by creating additional indexes or choosing different storage options.

The following diagram depicts typical workflow with system-versioned temporal tables:
![Getting Started with Temporal](../../relational-databases/tables/media/getting-started-with-temporal.png "Getting Started with Temporal")

This topic is divided into the following 5 subtopics:

- [Creating a System-Versioned Temporal Table](../../relational-databases/tables/creating-a-system-versioned-temporal-table.md)
- [Modifying Data in a System-Versioned Temporal Table](../../relational-databases/tables/modifying-data-in-a-system-versioned-temporal-table.md)
- [Querying Data in a System-Versioned Temporal Table](../../relational-databases/tables/querying-data-in-a-system-versioned-temporal-table.md)
- [Changing the Schema of a System-Versioned Temporal Table](../../relational-databases/tables/changing-the-schema-of-a-system-versioned-temporal-table.md)
- [Stopping System-Versioning on a System-Versioned Temporal Table](../../relational-databases/tables/stopping-system-versioning-on-a-system-versioned-temporal-table.md)

## Next steps

- [Temporal Tables](../../relational-databases/tables/temporal-tables.md)
- [Temporal Table System Consistency Checks](../../relational-databases/tables/temporal-table-system-consistency-checks.md)
- [Partitioning with Temporal Tables](../../relational-databases/tables/partitioning-with-temporal-tables.md)
- [Temporal Table Considerations and Limitations](../../relational-databases/tables/temporal-table-considerations-and-limitations.md)
- [Temporal Table Security](../../relational-databases/tables/temporal-table-security.md)
- [Manage Retention of Historical Data in System-Versioned Temporal Tables](../../relational-databases/tables/manage-retention-of-historical-data-in-system-versioned-temporal-tables.md)
- [System-Versioned Temporal Tables with Memory-Optimized Tables](../../relational-databases/tables/system-versioned-temporal-tables-with-memory-optimized-tables.md)
- [Temporal Table Metadata Views and Functions](../../relational-databases/tables/temporal-table-metadata-views-and-functions.md)
