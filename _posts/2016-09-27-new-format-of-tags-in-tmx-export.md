---
id: 8968
title: New format of tags in TMX export
date: 2016-09-27T00:31:14+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=8968
permalink: /2016/09/27/new-format-of-tags-in-tmx-export/
categories:
  - New Features
tags:
  - project managers
  - translators
---
Memsource tags are in displayed as {1> and <1} or as {2} and are also saved to the Translation memory in this manner. TMX exported from Memsource Translation memory also used this format of tags.

To provide better compatibility with other CAT tools, the Memsource tags in the TMX exported from TM or from job (Downloaded as TMX) will be converted to <bpt>, <ept> and <ph> tags, which are standard for TMX format.