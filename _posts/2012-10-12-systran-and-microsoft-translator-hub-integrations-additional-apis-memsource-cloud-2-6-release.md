---
id: 1122
title: 'Systran and Microsoft Translator Hub Integrations, Additional APIs &#8211; Memsource Cloud 2.6 Release'
date: 2012-10-12T16:12:50+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=1122
permalink: /2012/10/12/systran-and-microsoft-translator-hub-integrations-additional-apis-memsource-cloud-2-6-release/
image_link:
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
categories:
  - Memsource Blog
tags:
  - Memsource Cloud
  - new release
---
<div>
  <a href="http://www.memsource.com/"><img class=" alignleft" title="Memsource Cloud – medium" src="/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png" alt="" width="221" height="70" /></a>
</div>

<div>
   Memsource Cloud 2.6 has just been released. This version includes over 120 improvements and bug fixes.
</div>

<!--more-->

<div>
  <h2>
    New Machine Translation Options
  </h2>
</div>

  * We have added new machine translation engines to which Memsource users can connect out of the box as well as new features 
      * Systran is now supported out of the box in MemSource
      * Microsoft Translator Hub is also supported out of the box in MemSource, including the &#8220;feedback&#8221; option (see below)
      * We have also redesigned the user interface to handle MT; it is much easier now &#8220;create&#8221; new machine translation engines, configure specific MT domains, etc.
      * We have also introduced an optional &#8220;feedback&#8221; feature for MT engines that support this (e.g. Microsoft Translator Hub). When feedback is enabled, post-edited translations are sent to the MT engine to improve it

<div>
  <a href="/wp-content/uploads/2012/10/machine-translation.png"><img class="alignnone size-medium wp-image-1180" title="machine-translation" src="/wp-content/uploads/2012/10/machine-translation-300x133.png" alt="" width="300" height="133" /></a>
</div>

  * A new quality assurance check: &#8220;No text between tags&#8221; 
      * When there is no text between paired tags in the target but there is some in the source, a warning will get triggered in quality assurance
  * MXLIFF files can now be directly imported into Memsource translation memory, as if it was a TMX file 
      * In fact the &#8220;Import TMX&#8221; button is used for this
      * This feature can be useful in many ways, e.g. in an emergency, when recovering a translation job gone wrong if you only have the MXLIFF file you are not able to generate a TMX file directly from Memsource Cloud
  * New API calls have been added, for instance: 
      * Set Translation Memories
      * Get Translation Memories
      * Create Analysis (and get results)
      * Set Term Bases
      * Get Term Bases
      * Delete Project
      * &#8230;
      * Memsource wiki lists all [Memsource APIs](http://wiki.memsource.com/wiki/MemSource_API), including the related documentation
      * With the latest API additions, Memsource translation projects, jobs, translation memories and term bases can be efficiently managed from 3rd party applications
  * New configuration options have been added for HTML file imports 
      * Break tags create a new segment
      * Non-HTML tags convert to Memsource tags
  * Text files (TXT, CSV, PROPERTIES&#8230;) are now always exported (after translation) in UTF8 character set
  * 101% matches can now be locked during pre-translation 
      * When locked, segments may not be edited by a linguist user
      * A project manager or administrator may also manually lock/unlock segments in Memsource Editor
  * Memsource Cloud UI localization 
      * Besides the existing Japanese, also Russian localization is now available (branded as &#8220;community translation&#8221;)
  * Memsource Web Editor 
      * A completely web-based editor, an alternative to Memsource Editor, is now available to selected organizations
      * A public launch is not far away
  *  Launching and resolving QA warnings can be enforced 
      * A new option is available under the Quality Assurance settings in a project: &#8220;Linguists may not set jobs with QA warnings to Completed&#8221;
      * When this option is selected, linguist users will not be able to set a job to the Completed status if QA was not launched or QA warnings have not been resolved or ignored
  * A linguist may set a job to the Completed status only if all segments are confirmed 
      * Otherwise an error message pops up: &#8220;Failed: Less than 100% segments confirmed. [Confirm all segments, upload](http://support.memsource.com/topic/how-to-upload-an-mxliff-file-to-memsource-cloud), and then retry.&#8221;
  * ZIP file import improvement 
      * When files get imported from a zip file, the path for each file is included (it is part of its name in the list of jobs, e.g. &#8220;&#8230;/dir/filename&#8221;)
  * New macros for email templates has been introduced 
      * {jobs.count}
      * {jobs.newStatus}
      * Project managers can now get automated notification emails, such as &#8220;Project _SomeName_: 4 Jobs Completed
  * Clone 
      * Projects can now be cloned via the new Clone button