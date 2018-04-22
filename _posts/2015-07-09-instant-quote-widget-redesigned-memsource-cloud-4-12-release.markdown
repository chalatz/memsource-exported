---
author: vaclavb
comments: true
date: 2015-07-09 10:42:26+00:00
layout: post
link: https://www.memsource.com/blog/2015/07/09/instant-quote-widget-redesigned-memsource-cloud-4-12-release/
slug: instant-quote-widget-redesigned-memsource-cloud-4-12-release
title: 'Instant Quote Widget Redesigned: Memsource Cloud 4.12 Release'
wordpress_id: 4292
categories:
- Memsource Blog
tags:
- new release
- Memsource Cloud
---

[![](/wp-content/uploads/2014/04/cloud-logo-221x100-3.png)](http://www.memsource.com/)

Memsource Cloud 4.12 is scheduled for release on Sunday, 12 July 2015 at 9:00 AM GMT. These are some of the most notable improvements:




### Your Services






	
    * We have introduced a brand new section under Setup - Your Services.


	
      * You will be able to define your services, for example "Professional translation" or "Crowdsourcing translation", which you will be able to use with your Instant Quote widgets, in combination with Project Templates. (Only "Professional translation" is available at the moment).<!-- more -->

	
      * Set your Price list to the service

	
      * Add a workflow steps

	
      * You can also set a Buyer, if you plan to use Instant Quote widget for one specific buyer only


	
    * We will continue to improve this feature in our next releases.




<!-- more -->


[![](/wp-content/uploads/2015/07/Service_1-300x184.png)](/wp-content/uploads/2015/07/Service.png)





### Instant Quote Widget Redesigned






	
    * The Instant Quote widget has been redesigned and users should find it more intuitive and simpler.


	
      * Use the new "Your Services" feature to create IQ widget faster

	
      * Use project template as additional information for creating projects

	
      * It will be possible to drag&drop files directly into IQW

	
      * Once a sender's e-mail is verified, there will no longer be a need for the intermediary "approve" step.

	
      * The word counts and prices are displayed before the IQ request is submitted.






 [![](/wp-content/uploads/2015/07/IQW_1-300x183.png)](/wp-content/uploads/2015/07/IQW.png)





### Linguists MUST Change Status to Accepted before Starting to Translate






	
    * **This is an important change that will affect a lot of users and it should be well noted by all Project Managers**

	
    * For the time being, translators can start translating even if they leave the job status as New. In order to make the whole process more transparent, we have implemented the following changes:


	
      * If a job **IS NOT** assigned to any linguist, then any linguist who gets access to the job can edit it. You may therefore distribute a link to the project or send mxliff files to your translators, even without assigning the files to the specific linguists.

	
      * However, if a job **IS** assigned to a linguist, the linguist will only be able to open the job in a "read-only mode" and will not be able to start translating before changing the job status to "Accepted". There are messages and links to guide the linguists to take the necessary action before starting the translation process.




[![](/wp-content/uploads/2015/07/read-only_1.png)](/wp-content/uploads/2015/07/read-only.jpg)


### File Conversion







	
      * **Improvements to New MS Word Filter**


	
        * We introduced a new filter for MS Word files in version 4.11. Based on user feedback and live experience, we have made more improvements to it.


	
          * New option to "Import document properties"






[![](/wp-content/uploads/2015/07/MS_Word_import.png)](/wp-content/uploads/2015/07/MS_Word_import.png)





	
      * **Friendlier Import of MS Excel files**


	
        * For Excel documents, you can now specify which columns contain which data for the translation process. Similar to what is currently available for CSVs, you can now specify the following for Excel files:


	
          * Source text

	
          * Target text (to be replaced with the translation)

	
          * Context note (will be displayed in Memsource Editors as context)

	
          * Maximum length (maximum translation length in characters)






[![](/wp-content/uploads/2015/07/bilingualXLSX.png)](/wp-content/uploads/2015/07/bilingualXLSX.png)





	
      * **New import settings for iOS string format
**


	
        * Additional features:


	
          * use HTML subfilter

	
          * convert to Memsource tags






[![](/wp-content/uploads/2015/07/iOS_String.png)](/wp-content/uploads/2015/07/iOS_String.png)





	
      * **IDML filter improved**


	
        * Cross-reference definitions are now automatically imported for translation.  The definitions are imported as the first segments in bilingual Mxliff file.


	
      * **Bilingual XML filter improved**


	
        * New options added:


	
          * Option "Segment bilingual XML" is now available.


	
        * There was a slight change in the import XPATH settings. The opening slash character is no longer needed (see tooltip at Import Settings)





[![](/wp-content/uploads/2015/07/bilingualXML_1.png)](/wp-content/uploads/2015/07/bilingualXML.png)


### Mobile Friendly







	
      * **Memsource Cloud is now made even more mobile friendly**


	
        *  Memsource Cloud will look better on 5" screens







### New QA Check







	
      * **New QA check added: "Newer version in a preceding workflow step available."**


	
        * The purpose of this new QA check is to give users warnings whenever a segment is by any mistake edited in the previous workflow step after it is edited/confirmed in a later workflow step.







### Miscellaneous







	
      * **New Project / Job  Status**


	
        * We have added a new project status and new Job status: Cancelled.




	
      * **Metadata in TM Export (XLSX)**


	
        * If you export your TM into Excel, it is now possible to choose which metadata you wish to be included in the exported data.




	
      * **New Language: Tibetan**


	
        * We have introduced new language into Memsource: Tibetan (bo).


	
      * **New macro for Email templates**


	
        * **{linguist.email}** can be now added to the CC field of "Job Status Changed" template, so the linguists can have email confirmation of their action.







### API








	
        * **API for Multiple TB Search**


	
          * It is now possible to [search through multiple TBs with one call](http://wiki.memsource.com/wiki/Term_Base_API_v2).




	
        * **API for Listing Deleted Users**


	
          * There is a new API call to list the deleted users.




	
        * **Terminologist Attribute included in API**


	
          * The "Get User" and "Get By User Name" API calls now return the terminologist attribute in the JSON response.







