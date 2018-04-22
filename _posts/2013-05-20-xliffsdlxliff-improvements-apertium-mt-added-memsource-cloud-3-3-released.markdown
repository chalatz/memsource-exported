---
author: admin
comments: true
date: 2013-05-20 16:37:32+00:00
layout: post
link: https://www.memsource.com/blog/2013/05/20/xliffsdlxliff-improvements-apertium-mt-added-memsource-cloud-3-3-released/
slug: xliffsdlxliff-improvements-apertium-mt-added-memsource-cloud-3-3-released
title: 'XLIFF/SDLXLIFF Improvements, Apertium MT Added: Memsource Cloud 3.3 Released'
wordpress_id: 1635
categories:
- Memsource Blog
- New Features
tags:
- new release
---

[![](/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png)](http://www.memsource.com/)

Memsource Cloud 3.3 has been released on Sunday, 19 May 2013 at 6:30 PM GMT.

Memsource Cloud 3.2 includes over 80 improvements and bug fixes. Let's have a look at the most important new features:<!-- more -->


### Project Management





	
  * Workflow

	
    * When linguists attempt to download an MXLIFF or launch the Web Editor for a job that has not yet been completed in the preceding workflow step, a warning will pop up and they will be asked whether to proceed or not





[![](/wp-content/uploads/2013/05/proceed-yes-no.png)](/wp-content/uploads/2013/05/proceed-yes-no.png)



	
  * Info on translation progress more precise

	
    * Previously, Memsource displayed the percentage of confirmed segments for each job in a project. Now it is based on the percentage of confirmed characters (the percentage of characters of the total character count in confirmed segments

	
    * This only works for jobs created after 29 May 2013; information for older jobs is still based on the old algorithm (percentage of confirmed segments)

	
    * The new way is much more precise as segments can have varying character distribution; 50% of confirmed segments can sometimes mean only e.g. 20% of translation done based on character count





[![](/wp-content/uploads/2013/05/chars-confirmed-300x88.png)](/wp-content/uploads/2013/05/chars-confirmed.png)



	
  * Client and domain fields

	
    * These fields are now only displayed when creating a new project when there exists at least one client and domain entry







### Locked Segments





	
  * Setting jobs with locked segments to completed status

	
    * Previously, jobs that had locked segments that were not confirmed could not be set to the completed status by linguist users

	
    * From now on linguists will be able to set such jobs as completed




	
  * Passing confirmed locked segments through workflow

	
    * Previously, confirmed locked segments would pass to the next workflow step as not confirmed (like all other segments)

	
    * From now on, confirmed locked segments will remain confirmed when passing to the next workflow step







### XLIFF





	
  * Segment status mapping

	
    * XLIFF segment state can be mapped to MXLIFF segment status on import

	
    * MXLIFF segment status can be mapped to XLIFF segment state on export

	
    * Confirmed segments can optionally be saved directly to TM on import




	
  * Do not import selected segments

	
    * Selected segments, based on their segment state, will  not get imported




	
  * Tag content visualized

	
    * XLIFF tags can be visualized in Memsource Editor (from version 3.104 and up)




	
  * Segmentation

	
    * <source> gets now segmented by default

	
    * <seg-source> does not get segmented (no change)







### SDLXLIFF





	
  * Segment status mapping

	
    * SDLXLIFF status can be mapped to MXLIFF segment status on import

	
    * MXLIFF segment status can be mapped to SDLXLIFF segment status on export

	
    * Locked SDLXLIFF segments can be mapped to locked MXLIFF segments

	
    * Confirmed segments can optionally be saved directly to TM on import




	
  * Do not import selected segments

	
    * Selected segments, based on their segment status, will  not get imported





[![](/wp-content/uploads/2013/05/sdlxliff-import-rules-300x166.png)](/wp-content/uploads/2013/05/sdlxliff-import-rules.png)


### TTX





	
  * Confirmed segments can optionally be saved directly to TM on import




### HTML





	
  * Tag content visualized

	
    * HTML tags can be visualized in Memsource Editor (from version 3.105 and up)







### XML





	
  * Tag content visualized

	
    * XML tags can be visualized in Memsource Editor (from version 3.105 and up)







### IDML





	
  * Stories reordered

	
    * Stories now presented in the reading order in MXLIFF instead of the default order (the order in which the stories were added)







### PowerPoint





	
  * Hidden slides

	
    * Hidden slides are now not imported by default. A new option has been added to import hidden slides







### .PO





	
  * .PO localization file format

	
    * .PO localization files are now supported and can be added as jobs to a Memsource project







### Apertium





	
  * Apertium MT engine added

	
    * Memsource now supports Apertium, an open-source rule-based machine translation engine

	
    * Apertium is recognized for quality machine translation between English and Romance languages





[![](/wp-content/uploads/2013/05/Apertium.png)](/wp-content/uploads/2013/05/Apertium.png)


### Spellchecker





	
  * Spellchecker user dictionary import/export

	
    * The dictionary can now be imported and exported under Setup - User Settings - Spellchecker User Dictionary




	
  * Spellchecker speed

	
    * The spellchecker service has been made about 10 times faster







### API





	
  * project/list

	
    * A new API call has been added: [list projects](http://wiki.memsource.com/wiki/Project_API_v2#List_Projects)




	
  * user/list

	
    * If no user is specified, all organization's users will be retrieved




	
  * activeJobsCount

	
    * A new field has been added to user/get and user/list methods that makes it possible to retrieve the number of jobs in progress for a user




	
  * termBase/clear

	
    * A new API call has been added to [clear all data](http://wiki.memsource.com/wiki/Term_Base_API_v2#Clear_Data) in a term base in one go





