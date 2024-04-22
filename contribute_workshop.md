# Contributing
Below you will find information and instructions about contributing a workshop to PULdischo. 

## Format
Requirements for file types are flexible, as the format for your workshop repository will vary based on your workshop's needs. Some workshops may use
slideshow files, while another may use a codebase from a static site generator. Regardless of the format, include a full copy of
all the files necessary to run the workshop. 

In addition to your workshop files, include a `readme.md` file (see a [template here](readme_template.md)) that contains the following information:
- title and overview of workshop
- information about DiScho unit and how to get involved (i.e. workshops and consultations)
- technical specifications
- instructions for contributing
- credits and licensing information

When submitting your workshop to Github, please follow our naming conventions:
- repository name is a shortened version of the workshop title
- only lowercase letters
- no white (or blank) spaces, with hypens (rather than underscores) as separators

For example, the workshop "Introduction to Python for Working with Text" should have the repo name "python-for-text" when you add it to PUldischo.

Additionally, when making short links for the workshop (like [bit.ly](https://bit.ly), include the repo name as the short link extension, when possible. 

## Contributing a new workshop (for PULdischo members only)
To contribute a workshop, you need to first join the PULdischo organization and then add your workshop to the organization. Please follow the instructions below.

Instructions for [joining the PULdischo organization](https://github.com/PULdischo/contribute?tab=readme-ov-file#join-our-organization-on-github). 

Instructions for adding your workshop:
- create the workshop under your personal account (preferable) or under dischoPUL
- from your personal account, fork the repository to PUL_discho (the owner username for PULdischo)
- in the "owner" dropdown, select "PUL_discho"

## Updating an existing workshop
Workshops should be updated every semester, ideally around the time that the workshop is being run. Workshops that are not being run that semester or workshops that are archived should be checked once a year to make sure the technology and/or content is functional and up to date.

To update an existing workshop, do so directly on the Github interface (preferable for beginners) or by downloading the workshop to your own computer and editing the files locally.

To work on Github interface, follow these steps:
- to edit an existing file, select "edit file" icon, which looks like a pencil, at the top of the page that you want to update
- to add a new file, navigate to the repo's main page and select "add file" from the menu at the top (next to the green "code" button)
- in the file editor window, you may add or edit content
- to save the changes, press "commit changes"
- include sure you include a commit a simple message of your changes

## Advanced git users
Making changes to a downladed copy of the workshop requires some knowledge of git (the underlying software for github), such as how to initialize a repository, stage, commit, and push changes from your local machine to a remote repository. To learn more about this process, see the [GitHub Docs](https://docs.github.com/en/get-started/using-git)

If you would like to update a workshop using git, follow these steps:
- download ("clone") the repository from the organization's repository page
- make changes on the downloaded files
- add and commit your changes 
- push your changes to the "remote" repo on github.

Please feel free to reach out to us with any questions.
