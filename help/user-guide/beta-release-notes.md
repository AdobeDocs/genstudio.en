---
title: Adobe GenStudio for Performance Marketers beta release notes
description: Learn about the latest feature introductions and enhancements to Adobe GenStudio.
---

# Adobe GenStudio for Performance Marketers beta release notes

These notes highlights significant Adobe GenStudio fixes and enhancements for the week ending August 16.

## Highlights

GenStudio feature development is rapid and continuous. Notable new features include:

### Brand

**Brand validation panel enhancements**. The Brand validation panel has been enhanced to improve user experience, including these changes: 

   * _Percentage-based validation score_. Brand validation now displays brand validation score as a percentage rather than a pass/fail value. 

   * _Updated Brand extraction interface_. Brand extraction now shows completion of the extraction process as a percentage.

   * _Incremental brand load during extraction_. Brand guidelines are now incrementally loaded in the user interface.

   * _Simplificatiom of the Copy Guideline schema_. The  `unique attributes` and `frequent keywords` field have been removed from the Copy Guideline schema, simplifying the guideline set-up process.

   * _Image Generation: Category Selection_. Users can now select the image guidelines that are specific to their image regeneration needs.

### Create

* **Multi-section email creation**. Users can now create emails composed of separate headline, image, body, and CTA elements. 

* **Meta Ads Resize**. Creators can resize a Meta ad aspect ratios.

### Insights

* **Limited Insights login accounts**. The Insights login now supports only one account per customer.

## Enhancements and fixed issues

This release includes the following additional fixes.

### Insights

* The _Experience Detail_ page feed placement name now specifies Facebook or Instagram feed.

* Cropping of larger images and videos is now consistent when user navigates from the _Asset Overview_ page to the _Asset detail_ page.  

* The Attributes screen search result count no longer displays `0 of` before a user logs in. <!-- GS- 3665 -->

* Clicking on the **[!UICONTROL Insight]**  > **[!UICONTROL Asset]** count field no longer clears search and filter settings. <!-- GS-3476 -->

## Known issues

The following known issues will be resolved by the GenStudio GA release. 

## Analytics

* Actions triggered by the **[!UICONTROL Add templates]** and **[!UICONTROL Upload]** buttons are not currently tracked. <!-- GS-3505 -->

### Brand

* A creator can successfully publish a brand, but organization members cannot see the brand. <!-- XI-2197 -->

### Create

* Image cropping in Meta ads is inconsistent. <!-- GS-3739 -->

* Templates composed of multiple groups of page elements fail brand validation. <!-- GS-4037 --> 

### Insights

* Access denied errors occur with `/admin/addOffer` endpoint (provisioning service). **Resolved  8/12**. <!-- GS-4047 -->

* **Spend at Campaign level** values are not accurate. Data is not currently consistent between FaceBook Ads Manager and the data lake. <!-- GS-3202 -->

### Reviews and Approvals

* Creators can change assets after approval before publishing it. Approvers are not notified of these changes.
