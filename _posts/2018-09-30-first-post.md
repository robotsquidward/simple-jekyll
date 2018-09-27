---
layout: post
title:  "Before You Begin"
categories: jekyll github
subtitle: "Why Jekyll?"
---

The first step into a new technology is always a little intimidating.  Before your journey begins, it might help to understand why you might want to take the plunge into Jekyll site-building.

<!--more-->

## What is Jekyll?

Let's get the basics out of the way first.

Jekyll is...

* ...a [Ruby](https://www.ruby-lang.org/en/) [gem](https://guides.rubygems.org/what-is-a-gem/)
* ...a static site generator
* ...blog-aware
* ...simple

### A Ruby gem

Ruby is a programming language.  Simply put, Ruby is...

> A dynamic, open source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write.

A Ruby gem is simply a Ruby program all packaged up with it's code, documentation, and `gemspec`, and usually is available to anyone at [rubygems.org](https://rubygems.org)

### A static site generator

As the [Jekyll homepage](https://jekyllrb.com) puts it...

> Markdown, Liquid, HTML & CSS go in. Static sites come out ready for deployment.

Jekyll essentially takes the scaffolding of HTML and CSS, adds some simple templating with [Liquid](https://github.com/Shopify/liquid/wiki), and then builds a site from that framework by populating it with your [Markdown](https://daringfireball.net/projects/markdown/) content.

What comes out is a 'static' site.  Static sites are essentially just plain sites that aren't hosting any application type logic.  They essentially just present content, plain and simple.

### Blog-Aware

Most blogs are static sites. They host simple content updated by their authors on a regular basis. Usually new posts have dates, tags, and other meta-data that makes them easy to find. Pages on a blog usually include an About page, maybe an FAQ, or any other standard information the Author wants to host.

Jekyll sites are built for handling this kind of content.  Almost every Jekyll site is built in a way to handle simple content in the form of [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) files that make up each post and page. Once you publish your site, it's just a matter of updating or adding Markdown files - Jekyll handles the rest.

### Simple

All will become clear.

In the end, the minimum you'll have to do is pick a theme, add some Markdown, and push it to a repository.  Jekyll handles the rest.

## Why Jekyll?

If just learning about what Jekyll is didn't convince you, or if you're comparing Jekyll against other static site generators like [Gatsby](https://www.gatsbyjs.org) or website builders like [Squarespace](https://www.squarespace.com) or [WordPress](https://wordpress.com), let's dive into the pro list.

### Built for Markdown

If you love authoring with Markdown, Jekyll has a bit of a leg up over Gatsby or Squarespace/WordPress.

**Compared to Gatsby** Jekyll is geared towards Markdown specifically as it's language of choice for content, whereas Gatsby is built to handle many different data sources.  So while there is rich Markdown support, Jekyll is just a little easier to manage with Markdown.

**Compared to site-builders** Jekyll has the clear edge if you're a Markdown writer.  Most sites like Squarespace allow you to do rich text entry (that in many cases might be easier than Markdown for new users), but if you're a Markdown aficionado then Jekyll is the tool for you.

### Easy to Understand/Learn

**Compared to Gatsby** Jekyll is a bit more 'static' than Gatsby.  One of the benefits of Gatsby is it's use of the powerful and flexible [GraphQL](https://graphql.org) to get data.  However, this is also a downfall for new site-builders who just want to know where to put content.  For ease of getting started, Jekyll is far and away simpler than trying to grapple with Gatsby.

**Compared to site-builders** While Squarespace and WordPress might be a little more focused on the amateur crowd, Jekyll doesn't fall too far behind them.  Because a Jekyll site is usually very small and lightweight, it can be easier to manage over time than a Squarespace page, depending on how comfortable you are with their editors vs. Markdown and basic HTML.

### Affordable

**Compared to Gabsby** Jekyll and Gatsby are both open source, so this one is pretty much a wash. Jekyll's main advantage is its integration with GitHub pages - meaning you can host Jekyll sites for free on GitHub out of the box - saving you from hosting fees.

**Compared to site-builders** Squarespace can get expensive fast, and there isn't a free tier.  WordPress can be free, but optional themes and plugins can be pricy, and are not very easy to understand and scale.  Jekyll is open source and free to host on GitHub, making it a great choice if you're on a budget.

In both cases, the only time you'll have to pay for Jekyll is if you're purchasing a premium theme or want to own your own domain name.

## Why not Jekyll?

I won't tell you that Jekyll is perfect.  There are downfalls to any piece of technology.  Here are a few reasons I see for avoiding Jekyll for your next website.

### You actually need a web *app*.

Jekyll is not a web app framework. If you're looking to build a full blown web application, Jekyll will fall flat.

### You don't want to learn even the website basics.

This is totally valid.  If you're completely non-technical, or have no interest in learning the basics of HTML or Markdown, then Jekyll probably isn't right for you.

Of course I encourage you to learn with Simple Jekyll, and remind you that Jekyll doesn't require much previous knowledge to get started.

### You already know another similar framework.

This is primarily aimed at seasoned web developers.  If you already have a solid foundation in [React](https://reactjs.org) or GraphQL - you probably want to stick with Gatsby.  If you're a WordPress pro you probably won't see a huge benefit from Jekyll sites.

That said, I encourage you to give it a try and see how you like the power and simplicity of Jekyll.
