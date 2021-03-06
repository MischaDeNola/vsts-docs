---
title: Manage notifications for an organization
titleSuffix: Azure DevOps 
description: Manage notifications for an organization in Azure DevOps or Team Foundation Server (TFS)
ms.technology: devops-collab
ms.prod: devops
ms.manager: mijacobs
ms.reviewer: wismythe
ms.author: chcomley
author: chcomley
ms.topic: conceptual
ms.date: 12/30/2019
monikerRange: '>= tfs-2017'
---

# Manage notifications for an organization

[!INCLUDE [version-vsts-tfs-2017-on](../includes/version-tfs-2017-through-vsts.md)]

> [!NOTE] 
> This article applies to Azure DevOps, TFS 2017 Update 1, and later versions. If you work from an on-premises TFS 2017 or earlier versions, see [Set alerts, get notified when changes occur](../work/track/alerts-and-notifications.md). For on-premises TFS, [you must configure an SMTP server](/azure/devops/server/admin/setup-customize-alerts) in order for team members to see the Notifications option from their organization menu and to receive notifications.

In this article, learn about managing notifications for your organization. 

> [!TIP]
> We don't support organization-wide notifications. As an alternative, you can provide an email distribution list that goes to your entire organization. 

## Organization level notifications page

See [Navigating the UI](navigating-the-ui.md) to learn how to locate this page.

The organization notifications page consists of the following sections:

* Default subscriptions - view all [default notification subscriptions](./oob-built-in-notifications.md)
* Subscribers - view notification subscriptions for a specific group, team, or individual
* Statistics - view the most active subscriptions and top event initiators
* Settings - manage organization level settings such as delivery preferences

## Organization notifications page: Default subscriptions

The `Default subscriptions` section lists all default subscriptions available to the organization. The globe icon on a notification subscription indicates the subscription is a default subscription.

Members of the **project collection administrators** group have permission to enable/disable any default subscription in this view. Any member project collection valid users have permission to view the details of the default subscription. The view and enable options are available in the context menu (`...`) associated with each individual subscription.

> [!div class="mx-imgBorder"] 
>![Organization level notifications page: Default subscriptions](media/view-organization-notification-default-subscriptions.png)

## Organization notifications page: Subscribers

The `Subscribers` section begins with an empty identity search box. Enter any group, team, or individual to view the list of subscriptions associated with the specified identity.

> [!div class="mx-imgBorder"] 
>![Organization level notifications page: Subscribers empty](media/view-organization-notification-subscribers-empty.png)

All notification subscriptions for the chosen identity are listed in this view. Management options are available from the context menu (`...`) associated with each subscription. Note, the ![globe](media/oob-notification.png) icon on subscription row indicates a default subscription.

> [!div class="mx-imgBorder"] 
>![Organization level notifications page: Subscribers list](media/view-organization-notification-subscribers.png)

## Organization notifications page: Statistics

The `Statistics` section shows the most active notification subscriptions and the top event initiators (group, team, or individual). The statistics are only for the current day and reset at 00:00 UTC. A benefit of these statistics is identifying unintended high volume subscriptions or event initiators.

> [!div class="mx-imgBorder"] 
>![Organization level notifications page: Statistics](media/view-organization-notification-stats.png)

## Organization notifications page: Settings

The `Settings` section allows organization level notification settings to be managed by any member of the **project collection administrators** group. All teams and groups inherit the _Default delivery option_ setting, which is why it isn't explicitly set at the team or group level.

> [!div class="mx-imgBorder"] 
>![Organization level notifications page: Settings](media/view-organization-notification-settings.png)

