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

## Why follow the `#scientific-software` channel?

This channel is linked to the `FredHutch/easybuild-life-sciences` GitHub repository and recieves real time updates on GitHub [commits](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/github-glossary#commit), [issues](https://guides.github.com/features/issues/), and [pull requests](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-pull-requests).


# Outline
Two main things to explain:

1. How to read and understand this channel
    - Automated github updates
      - Link to or briefly explain what an issue, commit, pull request
      - provide a screenshot of the channel and walk through what each post means
    - Why connect your slack and github?
      - Another place to update users on whats happening 
      - users can file an issue and get notified about it's progress in real time
      - This is important esp for folks doing analysis on Rhino

2. What is [easybuild](https://easybuild.readthedocs.io/en/latest/index.html)?

From easybuild docs:

>EasyBuild is a software build and installation framework that allows you to manage (scientific) software on High Performance Computing (HPC) systems in an efficient way. It is motivated by the need for a tool that combines the following features:

>- a flexible framework for building/installing (scientific) software 
>- fully automates software builds divert from the standard `configure` / `make` / `make install` with custom procedures
>- allows for easily reproducing previous builds
>- keep the software build recipes/specifications simple and human-readable
>- supports co-existence of versions/builds via dedicated installation prefix and module files
>- enables sharing with the HPC community (win-win situation)
>- automagic dependency resolution
>- retain logs for traceability of the build processes

From Fredhutch/easybuild-life-science:
>- FredHutch Scientific Computing uses Easybuild to provide 100s of OSS packages to our Scientists.
>- Scientists can load multiple versions of any software via Environment modules (LMOD).
>- All software is built to offer high reproducibility, it can be rebuilt exactly even 10 years from now.

Managed by John Dey here at the Hutch.

The scientific software channel automatically logs updates to the `FredHutch/easybuild-life-sciences` repository.
