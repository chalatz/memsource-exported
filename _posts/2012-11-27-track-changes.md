---
id: 1299
title: 'Track Changes, Created by/Modified by Filters &#8211; Memsource Editor 1.71 Released'
date: 2012-11-27T13:29:42+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=1299
permalink: /2012/11/27/track-changes/
image_link:
  - http://blog.memsource.com/wp-content/uploads/2011/10/memsource-editor-icon.png
  - http://blog.memsource.com/wp-content/uploads/2011/10/memsource-editor-icon.png
  - http://blog.memsource.com/wp-content/uploads/2011/10/memsource-editor-icon.png
categories:
  - Memsource Blog
tags:
  - Memsource Editor
  - new release
---
<img class=" alignleft" title="Memsource Editor - medium" src="/wp-content/uploads/2012/08/MemSource-Editor-medium.png" alt="" width="221" height="70" />

We have released Memsource Editor version 1.71 today. This article provides a cumulative list of features that have been recently added to Memsource Editor.<!--more-->

  * Information on a segment&#8217;s status in the preceding workflow step 
      * Confirmed (the black confirm icon means that the segment was confirmed in the preceding workflow step as opposed to a green confirm icon that indicates that the segment was confirmed in your own workflow step, that is for instance by you)
      * Not confirmed (similarly, the black cross (not-confirmed) icon means that the segment is not confirmed in the preceding workflow step as opposed to a red cross that indicates that the segment is not confirmed in your own workflow step)

<div>
  <a href="/wp-content/uploads/2012/11/segment-status-in-preceding-workflow-step.png"><img class="alignnone size-medium wp-image-1304" title="segment-status-in-preceding-workflow-step" src="/wp-content/uploads/2012/11/segment-status-in-preceding-workflow-step-300x177.png" alt="" width="300" height="177" /></a>
</div>

&nbsp;

  * Jump to the &#8220;Next segment confirmed in the preceding workflow step&#8221; 
      * This is a new option located under File &#8211; Preferences that lets a user jump to the next segment after confirming a segment
      * This feature is useful when, for instance, a reviser needs to start revising a translation that was not fully completed. The reviser will be taken just to those segments that were already confirmed by the translator and not to the ones the translator is still working on
  * The quality assurance check for inconsistent translations has been extended 
      * It has already identified segments with identical source had different translations
      * Now it also identifies segments with identical translations that have different source
  * Locked segments 
      * Project manager and administrator users may lock/unlock segments in Memsource Editor (shortcut Ctrl+L for both locking and unlocking)
  * Terms can be edited directly from within Memsource Editor 
      * When a user selects a term entry in the Memsource Editor CAT panel and the user is allowed to edit it, a clickable link will appear: &#8220;Edit Source Term/Target Term&#8221;. The link will take the user directly to the term edit page in Memsource Cloud
      * Project manager and administrator users may edit all terms
      * Linguist users may edit terms if their status is &#8220;New&#8221; and the project&#8217;s term base is in the write mode (both conditions must be met)

<div>
  <a href="/wp-content/uploads/2012/11/linguists-edit-terms-in-memsource-editor.png"><img class="alignnone size-medium wp-image-1305" title="linguists-edit-terms-in-memsource-editor" src="/wp-content/uploads/2012/11/linguists-edit-terms-in-memsource-editor-300x214.png" alt="" width="300" height="214" /></a>
</div>

&nbsp;

  * Multiple QA warnings can be selected and ignored now
  * New segment filtering options added. Segments can now be filtered by additional attributes: 
      * Segments created by 
          * Will filter segments created by the selected user
      * Segment last modified by 
          * Will filter segments last modified by the selected user
      * Comments created by 
          * Will filter segments with comments created by the selected user
      * Comments last modified by 
          * Will filter segments with comments last modified by the selected user
      * Track changes 
          * Will filter segments changed against the selected workflow step

<div>
  <a href="/wp-content/uploads/2012/11/memsource-editor-new-filters.png"><img class="alignnone size-medium wp-image-1306" title="memsource-editor-new-filters" src="/wp-content/uploads/2012/11/memsource-editor-new-filters-300x148.png" alt="" width="300" height="148" /></a>
</div>

&nbsp;

  * Changes panel added 
      * The changes panel can be found at the bottom right. It displays all changes to a segment that were done in any of the workflow steps
      * Double-clicking on any of the versions will insert the translation into the target, making it very easy to override an existing translation with its alternative originating from any of the preceding or even following workflow steps

<div>
  <a href="/wp-content/uploads/2012/11/track-changes.png"><img class="alignnone size-medium wp-image-1307" title="track-changes" src="/wp-content/uploads/2012/11/track-changes-300x180.png" alt="" width="300" height="180" /></a>
</div>

&nbsp;

  * Each segment has additional metadata available displayed 
      * Created by
      * Last modified by
      * Created at (hover over the username with your mouse to get the date/time info displayed)
      * Last modified at

<div>
  <a href="/wp-content/uploads/2012/11/created-modified-metadata.png"><img class="alignnone size-medium wp-image-1308" title="created-modified-metadata" src="/wp-content/uploads/2012/11/created-modified-metadata-300x105.png" alt="" width="300" height="105" /></a>
</div>

&nbsp;

  * Non-breaking spaces get displayed in Memsource Editor 
      * Previously, non-breaking spaces could be inserted in Memsource Editor but they were displayed just as regular spaces
      * Now they are displayed distinctly
  * Partial text selection from TM search results and from MT has been enabled 
      * Previously it was only possible to insert the entire target segment from TM search results/MT
      * Now it is possible to select just partial text, as we have provide the text at the bottom of the CAT panel

[<img class="alignnone size-medium wp-image-1309" title="copy-from-concordance" src="/wp-content/uploads/2012/11/copy-from-concordance-282x300.png" alt="" width="282" height="300" />](/wp-content/uploads/2012/11/copy-from-concordance.png)