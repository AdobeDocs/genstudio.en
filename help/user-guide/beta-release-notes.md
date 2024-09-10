---
title: Adobe GenStudio for Performance Marketers Beta release notes
description: Learn about the latest features and enhancements to Adobe GenStudio for Performance Marketers.
exl-id: 2ae60dcb-ac95-4ed4-bceb-84b396f7fa4e
---
# Adobe GenStudio for Performance Marketers Beta release notes

These notes highlight significant Adobe GenStudio for Performance Marketers fixes and enhancements for the week ending September 6.

## New features

* GenStudio now supports the option to preview media assets in [!DNL Insights] table and gallery views. Video thumbnails include a **Play** button with a mute option. <!-- GS-4398 -->

## Known issues

The following known issues are scheduled for resolution in the GenStudio for Performance Marketers GA release.

* Editors occasionally encounter a "Something went wrong" error message  on the [!DNL Create Canvas] during image generation. **Workaround**: If the error repeats, the user can log out, then log back in to GenStudio and regenerate the image.  <!-- GS-4813 -->

* The [!DNL Create Canvas] renders images in Meta ads incorrectly. <!-- GS-4864 -->

* Assets without campaigns can be successfully uploaded into [!DNL Content] but may not be visible to users. <!-- GS-4815 -->

* Discrepancy exists between MetaAds Canvas previews and exported views. <!-- GS-4492 4401 -->

* Campaign thumbnails are missing from [!DNL Insights]. <!-- GS-4648 -->

* Users can currently select small assets that require resizing, but enlarging those assets is not supported. <!-- GS-3131 -->

* Users must log in twice to a channel Meta Ads account when they are also logged in to Facebook. **Workaround**: Log out of Facebook before logging into a channel Meta Ads account.

* Uploaded images do not always include the expected smart tags. <!-- GS-4856 -->

### Additional Enhancements and fixed issues

* The _Add Assets_ popup is now localized as expected. <!-- GS-3834 -->

* Issues with the scaling of the Meta ads experience template have been resolved. <!-- GS-4174 -->

* Text fields in the CSV export file for multi-part emails are now ordered as expected. <!-- GS-4013 -->

* The [!DNL Content] search field no longer disappears when a user repeatedly presses the **Backspace** key to erase search field text.  <!-- GS-4543 -->

* GenStudio now loads users as expected when a collaborator adds an @ mention to a comment. Previously, GenStudio did not load users and displayed this error: `Unable to load users. Refresh the page`. <!-- GS-4113 -->

* GenStudio no longer displays the **Something went wrong** message when an editor clicks **Select content** during email creation in the prompt area. <!-- GS-4879 -->

## Previous Beta releases

Previous Beta releases included the following highlights and fixes. 

### Highlights

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

* **Meta Ads Resize**: Editors can resize Meta ad aspect ratios. (fixed 8/16)

* **Limited [!DNL Insights] login accounts**: The [!DNL Insights] login now supports only one account per customer. (fixed 8/16)

### Additional Enhancements and fixed issues

* The _Experience Detail_ page feed placement name now specifies Facebook or Instagram feed. (fixed 8/16)

* Cropping of larger images and videos is now consistent when user navigates from the _Asset Overview_ view to the _Asset Detail_ view. (fixed 8/16)

* The Attributes screen search result count no longer displays `0 of` before a user logs in. (fixed 8/16) <!-- GS-3665 -->

* Clicking the **[!UICONTROL [!DNL Insights]]**  > **[!UICONTROL Asset]** count field no longer clears search and filter settings. (fixed 8/16) <!-- GS-3476 -->

### Known issues resolved in past Beta releases

* GenStudio displays an error when a user tries to enter credentials in the [!DNL Insights] view. (fixed 8/29) <!-- GS-4689 --> 

* Upload of brand guidelines fails due to issues with the ACP storage platform. (fixed 8/22) <!-- GS-4369 -->

* The Prompt area [!DNL Brands] drop-down menu displays a spinner at the end of the [!DNL Brands] list during email creation. (fixed 8/22) <!-- GS-4077 -->
