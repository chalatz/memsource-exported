---
author: Sarah
comments: true
date: 2016-05-27 09:52:40+00:00
layout: post
link: https://www.memsource.com/blog/2016/05/27/localization-for-top-eleven/
slug: localization-for-top-eleven
title: Top Eleven Football Manager Localization
wordpress_id: 7308
categories:
- Memsource Blog
- Featured Articles
tags:
- Customer Stories
- game localization
---

Nordeus is a Serbian game developer behind [Top Eleven](http://www.topeleven.com/), a football management game which has more than 140 million registered users and 10 million active monthly players. It's one of the most popular sports games in the world, and it is primarily played on mobile devices. Jasmin Jelača, localization engineer, is responsible for continuous localization of Top Eleven into 30 languages. We spoke with Jasmin to learn how he manages the stream of hundreds of small translation jobs.

<!-- more -->

The principle of mobile first means that the app is designed primarily from the point of view of a player with a mobile phone. Mobile devices have small screens, and the space for text is limited. Developer often play around with Call-to-Action buttons and descriptions to get better user experience. A localization team has to respond by quickly localizing small changes in an emphatic way.  Managing localization in mobile first environment is all about automating small tasks and keeping a flexible infrastructure.

Here is how Nordeus does it:

**1) Users download localization anew when the launch the game on their phones. **

The Top Eleven Team at Nordeus came up with a solution to pull localization from the server every time a user logs in.  Localization is no longer embedded in the game itself, but it is stored on the Nordeus’ servers. Users download it each time it changes. One language locale is about 70,000 words in size, and this is something that users can easily download with 3G or WiFi. In technical terms, when player launches Top Eleven, the app searches for the newest locales through the Settings file and gathers those from the server. The game pulls language data to the user’s device.

![nordeus](/wp-content/uploads/2016/05/nordeus.png)

_Language files are constantly updated and pushed to the user's phone_

2) **Translation jobs are created in Memsource via API.**

On the backend, every time something changes in the main resource file, a script detects changes and opens translation requests in Memsource via API. Using a [project template](http://wiki.memsource.com/wiki/Memsource_Cloud_User_Manual#Project_Templates) the localization team can spawn and assign translation jobs automatically in all 30 languages.

A multilingual LSP handles all translations and runs quality control. Once the localization into all languages and the testing processes are complete, the script rebuilds the localization, pushes it to the game server and adds +1 to the version. The next time when a user signs into the game, the login procedure will get the latest updates. 

**3) Text de-duplication.**

Nordeus uses only one master resource file in English. 

The localization team developed a simple debug tool that shows all the keys in the game and allows the search for duplicates. With this tool, the localization engineers replace the duplicate keys with just one centralized key that was linked to from different screens. For example, there were three buttons to <Select all> players: for an exercise, to intensify training and for the match. In the code the button text was stored as three separate strings, although it was the same. With the debug tool it is now a single string, which spawns only one translation job.

[![showkeys](/wp-content/uploads/2016/05/showkeys-300x169.png)](/wp-content/uploads/2016/05/showkeys.png)[![showkeyssettings](/wp-content/uploads/2016/05/showkeyssettings-300x169.png)](/wp-content/uploads/2016/05/showkeyssettings.png)

_Show keys tool for string de-duplication_

4) **Localization runs a dedicated testing server**

This way the locteam gained autonomy from the developers, and greatly improved the speed for localization engineering. Currently the server allows them to:



 	
  * test new locales internally.

 	
  * create game builds for l10n purposes.

 	
  * run regression testing.


![dashboard (1)](/wp-content/uploads/2016/05/dashboard-1-1024x576.png)

Server dashboard in the test build, where Nordeus localization team sets up testing.

5) **Testing and optimization geared towards iPhone 5-6 and top Android models.**

With over 2000 different mobile devices on the market, it is impossible to cover everything. Nordeus localization team focuses on top Apple and Android models that more than 70% of the player base uses.

6) **Context is sent to translators in the CAT-tool, and is conveyed in briefings.**

Because texts are short, but translations need to produce a powerful effect, Nordeus provides detailed written descriptions to the translators and holds kick-off meetings with the LSP when developing a feature, or especially when the translation and the testing start. For example, one title for a training session said “Use your head”. The football game doesn’t mean “think” here, but literally it implies hitting the ball with a head. 

**7) Quality checks via a LQA service and in-game feedback buttons.**

Nordeus employs a secondary agency to run occasional quality checks on the translations. They use the LISA QA model to evaluate and provide feedback, which helps rate the main vendor and develop a relationship with them. Another instrument are drawable notifications that appear in the game when users log in and navigate to certain screens in the game.



* * *



Jasmin is the Localization Project Manager at Nordeus, the developer company behind the popular sports game Top Eleven. With 4 years experience in enterprise localization, Jasmin manages a team in Belgrade and Dublin and is responsible for vendor communications and technology. He loves playing video games and spends long nights watching NBA matches.



The full version of this article first appeared in [Multilingual Magazine in June, 2016](http://dig.multilingual.com/2016-06/index.html?page=38)


