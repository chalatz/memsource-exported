---
author: Sarah
comments: true
date: 2016-03-07 08:18:00+00:00
layout: post
link: https://www.memsource.com/blog/2016/03/07/our-first-ever-zero-downtime-deployment-of-major-release/
slug: our-first-ever-zero-downtime-deployment-of-major-release
title: Our First-Ever Zero-Downtime Deployment of a Major Release
wordpress_id: 6159
categories:
- Memsource Blog
tags:
- new release
- Memsource Cloud
- user support
---

[![Zero Downtime Deployment 1](/wp-content/uploads/2016/03/Zero-Downtime-Deployment-1.png)](/wp-content/uploads/2016/03/Zero-Downtime-Deployment-1.png)

Upgrading software to a new version can bring lots of improvements, but at the same time can cause disruption to its users. In the pre-cloud era, a system administrator would need to install the upgrade. The software would need to be at least restarted. Sometimes data would need to be migrated, hardware re-configured. All sorts of issues could come up. For that reason, software publishers would try to minimize the number of new releases to just a few per year. This is still true for most non-cloud software.

<!-- more -->A cloud setup makes it possible to remove most of these drawbacks. For this reason, users of a cloud-based software product will typically get upgrades much more often. At Memsource, we typically deploy **2 minor releases per day** and a **major new release once a month**. Our minor deployments include bug fixes and minor features. The major deployments include major new features.

Our daily minor deployments cause no disruption to Memsource users: Memsource is available without interruption and users are not even logged out. This used to be different for our major deployments that would take place once a month on Sundays: Our users understood that, in exchange for the new features, Memsource would not be available for a limited period of time (30-60 minutes) once a month.

However, it has been our goal for some time to deploy our major monthly releases without any service interruption. And we have recently succeeded: Our latest release, **[Memsource Cloud 5.4](/memsource-cloud-5-4-api-analytics-for-all-clone-jobs-indd/), has been deployed without any downtime.** Users may have just noticed periods of increased network latency. 

So how did we do it? The idea sounds simple: Each and every server, one by one, is removed from the cloud production environment, upgraded to a newer version and then inserted back.

The difficulty starts with the realization that, for a certain period of time, one part of the infrastructure runs an older version and the rest runs a newer version. Without the right precautions, incompatibilities between the two parts may undermine the whole process.

Preparations for a zero-downtime deployment of our latest version actually started immediately after the release of our previous version, [Memsouce Cloud 5.3](/memsource-cloud-5-3-multilingual-excel-analytics-indesign-preview/), over a month ago. From that point on, we had to make sure that every new feature, change or bug fix was going to be implemented in a backwards-compatible way at multiple levels – from the database, through internal service communication, all the way up to the user interface.

A few days before the deployment, long-running DB operations were initiated to update the tables and relations to the expectations of the new version. Finally, after all the preparations, it took us **less than an hour to seamlessly bring you all the new and exciting features** of [Memsource Cloud 5.4](/memsource-cloud-5-4-api-analytics-for-all-clone-jobs-indd/).

And guess what? We plan to deploy our next major release with zero-downtime too. Keep your fingers crossed for us...
