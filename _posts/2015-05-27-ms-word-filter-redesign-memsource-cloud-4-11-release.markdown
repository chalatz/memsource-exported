---
author: admin
comments: true
date: 2015-05-27 14:16:26+00:00
layout: post
link: https://www.memsource.com/blog/2015/05/27/ms-word-filter-redesign-memsource-cloud-4-11-release/
slug: ms-word-filter-redesign-memsource-cloud-4-11-release
title: 'MS Word Filter Redesign: Memsource Cloud 4.11 Release'
wordpress_id: 4025
categories:
- New Features
tags:
- new release
- Memsource Cloud
---

[![](/wp-content/uploads/2014/04/cloud-logo-221x100-3.png)](http://www.memsource.com/)

Memsource Cloud 4.11 is scheduled for release on Sunday, 31 May 2015 at 9:00 AM GMT. <!-- more --> These are some of the most notable improvements:


### File Conversion





	
  * **MS Word Filter Redesign**


	
    * We have completely redesigned our MS Word file filter which is the most popular file type used in Memsource Cloud (and probably in the translation industry in general) and so this is a big change.

	
    * The new filter is better and faster. Here are some of the improvements:


	
      * Footnotes and comments are now displayed right below the "parent" segment (the segment to which they are related to). Previously, they were displayed at the end of the bilingual file for translation.

	
      * Special fields with automatic update and tables of content are now automatically updated in the completed target MS Word file.

	
      * Formatting tags are expandable and editable.




[![](/wp-content/uploads/2015/05/Expandable-tags-in-MS-Word1.png)](/wp-content/uploads/2015/05/Expandable-tags-in-MS-Word1.png)





	
      * Changes in tag order (target tags need to be ordered differently from source tags) are handled much better.

	
      * RTL text mixed with LTR is handled much better.


	
    * New File Import Options:


	
      * Import hyperlink target (select when there are tags that include a hyperlink and the hyperlink needs to be edited).

	
      * Minimize number of tags (select for e.g. scanned documents with excess formatting).

	
      * Target font (select a font in which the completed target file should be exported).

	
      * Convert to Memsource tags (convert arbitrary text to Memsource tags using regexp).




[![](/wp-content/uploads/2015/05/MS-Word-File-Import-Settings.png)](/wp-content/uploads/2015/05/MS-Word-File-Import-Settings.png)



	
  * **Tracking/Kerning Support for Adobe InDesign**


	
    * We have introduced two new file import options for Adobe InDesign files:


	
      * Keep kerning

	
      * Keep tracking




[![](/wp-content/uploads/2015/05/Keep-Kerning-and-Tracking1-300x271.png)](/wp-content/uploads/2015/05/Keep-Kerning-and-Tracking1.png)



	
  * **Improved \n tags handling in .PO **gettext **files**


	
    * We have introduced a new file import option for .PO files:


	
      * Export multi-line strings


	
    * This option is selected by default and improves handling .PO files with \n tags



[![](/wp-content/uploads/2015/05/PO-gettext-Export-Multiline-Strings-300x127.png)](/wp-content/uploads/2015/05/PO-gettext-Export-Multiline-Strings.png)


### Quality Assurance





	
  * **Checking "No Text between Tags" for XLIFF Files**


	
    * Our current QA check "No Text between Tags" has been extended to also cover a situation when there is no text between bpt and ept tags in XLIFF files


	
  * **Checking Line Breaks**


	
    * The current "Tags & Formatting" check has been extended to also check for missing or redundant line breaks between source and target.





### Machine Translation





	
  * **Introducing CrossLang**


	
    * We are introducing CrossLang as one of the out-of-the-box MT connectors available in Memsource.

	
    * CrossLang is really a proxy that can provide access to multiple MT engines (custom, generic, etc.).


	
  * **Microsoft with Feedback**


	
    * [Microsoft with Feedback](http://wiki.memsource.com/wiki/Microsoft_Translator#Microsoft_Translator_with_Feedback_.28free.29), the free MT that comes with Memsource, continues to be available free of charge. However, it is not available for batch pre-translation anymore (to pre-translate a file in one go via the Pre-translate menu in Memsource Cloud).

	
    * It continues to be available in Memsource Editor and Memsource Web Editor for segment-per-segment pre-translation.

	
    * We think that [pre-translating files in advance](http://support.memsource.com/topic/should-we-always-pre-translate-a-file-before-a-translator-starts-translating-it) is typically not the best practice. However, if this approach is needed, any of the [commercial MT engines](http://wiki.memsource.com/wiki/Machine_Translation) can be used of course.





### Security





	
  * **Login History**


	
    * Administrators and project managers can now view and/or download 3 months of login history for all users.

	
    * Login history is available from the Users page and by customizing the displayed columns via [this icon](http://wiki.memsource.com/images/e/e1/Customize-columns.png) at the top right of the page and selecting Login History.

	
    * This information that gets logged for each user looks like this:



[![](/wp-content/uploads/2015/05/Login-History-300x158.png)](/wp-content/uploads/2015/05/Login-History.png)



	
  * **Forwarding to HTTPS for Custom Domains**


	
    * Organizations that use their own custom domain to login to Memsource Cloud can select to always forward their traffic to the encrypted HTTPS (just like in the standard Memsource Cloud scenario).

	
    * This feature is of course only useful for those organizations that use an HTTPS domain. To activate this feature, please contact Memsource Support.





### API





	
  * **Introducing Callbacks**


	
    * We have introduced callbacks as an alternative to the currently available polling for our API asynchronous requests.

	
    * The callback method brings a number of advantages:


	
      * Reduction of complexity for 3rd party integrators.

	
      * Compliance with the SOA pattern of "fire and forget."

	
      * Better scalability.


	
    * This is how it works:


	
      * API customers provide a callback_url.

	
      * A queue/consumer pattern is used.

	
      * As soon as a Memsource async worker finishes its work, it adds its async_id into the queue.

	
      * The consumer grabs the async_id messages from the queue.

	
      * The consumer retrieves the work related with the async_id (via directly accessing data storage or by making an http call).

	
      * The payload is prepared and sent to the customer's callback_url.






### Miscellaneous





	
  * **Memsource UI in Turkish**


	
    * Memsource Cloud UI is now also available in Turkish, as part of the Memsource crowdsourced localization project.

	
    * Big thanks to the students of the [Yeni Yuzyil University](http://www.yeniyuzyil.edu.tr/) for their contribution.



[![](/wp-content/uploads/2015/05/Memsource-Cloud-UI-in-Turkish1-300x183.png)](/wp-content/uploads/2015/05/Memsource-Cloud-UI-in-Turkish1.png)



	
  * **New Language: Papiamento**


	
    * We have introduced new language into Memsource: Papiamento (pap), spoken on the Caribbean ABC islands.



