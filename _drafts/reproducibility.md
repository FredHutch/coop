---
title: "Reproducibility in data-intensive science"
categories: # delete the categories that do not apply
#  - Community
#  - Technical
  - Science
tags:   # add a few lowercase tags that are relevant to your post, ex: r, python, genomics, workflows
  - reproducibility
  - open science
---

The Coop hosted a panel discussion in reproducibility in data analysis for our monthly meeting on Tuesday, December 3 featuring panel participants Keith Curtis (member of Lampe Lab, PHS), Kate Dusenbury (member of Bloom Lab, Computational Biology, PHS), Monica Gerber (statistical researcher, SCHARP, VID), and Erick Matsen (leader of Matsen Lab, Computational Biology, PHS). The following represents a few of the main questions addressed and summarized thoughts from both panelists and audience members.

## What is reproducibility in the context of computational research and/or data analysis?

Reproducibility is a cornerstone of the scientific process, and underlies many considerations for research design in both experimental (wet lab, clinical, etc) and computational work. In a general sense, reproducibility refers to the availability of a set of instructions that can be used to recreate research results. That being said, reproducibility exists along a continuum: some research has incomplete instructions, unclear guidelines, or pieces of the instructions are impossible to follow. The quality and effectiveness of the instructions (e.g., reproducibility) rely on two factors: first, the accessibility of both the data and code (including the underlying environment in which the code was run), as well as the ease with which the analysis can be re-run. Moreover, evaluating reproducibility depends on who is attempting to recreate the results, and when. For example, the same researcher may need to reproduce results at a later time, or a collaborator in a different lab may need to rerun an analysis on a different computing system. These considerations all affect the methods used to uphold and assess reproducibility.

Although reproducibility is widely considered an asset to effective science, our discussion acknowledged that it does require deliberate and diligent effort. Time and effort need to be committed during and after a project to ensure computational results will continue to be reproducible. Moreover, little attention is paid to the reasons *why* reproducibility is important for any given research project: will the lab need to reuse these methods on other datasets? Will the methods need to be altered before the end of the project? Computational reproducibility is similar to lab experiments in a conceptual sense, but often requires different tools, planning, and even thought processes to ensure.


## What's the best place to get started improving reproducibility in data analysis?

[Coding habits for data scientists](https://www.thoughtworks.com/insights/blog/coding-habits-data-scientists) by David Tan
functions
code review
will this be recognizable to everyone else? conventions and standards

history from command line, convert to script
easing entry points for sharing resources among lab members
workflow tools
test driven development, type driven development
document along the way!
workflow managers

institutional support (tools, training) for reproducibility
reward structure for reproducibility: pace of work, cost of learning vs productivity, reducing complexity of development over time, citations, institutional leaderboard?
