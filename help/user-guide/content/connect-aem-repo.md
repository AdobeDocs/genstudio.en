---
title: Connect an AEM content repository
description: Learn how to connect GenStudio for Performance Marketers to an Adobe Experience Manager (AEM) repository and leverage exisiting approved content.
level: Admin
feature: Assets, Content
---
# Connect an AEM content repository

If you have assets in Adobe Experience Manager (AEM), you can follow these steps to make them asccessible in GenStudio for Performance Marketers.

>[!BEGINSHADEBOX]

**Prerequisites**:

Much of the following steps require administrative access to Admin Console and AEM Assets as a Cloud Service.

>[!ENDSHADEBOX]

## Step 1: Deploy [!DNL Content Hub]

Deploy Content Hub for your existing AEM repo. This is a self-service process in Cloud Manager. See [Deploy [!DNL Content Hub]](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub) in the _AEM as a Cloud Service_ documentation.

After you enable [!DNL Content Hub], you have a new instance with the `contenthub` suffix within [!DNL AEM Assets as a Cloud Service] on Admin Console.

## Step 2: Onboard GenStudio users

In the [!DNL Admin Console], add GenStudio users or user groups to the Content Hub product profiles. [!DNL Content Hub] users can view assets but cannot add assets or modify existing assets.

- [Onboard [!DNL Content Hub] administrator](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub#onboard-content-hub-administrator)
- [Onboard [!DNL Content Hub] users](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub#onboard-content-hub-users)


## Step 3: Approve assets

You must approve assets for use in [!DNL Content Hub], which in turn makes them available in GenStudio for Performance Marketers.

## Step 4: Configure asset visibility

TBD

- Configure what GenStudio users would see in existing AEM CS repo (self-service in Content Hub configuration UI)
- Configure filters, metadata in Assets View Details page, search, and brand name that is available for GenStudio users

## Step 5: Verify connection

TBD
