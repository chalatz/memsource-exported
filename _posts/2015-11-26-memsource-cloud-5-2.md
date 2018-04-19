---
id: 5515
title: 'Multilingual XML: Memsource Cloud 5.2'
date: 2015-11-26T15:25:29+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=5515
permalink: /2015/11/26/memsource-cloud-5-2/
categories:
  - Memsource Blog
tags:
  - Memsource Cloud
  - new release
---
Memsource Cloud 5.2 is scheduled for release on Sunday, 29 November 2015, at 11:00 AM GMT. This release introduces multilingual XML, more job-related info in projects, new API calls and other improvements.<!--more-->

### Multilingual XML

  * **Multilingual XML files include a source language and multiple target languages. They are now supported out-of-the-box in Memsource:** 
      * Previously, when you needed to import a multilingual XML file into Memsource with for example English as the source language and German, Spanish and Korean as the target languages, you were able to make use of our bilingual XML filter but needed to manually create separate jobs for each language pair (in this case English &#8211; German, English &#8211; Spanish and English &#8211; Korean)
      * From now on, you can work with just one file, using our new [Multilingual XML](http://wiki.memsource.com/wiki/Multilingual_XML) filter
      * All you need to do is map the corresponding target language elements in the file import settings
      * This will lead to the automatic creation of separate jobs for each language pair, while in the background the file will remains as one and when you download the completed file after translation, you will have a single XML containing all languages

[<img class="aligncenter size-full wp-image-5517" src="/wp-content/uploads/2015/11/multilingual-xml.png" alt="multilingual xml" width="677" height="589" data-id="5517" />](/wp-content/uploads/2015/11/multilingual-xml.png)

### Connect Sitecore, AEM, WordPress and other CMSes with Memsource via iLangL

  * **[iLangL](http://ilangl.com/), a provider of CMS-TMS integration, now supports Memsource out of the box.** 
      * The combined solution of iLangl and Memsource makes it quite easy to connect the below Content Management Systems and automate file logistics between the CMS and Memsource: 
          * Adobe Experience Manager
          * Sitecore
          * DNN Evoq
          * Drupal
          * EPiServer
          * Umbraco
          * WordPress
      * To learn more, [contact us](mailto:support@memsource.com). Or, stay tuned for more information. We will be providing more info on the integration shortly.

[<img class="aligncenter wp-image-5536" src="/wp-content/uploads/2015/11/iLangL-CMS-Integration.png" alt="iLangL CMS Integration" width="480" height="243" data-id="5536" />](http://ilangl.com/)

### More Job-related Information for Project Managers

  * **Info on job status changes and other job-related metadata can now be viewed by project managers** 
      * We have removed the blue info icon that would pop up when hovering over a job in a project and moved the information into two new tooltips and added even more details.
      * For each job, PMs can now view details about each job status change:
  
        [<img class="aligncenter size-full wp-image-5518" src="/wp-content/uploads/2015/11/job-activity.png" alt="job activity" width="629" height="310" data-id="5518" />](/wp-content/uploads/2015/11/job-activity.png)
      * Also, PMs can view even more job-related data in a tooltip displayed when hovering over the percentage completed:<img class="aligncenter size-large wp-image-5519" src="/wp-content/uploads/2015/11/job-statistics.png" alt="job statistics" width="354" height="280" data-id="5519" />

### Project Managers Can Set Time Zone for Linguists

  * **The time zone setting is not new but now it can be set by project managers for their linguist users** 
      * The time zone setting is not new by any means and every user can set it under Setup &#8211; User Settings in Memsource Cloud. In this way, all dates/times get fully converted based on the local time zone of each user (especially important for deadlines!).
      * From now on, PMs can set time zone for their linguists when creating or editing a linguist user:
  
        [<img class=" size-full wp-image-5520 alignleft" src="/wp-content/uploads/2015/11/Time-Zone.png" alt="Time Zone" width="610" height="496" data-id="5520" />](/wp-content/uploads/2015/11/Time-Zone.png)

### Context for CSV and Excel Files from More Columns

  * **Context from multiple columns can now be imported from bilingual Excel files** 
      * Multiple columns containing context information can be selected in file import settings in order to be displayed to translators. Context info from each column will be displayed on a separate line:
  
        [<img class="  wp-image-5522 alignnone" src="/wp-content/uploads/2015/11/context.png" alt="context" width="694" height="412" data-id="5522" />](/wp-content/uploads/2015/11/context.png)

### New Languages

  * **We have added a few more languages/language locales:** 
      * Arabic (Algeria)
      * English (Lebanon)
      * English (Saudi Arabia)
      * Greenlandic

### New Macro for Email Templates: {project.internalId}

  * **A new macro was added to the [list of macros](http://wiki.memsource.com/wiki/Template_macros) which can be used in email templates.** 
      * {project.internalId} will display the internal project number that users can see at the top of their projects:
  
        [<img class="aligncenter size-full wp-image-5523" src="/wp-content/uploads/2015/11/project-id.png" alt="project id" width="491" height="136" data-id="5523" />](/wp-content/uploads/2015/11/project-id.png)

### Improved Term Recognition for Hebrew and Arabic

  * **Term-base recognition of words with typical prefixes in Arabic and Hebrew has been improved.** 
      * Term base entries will now be recognized even if you enter the root of a word that is preceded by a standard prefix, for example ה in Hebrew.

### API

  * **New API calls have been introduced:** 
      * transMemory/getRelatedProjects 
          * Get a list of projects in which a specific TM is used.
      * JobService.splitFileBySpecificRange 
          * Split jobs after specific segments.
  * **New optional parameters added to the Search Segments by Task API:** 
      * maxSegments
      * maxSubSegments