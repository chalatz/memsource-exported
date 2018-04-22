---
author: admin
comments: true
date: 2014-08-14 09:16:46+00:00
layout: post
link: https://www.memsource.com/blog/2014/08/14/introducing-gengo-human-translation-engine-memsource-cloud-4-5-release/
slug: introducing-gengo-human-translation-engine-memsource-cloud-4-5-release
title: 'Introducing Gengo Human Translation Engine: Memsource Cloud 4.5 Release'
wordpress_id: 2670
categories:
- Memsource Blog
tags:
- new release
- Memsource Cloud
---

[![](/wp-content/uploads/2014/04/cloud-logo-221x100-3.png)](http://www.memsource.com/)

Memsource Cloud 4.5 is scheduled for release on Sunday, 17 August 2014 at 9:00 AM GMT. Memsource Cloud 4.5 includes over 100 improvements and bug fixes.<!-- more -->


### Human Translation





	
  * Pre-translation from translation memory and machine translation has been available right from the start in [Memsource Cloud](http://www.memsource.com/). Now we have added human pre-translation powered by [Gengo](http://gengo.com/).


[![](/wp-content/uploads/2014/08/Human-translate-via-Gengo2-300x160.png)](/wp-content/uploads/2014/08/Human-translate-via-Gengo2.png)



	
  * Gengo is the world's leading crowdsourced human translation provider that supports dozens of language pairs (primarily with English as either the source language or target language).

	
  * Memsource is able to offer Gengo translation at the Gengo API rate of $0.05 per word for any language pairs until the end of 2014 (the non-API rate is $0.06). Gengo charges no minimum fee, so even a single word can be translated at this rate from within Memsource Cloud.

	
  * Gengo works best:

	
    * When fast turnaround is important

	
    * For shorter texts

	
    * For content that is not highly complex such as:

	
      * Blog/news/social media and other digital content

	
      * Product catalogs

	
      * Website translation

	
      * Etc.







	
  * Gengo can be a very useful resource for translation companies:

	
    * When they run short of their own translators.

	
    * For small translation jobs that would be inefficient if translated by the agency's standard translation process.




	
  * Billing for Gengo services is extremely simple and works in the same way as for machine translation providers in Memsource. Simply sign up with Gengo, top up your credit and enter your API token in Memsource Cloud under Setup - Human Translation Engines. Refer to our [Gengo setup guide](http://wiki.memsource.com/wiki/Human_Translation_Engines#Gengo_Set_Up) for detailed instructions and screenshots.




### Project Management





	
  * **Linguist Notification and Selection when Creating a New Job**

	
    * Linguists can now be notified of a new job already during new job creation.

	
    * Linguists can be entered for all workflow steps already during new job creation (relevant for projects with workflow).





[![](/wp-content/uploads/2014/08/new-job-with-workflow-300x265.png)](/wp-content/uploads/2014/08/new-job-with-workflow.png)



	
  * **"Locked" Renamed to "Delivered"**

	
    * We have changed the job status label "locked" to "delivered." From a functional perspective nothing has changed, this is really just about renaming. We found that "delivered" makes more sense and in fact quite a few of our customers have used "locked" to mean "delivered."




	
  * **Analyze by Linguist**

	
    * This new option makes it possible to generate separate analyses for all linguists with a single click.





[![](/wp-content/uploads/2014/08/analyze-by-linguist-300x276.png)](/wp-content/uploads/2014/08/analyze-by-linguist.png)



	
  * **New Languages Added**

	
    * We have started supporting new languages in Memsource Cloud:

	
      * cld (Chaldean)

	
      * hak (Hakka Chinese)

	
      * hbs (Serbo-Croatian)

	
      * kpe (Kpelle)

	
      * kri (Krio)

	
      * man (Mandingo)

	
      * tet (Tetum)

	
      * tw (Twi)

	
      * ymm (Maay)







	
  * **Analyze Translation Memory Post-editing**

	
    * A new option has been introduced to the [post-editing analysis](http://wiki.memsource.com/wiki/Post-editing_Analysis). With this option selected, the post-editing analysis will include not just machine translation edits but also translation memory edits.

	
    * Example: If a linguist modifies a 100% TM match by 10%, the analysis will return 90% with this option selected. The analysis will return 100% if the option is not selected.**
**





[![](/wp-content/uploads/2014/08/analyze-TM-post-editing-300x214.png)](/wp-content/uploads/2014/08/analyze-TM-post-editing.png)



	
  * **Default Project Owner in a Project Template**

	
    * It is now possible to set a default project owner in a project template.

	
    * This can be useful when projects are created in an automated way, for instance via an instant quote widget, and the projects should be assigned to different project owners based on specific source/target languages.




	
  * **Change Source/Target Languages in an Existing Project**

	
    * Previously, Memsource was very strict and made it impossible to change the source language or remove target languages from an existing project.

	
    * It is now possible to change the source language and remove target languages if it causes no harm (e.g. if no jobs, translation memories or term bases have been added to the project).




	
  * **Shared Projects Available also in Trial Accounts**

	
    * Previously, shared projects were not supported in trial accounts. This has changed now.







### File Conversion





	
  * **Configurable Context for XML Files**

	
    * The context note for [XML](http://wiki.memsource.com/wiki/XML) is not a new feature. However, previously it was not configurable.

	
    * Now it is possible to define what should be extracted as a context note.

	
    * The context note and other context information can be easily displayed for each segment in both Memsource Editor and Memsource Web Editor (Tools - Toggle Context).

	
    * Please note that the context note for XML is only supported in the XPath file import settings.





[![](/wp-content/uploads/2014/08/context-note-for-XML-300x211.png)](/wp-content/uploads/2014/08/context-note-for-XML.png)



	
  * **A New HTML File Import Option**

	
    * "Convert to Memsource tags (use regexp)" is a new option in the HTML file import settings.




	
  * **File Import Warning**

	
    * Memsource will display a file import warning in some cases notifying the user of specific issues related to the imported file. These can be:

	
      * A MS Word file includes embedded MS Excel sheets.

	
      * Hidden cells are merged with visible cells in MS Excel.

	
      * Incorrect encoding for some localization file types.

	
      * Importing an SDLXLIFF with locked x tags.

	
      * ...








[![](/wp-content/uploads/2014/08/file-import-warning1-300x111.png)](/wp-content/uploads/2014/08/file-import-warning1.png)


### User Management





	
  * **Activate/deactivate Linguists Automatically**

	
    * The option "Activate/deactivate linguists automatically" under Setup - Access and Security is now also available in the [Team edition](http://wiki.memsource.com/wiki/MemSource_Editions#Team_Edition).

	
    * With this option on, linguist users are made inactive automatically once they set a job to completed if they have no other jobs open.

	
    * Before being made inactive, the following message is displayed to linguists:

	
      * "You have no other jobs in progress and your account will be deactivated until new jobs arrive. Proceed?"










### Machine Translation





	
  * **Safaba**

	
    * Safaba MT engine is now available in Memsource Cloud.




	
  * **PROMT**

	
    * PROMT MT engine is now available in Memsource Cloud.







### API





	
  * **Remaining Licenses**

	
    * We have introduced a new call that will return the number of remaining unused user licenses.

	
    * [api/v2/user/getLimits](http://wiki.memsource.com/wiki/User_API_v2#Get_Limits)




	
  * **Assign Vendor**

	
    * A new API call has been introduced, related to shared projects that makes it possible to assign vendors.

	
    * [api/v3/project/assignVendor](http://wiki.memsource.com/wiki/Project_API_v3#Assign_Vendor)




	
  * **Use Template for Project Creation**

	
    * It is now possible to create a project based on a project template via API.

	
    * [api/v3/project/createFromTemplate](http://wiki.memsource.com/wiki/Project_API_v3#Create_New_Project_From_Template)




	
  * **Create and List Project Templates**

	
    * It is now possible to create and list project templates via API.

	
    * [api/v2/projectTemplate/create](http://wiki.memsource.com/wiki/Project_Template_API_v2)

	
    * [api/v2/projectTemplate/list](http://wiki.memsource.com/wiki/Project_Template_API_v2)





