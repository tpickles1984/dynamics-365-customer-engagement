---
title: "Install and set up the Dynamics 365 app for Teams| MicrosoftDocs"
ms.custom: 
description: "Install and set up the Dynamics 365 app for Teams."
ms.date: 12/04/2018
ms.reviewer: 
ms.service: crm-online
ms.suite: 
ms.tgt_pltfrm: 
ms.topic: article
applies_to: 
  - Dynamics 365 for Customer Engagement apps
  - Dynamics 365 for Customer Engagement Version 9.x
ms.assetid: 8097c9ec-023b-407d-ac0e-074b5e1964a5
caps.latest.revision: 17
author: jimholtz
ms.author: jimholtz
manager: kvivek
search.audienceType: 
  - enduser
search.app: 
  - D365CE
  - Powerplatform
---
# Install and set up the Dynamics 365 app for Teams

[!INCLUDE[cc-applies-to-update-9-0-0](../includes/cc_applies_to_update_9_0_0.md)]

[!INCLUDE [cc-beta-prerelease-disclaimer](../includes/cc-beta-prerelease-disclaimer.md)]

## Install the app and set up the Teams tab

1. In Microsoft Teams, select **Store**. 

   > [!div class="mx-imgBorder"]
   > ![Select Store](media/select-store.png "Select Store")

2. Search for **dynamics**, and then select the **Dynamics 365 (Preview)** tile.

   > [!div class="mx-imgBorder"]
   > ![Search for and select Dynamics 365](media/teams-search-select-dynamics-365-app.png "Search for and select Dynamics 365")

3. Verify that **Add for you** and **Add to a team** are both set to **Yes**.

   You can use Dynamics 365 for Customer Engagement apps for your own use or use on a Microsoft Teams channel to collaborate with others. If you have an existing Microsoft Teams channel, select both options. Otherwise, you can start installing for your personal use and install the app for your Teams later.

   > [!div class="mx-imgBorder"] 
   > ![Enable personal and team features](media/teams-store-install-both75.png "Enable personal and team features")

4. For **Add to a team**, choose a team and then select **Install**. 

   > [!div class="mx-imgBorder"] 
   > ![Add to team](media/teams-store-install-add-team75.png "Add to team")

5. Pick a channel in Microsoft Teams to connect to a Dynamics record and then select **Set up**.

   > [!div class="mx-imgBorder"] 
   > ![Pick a channel and select Set up](media/teams-install-app-step2.png "Pick a channel and select Set up")

6. Select **Review permissions**.

   > [!div class="mx-imgBorder"] 
   > ![Review permissions](media/teams-review-premissions75.png "Review permissions")

7. Read through the permissions and select **Accept**.

   > [!div class="mx-imgBorder"] 
   > ![Accept permissions](media/teams-permissions-requested.png "Accept permissions")

8. Select a version 9.x org and a Unified Interface app to connect, and then choose **Save**.

   > [!div class="mx-imgBorder"] 
   > ![Select org and app module](media/teams-fre-org-app.png "Select org and app module")

   > [!NOTE]
   > - Only Dynamics 365 for Customer Engagement version 9.x or later organizations appear in the list. Also, only active organizations (those that are not disabled or provisioning) are displayed. 
   > - Only Unified Interface apps are listed.
   > - Only app modules licensed for the selected organization are listed. 

9. Select an entity to connect. You can pick a recently viewed record or use search to find records. You can use **Filter by** to narrow the search to an entity type. Once you've picked a record, select **Save**.

   > [!div class="mx-imgBorder"] 
   > ![Select an entity](media/teams-add-channel-pin-record2.png "Select an entity")

After completing the above steps, you can select a Dynamics 365 for Customer Engagement apps record to connect to the Microsoft Teams channel. For more information, see [Collaborate with Teams](teams-collaboration.md). 

> [!div class="mx-imgBorder"] 
> ![Record successfully connected and pinned](media/teams-pinned-record.png "Record successfully connected and pinned")

For troubleshooting, see [Troubleshoot Teams integration](teams-troubleshoot.md).

## Set up the Dynamics 365 bot

> [!NOTE]
> The Dynamics 365 bot for Teams is currently only available for organizations in the North American region.

Set up the bot feature to interact with Dynamics 365 for Customer Engagement apps.

1. Find and open the Dynamics 365 bot. Open **Chat** on the left side of the Teams app, and then select **Dynamics 365 for Customer Engagement apps**.

2. The **Conversation** tab opens with the welcome message sent by the bot that provides an overview of the bot’s abilities. Select **Sign in**.

   > [!div class="mx-imgBorder"] 
   > ![Sign in to the bot](media/teams-bot-welcome.png "Sign in to the bot")

3. Select an org, and then select **Next**.

   If the org has multiple app modules (Sales, Marketing, Service, and so on), then you'll also select an app module.

   > [!div class="mx-imgBorder"] 
   > ![Select an org](media/teams-bot-select-org.png "Select an org")

   > [!NOTE]
   > Only Dynamics 365 for Customer Engagement version 9.x or later organizations appear in the list. Also, only active organizations (those that are not disabled or provisioning) are displayed.

4. Enter credentials and sign in.

   The Dynamics 365 bot setup is complete and some preloaded options are available for getting started.

   > [!div class="mx-imgBorder"] 
   > ![Bot is set up](media/teams-bot-confirmation.png "Bot is set up")

See [Use the bot](teams-bot-search.md) for information on how you can use the bot feature to interact with Dynamics 365 for Customer Engagement apps.

## Set up the personal dashboard
Set up the personal dashboard (My Dashboard) to interact with Dynamics 365 for Customer Engagement apps without involving other team members.

1. Open the Dynamics 365 app.

   > [!div class="mx-imgBorder"] 
   > ![Open the Dynamics 365 for Customer Engagement appsapp](media/teams-pick-app.png "Open the Dynamics 365 for Customer Engagement appsapp")

2. Select a version 9.x org and a Unified Interface app to connect with Dynamics 365 for Customer Engagement apps, and then choose **Save Changes**.

   > [!div class="mx-imgBorder"] 
   > ![Select org and app module](media/teams-mydashboard-org-app.png "Select org and app module")

   > [!NOTE]
   > - Only Dynamics 365 for Customer Engagement version 9.x or later organizations appear in the list. Also, only active organizations (those that are not disabled or provisioning) are displayed. 
   > - Only Unified Interface apps are listed.
   > - Only app modules licensed for the selected organization are listed. 

3. Select the **My Dashboard** tab.

See [Use the personal dashboard](teams-personal-use.md) for information on how you can use **My Dashboard**.

## For Dynamics 365 for Customer Engagement admins: enable Microsoft Teams integration Preview features

Because this is a preview feature, you can control whether to display Teams integration in Dynamics 365 for Customer Engagement apps. For [Teams integration in Customer Engagement apps](teams-collaboration.md#teams-integration-in-dynamics-365-for-customer-engagement-apps), the Customer Engagement apps admin should enable the following setting.

> [!NOTE]
> This setting is currently only available for organizations in the North American region. 

1. Sign in as a System administrator to Dynamics 365 for Customer Engagement apps.
2. Go to **Settings** > **Administration** > **System Settings** > **Previews** tab.
3. Enable **Microsoft Teams Integration Preview**.

   > [!div class="mx-imgBorder"] 
   > ![Enable preview settings](media/teams-system-settings.png "Enable preview settings")

When Microsoft Teams Integration Preview is enabled, the **Collaborate** button appears on records in Dynamics 365 for Customer Engagement apps so you can see the connected team channel. In addition, in the **Documents** tab, files synchronized with Teams will appear.   

If not enabled, users can still connect Dynamics 365 for Customer Engagement apps records to Microsoft Teams but the related Microsoft Teams channel and document do not appear in Dynamics 365 for Customer Engagement apps.  

### See also  
 [Troubleshoot Teams integration](teams-troubleshoot.md)

