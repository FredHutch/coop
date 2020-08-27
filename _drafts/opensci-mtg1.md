---
title: "Title goes here"
author: Lauren Wolfe
categories: # delete the categories that do not apply and keep at least one
  - Technical
  - Science
tags: # add 1-4 lowercase tags that are relevant to your post, ex: r, python, genomics, workflows
  - open science
  - reproducibility
  - workflow
  - collaboration
  - communication
---

- First post of the open science series!
- For more information on this series see our previous post [needs link]

**Question**: This week revolves around the question of what does a team workflow using open data science look like and what does the transition to this system look like?

**Goals to keep in mind**:
- Transition into open data science incrementally
- Involve peer-to-peer learning and online communities.

**Read**: [Lowndes, J. S. S. et al. Nature Ecol. Evol. 1, 0160 (2017)](https://www.nature.com/articles/s41559-017-0160)
- Reproducibility is taught to be a central pillar of doing science
  - goes hand in hand with open science - what is the use in sharing code/software/analyses if a user cannot reproduce the results you came to anyways?
  - Think of open science as "transparent, reproducible, collaborative and openly shared and communicated science"
- It's become more and more challenging to achieve
  - The authors of this paper are Environmental scientists and often are required to re-run analyses with new data as it becomes available
    - Found it very difficult to reproduce their OWN analyses
    - Not unique to esci, high profile papers from cancer biology, psychology illustrate this problem (see bibliography)
- Most folks doing analysis in esci (similar to biology) are self taught
  - develop workarounds to keep pace with publishing a paper (have to balance learning "the right way" with time/output)
  - wastes time and effort reinventing the wheel just to create a result that is likely unintelligable to someone else or themselves a year down the line 
- This lab utilized workflows, tools, and philosiphies from sfotware dev to improve their ability to and the speed that they reproduce their results
- (Fig 1) Notice that this is a highly iterative and long term process!
  - This has been ongoing from 2012 - 2017!
  - Each year there is a different focus to work through (Rather than trying to solve it all at once)
  - Started with code/analyses and moved into documentation/version controlling/data management
- Changing the way you have always worked is intimidating
- key lessons
  - "powerful tools exist and are freely available to use"
  - "The barriers to entry seem to be exposure to relevant tools and building confidence using them"
- They thought they were doing reproducible science!
  - Focused on reproducible science methods rather than data science methods
  - Data was being prepared manually in Excel. Documentation on this process was scattered in Excel, emails, word files and difficult to recover/make sense of
  - Communicate in shared files, often vaguely named and manually versioned via the title
- Second assessment in 2013 showed that this approach did not work. Relies on human memory, email chains and personal organization.
    - especially problemnatic when someone moves on from the lab
- Identified three areas to improve in 2013 assessment - reproducibility, communication, collaboration
- Focused on learning R for modeling and visualization, Git for version control, GitHub for collaboration and communication
- Open data science tools took a substantial investment to learn
  - Most in the lab had only learned enough programming to achieve a desired result using their own unique practices/workflows along the way
  - working collaboratively and effectively using these tools would require adopting best practices
- focus for reproducibility:
  - methods are transparent, reproducible, and also repeatable with additional data for tracking changes through time
- focus for collaboration:
  - Our team collaborates in real-time and also treats our future selves as collaborators, knowing that ‘future us’ can only rely on detailed records
- focus for communication:
  - share our code online, but to create reports, e-books, interactive web applications, and entire websites, which we can share for free to communicate our work.
- Closing thoughts
  - many researchers don't even try to reproduce their past work
  - This process, while painful, is enlightening and makes it easier to identify inefficiencies
  - without visible examples of how to use open data tools in scientific research fields folks will continue to recreate the wheel
  - reproducibility across all disciplines in modern science is working effectively and collaboratively with data, including wrangling, formatting and other tasks that can take 50–80% of a data scientist's time
  - Scientific progress requires that we build off of the previous work of others. How can we do this if work isn't reproducable?
  - "benefits of openness can be a by-product of time-saving efficiencies, because tools that reduce data headaches also result in science that is more transparent, reproducible, collaborative and freely accessible to others"


[Include this table??](https://www.nature.com/articles/s41559-017-0160/tables/1)


**Discussion prompt**: 
- How do we approach reproducibility
- Collaboration and communication?
