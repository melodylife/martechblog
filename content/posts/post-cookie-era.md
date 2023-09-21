---
title: "Post Cookie Era"
date: 2023-08-27T22:18:17+08:00
categories:
keywords:
comments: true # Enable Disqus comments for specific page
pager: true # Enable pager navigation (prev/next) for specific page
description: [Please add file name as description here without extension]
mathjax: true # Enable MathJax for specific page
thumbnail: "https://www.ipvanish.com/wp-content/uploads/2021/12/what-are-internet-cookies_IPV-blog.png"
draft: false
---
## What role does cookie play in the advertisement industry ?
Cookie , in internet industry, sounds like an ancient era. The ID identifier was generated in last century and has been serving the web users for more than several decades. The cookie was introduced by Netscape who was the browser pioneer. It's been used to identify users on website. You can simply take it as an ID of a user in a specific domain/website. There are many different types of cookie used for different purposes. The website owners usually use it to differentiate users or user
sessions. 
However, with more and more concerns of online privacy, some types of cookie will be retired from the stage, which we can say that the curtain post cookie era is now rising.  
![Cookie in the Browser](cookie-browser.webp)
## What will the industry giant do to the cookie ? 
There are many types of cookies. Regarding to the recent changes of cookie, we will focus more on the 3rd party cookies. Hence, let's simply understand what is 3rd party cookie ? In short , the cookies are bound to the domain or even sub-domain. Hence, the cookies can be named according to the domain that they are bound to. If the cookie is assigned by the website you are visiting right now, we can call it first-party cookie. In opposite, if the cookies which are fired are bound to
another domain, we usually call them 3rd-party cookies. You may ask, why does browser fire cookies which are not bound to the website which I'm not visiting ? Where are those cookies go ? What data do they convey ? If you have the similar questions, you've already got the point of why browsers are retiring the 3rd-party cookies. The main reason is that they are not transparent. Here are some use cases taking advantage of 3rd party cookie
* Online user behavior tracking. This is quite straightfoward. Product like Google Analytics, they are mostly using cookies to track and identify online users. Since the tracking product are not using same domain as the customers' website, their cookie will be taken as 3rd party cookies.
* Online advertisement traccking. This is similar to the one above. The difference is it's used in wider area. Besides tracking the targeted users, it's also used to record conversions. It should convey more complex payload when transfering versus the last use case. 
* Cookie mapping across two different domains.This use case is not usually mentioned nowadays. Before the era of mobile, people are surfing internet via laptops. Two platforms can build cookie mapping relationship with each other via a pixel on the webpage. With the mapping relationship, platforms can target users across different domains precisely.

After clarifying the concept and use cases of 3rd party cookie, we are very close to what the tech giants do with it. However, as difference of business models, the approaches are different. Yup, I mean Google and Apple,who are sitting on different chairs. Hence they are carrying out different approaches to handle users privacy concerns.
In common, both Chrome and Apple will drop 3rd party cookie. Neither of both will fire 3rd party cookie. In safari,both mobile and Mac, they've disabled 3rd party cookies already. 
* Google
Google now haven't disabled 3rd party cookies. The main reason as we all know is that Google is the biggest online advertising company. Therefore , the 3rd party cookie is critical for the advertising business. Without workable replacement, Google will not drop 3rd party cookie in Chrome. After experiment for a couple of years, Google have decided to use privacy sandbox to replace original 3rd party cookie. In brief, privacy sandbox is a set of API that publishers need to implement
on their website. The APIs will interact with Google data system to form user groups for targeting. For the daily-used tracking, so far as I know, Google will leverage its account system as well as sandbox mechanism to solve the problem.
* Apple 
Apple doesn't care much about the online advertisement industry in its earning report. In that case, the approach of Safari is more brutal. Apple has already disabled 3rd cookies in both mobile and laptop by default. If you want to enable them, you need go through multiple geeky steps. 
![Cookie in Web](cookie-web.png)
## How to embrace the post cookie era ? 
The the cookie avoidance trend seems inevitible. We've already entered post cookie era. How can we minimize our loss in the coming era? Here are some items we may think of. 
* Turn the cookie identifier into other types. For example, some tracking companies are using finger print to identify users. The other approach is to use first party data to map the users in the tracking system. For every tracking call, attach the first party user id to the parameter queue that system will leverage them to identify users. 
* The other way is to turn the client based call into server side call. Call the tracking system from server. The server call can avoid usage of cookie as well. 
* For some specific use cases, turn the tracking domain same as the website domain. In such case, the tracking cookie is under first party domain. The cookie won't be droped by the browser.
* Publishers should integrate with Google privacy sandbox. Since Chrome is the browser with most market share, to integrate with Chrome's solution will offer publishers sustainable income on traffic monetization. 


