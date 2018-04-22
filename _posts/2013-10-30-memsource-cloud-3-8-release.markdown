---
author: admin
comments: true
date: 2013-10-30 11:22:11+00:00
layout: post
link: https://www.memsource.com/blog/2013/10/30/memsource-cloud-3-8-release/
slug: memsource-cloud-3-8-release
title: Memsource Cloud 3.8 Released
wordpress_id: 1958
categories:
- Memsource Blog
- New Features
tags:
- new release
- Memsource Cloud
---

[![](/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png)](http://www.memsource.com/)

Memsource Cloud 3.8 has been released on Sunday, 3 November 2013 at 11:15 AM GMT. Memsource Cloud 3.8 includes over 100 improvements and bug fixes. These are the most important new features:<!-- more -->


### Project Management





	
  * Job dashboard

	
    * The job dashboard provides an overview of the statuses of a project's jobs. It is displayed for projects 2 and more jobs and is minimized by default.





[![](/wp-content/uploads/2013/10/Dashboard-cursor-300x248.png)](/wp-content/uploads/2013/10/Dashboard-cursor.png)



	
  * Project sections minimization

	
    * All sections (jobs, analyses, TMs, TBs...) in a project page can be minimized/maximized by clicking on the section's title.




	
  * Jobs in progress

	
    * A new field "Jobs in Progress" has been added to the user detail page. It displays the same information that has been available already in the user list page (under "Jobs").




	
  * Job status filtering

	
    * It is now possible to select multiple job statuses when filtering jobs in a project




	
  * Projects filtering by language

	
    * Projects can now be [filtered](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Project_Filter) by source and/or target language




	
  * Which term base for QA

	
    * It is now possible to select against which term base(s) quality assurance should be launched in a project

	
    * This can prevent a lot of noise during QA, by not selecting term bases that are not sufficiently specific for example





[![](/wp-content/uploads/2013/10/QA-for-TB-300x213.png)](/wp-content/uploads/2013/10/QA-for-TB.png)



	
  * German is now available as another language  in Memsource Cloud user interface, thanks to our German localization partner [zappmedia](http://www.zappmedia.de/).

	
  * Pre-translating locked segments

	
    * The pre-translate feature available from within Memsource Cloud used to override locked segments. Now, locked segments are left intact.




	
  * New languages

	
    * We have added support for Sami North and Sami Lule




	
  * Linguist users with an outdated version of Memsource Editor will be notified


[![](/wp-content/uploads/2013/10/new-editor-300x59.png)](/wp-content/uploads/2013/10/new-editor.png)


### Data Storage





	
  * [Data storage policy](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Data_Storage) updated

	
    * We have already announced some changes to our data storage policy with our previous release. We have added some more options now and also postponed the start of old project deletion

	
    * As of 5 February 2014, Memsource system will start deleting projects that are older than 1 year

	
    * Users will be able to postpone (even repeatedly) the project deletion date for selected projects





[![](/wp-content/uploads/2013/10/Postpone-300x86.png)](/wp-content/uploads/2013/10/Postpone.png)




	
    * Users will also be able to purchase extra project lifetime when subscribing



[![](/wp-content/uploads/2013/10/extra-storage-300x298.png)](/wp-content/uploads/2013/10/extra-storage.png)


### Pricing





	
  * Adjustment of our pricing in US dollars

	
    * The US dollar has been trading at a [two-year low](http://www.bloomberg.com/news/2013-10-23/dollar-trades-near-2-week-low-versus-yen-as-yield-gap-narrows.html) for some time now and the gap between our euro and dollar pricing has become too wide. Therefore, we will be increasing our US dollar pricing slightly as of 1 November 2013. For instance, the [Team edition](http://wiki.memsource.com/wiki/Edition_comparison#Team_Edition) will cost $180 instead of $170 monthly per project manager. Our euro prices remain unchanged




	
  * Add users/upgrade online

	
    * It is now possible to add users and/or upgrade one's Memsource edition directly through Memsource Cloud, without contacting Memsource support. Just click on the "Add users or upgrade edition" link under Setup in Memsource Cloud







### Compatibility





	
  * Memsource Editor

	
    * Memsource Editor 3.132 or higher should be used with Memsource Cloud 3.8. Download and install now.







### Integrations





	
  * Plunet and XTRF

	
    * Both Plunet and XTRF have introduced API-driven integration starting with Memsource Cloud 3.8.







### Term Base





	
  * Term metadata tooltip

	
    * We have introduced a metadata tooltip that displays term metadata when browsing through a Memsource Cloud term base.




	
  * TBX metadata mapping

	
    * When importing terminology from a 3rd-party tool, such as MultiTerm, critical metadata such as timestamps, notes "note" and usage notes "usageNote" get now automatically mapped to the corresponding fields in MemSource







### Aligner





	
  * Custom segmentation

	
    * It is now possible to select custom segmentation rules when [aligning files](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Align).







### Machine Translation





	
  * KantanMT

	
    * Memsource now supports [KantanMT](http://wiki.memsource.com/wiki/Machine_Translation#KantanMT) out of the box







### File Conversion





	
  * InDesign and locked layers

	
    * The InDesign filter does not process locked layers by default ("Extract locked layers").




	
  * We have redesigned our XLIFF and HTML filters to be able to provide more advanced functionality

	
    * For instance, we will be able to support the localization functionality of HTML5 and also introduce the support of XLIFF 2.0 more rapidly







### Documentation





	
  * List of editor hotkeys

	
    * We have created a page with a [comprehensive list of hotkeys](http://wiki.memsource.com/wiki/Keyboard_Shortcuts) of both Memsource Editor and Memsource Web Editor







### API





	
  * Changes in how QA is applied to term bases in a project

	
    * QA must be specifically selected for a term base in project if QA is to be run against that term base

	
    * Use the qualityAssuranceTermBase parameter in the project/setTermBases API call to do this




	
  * Delete analysis

	
    * A new API call has been introduced: [analyse/delete](http://wiki.memsource.com/wiki/Analysis_API_v2#Delete_Analysis).




	
  * QA-related info

	
    * More QA-related info is available for jobs via [job/getSegmentsCount](http://wiki.memsource.com/wiki/Job_API_v3#Get_Segments_Count_.28.22Get_Progress.22.29).




	
  * Search term base

	
    * A new call that allows searching a term base has been introduced: [termBase/search](http://wiki.memsource.com/wiki/Term_Base_API_v2#Search)




	
  * Translation memory search API expanded

	
    * [transMemory/search](http://wiki.memsource.com/wiki/Translation_Memory_API_v4#Search) now supports additional parameters, such as previousSegment and nextSegment. Thanks to these improvements, in-context matches are now supported in the API.




	
  * Insert into translation memory

	
    * [transMemory/insert](http://wiki.memsource.com/wiki/Translation_Memory_API_v4#Insert) is a new API call that we have introduced




	
  * New option in QA settings

	
    * strictJobStatus is a new parameter that makes it possible to enforce the resolution of all QA warnings by linguists

	
    * When true, linguists may not set jobs with unresolved QA warnings to Completed





