---
layout: blog
title: Approving by default
date: 2025-07-20T08:20:00.000+02:00
slug: approving-default
tags: programming
draft: false
---
A couple of weeks ago, I came across a podcast episode by Ryan Peterman (which I didn't know until then, but highly recommend if you're interested in programming, organizations and career development) with Jake Bolam, who is an IC8 (Principal Engineer) at Meta. I enjoyed the entire episode a lot and would recommend it, but one idea in particular stood out to me.

Jake mentioned that he always approves all Pull Requests he sees. He reviews them, he notes his remarks, but he approves them. That goes as far as approving something that might break production if merged unaddressed. 

My initial thought was that this was crazy. We use GitHub at work and it gives you three buttons, probably for a reason. Why only use one of them, especially if you notice big flaws? But as I often do with ideas that initially sound crazy to my, I gave it a shot, just to see if there is something to it. 

I've been approving every single Pull Request I reviewed for the past couple of weeks now. This post is about why I will continue doing it.

I think initially, this caused some confusion in my peers. Usually, we would approve only if there are nitpicks that we did not feel strongly about. As soon as there was something "bigger", we usually comment (which will not allow the author to merge the PR) or request changes (which does the same, but adds a lot of red text that screams at you). There is another argument to be had about the differences of using "Comment" and "Request Changes", but this is not the place for it.

When I started doing this, I did not tell anybody, I just started. There were now instances where I commented that something would not work in production or was clearly different from how we usually do things, but approved it anyways. Coming from our current workflow, this reads somewhat unintuitive. However, I did not get any questions about it as well, so it does not seem to be such an outlandish idea after all.
