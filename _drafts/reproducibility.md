---
title: "December 2019 Coop Panel Summary: Reproducibility in data-intensive science"
author: Kate Hertweck
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

Given the complexities of implementing reproducible computational methods, our discussion focused heavily on ways to begin improving reproducibility in data analysis. Most cutting-edge tools to support reproducibility require writing code, or at least being knowledgeable about running software from the command line. We discussed methods to ease the point of entry for researchers new to these methods. For example, following basic training in such methods, learning how to document what you try with code is a step towards developing reusable scripts (moreover, documenting along the way can be a challenge even difficult for experienced programmers!). One particularly useful resource mentioned was [Coding habits for data scientists](https://www.thoughtworks.com/insights/blog/coding-habits-data-scientists) by David Tan, which highlights some general mindsets and basic practices that can help researchers improve the robustness and effectiveness of their code, such as writing functions and using test-driven development. Panelists repeatedly mentioned version control with Git and the public web repository GitHub as useful tools, and increasingly common tools like Docker containers and workflow managers (like Nextflow) as particularly exciting developments.

Such practices may be useful for individuals, but research groups and labs can also encourage reproducibility by using methods that support team members sharing resources. Identifying conventions and standards for code that may be shared and reused by others can help uphold a basic tenet of reproducibility mentioned by the panel: will this approach be interpretable and recognizable to other people? One way to help encourage a supportive culture for reproducible methods is code review, in which team members test, review, and comment on each other's work. On an even broader scale, institutional support for specific tools and concomitant training to onboard researchers is essential for adoption of reproducible methods. We also discussed the rewards structure for reproducibility. From a research perspective, reproducibility can ultimately increase the pace of work (e.g., rate and number of papers published) by reducing the complexity of data analysis in subsequent projects, and can increase the number of citations for a published work, as other researchers are able to apply the methods more easily.

This barely scratches the surface of the breadth and depth of issues related to reproducibility. Please feel free to reach out to coophelp at fredhutch.org with any ideas for follow-up discussions, and thanks again to our panel speakers and to the audience for their comments and questions!
