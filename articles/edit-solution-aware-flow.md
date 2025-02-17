---
title: Edit a solution-aware cloud flow | Microsoft Docs
description: Learn how to edit solution-aware cloud flows.
services: ''
suite: flow
documentationcenter: na
author: msftman
manager: tapanm
editor: ''
tags: ''

ms.devlang: na
ms.subservice: cloud-flow
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 10/12/2022
ms.author: deonhe
search.app: 
  - Flow
search.audienceType: 
  - flowmaker
  - enduser
---

# Edit a solution-aware cloud flow

You can edit solution-aware cloud flows via [solutions](#edit-a-solution-aware-cloud-flow-via-solutions) or via [my flows](#edit-a-solution-aware-cloud-flow-via-my-flows).

> [!IMPORTANT]
> Stop your flow before you edit it so that you don't lose your changes.

## Edit a solution-aware cloud flow via Solutions

1. Sign into [Power Automate](https://powerautomate.com), and then select **Solutions** from the navigation bar on the left side.
1. Select the solution that contains the flow you want to edit.

   ![Displays a new flow inside a solution.](./media/edit-solution-aware-flow/new-flow-inside-solution.png "Displays a new flow inside a solution")

1. Select **...** (Commands) for your flow, and then select **Turn off**.
1. Select **...** (Commands) for your flow, and then select **Edit**.

   ![Displays editing a cloud flow.](./media/edit-solution-aware-flow/edit-flow.png "Displays editing a cloud flow")

1. Make your edits in the Power Automate designer, test your changes, and then save your flow.
1. Turn on your flow if you'd like it to run.

## Edit a solution-aware cloud flow via My flows

1. In [Power Automate](https://powerautomate.com), select **My flows** from the navigation bar on the left side.
1. Find the flow you want to edit. Cloud flows you own will be in the **Cloud flows** tab and flows you have co-ownership of will be in the **Shared with me** tab.
1. Select **...** (Commands) for your flow, and then select **Turn off**.
1. Select **...** (Commands) for your flow, and then select **Edit**.
1. Make your edits in the Power Automate designer, test your changes, and then save your flow.
1. Turn on your flow if you'd like it to run.

>[!WARNING]
>When you edit solution-aware flows, it's possible for you to introduce unmanaged customization layers into your managed solution-aware flows. Unmanaged customization layers can impact your ability to update these flows in the future.

## Learn more

* [Manage and edit a cloud flow](/power-automate/get-started-logic-flow#manage-a-cloud-flow)
* [Create a solution](./overview-solution-flows.md)
* [Create a cloud flow in a solution](./create-flow-solution.md)
* [Export a solution](./export-flow-solution.md)
* [Import a solution](./import-flow-solution.md)
* [Remove a solution-aware flow](./remove-solution-aware-flow.md)

[!INCLUDE[footer-include](includes/footer-banner.md)]
