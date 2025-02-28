---
title: Self-review of an access package in Azure AD entitlement management
description: Learn how to review user access of entitlement management access packages in Azure Active Directory access reviews (Preview).
services: active-directory
documentationCenter: ''
author: ajburnle
manager: karenhoran
editor: 
ms.service: active-directory
ms.workload: identity
ms.tgt_pltfrm: na
ms.topic: how-to
ms.subservice: compliance
ms.date: 06/18/2020
ms.author: ajburnle
ms.reviewer: 
ms.collection: M365-identity-device-management


#Customer intent: As a user, I want to complete an access review of my active assignments myself.

---
# Self-review of an access package in Azure AD entitlement management

Azure AD entitlement management simplifies how enterprises manage access to groups, applications, and SharePoint sites. This article describes how a user does a self-review of their assigned access package(s).

## Open the access review

To do an access review, you must first open the access review. Use the following procedure to find and open the access review:

1. You may receive an email from Microsoft that asks you to review access. Locate the email to open the access review. Here is an example of an email requesting a review of access: 
    
    ![Access review self-reviewer email](./media/entitlement-management-access-reviews-review-access/self-review-reviewer-email.png)

1. Click the **Review access** link.

1. You can also go directly to https://myaccess.microsoft.com to find your pending access reviews if you don't receive an email.  (For US Government, use `https://myaccess.microsoft.us` instead.)

1. Click **Access reviews** on the left navigation bar to see a list of pending access reviews assigned to you.


1.	Click the review that you’d like to begin.

## Perform the access review

Once you open the access review, you can see your access. Use the following procedure to do the access review:

1.	Decide whether you still need access to the access package. For example, the project you're working on isn't complete, so you still need access to continue working on the project.

1.	Click **Yes** to keep your access or click **No** to remove your access.
    >[!NOTE]
    >If you stated that you no longer need access, you aren't removed from the access package immediately. You will be removed from the access package when the review ends or if an administrator stops the review.

1.	If you clicked **Yes**, you may need to include a justification statement in the **Reason** box.

1.	Click **Submit**.

You can return to the review if you change your mind and decide to change your response before the end of the review.

## Next steps

- [Review access to access packages](entitlement-management-access-reviews-review-access.md) 
