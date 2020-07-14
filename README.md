### Description

Documentation for Manta Trader, written in markdown and dynamically rendered on mantatrader.com

### How it works

Manta-Docs is added as a git submodule on the Manta-App repository, that way, as new commits are sent to the Manta-Docs repo, it is automatically integrated into the site with some CI/CD magic. The repo is then parsed when someone navigates to the /documentation page, and the markdown is rendered with a NPM package called react-markdown.

### Benefits

It is much easier to write in Markdown as it is quick and widely known. This also allows our team to colaborate easily, as well as accept PR's from outside

### How to Use

1. Simply create a new .md file in the directory below with it's name
2. Fill that .md file with the necissary documentation
3. Submit a PR!

### Directory

gettingstared.md - Getting Started
