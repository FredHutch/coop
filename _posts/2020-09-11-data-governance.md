---
title: "What is data governance, and how can it help you?"
author: Kate Hertweck
categories:
  - Community
tags:
  - data management
  - data security
---

Earlier this summer, I was invited to join a project led by Center IT assessing the current status of data governance at Fred Hutch. 
As a part of my work as computational training and community lead,
I spend a lot of time learning how researchers think about and work with data.
While many people may not be familiar with the concept of data governance,
I've learned that most members of the Coop community have quite a lot of interest in its key elements. 
In this post, I'll discuss what data means in the context of computational research,
identify how governance guides work with data,
and highlight a few ways in which this work can potentially help you in the future.

## Data

If you asked five different researchers on campus to describe their data,
you'd likely receive five very different types of responses.
That's partly because the type of research varies:
the data associated with genomic analysis, microscopy, and clinical studies are all structured, stored, and analyzed differently.
It's also because scientists may *think* about data in dramatically different ways,
and place value on data at different stages of analysis.

For example,
the steps required for a research project investigating effectiveness of a particular disease treatment from electronic medical records involves:
- accessing original records
- extracting specific test results for all patients along with relevant demographic and disease information
- reformatting and standardizing test results
- modeling test results according to demographic and disease information

Each of these steps in the process involve data,
but the nature of the data vary throughout the project.
Various researchers will have different ideas about which type represents the "original" data,
and what are the most important. 

## Governance

The general idea of governance includes the people and processes involved in guiding and directing.
Just as government at the local, state, and federal level guides our legal, medical, and social systems, 
institutions can idenitfy governance for particular projects as well. 

In the context of research,
governance occurs both explicitly and implicitly.
Explicitly,
the principal investigator of a lab is responsible for obtaining funding and overseeing research.
Individual lab members have separate expectations surrounding thier job duties and the roles they play in collaborative experiments.
Implicit guidelines include both social norms, 
like cleaning up after yourself in shared lab space,
as well as methodological procedures,
like experimental protocols for particular experiments
(or computer scripts for computational work!).

Developing governance procedures allows all of these expectations to be stated clearly for everyone to understand.

## What does this mean for researchers?

With this understanding of data and governance as independent ideas,
We can start to envision how *data governance* works in a research setting. 

Many available resources for data governance relate to governmental or corporate environments, 
where there are clearly defined expectations around structure and ownership of data. 
Data governance from an academic or research perspective can be more difficult to envision,
since an individual research project can include many types of data, as well as a wide array of collaborators
(not to mention other stakeholders like funding agencies, publishers, and the broader scientific community).
University of New South Wales has an [excellent set of resources](https://www.datagovernance.unsw.edu.au/research-data-governance) 
that provides one perspective on research data governance.

In general, data governance policies help you answer the following questions about research data:
- *Who owns these data, and who else can access the data?* 
While this seems like a straightforward issue,
the example about electronic medical records above highlights how complicated data stewardship can become. 
Original records have important privacy concerns,
with strict limits on who can access them.
While data from later steps in the project do not require such stringent limitations,
the nature of research requires that metadata (information about the data) 
be developed and curated to ensure appropriate quality thresholds.
Clearly, this question has implications for other conceptual questions about data, 
as well as more practical questions about authorship on publications.
- *How are data managed and stored?* 
Continuing from the previous question, 
it becomes clear that data governance is immensely important for ensuring the provenance (history) associated with data, 
and what changes have occurred to the data over time. 
This question also addresses how data are stored while the project is in progress, 
as well as where data will be published and/or archived for future researchers to inspect or reuse.
- *How do we ensure data integrity and quality?* 
As data is shared among collaborators, 
and is transformed, filtered, or otherwise altered during the course of an analysis, 
we rely on each other to ensure the analysis remains consistent with both the method of data collection and the questions such a project is attempting to address.
As we move towards more complex datasets, 
especially those aggregated with publicly available data,
data governance promotes appropriate decision-making to maintain high-quality, well-documented data.

Sometimes guidelines associated with data governance are seen as restrictive and burdensome,
and appear to detract from scientific progress.
In reality, 
a cohesive institutional approach to data governance promotes and facilitates research,
by ensuring data are kept secure, maintain high quality, and are available for researchers in the future.

Here at the Coop, 
we care about data governance because transparent and equitable policies support our [core values](https://fredhutch.github.io/coop/community/coop-values/),
such as open science and building connections.
If you're a Fred Hutch employee and would like to learn more about this work, 
head over to Centernet and search for "data governance."
The data governance work at Fred Hutch is currently focused on assessing how all groups,
from research labs to administrative departments,
manage their data, 
and is specifically focused on data that is valuable 
(like unique research data that would be difficult to collect again), represent a potential security risk (such as personal health data), 
or are necessary to maintain across time (summary data for long-term research projects).
Stay tuned in coming months about data governance at Fred Hutch,
because after all,
**Data governance is everyone's job.**
