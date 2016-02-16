---
title: my Txt redirect
author: Gadsby
layout: post
date: 2013-10-21
url: /my-txt-redirect/
categories:
  - Uncategorized
tags:
  - digital marketing
  - web design

---
This is a new service that i created for charities who are looking to deploy txt to give asks through Facebook. The tool helps them create a link which when posted on Facebook and clicked on by a user, will directly open the sms app on their phone, with the correct txt number already populated.  
  


The specific use case is for when charities are investing in Facebook Advertising, as using this method, they are able to target mobile browsers only.  
  


The site creates a new page with <meta http-equiv=&#8217;refresh&#8217; content=&#8217;0;url=sms:XXXXX&#8217; /> in the header, as well as including the relevant information in the Open Graph header properties so that the right information shows when posting to Facebook.  
  


Android phones and iOS devices react differently to this type of redirect. It is actually possible to pre-populate the body message on Android, using the body= parameter, however if this type of link is opened within iOS then the txt number is stripped as well.  
  


The next stage of improvement will probably be to allow the user to upload a custom thumbnail to go along with the post, as well as being able to create separate Android and iOS targetted posts&#8230;  
  


<http://www.mytxtrdr.com>