---
title: Adobe GenStudio for Performance Marketers Beta release notes
description: Learn about the latest features and enhancements to Adobe GenStudio for Performance Marketers.
exl-id: 2ae60dcb-ac95-4ed4-bceb-84b396f7fa4e
---
# Adobe GenStudio for Performance Marketers Beta release notes

These notes highlight significant Adobe GenStudio for Performance Marketers fixes and enhancements for the week ending September 13.

## Enhancements

* The [!DNL Create] content selector has been refactored to improve asset loading. <!-- GS-2586 -->

## Known issues

The following known issues are scheduled for resolution in the GenStudio for Performance Marketers GA release.

* Intermittent latency issues affect some [!DNL Create] Canvas operations. <!-- GS-5203 -->

* Email generation results in an incomplete email. **Workaround**: Refresh the page and regenerate. <!-- GS-5209 -->

* Templates can be uploaded but not seen. **Workaround**: Create or upload an asset and enter an asset group name in the **[!UICONTROL Campaigns]** field. Assigning the asset to a [!DNL Campaign] adds the group name metadata value. Then, upload the template again. <!-- GS-4815 --> 

* Campaign thumbnails are missing from [!DNL Insights]. <!-- GS-4648 -->

* Users must log in twice to a channel Meta Ads account when they are also logged in to Facebook. **Workaround**: Log out of Facebook before logging into a channel Meta Ads account. <!-- GS-4806 -->

### Additional enhancements and fixed issues

* The [!DNL Create] Canvas now renders images in Meta Ads correctly. <!-- GS-4864 -->

* Although discrepancies can exist between Meta Ads Canvas previews and exported views, exported experiences work as expected. <!-- GS-4492 4401 -->

* Uploaded images now include the expected smart tags. <!-- GS-4856 -->

* The Meta Ads export CSV file now contains images as expected. Previously, the ZIP file contained the CSV export file and NULL files instead of images.  <!-- GS-5107 -->

* Users can now enter text into the Template Detail view **[!UICONTROL Uploaded by]** field as expected. Previously, the loading icon prevented users from entering text. <!-- GS-4887 -->

* Users are no longer redirected to the Detail view of a brand after the brand has been deleted. <!-- GS-2663 -->

* Editors no longer receive the following error when sending variants for review and approval: `You have no access to view comments on this Object`.  <!-- GS-5140 -->

* Updated the email template used by the review and approvals workflow. <!-- GS-5239 -->

* GenStudio now displays an error message when a network error occurs during template selector loading. <!-- GS-4682 -->

* Resolved issues with navigating from an asset, experience, or template card to the selected object. <!-- GS-4390 -->

* The _Add Assets_ popup is now localized when opened from the Create Canvas.  <!-- GS-4867 -->

* Brand validation is now triggered for regenerated variants. Previously, if an editor regenerated variants of an existing draft, validation was not triggered. <!-- GS-3971 -->

## Previous Beta releases

Previous Beta releases included the following highlights and fixes. 

### Highlights

* GenStudio now supports the option to preview media assets in [!DNL Insights] table and gallery views. Video thumbnails include a **Play** button with a mute option. <!-- GS-4398 -->

* Instagram and Facebook channel guidelines have been combined into Meta brand guidelines.

* [!DNL Create] Canvas navigation elements have been streamlined. The [!DNL Create] landing page displays the left navigation panel, but users now use a **[!UICONTROL Back]** button to navigate to this space from other [!DNL Create] work areas.

* Navigation elements have been enhanced to support user focus while performing tasks throughout the product, including these product areas:

  * Asset, Experience, Template details in [!DNL Content]
  * Experience, Asset, Attribute detail in [!DNL Insights]
  * Brand details in [!DNL Brands]
  * Product and Persona details in Products and Personas

* Users no longer need to click the **[!UICONTROL Refresh]** button to see updates to Experiences in [!DNL Content].

* The _Experience Details_ page now renders external asset thumbnails as HTML.

* UI latency after adding or deleting Assets and Experiences has been improved.

* Template previews now include more descriptive default text. See [Customize a template](https://experienceleague.adobe.com/en/docs/genstudio/user-guide/content/templates/customize-template#template-preview). 

* **Percentage-based validation score**: Brand validation now displays brand validation score as a percentage rather than a pass/fail value. (fixed 8/16)

* **Updated Brand extraction interface**: Brand extraction now shows completion of the extraction process as a percentage. (fixed 8/16)

* **Incremental brand load during extraction**: Brand guidelines are now incrementally loaded in the user interface. (fixed 8/16)

* **Multi-section email creation**: Users can now create emails composed of separate headline, image, body, and CTA elements. (fixed 8/16)

* **MetaAds Resize**: Editors can resize MetaAd aspect ratios. (fixed 8/16)

* **Limited [!DNL Insights] login accounts**: The [!DNL Insights] login now supports only one account per customer. (fixed 8/16)

### Additional Enhancements and fixed issues

* The _Add Assets_ popup is now localized as expected. <!-- GS-3834 -->

* Issues with the scaling of the Meta ads experience template have been resolved. <!-- GS-4174 -->

* Text fields in the CSV export file for multi-part emails are now ordered as expected. <!-- GS-4013 -->

* The [!DNL Content] search field no longer disappears when a user repeatedly presses the **Backspace** key to erase search field text.  <!-- GS-4543 -->

* GenStudio for Performance Marketers now loads users as expected when a collaborator adds an `@` mention to a comment. Previously, users were not loaded and an error displayed: `Unable to load users. Refresh the page`. <!-- GS-4113 -->

* GenStudio no longer displays the **Something went wrong** message when an editor clicks **Select content** during email creation in the prompt area. <!-- GS-4879 -->

* The _Experience Detail_ page feed placement name now specifies Facebook or Instagram feed. (fixed 8/16)

* Cropping of larger images and videos is now consistent when user navigates from the _Asset Overview_ view to the _Asset Detail_ view. (fixed 8/16)

* The Attributes screen search result count no longer displays `0 of` before a user logs in. (fixed 8/16) <!-- GS-3665 -->

* Clicking the **[!UICONTROL [!DNL Insights]]**  > **[!UICONTROL Asset]** count field no longer clears search and filter settings. (fixed 8/16) <!-- GS-3476 -->

* GenStudio displays an error when a user tries to enter credentials in the [!DNL Insights] view. (fixed 8/29) <!-- GS-4689 --> 

* Upload of brand guidelines fails due to issues with the ACP storage platform. (fixed 8/22) <!-- GS-4369 -->

* The Prompt area [!DNL Brands] drop-down menu displays a spinner at the end of the [!DNL Brands] list during email creation. (fixed 8/22) <!-- GS-4077 -->
