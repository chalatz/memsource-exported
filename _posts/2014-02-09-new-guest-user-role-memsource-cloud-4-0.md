---
id: 2181
title: 'New Guest User Role: Memsource Cloud 4.0 Released'
date: 2014-02-09T13:53:45+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=2181
permalink: /2014/02/09/new-guest-user-role-memsource-cloud-4-0/
image_link:
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
  - http://blog.memsource.com/wp-content/uploads/2011/08/MemSource-Cloud.png
rating:
  - "0"
  - "0"
  - "0"
slide_template:
  - ""
  - ""
  - ""
categories:
  - New Features
tags:
  - Memsource Cloud
  - new release
---
[<img class=" alignleft" title="Memsource Cloud – medium" src="/wp-content/uploads/2012/08/MemSource-Cloud-–-medium.png" alt="" width="221" height="70" />](http://www.memsource.com/)

Memsource Cloud 4.0 has been released on Sunday, 9 February 2014 at 10:00 AM GMT. Memsource Cloud 4.0 includes over 100 improvements and bug fixes. These are the most important new features:<!--more-->

### User Management

  * New guest user role 
      * We have introduced a completely new guest user role
      * We have renamed all &#8220;old&#8221; guest user accounts (created before 9 February 2014) to &#8220;restricted access&#8221;
      * The new guest user role, available in the [Team](http://wiki.memsource.com/wiki/MemSource_Editions#Team_Edition) and [Ultimate](http://wiki.memsource.com/wiki/MemSource_Editions#Ultimate_Edition) editions, works just like the project manager user role except that it is limited to projects, translation memories and term bases of a specific client
      * Just like the project manager user role, the new guest user role is highly customizable
      * The new guest role can be provided to users to do any of the following (but always limited to the data of a single, pre-selected client): 
          * View/modify/create projects
          * View/modify/create translation memories
          * View/modify/create term bases

[<img class="alignnone size-medium wp-image-2191" title="guest-user-rights" src="/wp-content/uploads/2014/02/guest-user-rights-150x300.png" alt="" width="150" height="300" />](/wp-content/uploads/2014/02/guest-user-rights.png)

  * The &#8220;old&#8221; guest user role 
      * All &#8220;old&#8221; guest user accounts have been renamed to &#8220;restricted access&#8221; and will be permanently removed from Memsource after 1 April 2014
      * It is **highly recommended** that Memsource administrators/project managers change all their &#8220;restricted access&#8221; user accounts to the (new) guest accounts
      * It is not possible to create new &#8220;restricted access&#8221; user roles
      * The &#8220;restricted access&#8221; user accounts are not counted to the purchased user licenses

### File Conversion

  * MS Office macro files 
      * The macro-enabled MS Office file formats are now supported
      * The extensions of the newly supported file formats are: docm, dotm, xlsm, xltm, pptm, potm
  * Target font mapping for IDML 
      * A target font can now be set for IDML files in the IDML file import settings
      * If a target font is not explicitly set by the user, a default target font will be used. For instance, MS Mincho will be used for Japanese by default
  * MS Office file import settings 
      * We have removed the option &#8220;Import editable texts from drawings&#8221;
      * Such content will always be imported for translation from now on

### Aligner

  * Multiple files can be selected for alignment 
      * Saves a lot of time when there are many files for alignment
      * The file pairs (source/target) must have identical names and are imported in a zip file with a &#8220;source&#8221; and &#8220;target&#8221; folders

[<img class="alignnone size-medium wp-image-2198" title="align-multiple" src="/wp-content/uploads/2014/02/align-multiple-300x57.png" alt="" width="300" height="57" />](/wp-content/uploads/2014/02/align-multiple.png)

### Project Management

  * New languages supported 
      * IUM (Iu Mien)
      * MH (Marshallese)
      * CHK (Chuukese)
      * CHR (Cherokee)
      * QUC (K&#8217;iche&#8217;)
      * MI (Maori)
      * IU (Inuktitut)
      * NSO (Northern Sotho)
  * Email notifications 
      * When job status is changed by a linguist, the project owner receives an email notification (this behavior has been in place for a long time already). And from now on email notification get also sent when the user who is assigned a job is a project manager (previously, no email notification was sent)

### Quality Assurance

  * New QA checks have been introduced: 
      * Inconsistent tag content 
          * Checks whether tag content between source and their corresponding target tags is identical
          * Target tags that with different tag content are displayed in orange in Memsource Editor
      * Empty tag content 
          * Displays a warning when tag content is empty
      * XLIFF tags 
          * This check is applied only to XLIFF source files
          * It checks, for example, whether paired tags (such as bpt and ept) are in correct order in the completed target file
          * Specifically, it checks whether bpt and ept with same rid (or id) value form a pair (where bpt is opening and ept is closing)  and that such pairs do not overlap with other pairs
      * These new QA checks are supported in the current version of Memsource Web Editor and in Memsource Editor 3.144 and higher
  * All tag-related QA checks selected by default 
      * All tag-related QA checks will be selected by default for new projects