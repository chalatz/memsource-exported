---
id: 5618
title: 'Memsource Cloud 5.3: Multilingual Excel, Analytics, InDesign Preview'
date: 2016-01-14T10:55:39+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=5618
permalink: /2016/01/14/memsource-cloud-5-3-multilingual-excel-analytics-indesign-preview/
categories:
  - Memsource Blog
tags:
  - integration
  - Memsource Cloud
  - new release
---
Memsource Cloud 5.3 is scheduled for release on Sunday, 17 January 2016, at 11:00 AM GMT. This release introduces a new analytics capability, Adobe InDesign previews, multilingual Excel file support and other improvements.<!--more-->

### Multilingual Excel Files

  * **Multilingual Excel files include a source language and multiple target languages. They are now supported out-of-the-box in Memsource:** 
      * Previously, processing multilingual Excel files involved a lot of manual pre- and post-processing in Memsource. When you needed to import a multilingual Excel file into Memsource with, for example, English as the source language and German, Spanish and Japanese as the target languages, you were able to make use of our bilingual Excel filter but needed to manually create separate jobs for each language pair (in this case English-German, English-Spanish and English-Japanese).
      * From now on, you can work with just a single file, using our new multilingual Excel filter.
      * All you need to do is map the corresponding target language columns in the file import settings.
      * This will lead to the automatic creation of separate jobs for each language pair, while in the background the file will remain as one. When you download the completed file after translation, you will have a single Excel file containing all languages.

[<img class="aligncenter  wp-image-5619" src="/wp-content/uploads/2016/01/Multilingual-MS-Excel.png" alt="Multilingual MS Excel" width="561" height="404" data-id="5619" />](/wp-content/uploads/2016/01/Multilingual-MS-Excel.png)

### InDesign Preview

  * **Adobe InDesign files can now be previewed from within Memsource Web Editor.** 
      * We are bringing this new feature thanks to our integration with [Frontlab](http://express.frontlab.com/preview-express/?referrer=memsource), a leader in InDesign preview and proofing tools.
      * To use this new functionality, first [sign up](http://express.frontlab.com/preview-express/?referrer=memsource) with Frontlab and then enter your Frontlab credentials into Memsource under Setup &#8211; Integrations &#8211; Frontlab.
      * When you are done, a new menu item, &#8220;PDF Preview&#8221;, will appear in the Web Editor under the Document menu.
      * After clicking on PDF Preview, the InDesign preview will be downloaded to your PC as a PDF file.

[<img class="aligncenter  wp-image-5623" src="/wp-content/uploads/2016/01/PDF-Preview1.png" alt="PDF Preview" width="580" height="399" data-id="5623" />](/wp-content/uploads/2016/01/PDF-Preview1.png)

### Business Analytics

  * **Translations processed through Memsource have exceeded 1 billion words in the last quarter of 2015. We are now launching business analytics so that our users can track translation volumes, costs, productivity and other metrics.** 
      * We have deployed a dedicated data warehouse to serve all of our analytics needs. With the warehouse in place, we can now start launching new analytics features.
      * Initially, the new analytics features are only available for Memsource customers with one of our enterprise editions.
      * To start with, we are now releasing a set of pre-configured charts that can be set up in the new Home page. [
  
](/wp-content/uploads/2016/01/Analytics.png) [<img class="aligncenter  wp-image-5629" src="/wp-content/uploads/2016/01/Languages-and-File-Types-Analytics.png" alt="Languages and File Types Analytics" width="703" height="353" data-id="5629" />](/wp-content/uploads/2016/01/Languages-and-File-Types-Analytics.png)
      * A number of additional features and improvements are on the way in our analytics domain.
      * And most importantly, we will extend these new features also to our translation agency customers (Team Start, Team Ultimate editions) &#8211; we hope by the end of Q1/2016.

### Home Page

  * **The Home page is a new dashboard-like page with customizable widgets. ** 
      * Currently, analytics and [automation widgets](http://wiki.memsource.com/wiki/Automation_Widget) can be added to the page.
      * The Home page is currently only available to our enterprise customers:

[<img class="aligncenter  wp-image-5681" src="/wp-content/uploads/2016/01/Home-page2.png" alt="Home page" width="847" height="799" data-id="5681" />](/wp-content/uploads/2016/01/Home-page2.png)

### A Custom Welcome Message for the Automation Widget

  * **A custom welcome message can now be set for the Automation Widget.** 
      * The current message can be customized by going to Setup &#8211; Automation Widgets.

[<img class="  wp-image-5636 aligncenter" src="/wp-content/uploads/2016/01/Custom-Welcome-Message.png" alt="Custom Welcome Message" width="804" height="433" data-id="5636" />](/wp-content/uploads/2016/01/Custom-Welcome-Message.png)

###   Job Board

  * **We have made a few improvements to our Job Board (still in beta).** 
      * It is now easier to submit new job postings. Try for yourself:

[<img class="aligncenter  wp-image-5664" src="/wp-content/uploads/2016/01/Job-Board.png" alt="Job Board" width="1241" height="476" data-id="5664" />](/wp-content/uploads/2016/01/Job-Board.png)

### Custom Domain for the Team Edition

  * **A number of our customers have uploaded their own logo to Memsource Cloud. Team edition customers can now take this one step further. ** 
      * A custom domain is now supported also for the Team edition (previously only for the Ultimate edition).
      * Read the support article on how to [setup a custom domain](http://support.memsource.com/topic/is-it-possible-to-set-up-a-custom-domain-for-https) for your Team or Ultimate editions.

[<img class="aligncenter  wp-image-5665" src="/wp-content/uploads/2016/01/Custom-Logo-and-Domain.png" alt="Custom Logo and Domain" width="689" height="405" data-id="5665" />](/wp-content/uploads/2016/01/Custom-Logo-and-Domain.png)

### Quality Assurance

  * **A new QA check has been added to our quality assurance module:**: 
      * Target identical to source

### API

  * **Translation memory maintenance:** 
      * We have added two new API calls that can be helpful when global changes (e.g. find and replace) need bo applied to a translation memory. 
          * [Advanced translation memory query](http://wiki.memsource.com/wiki/Translation_Memory_Asynchronous_API_v2#Export_By_Query)
          * [Export results generated by the query](http://wiki.memsource.com/wiki/Translation_Memory_Asynchronous_API_v2#Download_Export)