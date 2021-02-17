---
title: "Graze.com CSS framework"
description: "Front end framework and design system for graze.com"
date: 2017-01-05
tags: ['UI Design', 'Development']
layout: layouts/post.njk
feature_image: portfolio-cover-pistachio.png
banner_image: portfolio-pistachio-lifestyle.jpg
theme_color: "#41969C"
---
## My role

Main responsibilities included research, UI design, architecture and guidance copy to explain how and why we use certain design patterns.

## The challenge

In 2013 <a href="//graze.com">graze.com</a> moved to a responsive website that used Bootstrap with custom overrides. Since then additional styles had been regularly added without any formal process, sometimes for individual use. Within two years the framework had become bloated and style patterns across the website were inconsistent which resulted in a poor user experience.

## The goal

Create a style guide to establish a common language, enforce a more sequential workflow from design through to development and create a more consistent experience for the user.

## The process

### Research

I did some research to find leading examples of style guides. The three that we were most inspired by were <a href="//rizzo.lonelyplanet.com/styleguide/design-elements/colours">Lonely Planet</a>, <a href="//ux.mailchimp.com/patterns">MailChimp</a> and <a href="//www.gov.uk/service-manual/design">Gov UK</a>. We also read a lot about Brad Frost's <a href="//bradfrost.com/blog/post/atomic-web-design/">Atomic Design</a> methodology, which certainly influenced our approach.

### The audit

I performed an audit of the website, which included taking screenshots of each page and specific elements, printing them out and putting them up for the front end team to look at. We also performed some online tests which included a colour palette test.

<figure>
{% imageTest "./img/pistachio-styles-audit.jpg", "Small sample of the styles printed out and grouped", "1200" %}
<figcaption>Small sample of the styles printed out and grouped</figcaption>
</figure>

From the audit we discovered that:

* The site had inconsistencies, even on individual pages.
* We had over 200 colours including 30 shades of grey alone (some imperceptible for most users).
* We were using seven different button styles.
* Single pages had as many as 10 different fonts styles.
* 30 shades of grey

<figure>
{% imageTest "./img/30-shades-of-grey.png", "30 Shades of Grey", "1200" %}
<figcaption>30 Shades of Grey</figcaption>
</figure>

Together with the front end developers we went through the various screenshots voting whether to keep, drop or redesign. We put together a list of simple items that we knew we needed which included alerts, buttons, form elements, typography and colour palette.

Although brand colours themselves were created by the creative team, it was our responsibility to ensure that they were used in the correct way for usability purposes on the website. For example, the old framework had many shades of grey that wouldn't be seen by many users, either because of visual impairment or because of the monitor they're using.

We were supporting 6 different fonts (4 custom fonts) and various different styles assigned to classes. Because of how we had arranged styles and class names, it meant that dozens of combinations could be created. For example, <p class="lead h3"> was being used. The 'lead' class to make the font size larger and weight lighter and the 'h3' class to add a margin. This was something we needed to avoid in future.

Over the course of four months more items were added, as long as the team believed they belonged within the framework. If it was an item that was going to be used in more than one place it was added as long as there wasn't something that already existed that could be used instead.

### The structure

* Basics
  * Buttons
  * Colour palette
  * Forms
  * Images
  * Lists
  * Tables
  * Typography
* Components
  * Accordion
  * Alerts
  * Breadcrumbs
  * Health badges
  * Icons
  * Navigation
  * Page sections
  * Pagination
  * Panels
  * Progress
  * Ribbons
  * Sashes
  * Stickers
  * Tooltips
* Examples
  * Article page
  * Drop down menu
  * Feature page
  * Off screen menu
  * Product tiles full width
  * Product tiles with nav

## The outcome

The end product was Pistachio - a living style guide and custom-built CSS front end framework.

<figure>
{% imageTest "./img/portfolio-graze-living-styleguide-responsive.jpg", "Screenshots showing Pistachio on desktop and mobile", "1200" %}
</figure>

<a href="https://pistachio.graze.com">Visit website</a>
