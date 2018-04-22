---
author: admin
comments: true
date: 2013-01-21 15:21:08+00:00
layout: post
link: https://www.memsource.com/blog/2013/01/21/improved-usability-xls-terminology-imports-faster-qa-memsource-cloud-2-9-released/
slug: improved-usability-xls-terminology-imports-faster-qa-memsource-cloud-2-9-released
title: Improved Usability, XLS Terminology Imports, Faster QA - Memsource Cloud 2.9
  Released
wordpress_id: 1411
categories:
- Memsource Blog
tags:
- new release
---

[![](/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png)](http://www.memsource.com/)

Memsource Cloud 2.9 has been released today.

To learn more, continue reading and/or [sign up for a webinar](/webinars/) covering the new features. Memsource Cloud 2.9 includes almost 100 bug fixes and improvements. Some of the most noteworthy are listed below:<!-- more -->


### Usability Improvements





	
  * Project filter introduced

	
    * It is now possible to filter projects by name, client, domain, owner, status, created and due date:





[![](/wp-content/uploads/2013/01/project-filter-300x76.png)](/wp-content/uploads/2013/01/project-filter.png)



	
  * Client, domain and subdomain lists can be sorted by name now

	
  * Linguist notification in a subsequent workflow step

	
    * This feature is useful for projects with multiple workflow steps (available in the Team and Ultimate editions)

	
    * Once a linguist sets a job's status to completed, the linguist in the next workflow step is notified automatically

	
    * This is the new [email template](http://wiki.memsource.com/wiki/Next_Step_Ready_Email_Template)




	
  * A change to Active Jobs

	
    * The user list page displays "Active Jobs" (all jobs whose status is not completed or locked) for each user. For project manager and administrator users it now displays the total number of active jobs across all projects owned by the user.

	
    * For linguists, it continues to display the number of jobs in progress assigned to the user

	
    * This feature is only available in the Team and Ultimate editions




	
  * User accounts overview

	
    * When you hover with your mouse over the New button (to create a new user) in the user list page, a tooltip will display an overview of how many user accounts have been created and how many can still be set up:





[![](/wp-content/uploads/2013/01/user-overview-300x151.png)](/wp-content/uploads/2013/01/user-overview.png)



	
  * Exclude locked segments from analysis

	
    * Locked segments can be now excluded from a file analysis




	
  * Due date filter in jobs

	
    * Jobs may be filtered by their due date now




	
  * Dates display format

	
    * We have improved the date display format - months are now displayed with the abbreviation of their name, not with their number (to prevent the confusion with days which are expressed as a number). Additionally, when you hover over a date, the full date gets displayed, including the year, which was not the case previously







### Terminology Management





	
  * Terminology import and export via MS Excel

	
    * Previously we have supported TBX and CSV file formats for terminology imports and exports. We found that a lot of users had problems with creating the CSV file in the right format. Therefore, we have decided to replace the CSV with XLS

	
    * Users can now directly import and export terminology in a XLS file

	
    * Additional fields for import/export are now supported, such as Note, Usage

	
    * Read more on [XLS terminology import](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#XLS_Import_Format) in our documentation.

	
    * The CSV import format will still be supported for some time

	
    * Importing terminology got just much easier with the XLS file import format. This is how easy it gets:





[![](/wp-content/uploads/2013/01/plain-terminology-import1-300x171.png)](/wp-content/uploads/2013/01/plain-terminology-import1.png)


### Quality Assurance





	
  * Exclude locked segments

	
    * Locked segments can now be excluded from a QA check in the project's QA settings




	
  * Ignore not approved terms

	
    * Not approved terms can be optionally ignored during a QA terminology check




	
  * Launching quality assurance in batches of 100 segments

	
    * Previously, when QA was launched, it ran for the entire file. This could take a while for large files. To deliver results quicker, we will now process QA in batches of 100 segments. To get more QA results, the user has to click on "Show more" (available only with Memsource Editor 1.80 and higher):





[![](/wp-content/uploads/2013/01/show-more-qa-300x166.png)](/wp-content/uploads/2013/01/show-more-qa.png)


### Last But Not Least





	
  * Custom Memsource Cloud url

	
    * Organizations that subscribe to the Ultimate edition can set up their own private url for accessing Memsource Cloud; e.g. ourdomain.com




	
  * The <note> element in XLIFF files supported

	
    * The <note> element can now be optionally imported into MXLIFF. It will get stored in the comments section of the MXLIFF file. This feature can be useful for localization projects.






