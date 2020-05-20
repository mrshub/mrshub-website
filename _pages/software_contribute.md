---
title: "Sharing software on MRSHub"
permalink: /software_contribute/
date: 2020-05-15T9:00:00+00:00
classes: wide
sidebar:
  nav: "software"

---

# How do I submit code to be hosted on MRSHub?

There are three easy ways to submit code to MRSHub (more details below:)

1. Create an [MRSHub forum](https://forum.mrshub.org) post with `[CODE SUBMISSION] ...` in the title and ...
   * Attach a `.ZIP` file (and other required information)
   * **OR**, include your existing GitHub repository (and other required information)

2. [E-mail (remove the dashes)](mailto:goe-ltzs-1[a]jh-mi.edu) us directly, we'll put it in our default repository.

We will generate an [MRSHub website](https://www.mrshub.org/software) entry, and add your code to the [MRSHub GitHub account](https://github.com/mrshub).

# How do I just create an MRSHub entry for my external project?

For larger projects, you may prefer to simply point to an existing website, or a repository where your code lives in. We would still love to add an entry to the [MRSHub software collection](https://www.mrshub.org/software)! In that case, simply follow the submission guidelines below, and make sure you point to the appropriate URL associated with your project.

If your project lives on GitHub, you can also add the topic `mrshub` to your repository - see this [how-to in the GitHub documentation](https://help.github.com/en/github/administering-a-repository/classifying-your-repository-with-topics). Your repository will then appear if GitHub users search for the [`mrshub` topic](https://github.com/topics/mrshub).

# What do I have to include in my submission?

There is one short text file required, and two optional files you can provide.

1. **(required)** In all three submission methods, you have to provide a `SUBMISSION.md` text file. This contains the information that shows up in your MRSHub website entry.

2. **(optional)** You may provide a `LICENSE.md` text file with your licensing requirements.
  * **If not provided, we will automatically include a [BSD 3-clause license](https://opensource.org/licenses/BSD-3-Clause) (approved by the Open Source Initiative) to your repository.**
  * Templates for various licenses (BSD, MIT, GPL) can be found [here](https://choosealicense.com/).

3. **(optional)** You may provide a small, square logo file (`.PNG` or `.JPG` format) that will help personalize your MRSHub website entry.

# What goes into the `SUBMISSION.md` file?

We provide a template `SUBMISSION.md` file for your convenience [here](/assets/examplefiles/SUBMISSION.md).

| Field | Mandatory? | Description |
| ----  | ---------- | ----------- |
| Developer | Yes | The name(s) you want to credit with development |
| Name of software | Yes | A unique, descriptive name for the software/piece of code |
| Abstract | Yes | A brief abstract of the purpose, scope, and functions of the code you contribute |
| Languages | Yes | The primary programming language(s) of your contribution |
| Credit | No | Indicate if and how you would like to be credited for your software - for example, if a certain publication should be cited, or whether you would like to be acknowledged in publications using your code. Can also include general information about licensure. |
| Contact | No | A way you can be contacted, for example an e-mail address, the website of your lab, or your LinkedIn/Researchgate/Google Scholar page. Please note, this information will be made available on MRSHub website, so if you would rather your e-mail not be made public, please don't include. |
| Publication | No | A publication you want to associate with the submission |
| URL | No | A URL to a project page, code repository etc. associated with the submission |

# Very specific details about how to submit

## Submitting through MRSHub forum

Create a new topic in the [MRSHub forum](https://forum.mrshub.org) with `[CODE SUBMISSION]` at the start of the title. Give us a **brief** description of what you are providing and how you've included it in this post. Upload a `.ZIP` file containing the code folder, example data, the `SUBMISSION.md` file and (optionally) the `LICENSE.md` and logo files to the post **OR** include a link in the body of the post to an online file host where we can access your files. We will create a repository in the [MRSHub GitHub account](https://github.com/mrshub) for you.

## Submitting directly via GitHub

Create a new topic in the [MRSHub forum](https://forum.mrshub.org) with `[CODE SUBMISSION]` at the start of the title. In the body of the post, include a link to your existing GitHub repository. Your repository should include a code folder, example data, the `SUBMISSION.md` file and (optionally) the `LICENSE.md` and logo files. We will fork the repository into the [MRSHub GitHub account](https://github.com/mrshub).

(optional) Whenever you update your own repository and wish to have the new features included in MRSHub repository, submit a pull request from your personal repository to MRSHub repository, or let us know in the forum topic belonging to your initial submission.

## Submitting through e-mail

Create a `.ZIP` file containing the code folder and example data, the `SUBMISSION.md` file and (optionally) the `LICENSE.md` and logo files. Send us an [e-mail (remove the dashes)](mailto:goe-ltzs-1[a]jh-mi.edu) with the `.ZIP` file attached, or include a link to an online file host where we can access it.

# Good coding practices

"Code is more often read than written." (Guido van Rossum)

We understand that most MRSHub users and contributors are MR physicists, neuroscientists, or clinical researchers first, and code developers second. Any line of code can potentially be useful to someone else. Don't fret if you think your code "isn't perfect"! If you can save someone else a chunk of time they'd otherwise spend duplicating your effort, your code is good enough!

HOWEVER, to maximize the impact and usability of your submission, please try and make your code as generalizable, readable, and understandable as you can. Annotate and comment as much of your code as possible. Provide an example dataset along the code itself, and show the output of your code so users know what the code is supposed to accomplish.

Many programmers have written about good coding practices:
* [Guidelines for writing clean and fast code in MATLAB](https://www.mathworks.com/matlabcentral/fileexchange/22943-guidelines-for-writing-clean-and-fast-code-in-matlab)
* [How to Write Beautiful Python Code With PEP 8](https://realpython.com/python-pep8/), following the official [PEP 8 Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)
* [How to write Clean, Beautiful and Effective C++ Code](https://medium.com/@MKahsari/how-to-write-clean-beautiful-and-effective-c-code-d4699f5e3864)
* [Advanced R - Style Guide](http://adv-r.had.co.nz/Style.html)
