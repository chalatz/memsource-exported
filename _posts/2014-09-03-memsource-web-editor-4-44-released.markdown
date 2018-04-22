---
author: admin
comments: true
date: 2014-09-03 11:06:21+00:00
layout: post
link: https://www.memsource.com/blog/2014/09/03/memsource-web-editor-4-44-released/
slug: memsource-web-editor-4-44-released
title: Memsource Web Editor 4.44 Released
wordpress_id: 2764
categories:
- New Features
tags:
- new release
- Memsource Web Editor
---

![](/wp-content/uploads/2014/08/webeditor-logo-300x111.png)

This article lists and describes major new features that have been recently introduced into Memsource Web Editor. The Web Editor is our younger translator's workbench, compared to the older desktop Memsource Editor.<!-- more -->

When developing the Web Editor we have used the latest technologies and have gone to test the limits of current web app development. For instance, Memsource users will not be annoyed by pagination when scrolling through long documents. In Memsource Web Editor the content keeps loading dynamically, just like on Twitter or Facebook. Although recent, the Web Editor has already had some history:



	
  * It was launched as a beta version in March 2013 and rolled out only to some of our users initially

	
  * By May 2014 we have stripped the beta label and made it available to all Memsource users

	
  * With the current 4.44 release we have introduced almost all of the features that have been available in the desktop Memsource Editor also to Memsource Web Editor




Below is an overview of selected features that we have recently added to Memsource Web Editor:


### Context





	
  * When translating, it is important that translators have access to the context of the translated content. This can be especially critical in software localization.

	
  * Three types of context information have been implemented in Memsource Web Editor:

	
    * Context key

	
      * For instance the key in a java properties file

	
      * The context key information is retrieved from source files automatically

	
      * Supported for: chrome json, csv, desktop entry, dtd, joomla ini, json, mac strings, mif, mozilla properties, po, properties, resjson, resx, srt, ts, windowsrc, xliff, xml, yaml








[![](/wp-content/uploads/2014/08/context-key.png)](/wp-content/uploads/2014/08/context-key.png)




	
    * Context note

	
      * Additional context information

	
      * Can be set by user in file import settings

	
      * Supported for: chrome json, csv, json, mac strings, po, resjson, resx, sbv, srt, ts, windowsrc, xliff, xml, yaml






[![](/wp-content/uploads/2014/08/context-note1.png)](/wp-content/uploads/2014/08/context-note1.png)




	
    * Context origin

	
      * Information about the origin of a segment. This context information is retrieved from the source file.

	
      * For instance, this value can be “footer” for a segment originating from the footer of a DOCX source file.

	
      * Supported for: desktop entry, mif, ts, MS Office






[![](/wp-content/uploads/2014/08/context-origin1.png)](/wp-content/uploads/2014/08/context-origin1.png)


### ADDITIONAL METADATA





	
  * Metadata such, as client, domain and subdomain are now available in a tooltip when you hover over the metadata section at bottom right.


[![](/wp-content/uploads/2014/08/additional-metadata-300x145.png)](/wp-content/uploads/2014/08/additional-metadata.png)


### VIEW PROJECT





	
  * There is now a new menu item which will take you directly to the project you are translating. This can be useful if, for instance, you have accidentally closed the tab with your project and would like to review its status.


[![](/wp-content/uploads/2014/08/view-project-300x146.png)](/wp-content/uploads/2014/08/view-project.png)


### TRACK CHANGES FILTER





	
  * The track changes filter option is now also available in the numerous segment filter and sorting features that have already been available for some time. The track changes filter makes it possible to filter for segments containing track changes, capturing the edits between workflow steps.


[![](/wp-content/uploads/2014/08/track-changes1-300x98.png)](/wp-content/uploads/2014/08/track-changes1.png)


### EDITING TAG CONTENT





	
  * It is now possible to edit tag content. In order to do this, you need to display the full content of tags (Edit – Expand Tags) and then click on the tag you wish to edit. A window will pop up enabling you to edit the content. This feature is only supported for software localization file types, such as xml, html, json, properties, etc.


[![](/wp-content/uploads/2014/08/edit-tag-content-300x67.png)](/wp-content/uploads/2014/08/edit-tag-content.png)


### NOTE AND USAGE WHEN CREATING TERMS





	
  * Note and Usage can now be entered directly from Web Editor when entering a new term.


[![](/wp-content/uploads/2014/08/note-and-usage-300x116.png)](/wp-content/uploads/2014/08/note-and-usage.png)


### USABILITY





	
  * Edited segment pinned to the center

	
    * The currently edited segment is now pinned to the center for better user experience




	
  * Enhancement of the filtering feature

	
    * It is possible to filter for segments containing certain text by selecting the text in the source or target and pressing CTRL+SHIFT+F




	
  * Orange to indicate difference in tag content

	
    * When tag content between the source and target differs, the tag in the target is displayed in orange to indicate the inconsistency





