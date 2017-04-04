---
# required metadata

title: Back up database for an LCS solution
description: A Dynamics 365 for Operations database backup is required for your LCS solution package. When you back up your database, you must include the master, reference, and transactional data that is specific to your solution and industry. This will be used for your pre-sales demo deployments. 
author: kfend
manager: AnnBe
ms.date: 2017-04-04
ms.topic: article
ms.prod: 
ms.service: Lifecycle Services
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: IT Pro
# ms.devlang: 
# ms.reviewer: 51
ms.search.scope: Lifecycle Services
# ms.tgt_pltfrm: 
ms.custom: 196833
ms.assetid: fc0f06e8-1a20-45f7-ae98-ee074fe1f030
ms.search.region: Global
# ms.search.industry: 
ms.author: omarc
ms.search.validFrom: 
ms.dyn365.ops.version: 

---

# Back up database for an LCS solution

A Dynamics 365 for Operations database backup is required for your LCS solution package. When you back up your database, you must include the master, reference, and transactional data that is specific to your solution and industry. This will be used for your pre-sales demo deployments. 

On demo or development environments, the database is typically called AXDBRain. Your database backup should be no larger than 15 gigabyte (GB). If your database is larger, a timeout error may occur when you try to upload the database to the **Asset library **in Lifecycle Services (LCS). To compress your database backup, in SQL Server Management Studio, on the **Back Up Database** page, in the **Set backup compression** field, select **Compress backup**. [![databasebackup01](./media/databasebackup01.jpg)](./media/databasebackup01.jpg)

See also
--------

[LCS Solutions for AppSource home page](lcs-solutions-app-source.md)
