---
id: 10201
title: Batch Import of Users
date: 2016-12-20T11:32:15+00:00
author: admin
layout: post
guid: http://memsource.elcaptain.cz/?p=10201
permalink: /2016/12/20/batch-import-of-users/
categories:
  - New Features
tags:
  - admins
  - project managers
---
If you&#8217;re in need of quickly creating multiple users in one go, you can import them from XLSX. Just follow these steps:

  1. Go to **Users** and click on the **Import** button.
  2. Download a sample XLSX file which serves as an import template.
  3. Open the template and fill the required information (Note column is optional). 
      *  The template gives you a hint what the expected values are and we have also implemented some basic checks directly into it.
      * Mind the capitalisation in Role, Active and Receive newsletter columns.
  4. Go back to **Import Users** window, which is still open, select the file and click **Import**.
  5. Memsource displays number of successfully imported users and list of rows with error description, if there are any.

**Note: **After fixing errors in the XLSX file, be sure to delete rows that were previously imported successfully; otherwise, Memsource would generate &#8220;The specified username is not unique (already exists in the system)&#8221; error since you would try to import the same users again.