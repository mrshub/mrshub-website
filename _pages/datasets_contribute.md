---
title: "Sharing data on MRSHub"
permalink: /datasets_contribute/
date: 2020-05-20T9:00:00+00:00
classes: wide
sidebar:
  nav: "datasets"
---

There are two easy ways to submit data to be featured on MRSHub (more details below:)

1. Create an [MRSHub forum](https://forum.mrshub.org) post with `[DATA SUBMISSION] ...` in the title, and include the submission information outlined below.

2. [E-mail (remove the dashes)](mailto:goe-ltzs-1[a]jh-mi.edu) us directly.

We will then generate an [MRSHub website](https://www.mrshub.org/datasets) entry.

# What kind of data can I submit?

We distinguish between two types of dataset submission:
- **Example datasets**: Smaller datasets that can be hosted in a single GitHub repository, and have a total size of less than 200 MB. We can fork these data into the [MRSHub GitHub account](https://github.com/mrshub).
- **Large datasets**: Larger-scale datasets exceeding a total size of 200 MB. These datasets need to be hosted on an external file hoster ([please click here for further instructions](https://www.mrshub.org/datasets_host_organize)). Once you submit a large dataset, we will add an entry to the [MRSHub dataset collection](https://www.mrshub.org/datasets/)

# What do I have to include in my submission?

There are two short text files required, and one optional file you can provide.

1. **(required)** In both submission methods, you have to provide a `SUBMISSION.md` text file. This contains the information that shows up in your MRSHub website entry.

2. **(required)** You should provide a `LICENSE.md` text file with your licensing requirements. **If not provided, we will automatically include a [BSD 3-clause license](https://opensource.org/licenses/BSD-3-Clause) (approved by the Open Source Initiative) to the dataset.**

    * Templates for various licenses (BSD, MIT, GPL) can be found [here](https://choosealicense.com/).

3. **(optional)** You may provide a small, square logo file (`.PNG` or `.JPG` format) that will help personalize your MRSHub website entry.

# What goes into the `SUBMISSION.md` file?

We provide a template `SUBMISSION.md` file for your convenience [here](/assets/examplefiles/SUBMISSION_DATA.md).

| Field | Mandatory? | Description |
| ----  | ---------- | ----------- |
| Developer | Yes | The name(s) you want to credit with development |
| Name of dataset | Yes | The name of the dataset. |
| Abstract | Yes | A brief description of the dataset you contribute. |
| Type | Yes | The type of data. We recommend to pick one of these: `svs` (single-voxel MRS), `mrsi`, `mm` (macromolecule data), `basis sets` (eg LCModel .BASIS files). |
| Format | Yes | The file formats used to store your dataset. |
| Sequence | Yes | The MRS sequence(s) used to acquire the dataset. |
| Credit | No | Indicate how you would like to be credited for your data - for example, if a certain publication should be cited, or whether you would like to be acknowledged in publications using your data. |
| Contact | No | A way you can be contacted, for example an e-mail address, the website of your lab, or your LinkedIn/Researchgate/Google Scholar page. Please note, this information will be made available on MRSHub website, so if you would rather your e-mail not be made public, please don't include. |
| Publication | No | A publication you want to associate with the submission |
| URL | Yes/No | A URL to a project page, data repository etc. associated with the submission. If you are submitting data hosted in an external repository, this field is mandatory. |


# Very specific details about how to submit

## Submitting through MRSHub forum

Create a new topic in the [MRSHub forum](https://forum.mrshub.org) with the basic submission information. We will then create an entry for your submission to the [MRSHub dataset collection](https://www.mrshub.org/datasets/). If you submit an example dataset (<200 MB total file size), we will also create a repository in the [MRSHub GitHub account](https://github.com/mrshub).

## Submitting directly via GitHub (EXAMPLE DATASETS ONLY)

Create a new topic in the [MRSHub forum](https://forum.mrshub.org) with a link to your example data repository. We will fork the repository into the [MRSHub GitHub account](https://github.com/mrshub).

## Submitting through e-mail

Send an [e-mail (remove the dashes)](mailto:goe-ltzs-1[a]jh-mi.edu) with the basic submission information. We will then create an entry for your submission to the [MRSHub dataset collection](https://www.mrshub.org/datasets/). If you submit an example dataset (<200 MB total file size), we will also create a repository in the [MRSHub GitHub account](https://github.com/mrshub).
