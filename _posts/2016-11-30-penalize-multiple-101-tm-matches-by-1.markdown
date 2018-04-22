---
author: Sarah
comments: true
date: 2016-11-30 15:56:13+00:00
layout: post
link: https://www.memsource.com/blog/2016/11/30/penalize-multiple-101-tm-matches-by-1/
slug: penalize-multiple-101-tm-matches-by-1
title: Penalize Multiple 101% TM Matches by 1%
wordpress_id: 9968
categories:
- New Features
tags:
- project managers
- admins
---

[![penalize_import-300x155](http://www.memsource.com/wp-content/uploads/2016/11/penalize_import-300x155.png)](http://www.memsource.com/wp-content/uploads/2016/11/penalize_import-300x155.png)This new option can be set in _Job Import Settings_ > _TM Match Context and Optimization. _It is available only when importing the job and cannot be changed later.

Out new feature allows penalization of multiple 101% matches - for example if there are more 101% matches in several TMs in the project or if the option _Previous OR next segment context as 101% _is used_._

Generally the newest 101% match is found and displayed. But when option _Penalize multiple 101% TM matches by 1%_ is selected and more then one 101% with different target (translation) is found, then all 101% matches are displayed as 100% with an arrow signaling the penalization.

[![penalize101match-300x100](http://www.memsource.com/wp-content/uploads/2016/11/penalize101Match-300x100.png)](http://www.memsource.com/wp-content/uploads/2016/11/penalize101Match-300x100.png)

First two CAT results are 101% matches penalized by 1%.

This can be very useful with pre-translate feature: Memsource will pre-translate all 101% where there is only one match in TM, while segments with multiple matches will be sorted out by linguists or proofreaders.

This settings will be also reflected in Analysis: segment with multiple 101% matches will be counted as 100% match.
