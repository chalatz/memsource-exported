---
author: admin
comments: true
date: 2013-08-16 12:59:27+00:00
layout: post
link: https://www.memsource.com/blog/2013/08/16/aligner-and-more-memsource-cloud-3-6-release/
slug: aligner-and-more-memsource-cloud-3-6-release
title: 'Aligner and More: Memsource Cloud 3.6 Released'
wordpress_id: 1805
categories:
- Memsource Blog
tags:
- new release
- Memsource Cloud
---

[![](/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png)](http://www.memsource.com/)

Memsource Cloud 3.6 has been released on Sunday, 18 August 2013 at 8:30 AM GMT. Memsource Cloud 3.6 includes over 100 improvements and bug fixes. These are the most important new features:<!-- more -->


### Aligner





	
  * With this release we are introducing a much-requested feature: an [alignment](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Align) functionality that makes it possible to create a translation memory from a translation (and its original) that was not processed through a CAT tool

	
  * To use this feature is simple:

	
    * Click on the [align button](http://wiki.memsource.com/images/7/72/Align-button.png) (located in every translation memory page) and import the 2 files (original and translation) for alignment

	
    * A XLSX file will get created with two columns (segments in source and target language)

	
    * You can edit it if needed and then [import the XLSX file directly into a translation memory](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#XLS_Import)





[![](/wp-content/uploads/2013/08/align-button-300x264.png)](/wp-content/uploads/2013/08/align-button.png)


### Project Management





	
  * Memsource Cloud UI is also in Spanish now

	
    * Localization provided with the generous support of [Precisa Traduciones](http://www.precisatraducciones.com/en/), based in Mexico




	
  * New user detail page

	
    * We have introduced a new user detail page that, among other things, lists 30 most recent jobs assigned to the user




	
  * Delete all translations

	
    * The feature "Delete All Translations" will now delete all translation except locked segments




	
  * Filter by status in preceding workflow step

	
    * It is now possible to filter jobs by whether they are completed or not in the preceding workflow step





[![](/wp-content/uploads/2013/08/preceding-stepc-300x106.png)](/wp-content/uploads/2013/08/preceding-stepc.png)


### Translation Memory





	
  * Automated tag renumbering for higher leverage

	
    * For 99% TM matches because of different tag numbers from the segment for translation, we will automatically renumber the tags on the fly, so that the user gets a 100% match (in an analysis, TM search, pre-translation - simply everywhere).

	
    * For example, if your segment for translation is _{1}Good {2}morning_ and the TM match is _{2}Good {3}morning_, you will get a 100% match now and will in fact see already the renumbered segment in TM results.




	
  * Export TM as XLSX, edit it and re-import it back

	
    * Translation memories can now be [exported as XLSX](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Export_XLSX), edited in MS Excel or similar application and [re-imported back](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#XLS_Import_with_IDs) into MemSource

	
    * Memsource will update records that have been changed




	
  * Export only selected target languages

	
    * It is now possible to select which target languages should be exported for multilingual TMs





[![](/wp-content/uploads/2013/08/export-tm1.png)](/wp-content/uploads/2013/08/export-tm1.png)


### File Conversion





	
  * Improvement of HTML subfilter for XML files

	
    * When XML includes some HTML content, the HTML content can be processed by a HTML subfilter

	
    * Now it is possible to use the [HTML file filter settings](http://wiki.memsource.com/wiki/HTML) when creating a new job to customize the HTML subfilter




	
  * XLIFF segmentation optional

	
    * Previously, XLIFF files got segmented by default. Now there is an option that makes this optional




	
  * Non-translatable inline elements in XML

	
    * We have split the previous [XML](http://wiki.memsource.com/wiki/XML) file import option  "Inline elements" into "Translatable inline elements" and "Non-translatable inline elements"







### Machine Translation





	
  * NICT MT engine

	
    * Memsource now supports the [NICT MT engine](http://wiki.memsource.com/wiki/Machine_Translation#NICT) out of the box







### API





	
  * Download analysis as CSV/LOG file

	
    * A new API call [analyse/download](http://wiki.memsource.com/wiki/Analysis_API_v2#Download_Analysis) makes it possible to download the analysis files

	
    * However, if you need to get the analysis in a machine-readable format, the JSON response may still be your best option, via [analyse/get](http://wiki.memsource.com/wiki/Analysis_API_v2#Get_Analysis)




	
  * Get analysis

	
    * A new API call [analyse/get](http://wiki.memsource.com/wiki/Analysis_API_v2#Get_Analysis) makes it possible to get analysis results from an existing analysis (without the need to launch a new analysis)




	
  * Edit project

	
    * We have introduced a new API call [project/edit](http://wiki.memsource.com/wiki/Project_API_v3#Edit_Project) that makes editing project data possible, such as updating project name, client, domain, adding target languages




	
  * List of jobs assigned to a user

	
    * A new API call [job/listByAssignedTo](http://wiki.memsource.com/wiki/Job_API_v3#List_By_User_.28Assigned_To.29) makes it possible to retrieve jobs assigned to a user




	
  * Get progress

	
    * A new API call [getSegmentsCount](http://wiki.memsource.com/wiki/Job_API_v3#Get_Segments_Count_.28.22Get_Progress.22.29)  makes it possible to get job metadata related to job progress and other job-related information, such as:

	
      * Number of segments

	
      * Quality assurance status

	
      * Translation progress







	
  * API token expiration

	
    * In line with our  API documentation we have started expiring API tokens

	
    * Each API token is valid 24 hours only




	
  * Client, Domain, SubDomain APIs

	
    * These are new APIs that we have introduced. Now you can get or create:

	
      * [Clients](http://wiki.memsource.com/wiki/Client_API_v2)

	
      * [Domains](http://wiki.memsource.com/wiki/Domain_API_v2)

	
      * [Subdomains](http://wiki.memsource.com/wiki/SubDomain_API_v2)







	
  * Get user by username

	
    * This new API call ([user/getByUserName](http://wiki.memsource.com/wiki/User_API_v2#Get_By_User_Name)) makes it possible to get a user by his/her username





