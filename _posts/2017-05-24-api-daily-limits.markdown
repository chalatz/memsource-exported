---
author: KaterinaBenova
comments: true
date: 2017-05-24 18:20:15+00:00
layout: post
link: https://www.memsource.com/blog/2017/05/24/api-daily-limits/
slug: api-daily-limits
title: API daily limits
wordpress_id: 15252
categories:
- New Features
tags:
- API
---

API is enabled for all paid Memsource edition with different [daily limits](https://wiki.memsource.com/wiki/Memsource_API#API_limits_for_Editions).

The limits are checked every 30 minutes and reset every day at 0:00 GMT.

User can set an email notification when 80% or 100% of the limit is reached in Cloud Setup > API statistic.

The API response when limit is exceeded is error code 403 ApiLimitReached.

[![](http://www.memsource.com/wp-content/uploads/2017/05/API_statistic-300x169.png)](http://www.memsource.com/wp-content/uploads/2017/05/API_statistic.png)
