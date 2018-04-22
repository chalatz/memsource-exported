---
author: jitkaj
comments: true
date: 2016-12-20 10:32:15+00:00
layout: post
link: https://www.memsource.com/blog/2016/12/20/batch-import-of-users/
slug: batch-import-of-users
title: Batch Import of Users
wordpress_id: 10201
categories:
- New Features
tags:
- project managers
- admins
---

If you're in need of quickly creating multiple users in one go, you can import them from XLSX. Just follow these steps:



 	
  1. Go to **Users** and click on the **Import** button.

 	
  2. Download a sample XLSX file which serves as an import template.

 	
  3. Open the template and fill the required information (Note column is optional).

 	
    *  The template gives you a hint what the expected values are and we have also implemented some basic checks directly into it.

 	
    * Mind the capitalisation in Role, Active and Receive newsletter columns.




 	
  4. Go back to **Import Users** window, which is still open, select the file and click **Import**.

 	
  5. Memsource displays number of successfully imported users and list of rows with error description, if there are any.


**Note: **After fixing errors in the XLSX file, be sure to delete rows that were previously imported successfully; otherwise, Memsource would generate "The specified username is not unique (already exists in the system)" error since you would try to import the same users again.
