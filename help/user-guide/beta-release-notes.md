---
title: Adobe GenStudio for Performance Marketers Beta release notes
description: Learn about the latest features and enhancements to Adobe GenStudio.
---

# Adobe GenStudio for Performance Marketers Beta release notes

These notes highlight significant Adobe GenStudio fixes and enhancements for the week ending August 16.

## Highlights

GenStudio feature development is rapid and continuous. Notable new features include:

### Brand

The Brand validation panel was enhanced to improve user experience, including these changes: 

* _Percentage-based validation score_: Brand validation now displays brand validation score as a percentage rather than a pass/fail value. 

* _Updated Brand extraction interface_: Brand extraction now shows completion of the extraction process as a percentage.

* _Incremental brand load during extraction_: Brand guidelines are now incrementally loaded in the user interface.

* _Simplificatiom of the Copy Guideline schema_: The  `unique attributes` and `frequent keywords` field have been removed from the Copy Guideline schema, simplifying the guideline set-up process.

### Create

* **Multi-section email creation**: Users can now create emails composed of separate headline, image, body, and CTA elements. 

* **Meta Ads Resize**: Creators can resize Meta ad aspect ratios.

### Insights

* **Limited Insights login accounts**: The Insights login now supports only one account per customer.

## Enhancements and fixed issues

This release includes the following additional fixes.

### Insights

* The _Experience Detail_ page feed placement name now specifies Facebook or Instagram feed.

* Cropping of larger images and videos is now consistent when user navigates from the _Asset Overview_ view to the _Asset detail_ view.  

* The Attributes screen search result count no longer displays `0 of` before a user logs in. <!-- GS- 3665 -->

* Clicking the **[!UICONTROL Insight]**  > **[!UICONTROL Asset]** count field no longer clears search and filter settings. <!-- GS-3476 -->

## Known issues

The following known issues will be resolved by the GenStudio for Performance Marketers GA release. 

### Analytics

* Actions triggered by the **[!UICONTROL Add templates]** and **[!UICONTROL Upload]** buttons are not currently tracked. <!-- GS-3505 -->

### Insights

* Videos cannot be played from _Assets_.  <!-- GS-3846 -->

* Users must log in twice when they are also logged in to Facebook. **Workaround**: Log out of Facebook before logging into Insights. 

* **Spend at Campaign level** values are not accurate. Data is not currently consistent between FaceBook Ads Manager and the data lake. <!-- GS-3202 -->

### Reviews and Approvals

* Creators can change assets after approval them before publication. Approvers are not notified of these changes.

