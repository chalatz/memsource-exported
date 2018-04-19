---
id: 1562
title: 'Project Templates, Pseudo-translate And More: Memsource Cloud 3.2 Released'
date: 2013-04-22T17:13:04+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=1562
permalink: /2013/04/22/project-templates-pseudo-translate-and-more-memsource-cloud-3-2-released/
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
[<img class=" alignleft" title="Memsource Cloud – medium" src="/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png" alt="" width="221" height="70" />](http://www.memsource.com/)

Memsource Cloud 3.2 has been released on Sunday, 21 April 2013 at 6:30 PM GMT.

Memsource Cloud 3.2 includes over 100 improvements and bug fixes. Let&#8217;s have a look at the most important new features:<!--more-->

### 

<div>
  <h3>
    Usability
  </h3>
</div>

  * Project templates 
      * [Project templates](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Project_Templates) make it possible to speed up project creation of repetitive projects and also reduce the risk of human error
      * Any project can be saved as a template through the [Save as](http://wiki.memsource.com/images/e/e6/Save-as-template.png) button
      * The following settings can be defined in a project template: File import settings, project TMs and TBs, project settings and reference file
  * Email login to new users 
      * Login information can now easily be sent to new users via the &#8220;[Email Login](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Email_Login)&#8221; button. The new [login info email template](http://wiki.memsource.com/wiki/Login_Info_Email_Template) will be used.

[<img class="alignnone size-medium wp-image-1566" title="email-login" src="/wp-content/uploads/2013/04/email-login1-300x127.png" alt="" width="300" height="127" />](/wp-content/uploads/2013/04/email-login1.png)

  * Join files and open them in [Memsource Web Editor](http://wiki.memsource.com/wiki/MemSource_Web_Editor_User_Manual) 
      * Select multiple jobs in Memsource Cloud and click on one of the file names of the selected jobs to open them as a joined &#8220;file&#8221; in Memsource Web Editor
  * Select, unselect all target languages 
      * It is possible to [select and unselect all/multiple target languages](http://support.memsource.com/topic/what-is-the-best-way-to-upload-files-to-a-multilingual-project) at once when adding a new job
  * ZIP files 
      * The maximum file size for a ZIP file upload is now set at 100 MB (1 GB for all other file types)
  * Pseudo-translate _(from Team edition up)_ 
      * We have introduced [pseudo-translation](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Pseudo-translate), a feature useful for localization but also general translation projects.

[<img class="alignnone  wp-image-1568" title="pseudo-translate" src="/wp-content/uploads/2013/04/pseudo-translate-300x161.png" alt="" width="270" height="145" />](/wp-content/uploads/2013/04/pseudo-translate.png)

### Quality Assurance

  * Spelling 
      * Spelling is now one of the available quality assurance checks and it is selected by default for new projects.

### Terminology

  * CSV terminology import deprecated 
      * Importing terms in a CSV file format has been superseded by the [MS Excel terminology import](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#XLS_Import_Format) and we stopped supporting the CSV terminology import

### API

  * User Management 
      * The following [user management APIs](http://wiki.memsource.com/wiki/User_API_v2) have been introduced: create new users, edit user, delete user, get user, list users, send login info
  * Email Template 
      * A new API call has been introduced: [Email Template](http://wiki.memsource.com/wiki/Email_Template_API_v2)
  * getJobByTask 
      * A new API call has been introduced: [getJobByTask](http://wiki.memsource.com/wiki/Job_API_v3#Get_Job_By_Task)
  * getCompletedFileByTask 
      * A new API call has been introduced: [getCompletedFileByTask](http://wiki.memsource.com/wiki/Job_API_v3#Get_Completed_File_By_Task)