---
id: 3360
title: 'Redesigned DITA Filter, Asynchronous APIs and More: Memsource Cloud 4.7'
date: 2014-11-20T12:23:58+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=3360
permalink: /2014/11/20/redesigned-dita-filter-asynchronous-apis-and-more-memsource-cloud-4-7/
categories:
  - Memsource Blog
tags:
  - Memsource Cloud
  - new release
---
[<img class="alignleft size-full wp-image-2344" title="Memsource Cloud" src="/wp-content/uploads/2014/04/cloud-logo-221x100-3.png" alt="" width="221" height="100" />](http://www.memsource.com/)

Memsource Cloud 4.7 is scheduled for release on Sunday, 23 November 2014 at 11:00 AM GMT. Memsource Cloud 4.7 includes over 100 improvements and bug fixes.<!--more-->

### Collaboration & Sharing

  * **Transfer Project to Buyer**
  * When buyer and vendor collaborate in Memsource Cloud, the buyer may typically initiate a project and then share it with the vendor. However, there are a number of instances when it is the vendor who initiates the project and then would need to turn it into a shared project ex post.
  * This is exactly what this new feature (&#8220;Transfer Project to Buyer&#8221;) does: It turns an existing project created by a vendor into a shared project owned by the buyer and shared with the vendor. Once transferred, the buyer will be notified of the new shared project.
  * This feature will only be available to organizations that have provided their [vendor token](http://wiki.memsource.com/wiki/Sharing#Vendor_Token) to at least one buyer (and in that case they will be able to see the buyer list under Setup &#8211; Buyers.)

[<img class="alignnone size-medium wp-image-3367" title="Transfer Project to Buyer" src="/wp-content/uploads/2014/11/Transfer-Project-to-Buyer-300x118.png" alt="" width="300" height="118" />](/wp-content/uploads/2014/11/Transfer-Project-to-Buyer.png)

### File Conversion

  * **DITA Filter Redesign**
  * We have completely redesigned our DITA filter and added a number of useful options.
  * Tag content can now be visualized and edited and custom target tags can be created.
  * A new file import options have been added:
  * Translatable elements
  * Non-translatable elements
  * Translatable inline elements
  * Non-translatable inline elements

[<img class="alignnone size-medium wp-image-3363" title="DITA File Import Options" src="/wp-content/uploads/2014/11/DITA-File-Import-Options-300x110.png" alt="" width="300" height="110" />](/wp-content/uploads/2014/11/DITA-File-Import-Options.png)

  * **ICML Filter Redesign**
  * We have made redesigned our ICML filter to be more robust and also consistent with our IDML filter.

  * **Scalable Vector Graphics (SVG) Supported**
  * We have started supporting SVG as a new file type.

  * **Electronic Publication (EPUB) Supported**
  * We have started supporting EPUB (.epub) as a new file type.

  * **Automated Identification of Inline Elements for XML**
  * We have introduced a new option in XML file import settings:
  *  &#8220;Identify inline elements automatically&#8221;

  * With this option enabled, elements that are neighbors of text nodes will be automatically converted to inline tags.

[<img class="alignnone size-medium wp-image-3364" title="Identify Elements Automatically for XML" src="/wp-content/uploads/2014/11/Identify-Elements-Automatically-for-XML-300x91.png" alt="" width="300" height="91" />](/wp-content/uploads/2014/11/Identify-Elements-Automatically-for-XML.png)

### Miscellaneous

  * **Custom Domains for HTTPS Supported**
  * We have previously supported custom domains only for HTTP.
  * Custom domains can now be set also for HTTPS.
  * Custom domains are currently only available for the Ultimate edition. Read more about [s](http://support.memsource.com/topic/is-it-possible-to-set-up-a-custom-domain-for-https)[etting up a custom domain over HTTPS](http://support.memsource.com/topic/is-it-possible-to-set-up-a-custom-domain-for-https).

  * **New Languages Added**
  * Fante (fat)
  * Soninke (snk)
  * Mixtec, Jamiltepec (mxt)

### API

  * **Asynchronous API Calls**
  * We have introduced [asynchronous API calls](http://wiki.memsource.com/wiki/Memsource_API#Asynchronous_APIs). These are the new asynchronous calls:
  * Get Asynchronous Request
  * Create New Analysis
  * Pre-translate a Job

  * We may add more asynchronous API calls in our future releases, for instance for creating new jobs.

  * **Price List API**
  * We have introduced new [Price List APIs](http://wiki.memsource.com/wiki/Price_List_API_v2) with a number of calls:
  * Create New Price List
  * Get Price List
  * List Price Lists
  * Update Price List
  * Delete Price List
  * Add Language Pairs
  * Remove Language Pairs
  * Get Price
  * Set Minimum Price
  * Set Price

  * **List Projects by Client**
  * A new parameter &#8220;client&#8221; has been added to the [List Projects API call](http://wiki.memsource.com/wiki/Project_API_v3#List_Projects), so that it is possible to list/search projects by client name.

  * **TM And TB Removal from Project**
  * Translation memories and term bases can now be removed from a project through API.

  * **Notify Assigned Linguist**
  * An option to add email addresses in cc has been added to the [Notify Assigned Linguist API call](http://wiki.memsource.com/wiki/Job_API_v6#Notify_Assigned_Linguist).

  * **Overwrite Segments in Pre-translate API**
  * A new parameter &#8220;overwrite&#8221; has been added to the [Pre-translate API cal](http://wiki.memsource.com/wiki/Job_API_v6#Pre-translate)[l](http://wiki.memsource.com/wiki/Job_API_v6#Pre-translate). When true, non-empty segments will not be skipped but overwritten during the pre-translate operation.