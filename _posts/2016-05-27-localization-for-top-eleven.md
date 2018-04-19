---
id: 7308
title: Top Eleven Football Manager Localization
date: 2016-05-27T10:52:40+00:00
author: admin
layout: post
guid: http://blog.memsource.com/?p=7308
permalink: /2016/05/27/localization-for-top-eleven/
epicredrank:
  - "0"
  - "0"
  - "0"
slide_template:
  - ""
  - ""
  - ""
categories:
  - Featured Articles
  - Memsource Blog
tags:
  - Customer Stories
  - game localization
---
Nordeus is a Serbian game developer behind [Top Eleven](http://www.topeleven.com/), a football management game which has more than 140 million registered users and 10 million active monthly players. It&#8217;s one of the most popular sports games in the world, and it is primar<span style="font-weight: 400;">ily played on mobile devices. Jasmin Jelača, localization engineer, is responsible for continuous localization of Top Eleven into </span>30 languages. We spoke with Jasmin to learn how he manages the stream of hundreds of small translation jobs.

<!--more-->

The principle of mobile first means that the app is designed primarily from the point of view of a player with a mobile phone. Mobile devices have small screens, and the space for text is limited. Developer often play around with Call-to-Action buttons and descriptions to get better user experience. A localization team has to respond by quickly localizing small changes in an emphatic way.  <span style="font-weight: 400;">Managing localization in mobile first environment is all about automating small tasks and keeping a flexible infrastructure.</span>

Here is how Nordeus does it:

<span style="font-weight: 400;"><strong>1) Users download localization anew when the launch the game on their phones. </strong></span>

The Top Eleven Team at Nordeus came up with a solution to pull localization from the server every time a user logs in.  Localization is no longer embedded in the game itself, but it is stored on the Nordeus’ servers. Users download it each time it changes. One language locale is about 70,000 words in size, and this is something that users can easily download with 3G or WiFi. In technical terms, when player launches Top Eleven, the app searches for the newest locales through the Settings file and gathers those from the server. The game pulls language data to the user’s device.

<img class="alignnone wp-image-7310 size-full" src="/wp-content/uploads/2016/05/nordeus.png" alt="nordeus" width="699" height="648" data-id="7310" />

_Language files are constantly updated and pushed to the user&#8217;s phone_

2) **Translation jobs are created in Memsource via API.**

<span style="font-weight: 400;">On the backend, every time something changes in the main resource file, a script detects changes and opens translation requests in Memsource via API. Using a <a href="http://wiki.memsource.com/wiki/Memsource_Cloud_User_Manual#Project_Templates">project template</a> the localization team can spawn and assign translation jobs automatically in all 30 languages.</span>

<span style="font-weight: 400;">A multilingual LSP handles all translations and runs quality control. Once the localization into all languages and the testing processes are complete, the script rebuilds the localization, pushes it to the game server and adds +1 to the version. The next time when a user signs into the game, the login procedure will get the latest updates. </span>

**3) Text de-duplication.**

<span style="font-weight: 400;">Nordeus uses only one master resource file in English. </span>

The localization team developed a simple debug tool that shows all the keys in the game and allows the search for duplicates. With this tool, the localization engineers replace the duplicate keys with just one centralized key that was linked to from different screens. <span style="font-weight: 400;">For example, there were three buttons to <Select all> players: for an exercise, to intensify training and for the match. In the code the button text was stored as three separate strings, although it was the same. With the debug tool it is now a single string, which spawns only one translation job.</span>

[<img class="alignnone wp-image-7359 size-medium" src="/wp-content/uploads/2016/05/showkeys-300x169.png" alt="showkeys" width="300" height="169" data-id="7359" />](/wp-content/uploads/2016/05/showkeys.png)[<img class="alignleft wp-image-7360 size-medium" src="/wp-content/uploads/2016/05/showkeyssettings-300x169.png" alt="showkeyssettings" width="300" height="169" data-id="7360" />](/wp-content/uploads/2016/05/showkeyssettings.png)

_Show keys tool for string de-duplication_

4) **Localization runs a dedicated testing server**

<span style="font-weight: 400;">This way the locteam gained autonomy from the developers, and greatly improved the speed for localization engineering. </span><span style="font-weight: 400;">Currently the server allows them to:</span>

<li style="font-weight: 400;">
  <span style="font-weight: 400;">test new locales internally.</span>
</li>
<li style="font-weight: 400;">
  <span style="font-weight: 400;">create game builds for l10n purposes.</span>
</li>
<li style="font-weight: 400;">
  <span style="font-weight: 400;">run regression testing.</span>
</li>

<img class="alignnone wp-image-7361" src="/wp-content/uploads/2016/05/dashboard-1-1024x576.png" alt="dashboard (1)" width="600" height="337" data-id="7361" />

Server dashboard in the test build, where Nordeus localization team sets up testing.

5) **Testing and optimization geared towards iPhone 5-6 and top Android models.**

<span style="font-weight: 400;">With over 2000 different mobile devices on the market, it is impossible to cover everything. Nordeus localization team focuses on top Apple and Android models that more than 70% of the player base uses.</span>

6) **Context is sent to translators in the CAT-tool, and is conveyed in briefings.**

Because texts are short, but translations need to produce a powerful effect, Nordeus <span style="font-weight: 400;">provides detailed written descriptions to the translators and holds kick-off meetings with the LSP when developing a feature, or especially when the translation and the testing start. </span><span style="font-weight: 400;">For example, one title for a training session said “Use your head”. The football game doesn’t mean “think” here, but literally it implies hitting the ball with a head. </span>

**7) Quality checks via a LQA service and in-game feedback buttons.**

<span style="font-weight: 400;">Nordeus </span><span style="font-weight: 400;">employs a secondary agency to run occasional quality checks on the translations. They use the LISA QA model to evaluate and provide feedback, which helps rate the main vendor and develop a relationship with them. </span><span style="font-weight: 400;">Another instrument are drawable notifications that appear in the game when users log in and navigate to certain screens in the game.</span>

* * *

<span class="il">Jasmin</span> is the Localization Project Manager at Nordeus, the developer company behind the popular sports game Top Eleven. With 4 years experience in enterprise localization, <span class="il">Jasmin</span> manages a team in Belgrade and Dublin and is responsible for vendor communications and technology. He loves playing video games and spends long nights watching NBA matches.

&nbsp;

The full version of this article first appeared in <a href="http://dig.multilingual.com/2016-06/index.html?page=38" target="_blank">Multilingual Magazine in June, 2016</a>

&nbsp;