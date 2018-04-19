---
id: 13133
title: Drupal Connector
date: 2017-02-14T16:06:51+00:00
author: admin
layout: post
guid: http://memsource.elcaptain.cz/?p=13133
permalink: /2017/02/14/drupal-connector/
slide_template:
  - default
  - default
  - default
categories:
  - New Features
tags:
  - admins
  - enterprises
  - project managers
---
Users can now sync Memsource accounts with yet another CMS – Drupal. <span style="font-weight: 400;">Please note that the Drupal connector works only with </span>**Drupal 8 (and later) **and the [integration](http://wiki.memsource.com/wiki/Connectors) allows both manual file and automatic import (_updated 22/3/17_).<!--more-->

Follow 10 steps below to successfully enable Memsource Connector module on your Drupal site and synch it with your Memsource account.

1) Go to your Drupal server and find Admin / Configuration / Regional and Language / Languages page.

[<img class="alignnone wp-image-13134 size-large" src="http://www.memsource.com/wp-content/uploads/2017/02/Drupal_Languages-page-1024x597.png" alt="drupal_languages-page" width="750" height="437" data-id="13134" />](http://www.memsource.com/wp-content/uploads/2017/02/Drupal_Languages-page.png)

<span style="font-weight: 400;">2) Add all languages you want to use and set one of them as </span>**Default** <span style="font-weight: 400;">(this is equivalent to &#8220;source language&#8221; in Memsource and will be probably the same as the main language of your Drupal site).</span>

<span style="font-weight: 400;">3) Go to Admin / Configuration / Regional and Language / Content language and translation page.</span>

<span style="font-weight: 400;">4) Select </span>**translatable content types**<span style="font-weight: 400;">. Memsource currently supports &#8220;Content&#8221; and its subtypes (&#8220;Article&#8221; and &#8220;Basic page&#8221;).</span>

 <span style="font-weight: 400;">5) Go to </span>**Downloads** <span style="font-weight: 400;">section on</span> [<span style="font-weight: 400;">https://www.drupal.org/project/memsource_connector</span>](https://www.drupal.org/project/memsource_connector) <span style="font-weight: 400;">and copy the link address of the version you would like to install.<a href="http://www.memsource.com/wp-content/uploads/2017/02/Drupa_Copy-URL-1.png"><img class="alignnone wp-image-13141 size-full" src="http://www.memsource.com/wp-content/uploads/2017/02/Drupa_Copy-URL-1.png" width="636" height="261" data-id="13135" /></a></span>

<span style="font-weight: 400;">6) Go to Admin / Extend / Install new module.</span>

<span style="font-weight: 400;">7) Paste the URL copied in step 5) into </span>**Install from a URL** <span style="font-weight: 400;">field and install the module.</span>

<span style="font-weight: 400;">8) Go back to the Admin / Extend page, find &#8220;Memsource Connector&#8221; in the MULTILINGUAL category. Select the checkbox and click </span>**Install**<span style="font-weight: 400;">.</span>

 <span style="font-weight: 400;">9) Go to Admin / Configuration / Regional and Language / Memsource Connector page. Copy the value of </span>**Memsource Connector authentication token** <span style="font-weight: 400;">field to the clipboard.<a href="http://www.memsource.com/wp-content/uploads/2017/02/Drupal_Memsoruce-token.png"><img class="alignnone wp-image-13142 size-large" src="http://www.memsource.com/wp-content/uploads/2017/02/Drupal_Memsoruce-token-1024x588.png" alt="drupal_memsoruce-token" width="750" height="431" data-id="13142" /></a></span>

<span style="font-weight: 400;">On this page, you may also set what posts should be </span>**translatable based on their statuses** <span style="font-weight: 400;">(only Published posts, only Unpublished posts, or both) and set the </span>**status of translated posts** <span style="font-weight: 400;">(Published or Unpublished).</span>

<span style="font-weight: 400;">10) Log in to your Memsource Cloud account and create a new </span>**Drupal connector** <span style="font-weight: 400;">with the copied token and your Drupal site URL.</span>

Drupal connector is available for Team, Ultimate and all Business editions.