---
author: Sarah
comments: true
date: 2016-10-12 12:21:29+00:00
layout: post
link: https://www.memsource.com/blog/2016/10/12/memsource-wordpress-connector/
slug: memsource-wordpress-connector
title: 'Memsource 6.4: WordPress Connector'
wordpress_id: 9204
categories:
- Memsource Blog
tags:
- new release
- Memsource Cloud
- Marketing
- CMS Connector
---

This week's release hails in a major new feature: the ability to connect to WordPress sites and easily translate them online.

<!-- more -->

In the past, content managers who wished to translate a WordPress website had to download content as a set of HTML pages, or as XLIFF files via WPML plugin. It was a complicated process with many manual operations and a high error rate.

With the new [plugin for WordPress](http://wiki.memsource.com/wiki/WordPress_Plugin) and the [Connector](http://wiki.memsource.com/wiki/Connectors) feature, content managers can import blog posts and pages into Memsource to translate them using translation memory, term bases and MT engines. Web pages are parsed during the translation, protecting markup, tags, formatting, images, tables and embedded video and other elements. Completed translations are pushed back to WordPress, creating a parallel page in a new language. Importing new content for translation can even [happen automatically](http://wiki.memsource.com/wiki/Automated_Project_Creation) on a regular basis.

This is an easier, faster, and far more efficient way to localize websites than by manually exporting content. Now you can automate the process and concentrate on making the website truly global.

The [Connector](http://wiki.memsource.com/wiki/Connectors) is available for the following editions: Team Start, Team, Ultimate, Biz Start, Biz Team, Biz Ultimate



[![](/wp-content/uploads/2016/10/Blog_connector-1.png)](/wp-content/uploads/2016/10/Blog_connector-1.png)

_Example: selecting posts to translate from the Memsource Blog via the connector_

To access files on the website, create a job using 'Create from Online Repository' option. Once the translation is complete, you can upload the content back to WordPress directly via Download > Export to Online Repository. The connector works together with WPML plugin, and will create and publish a new post in the target language using WPML site structure. For example, if your German pages are available via yoursite.com/de, an "About Us" page will be automatically published under the following structure:

Source: mysite.com/about-us >>
Target: mysite.com/de/about-us

You can change the url structure after publishing by editing the post in the WordPress dashboard.


### Installing the connector





 	
  1. To add the Memsource Plugin to your Wordpress site, log into your Dashboard, go to “Plugins”, and Select “Add New”.
[![plugins](/wp-content/uploads/2016/10/Plugins.png)](/wp-content/uploads/2016/10/Plugins.png)

 	
  2. On the plugin page, search for Memsource Connector and click Install Now.
[![memsource-wp-2](/wp-content/uploads/2016/10/Memsource-WP-2.jpg)](/wp-content/uploads/2016/10/Memsource-WP-2.jpg)

 	
  3. Once the plugin is installed, WordPress can be selected as a [connector in Memsource Cloud](http://wiki.memsource.com/wiki/Connectors).
_Note: the Memsource Cloud connector is available for the following editions: Team Start, Team, Ultimate, Biz Start, Biz Team, Biz Ultimate_

 	
  4. Your WordPress website will need a WPML plugin to manage multilingual pages. Languages in WPML must match languages of the project. To support local variations, for example French (Canada), define languages in WPML panel inside WordPress.Example:


[![languages_in_wpml](/wp-content/uploads/2016/10/languages_in_WPML.png)](/wp-content/uploads/2016/10/languages_in_WPML.png)

_Example: Editing languages in WPML_


### Translating WordPress Pages and Updated Posts


The Memsource connector can help manage multiple small updates to WordPress pages. Blog authors and content managers tend to correct and change some pages very often, which is difficult to support when localizing into several languages. With large websites and hundreds of changes a day, managing without automation is impossible. Use the following setup to streamline translation updates with Memsource:



 	
  * Identify altered pages by last modified date and send them as a batch for translation.

 	
  * Use a project template with an existing TM and the following settings checked in:




**Set segment status to confirmed for**
+ Non-translatables
+ 100% matches
+ 101% matches




**Lock**
+ 100% matches
+ 101% matches
+ Non-translatables


As you run the pages through translation memory, Memsource will confirm and lock segments that did not change. The translator will need only to filter unconfirmed segments and translate them in Memsource Editor or Web Editor. Once all files have been set to Completed, batch upload them to WordPress from Memsource. This will overwrite existing translated posts and pages on your website with an updated version.


### Automated Translation for New Content


Users of Team, Ultimate, Biz Team, Biz Ultimate, and Academic editions can create a rule to automatically check the website for new content on a regular basis, such as once per day at 7:00 AM, or every 15 minutes. All freshly published posts and pages not indexed in the previous search will be imported for translation using your project template, workflows, price lists, and a group of responsible linguists.

To set up this automation scenario, consult [our documentation](http://wiki.memsource.com/wiki/Automated_Project_Creation).



* * *





## New Features Page


Memsource now has a page listing new features as they are deployed.

/new

In June 2016, Memsource switched to a weekly release cycle with no system downtime and our regular email newsletter is published bi-weekly. In order to stay updated with the latest features as they appear in the system, please follow the New Features page, or subscribe via RSS. The page is maintained by the Memsource Support team and includes brief notifications, while the blog and the support website will continue to provide more detailed explanations.


## Custom Email Address for Notifications




Users of the BIZ Ultimate and Ultimate Editions will now be able to whitelabel the email address Memsource uses to send out notifications. Emails have been sent from a general email address (system@memsource.com), but with the release of Memsource 6.4, this email address can be customized. Organizations can send emails from their private domain for a more corporate look. If you wish to setup your Custom Email, please contact support@memsource.com, and see more details on our help website.


Please note that the desired combination of subdomain and domain may already be taken.


## Due Date Information for Linguists in Automation Widget Projects




When a customer orders translations via an [automation widget](https://www.youtube.com/watch?v=uTTDOksuvlI) and sets a due date, Memsource will now set the same due date not only for the project manager responsible for this automation widget, but also for the assigned linguists. If you're running projects without direct control of a PM, during off-business hours, or on weekends and holidays, the deadline will still be communicated to your translators and reviewers. This scheme suits best LSP - Buyer relationships where the translation company has already assigned a pool of linguists to the customer, and the translation volume is regular.







Please note that Memsource can only communicate the time limits for the whole project, not for each workflow step individually. If you have more steps, you will need to set the Job Due Date to manual, and then adjust the deadline for each workflow step.







It is possible to customize rules for deadlines and job urgency by creating Due Date Schemes under Setup.


![due-date-scheme](/wp-content/uploads/2016/10/due-date-scheme.png)


## New QA check: Unedited Fuzzy Matches


The new QA check in Memsource Editor and Web Editor flags a warning when linguists confirm a fuzzy matches without editing them.

A match is called fuzzy if the source text is similar, but not 100% identical to the segment stored in the translation memory. Confirming fuzzy matches without editing them might mean the translator is going too fast and is not checking the content thoroughly.


## API






It is now possible to list term base entries by concept ID, in addition to term ID.

The new call is api/v2/termBase/listTermsOfConcept


