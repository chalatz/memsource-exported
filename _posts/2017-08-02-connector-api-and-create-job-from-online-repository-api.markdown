---
author: jakubj
comments: true
date: 2017-08-02 11:38:08+00:00
layout: post
link: https://www.memsource.com/blog/2017/08/02/connector-api-and-create-job-from-online-repository-api/
slug: connector-api-and-create-job-from-online-repository-api
title: Connector API and Create Job from Online repository API
wordpress_id: 16322
categories:
- New Features
---

The Connector functionality has been enabled for use even through the APIs.

Two new calls have been added ([Get Connector Info and List Connectors](https://wiki.memsource.com/wiki/Connector_API_v1)) which can be used to receive detailed information about connectors created for specific account. More importantly, each of these calls returns a **localToken** ID which can then be used to directly [Create New Job from Online Repository](https://wiki.memsource.com/wiki/Job_API_v8#Create_New_Job_from_Online_Repository) as **connectorID.**

Addition of these calls allows users to not only use their repositories from within the Memsource UI, but also access this feature from their built integrations.
