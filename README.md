### Description

Documentation for Manta Trader, written in markdown and dynamically rendered on mantatrader.com

### How it works

Manta-Docs is added as a git submodule on the Manta-App repository, that way, as new commits are sent to the Manta-Docs repo, it is automatically integrated into the site with some CI/CD magic. The repo is then parsed when someone navigates to the /documentation page, and the markdown is rendered with a NPM package called react-markdown.

### Benefits

It is much easier to write in Markdown as it is quick and widely known. This also allows our team to colaborate easily, as well as accept PR's from outside

### How to Use

1. To create a new section on the docs, just create a new folder, and it will appear on the side menu
2. To create a new documenation page, simply create a .md file in the folder (category) that's appropriate, and once finished, submit a PR!
