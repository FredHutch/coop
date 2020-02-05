---
title: "Get flowing with Nextflow" # replace with the title of your post, a short catchy description to entice readers
author: The Coop Team # the author value should match the 'title' value of your contributor file located here /gh-pages/_contributors. If you do not have a contributor file, please feel free to make one or contact one of our team members to assist you.
categories: # delete the categories that do not apply and keep at least one
  - Community
  - Technical
tags: # add 1-4 lowercase tags that are relevant to your post, ex: r, python, genomics, workflows
  - nextflow
  - workflow manager
---
#### What is Nextflow?

Workflow managers are software that facilitate the setup, execution, and monitoring of multi-step scientific analyses. These are especially important for complex bioinformatic analyses that require various software dependencies and resource requirements, and can make your analysis both easier to troubleshoot and more reproducible. There are  a handful of workflow managers out there with [Nextflow](https://www.nextflow.io/) becoming a popular choice. Other workflow managers that people may recognize are Snakemake, Cromwell, Toil, and CWL. The benefits of a workflow manager like Nextflow is that it makes it easier to run your analysis while transparently managing all of the issues that tend to crop up when running a shell script like missing dependencies, not enough resources, cryptic failures and errors, or difficulty sharing the constructed workflow with collaborators.

[Nextflow](https://www.nextflow.io/) is free, open source software distributed under the Apache 2.0 license and is developed by the Comparative Bioinformatics group at the [Barcelona Centre for Genomic Regulation (CRG)](https://www.crg.eu/). They have extensive documentation on how to write workflows and [run Nextflow on their documentation pages](https://www.nextflow.io/docs/latest/index.html). There is also [NF-Core](https://nf-co.re/), a community effort and curated collection of analysis pipelines built using Nextflow. Think of it as a repository of Nextflow workflows. Additionally and more importantly, staff and research scientists here at Fred Hutch have created this page to [help get you up and running with Nextflow](https://sciwiki.fredhutch.org/compdemos/nextflow/) using the minimum requirements and AWS for the execution. The Fred Hutch research community is also building out and maintaining a [set of Nextflow workflows here as well](https://github.com/FredHutch/reproducible-workflows/tree/master/nextflow).

#### How is it used at Fred Hutch?

A workflow in Nextflow is a text file written in a particular format containing all of the details of the analysis that are generally true for all of the times that you need to run that analysis. Any of the details specific to a single experiment or batch of samples can be specified as parameters, which are specified for each individual batch of data whenever you invoke the workflow. The nice thing about Nextflow is that it can be used to run analyses on AWS, without having to know much about how AWS works. In other words, Nextflow will take care of running jobs on AWS, pulling data down from S3 into the job, running the analysis inside the appropriate Docker image, and pulling the results out of the job and returning them to the right place. Some of the general use cases here at the Hutch have been:

- scientists using it to wrestle with computational pipelines to get their work done
- automatic parallelization across tasks
- docker containerization
- scaling up work with cloud computing resources
- utilizing detailed workflow summary reports

Some examples of the specific workflows designed and used here help [align proteins with DIAMOND](https://github.com/FredHutch/reproducible-workflows/tree/master/nextflow/align-proteins-diamond), provide taxonomy counts using mothur, cluster proteins quicker, or provide taxonomic classification. Nextflow workflows are also being used at the Hutch for concurrently processing large batches of samples for bacterial genomic annotation. Researchers here have implemented a simple Nextflow workflow which enables any researcher to run the [PGAP, developed by NCBI](https://github.com/ncbi/pgap), genome annotation pipeline on [their own collection of bacterial genomes](https://github.com/FredHutch/PGAP-nf). Nextflow is also be used in ribosomal 16S amplicon analysis using [MaLiAmPi](https://github.com/jgolob/maliampi/) which is a phylogenetic placement-based pipeline for handling 16S rRNA amplicons. Nextflow can be utilized to automate the common task of sequencing the genome of microbial isolates using the [UniCycler assembler in an easy-to-use workflow](https://github.com/FredHutch/unicycler-nf/). The community here has also made it easier to do microbial pan-genome analysis with Nextflow using the [anvi'o software suite](http://merenlab.org/software/anvio/). Now researchers have an easy point of entry with a [workflow that imports a set of bacterial genomes into the anvi’o database format](https://github.com/FredHutch/nf-anvio-pangenome). Then launches a graphical viewer which allows the user to explore their pan-genome collection. Nextflow workflows are also being used here for [microbial RNA seq](https://github.com/FredHutch/microbial-rnaseq) and for [parallelizing whole-genome sequencing](https://github.com/FredHutch/nf-viral-metagenomics) to then align and matchback against a reference database in a distributed cloud service. 

More details about Nextflow-based tools used for microbiome analysis at Fred Hutch can be found at [Bioinformatics Tools for Microbiome Analysis](https://sciwiki.fredhutch.org/compdemos/microbiome_tools/). Fred Hutch researchers are also [building and maintaining a set of Nextflow workflows](https://github.com/FredHutch?utf8=%E2%9C%93&q=nf&type=&language=) for use by the [general community](https://github.com/FredHutch/reproducible-workflows/tree/master/nextflow) here and are also providing [examples of how to write your own workflows](https://sciwiki.fredhutch.org/compdemos/nextflow/) in Nextflow. Check out the supporting documentation on the [Fred Hutch Biomedical Data Science Wiki](https://sciwiki.fredhutch.org/compdemos/nextflow/).

#### Want to learn more?

If you want to learn more about Nextflow to see if it makes sense for you feel free to use the resources available to you at the Hutch. The [Bioinformatics & Data Science Cooperative or Coop](https://research.fhcrc.org/coop/en.html) supports a series of [community groups](https://sciwiki.fredhutch.org/scicomputing/reference_training/#community-groups) with one of them being for Nextflow. The Nextflow User Group meets every other Thursday in the Coop Lab (Arnold M1-B406) from 11-12pm to discuss issues related to the use of Nextflow. The group welcomes Nextflow users of all levels of expertise as well as those just learning about the tool. Check out the [Coop calendar](https://fredhutch.github.io/FHBig/calendar/) for the latest schedule. In addition, to Thursday's bi-weekly Nextflow User Group the Coop also supports a `#nextflow` [slack channel](https://fredhutch.github.io/coop/community/slack-new/) as well and you can find more information about that [here](https://sciwiki.fredhutch.org/scicomputing/reference_training/#community-groups).

Finally, the Translational Data Science IRC is sponsoring, with support from the Fred Hutch Microbiome Research Initiative, training in Nextflow April 23-24 which will include:
 
- Overview of Nextflow workflow system
- Language syntax and data structures
- Simple pipeline implementation
- Pipeline sharing and reproducibility
- Managing dependencies with containers
- Error recovery and strategies for error handling
- Implementation of an example variant calling pipeline

Apply now for a space in the training at https://www.surveymonkey.com/r/8DT7FBR. There is no cost to attend, but space is limited. Applications will be open until February 21st, and final acceptances will be sent out by March 6th.

- **What**: Nextflow Training
- **Where**: The Coop Lab (Arnold M1-B406)
- **When**: April 23-24, 2020
- **Contact**: Sam Minot, Staff Scientist, Microbiome Research Initiative

Thanks for supporting the bioinformatics and data science community!