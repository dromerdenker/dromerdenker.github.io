---
hidden: true
layout: post
title: "The state of Less-Email.com"
date: 2020-05-16 04:043:00 +0200
description: Retrospective on a big project of mine. # Add post description (optional)
img: emails-iphone.jpg # Add image post (optional)
tags: less-email restrospective
---

In August of 2019, I launched [Less-Email.com](https://www.less-email.com). That was a considerable project. Nine months in,  here is my retrospective; a keep/try list for future hobby projects.

### Keep
 * Register a domain name 
 * Hire a professional artist to design the logo 
    
    
    Both set the tone of seriousness that motivates me to push on, late evenings, to deploy a result.
 * Explore new technology 
 * Develop what I care about having. Build what needs building, scratch my own itch.
 * Automate constantly. Each terminal command I capture in a script. Document whatever I can.

### Try to do different

  * **Avoid WordPress.** WordPress seemed like a good idea, but I found Wordpress' database (mysql) mixes content (less-email recipes) and platform configuration. Every WP plugin installed gets immediately intertwined with the content database, making it very hard to CI-deploy only code, or only content! To top it off Wordpress is just plain slow to load.
  
  Next web site, I will trade WordPress for a JAM-stack, like this blog. It is fast, cheap to host, simple to secure, and comes with a cleaner separated back-end. Come to think of WordPress: I don't __WANT__ a mysql database for posts, that in itself is a most terrible storage mapping. Markdown posts are a lot easier to edit and update. Plain-text always beats  databases for raw content.

  * **Ask my network for tech choices advice.** It can be hard to spot what's the latest trend. That's how I picked WordPress: every one is doing it. The professionals I call my friends generally know what's hot and a good fit for my idea.  
  * When learning new technology it's challenging to build unit tests. But on the other hand, **unit testing consistently accelerates learning, development and forces understanding**. So, even if it is hard, by the time you passed three steps beyond hello world, spend an evening on unit testing, and take it from there.
  
### How I feel about the project [Less-Email.com](https://www.less-email.com)

I learned about WordPress, refreshed some PHP (20 years ago!), but that was no fun. The fun was in my creation coming to life. I am pleased the site is so stable, it is a sad it has little traction yet. I guess I should be marketing it more - i.e. shove it down people's throats!

To migrate the servers, I now converted it into a static site (using WP2static). That boosts performance. I suppose now is the time to keep nudging people to it.
