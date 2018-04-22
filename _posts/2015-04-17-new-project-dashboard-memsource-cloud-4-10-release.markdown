---
author: vaclavb
comments: true
date: 2015-04-17 07:43:09+00:00
layout: post
link: https://www.memsource.com/blog/2015/04/17/new-project-dashboard-memsource-cloud-4-10-release/
slug: new-project-dashboard-memsource-cloud-4-10-release
title: 'New Project Dashboard: Memsource Cloud 4.10 Release'
wordpress_id: 3992
categories:
- Memsource Blog
tags:
- new release
- Memsource Cloud
---

[![](/wp-content/uploads/2014/04/cloud-logo-221x100-3.png)](http://www.memsource.com/)

Memsource Cloud 4.10 is scheduled for release on Sunday, 19 April 2015 at 9:00 AM GMT. <!-- more -->These are some of the most notable improvements:


### Project Dashboard


We have had a project dashboard for some time. However, we felt it needed to be improved. The current release includes the first version of a completely redesigned project dashboard. The dashboard is visible to administrator, project manager and guest users. We hope that it will make the life of project managers easier. These are the main components of the new dashboard:



	
  * **Progress**

	
    * The dashboard lists target languages as rows and displays a progress bar for each target language (% of characters confirmed) and the total word count for each target language.

	
    * **Warnings**


	
      * When issues related to job status arise, warnings are displayed at the top of the "Progress" section. Currently, the following issues are flagged here:


	
        * Overdue jobs

	
        * Declined jobs






	
  * **Quality Assurance**


	
    * This section displays useful information related to the quality assurance feature:


	
      * Indication whether quality assurance has been launched at all

	
      * Percentage of segments checked by the quality assurance feature

	
      * The number of unresolved QA warnings



	
  * **MT Usage**


	
    * If MT is enabled for a given target language, we display here the percentage of segments in which raw machine translation was used (the linguist used MT without any additional post-editing)



[![](/wp-content/uploads/2015/04/Project-Dashboard-300x189.png)](/wp-content/uploads/2015/04/Project-Dashboard.png)


### Additional Project Management Features






	
    * **Net Rate Schemes Applied Automatically**


	
      * Each linguist can now be linked to a specific net rate scheme and price list. If you run an analysis with the "Analyze by Linguist" option selected, not only that the analysis is assigned to the linguist in question, but also the corresponding net rate scheme is applied.


	
    * **Linguists Automatically Activated on Job Status Change**


	
      * With the setting "Activate/deactivate linguists automatically" enabled, an inactive linguist user will be automatically activated if a job's status is changed from Completed or Delivered to e.g. Accepted.


	
    * **New Email Template Macro**


	
      * A new email template macro {job.previousWorkflow.dateDue} lets you add information on the job due date in the preceding workflow step. This is useful for situations when you assign a job to a reviewer and you want to let them know what the deadline is in the preceding workflow step, i.e. when approximately they can expect the "Next step ready" e-mail to arrive.


	
    * **Cost Centers**


	
      * A cost center can now be entered for a project.


	
    * **Raw MT Usage**


	
      * The job metadata now include information on the percentage of segments in which raw machine translation has been used.




[![](/wp-content/uploads/2015/04/Raw-MT-300x209.png)](/wp-content/uploads/2015/04/Raw-MT.png)


### File Conversion





	
  * **Maximum Target Length for XLIFF**


	
    * _Maxwidth_ defines segment length.


	
      * We now interpret the _maxwidth_ value in XLIFF file as the specification of the maximum number of characters per segment.

	
      * When the limit is exceeded, a red indicator is displayed in both Editors as a warning.

	
      * This is also covered by the QA check.





	
  * **TMX Improvements**


	
    * TMX files can also be imported as files for translation (as jobs in a project).

	
    * We have now substantially improved our processing of TMX files as translatable files and included the support for the <note> element.





### Miscellaneous





	
  * **Kurdish Alphabet**


	
    * Memsource now supports the Arabic version of Kurdish, in addition to the Latin one.





### Integrations





	
  * **tauyou**


	
    * We have significantly improved our integration with the tauyou MT engine.

	
    * The improvements should lead to better performance.


	
  * **Gengo**


	
    * A new option has been added when ordering Gengo-powered translation from within Memsource:


	
      * "Use preferred translator"



	
  * **XTRF**


	
    * XTRF-Memsource integration no longer relies on IFrames and introduces a better approach.



