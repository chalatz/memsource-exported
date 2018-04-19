---
id: 1261
title: 'Better Usability and Full Encryption &#8211; Memsource Cloud 2.8'
date: 2012-12-11T13:36:42+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=1261
permalink: /2012/12/11/better-usability-and-full-encryption-memsource-cloud-2-8/
image_link:
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
categories:
  - Memsource Blog
tags:
  - new release
---
<div>
  <a href="http://www.memsource.com/"><img class=" alignleft" title="Memsource Cloud – medium" src="/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png" alt="" width="221" height="70" /></a>Memsource Cloud 2.8 has been deployed today.
</div>

To learn more, continue reading and/or sign up for a [webinar](/webinars/) covering the new features. Memsource Cloud 2.8 includes a number of usability improvements and also an important security enhancement. Let&#8217;s have a look at the new features:<!--more-->

### Security

  * All communication encrypted by default 
      * Previously, users could choose to use encrypted connection to Memsource Cloud servers (via https) but the default was http. From now on, all communication will be encrypted by default between a user&#8217;s browser and our servers

### Usability

  * &#8220;Where did the **Join Files** feature go?&#8221; We needed to modify the entire **Download** menu since some of its items did not trigger any download anymore &#8211; only historically they did (e.g. **Email**, **Split File**)

[<img class="alignnone size-full wp-image-1341" title="old-download-menu" src="/wp-content/uploads/2012/12/old-download-menu.png" alt="" width="117" height="214" />](/wp-content/uploads/2012/12/old-download-menu.png)

  * **Split File** and **Email** have been moved under the new **Tools** menu where you will also find the **Upload** feature now

[<img class="alignnone size-medium wp-image-1351" title="tools-menu" src="/wp-content/uploads/2012/12/tools-menu-300x70.png" alt="" width="300" height="70" />](/wp-content/uploads/2012/12/tools-menu.png)

  * **Join Files** has been removed completely from the menu. Of course you can still join files. Simply select the jobs you want to join and click on **Download &#8211; Bilingual MXLIFF** and a small dialogue window will appear that will let you join the selected files

[<img class="alignnone size-full wp-image-1343" title="join-files" src="/wp-content/uploads/2012/12/join-files1.png" alt="" width="257" height="159" />](/wp-content/uploads/2012/12/join-files1.png)

  *  A new sorting feature for jobs in a project 
      * Previously one could only filter jobs, now they can also be sorted

[<img class="alignnone size-medium wp-image-1345" title="job-filtering-sorting" src="/wp-content/uploads/2012/12/job-filtering-sorting-300x74.png" alt="" width="300" height="74" />](/wp-content/uploads/2012/12/job-filtering-sorting.png)

  * Job paging introduced 
      * Previously, there was no job paging. If there were hundreds of jobs in a project, they would all appear in a single page which made it a little cumbersome and also slow
      * We have introduced paging that will create a new page for every 50 jobs. The job filtering and sorting feature helps managing a large number of jobs efficiently
      * The new **Select all** option makes it possible to select all jobs across multiple pages. This option will only get displayed once all jobs in a single page have been selected

[<img class="alignnone size-medium wp-image-1346" title="job-paging" src="/wp-content/uploads/2012/12/job-paging-300x93.png" alt="" width="300" height="93" />](/wp-content/uploads/2012/12/job-paging.png)

  * The **Domain** and **Client** fields were turned into picklist fields which will make it possible to have better control over the data in these fields and also use the data in a useful way (for instance to identify **relevant** translation memories for a project &#8211; see below). The Domain and Client data can now be added/modified via Setup &#8211; Clients or Setup &#8211; Domains.

[<img class="alignnone size-medium wp-image-1349" title="domain-client-picklist" src="/wp-content/uploads/2012/12/domain-client-picklist1-300x244.png" alt="" width="300" height="244" />](/wp-content/uploads/2012/12/domain-client-picklist1.png)

  * A new **Subdomain** domain field has been introduced for those who need more metadata for their projects. It will only get displayed in a project if you enter at least one subdomain value via Setup &#8211; Subdomains.
  * Translation memories and term bases got new fields: **Client**, **Domain**
  * Thanks to these improvements (related to the Client, Domain and Subdomain fields), Memsource will be able to enhance its feature that suggests relevant linguists for translation jobs (based on previous jobs the linguists did); available only in the Team edition and up
  * All users will benefit from a new feature that suggests relevant translation memories and term bases for projects. If you have the same client entered in your translation memory and your project, the client TM will come up at the top as relevant when selecting a TM for the project:

[<img class="alignnone size-medium wp-image-1352" title="relevant-tms" src="/wp-content/uploads/2012/12/relevant-tms1-300x165.png" alt="" width="300" height="165" />](/wp-content/uploads/2012/12/relevant-tms1.png)

  *  Users can choose which columns they want to have displayed in project, TM and TB lists:

[<img title="customize-columns" src="/wp-content/uploads/2012/11/customize-columns-284x300.png" alt="" width="284" height="300" />](/wp-content/uploads/2012/11/customize-columns.png)

  *  A new progress bar is displayed in the project list, displaying job status in each listed project: Completed (green) and overdue (red):

[<img title="progress-bar-cursor" src="/wp-content/uploads/2012/11/progress-bar-cursor-300x191.png" alt="" width="300" height="191" />](/wp-content/uploads/2012/11/progress-bar-cursor.png)

  * A new QA check: **Not Allowed** 
      * This new quality assurance check makes it possible to list characters that are not allowed in the target
      * The actual characters or utf-8 codes can be entered into the Not Allowed QA field (separated by commas)

[<img class="alignnone size-full wp-image-1370" title="not-allowed" src="/wp-content/uploads/2012/12/not-allowed.png" alt="" width="363" height="33" />](/wp-content/uploads/2012/12/not-allowed.png)