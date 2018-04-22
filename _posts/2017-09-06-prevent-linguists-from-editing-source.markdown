---
author: zbynek.fridrich@gmail.com
comments: true
date: 2017-09-06 07:09:45+00:00
layout: post
link: https://www.memsource.com/blog/2017/09/06/prevent-linguists-from-editing-source/
slug: prevent-linguists-from-editing-source
title: Prevent Linguists from Editing Source
wordpress_id: 17557
categories:
- New Features
tags:
- Memsource Editor
- Memsource Web Editor
- API
- project managers
- linguists
- administrators
- UI
---

An option has been introduced for project managers and administrators to prohibit any editing of source by linguists – either by editing in editors or by manually uploading a bilingual file via our UI or API. The option **Linguists may edit source** (selected by default) is located in the **Access and Security** section in the project as well as global settings. If the option is deselected, linguists are not allowed to:



 	
  * **Edit source in the Desktop Editor or Web Editor** – when pressing F2, **“Source edits disabled by project owner.”** message is displayed in the Web Editor, editing is not allowed in the Desktop Editor.

 	
  * **Upload bilingual MXLIFF or DOCX** files including any source modification in the Cloud UI, API, Desktop Editor or Web Editor – **“****Source edits prohibited by project owner. Upload failed.” **message is displayed when attempting to do so.

 	
  * Joining and splitting segments also count as source modification that will be prohibited.


