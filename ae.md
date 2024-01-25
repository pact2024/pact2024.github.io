---
title: PACT 2023 Artifact evaluation
description:  Artifact evaluation instructions
id:           ae
layout:       page_sidebar
show_sidebar: true
---

# Artifact Submission

_Note: This page is based on the [submission guidelines for artifact evaluation set by ML Commons](https://github.com/mlcommons/ck/blob/master/docs/artifact-evaluation/submission.md)._

PACT 2023 is happy to introduce an Artifact Evaluation process to promote the reproducibility of experimental results. We encourage artifact sharing to help the community quickly validate and compare alternative approaches. PACT 2023’s artifact evaluation process will follow the [guidelines for artifact evaluation set by ML Commons](https://github.com/mlcommons/ck/blob/master/docs/artifact-evaluation/submission.md).

**Artifact submissions will be due by August 22, 2023**.

Authors are invited to formally describe all supporting material (code, data, models, workflows, results) using the [unified Artifact Appendix and the Reproducibility Checklist template](https://github.com/mlcommons/ck/blob/master/docs/artifact-evaluation/checklist.md) and submit it to the [single-blind AE process](https://github.com/mlcommons/ck/blob/master/docs/artifact-evaluation/reviewing.md). Reviewers will then collaborate with the authors to evaluate their artifacts and assign the following [ACM reproducibility badges](https://www.acm.org/publications/policies/artifact-review-and-badging-current):

![](https://www.acm.org/binaries/content/gallery/acm/publications/replication-badges/artifacts_available_dl.jpg)
![](https://www.acm.org/binaries/content/gallery/acm/publications/replication-badges/artifacts_evaluated_functional_dl.jpg)
![](https://www.acm.org/binaries/content/gallery/acm/publications/replication-badges/results_reproduced_dl.jpg)

## Preparing your Artifact Appendix and the Reproducibility Checklist

You need to prepare the [Artifact Appendix](https://github.com/mlcommons/ck/blob/master/docs/artifact-evaluation/template/ae.tex) describing all software, hardware and data set dependencies, key results to be reproduced, and how to prepare, run and validated experiments.  You can find the examples of Artifact Appendices in the following [reproduced papers](https://cknow.io/reproduced-papers).

##  Preparing your experimental workflow

**You can skip this step if you want to share your artifacts without the validation of experimental results - in such case your paper can still be entitled for the "artifact available" badge!**

We strongly recommend you to provide at least some automation scripts to build your workflow, all inputs to run your workflow, and some expected outputs to validate results from your paper. You can then describe the steps to evaluate your artifact using README files or [Jupyter Notebooks](https://jupyter.org/).

Feel free to reuse [portable CM scripts](https://github.com/mlcommons/ck/tree/master/cm-mlops/script) being developed by the MLCommons to automate common steps to prepare and run various benchmarks across continuously changing software, hardware and data.

## Making artifacts available to evaluators

Most of the time, the authors make their artifacts available to the evaluators via GitHub, GitLab, BitBucket or private repositories. It allows the authors to quickly fix encountered issues during evaluation before submitting the final version to archival repositories.


Other acceptable methods include:

*   Using zip or tar files with all related code and data, particularly when your artifact should be rebuilt on reviewers' machines (for example to have a non-virtualized access to a specific hardware).
*   Using [Docker](https://www.docker.com/), [Virtual Box](https://www.virtualbox.org/) and other containers and VM images.
*   Arranging remote access to the authors' machine with the pre-installed software
*   this is an exceptional cases when rare or proprietary software and hardware is used. You will need to privately send the private access information to the AE chairs.

Note that your artifacts will receive the ACM "artifact available" badge **only if** they have been placed on any publicly accessible archival repository such as [Zenodo](https://zenodo.org/), [FigShare](https://figshare.com/), and [Dryad](http://datadryad.org/). You will need to provide a DOI automatically assigned to your artifact by these repositories in your final Artifact Appendix!

##  Submitting artifacts

Write a brief abstract describing your artifact, the minimal hardware and software requirements, how it supports your paper, how it can be validated and what the expected result is. Do not forget to specify if you use any proprietary software or hardware! This abstract will be used by evaluators during artifact bidding to make sure that they have an access to appropriate hardware and software and have required skills.

Submit the artifact abstract and the PDF of your paper with the Artifact Appendix attached using the PACT HotCRP website. Artifact evaluation will go live on 18 August 2023.

## Asking questions

If you have questions or suggestions, do not hesitate to get in touch with the the AE chairs: James Tuck [jtuck AT ncsu DOT edu] or Soumyadeep Ghosh [deepghosh AT meta DOT com].

##  Preparing your camera-ready paper

If you have successfully passed AE with at least one reproducibility badge, you will need to add up to 2 pages of your artifact appendix to your camera ready paper while removing all unnecessary or confidential information. This will help readers better understand what was evaluated and how.
