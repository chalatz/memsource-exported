---
id: 2135
title: 'Custom Target Tags: Memsource Editor 3.148 Released'
date: 2014-01-28T17:54:15+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=2135
permalink: /2014/01/28/custom-target-tags-memsource-editor-3-147-released/
image_link:
  - http://blog.memsource.com/wp-content/uploads/2011/10/memsource-editor-icon.png
  - http://blog.memsource.com/wp-content/uploads/2011/10/memsource-editor-icon.png
  - http://blog.memsource.com/wp-content/uploads/2011/10/memsource-editor-icon.png
slide_template:
  - ""
  - ""
  - ""
categories:
  - Memsource Blog
  - New Features
tags:
  - Memsource Editor
  - new release
---
<img class=" alignleft" title="Memsource Editor - medium" src="/wp-content/uploads/2012/08/MemSource-Editor-medium.png" alt="" width="221" height="70" />

We have just released Memsource Editor 3.148. It is available now for download and we will start pushing this new version through our automated update feature to all Memsource users soon.<!--more-->

### Formatting and Tags

  * The content of tags can be edited 
      * After tags get expanded (Edit &#8211; Expand tags), they can be edited by clicking on the tag and hitting F2.

[<img class="alignnone size-medium wp-image-2142" title="edit-tags" src="/wp-content/uploads/2014/01/edit-tags-300x121.png" alt="" width="300" height="121" />](/wp-content/uploads/2014/01/edit-tags.png)

  * Custom target tags 
      * Arbitrary target tags can be created via Edit &#8211; Create Custom Tag (supported in HTML, XML or XLIFF source files).
      * Their content can be added/edited by clicking on the tag and hitting F2.
      * Custom tags and tags with different tag content between the source and target tag  (e.g. when the user has edited tag content in the target) are displayed in yellow.

[<img class="alignnone size-medium wp-image-2137" title="create custom tag" src="/wp-content/uploads/2014/01/add-tag-content-300x160.png" alt="" width="300" height="160" />](/wp-content/uploads/2014/01/add-tag-content.png)

### Terminology

  * Note and usage fields 
      * Note and usage information is displayed for terms in target now. Previously, this information was displayed for terms in source.
      * We have made this change based on user feedback. Unfortunately it means that if you have been using this feature, you will have to port the contents of your notes and usage fields from source to target terms. It can be done via the term base Excel [export](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Export_Terminology)/[import](http://wiki.memsource.com/wiki/MemSource_Cloud_User_Manual#Terminology_Import) at once.
  * The note and usage fields are now directly accessible from Memsource Editor when creating new terms.

[<img class="alignnone size-medium wp-image-2141" title="note-usage" src="/wp-content/uploads/2014/01/note-usage-300x120.png" alt="" width="300" height="120" />](/wp-content/uploads/2014/01/note-usage.png)

### Usability

  * Automated switching back to the CAT pane after search 
      * If a user works with the search pane and then confirms a segment, he/she is automatically switched back to the CAT pane for the next segment.
      * We believe this behavior makes sense and saves time to users, so that they do not have to manually switch to the CAT pane.
  * The Preferences menu is now located under Tools (to unify this with Memsource Web Editor)
  * The Insert feature (to overwrite text) is now supported
  * Obsolete versions of Memsource Editor 
      * If a user uses an obsolete version of Memsource Editor, he/she will get disconnected from Memsource Cloud servers and an error message will pop up, prompting the user to update Memsource Editor from our download site.
      * Currently, the obsolete version is defined as 3.137 or lower.