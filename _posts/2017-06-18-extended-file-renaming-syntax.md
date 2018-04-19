---
id: 15780
title: Extended File Renaming Syntax
date: 2017-06-18T19:45:39+00:00
author: admin
layout: post
guid: http://memsource.elcaptain.cz/?p=15780
permalink: /2017/06/18/extended-file-renaming-syntax/
slide_template:
  - default
  - default
  - default
categories:
  - New Features
tags:
  - project managers
---
The file renaming syntax has been extended with the ability to remove characters from the name of the original file, when compiling the completed file.

This is especially useful if your source file has a language code embedded in the file name, which you wish to remove.

For example the original file is messages-us.properties, and you want to create messages-de.properties and messages-fr.properties.

In this case, you will use {fileName[:-3]}.