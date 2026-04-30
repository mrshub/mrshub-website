---
title: "How to host and organize your dataset"
permalink: /datasets_host_organize/
date: 2020-06-18T9:00:00+00:00
classes: wide
sidebar:
  nav: "datasets"
---

# Hosting your dataset

We recommend uploading the data that you'd like to share in a secure, permanent file-hosting space, such as an institutional server, or a third-party cloud service.

While the neuroimaging community has created resources such as [OpenNeuro](https://openneuro.org/), these repositories are currently tailored towards imaging modalities such as fMRI, EEG or MEG.

However, several open-source initiatives allow sharing of arbitrary data. We recommend looking into one of the following resources:

| Name | Organization | Website | Description | Size limit |
| ---- | ------------ | ------- | ----------- | --------------- |
| Zenodo | OpenAIRE / CERN | [zenodo.org](https://zenodo.org/) | Zenodo is a general-purpose open-access repository developed under the European OpenAIRE program and operated by CERN. It allows researchers to deposit data sets, research software, reports, and any other research related digital artifacts. For each submission, a persistent digital object identifier (DOI) is minted, which makes the stored items easily citeable. | 50 GB per dataset (but number of datasets is unlimited)|
| Open Science Framework | Center for Open Science | [osf.io](https://osf.io) | The Open Science Framework (OSF) is an open source software project that facilitates open collaboration in science research. This framework was used to work on a project in the reproducibility of psychology research. | 5 GB for individual files (but unlimited project storage) |
| NITRC | NITRC | [nitrc.org](https://www.nitrc.org) | NITRC's mission is to provide a user-friendly knowledge environment that enables the distribution, enhancement, and adoption of neuroimaging tools and resources and has expanded from MR to Imaging Genomics, EEG/MEG, PET/SPECT, CT, optical imaging, clinical neuroinformatics, and computational neuroscience. | 2 GB |

Please note that it is your responsibility to comply with institutional, legislative and ethical requirements regarding data sharing and preserving data privacy. **We assume no responsibility or liability for data that is improperly de-identified, or shared without institutional permission. Such data will be immediately removed.** You can find further guidance [under this link](https://www.mrshub.org/datasets_privacy/).

# Organizing your dataset

Every researcher organizes their data in a different way, which often leads to confusion and a lot of time spent on figuring out someone else's organization structure.

The [Brain Imaging Data Structure (BIDS)](https://bids.neuroimaging.io/) specification is a consortium effort to standardize the way that neuroimaging data and metadata are organized into folder structures. When submitting your datasets to be featured on MRSHub, please consider organizing them according to the [BIDS folder hierarchy](https://github.com/bids-standard/bids-starter-kit/wiki/The-BIDS-folder-hierarchy), and include useful metadata (age, sex, ...).

If you upload raw data, please also consider including example code scripts you have used to load and process the data.
