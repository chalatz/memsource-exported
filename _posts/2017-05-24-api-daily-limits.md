---
id: 15252
title: API daily limits
date: 2017-05-24T19:20:15+00:00
author: admin
layout: post
guid: http://memsource.elcaptain.cz/?p=15252
permalink: /2017/05/24/api-daily-limits/
slide_template:
  - default
  - default
  - default
categories:
  - New Features
tags:
  - API
---
API is enabled for all paid Memsource edition with different [daily limits](https://wiki.memsource.com/wiki/Memsource_API#API_limits_for_Editions).

The limits are checked every 30 minutes and reset every day at 0:00 GMT.

User can set an email notification when 80% or 100% of the limit is reached in Cloud Setup > API statistic.

The API response when limit is exceeded is error code 403 <tt>ApiLimitReached</tt>.

[<img class="alignnone size-medium wp-image-15253" src="http://www.memsource.com/wp-content/uploads/2017/05/API_statistic-300x169.png" alt="" width="300" height="169" data-id="15253" />](http://www.memsource.com/wp-content/uploads/2017/05/API_statistic.png)