---
title: Add users and assign licenses in Microsoft Defender for Business
description: Add users and assign Defender for Business licenses to protect their devices
search.appverid: MET150
author: denisebmsft
ms.author: deniseb
manager: dansimp 
audience: Admin
ms.topic: conceptual
ms.service: microsoft-365-security
ms.subservice: mdb
ms.localizationpriority: medium
ms.date: 08/24/2022
ms.collection: 
- m365-security
- tier1
ms.reviewer: shlomiakirav
f1.keywords: NOCSH 
---

# Add users and assign licenses in Microsoft Defender for Business

As soon as you have signed up for Defender for Business, your first step is to add users and assign licenses. This article describes how to add users and includes next steps.

## Add users and assign licenses

> [!IMPORTANT]
> You must be a global administrator to perform this task.  The person who signed up your company for Microsoft 365 or for Defender for Business is a global administrator by default.

1. Go to the Microsoft 365 admin center at [https://admin.microsoft.com](https://admin.microsoft.com) and sign in.

2. Go to **Users** > **Active users**, and then select **Add a user**.

3. In the **Set up the basics** pane, fill in the basic user information, and then select **Next**.

   - **Name**: Fill in the first and last name, display name, and username.
   - **Domain** Choose the domain for the user's account. For example, if the user's username is `Pat`, and the domain is `contoso.com`, they'll sign in by using `pat@contoso.com`.
   - **Password settings**: Choose whether to use the autogenerated password or to create your own strong password for the user. The user must change their password after 90 days. Or you can choose the option to **Require this user to change their password when they first sign in**. You can also choose whether you want to send the user's password in email when the user is added.

4. On the **Assign product licenses** page, select Defender for Business (or Microsoft 365 Business Premium). Then choose **Next**. 

   If you don't have any licenses available, you can still add a user and buy additional licenses. For more information about adding users, see [Add users and assign licenses at the same time](../../admin/add-users/add-users.md).

5. On the **Optional settings** page, you can expand **Profile info** and fill in details, such as the user's job title, department, location, and so forth. Then choose **Next**.

6. On the **Review and finish** page, review the details, and then select **Finish adding** to add the user. If you need to make any changes, choose **Back** to go back to a previous page.

## Next steps

- [Visit the Microsoft 365 Defender portal](mdb-get-started.md)
- [Use the setup wizard in Defender for Business](mdb-use-wizard.md).
