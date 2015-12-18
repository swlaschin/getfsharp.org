# getfsharp.org

This repo contains content for the http://getfsharp.org site.
We are using GitHub pages, so note that the working branch is `gh-pages`, not `master`.

## How to contribute

We need your help us improve the entire "out-of-the-box experience" (OOBE) of using F#,
so that includes not only installing F#, but also installing dependencies like Mono, important tools like FAKE, etc.

Anything that stops the users' experience from being smooth and trouble-free is an OOBE issue!

So please help!

* If you get feedback that any of the download or getting starting instructions are unclear or incorrect, please raise an issue and tag it with the "OOBE" label. 
* If you feel that a particular distribution or method of download is undocumented, or any other content is missing, please raise an issue and tag it with the "Content" label.

## Contributing new content

If you would like to contribute content yourself, please fork the repo, make changes, and then submit a PR to the `gh-pages` branch.
All reasonable PRs will be accepted.

For instructions for a new distribution (say Atom with Ionide):

1. Create a subdirectory in all lower case (`/atom-ionide/` say).
1. Add an `index.md` file to that directory with the instructions written in markdown.
1. Add any images into that directory as well.
1. Finally, edit the home page (`/index.md`)

*NOTE: Please do NOT remove the `CNAME` file in your fork, even though github tells you too!*
