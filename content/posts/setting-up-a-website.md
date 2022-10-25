---
title: "Setting Up a Website"
date: 2022-10-25T14:44:22-04:00
draft: false
---
# Setting Up a Website
Taking an idea in your head and forming that into a website that can be viewed anywhere and everywhere is one of the most satisfying steps to carving out your corner of the internet. And of course, having a platform that you can point back to as your own, unfiltered, curated forum is unparalleled by any other online medium.

Going about getting a website up has never been easier. There are plenty of resources online that teach the basics, HTML and CSS. Within a weekend you could have a functional site up and running even with no prior knowledge. Will it be a blazingly fast, beautiful, dynamic, responsive masterpiece that will end up on “I Reviewed Your Mind Blowing Websites! | Part 34”? No. Not even close, and, lest we delve the depths of… modern javascript, that’s where site generators come in.

Site generators like Ghost, offer industry level control over your site, newsletters, subscriber data, paid content, all in one place. However, from what I can tell, while being creator focused, it does not look like you can get the granular control directly over the website and its code. You interact with your site through Ghost. As a developer, if I have the option to take this low level control I will. (A topic I’ll explore in another blog post.)

This leaves even higher level, further abstracted, site generators such as Wix, Wordpress, Squarespace to use to build your sites. All with varying levels of control, ease of use, and data collection. These are excellent options for people who want/need the simple to pick up and easy to use platform 

>Decide the purpose of your website. Now, how involved with its source code do you need to be to achieve that?

Don’t waste time and energy on learning React or Vue for the sole purpose of building a blog. Find your goal, and find the steps towards that goal, no more.

Wix, Wordpress, Squarespace are great for some, but these options are all too far away from the actual source code of the website for me to use. So what am I left with?

Hugo. It is an accessible, low-ish level, static site generator. What does this mean?

This means it’s a fast and flexible way to make “simple” websites. I use the word “simple” because Hugo’s simplicity is only in its static-ness. A static site is basically a bunch of blogposts, recipes, articles, linked to each other – every user sees the same thing. Contrast with a dynamic website that generates content as you go. A static site is a site such as www.collinsself.com while a dynamic website would be something like www.youtube.com. 

A static website was perfect for my use case because it lends itself towards the blog structure. Hugo is the generator I went with because it offers different levels of intimacy with the source code of the website…

Highest Level Hugo.

Download Hugo, generate a site with its CLI, link a theme, publish content in a markdown format. Done.

It’s no “click and drag a text box onto the screen,” like Squarespace, but if you aren’t too particular about the exact layout of the site, Hugo will handle it all for you.

This option follows the quickstart page on Hugo’s site.

Mid Level Hugo.

At this stage you operate more at the theme level. And I think this is where Hugo really shines. Having a background with even just vanilla CSS will benefit you here as you will be able to edit the theme you add to your site and effectively modify the front matter of your pages to add more specific flavor to each.

Hugo’s file structure is extremely basic:

Archetypes are templates for the front matter of pages

Config.toml is the overall config for the behavior of the site and theming

Content is… where you put the content - also contains your _index.md

Layouts are the aesthetic layouts of different pages, list pages, main pages

Static is where all the assets you use such as your .css or .js modifications

Those are the main ones; a cursory understanding of these directories will give you an idea of the flexibility of Hugo as a site generator.

If you want to make a site at this level or lower, Jake Wiesler of www.jakewiesler.com (a site that is built with Hugo) has some great write-ups on different, slightly advanced Hugo topics.

Low Level Hugo

Building your own theme. Theming in Hugo is its main draw and fundamental to your website. Using a theme made by someone else is easy and flexible (depending on the theme and your expertise) – it’s how I built my site, but if you want exact styling and control over the minutiae of your site, making your own theme is the way to go. See Luke Smith –

I originally wanted to include how I hosted my site with Firebase, but in the interest of an already too long post I will save this for another day. Happy developing!
