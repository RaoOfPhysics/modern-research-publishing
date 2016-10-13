# Modern workflows for publishing research [![made for: #mozstudyCERN](https://img.shields.io/badge/made%20for-%23mozstudyCERN-blue.svg)](https://github.com/CERNStudyGroup/cernstudygroup.github.io/issues)

A meta-tutorial for [a CERN Study Group lesson](https://github.com/CERNStudyGroup/cernstudygroup.github.io/issues/57) on using markdown, GitHub, Authorea and Zenodo to publish your next paper (or your thesis!).

## Intro

There are many publishing workflows in academia, but here’s something that has worked for me.
I’ve decided to conduct this Study Group lesson as an interactive, hands-on tutorial.
We’re going to take a look at the following topics:

- Getting started with the tools
- Why markdown? / Why not LaTeX?
- Git and branches
- Authorea and its export options
- Benefits of using GitHub (over, at the moment, GitLab)
- Minting DOIs with Zenodo

## Requirements

- A text editor for working with your markdown files (I use [Atom](https://atom.io/) but Vim works pretty well too)
- Git, of course
- A GitHub account
- An [Authorea](https://www.authorea.com/signup) account linked with your GitHub account and associated with your CERN e-mail address
- A [Zenodo](https://zenodo.org/signup/) account linked with your GitHub account

## Basic steps

1. Create a new document in Authorea.
Make sure to select `Markdown` as the format.
2. Setup [Authorea&harr;GitHub](https://www.authorea.com/users/3/articles/17235/_show_article) integration.
3. Clone your newly created repo from GitHub to your desktop.
4. Add a [meaningful `README(.md)`](https://github.com/noffle/art-of-readme) file.
5. License your content appropriately with a `LICENSE(.md)` file.
6. Add/edit chapters/sub-chapters into appropriate directories.
7. Add/edit relative links to chapters/sub-chapters in your `layout.md` file in the order you want them to appear.
8. Add, commit, push!
9. [OPTIONAL] GOTO 6
10. When you're satisfied, export the file from Authorea into PDF in any style you like.
11. Flip the [GitHub&rarr;Zenodo](https://guides.github.com/activities/citable-code/) switch, publish a “release” including the newly prepared PDF and get a lovely DOI to go with your publication!

## Resources:

- [CERN Bulletin article on the lab's partnership with Authorea](http://cds.cern.ch/journal/CERNBulletin/2015/49/News%20Articles/2105082) a.k.a. free private documents with CERN credentials (for now?)
- @RaoOfPhysics’s example &mdash; conference proceedings:
    - On GitHub: https://github.com/RaoOfPhysics/201607_PCST-Proceedings
        - All mistakes/changes/whatnot: https://github.com/RaoOfPhysics/201607_PCST-Proceedings/commits/master
    - On Zenodo: http://dx.doi.org/10.5281/zenodo.60214
    - On Authorea: https://www.authorea.com/users/8205/articles/116704/
    - Submitted version: http://www.pcst.co/papers/view/292
- @RaoOfPhysics’s PhD Starter Kit: https://raoofphysics.github.io/phd-starter-kit/

## Licence

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Modern workflows for publishing research</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/RaoOfPhysics/modern-research-publishing" property="cc:attributionName" rel="cc:attributionURL">Achintya Rao</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
