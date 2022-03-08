PP-Module for WLAN Clients
===============
![Master Badges](https://img.shields.io/badge/Build-master-black.svg)
![Build](https://github.com/commoncriteria/wlanclient/workflows/Build/badge.svg)
![Validate](https://github.com/commoncriteria/wlanclient/workflows/Validate/badge.svg)

![Last QuickBuilt Branch](https://raw.githubusercontent.com/commoncriteria/wlanclient/gh-pages/build-branch-badge.svg)
[![Validation](https://raw.githubusercontent.com/commoncriteria/wlanclient/gh-pages/validation.svg)](https://github.com/commoncriteria/wlanclient/blob/gh-pages/ValidationReport.txt)
[![SanityChecks](https://raw.githubusercontent.com/commoncriteria/wlanclient/gh-pages/warnings.svg)](https://github.com/commoncriteria/wlanclient/blob/gh-pages/SanityChecksOutput.md)
[![SpellCheck](https://raw.githubusercontent.com/commoncriteria/wlanclient/gh-pages/spell-badge.svg)](https://github.com/commoncriteria/wlanclient/blob/gh-pages/SpellCheckReport.txt)
[![QuickBuild](https://github.com/commoncriteria/wlanclient/actions/workflows/quick_build.yml/badge.svg)](https://commoncriteria.github.io/wlanclient)


This repository hosts the draft version of the PP-Module for WLAN Clients based on the 
[Essential Security Requirements (ESR)](https://commoncriteria.github.io/pp/QQQQ/QQQQ-esr.html) for this technology class of 
products. This PP-Module is intended for use with the following Base-PPs:

* General Purpose Operating System (GPOS) Protection Profile
* Mobile Device Fundamentals (MDF) Protection Profile

This repository is used to facilitate collaboration and development on the draft document. 
See the [release](#Release-Version) section if you are looking for the officially released version for evaluations. 
A list of products that have passed evaluation against this Protection Profile can be found [here](https://www.niap-ccevs.org/Profile/Info.cfm?PPID=386&id=386).

## Draft Version

* [PP-Module for WLAN Client v1.0](https://commoncriteria.github.io/pp/wlanclient/wlanclient-release.html) (html)
* [PP-Module for WLAN Client v1.0](https://commoncriteria.github.io/pp/wlanclient/wlanclient-release.pdf) (pdf)
* [Supporting Document](https://commoncriteria.github.io/pp/wlanclient/wlanclient-sd.html) (html)
* [Supporting Document](https://commoncriteria.github.io/pp/wlanclient/wlanclient-sd.pdf) (pdf)
## Release Version
* [PP-Module for WLAN Client](https://www.niap-ccevs.org/Profile/Info.cfm?PPID=386&id=386)

## Contributing

If you are interested in contributing directly to future versions the this Protection Profile, please consider joining the NIAP technical community.

* [How to join the NIAP Technical Community (Mailing list and updates)](https://www.niap-ccevs.org/NIAP_Evolution/tech_communities.cfm)

## Feedback

Questions, comments, and fixes can be submitted to the [repository issue tracker](https://github.com/commoncriteria/wlanclient/issues)

## Quickstart
To clone this project along with its _transforms_ submodule run:

````
  git clone --recursive git@github.com:commoncriteria/wlanclient.git
````
To pull updates from the upstream _transforms_ submodule and commit them run:
````
 git submodule update --remote transforms
 git add transforms
 git commit
````

### Development Info
[Help working with Transforms Submodule](https://github.com/commoncriteria/transforms/wiki/Working-with-Transforms-as-a-Submodule)

## Repository Content
* input - Contains the 'meat' of the project. It's the input content (in XML form) that gets transformed to readable html.
* output - The output directory where the html is placed after transformation.
* output/images - The directory where images are stored
* transforms - Points to the transform subproject which is really a repository for resources shared amongst many Common Criteria projects.

## Links 
* [National Information Assurance Partnership (NIAP)](https://www.niap-ccevs.org/)
* [Common Criteria Portal](https://www.commoncriteriaportal.org/)

## License
See [License](./LICENSE)
