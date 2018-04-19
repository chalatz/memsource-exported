---
id: 1462
title: 'Memsource Web Editor &#8211; What&#8217;s New in Memsource Cloud 3.0'
date: 2013-02-27T14:19:30+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=1462
permalink: /2013/02/27/introducing-memsource-web-editor-in-memsource-cloud-3-0/
image_link:
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
categories:
  - Memsource Blog
tags:
  - new release
---
[<img class=" alignleft" title="Memsource Cloud – medium" src="/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png" alt="" width="221" height="70" />](http://www.memsource.com/)

Memsource Cloud 3.0 has been released on Sunday, 3 March 2013 at 9:00 PM GMT.

To learn more, continue reading and/or sign up for a webinar covering the new features. Memsource Cloud 3.0 includes over 130 improvements and bug fixes. Let&#8217;s have a look at the most important new features:<!--more-->

### Memsource Web Editor

  * This is, no doubt, the most significant enhancement of the 3.0 version. So far, a completely web-based translator&#8217;s workbench was missing in MemSource. With its introduction, we now offer both browser-based [Memsource Web Editor](http://wiki.memsource.com/wiki/MemSource_Web_Editor_User_Manual) as well as [Memsource Editor](http://wiki.memsource.com/wiki/MemSource_Editor_User_Manual), which is a lightweight and fast desktop translator&#8217;s workbench seamlessly connected to Memsource Cloud. And Memsource is currently the only cloud-based translation technology provider that offers both a web-based as well as desktop translation client
  * Memsource Web Editor will be rolled gradually to Memsource users: 
      * It is immediately available to all new organizations/individuals that [sign up for a Memsource account](http://www.memsource.com/pricing/)
      * It is also available by default for all new projects for organizations that had Memsource Web Editor enabled as a pre-release
      * Existing customers can ask [Memsource support](http://wiki.memsource.com/wiki/MemSource_Support#Email_Support) to enable the Web Editor for them (please provide your username)
  * Memsource Web Editor does not yet have all the features of the more mature Memsource Editor, that&#8217;s why we have labeled the Web Editor as a beta version for the time being. However, we are working hard on adding them and in fact all essential features are available, so nothing should stop anyone to produce a translation in it.

### Usability

  * List page filters can be [saved](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Save_a_Project_Filter), also TM, TB and user lists are now supported with the filter feature 
      * Project managers can now comfortably filter in the lists of projects, TMs, TBs and users
      * The filters can be saved as personal filter with a custom name

[<img class="alignnone size-medium wp-image-1509" title="Save-filter-as" src="/wp-content/uploads/2013/02/Save-filter-as-300x76.png" alt="" width="300" height="76" />](http://wiki.memsource.com/images/3/30/Save-filter-as.png)

  * File import settings get saved 
      * Each project now &#8220;remembers&#8221; [file import settings](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#File_Import_Settings). This mean that if a user sets up custom file import setting for one or more file formats, they will be saved with the project for additional file imports into that project
  * Job due date filter 
      * A number of pre-defined options are now supported, such as &#8220;overdue&#8221; jobs
  * A new &#8220;Note&#8221; filed has been introduced for projects, translation memories and term bases 
      * If a note is available for any of these, it will also be visible in project/TM/TB list
  * Analyses batch export introduced 
      * It is possible to export analysis data for all analyses in specified period into a CSV file
      * Each line represent an analysis with the corresponding word count and also included is the linguist to whom the analysis was assigned to
      * This makes it possible to use such data for billing purposes, e.g. import them into a billing/invoicing application or simply process them in MS Excel
  * Analysis settings saved 
      * For new analyses, settings get saved in the project (hover over the blue circle that gets displayed at the far right of the analysis section in a project and you will see whether the analysis was launched with e.g. &#8220;Exclude numbers&#8221;, &#8220;Exclude confirmed segments&#8221;, etc.

### File Conversion

  * SDLXLIFF 
      * A number of improvements have been made to make the translation of SDXLIFF smoother
      * For instance, we now support line breaks for SDLXLIFF or our method for removing illegal xml characters from SDLXLIFF has been improved

### Machine Translation

  * Asia Online 
      * [Asia Online](http://wiki.memsource.com/wiki/Machine_Translation#Asia_Online) has been added as a supported MT provider

### Translation Memory

  * XLS to TM 
      * A bilingual or multilingual Excel file can now be imported directly into a translation memory through the Import button
  * Improvements for CJK languages, Thai and Persian 
      * Improved efficiency for CJK (Chinese, Japanese, Korean), Thai and Persian languages, which leads to better translation memory leverage
  * Symbols indexed 
      * Symbols now get indexed; Previously, if a segment only contained a symbol, it would not get indexed, now it will get indexed and consequently returned in translation memory search or pre-translation like any other segment

### APIs

  * Spell check API introduced 
      * The [spell check API](http://wiki.memsource.com/wiki/Spell_Check_API_v2) supports _check_, _suggest_ and _add text_ operations. This API is used to provide the spellchecking functionality in Memsource Web Editor
  * File import settings supported in API 
      * File import settings are now supported when [creating new translation jobs through API](http://wiki.memsource.com/wiki/Job_API_v3#Create_New_Job)
  * Support for multiple jobPart arguments has been added