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

The Coop Communities Slack is the main way in which the Coop and Scientific Computing communicate with the research community in real time. Each channel in Slack is meant to have a specific purpose. You're automatically subscribed to a few channels like `#generic` and , but the rest are available for folks to add to their workspace as they see fit. Some channels are straightforward. For example, `#question-and-answer` is a place to ask questions and get answers! Other channels are less straightforward, like `#scientific-software`. If you need more information about a channel you can always click the circled 'i' icon in the top right corner of your screen to view the description of each channel.

For this post we are going to deep dive into the `#scientific-software` channel! If this channel isn't on your sidebar it means that you haven't joined it yet! For more information on how to join a Slack channel follow [this link](https://slack.com/help/articles/205239967-Join-a-channel).

## What is Easybuild?

Easybuild is a software build and installation framework that makes managing scientific software on [High Performance Computing Systems (HPCs)](https://www.usgs.gov/core-science-systems/sas/arc/about/what-high-performance-computing#:~:text=High%20Performance%20Computing%20most%20generally,science%2C%20engineering%2C%20or%20business.) efficiently. For more information on EasyBuild check out the [Introductory Topics](https://easybuild.readthedocs.io/en/latest/#introductory-topics) in their documentation. 

Fred Hutchinson's Scientific Computing group uses Easybuild to provide hundreds of open source software packages to scientists. With easybuild, users are able to load multiple versions of any software and all software is built so that it can be rebuilt exactly the same way even a decade from now. This is incredibly useful for making computational research reproducible! All the code is open source and managed through the [`FredHutch/easybuild-life-sciences`](https://github.com/FredHutch/easybuild-life-sciences) respository on GitHub. Check out [this](https://fredhutch.github.io/easybuild-life-sciences/) site for Fred Hutch specific easybuild information including announcements and a full inventory of software available on the clusters.

If you have questions about easybuild or need to request a software update email `scicomp@fredhutch.edu`

## Why follow the `#scientific-software` channel?

This channel is most relevant to people who use the high performance computing clusters for development and analysis. It is linked to the `FredHutch/easybuild-life-sciences` GitHub repository and recieves real time updates on 
GitHub [commits](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/github-glossary#commit), [issues](https://guides.github.com/features/issues/), and [pull requests](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-pull-requests) from that repository. Linking the GitHub repostiory to a Slack channel helps to centralize all of your updates into one place. 

## Making sense of posts sent from GitHub

If you're not familiar with GitHub it can be a little disorienting when you first look at the `#scientific-software` channel. The automated posts from GitHub look a little different than standard messages sent from other Slack users.

Lets break down a post!

FIXME PIC OF SLACK

- Starting from the top left you can see that this is an message sent by GitHub at 11:22 AM. We know that this means it is an automated message sent from a linked GitHub repository. 
- Next we can see that this message was sent because an "issue opened by [`dtenenba`](https://github.com/dtenenba)". You can see by going to that GitHub profile that this is Dan Tenenbaum from Scientific Computing at Fred Hutch!
- Underneath this we can see that Dan opened this issue to report a problem with the new version of `rstudio-server`. You can see the full text of the issue as well as click the links to go to the relevant page in GitHub. 
- If you scan even further down the post you can see that the user [`fizwit`](https://github.com/fizwit) has been assigned to fix this problem. Again, if you go to this users GitHub profile you will see that this is John Dey! John works in Scientific Computing at the Hutch and manages the easybuild software. He's involved in the global easybuild community and an excellent resource if anyone has questions!
- Last, at the very bottom of the post you can see that this message was sent from the `FredHutch/easybuild-life-science` repository on October 19. This is important information because sometimes a Slack channel might be linked to multiple repositories.
