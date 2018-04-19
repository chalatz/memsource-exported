---
id: 1520
title: 'Open Files with 100K+ Segments: Memsource Editor 3.90 Released'
date: 2013-03-25T18:06:20+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=1520
permalink: /2013/03/25/open-files-with-100k-segments-memsource-editor-3-90-released/
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

You may have noticed that we have recently released [Memsource Web Editor](http://wiki.memsource.com/wiki/MemSource_Web_Editor_User_Manual) (as part of [Memsource Cloud 3.0 release](/introducing-memsource-web-editor-in-memsource-cloud-3-0/)). However, we have not stopped improving our (more mature) desktop translator&#8217;s workbench &#8211; Memsource Editor. Today we have released Memsource Editor 3.90. It is immediately available for download and we have just started pushing this new version to our users through the automated upgrade process.<!--more-->

Here is a list of the new features:

  * Change in version numbering 
      * The last version that was available to Memsource Cloud users was 1.83. We have changed the version numbering system, so that it is immediately clear with what version of Memsource Cloud our editors are compatible. Since now have Memsource Cloud 3.0, we have changed the version numbering from 1.90 to 3.90.
  * Memsource Editor even faster and optimized for large files 
      * Previous versions of Memsource Editor have been praised for being fast for general editing tasks. We have now made it even faster, including for large files. It is now possible to open MXLIFF files with over 100 thousand segments. For instance, an MXLIFF file with **250,000 segments** will open in 1-2 minutes (depending on your CPU) and it is possible to edit it quite comfortably. Scrolling through this file is surprisingly fast.
  * Repetition exception 
      * Clicking on the repetition icon in a segment will turn on/turn off the repetition exception feature for that segment. The repetition exception makes it possible to translate a repeated segment differently from the other repeated segments. This can be useful in a number of cases &#8211; especially when the context is different and a single translation will not do for all repetitions.

[<img class="alignnone size-medium wp-image-1526" title="Repetition-and-repetition-exception" src="/wp-content/uploads/2013/03/Repetition-and-repetition-exception1-300x130.png" alt="" width="300" height="130" />](/wp-content/uploads/2013/03/Repetition-and-repetition-exception1.png)

  * Login tab pops up if no login info available 
      * If a user opens Memsource Editor and no login information is entered under File &#8211; Preferences, the Login tab pops up automatically, with &#8220;cloud1.memsource.com&#8221; pre-populated in the Server field.
  * Source file name displayed 
      * The source file name for the selected segment is now displayed in the Editor&#8217;s status bar. This is especially useful when translating a joined file, as it is immediately apparent which source file gets edited by a user at any given moment.

[<img class="alignnone size-medium wp-image-1527" title="file-name" src="/wp-content/uploads/2013/03/file-name-300x58.png" alt="" width="300" height="58" />](/wp-content/uploads/2013/03/file-name.png)

  * Selected quotation option remembered 
      * Previously, when a user selected a specific quotation option, it would get reverted back to the default one after relaunching. The Editor remembers the selected option now.
  * Segment source and target character count 
      * Segment source and target character count is now displayed in the status bar for a selected segment

[<img class="alignnone size-medium wp-image-1528" title="segment-char-count" src="/wp-content/uploads/2013/03/segment-char-count-300x55.png" alt="" width="300" height="55" />](/wp-content/uploads/2013/03/segment-char-count.png)

  * Quality assurance launched in steps 
      * If there are hundreds or thousands of QA warnings, the QA panel will only show warnings for the first hundred segments and will allow the user to retrieve additional warnings by clicking on the &#8220;Show more&#8221; link.
  * After copying source to target, cursor positioned at the segment&#8217;s start 
      * Previously, the cursor would jump to the end of the segment
  * Unconfirm command introduced 
      * Segments can be unconfirmed by using the Uncofirm command (located under the Edit menu) or the shortcut Ctrl+Shift+Return
  * Editor updates correctly on Mac now 
      * The previous versions did not update automatically on Mac computers in some cases. This has been fixed.
  * Tags displayed as images 
      * Previously, tags were displayed as text, now they are displayed as images. The screenshot below shows a couple of paired tags and an unpaired tag.

[<img class="alignnone size-medium wp-image-1530" title="tags" src="/wp-content/uploads/2013/03/tags-300x68.png" alt="" width="300" height="68" />](/wp-content/uploads/2013/03/tags.png)

  * Line breaks and paragraph breaks introduced 
      * Line breaks (Shift+Enter) and new paragraphs can be created now in segments
  * Names of users displayed only to project managers 
      * First and last names of users are now only displayed to project managers/administrators for created by/last modified by metadata in Memsource Editor. Usernames are displayed to all users.
  * Linguists may confirm locked segments if confirmed in the preceding workflow step 
      * The inability to do this sometimes created problems for linguists as they were not able to set a translation job&#8217;s status to completed when locked segments were not confirmed