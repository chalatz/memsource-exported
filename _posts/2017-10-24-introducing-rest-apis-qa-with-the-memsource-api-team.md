---
id: 17239
title: 'Introducing REST APIs &#8211; Q&#038;A with the Memsource API Team'
date: 2017-10-24T18:28:50+00:00
author: admin
layout: post
guid: https://www.memsource.com/?p=17239
permalink: /2017/10/24/introducing-rest-apis-qa-with-the-memsource-api-team/
slide_template:
  - default
  - default
  - default
fake_id:
  - ""
main_logo_heading:
  - ""
transparent_logo_heading:
  - ""
floating_logo_heading:
  - ""
bottom_logo_heading:
  - ""
favicon_heading:
  - ""
categories:
  - Featured Articles
  - Memsource Blog
  - New Features
---
<span style="font-weight: 400;">APIs have always been one of the strongest features of the Memsource Cloud platform. Many global companies and translation agencies have used them since the earliest days of Memsource to connect and customize the platform for their localization needs. </span><!--more-->

<div style="background-color: #cccccc; text-align: left; vertical-align: middle; padding: 20px 47px;">
  <b>Webinar:</b> <span style="font-weight: 400;"><a href="https://attendee.gotowebinar.com/register/4180124791812473090" target="_blank" rel="noopener">Faster Data Transfer with REST APIs</a><br /> Wednesday, October 25, 2017, 17:00 CEST</span>
</div>

### API Usage in Memsource

<span style="font-weight: 400;">With the advancement of technology and an ever-increasing number of <a href="https://www.memsource.com/integrations/" target="_blank" rel="noopener">connectors and integrations</a>, APIs are being used more and more by Memsource users to customize the system according to their policies or specific workflows. Over the past two years, API usage in Memsource Cloud has increased from around 30,000,000 monthly calls to between an average of 40,000,000-50,000,000 monthly calls.</span><figure id="attachment_17246" style="width: 781px" class="wp-caption alignnone">

[<img class="wp-image-17246 size-full" src="https://www.memsource.com/wp-content/uploads/2017/10/Monthly-API-Calls-2-years1.png" alt="" width="781" height="401" data-id="17246" />](https://www.memsource.com/wp-content/uploads/2017/10/Monthly-API-Calls-2-years1.png)<figcaption class="wp-caption-text">Number of monthly API calls in Memsource Cloud from January 2016 &#8211; October 2017</figcaption></figure> <figure id="attachment_17252" style="width: 750px" class="wp-caption alignnone">[<img class="wp-image-17252 size-large" src="https://www.memsource.com/wp-content/uploads/2017/10/Daily-API-Calls-6-months-1024x429.png" alt="" width="750" height="314" data-id="17252" />](https://www.memsource.com/wp-content/uploads/2017/10/Daily-API-Calls-6-months.png)<figcaption class="wp-caption-text">Daily API calls from May 2017 &#8211; October 2017</figcaption></figure> 

<span style="font-weight: 400;">Additionally, the Memsource platform uses the same APIs it offers to its clients. This allows us to ensure the highest quality data transfers are utilized and encourages us to constantly develop and improve it for our clients. Within Memsource, APIs are used in Memsource Cloud, both web and desktop editors, and the new mobile app.</span>

<span style="font-weight: 400;">In response to the increasing use, the desire for ever-increasing data speeds, and a drive to provide the best connections possible, the Memsource API team is developing new REST APIs for all users with API-enabled editions. A few have been released and the rest will come over the following weeks.<br /> <em>Edit: As of January 16, 2018, <a href="https://www.memsource.com/blog/2018/01/16/update-all-memsource-rest-apis-now-available/" target="_blank" rel="noopener">all REST APIs are now available</a>.</em></span>

### A Chat with the API Team

<span style="font-weight: 400;">The Memsource Marketing team loves talking about localization technology, but we needed some reinforcement for this post. We spoke with developer Jiří Zmeškal and the rest of the API team about what this means for current Memsource users and developers who wish to take advantage of the new API technology and documentation format.</span>

**What is a REST API?**
  
A REST &#8211; or Representational state transfer &#8211; API is a way to enable interoperability between computer systems using HTTP protocol. It uses HTTP methods such as GET, POST, PUT, DELETE and PATCH. (These are types of operations to achieve a desired action. For example, if you enter a URL into a web browser address bar, the browser will carry out an HTTP GET request to the URL.)

**What is the difference between the previous Memsource APIs and the new REST-based APIs?**
  
The main difference between them is their format. The previous APIs are parameter-based while the new APIs are based on JSON. Using both JSON and standard HTTP allows greater flexibility &#8211; with JSON you can perform more complex requests, faster.

We’ve released a few new APIs in our new documentation and the rest will come in the upcoming weeks.

**What were the reasons for doing an update? What are the benefits?**
  
We wanted to make our APIs more user-friendly and provide a more common API standard for developers. We know that a lot of developers are used to working with REST, so our update makes it easier for them to integrate our APIs.

Some additional benefits include:

  * _User-friendly documentation:_ We wanted to make the API documentation easier to use &#8211; we have done this by incorporating the OpenAPI (previously Swagger) specification. The API documentation is also automatically generated and can even be downloaded and exported.
  * _Faster response times_: Users will notice improvements such as faster response times as requests are processed more quickly.

**Ok, what about the nuts and bolts &#8211; how is the new REST API built differently?**
  
The structure of our new APIs is more effective. We have:

  * _Reduced the response size_: The previous APIs returned too much information. We have reduced the size by looking at both requests and responses in our previous APIs.
  * _Created a standard set of operations_: Each new API includes the list, get, create, update and delete operations.
  * _Improved HTTP methods_: HTTP GET can now be used for creating a list or retrieving details about a resource without changing the state of the resource. HTTP PUT is now available so it’s possible to do a complete update of a resource.
  * _Included more HTTP headers_: The new API can use more headers, including the ‘Accept’ header which allows users to specify the format of the answer they require from the HTTP call.

**You’ve made some updates to the API documentation &#8211; what are some of those changes?**
  
Previously, a request body would need to be created from scratch by a user. Now, our documentation provides API request and response samples which can be easily copied.

Users can now download the documentation in a machine-readable format (JSON or YAML) and import it into tools such as Postman and Swagger Editor. The documentation also includes access to <a href="https://swagger.io/swagger-codegen/" target="_blank" rel="noopener">third-party libraries</a> which users can use to generate code.

**Will I have to change anything in my Memsource account?**
  
No, your Memsource account is not affected and you don’t need to set up a new API. As long as you have access to a Memsource edition that supports API calls, you can benefit from the new ones. Also, the new APIs won’t affect any existing integrations.

**Can I still use the previous Memsource API?**
  
Yes, the previous Memsource APIs will remain in place and be fully supported. However, new features will be implemented with new REST APIs.

&#8212;

Do you have some questions we didn&#8217;t answer?
  
Check out our **API User Documentation**, both the new** **<span style="font-weight: 400;"><a href="https://cloud.memsource.com/web/docs/api" target="_blank" rel="noopener">REST API</a> and the </span><a href="https://wiki.memsource.com/wiki/Memsource_API" target="_blank" rel="noopener"><span style="font-weight: 400;">legacy API</span></a>, and [contact our Support Team](mailto:support@memsource.com) if you have any further questions.

<span style="font-weight: 400;">&#8212;</span>

**Try Memsource Today**

<span style="font-weight: 400;">E-commerce company <a href="https://www.memsource.com/blog/2017/01/18/case-study-localizing-ecommerce-websites/" target="_blank" rel="noopener">Tennis-Point</a> and translation agency <a href="https://www.memsource.com/blog/2017/07/25/ciklopea-localizes-wordpress-websites-up-to-30-faster/" target="_blank" rel="noopener">Ciklopea</a> use Memsource’s API to save time through automation and to power connectors and integrations.</span>

<span style="font-weight: 400;">Want to test out the new REST APIs for yourself? <a href="https://cloud.memsource.com/web/organization/signup?e=ULTIMATE" target="_blank" rel="noopener">Start a free trial</a>.</span>