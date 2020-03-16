---
title: 'Power vs usability: building a website in 2020'
date: 2020-03-01 08:00:00 +0000
thumb_img_path: images/9.jpg
content_img_path: images/9.jpg
excerpt: Work at home parent is an entrepreneur who works from home and integrates
  parenting into his or her business activities. They are sometimes referred to as
  a WAHM (work at home mom) or a WAHD (work at home dad).
layout: post
subtitle: 'I got my hands dirty in web development stacks and channeled my inner Ben
  Thompson. #longread'
canonical_url: ''

---
I have a love-hate relationship with web development. I love it, because web apps are the “flagship store” of marketing: your brand is as good as you web app. On the other hand I always struggled with website control, development speed, and portability.

**Control:** Changing the simplest web app requires an engineer, and tedious workflows where changes are pushed to a private “staging site” and deployed live after QA (quality assurance). While some content publishing can be automated (blogs), other elements just as important like forms, analytics script management, page speed, and design are almost never fully controlled by their core internal user: marketing. I want to own my site, end to end.

**Development speed**: when you don’t control a process, you also don’t control its length. In B2B, the marketing site is usually the least exciting, less automated, tech-debt-prone task that no developer looks forward to, and for good reason. Making changes to a website can take days, and the developer who does it is usually the single point of failure in the deployment.

**Portability**: non technical users depend on CMS (Content Management Systems) to update web apps without the help of a developer. The most popular CMS products, WordPress and Drupal, are monolithic systems written in PHP that developers dread, full of third party plugins that can break at any point. Once you make the CMS choice, usually by asking your devs which one they hate the least, you’re stuck with it. The only time where I wasn’t forced to use a 20-year old interface to change a site, I was editing on GitHub and publishing with a merge request. Not for the average writer.

🔥

Ultimately, I want a powerful web app that I can control end-to-end. But since I'm not a developer, I also need it to be usable. This dichotomy had me look hard for a web stack that would let me have it all.

## The past: static vs dynamic

In a world where Squarespace buys a Super Bowl ad, you would think everyone can make a website, no developer needed. Instead, it's an empty marketing promise, and the price of a “website builder” never takes into account the loss of control, flexibility, and, above all, portability. Web builders are great SaaS businesses because the switching costs for users are enormous. Ask anyone who ever tried to migrate a WordPress site.

How did we get here?

![An image from Notion](https://blog.veronica.fyi/api/asset?assetUrl=https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fd5d1130e-0d38-4082-821a-b445c27b3216%2FThe_evolution_of_web_publishing.jpg&blockId=e9eb8117-e440-444a-8d3e-3c5637d89fcf)

A brief history of web publishing brings the memory back to “static” web apps rendered by the dominant browser: Microsoft Internet Explorer. It was the digital magazine of the Nineties, where all the end user can do is read. It was hard and ugly, but simple. All you needed was front-end code that the browser could render, and a back-end that connected to a database hosted somewhere.

Moving to “dynamic” sites and CMS systems was the “Web 2.0” revolution. It made it so much easier to create and host a website, and you could allow dynamic interactions like search, forms, comments. Companies like Blogger and Flickr invented single-purpose sites that evolved into what social media is today, and were bright examples of usability for the content creators.

Web 2.0 had just landed when people started browsing more on their smartphones and tablets than their desktop computers, and your web app had to be “responsive”. Unless you could make a ready-made template work for your business, you needed a front-end developer. E-commerce got its own renaissance a few years ago thanks to products like Shopify and WooCommerce: single-purpose side builders where the template model just shined. Cloud computing, the most impactful tech switch of the past 15 years, made back-end architecture cheaper, but also more complex: you had to configure the cloud server, set it up for spikes in traffic, make architecture choices. You still needed a full-stack engineer.

## Building a website in 2020: power vs usability

There's a reason the majority of web apps are built on WordPress. According to my former boss and mentor Jeff Zwelling, everything can be explained on a 2x2 matrix, so check out the one below. When it comes to picking a web stack, it’s a compromise between **power** and **usability**. Wordpress is still the happy medium, after 20 years. You should probably ask for dev help, but you can get away without if you pick a template and have simple goals.

![An image from Notion](https://blog.veronica.fyi/api/asset?assetUrl=https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fe1322e84-9b8e-4da8-958c-89a8c87403bb%2FBuilding_a_website_in_2020.jpg&blockId=74de44cc-4727-4e37-8756-bbbdc9fce609)

The future seems to point us in 3 directions, at the opposite sides of the quadrants.

## Unbundling of site builders (green)

Single-purpose site builders have been wildly successful, from LiveIntent to Spotify. The latest generation is that of mobile-first site builders, like Universe. Universe and similar apps (Weebly, Wix, etc) strip down the basic elements of a web app and optimize the creation for touch control. It works, but the end results is not powerful, not pretty, and certainly not portable. Basic website functionalities to users, like collecting responses to a form, are actually quite advanced for these site builders, and require integration that chips away to the feeling of something that makes you build a live app in one hour.

On the other hand, if you need to build a landing page, the fastest way is to go a landing page builder like Unbounce. B2B software website are so [cookie-cutter](https://saaslandingpage.com/) that almost every site builder will give you a free responsive template, with no need for a designer nor developer.

## No code: Webflow (orange)

In the last 5 years there has been an flurry of professional-level site builders like Webflow. Webflow has solved better than anyone else a problem that every designer wanted to solve: control and independence over developers (marketers can also sympathize with this feeling). It’s a visual editor that spits out front-end code, so completely exportable. They then built a CMS and back-end functionality like hosting and CDN (Content Delivery Network, that speeds up loading times), which made Webflow an end-to-end website builder that anybody can use, with some training, and is the best solution for web design agencies.

I was able to build [a website](http://valkyrieicelandic.com/) from a Webflow template in less than 8 hours, but most importantly I could turn it over to someone completely non-technical, that can learn to add content and even change the design without depending on me.

The price of usability in web development has been either sticking with pre-built templates and out-of-the-box features, or facing a slow deployment process because you have to go to a developer to change a comma on your site. Webflow lets you compromise, and give the Gift of Power **and** Control. Is it easier and faster than using a single-purpose tool like Shopify? No. Can you build it on your phone? Absolutely not. The tradeoff between usability and power is still there, for now.

## History repeating: JAMstack (teal)

Like designers got tired of needing front-end devs to make their dreams come true, front-end developers got tired of back-end. They hacked their way into building end-to-end apps with the languages they already know (HTML, CSS, JavaScript in all possible framework permutations), and skip the tedious back-end work of dealing with server setup and database configuration — “serverless”. Need search on your site? Why build it, when [Algolia](https://www.algolia.com/) has a great API you can connect to? Don’t make your own coffee when the best barista in the world is an API call away.

They called it JAMstack (devs love acronyms). Its benefits are particularly attractive to those who, like me, care a lot about power and control.

1. **Page speed**. Static sites are blazing fast, because the content is not stored in a remote server, but in this elusive place called "the Edge". To me, the Edge is U2's guitarist. It turns out that the Edge can immediately serve HTML, CSS, JavaScript, and even assets (basically all the static elements of a web app) because it has copies of them. No need to call the remote server and make the user wait. Save money on that cloud bill. Blazing fast means less than a second. Mobile users, rejoice. Google SEO algorithms love you when you're this fast, making any marketer successful. A CDN, now used by less than 10% of web apps, is all you need to connect to the Edge, and is extremely cheap and easy to configure.
2. **Security**. A nice side benefits of storing static files on the Edge, it turns out, is that they can't be easily hacked. At my last job, our staging Wordpress instance was hacked because we didn't update a plugin. It didn’t matter it was password protected. A script was able to log it and inject a bunch of dubious pharma URLs all over it. This would never have happened if we had a static site. SSL is backed in for free on all JAMstack hosting services I've checked.
3. **Speed of deployment and version control**. If you have worked on website copy, you either skipped version control for content and regretted it, or you have a parallel database of Google or Word docs with your own version of the website. They live on your account and computer and good luck to the next site editor in figuring out where the latest draft lives. In JAMstack, git is the single source of truth. Iteration and versioning are the same for content and development. If you are a developer, deployment is [one command](https://zeit.co/features/deployment-previews), whereas [entire companies](https://bitbucket.org/) have been built on the CI/CD functionality only.
4. **Flexibility**. By definition, JAMstack is the anti-monolithic system. Everything is modular, APIs can be switched in a second if a better solution comes along. This make it the most future-proof stack choice out there today, and increases competition for its ecosystem.

![An image from Notion](https://blog.veronica.fyi/api/asset?assetUrl=https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F0f3d0b51-11f5-4964-bcec-36b08ae46ba5%2FJAMstack.jpg&blockId=9c2ca6de-6d53-46ea-991d-1bfc76ed70af)

JAMstack is very powerful and, if you ask devs, quite great to use. Sadly, it's far from crossing the line of usability. Its flexibility means the options are more overwhelming than a Chinese menu ordered by meat type. Then, to give non-technical users the ability to edit, you need another piece of the puzzle: “headless” CMS. Think Wordpress, without the monolith architecture. Everything you write can flow anywhere in the form of structured data. You can stream it over Twitter, if you so wish. Companies like Stackbit try to help simplify picking the stack and CMS at the same time, but f you want to use JAMstack today, and you have a big app, it's going to take time. Smashing Magazine took [a year](https://www.smashingmagazine.com/2020/01/migration-from-wordpress-to-jamstack/) to migrate from Wordpress.

Simpler use cases are not user-friendly, either. I was able to publish my J[AMstack site](http://veronica.fyi/) on [Zeit](https://zeit.co/) in less than 1 hour, but I needed a GitHub account and basic coding experience. To make it into a [blog](https://blog.veronica.fyi/) - using someone else’s script that reversed engineer Notion’s API to use it as a CMS - took me a day. I cannot recommend it to anybody who's not comfortable with a CLI (command line interface).

Last but not least, JAMstack is powerful, but can't do everything. While you can add scripts to the header, injecting ads into a JAMstack site is equivalent to boarding the earlier flight while your bag is on the original aircraft, arriving 2 hours later. From what I could see, this technology really shines for marketing or subscription websites, which is a pity as page speed is so important for ad-supported business.

## Conclusion

I'm not a fan of feature-based software comparisons. Given the high switching costs between website builders and web stacks in general, it's worth taking a step back and defining the end job that the web app you want needs to do. If you're not a developer, you will have to make a compromise between power and usability. Some questions that help you figure out the best quadrant to land on:

* How often will you need to update the web app?
* How fast you need to go live with changes?
* Who needs to edit the content? How technical are they?
* How hard is to add new functionality and scale as the content grows and business needs change?
* How important is loading page speed to you?