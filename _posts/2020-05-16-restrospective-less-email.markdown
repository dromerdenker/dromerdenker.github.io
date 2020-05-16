---
layout: post
title: "The state of Less-Email.com"
date: 2020-05-16 04:043:00 +0200
description: Retrospective on a big project of mine. # Add post description (optional)
img: emails-iphone.jpg # Add image post (optional)
tags: less-email restrospective
---

In August of 2019, I launched [Less-Email.com](https://www.less-email.com), which took considerable effort. Now, nine months in, it's high time for a retrospective, with a keep/try list.

### Keep
 * Register a domain name 
 * Buy a professional logo on Fiverr.com
    both give a sense of seriousness that motivates me to push on, late evenings and early mornings to publish the result.
 * Explore new technology with a clear vision for the result
 * Write / Develop things that I care about having. Build what needs building, scratch my own itch.
 * automate whatever you can, constantly. Each terminal command I capture in a script. Document whatever I can.

### Try to do different

  * **Swap out WordPress for a JAM-stack.** WordPress seemed like a good idea, but I found that it has one terrible aspect: Wordpress' database (mysql) does not separate content (less-email recipes) from the configuration of its platform. Every plugin you install gets intertwined with the content database, so it is nearly impossible to deploy only code, or only content! Not to mention that Wordpress is just plain slow to load.
  
  I'd rather trade WordPress in for a slimmer JAM-stack (like this blog). It would be faster, cheaper to host, simple to secure, and much cleaner to maintain the back-end for. I don't __WANT__ a mysql database for posts, that in itself is a most terrible storage mapping. Markdown files are a lot easier to edit, update and plain text always beats proprietary databases.

  * Ask my network for suggestions of technology. They generally know what's going on. It can be hard to spot what's the latest trend. 
  * It is challenging when learning new technology to build unit tests. But on the other hand, unit testing consistently accelerates learning, development and forces understanding. So, even if it is hard, by the time you passed three steps beyond hello world, spend an evening on unit testing, and take it from there.
  
### How I feel about it

Overall I learned a lot about WordPress, refreshed some PHP (20 years ago!) and the fun was in seeing my creation come to life. I am pleased the site is so stable, it is a bit sad the site has not received much traction yet. 
To migrate its hosting, I will convert it into a static site (using WP2static). That increases performance. I suppose now is the time to keep nudging people to it.
