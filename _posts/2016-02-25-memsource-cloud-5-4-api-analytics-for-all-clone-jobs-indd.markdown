---
author: admin
comments: true
date: 2016-02-25 17:17:54+00:00
layout: post
link: https://www.memsource.com/blog/2016/02/25/memsource-cloud-5-4-api-analytics-for-all-clone-jobs-indd/
slug: memsource-cloud-5-4-api-analytics-for-all-clone-jobs-indd
title: 'Memsource Cloud 5.4: API & Analytics for All, Clone Jobs, INDD'
wordpress_id: 5855
categories:
- Memsource Blog
tags:
- new release
- Memsource Cloud
---

Memsource Cloud 5.4 is scheduled for release on Sunday, 28 February 2016, at 11:00 AM GMT. This release is literally packed with new features including some major improvements. We are extending Memsource API support to all of our customers. And the recently introduced business analytics features will now also be available for our translation agency customers.<!-- more -->


### API for All Customers


**We are extending our API to all of our customers.**



	
  * [Memsource API](http://wiki.memsource.com/wiki/Memsource_API) is necessary to integrate Memsource with any 3rd-party software. Previously, API was only available to our Ultimate and BIZ Ultimate editions customers. We are now extending the API to all paying customers (this excludes the free Personal edition).

	
  * The Ultimate and BIZ Ultimate editions will continue to offer unlimited API calls to its subscribers. All other editions will enjoy full API functionality but with a daily limit on API calls which we will start enforcing during March 2016:


<table width="334" >
<tbody >
<tr >

<td width="203" >Edition
</td>

<td width="131" >Max. API Calls Daily
</td>
</tr>
<tr >

<td >Ultimate & BIZ Ultimate
</td>

<td >Unlimited
</td>
</tr>
<tr >

<td >Team & BIZ Team
</td>

<td >2000
</td>
</tr>
<tr >

<td >Team Start & BIZ Start
</td>

<td >1000
</td>
</tr>
<tr >

<td >Freelancer
</td>

<td >500
</td>
</tr>
<tr >

<td >Personal
</td>

<td >0
</td>
</tr>
</tbody>
</table>


### Clone Jobs


**Cloning jobs can prove extremely useful for multilingual projects.**

Typically for large projects with multiple target languages, it may make a lot of sense to prep the translation jobs before they are assigned to linguists. This may include modifications that will be identical in all target languages. It is quite tedious for project managers to have to apply the same modifications job by job for all the target languages. For instance, copy source to target for segments with non-translatable content. Or, lock some segments because they should not be touched, etc.

With the new _clone_ feature, jobs can be prepped in just a single target language and then cloned to any number of the project's target languages.

[![Clone jobs](/wp-content/uploads/2016/02/Clone-jobs.png)](/wp-content/uploads/2016/02/Clone-jobs.png)


### INDD Supported


**Native Adobe InDesign files (INDD) are now supported.**

We have supported IDML, the translation-friendly Adobe InDesign file format, for a long time. However, not the Adobe InDesign's native INDD format. It is always possible to convert INDD into IDML or ask your customer to provide IDML. However, it adds an extra step.

We have started supporting INDD directly in Memsource. Thanks to our partnership with [Frontlab](http://www.frontlab.com/), this feature is available for everyone in Memsource.

How it works exactly: Simply select the INDD file when creating a new translation job, it will be converted into IDML in the background and the new job will be created using the IDML file. When you are done with the translation, you will receive IDML as the output target file (not INDD - as this would be unnecessary). The translated IDML can then be directly imported into Adobe InDesign.


### Business Analytics for Translation Agencies


**We have recently completely redesigned our business analytics component and introduced the first set of analytics features in our previous release, [Memsource Cloud 5.3](/memsource-cloud-5-3-multilingual-excel-analytics-indesign-preview/) (and just for our enterprise customers). We are now extending business analytics also to our translation agency customers on the Team and Ultimate editions.**

To start with, we are now releasing a set of pre-configured charts that can be set up in the new Home page. The business analytics functionality will be significantly extended in our next releases.[![Languages and File Types Analytics](/wp-content/uploads/2016/01/Languages-and-File-Types-Analytics.png)](/wp-content/uploads/2016/01/Languages-and-File-Types-Analytics.png)


### Home Page for Translation Agencies


**The Home page is a new dashboard-like page with customizable widgets. It has been introduced in our previous release, [Memsource Cloud 5.3](/memsource-cloud-5-3-multilingual-excel-analytics-indesign-preview/), just for our enterprise customers. We are now making it available also to our translation agency customers.**

Currently, analytics and [automation widgets](http://wiki.memsource.com/wiki/Automation_Widget) can be added to the page. The Home page is available in our Team and Ultimate editions and all enterprise editions.

[![Home page](/wp-content/uploads/2016/01/Home-page2.png)](/wp-content/uploads/2016/01/Home-page2.png)


### Project Management


**Pre-translate on job creation.**

The project's pre-translate settings have received a new option: _Pre-translate on job creation. _When enabled, every new job will be pre-translated automatically, based on the project's pre-translate settings.

This new option can be very well used also in project templates and [automation widgets](http://wiki.memsource.com/wiki/Automation_Widget), associated with those templates.

![Pre-translate on job creation](/wp-content/uploads/2016/02/Pre-translate-on-job-creation.png)

**Entering a pool of linguists and/or vendors into a project template.**

In one of our previous releases, [Memsource Cloud 5.0](/more-automation-memsource-cloud-5-0/), we made it possible for project managers to assign jobs to a pool of [linguists](http://wiki.memsource.com/wiki/Memsource_Cloud_User_Manual#Linguists) or [vendors](http://wiki.memsource.com/wiki/Sharing#Vendor), order them by priority and let them be notified automatically by Memsource in the selected time interval. The first linguist available would be able to claim the job.

We are now bringing this exact same feature also to project templates which opens up a number of additional automation scenarios. For instance, creating an [automation widget](http://wiki.memsource.com/wiki/Automation_Widget), associating a project template with a pool of linguists/vendors and letting the translation automation flow...

![Assign Jobs to a Pool of Linguists](/wp-content/uploads/2015/09/Assign-Jobs-to-a-Pool-of-Linguists.png)

**Linguist relevancy data.**

Relevancy data for linguists can be entered already in the user creation page.

**Original file extension added to MXLIFF.**

Our MXLIFF files now include the file extension of the original source file which should help project managers for better orientation, especially when dealing with lots of files.



	
  * Previously: ABC.mxliff

	
  * Now: ABC.docx.mxliff


**Set net rate schemes by workflow steps.**

It is now possible to set specific net rate schemes for each workflow step. For instance, a different net rate scheme for translation and revision.

**New language added.**

We have added _Russian (Estonia)_ to our list of supported languages.

**New Memsource Cloud default url.**

Memsource Cloud has a new default url: cloud.memsource.com (previously cloud1.memsource.com).


### File Conversion


**Multiple columns for translation in multilingual MS Excel.**

It is now possible to enter multiple columns for translation, e.g.



	
  * Source - A,B,C

	
  * Target(de) - G,H,I

	
  * Target(cs) - J,K,L


There is also a new file import option that makes it possible to import specific rows only. Entering _2- _will import all rows except the first row:

[![MS Excel Import Specific Rows Only](/wp-content/uploads/2016/02/MS-Excel-Import-Specific-Rows-Only.png)](/wp-content/uploads/2016/02/MS-Excel-Import-Specific-Rows-Only.png)

**A new file import setting allowing to specify a context key.**

It is now possible to select the location of a key in a file for translation which will then be displayed to linguists during translation in order to provide more context information. Newly available for these file types:



	
  * XML

	
  * Multilingual XML

	
  * Multilingual Excel

	
  * CSV.


**Improved handling of index markers in FrameMaker.**

We have started placing index markers following the paragraph where they were used in order to separate them better from the translatable text. This should be more translator-friendly.

**New HTML file import option: Translatable meta tags.**

We have introduced a new file import option for HTML files which relates to translatable content in the meta section of HTML files. Previously, Memsource would only import _description _and _keywords _for translation. Now it is possible to specify (using a regular expression) what content should be imported from the HTML meta section.

[![Translatable meta tags](/wp-content/uploads/2016/02/Translatable-meta-tags.png)](/wp-content/uploads/2016/02/Translatable-meta-tags.png)

**Identify translatable text in text files using a regular expression.**

We have introduced a new option, _Translatable text_, that makes it possible to extract just translatable text in plain text files using a regular expression.

**Maximum target segment length for JSON.**

A new file import option, _Max. target length_, makes it possible to restrict maximum target length for JSON files.

**XLIFF 2.0 improvements.**

We have introduced a number of improvements to our XLIFF 2.0 handling:



	
  * Standalone file import settings for XLIFF 2.0 (previously the settings were shared with XLIFF 1.2).

	
  * srcLang and trgLang attribute support.

	
  * Better handling of translatable content in nested elements.

	
  * Better file-validation check when exporting a completed target file (to check whether the XLIFF file conforms to the XLIFF standard).


**Chaining context note parameters for XML files.**

Multiple parameters can be chained and entered into the _context note _field in XPath file import settings for XML files. For instance:



	
  * @comment|@refId|@note


**New file import settings for Multilingual XML files.**

We have added new XPath file import settings for multilingual XML files:



	
  * Context key.

	
  * Context note.

	
  * Max. target length.


[![New Multilingual XML File Import Options](/wp-content/uploads/2016/02/New-Multilingual-XML-File-Import-Options.png)](/wp-content/uploads/2016/02/New-Multilingual-XML-File-Import-Options.png)

**Conditional text from Adobe InDesign files extracted.**

Conditional text is now extracted for translation from Adobe InDesign files.


### Translation Memory


**Segments can now be saved to two translation memories in a project.**

Previously, we only supported a single translation memory to be set up in the "write" mode in a project (the TM into which segments are saved when they are confirmed). From now on, it is possible to select the write mode for up to two translation memories in a project.

This means that we now support up to 2 TMs in the write mode and up to 10 TMs in the read mode.

**Navigating search results from TMs with multiple languages got much easier.**

Viewing TM search results from within Memsource Cloud got a bit more user-friendly, especially for TMs with multiple target languages thanks to a few UI tweaks we have deployed. And by the way, it is possible to drag-and-drop each language column in the TM results page to re-order the languages for better viewing.

[![Translation memory viewing](/wp-content/uploads/2016/02/Translation-memory-viewing1.png)](/wp-content/uploads/2016/02/Translation-memory-viewing1.png)


### API


**New API call to list users by email address.**



	
  * [api/v2/user/list](http://wiki.memsource.com/wiki/User_API_v2#List_Users)


**New API call to clone projects.**



	
  * [api/v3/project/clone](http://wiki.memsource.com/wiki/Project_API_v3#Clone_Project)


**New API call to clear all translation memory segments.**



	
  * [api/v4/transMemory/clear](http://wiki.memsource.com/wiki/Translation_Memory_API_v4#Delete_Translation_Memory) (be careful, this action cannot be reverted!)


