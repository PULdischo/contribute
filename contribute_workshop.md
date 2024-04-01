# Contributing
Below you will find information and instructions about contributing a workshop to PULdischo. 

## Format
Requirements for file types are flexible, as the format for your workshop repository will vary based on your workshop's needs. Some workshops may use
slideshow files, while another may use a codebase from a static site generator. Regardless of the format, include a full copy of
all the files necessary to run the workshop. 

In addition to your workshop files, include a `readme.md` file that contains the following information:
- title and overview of workshop
- information about DiScho unit and how to get involved (workshops and consultations)
- technical specifications
- instructions for contributing
- credits and licensing information

A [template file](/readme_template.md) and [further instructions](/readme.md/) for the `readme.md` are available on this repository. 

When submitting your workshop to Github, make sure you follow our naming conventions:
- repository name should be a shortened version of the workshop title
- use all lowercase letters
- no white (or blank) spaces
- use hypens (rather than underscores) to indicate white spaces
- I.e. "Introduction to Python for Working with Text" should be titled "python-for-text"

Additionally, when making short links, include the repo name as the short link extension, when possible. 

## Contributing a new workshop (for PULdischo members only)
Only DiScho staff may contribute workshops, except by request. See instructions for [joining our organization](https://github.com/PULdischo/contribute?tab=readme-ov-file#join-our-organization-on-github). 

Instructions:
- create the workshop under your personal account (preferable) or dischoPUL. 
- from your personal account, fork the repository to PUL_discho
- in the "owner" dropdown, select "PUL_discho"

## Updating an existing workshop
Workshops should be updated every semester, ideally around the time that the workshop is being run. Workshops that are not being run that semester, or workshops that are archived, should be checked once a year to make sure the technology still works. 

To update an existing workshop, you may do so directly on github (preferable for beginners) or by downloading the workshop to your own computer. 

On github, follow these steps to update a workshop:
- at the top of the page that you want to update, select "edit file" icon (looks like a pencil). If you want to add a new file, navigate to the repo's main page (the landing page) and select "add file" from the menu at the top (next to the green "code" button).
- this option will open a new window where you can add or edit content.
- update the content then press "commit changes". Make sure you include a commit a simple message (no need to write an extended description in the extra box).

Making changes to a downladed copy of the workshop requires some knowledge about git (the underlying software for github), specifically how to initialize a repository, stage, commit, and push changes from your local machine to a remote repository. If you would like to do so, follow these steps:
- download ("clone") the repository from the organization's repository page
- make changes on the downloaded files, adding and committing your changes
- push your changes to the "remote" repo on github.

