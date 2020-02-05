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
#### What it is Nextflow?

[Nextflow](https://www.nextflow.io/) is one of a handful of workflow managers that have become popular in the last few years. Generally speaking, workflow managers are software tools that make it easier to run complex bioinformatic analyses that involve multiple steps, each of which may invoke a different piece of software with different environmental dependencies or resource requirements. Other workflow managers that people may recognize are Snakemake, Cromwell, Toil, and CWL. The benefits of a workflow manager like Nextflow is that it makes it easier to run your analysis while transparently managing all of the issues that tend to crop up when running a shell script like missing dependencies, not enough resources, cryptic failures and errors, or unable to easily publish or transfer the workflow to collaborators.

Nextflow is free and open source software distributed under the Apache 2.0 license and is developed by the [Comparative Bioinformatics group](https://www.crg.eu/en/programmes-groups/notredame-lab) at the [Barcelona Centre for Genomic Regulation (CRG)](https://www.crg.eu/). They have extensive documentation on how to write workflows and [run Nextflow on their documentation pages](https://www.nextflow.io/docs/latest/index.html). There is also [NF-Core](https://nf-co.re/), a community effort and curated collection of analysis pipelines built using Nextflow. Think of it as a repository of workflows. Additionally and more importantly, staff and research scientists here at Fred Hutch have created this [page to help get you up and running with Nextflow](https://sciwiki.fredhutch.org/compdemos/nextflow/) using the minimum requirements and AWS for the execution. The Fred Hutch research community is also building out and maintaining a [set of Nextflow workflows here as well](https://github.com/FredHutch/reproducible-workflows/tree/master/nextflow).

#### How it is used at Fred Hutch?

A workflow in Nextflow is a text file written in a particular format containing all of the details of the analysis that are generally true for all of the times that you need to run that analysis. Any of the details specific to a single experiment or batch of samples can be specified as parameters, which are specified for each individual batch of data whenever you invoke the workflow. The nice thing about Nextflow is that it can be used to run analyses on AWS, without having to know much about how AWS works. In other words, Nextflow will take care of running jobs on AWS, pulling data down from S3 into the job, running the analysis inside the appropriate Docker image, and pulling the results out of the job and returning them to the right place. Some of the use cases here have been:

        - scientists using it to wrestle with computational pipelines and get their work done
        - automatic parallelization across tasks
        - docker containerization
        - scaling up with cloud computing resources
        - utilizing detailed workflow summary reports

Some examples of the workflows designed and used here specifically help align proteins with DIAMOND, cluster proteins quicker, provide taxonomy counts using mothur, or provides taxonomic classification. Nextflow workflows are also being used here for concurrently processing large batches of samples for bacterial genomic annotation. Researchers here have implemented a simple workflow which enables any researcher to run the [PGAP, developed by NCBI](https://github.com/ncbi/pgap), genome annotation pipeline on their own collection of bacterial genomes and [details can be found here](https://github.com/FredHutch/PGAP-nf). Nextflow can also be used in ribosomal 16S amplicon analysis using [MaLiAmPi](https://github.com/jgolob/maliampi/) which is a phylogenetic placement-based pipeline for handling 16S rRNA amplicons. It can also be leverage to automate the common task of sequencing the genome of microbial isolates using the [UniCycler assembler in an easy-to-use workflow](https://github.com/FredHutch/unicycler-nf/). The community here has also made it easier with Nextflow to do microbial pan-genome analysis using the [anvi'o software suite](http://merenlab.org/software/anvio/). Now researchers have an easy point of entry with a [workflow that imports a set of bacterial genomes into the anvi’o database format, and then launches a graphical viewer which allows the user to explore their pan-genome collection](https://github.com/FredHutch/nf-anvio-pangenome). Nextflow workflows are also being used here for [microbial RNA seq](https://github.com/FredHutch/microbial-rnaseq) and for [parallelizing whole-genome sequencing](https://github.com/FredHutch/nf-viral-metagenomics) to then align and matchback against reference database yet in a distributed cloud service. More details can be found here, [Bioinformatics Tools for Microbiome Analysis](https://sciwiki.fredhutch.org/compdemos/microbiome_tools/).


Fred Hutch researchers are building and maintaining a set of Nextflow workflows for use by the [general community here](https://github.com/FredHutch/reproducible-workflows/tree/master/nextflow) and  also providing an example of how to write your own workflows.

Some Nextflow-based tools used for microbiome analysis at Fred Hutch can be found in the accompanying documentation https://sciwiki.fredhutch.org/compdemos/microbiome_tools/

- latest happenings of NF at FH?
        - Translational Data Science IRC is sponsoring a full training, with support from the Fred Hutch Microbiome Research Initiative, which will include:
            - Overview of Nextflow workflow system
            - Language syntax and data structures
            - Simple pipeline implementation
            - Pipeline sharing and reproducibility
            - Managing dependencies with containers
            - Error recovery and strategies for error handling
            - Implementation of an example variant calling pipeline

            Apply now for a space in the training at https://www.surveymonkey.com/r/8DT7FBR. There is no cost to attend, but space is limited. Applications will be open until February 21st, and final acceptances will be sent out by March 6th.
            
            What: Nextflow Training
            Where: The Coop Lab (Arnold M1-B406)
            When: April 23-24, 2020
            Contact: Sam Minot, Staff Scientist, Microbiome Research Initiative – sminot@fredhutch.org



#### Some of the gotchas
- link out to Eli's writings

#### Best practices of Nextflow at FH

#### Link out to SciWiki