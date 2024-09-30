---
title: Adobe GenStudio for Performance Marketing Beta release notes
description: Learn about the latest features and enhancements to Adobe GenStudio for Performance Marketing.
exl-id: 2ae60dcb-ac95-4ed4-bceb-84b396f7fa4e
---
# Adobe GenStudio for Performance Marketing Beta release notes

These notes highlight significant Adobe GenStudio for Performance Marketing fixes and enhancements for the week ending September 27.

## New features and enhancements

* GenStudio can now extract persona and product information from an uploaded PDF and populate related fields. <!-- GS-3806 -->

* Users can now filter [!DNL Content] assets and experiences by the name of the user who uploaded the asset. <!-- GS-1808 --> 

* Renamed the [!DNL Additional details] section to [!DNL Messaging preferences] in the [!DNL Products] detail page. <!-- GS-5133 5134 -->

* Added an [!DNL Add persona] button to the _Add your first persona_ page. <!-- GS-5132 -->

## Known issues

The following known issues are scheduled for resolution in the GenStudio for Performance Marketing GA release.

* Templates can be uploaded but not seen. **Workaround**: Upload an asset with the **[!UICONTROL Campaigns]** field populated. Then, upload the template again. <!-- GS-4815 5650--> 

* Users cannot manually crop Meta ads after resizing them. <!-- GS-5871 --> 

* Users must log in twice to a channel Meta ads account when they are also logged in to Facebook. Workaround: Log out of Facebook before logging into a channel Meta ads account. <!-- GS-3009 --> 

### Additional enhancements and fixed issues

* Intermittent latency issues with some [!DNL Create] Canvas operations have been resolved. <!-- GS-5203 -->

* Users no longer need to log in twice to a channel Meta ads account when they are also logged in to Facebook. <!-- GS-4806 -->

* Email generation now longer results in an incomplete email. <!-- GS-5209 -->

* Creating a campaign in the template workflow now stores IDs as expected.  <!-- GS-4923 -->

* The multi-repository selector now lists repositories in alphabetical order. <!-- GS-5553 -->

* Issues with CSV export file formats for non-English languages have been resolved. <!-- GS-5141 -->

* Users can now click the [!DNL Create] _Recent work_ area **[!UICONTROL View all drafts]** button  while drafts are loading. Previously, clicking this button before all drafts had loaded resulted in only a few drafts being loaded, and the **[!UICONTROL View all drafts]** button became unavailable. <!-- GS-3938 -->

* The [!DNL Create] Canvas now displays the **[!UICONTROL View all drafts]** button as expected when the Canvas displays more than four drafts. <!-- GS-5588 -->

* Search now works as expected in the _Attributes_ tab. <!-- GS-5658 -->

* Shimmer animation is now scaled properly during experience loading. <!-- GS-5574 -->

* Thumbnail previews for multi-part emails now render as expected in [!DNL Content]. <!-- GS-5258 -->

* Corrected a Workfront-related issue with the **[!UICONTROL Send for approval]** button. <!-- GS-5847 -->

* Corrected issues with loading shimmer on the [!DNL Create] Recent work view. <!-- GS-5589 -->

* Entering a search term now results in only one search call as expected.  <!-- GS-2999 -->

* Corrected image rendering of Meta ad-generated images after export. <!-- GS-5749 -->

* The `%` symbol is now rendered correctly in DEU, FRA and ESP locales when users zoom in or zoom out of email variants in the C[!DNL Create] Canvas. <!-- GS-5007 -->

#### Localization

This release includes improvements to localization throughout the product interface, especially throughout [!DNL Create]. The following interface components have been localized: <!-- GS-5295 -->

* All strings in the _Prompt_ area (Parameters title, dropdown-menu option names, and prompt placeholder text) <!-- GS-5027 -->

* All strings in the _Resize_ window for generated Meta ads in [!DNL Create] <!-- GS-5035 -->

* All strings in the _Recent work_ area in [!DNL Create] <!-- GS-5037 -->

* The Brands, Personas, and Product dropdown menu option strings in the Prompt area <!-- GS-5293 -->

* The **Zoom to fit to screen** string displayed during email and Meta ad generation <!-- GS-5063 -->

* Date and time formats, **Untitled Draft** string, and error messages in Email and Meta ads names <!-- GS-5023 5022 5048-->

* The [!DNL Content] _Assets_ tab gallery view strings and percentage symbol (%)  <!-- GS-4983 4984-->

* The percentage symbol (%) used in the Insights > Experiences click-through rate <!-- GS-4279 -->

* Error message displayed when a system error occurs during email or Meta ads creation<!-- GS-5061 -->

* Decimal separator for the "Word Count Per Sentence"  phrase on the Insights Experience details page <!-- GS-4986 -->

* Strings in the Export menu for a Meta ad generated with a template. <!-- GS-5031 -->

