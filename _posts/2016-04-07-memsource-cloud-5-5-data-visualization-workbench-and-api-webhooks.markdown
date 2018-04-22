---
author: admin
comments: true
date: 2016-04-07 13:26:51+00:00
layout: post
link: https://www.memsource.com/blog/2016/04/07/memsource-cloud-5-5-data-visualization-workbench-and-api-webhooks/
slug: memsource-cloud-5-5-data-visualization-workbench-and-api-webhooks
title: 'Memsource Cloud 5.5: Data Visualization Workbench and API Webhooks'
wordpress_id: 6184
categories:
- Memsource Blog
tags:
- new release
- Memsource Cloud
- API
---

[![release5.5](/wp-content/uploads/2016/04/release5.5.png)](/wp-content/uploads/2016/04/release5.5.png)

Memsource Cloud 5.5 has been released on Sunday, 10 April 2016, at 11:00 AM GMT with zero downtime. This release brings a number of improvements of which these two stand out: A) Custom data visualization and exploration using Kibana, a free data visualization workbench. B) Advanced API improvements, such as webhooks as well as opening up our API to linguist users (our API was previously limited to administrator and project manager users).<!-- more -->


### Kibana - Data Visualization Workbench


**Users of the Memsource BIZ Ultimate edition will be able to visualize data from their accounts through Kibana, an open source data visualization workbench.**

Kibana allows you to visualize and explore all data indexed by our analytics data warehouse. Each organization only has access to the subset of its own data. Currently, all project-related data have been indexed. There is an almost endless number of queries that can be visualized using Kibana.

**Sample Visualizations**

These are some of the queries that can be built and visualized using Kibana:



 	
  * Projects/jobs by the project manager

 	
  * Projects by the machine translation engine used

 	
  * Jobs by the linguist/vendor, including overdue jobs

 	
  * Jobs by file type

 	
  * Top language pairs, etc.


[caption id="attachment_6743" align="aligncenter" width="719"][![top 10 language pairs](/wp-content/uploads/2016/04/top-10-language-pairs1.png)](/wp-content/uploads/2016/04/top-10-language-pairs1.png) This week's top 10 language pairs in the Memsource demo account.[/caption]

**Project-level Data**

As mentioned above, currently all of our project-related data have been indexed. This includes data, such as:



 	
  * Project

 	
    * Project creation date, last modification, created by, last modified by, source language, target languages, project settings, client, domain, subdomain, business unit, project status, due date, etc.




 	
  * Jobs

 	
    * Job creation date, last modification, created by, last modified by, source language, target language, assigned to linguist/vendor, due date, workflow step, file type, etc.




 	
  * Analyses

 	
    * Total wordcount, net wordcount, translation memory matches, machine translation matches, etc.







**Segment-level Data**

We also plan to index all of our segment-level data (translation data) in the near future. This will make it possible for our customers to obtain unique insight into their translation productivity and visualize data, such as:



 	
  * Translation memory leverage by customer

 	
  * Translation productivity by MT engine

 	
  * Translation time vs. translation memory and/or machine translation leverage based. Kibana also gives you the details on each individual job/file in your account, including when it was created, who was the author, who  processed, and perhaps deleted it.




### API


Memsource APIs have seen some major improvements in the current release.

**Webhooks**



 	
  * Webhooks (or callbacks) for monitoring status changes have been introduced. Previously, users needed to call GetJob in order to see if the reply contains any information about the status change. Now, as soon as a job status changes, we will send a call directly to the user's integration.


**API extended to Linguist Users**




 	
    * APIs are now available to linguist users, in addition to [all paid editions](https://www.youtube.com/watch?v=6hCjjMpEQ98). Linguists can for example take advantage of the Memsource/XBench integration for extended quality assurance.





**Miscellaneous**



 	
  * Linguists can now be assigned based on project templates when creating projects from APIs.

 	
  * Multilingual MS Excel files can also be imported via APIs.

 	
  * It is now possible to delete clients, domains and subdomains (metadata) using APIs.




### XLIFF 2.0


Memsource now has separate file import settings for XLIFF 1.2 and XLIFF 2.0. Both include the corresponding import and export attribute mapping.

[![xliff](/wp-content/uploads/2016/03/xliff.png)](/wp-content/uploads/2016/03/xliff.png)


### Indexes in InDesign Files


It is now possible to translate indexes in InDesign files without any need for post-processing in Adobe InDesign.


### New UI Languages


We have added three more languages in which the Memsource user interface can be viewed:



 	
  * French (translation by [Semantix](http://www.semantix.eu))

 	
  * Finnish (translation by [Semantix](http://www.semantix.eu))

 	
  * Dutch (translation by ProLinguo)


We would like to take this opportunity and thank all our localization partners for their continued support.


### Machine Translation


**TildeMT**



 	
  * We have made improvements in the way users log in to the service from Memsource.




### New Languages


We have started supporting the following languages:



 	
  * English - Hong Kong

 	
  * English - Indonesia

 	
  * English - Malaysia

 	
  * Buryat




### 
