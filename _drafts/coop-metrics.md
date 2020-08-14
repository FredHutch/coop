---
title: "R Package Development"
author: Lauren Wolfe
  - Technical
tags: # add 1-4 lowercase tags that are relevant to your post, ex: r, python, genomics, workflows
  - r
  - coding
  - package development
---

A few months ago Kate mentioned to me that she would like for us to start collecting various metrics from Google Analytics and GitHub to track the progress of the Coop Blog. After clicking through the Google Analytics interface a few times I realized that this monthly task would quickly become the bane of my existance. I could never remember exactly what metrics I was supposed to be looking for let alone where to find them. I wondered if I could bypass all the clicking and thinking and pull exactly the data I need directly into R where I could build out a report in R markdown. With a little investigation I discovered that both Google Analytics and Github have [application programming interfaces (APIs)](https://en.wikipedia.org/wiki/Application_programming_interface) available so developers like me can access their data programmatically.

So I brought my idea to Kate and we decided that this was a problem worth solving programmatically and that it made sense to package up the required functions as an R package. And so, [`coopMetrics`](https://github.com/FredHutch/coopMetrics) was born! Of course an added benefit being that I could blog about the development process as things progressed!

While I have some experience contributing to R packages from my time working on [ImmuneSpaceR](https://github.com/RGLab/ImmuneSpaceR), I do not have any experience developing an R package from scratch. So I decided to start at the very beginning - the first step I took was Googling "How to build an R package". There are a ton of great resources out there but I found [Hilary Parker](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/) and [Karl Broman's](https://kbroman.org/pkg_primer/) blog posts to be quick and relatively painless tutorials to get me started with the package development process. As I began developing and ran into more specific or in depth questions I referenced the classic [R Packages](http://r-pkgs.had.co.nz/) book by Hadley Wickham.

My next move was figuring out how to tie all this information together and access the API endpoints I needed in R. This required poetically simple Google search: "R API". I immediately found a [DataQuest blog post tutorial](https://www.dataquest.io/blog/r-api-tutorial/) on all things R and APIs. I 


## Resources

- [Writing an R Package from Scratch - Hilary Parker](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/)
- [R Package Primer: A Minimal Tutorial - Karl Broman](https://kbroman.org/pkg_primer/)
- [R Packages - Hadley Wickham](http://r-pkgs.had.co.nz/)

[Google Analytics API](https://developers.google.com/analytics/devguides/reporting/core/v4)
[GitHub REST API](https://docs.github.com/en/rest) 
