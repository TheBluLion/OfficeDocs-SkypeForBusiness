---
title: "MediationServers table"
ms.reviewer: 
ms.author: v-cichur
author: cichur
manager: serdars
ms.date: 3/9/2015
audience: ITPro
ms.topic: article
ms.prod: skype-for-business-itpro
f1.keywords:
- NOCSH
ms.localizationpriority: medium
ms.assetid: 9f757377-ab79-4795-aaa9-1163cb9c8a59
description: "The MediationServers table is a supporting table. Each record stores information about one Mediation Server that is involved in calls that have records in the database."
---

# MediationServers table
 
The MediationServers table is a supporting table. Each record stores information about one Mediation Server that is involved in calls that have records in the database.
  
|**Column**|**Data Type**|**Key/Index**|**Details**|
|:-----|:-----|:-----|:-----|
|**MediationServerId** <br/> |int  <br/> |Primary  <br/> |Unique number identifying this Mediation Server.  <br/> |
|**MediationServer** <br/> |nvarchar(256)  <br/> | <br/> |Mediation Server name.  <br/> |
   

