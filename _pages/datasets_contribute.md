---
title: "How to contribute data to MRSHub"
permalink: /datasets_contribute/
date: 2020-05-20T9:00:00+00:00
classes: wide
sidebar:
  nav: "datasets"
---

# Why share data?

Contributing MRS datasets that you acquired and/or simulated provides the community with new resources to...
* develop and improve data processing routines.
* benchmark quantification algorithms.
* have your findings scrutinized and reproduced.
* get credit for your work.
* gain recognition of your name and familiarity with your work.

# How do I submit data?

There are two easy ways to submit data to be featured on the MRSHub (more details below:)

1. Create an [MRSHub forum](https://forum.mrshub.org) post with `[DATA SUBMISSION] ...` in the title, and include the submission information outlined below.

2. [E-mail (remove the dashes)](mailto:goe-ltzs-1[a]jh-mi.edu) us directly.

We will then generate an [MRSHub website](https://www.mrshub.org/datasets) entry.

# What kind of data can I submit?

We distinguish between two types of dataset submission:
- **Example datasets**: Smaller datasets that can be hosted in a single GitHub repository, and have a total size of less than 200 MB. We can fork these data into the [MRSHub GitHub account](https://github.com/mrshub).
- **Large datasets**: Larger-scale datasets exceeding a total size of 200 MB. These datasets need to be hosted on an external file hoster, such as an institutional server, cloud service, or [NITRC](https://www.nitrc.org). Once you submit a large dataset, we will add an entry to the [MRSHub dataset collection](https://www.mrshub.org/datasets/)

# What do I have to include in my submission?

There is one short text file required, and two optional files you can provide.

1. **(required)** In both submission methods, you have to provide a `SUBMISSION.md` text file. This contains the information that shows up in your MRSHub website entry.

2. **(optional)** You may provide a `LICENSE.md` text file with your licensing requirements.
  * **If not provided, we will automatically include a [BSD 3-clause license](https://opensource.org/licenses/BSD-3-Clause) (approved by the Open Source Initiative) to your repository.**
  * Templates for various licenses (BSD, MIT, GPL) can be found [here](https://choosealicense.com/).

3. **(optional)** You may provide a small, square logo file (`.PNG` or `.JPG` format) that will help personalize your MRSHub website entry.

# What goes into the `SUBMISSION.md` file?

We provide a template `SUBMISSION.md` file for your convenience [here](/assets/examplefiles/SUBMISSION.md).

| Field | Mandatory? | Description |
| ----  | ---------- | ----------- |
| Developer | Yes | The name(s) you want to credit with development |
| Name of dataset | Yes | The name of the dataset. |
| Abstract | Yes | A brief description of the dataset you contribute. |
| Format | Yes | The data formats used in your dataset. |
| Sequence | Yes | The MRS sequence(s) used to acquire the dataset. |
| Credit | No | Indicate how you would like to be credited for your data - for example, if a certain publication should be cited, or whether you would like to be acknowledged in publications using your data. |
| Contact | No | A way you can be contacted, for example an e-mail address, the website of your lab, or your LinkedIn/Researchgate/Google Scholar page. Please note, this information will be made available on the MRSHub website, so if you would rather your e-mail not be made public, please don't include. |
| Publication | No | A publication you want to associate with the submission |
| URL | No | A URL to a project page, data repository etc. associated with the submission |

# Very specific details about how to submit

## Submitting through the MRSHub forum

Create a new topic in the [MRSHub forum](https://forum.mrshub.org) with the basic submission information. We will then create an entry for your submission to the [MRSHub dataset collection](https://www.mrshub.org/datasets/). If you submit an example dataset (<200 MB total file size), we will also create a repository in the [MRSHub GitHub account](https://github.com/mrshub).

## Submitting directly via GitHub (EXAMPLE DATASETS ONLY)

Create a new topic in the [MRSHub forum](https://forum.mrshub.org) with a link to your example data repository. We will fork the repository into the [MRSHub GitHub account](https://github.com/mrshub).

## Submitting through e-mail

Send an [e-mail (remove the dashes)](mailto:goe-ltzs-1[a]jh-mi.edu) with the basic submission information. We will then create an entry for your submission to the [MRSHub dataset collection](https://www.mrshub.org/datasets/). If you submit an example dataset (<200 MB total file size), we will also create a repository in the [MRSHub GitHub account](https://github.com/mrshub).

# Organizing your dataset

Every researcher organizes their data in a different way, which often leads to confusion and a lot of time spent on figuring out someone else's organization structure.

The [Brain Imaging Data Structure (BIDS)](https://bids.neuroimaging.io/) specification is a consortium effort to standardize the way that neuroimaging data and metadata are organized into folder structures. When submitting your datasets to be featured on the MRSHub, please consider organizing them according to the [BIDS folder hierarchy](https://github.com/bids-standard/bids-starter-kit/wiki/The-BIDS-folder-hierarchy), and include useful metadata (age, sex, ...)

# De-identification

It is your responsibility to comply with the requirements to remove all protected health information (PHI) from file names, headers, and files themselves. It is also your responsibility to comply with your institutional, legislative, and ethical requirements regarding data sharing. If you include anatomical data in your dataset, make sure that you make use of appropriate defacing algorithms as well.

You can find a list of de-identification tools in the [MRSHub software collection](https://www.mrshub.org/software_deid).

If you see an instance of questionable data including PHI hosted in our repository or in a repository linked on the MRSHub website, please contact us through the forum so we can address the situation.
