---
author: admin
comments: true
date: 2014-06-30 16:15:40+00:00
layout: post
link: https://www.memsource.com/blog/2014/06/30/memsource-cloud-4-4-release/
slug: memsource-cloud-4-4-release
title: 'Instant Quote Widget for Your Website: Memsource Cloud 4.4 Released'
wordpress_id: 2473
categories:
- Memsource Blog
tags:
- new release
- Memsource Cloud
---

[![](/wp-content/uploads/2014/04/cloud-logo-221x100-3.png)](http://www.memsource.com/)

Memsource Cloud 4.4 has been released on Sunday, 29 June 2014 at 8:30 AM GMT. Memsource Cloud 4.4 includes over 100 improvements and bug fixes.<!-- more -->


### INSTANT QUOTE WIDGET






	
    * **Job Widget Renamed to Instant Quote Widget**

	
      * We have renamed the _job widget_ to _instant quote widget_, a more of a self-explanatory name we think.

	
      * We have created a dedicated [instant quote widget page](http://wiki.memsource.com/wiki/Instant_Quotes) in our user documentation to better explain its features.




	
    * **Integrate the Widget  into Your Website Using an IFrame**

	
      * It has become very easy to integrate the widget into your website. Simply add the widget's IFrame HTML code. We have done it right here:








	
  * **Appearance**

	
    * The widget's appearance can be easily modified by tweaking its colors, using [CSS color codes](http://www.w3schools.com/cssref/css_colors.asp) or CSS color names, such as _red, green, azure, _etc.

	
    * Webmasters can use an additional library that will make it possible to resize the IFrame (covered in our documentation)





_[![](/wp-content/uploads/2014/06/Quote-Widget-Appearance-300x132.png)](/wp-content/uploads/2014/06/Quote-Widget-Appearance.png)_



	
  * **Default Project Owner**

	
    * It is now possible to set a default project owner for any instant quote widget.

	
    * The default project owner will be receiving all email notifications related to the widget and will also own all projects generated through the widget.




	
  * **Last Used Values Remembered**

	
    * Values that were last entered in the widget such as source language, email address, etc. are remembered so that they do not need to be entered over and over again.




	
  * **Source and Target Languages**

	
    * It is now possible to narrow down the source and target languages that should be displayed in the widget.

	
    * However, the widget user can click a "More..." link to have all languages displayed.




	
  * **Paste Text**

	
    * It is now possible to paste text from clipboard directly into the widget as an alternative to uploading a file for translation.

	
    * Memsource will automatically create a TXT file from the pasted text





[![](/wp-content/uploads/2014/06/Paste-Text-from-Widget-300x128.png)](/wp-content/uploads/2014/06/Paste-Text-from-Widget.png)



	
  * **Note**

	
    * The note field is now displayed also during quote approval, so that any comments can be added when approving the quote.







### PRICE LISTS





	
  * **Minimum Price**

	
    * A minimum price can be set per target language under Setup - Price Lists.

	
    * The minimum price is then reflected in all quotes, including the automatically produced instant quotes.







### ANALYTICS





	
  * **A New Analytics Page**

	
    * We have introduced a new analytics page that can be accessed via Setup - Analytics.

	
    * We plan to expand on the data and chart types that are currently available. Any suggestions welcome at support@memsource.com.





[![](/wp-content/uploads/2014/06/analytics-300x138.png)](/wp-content/uploads/2014/06/analytics.png)


### SHARED PROJECTS





	
  * **New Email Macro**

	
    * We have introduced a new macro for email templates: {buyer.name} in [shared projects](http://wiki.memsource.com/wiki/Sharing#Shared_Projects). An equivalent macro {vendor.name} is already supported.




	
  * **Default Project Owner**

	
    * When an organization acts as vendor, its buyer(s) are listed in a new section Buyers under Setup.

	
    * It is now possible to set a default project owner for each buyer.

	
    * This means that all email notifications related to shared projects of a buyer will be delivered to the vendor organization's default project owner.





[![](/wp-content/uploads/2014/06/Buyers.png)](/wp-content/uploads/2014/06/Buyers.png)


### Context





	
  * **More context available**

	
    * When translating, it is important that translators have access to the context of the translated content. This can be especially critical in software localization.

	
    * Three types of context information have been introduced:

	
      * Context key

	
        * For instance the key in a java properties file

	
        * The context key information is retrieved from source files automatically

	
        * Supported for: chrome json, csv, desktop entry, dtd, joomla ini, json, mac strings, mif, mozilla properties, po, properties, resjson, resx, srt, ts, windowsrc, xliff, xml, yaml




	
      * Context note

	
        * Additional context information

	
        * Can be set by user in file import settings

	
        * Supported for: chrome json, csv, json, mac strings, po, resjson, resx, sbv, srt, ts, windowsrc, xliff, xml, yaml




	
      * Context origin

	
        * Information about the origin of a segment. This context information is retrieved from the source file.

	
        * For instance, this value can be "footer" for a segment originating from the footer of a DOCX source file.

	
        * Supported for: desktop entry, mif, ts, MS Office







	
    * **Important**

	
      * Please note that the context information can be currently viewed only in [Memsource Editor 4.153](http://download.memsource.com/production/updates/memsource-editor/win/archive/install/MemsourceEditor-4.153-windows.exe), which is a pre-release version (context info can be toggled via Ctrl+N). We will soon publish an official release and also plan to start supporting context information in Memsource Web Editor in one of the next releases.










### User Management





	
  * **Automated Linguist Activation and Deactivation**

	
    * When an inactive linguist user is assigned to a job, the user is automatically activated

	
    * When a linguist user sets a job to completed and has no other jobs in progress, the linguist user is deactivated

	
    * This feature will initially only be available in the Ultimate/Biz Ultimate edition, later also in the Team/Biz Team editions.

	
    * To turn this feature on, go to Setup - Access and Security and select "Activate/deactivate linguists automatically."







### File Conversion





	
  * **New CSV file import **settings**:**


[![](/wp-content/uploads/2014/06/CSV-File-Import-Settings2.png)](/wp-content/uploads/2014/06/CSV-File-Import-Settings2.png)



	
  * **New JSON file import settings:**


**[![](/wp-content/uploads/2014/06/JSON-File-Import-Settings.png)](/wp-content/uploads/2014/06/JSON-File-Import-Settings.png)**



	
  * **New YAML **file import **settings**:****


**[![](/wp-content/uploads/2014/06/YAML-File-Import-Settings1.png)](/wp-content/uploads/2014/06/YAML-File-Import-Settings1.png)**



	
  * **New file import option for XLIFF**

	
    * A new file import option has been introduced:

	
      * "Interpret linebreak/pagebreak tags"




	
    * With this option selected, XLIFF linebreak and pagebreak tags will create a new segment





[![](/wp-content/uploads/2014/06/New-XLIFF-File-Import-Setting.png)](/wp-content/uploads/2014/06/New-XLIFF-File-Import-Setting.png)


### Term Base





	
  * **Search  by status**

	
    * It is now possible to search by status in term bases





[![](/wp-content/uploads/2014/06/Search-by-Term-Status.png)](/wp-content/uploads/2014/06/Search-by-Term-Status.png)


### Machine Translation





	
  * **KantanMT**

	
    * Memsource connector to KantanMT modified a bit to better respond to the situations when KantanMT initializes and does not provide any translations yet




	
  * **Asia Online**

	
    * A new project number field has been added to the Asia Online configuration settings in Memsource





