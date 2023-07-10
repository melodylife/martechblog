---
title: "Header Bidding in Ad Network"
date: 2023-07-10T15:24:52+08:00
categories:
- online advertising
- tech
keywords:
- header bidding
- programmatic
- online advertising
- ad network
- GDN
- criteo
comments: true # Enable Disqus comments for specific page
pager: true # Enable pager navigation (prev/next) for specific page
mathjax: true # Enable MathJax for specific page
thumbnail: "https://d1gqx5wdpmskko.cloudfront.net/posts/header-bidding-in-ad-network/programmatic-buying.png"
draft: false
---

## What is header biddig
### What was it like before header bidding
Header bidding sounds like a term of ancient online advertisement industry. It truely is. This word was originated from PC era within early 2010s. Header bidding is a trick of publisher placement auction. In short word, it's a revolutionary businenss model based on cocurrent technology. 
Before header bidding emerging, publishers had to decide one of the inventory monetization channel before deploy their website. After the decision, publishers had to rely on one of the Adnetwork they chose. Moreover if the buyers/publishers wanted to skip the Adnetwork to save cost , it's not possible or it will cost too much to switch. In the monetization aspects, publishers were not able to voice on the auction. All the programmatic auctions are controlled by Adnetworks, like
Doubleclick Adx, Appnexus, Rightmedia exhange, etc.
### How did header bidding change the game
According to above the original waterfall programmatic aution model was far from optimization. At that time, some Adnetworks with smaller size comparing to Google or Microsoft, started providing a piece of js snippet. It could be added to html header tag. That's why it's named header bidding. The js snippet distributes the placement to a special group of buyers simultaneously. Per the response with auction prices , the publishers have the right to decide the auction winner instead of Adnetwork. Usually, publishers will set a little higher floor price for the header bidding group to ensure additionl income within the new business model. With this new model, 
  * Publishers take over the right to decide the final price of each impression. Moreover, publishers can combine it with traditional waterfall model to maximize their income
  * Buyers are able to set up direct buying channel without brokers. Smaller agencies/DSP can buy premium inventory directly from publishers.
Header bidding switched on a new era of programmatic auction in the industry
![Header Bidding](https://d1gqx5wdpmskko.cloudfront.net/posts/header-bidding-in-ad-network/header-bidding.png)
## Why do Adnetwork need header bidding
We are all aware that publishers use header bidding to ensure better income. But how about Adnetworks. Why do they need such business model? Actually, different Adnetwork reacted differently. Doubleclick Adx, which is Google, was scared when header bidding came out then. 
### Small Adnetworks love it. 
Before header bidding came out, the premium inventories were fully controlled by big players in the market , like Google, Microsoft, etc. The auction was not transparent for publishers. They have to accept the final price from the big players once they add the placement tag on their website. Meanwhile, small Adnetworks and advertisers can't avoid extra cost by the big players. 
Hence the header bidding was welcome by small publishers, Adnetworks and advertisers. But it was what big players was willing to do. However, the header bidding was double-sided coins as well that the implementing party need to invest more to set up bidding logic at their end and sacrifice some loading performance. 
## How can header bidding work in mobile era
When it was during platform shifting, inventories were changing from PC web to mobile. Some industry experts was predicting that header bidding couldn't work on mobile platform. However, they were right about the implementation approach but they underestimate the temptation of the business model within online advertisement industry. 
### Benefits of header bidding in current mobile time
To maximize the income of the publishers, advertisers/Adnetworks now is providing technical solution to enable header bidding.Especially for some newly entry players, they can use header bidding to intercept the traditional programmatic buying process but to buy premium inventory with decent price. Now the publishers can implement the bidding process on their server side and cache the outcome that maintain the performance. Besides, some mobile publishers can leverage the device capability to localize the auction process on the device and continue to call other Ad networks if the prices coming out is not satisfying. At the same time, by skipping the broker, advertisers can pay more to publishers from the margin saved from buying from brokers.   
![The benefit of header bidding](https://d1gqx5wdpmskko.cloudfront.net/posts/header-bidding-in-ad-network/header-bidding-benefit.jpeg)
## The future of inventory distribution
The inventory distribution solution keeps on changing all the time. Even the head bidding model is still applicable but it can't be fitted into all the scenarios. 
### Who's better to use header bidding ?
For small publishers, it's better to leverage one monetization channel so that it will minimize the operation cost and maximize the income. 
For some publishers with middle size or above, header bidding should be their best choice to improve the inventory monetization outcome. In such size, publishers should be able to build auction logic on their own and hold an operation team to take care of the business. 
### What does header bidding bring to inventory monetization
Header bidding brought one more option for publishers to monetize their inventory. At the same time, with it, advertisers/buyers are able to buy premium inventory with reasonable prices. It shined a ray of light to the long-lasting market. More players can survive and make this market more transparent to all the entities. Even some big players started to provide such option in their technical solutions. For example, ByteDance, is providing monetization SDK with auction from multiple channels.  
I believe we can proactively to consider such business model when doing publisher monetization cases and pick one from both traditional and this one as well. We should always try the one which best fitting the current scenario. 
