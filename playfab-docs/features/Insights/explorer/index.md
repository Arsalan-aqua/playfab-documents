---
title: Explorer
author: nathankong-microsoft
description: Overview for PlayFab Explorer
ms.author: nakong
ms.date: 09/22/2020    
ms.topic: article
ms.prod: playfab
keywords: playfab, insights, explorer
ms.localizationpriority: medium
---

# PlayFab Explorer

## Overview

The PlayFab Explorer is the primary window into event data collected by your title and services. The data is stored in PlayFab Insights, an in-development offering designed to provide a complete back-end solution for data and analytics. For more information on the PlayFab Insights vision and strategy, see our [webinar](https://www.youtube.com/channel/UCaCZHrQg_-qPrYIVsTFuUHg). 

Explorer provides fast indexing and querying on large, diverse data sets. For optimized queries, the engine can query millions of records in a few seconds - a critical capability for games producing high throughput or large volumes of gaming events.

Explorer has two different querying modes - Basic and Advanced. Explorer Basic is designed to let you quickly discover insights in your event data without requiring query language knowledge. Explorer Advanced is designed for more complex queries and deeper insights using the [Kusto query language](https://docs.microsoft.com/azure/data-explorer/kusto/query) – a SQL-like language optimized for ad hoc data exploration. 

Explorer Advanced uses a simplified SQL-like language that's easy to pick up and learn. The [intellisense](https://docs.microsoft.com/azure/data-explorer/write-queries) capabilities make it possible for users of all skill levels to author complex queries and [render](https://docs.microsoft.com/azure/kusto/query/renderoperator) the results in-line.

Learn how to get started in the [Quickstart](quickstart.md) section. 
