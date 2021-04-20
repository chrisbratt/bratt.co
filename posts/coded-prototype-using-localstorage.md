---
title: "Coded prototype using localStorage"
description: "Using localStorage to enhance coded prototypes"
date: 2021-02-02
tags: ['Usability testing', 'Prototyping', 'Coding']
layout: layouts/post.njk
feature_image: coded-prototype-feature.jpg
banner_image: coded-prototype-banner.jpg
theme_color: ""
eleventyExcludeFromCollections: true
project_url: ""
---
## Why coded prototypes?

Often when usability testing our designs, we introduce our product to the user and explain that because it's a prototype some links may not work and that some of the details may not be accurate. Then when there's a form, often we've simply created 2 static pages, one with empty fields and one with pre-filled content - "You don't need to fill in the form, just tap anywhere and it'll update".

Often you have to guide a user down a set, linear path - and more often than not, that's a happy path. Whilst I fully agree that coded prototypes should not be the first prototype used for usability testing, I do feel they can be incredibly valuable.

I find coding a prototype can often be quicker to iterate on - but part of that is because I have a Web Development background. It also helps when you have a Design System, but coded prototypes don't need to inherit your company's look and feel, they can still very much be low fidelity.

But what happens in a scenario where it's vital that you can test multiple options and display accurate details? What happens if a good amount of your experience uses form inputs?

I briefly looked into prototyping tools that do cater for interactive input fields, but where it falls over is the ability to carry this information through the rest of the journey.

This is when I looked into localStorage.

## Why localStorage?

Essentially what localStorage allows us to do is set and get data that is stored on the users device locally, a bit like a Cookie. We can set default values and also update them through various different ways, such as onClick or onSubmit.
