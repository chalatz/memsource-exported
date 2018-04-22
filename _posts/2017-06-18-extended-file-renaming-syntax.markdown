---
author: vaclavb
comments: true
date: 2017-06-18 18:45:39+00:00
layout: post
link: https://www.memsource.com/blog/2017/06/18/extended-file-renaming-syntax/
slug: extended-file-renaming-syntax
title: Extended File Renaming Syntax
wordpress_id: 15780
categories:
- New Features
tags:
- project managers
---

The file renaming syntax has been extended with the ability to remove characters from the name of the original file, when compiling the completed file.

This is especially useful if your source file has a language code embedded in the file name, which you wish to remove.

For example the original file is messages-us.properties, and you want to create messages-de.properties and messages-fr.properties.

In this case, you will use {fileName[:-3]}.
