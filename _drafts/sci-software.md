---
title: "The `#scientific-software` channel explained!" # replace with the title of your post, a short catchy description to entice readers
author: Lauren Wolfe 
categories: # delete the categories that do not apply and keep at least one
  - Technical
  - Community
tags: # add 1-4 lowercase tags that are relevant to your post, ex: r, python, genomics, workflows
  - easybuild
  - scientific computing
  - slack
---

The Coop Communities Slack is the main way in which the Coop and Scientific Computing communicate with the research community in real time. Each channel in Slack is meant to have a specific purpose.  You're automatically subscribed to a few channels like `#generic` and `#question-and-answer`, but the rest are available for folks to add to their workspace as they see fit. This way communication streams are kept clear and relavent to the user. Some channels are straightforward. For example, `#question-and-answer` is a place to ask questions and get answers! Other channels are less straightforward, like `#scientific-software`. If you need more information about a channel you can always click the circled 'i' icon in the top right corner of your screen to view the description of each channel.

For this post we are going to deep dive into the `#scientific-software` channel! If this channel isn't on your sidebar it means that you haven't joined it yet! For more information on how to join a Slack channel follow [this link](https://slack.com/help/articles/205239967-Join-a-channel).

## Why follow the `#scientific-software` channel?

This channel is most relevant to people who use the [High Performance Computing (HPC)](https://www.usgs.gov/core-science-systems/sas/arc/about/what-high-performance-computing#:~:text=High%20Performance%20Computing%20most%20generally,science%2C%20engineering%2C%20or%20business.) clusters for development and analysis because it gets real time updates from the [`FredHutch/easybuild-life-sciences`](https://github.com/FredHutch/easybuild-life-sciences) GitHub repository. This repository contains the code Scientific Computing uses to manage all of the open source software on the HPC clusters using [easybuild](https://easybuild.readthedocs.io/en/latest/index.html). The updates let users know what problems with software on the clusters have been logged as issues and exactly when they are solved, including when software is added or or updated! While it's true that researchers could go to the GitHub page to get these updates, the benefit of linking to Slack is that it centralizes your notifications in one place.

>Interested in connecting a GitHub repository to a Slack channel? [This](https://slack.com/help/articles/232289568-GitHub-for-Slack) page from the Slack Help Center will get you started.

## What is Easybuild?

Easybuild is a software build and installation framework that makes managing scientific software on High Performance Computing Systems (HPCs) easier and more efficient. For more information on EasyBuild check out the [Introductory Topics](https://easybuild.readthedocs.io/en/latest/#introductory-topics) in their documentation. 

Fred Hutchinson's Scientific Computing group uses Easybuild to provide hundreds of open source software packages to scientists. With easybuild, users are able to load multiple versions of any software and all software is built so that it can be rebuilt exactly the same way even a decade from now. This is incredibly useful for making computational research reproducible! Check out [this](https://fredhutch.github.io/easybuild-life-sciences/) site for Fred Hutch specific easybuild information including announcements and a full inventory of software available on the clusters.

>If you have questions about easybuild or need to request a software update email `scicomp` to open a ticket.

## Making sense of posts sent from GitHub

If you're not familiar with GitHub it can be a little disorienting when you first look at the `#scientific-software` channel. The automated posts from GitHub look a little different than the standard messages sent from other Slack users.

### Lets break down a post!

![a slack post example]({{ site.baseurl }}/assets/sci-software/slack-img.png)

- Starting from the top left you can see that this is an message sent by GitHub at 11:22 AM. We know that this means it is an automated message sent from a linked GitHub repository. 
- Next we can see that this message was sent because of an "issue opened by [`dtenenba`](https://github.com/dtenenba)". You can see by going to that GitHub profile that this is Dan Tenenbaum from Scientific Computing at Fred Hutch!
- Underneath this we can see that Dan opened this issue to report a problem with the new version of `rstudio-server`. You can see the full text of the issue as well as click the links to go to the relevant page in GitHub. 
- If you scan even further down the post you can see that the user [`fizwit`](https://github.com/fizwit) has been assigned to fix this problem. Again, if you go to this users GitHub profile you will see that this is John Dey! John works in Scientific Computing at the Hutch and manages the easybuild software. He's very involved in the global easybuild community and an excellent resource if you have questions!
- Last, at the very bottom of the post you can see that this message was sent from the `FredHutch/easybuild-life-science` repository on October 19. This is important information because sometimes a Slack channel might be linked to multiple repositories. However, `#sci-software` only recieves updates from `FredHutch/easybuild-life-sciences`
