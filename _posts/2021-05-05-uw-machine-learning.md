---
title: "Machine learning resources for biomedical research" # replace with the title of your post, a short catchy description to entice readers
author: The Coop Team 
categories: # delete the categories that do not apply and keep at least one
 - Technical
tags: # add 1-4 lowercase tags that are relevant to your post, ex: r, python, genomics, workflows
 - training
 - machine learning
---

Last spring,
we reported on a collaborative project between our team and [University of Washington's Master of Science in Data Science (MSDS) program](https://www.washington.edu/datasciencemasters/)
in which a team of MSDS students supported development and implementation of a data pipeline to explore results from the Hutch's [Survivorship Program](https://www.fredhutch.org/en/research/patient-treatment-support/survivorship-program.html).
Based on lessons learned from that experience,
we decided to again sponsor a group of students in their capstone exercise in the fall 2020 and winter 2021 academic quarters.

Machine learning has been one of the most often requested areas for training suppoer throughout the history of [fredhutch.io](http://www.fredhutch.io).
We have periodically taught classes focused on both machine learning concepts and specific computing skills.
However, one of the most frequently cited difficulties is translating basic skills to working with novel datasets.
The MSDS students addressed this need by developing tutorials (via Jupyter notebooks) to demonstrate the application of machine learning methods to biomedical datasets.

The specific project requirements included the following characteristics:
- materials must be publicly available
- multiple levels of expertise (novice, intermediate, and advanced) programmers should be able to reference the materials
- reproducible computational methods should be demonstrated
- code should include explanations of why certain decisions were made during analysis, and why

See below for the results in the two resources developed through this collaboration.
Materials available to practice application of machine learning approaches to biomedical research is also available in this repository on GitHub:
[Practice data analysis - Machine learning](https://github.com/fredhutchio/practice-machine-learning)

## [Gene expression in cancer](https://github.com/fredhutchio/ml-pancancer-example)

This project used gene expression (TCGA RNAseq/transcriptome) 
data from the [National Cancer Institute's Genomic Data Commons](https://gdc.cancer.gov) to explore whether patterns of expression in a subset of genes from across the genome can predict the cancer type.
The included code explores highly multidimensional data,
including the importance of exploratory data visualization and model fitting.

MSDS collaborators:
- Andres De La Fuente - [GitHub](https://github.com/Oponn-1)
- Juan Solorio - [GitHub](https://github.com/JUAN-SOLORIO/), [LinkedIn](https://www.linkedin.com/in/juansolorio/), [Twitter](https://twitter.com/1juansolo0)


## [Image analysis for melanoma diagnosis](https://github.com/fredhutchio/ml-melanoma-example)

These tutorials explore images of skin lesions and uses machine learning to assess the ability to automate melanoma diagnosis.
The example code integrates demographic information with image analysis,
and uses machine learning for translational outcomes.

MSDS collaborators:
- Matthew Rhodes - [GitHub](https://github.com/MatthewCodes), [Twitter](https://twitter.com/MatthewRRCodes)
- Anmol Srivastava - [GitHub](github.com/Anmol-Srivastava), [LinkedIn](https://www.linkedin.com/in/srivastavaanmol)

---

Many thanks to the MSDS student team and their efforts to 
We are grateful for the opportunity to work with students who were able to bring their incredible skills and knowledge to their projects,
and who were sincerely interested in supporting the mission of the Hutch.
**Learn more about training materials for machine learning by clicking [here](https://github.com/fredhutchio/practice-machine-learning).**
