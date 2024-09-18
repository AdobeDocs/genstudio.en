---
title: Connect to an AEM Assets Content Hub repository
description: Learn how to connect GenStudio for Performance Marketers to an Adobe Experience Manager (AEM) Content Hub repository and leverage existing approved content.
level: Experienced
feature: Assets, Content
---
# Connect to an [!DNL AEM Assets Content Hub] repository

If you have assets in Adobe Experience Manager (AEM), you can follow these steps to make them accessible in GenStudio for Performance Marketers.

>[!BEGINSHADEBOX]

**Prerequisites**:

The following steps require administrative access to Admin Console and AEM Assets as a Cloud Service.

>[!ENDSHADEBOX]

## Step 1: Enable [!DNL AEM Assets Content Hub]

Follow the **Deploy Content Hub** self-service process to enable [!DNL Content Hub] for your existing AEM Assets in Cloud Manager. See [Deploy [!DNL Content Hub]](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub) in the _AEM as a Cloud Service_ documentation.

After you enable [!DNL AEM Assets Content Hub], you have a new instance with the `contenthub` suffix within [!DNL AEM Assets as a Cloud Service] on Admin Console.

## Step 2: Onboard GenStudio users

In the [!DNL Admin Console], add GenStudio users or user groups to the [!DNL AEM Assets Content Hub] product profiles. [!DNL AEM Assets Content Hub] users can view assets but cannot add assets or modify existing assets.

- [Onboard [!DNL Content Hub] administrator](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub#onboard-content-hub-administrator)
- [Onboard [!DNL Content Hub] users](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub#onboard-content-hub-users)

## Step 3: Approve assets

Approve assets for use in [!DNL AEM Assets Content Hub], which makes them available in GenStudio for Performance Marketers. See [Approve assets in Experience Manager](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/approve-assets) in the _AEM as a Cloud Service_ documentation.

## Step 4: Configure asset visibility

In _[!DNL AEM Assets Content Hub]_ configuration options, review each set of configuration options for filters, asset details, search, and branding. See [Configure Content Hub user interface](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/configure-content-hub-ui-options) in the _AEM as a Cloud Service_ documentation.

## Step 5: Verify the connection

In GenStudio for Performance Marketers Content, the _[!UICONTROL Location]_ list is available above the gallery on the right side. The list is not available if you do not have access or your organization has not deployed and connected an [!DNL AEM Assets Content Hub] repository.
