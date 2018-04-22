---
author: admin
comments: true
date: 2013-07-14 08:44:11+00:00
layout: post
link: https://www.memsource.com/blog/2013/07/14/memsource-cloud-3-5-release/
slug: memsource-cloud-3-5-release
title: Memsource Cloud 3.5 Released
wordpress_id: 1777
categories:
- Memsource Blog
tags:
- new release
- Memsource Cloud
---

[![](/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png)](http://www.memsource.com/)

Memsource Cloud 3.5 has been released on Sunday, 14 July at 20:20 GMT. Memsource Cloud 3.5 includes over 60 improvements and bug fixes. Let's have a look at the most important new features:<!-- more -->


### Project Management





	
  * 100 jobs displayed per page

	
    * Previously, Memsource would display 50 jobs per page in projects with 50+ jobs

	
    * We have raised this to 100 jobs per page now




	
  * Import of large batches of files faster

	
    * We have significantly speeded up the import of large batches of files (e.t. 100+ files) into Memsource Cloud




	
  * Update of segmentation rules  through XLSX

	
    * Previously, segmentation rules could be updated through SRX or CSV

	
    * While there is no change for SRX, the CSV format has been replaced by XLSX

	
    * We found XLSX is easier to handle for most users

	
    * Read more on [segmentation](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Segmentation) in our documentation site







### Tags





	
  * Tag numbering now spans across multiple segments

	
    * Previously, tag were numbered separately for each segment

	
    * The numbering is now configured per paragraph and can span across a multiple segments

	
    * This allows for higher flexibility when placing target tags in a different order from the source tags in joined segments

	
    * Tags that come from the same paragraph can now be placed in any order in a joined segment

	
    * Memsource Editor 3.121 or higher is required for this feature to function properly

	
    * The screenshot below compares the way tags were numbered previously (left) and in the new version (right). The difference in numbering can be spotted in segments 8 and 10:





[![](/wp-content/uploads/2013/07/tags-across-seg-vs-par-300x179.png)](/wp-content/uploads/2013/07/tags-across-seg-vs-par.png)


### HTML





	
  * New option for HTML files: Preserve whitespaces

	
    * Whitespace characters (spaces, tabs, newlines...) normally do not carry a lot of meaning in HTML files

	
    * That is why they will not get preserved in the target file

	
    * If you want to preserve whitespace characters, select the new option "Preserve whitespaces"





[![](/wp-content/uploads/2013/07/preserve-whitesp-300x119.png)](/wp-content/uploads/2013/07/preserve-whitesp.png)


### API





	
  * New API call: Pre-translate

	
    * The new pre-translate call makes it possible to batch pre-translate a job by calling api/v3/job/preTranslate

	
    * Read more on the [pre-translate API call](http://wiki.memsource.com/wiki/Job_API_v3#Pre-translate) in our documentation




	
  * New API call: Edit Job

	
    * It is now possible to edit jobs via our API

	
    * For instance, it is possible to reassign a job to another linguist

	
    * Read more on the [edit job API call](http://wiki.memsource.com/wiki/Job_API_v3#Edit_Job) in our documentation




	
  * Access & Security Settings

	
    * [Access & Security Settings](http://wiki.memsource.com/wiki/Project_API_v2#Edit_Access_.26_Security_Settings) can now be controlled via our API

	
    * For instance, it is possible to enable Memsource Web Editor for linguist users





