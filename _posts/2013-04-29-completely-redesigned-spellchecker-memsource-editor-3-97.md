---
id: 1577
title: 'Completely Redesigned Spellchecker: Memsource Editor 3.97'
date: 2013-04-29T09:44:12+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=1577
permalink: /2013/04/29/completely-redesigned-spellchecker-memsource-editor-3-97/
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

Today we are announcing a major improvement to Memsource Editor. The version 3.97 comes with a **completely redesigned spellchecker**. To get this new version immediately, download it manually now (the automated update has been initiated but it may take some time).<!--more-->

### Spellchecker

  * Powered by Memsource Cloud 
      * Previously, the spellchecker was desktop-based. Now it is powered by Memsource Cloud. That means you have to be online to use it. Apart from that there are only advantages: 
          * Users get identical results from the spellchecker in Memsource Editor and Memsource Web Editor
          * And the user dictionary is shared across both editing environments too
          * Improvements to the spellchecker (e.g. what is a spelling error and what is not) can be made available much faster, as they are deployed just to our centralized Memsource Cloud infrastructure
          * Interactions with our other cloud-based components are now much easier, such as the QA (see below)
  * Launching the spellchecker 
      * Press F7 or go to Tools &#8211; Spellchecker to launch the spellchecker
      * The errors will get listed in the QA panel
  * Inline spellchecking 
      * Misspelled words are underlined with a red curly line
  * Spelling alternatives 
      * Spelling alternatives are suggested after right-clicking on a misspelled word

[<img title="suggest-spelling" src="/wp-content/uploads/2013/04/suggest-spelling-300x160.png" alt="" width="300" height="160" />](/wp-content/uploads/2013/04/suggest-spelling.png)

  * Improved algorithm 
      * We have significantly improved the spellchecking algorithm to minimize &#8220;false alarms&#8221;
  * User dictionary 
      * Misspelled words that are in fact correct can be easily added to a user&#8217;s dictionary that is stored in Memsource Cloud and is available from any device for the user
  * Integrated in Memsource QA 
      * Starting with Memsource Cloud 3.2, spelling is one of the default QA checks for all new projects
      * Therefore, project managers can verify whether all spelling errors have been resolved (along with other QA warnings)
  * We have also integrated spelling into the QA panel in the Memsource Editor user interface. This makes it very efficient to go through the spelling errors. After confirming a segment that had spelling errors, the user jumps to the next segment with spelling errors

### Mac-friendly Shortcuts

  * We have added these Mac-friendly keyboard shortcuts: 
      * copy source to target = cmd+shift+i
      * insert cat result = cmd+ctrl+space
      * move cat result up = cmd+up
      * move cat result down = cmd+down
      * insert non-breaking space = ctrl+shift+space
      * find next = cmd+g
      * find previous = cmd+shift+g

### Other

  * Repetition Exception 
      * We have introduced the [repetition exception](http://wiki.memsource.com/wiki/MemSource_Editor_User_Manual#Repetition_Exception) feature already in one of our earlier releases. In the current release we have introduced the option to select multiple segments and mark them as repetition exceptions, using the Repetition Exception command that can be found under the Edit menu in Memsource Editor