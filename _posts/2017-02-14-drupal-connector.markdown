---
author: jitkaj
comments: true
date: 2017-02-14 15:06:51+00:00
layout: post
link: https://www.memsource.com/blog/2017/02/14/drupal-connector/
slug: drupal-connector
title: Drupal Connector
wordpress_id: 13133
categories:
- New Features
tags:
- project managers
- admins
- enterprises
---

Users can now sync Memsource accounts with yet another CMS – Drupal. Please note that the Drupal connector works only with **Drupal 8 (and later) **and the [integration](http://wiki.memsource.com/wiki/Connectors) allows both manual file and automatic import (_updated 22/3/17_).<!-- more -->

Follow 10 steps below to successfully enable Memsource Connector module on your Drupal site and synch it with your Memsource account.

1) Go to your Drupal server and find Admin / Configuration / Regional and Language / Languages page.

[![drupal_languages-page](http://www.memsource.com/wp-content/uploads/2017/02/Drupal_Languages-page-1024x597.png)](http://www.memsource.com/wp-content/uploads/2017/02/Drupal_Languages-page.png)

2) Add all languages you want to use and set one of them as **Default** (this is equivalent to "source language" in Memsource and will be probably the same as the main language of your Drupal site).

3) Go to Admin / Configuration / Regional and Language / Content language and translation page.

4) Select **translatable content types**. Memsource currently supports "Content" and its subtypes ("Article" and "Basic page").

5) Go to **Downloads** section on[ https://www.drupal.org/project/memsource_connector](https://www.drupal.org/project/memsource_connector) and copy the link address of the version you would like to install.[![](http://www.memsource.com/wp-content/uploads/2017/02/Drupa_Copy-URL-1.png)](http://www.memsource.com/wp-content/uploads/2017/02/Drupa_Copy-URL-1.png)

6) Go to Admin / Extend / Install new module.

7) Paste the URL copied in step 5) into **Install from a URL** field and install the module.

8) Go back to the Admin / Extend page, find "Memsource Connector" in the MULTILINGUAL category. Select the checkbox and click **Install**.

9) Go to Admin / Configuration / Regional and Language / Memsource Connector page. Copy the value of **Memsource Connector authentication token** field to the clipboard.[![drupal_memsoruce-token](http://www.memsource.com/wp-content/uploads/2017/02/Drupal_Memsoruce-token-1024x588.png)](http://www.memsource.com/wp-content/uploads/2017/02/Drupal_Memsoruce-token.png)

On this page, you may also set what posts should be **translatable based on their statuses** (only Published posts, only Unpublished posts, or both) and set the **status of translated posts** (Published or Unpublished).

10) Log in to your Memsource Cloud account and create a new **Drupal connector** with the copied token and your Drupal site URL.

Drupal connector is available for Team, Ultimate and all Business editions.
