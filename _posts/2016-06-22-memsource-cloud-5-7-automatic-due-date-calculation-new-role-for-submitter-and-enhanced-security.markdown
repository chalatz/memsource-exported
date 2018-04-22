---
author: vaclavb
comments: true
date: 2016-06-22 14:00:03+00:00
layout: post
link: https://www.memsource.com/blog/2016/06/22/memsource-cloud-5-7-automatic-due-date-calculation-new-role-for-submitter-and-enhanced-security/
slug: memsource-cloud-5-7-automatic-due-date-calculation-new-role-for-submitter-and-enhanced-security
title: 'Memsource Cloud 5.7: Automatic Due Date Calculation, New Role for Submitter
  and Enhanced Security'
wordpress_id: 7704
categories:
- Memsource Blog
---

Memsource Cloud 5.7 is scheduled for release on Sunday, 26 June 2016, at 10:00 AM GMT. In addition to a few improvements in the back end, several bug fixes and some more minor improvements, we are introducing an algorithm for the automatic calculation of due dates which users can use in automation widgets. We have also implemented support for OAuth 2.0 to provide for more security, and focused on further improving our [APIs](http://wiki.memsource.com/wiki/Memsource_API).

<!-- more -->


### Automatic Due Date Calculation


In the Automation Widget, users can currently choose the due date and time using a calendar at the bottom of the widget. While this will still remain an option, users will also be able to set a "Due Date Scheme" in which they can define quotas and rules based on which the due date and time will be computed automatically. If they choose one of their Due Date Schemes as part of the Services settings, the due date and time will be calculated and suggested automatically:



 	
  * You will find a new Due Date Scheme section under Setup


[![Image1](/wp-content/uploads/2016/06/Image1.png)](/wp-content/uploads/2016/06/Image1.png)



 	
  * This is how the automatically calculated due date/time will be presented to users:


[![Image2](/wp-content/uploads/2016/06/Image2-1024x488.png)](/wp-content/uploads/2016/06/Image2.png)



If you do not use any Due Date Scheme in your widget configuration, users will continue to see a calendar from which they will be able to pick the due date and time of their choice.




### 




### Memsource as OAuth 2.0 Provider


OAuth is a standard for the authentication of 3rd party apps used by all web giants for their platform API's (Google, Facebook, Twitter, Amazon, Microsoft, Yahoo, Salesforce, Paypal, etc.). By implementing OAuth, Memsource has made it much easier for 3rd party developers to create tools working with Memsource. An important message from the security point of view is that API users do not need to have their passwords saved anywhere, they just grant and further manage the access for each tool.




### APIs


We have introduced several changes in our APIs:



 	
  * New API call api/v8/job/listByProject returns a response with the paging section

 	
  * The API to create a new job now supports context type and optimization introduced in previous version

 	
  * To increase Memsource API security, a new parameter "uid" (with value such as 1O1hLcK8w1cXL8lMhzYz42)  is introduced in our API JSON responses. The old formats of ID ("id":2435) will still be valid and returned in JSON response and both types can be used in API calls, but we recommend to our users to start using the new format.





### Miscellaneous


We have added three new locales for Kurdish:



 	
  * Central Kurdish (ckb)

 	
  * Northern Kurdish (kmr)

 	
  * Southern Kurdish (sdh)


