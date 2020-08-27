---
title: "Title goes here" # replace with the title of your post, a short catchy description to entice readers
author: Lauren Wolfe 
categories: # delete the categories that do not apply and keep at least one
  - Technical
  - Science
tags: # add 1-4 lowercase tags that are relevant to your post, ex: r, python, genomics, workflows
  - open science
---

- Second post of the open science series!
- Past posts in this series [as links]:
  - Intro post 
  - Post 1

---

**Question**: How do we store and share our data, methods and code?

**Goals to keep in mind**: Have clear systems for data management, storage and backup, as well as for documentation of methods and code.


**Read**: [Wilson, G. et al. PLoS Comput. Biol. 13, e1005510 (2017).](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510)
    
notes:
- The focus of this paper is on accessible skills for sound scientific computing - hence "good enough"
- Summary of pratices:
  - Data management
  - Software
  - Collaboration
  - Project Organization
  - Keeping track of changes
  - Manuscripts

- Data management:
  - Data during a project exists in varous forms from raw -> cleaned/ready for analysis -> analysis results and visualization
  - Two main themes 1) tidy data to accelerate analysis 2) incrementally working towards ready to analyze data documenting the process and outputs along the way.
  - This section covers:
    - Which data to retain
    - backing up data
    - file formats
    - variable naming
    - tidy principles
    - documentation
    - handling multiple tables
  - saving intermediate files makes it easy to rerun parts of your analysis

- Software:
  - Even if you're only writing a few dozen lines of code and you are your only user adopting software engineering principles will make it easier for you to reuse and share your code
  - This section covers:
    - Commenting
    - using functions
    - reducing duplication
    - function and variable naming
    - dependencies
    - test data

- Collaboration:
  - Goal is to make it easy for collaborators (including your future self!) to set up a local workspace and contribute to your project.
  - Want to make it easy to get credited for your work
  - This section covers:
    - READMEs and CONTRIBUTING files
    - creating "to-do" lists
    - citation
- Project organization:
  - How you organize project directories is critical to how easy your project is to pick up and understand
  - This section covers:
    - where to put raw and meta data
    - project directory structure
    - where to put source code
    - file naming
    
- Keeping track of changes:
  - tracking changes is critical to documenting and understanding the software development process
  - version control systems like Git and Subversion
  - this section covers:
    - manual version control vs automated version control
    - cadence for sharing changes
    - different versioning systems
    - what not to version
    - inadvertant sharing

- Manuscript
  - Many researchers use an email based workflow. Comments on manuscripts are returned by email, comments in a document, and direct changes to a document.
  - There are a few different methods for collaborating on a manuscript but the general goals are:
    - Make text accesible by creating a master document that is accessible at all times
    - Reduce the risk of losing or overwriting work
    - Make it easy to track and merge contributions
    - Make it easy to share the final version with collaborators and submit
  - More important than any workflow is having an agreed upon workflow before writing starts
  - This section covers:
    - online tools for collaborating
    - text based docs under version control,
    - discussion on plain text vs a more accessible text editor




**Discussion prompt**: 
- What are our data-management systems?

**Hutch specific prompts**:

## About/link to next post


## We want to hear from you!

Maybe this post prompted your group to begin a dialogue on how to improve reproducibility or maybe your group is seasoned at thinking about these things. Regardless, we would love to hear from you about your groups open-science barriers, transition process, and/or solutions and share your story with the Coop community. It doesn't have to be as comprehensive as this paper which, and I cannot stress this enough, covers incremental changes a lab made over the course of **years**. Whether you came up with a solution for communicating and sharing data with your collaborators, improved documentation in your lab, or were just prompted to started the conversation let us know by Slack, MS Teams, the `FredHutch/coop` GitHub, or by emailing us at `coophelp`.
