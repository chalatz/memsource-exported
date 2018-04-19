---
id: 2071
title: Memsource Cloud 3.10 Released
date: 2014-01-03T11:30:17+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=2071
permalink: /2014/01/03/memsource-cloud-3-10-released/
image_link:
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
slide_template:
  - ""
  - ""
  - ""
categories:
  - Memsource Blog
  - New Features
tags:
  - Memsource Cloud
  - new release
---
[<img class=" alignleft" title="Memsource Cloud – medium" src="/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png" alt="" width="221" height="70" />](http://www.memsource.com/)

Memsource Cloud 3.10 has been released on Sunday, 1 January 2014 at 2:30 PM GMT. Memsource Cloud 3.10 includes over 90 improvements and bug fixes. These are the most important new features:<!--more-->

### User Management

  * Project manager user role customization 
      * The project manager user role can now be restricted to access only projects, translation memories or term bases of a specific client

[<img class="alignnone size-medium wp-image-2074" title="restrict-pm-by-client" src="/wp-content/uploads/2014/01/restrict-pm-by-client1-300x82.png" alt="" width="300" height="82" />](/wp-content/uploads/2014/01/restrict-pm-by-client1.png)

### File Conversion

  * ICML files supported 
      * We have started supporting InCopy Document files (ICML)
  * IDML &#8211; extract master spreads 
      * The option &#8220;extract master spreads&#8221; is now selected by default for newly imported IDML files
  * Locked elements/attributes in XML 
      * Elements and/or attributes that should be imported as locked can now be configured in the file import settings of XML files

[<img class="alignnone size-medium wp-image-2076" title="xpath" src="/wp-content/uploads/2014/01/xpath-300x128.png" alt="" width="300" height="128" />](/wp-content/uploads/2014/01/xpath.png)

### Quality Assurance

  * Checking tags and formatting 
      * The following QA checks will be selected by default for all new projects from now on: 
          * Tags & formatting
          * No text between tags

### API

  * Split file 
      * A new API call has been introduced that makes it possible to split files in two ways: 
          * [Split file into x parts](http://wiki.memsource.com/wiki/Job_API_v6#Split_By_Parts_Count)
          * [Split file every x segments](http://wiki.memsource.com/wiki/Job_API_v6#Split_By_Part_Size)