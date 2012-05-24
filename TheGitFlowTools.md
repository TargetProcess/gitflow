---
layout: default
title: "HubFlow: The GitFlow Tools Adapted For GitHub"
---
# HubFlow: The GitFlow Tools Adapted For GitHub

## Introduction

If you look at [Vincent's original blog post](http://nvie.com/posts/a-successful-git-branching-model/), he's listed all of the individual Git commands that you need to use to create all of the different branches in the GitFlow model.  They're all standard Git commands ... and if you're also still getting your head around Git (and still learning why it is different to centralised source control systems like Subversion, or replicated source control systems like Mercurial), it adds to what is already quite a steep learning curve.

Vincent created an extension for Git, called [GitFlow](https://github.com/nvie/gitflow), which turns most of the steps you need to do into one-line commands.  At [DataSift](http://datasift.com), we used it for six months, and we liked it - but we wanted it to do even more.  We also wanted it to work better with GitHub, so to reduce confusion with the original GitFlow tools, we've decided to maintain our own fork of the GitFlow tools called __HubFlow__.

## What Is HubFlow?

[HubFlow](https://github.com/datasift/hubflow) is:

* an extension to the Git command-line tools
* a fork of the original [GitFlow tools](https://github.com/nvie/gitflow)
* one-line commands for using the [GitFlow branching model](IntroducingGitFlow.html) with GitHub
* focused on making it as easy as possible to use GitFlow with GitHub

The main differences between the original GitFlow tools and HubFlow are:

* by default, commands push to / pull from GitHub wherever it is appropriate
* we've added additional commands