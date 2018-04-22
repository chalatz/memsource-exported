---
author: admin
comments: true
date: 2013-06-20 13:09:45+00:00
layout: post
link: https://www.memsource.com/blog/2013/06/20/supporting-software-localization-and-more-memsource-cloud-3-4/
slug: supporting-software-localization-and-more-memsource-cloud-3-4
title: 'Supporting Software Localization and More: Memsource Cloud 3.4'
wordpress_id: 1719
categories:
- Memsource Blog
tags:
- new release
- Memsource Cloud
---

Memsource Cloud 3.4 is scheduled for release on Sunday, 23 June at 18:00 GMT. Memsource Cloud 3.4 includes over 100 improvements and bug fixes. Let's have a look at the most important new features:<!-- more -->


### New File Types for Software Localization





	
  * We have added support for a number of file types that are used for software localization

	
    * iOS/Mac Strings

	
    * JSON

	
    * Haiku CatKeys

	
    * SRT

	
    * Skype Language Files

	
    * TS files

	
    * YAML







### MS Office Templates Now Supported





	
  * Microsoft Office template files are now supported

	
    * DOT, DOTX

	
    * POT, POTX

	
    * XLT, XLTX







### A New Option for XLIFF, SDLXLIFF and TTX





	
  * A new option has been introduced for XLIFF, SDLXLIFF, TTX: "Save confirmed segments to TM on import"

	
    * When selected, segments that get imported as confirmed (e.g. in-context matches, signed-off segments, etc.), get automatically saved into the project's TM in the write mode







### Project Management





	
  * Translation progress monitoring

	
    * Progress is now measured as the percentage of characters in confirmed segments

	
    * Previously the percentage was based on the percentage of confirmed segments which was less precise (there can be segments with a lot of text or very little text and that was not taken into account)





[![](/wp-content/uploads/2013/06/chars-conf-300x118.png)](/wp-content/uploads/2013/06/chars-conf.png)



	
  * User-related metadata can now be hidden

	
    * There is a new option under project settings: "User metadata displayed to linguists in Memsource Editor"

	
    * This option is by default selected. If unselected, linguist users will not see any user-related metadata in Memsource Editor

	
    * This feature will work correctly in Memsource Editor 3.114 and above




	
  * Completing jobs with not confirmed locked segments

	
    * Previously, linguists were not able to confirm jobs that were locked and not confirmed. This is possible now.




	
  * Web Editor enabled for linguists (a global setting)

	
    * This setting was previously only possible to set for a specific projects

	
    * Now it is possible to set this option globally and it will affect all new projects




	
  * Email notifications setting

	
    * It is now possible to disable all email notifications for a project

	
    * This can be useful if Memsource is used via API and the customer has their own solution for email notifications




	
  * Memsource Editor version displayed for each user

	
    * When you go to your user list, a new column will be available, titled "Editor Version" that will provide details on the status of Memsource Editor version for each user (never used, very outdated, outdated, OK)

	
    * Please note that you may need to [customize your column settings](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Project_Column_Customization) first in order to have it displayed





[![](/wp-content/uploads/2013/06/editor-version-300x283.png)](/wp-content/uploads/2013/06/editor-version.png)


### Machine Translation





	
  * LetsMT engine now supported

	
    * We have introduced an out-of-the-box support of the LetsMT machine translation engine







### API





	
  * Get character count without TM analysis

	
    * The [Create New Analysis](http://wiki.memsource.com/wiki/Analysis_API_v2#Create_New_Analysis) API has a new parameter _includeTransMemory_ that makes it possible to get just the word/character count without the TM analysis







### Other





	
  * A new credit card payment processor

	
    * We have introduced an additional credit card payment processor that will be used to primarily process credit card transactions when paying for MemSource

	
    * If you had problems with paying via PayPal, you can now try using the new method

	
    * We still keep PayPal for the time being




	
  * Memsource Cloud user interface localization

	
    * Memsource Cloud UI is now available in Czech and Greek, additional languages will be coming soon, as part of the [Memsource community translation effort](/translate-memsource-into-your-language/)





