---
title: "R Package Development"
author: Lauren Wolfe
  - Technical
tags: # add 1-4 lowercase tags that are relevant to your post, ex: r, python, genomics, workflows
  - r
  - coding
  - package development
---

A few months ago Kate mentioned to me that she would like for us to start collecting various metrics from Google Analytics and GitHub to track the progress of the Coop Blog. After clicking through the Google Analytics interface a few times I remembered just how much I hate clicking through GUI's to get track down the relevant data. I wondered if I could bypass all the clicking and pull my data down directly into R to build out an automated monthly report. I figured the best way to do this would be to develop an R package that contains functions to pull data from GitHub and GoogleAnalytics! And thus [`coopMetrics`](https://github.com/FredHutch/coopMetrics) was born!

A big misconception about building R packages is that you need to be an expert to do it. Let me be clear: I am not an expert! So I had to start at the very beginning - the first step I took was Googling "how to build an R package". I found [Hilary Parker](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/) and [Karl Broman's](https://kbroman.org/pkg_primer/) blog posts to be quick and relatively painless tutorials to get me started with the package development process. As I began developing and ran into more specific or in depth questions I referenced the classic [R Packages](http://r-pkgs.had.co.nz/) book by Hadley Wickham.

Once I got my R package directory structured and thought on my problem a little more I began to investigate how I would access the data I needed from GitHub and Google Analytics. Having worked on [ImmuneSpaceR]() I was familiar with utilizing application programming interfaces (APIs) to pull data from a website into R. I hoped that both Google Analytics and GitHub might have APIs that I could request my data through. Once again I turned to Google for answers and found documentation for the [GitHub REST API](https://docs.github.com/en/rest) and a [Google Analytics API](https://developers.google.com/analytics/devguides/reporting/core/v4). 

My next move was figuring out how to tie all this information together and access the API endpoints I needed in R. This required poetically simple Google search: "R API". I immediately found a [DataQuest blog post tutorial](https://www.dataquest.io/blog/r-api-tutorial/) on all things R and APIs. As I read through it my heart sank. I realized that not only would I have to make API calls but also parse [JSON files](). So I sulked a little bit and began to begrudgingly familiarize myself with JSON when it hit me: someone must have thought to do this in R before me! A quick google search brought me to the [`gh`](https://github.com/r-lib/gh) and [`googleAnalyticsR`](https://code.markedmondson.me/googleAnalyticsR/) packages.

Having worked on [ImmuneSpaceR](), a package that utilizes the LabKey R API to pull data from the [ImmuneSpace website]()
## Resources

- [Writing an R Package from Scratch - Hilary Parker](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/)
- [R Package Primer: A Minimal Tutorial - Karl Broman](https://kbroman.org/pkg_primer/)
- [R Packages - Hadley Wickham](http://r-pkgs.had.co.nz/)
