---
title: "R Package Development"
author: Lauren Wolfe
  - Technical
tags: # add 1-4 lowercase tags that are relevant to your post, ex: r, python, genomics, workflows
  - r
  - coding
  - package development
---

A few months ago, Kate mentioned to me that she would like for us to start collecting various metrics from Google Analytics and GitHub to track the progress of the Coop Blog. After clicking through the Google Analytics interface a few times I realized that this monthly task would quickly become the bane of my existence. I could never remember exactly what metrics I was supposed to be looking for, let alone where to find them. I wondered if I could bypass all the manual clicking and pull exactly the data I need directly into R where I could build out a report in R markdown. With a little investigation I discovered that both Google Analytics and GitHub have [application programming interfaces (APIs)](https://en.wikipedia.org/wiki/Application_programming_interface) available so developers like me can access their data programmatically.

I brought my idea to Kate and we decided that this was a problem worth solving programmatically and that it made sense to package up the required functions as an R package. And so, [`coopMetrics`](https://github.com/FredHutch/coopMetrics) was born! Of course, an added benefit being that I could blog about the development process as things progressed! I hope that this post will provide insight into my thought process as I began developing this package! I purposely included information about the resources I used (including Google searches) to illustrate how often I had to refer to the internet during this process.

## Setting up a package directory

While I have some experience contributing to R packages from my time working on [ImmuneSpaceR](https://github.com/RGLab/ImmuneSpaceR), I do not have any experience developing an R package from scratch, so I decided to start at the very beginning. The first step I took was Googling "How to build an R package". There are a ton of great resources out there but I found [Hilary Parker](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/) and [Karl Broman's](https://kbroman.org/pkg_primer/) blog posts to be quick and relatively painless tutorials to get me started with the package development process. As someone with dyslexia it's exhausting for me to read big chunks of text and I find quick primers are the most accessible way for me to get started! As I began developing and ran into more specific or in depth questions I referenced the classic [R Packages](http://r-pkgs.had.co.nz/) book by Hadley Wickham. 

Once I got a handle on basic package development, I built out a skeleton package directory. A minimal R package directory has `README.md`, `NAMESPACE`, and `DESCRIPTION` files and a `R/` directory. See [Chapter 5](https://r-pkgs.org/workflows101.html#creating) of the R Packages book for more information on what these files are for and more information on package directory structure.

## Accessing the data

My next move was figuring out how to tie all this information together and access the API endpoints I needed in R. This required a poetically simple Google search: "R API". I immediately found a [DataQuest tutorial](https://www.dataquest.io/blog/r-api-tutorial/) on all things R and APIs. This article really cleared up for me the steps I would have to take if I wanted to build functions from scratch. 

Now, some people might enjoy coding so much that they want to build their own R API package for Google Analytics and GitHub, but that is not me. Before diving into development, I did some more Google investigating and found that luckily someone else had already built R packages for accessing the GitHub and Google Analytics APIs! I decided to use the [`gh`](https://github.com/r-lib/gh) and [`GoogleAnalyticsR`](https://github.com/MarkEdmondson1234/googleAnalyticsR/) packages for my API calls.

## Developing functions

This package is in active development, so this part of the process is far from finished. You can view my entire code history [here](https://github.com/FredHutch/coopMetrics/commits/main/R) if you're interested! 

The hardest part of function development for me is getting started. Often times my brain gets caught up skipping back and forth between all the things I want to do! To help myself focus on small actionable steps I like to break down the task into smaller chunks first. I sketched out which metrics I wanted to pull from each API and roughly outlined how I imagined my function working (inputs, data pull, intermediate steps, outputs).

As someone who is a little out of practice when it comes to coding, this was a great reminder that coding is a messy and iterative process (or at least it is for me). Sometimes you have to burn it down and try again and that is ok! For example, I originally built a function that pulls a single month at a time. Then, when I started building out the monthly report for the blog, I realized that I would obviously want to pull multiple months at a time! I was a little annoyed with myself for having to overhaul chunks of code, but ultimately it only took a couple hours for me to figure out how to adapt things. This is to say, don’t let the fear of having to rework a chunk of code eventually keep you from getting started!

## Next steps

There is still quite a bit that I want to do with this package! My next steps are the following:
- Building out the monthly Coop blog report, including visualizations
- Transitioning my code to use the [Tidyverse](https://www.tidyverse.org/) suite of R packages
- Adding testing
- Making documentation on usage clearer
- Considering what it would take to adapt functions to work with other types of GitHub hosted blogs (like Hugo)
- Develop informative error messages/error handling

If you have a GitHub pages blog that you'd like to collect metrics on feel free to give this package a try! No promises it'll work perfectly or even at all, but your feedback would be greatly appreciated!

## Closing thoughts

This project has been a great practice in learning openly and vulnerably. When I first began writing code with a small team a few years ago the idea of sharing the code I wrote was terrifying and I absolutely hated it!  Even now, when Kate first told me that she wanted me to write this post I was not very excited about it. I'm someone who hates making mistakes and I feel pretty uncomfortable letting "the world" see an unfinished and imperfect project. I think this is pretty common, especially in academia. But here we are at the end of the post and I’m glad I wrote it!

## Other Resources

- [Devtools cheatsheet](https://rstudio.com/wp-content/uploads/2015/06/devtools-cheatsheet.pdf)
- [Developing packages with RStudio](https://support.rstudio.com/hc/en-us/articles/200486488-Developing-Packages-with-RStudio)
- [GitHub REST API Documentation](https://docs.github.com/en/rest)
- [Google Analytics API Documentation]()
