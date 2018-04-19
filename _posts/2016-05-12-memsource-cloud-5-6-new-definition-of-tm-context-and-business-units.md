---
id: 6731
title: 'Memsource Cloud 5.6: New Definition of TM Context and Business Units'
date: 2016-05-12T13:51:45+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=6731
permalink: /2016/05/12/memsource-cloud-5-6-new-definition-of-tm-context-and-business-units/
epicredrank:
  - "0"
  - "0"
  - "0"
categories:
  - Memsource Blog
tags:
  - new release
---
Memsource Cloud 5.6 is scheduled for release on Sunday, 15 May 2016, at 10:00 AM GMT. The most important of the new features introduced in this release is the new concept of translation memory context where users will be able to choose how in-context or perfect matches are constituted. We are also introducing a new metadata category, Business Units, which will help in the organization and structuring of especially large accounts with many users and resources.<!--more-->

### New Definition of 101% Matches

**Currently, 101% matches are defined as exact matches surrounded by the same previous and following segments. This means that if a sentence has previously been translated in some context, and it later appears as an identical sentence in an identical context, Memsource classifies this as a 101% match.**

This is now going to change. As Memsource is used by many for the translation of localization formats, where text strings are linked to specific IDs, keys, etc., we wanted to address the needs of such users translating texts where the actual succession of strings is irrelevant, but what matters is the actual link between the translated text and its ID counterpart. In addition, some users do not want any context, and instead they want to make sure that their translation memories never contain multiple translations of identical source texts. We have therefore introduced the following four options, which can be selected from the New Job page:

[<img class="aligncenter size-full wp-image-7143" src="/wp-content/uploads/2016/04/context.png" alt="context" width="471" height="275" data-id="7143" />](/wp-content/uploads/2016/04/context.png)

  * **Automatic** &#8211; context will be selected automatically, based on the file type (for example &#8220;previous and next&#8221; for MS Word documents, and &#8220;segment key&#8221; for Android strings or properties files)
  * **Previous and next segment** &#8211; context based on the previous and next segment
  * **Segment key** &#8211; context based on the segment ID or key
  * **No context** &#8211; no context will be saved in the TM, and only one 101% match will be kept for a specific source text

Please check [our documentation](http://wiki.memsource.com/wiki/TM_Match_Context_and_Optimization) for a detailed description.

### Business Units

Frequently, enterprise users will want to limit the access to projects by Business Units (departments or divisions). We have therefore introduced this as a new feature addressing this need and made it available to the subscriber of our BIZ Ultimate edition. Business Units can be created under Setup and can be applied to projects, translation memories and term bases.

Previously, it was possible to restrict Project Managers’ rights to access their own projects or the projects of a specific client. Since we wanted to provide additional customization of user access rights and possibly even division of users into separate groups, we have introduced the concept of Business Units. Unlike the Client field, multiple Business Units can be selected for users which will provide them with access to the relevant resources of a single or multiple Business Units, while preventing them from accessing data from other Business Units.

The following areas can be regulated by Business Units:

  * Access to projects
  * Access to translation memories
  * Access to term bases

### Reuse your File Import Settings

[<img class="aligncenter wp-image-7169" src="/wp-content/uploads/2016/05/reuse.png" alt="reuse" width="476" height="313" data-id="7169" />](/wp-content/uploads/2016/05/reuse.png)

When you place the mouse pointer over the job icon inside a project, you will see a tooltip providing information about the file type, the type of context selected (see the &#8220;New Definition of Context&#8221; above) and most importantly a link from which you can reuse the file import settings from which the file in question was imported, either to import a new file or to re-import the existing one.

### Macro Based File Renaming

Currently, if file renaming is enabled in Memsource Setup (Server Settings &#8211; File Renaming), completed files downloaded from Memsource are renamed according to the following rule: {path}/{fileName}-{sourceLang}-{targetLang}-{workflow}-{status}.

From now, you can create your own renaming syntax, using the available macros, plus some additional ones:

  * {path}
  * {fileName}
  * {sourceLang}
  * {targetLang}
  * {workflow}
  * {date}
  * {time}
  * {userName}

### Word Count in CJK Languages

We have improved our algorithm for counting words in CJK languages (Chinese, Japanese, and Korean). Previously, when the source text contained Latin characters, our algorithm counted each character as a word. We therefore modified it so that CJK characters are counted as words but words in Latin alphabets are counted on a word basis.

### New QA Check &#8211; Target Text Identical with Source

Translators sometimes copy source text to the target and may under some circumstances accidentally confirm this as a translation and such segments may be left unnoticed. This QA check will warn users if the source and target texts are identical. Segments containing only tags or numbers are excluded.

### New APIs

We have introduced several new APIs:

  * Business Units are now supported in the creation of new projects, editing and list of existing projects, and the creation and editing of users
  * Delete all translations from target
  * API getCompletedFile with a warning &#8211; if the completed file downloaded using API is invalid, we provide this information in the JSON response sent in reply to the API call
  * New api/v8/job/listByProject call, which includes &#8220;paging&#8221; info in the response, for easier listing of jobs

### Miscellaneous

  * We have managed to considerably **reduce the TM selection time** for organizations that manage hundreds of TMs in their accounts. While previously, the selection may have taken 30 seconds or even more, TMs are listed instantly now.
  * We have made some improvements to our **PHP import filter**
  * **Exact search in term base** &#8211; we now support a &#8220;wildcard&#8221; search and an &#8220;exact&#8221; search in term bases. Use quotes for an exact search.
  * **New languages** &#8211; North Ndebele and South Ndebele are now supported