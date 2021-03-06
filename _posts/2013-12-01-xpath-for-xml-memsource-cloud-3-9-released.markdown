---
author: admin
comments: true
date: 2013-12-01 17:51:39+00:00
layout: post
link: https://www.memsource.com/blog/2013/12/01/xpath-for-xml-memsource-cloud-3-9-released/
slug: xpath-for-xml-memsource-cloud-3-9-released
title: 'XPath for XML: Memsource Cloud 3.9 Released'
wordpress_id: 2040
categories:
- Memsource Blog
- New Features
tags:
- new release
- Memsource Cloud
---

![](/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png)

Memsource Cloud 3.9 has been released on Sunday, 1 December 2013 at 9:45 AM GMT. Memsource Cloud 3.9 includes over 80 improvements and bug fixes. These are the most important new features:<!-- more -->


### File Converter





	
  * XML filter now supports XPath and tag content editing

	
    * We have completely redesigned our XML filter

	
    * It now supports XPath, a powerful query language, thanks to which translatable content can be defined in a much more complex way than previously

	
    * The new XML filter also supports editing the contents of inline tags in Memsource Editor (by expanding the tag, clicking in the expanded tag and hitting F2)

	
    * These features are only supported for newly imported XML files





[![](/wp-content/uploads/2013/12/XML-XPath-300x179.png)](/wp-content/uploads/2013/12/XML-XPath.png)



	
  * Exclude elements in HTML

	
    * It is now possible to specify a list of HTML elements (tags) that should not be imported for translation





[![](/wp-content/uploads/2013/12/HTML-300x152.png)](/wp-content/uploads/2013/12/HTML.png)


### User Management





	
  * Project Manager User Rights Customization

	
    * The user rights of any project manager user can now be heavily [customized](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Project_Manager_User_Rights_Customization)

	
    * Early next year we will be adding an option restricting a project manager user to view/edit data by client







### Memsource Editor





	
  * Memsource Editor 3.138 highly recommended

	
    * It is highly recommended to use Memsource Editor 3.138 or higher with the current version of Memsource Cloud

	
    * Download the latest version of Memsource Editor  now if you are using an older version







### Machine Translation





	
  * PangeaMT Supported

	
    * The [PangeaMT engine](http://wiki.memsource.com/wiki/Machine_Translation#PangeaMT) is now supported out of the box

	
    * This brings the total number of MT engines supported in Memsource Cloud to 10







### API





	
  * A Deprecated API Call:

	
    * api/v3/job/listByProject has been deprecated as of today. Instead, use [api/v6/job/listByProject](http://wiki.memsource.com/wiki/Job_API_v6#List_By_Project)




	
  * Get Segments Count ("Get Progress") Accepts a List

	
    * [api/v6/job/getSegmentsCount](http://wiki.memsource.com/wiki/Job_API_v6#Get_Segments_Count_.28.22Get_Progress.22.29) now accepts a list of jobs




	
  * Tasks vs. Job Parts

	
    * We have created a dedicated section in our documentation that explains the [difference between tasks and job parts](http://wiki.memsource.com/wiki/API_Data_Types#Task_vs._Job_Part)





