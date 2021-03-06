---
title: "System | Microsoft Docs"
description: "Learn about system settings in Dynamics 365 Customer Insights."
ms.date: 02/05/2020
ms.service: dynamics-365-ai
ms.topic: "get-started-article"
author: m-hartmann
ms.author: mhart
ms.reviewer: nimagen
manager: shellyha
---

# System

The **System** page contains everything that administrators need to closely monitor the various processes running behind the scenes of Customer Insights. It includes four tabs: **Status**, **Schedule**, **About**, and **General**.

> [!div class="mx-imgBorder"]
> ![System page](media/system-tabs.png "System page")

> [!NOTE]
> If your data sources are updated on a regular basis, we highly recommend that you use the **Schedule** tab. Make sure to review the "Schedule tab" section later in this topic.

## Status tab

The **Status** tab lets you track the progress of data ingestion and several important product processes. Use this tab to ensure the completeness of any major process you've defined in Customer Insights. This tab includes two tables:

- **Data sources**: This table lists all the data sources from which you're ingesting your data. The left-side column specifies the names of those data sources. The middle column shows the status of ingestion for each of the data sources:
  - Didn't start
  - In progress
  - Already completed
  
   The right-side column shows the last data refresh date for each of the data sources.

- **System processes**: This table lists all the processes that should be executed in Customer Insights to create a unified customer profile. The left-side column specifies the names of those processes. The middle column shows the status of progress for each of the processes:
  - Didn't start
  - In progress
  - Already completed
  
    The right-side column shows the last data refresh date for each of the processes.

    > [!div class="mx-imgBorder"]
    > ![Refresh date](media/system-status-processes.png "Refresh date")

You can view the details of each completed data source ingestion or system process by selecting that item.

## Schedule tab

Use the **Schedule** tab to schedule automatic refreshes of all your ingested Customer Insights data. This helps ensure that updates from your data sources are reflected in your unified customer profile.

1. In Customer Insights, go to **Admin** > **System** and select the **Schedule** tab.

2. The default state for data refreshes is **Off**. To enable scheduled refreshes, change the toggle at the top of the screen to **On**.

3. Choose between **Weekly** (default) and **Daily** refreshes. If you intend to schedule weekly refreshes, select one or more days on which you want to run the refresh.

4. Select the **Time** field. In the timer dropdown, use the arrows to set your refresh timing. When you're finished, select **Set**. If you'd like to schedule multiple refreshes in a single day, select **Add another time**.

5. Select **Save** to apply your changes.

## About tab

The **About** tab contains your organization's **Display name**, the active **Instance name**, and the **Region**. If you have more than one work instance, you should give each an easily identifiable name.

## General tab

Only one option, **Language**, is currently available on the **General** tab. Supported languages appear in this menu. Select **Save** to apply your changes.
