---
title: 'DataLad: distributed system for joint management of code, data, and their relationship'
tags:
  - Python
  - command line
  - version control
  - data management
  - data distribution
  - data provenance
  - reproducibility
authors:
 - name: Yaroslav O. Halchenko^[co-first author]  # 4655 commits, issues: opened 1399 participated in 649
   orcid: 0000-0003-3456-2493
   affiliation: 1
 - name: Kyle Meyer  # 2152 commits, issues: opened 85 participated in 398
   affiliation: 1
 - name: Benjamin Poldrack  # 1898 commits, issues: opened 82 participated in 461
   orcid: 0000-0001-7628-0801
   affiliation: 2
 - name: Debanjum Singh Solanky  # 212 commits, issues: opened 7 participated in 12
   orcid: 0000-0002-0774-6564
   affiliation: 1
 - name: Adina Wagner  # 98 commits, issues: opened 36 participated in 45
   orcid: 0000-0003-2917-3450
   affiliation: 2
 - name: Jason Gors  # 60 commits, issues: opened 2 participated in 1
   affiliation: 1
 - name: Dave MacFarlane  # 30 commits, issues: opened 4 participated in 4
   affiliation: 14 # add full names if not yet listed, or indexes if already are
 - name: Dorian Pustina  # 0 commits, issues: opened 30 participated in 5
   orcid: 0000-0002-2834-7220
   affiliation: 7
 - name: Vanessa Sochat  # 16 commits, issues: opened 8 participated in 4
   orcid: 0000-0002-4387-3819
   affiliation: 4
 - name: Satrajit S. Ghosh  # 0 commits, issues: opened 7 participated in 13
   orcid: 0000-0002-5312-6729
   affiliation:  11
 - name: Christian Mönch  # 11 commits, issues: opened 4 participated in 1
   orcid: 0000-0002-3092-0612
   affiliation:  2
 - name: Christopher J. Markiewicz  # 5 commits, issues: opened 5 participated in 6
   orcid: 0000-0002-6533-164X
   affiliation: 9
 - name: Laura Waite  # 2 commits, issues: opened 11 participated in 2
   orcid: 0000-0003-2213-7465
   affiliation: 2
 - name: Ilya Shlyakhter  # 0 commits, issues: opened 12 participated in 3
   orcid: 0000-0002-9854-5118
   affiliation: 18
 - name: Alejandro de la Vega  # 4 commits, issues: opened 7 participated in 3
   orcid: 0000-0001-9062-3778
   affiliation:  10
 - name: Soichi Hayashi  # 1 commits, issues: opened 10 participated in 1
   orcid: 0000-0003-3641-3491
   affiliation:  13
 - name: Christian Olaf Häusler  # 10 commits, issues: opened 2 participated in 0
   orcid: 0000-0002-0936-317X
   affiliation: "2, 3"
 - name: Jean-Baptiste Poline  # 0 commits, issues: opened 2 participated in 7
   orcid: 0000-0002-9794-749X 
   affiliation: 5
# - name: Taylor Olson  # 7 commits, issues: opened 1 participated in 0
#   orcid: 
#   affiliation:  # add full names if not yet listed, or indexes if already are
# - name: Chris Gorgolewski  # 0 commits, issues: opened 5 participated in 3
#   orcid: 
#   affiliation:  # add full names if not yet listed, or indexes if already are
# - name: Simon Dube  # 0 commits, issues: opened 6 participated in 1
#   orcid: 
#   affiliation:  # add full names if not yet listed, or indexes if already are
 - name: Tobias Kadelka  # 0 commits, issues: opened 4 participated in 3
   orcid: 0000-0002-0152-3490
   affiliation: 2
 - name: Kusti Skytén  # 1 commits, issues: opened 4 participated in 1
   orcid: 0000-0001-7460-1157
   affiliation: 8
 - name: Dorota Jarecka  # 0 commits, issues: opened 5 participated in 1
   orcid: 0000-0001-8282-2988
   affiliation: 11
 - name: David Kennedy  # 0 commits, issues: opened 4 participated in 1
   orcid: 0000-0002-9377-0797
   affiliation:  17
 - name: Ted Strauss  # 0 commits, issues: opened 4 participated in 1
   orcid: 0000-0002-1927-666X
   affiliation:  15
# - name: Anisha Keshavan  # 3 commits, issues: opened 1 participated in 0
#   orcid: 
#   affiliation:  # add full names if not yet listed, or indexes if already are
# - name: Arvind Sharma  # 0 commits, issues: opened 4 participated in 0
#   orcid: 
#   affiliation:  # add full names if not yet listed, or indexes if already are
 - name: Matt Cieslak  # 2 commits, issues: opened 2 participated in 0
   orcid: 0000-0002-1931-4734
   affiliation:  16
 - name: Peter Vavra  # 0 commits, issues: opened 3 participated in 1
   orcid: 0000-0001-8432-5459
   affiliation: 12
 - name: Horea-Ioan Ioanas  # 1 commits, issues: opened 3 participated in 0
   orcid: 0000-0001-7037-2449
   affiliation: "6"
 - name: Robin Schneider  # 1 commits, issues: opened 1 participated in 1
   orcid: 0000-0003-1952-5459
   affiliation: 19
 - name: Michael Hanke^[co-first author]  # 4158 commits, issues: opened 1097 participated in 780
   orcid: 0000-0001-6398-6370
   affiliation: "2, 3"
affiliations:
 - name: Center for Open Neuroscience, Department of Psychological and Brain Sciences, Dartmouth College, Hanover, NH, USA
   index: 1
 - name: Institute of Neuroscience and Medicine, Brain & Behaviour (INM-7), Research Centre Jülich, Jülich, Germany
   index: 2
 - name: Institute of Systems Neuroscience, Medical Faculty, Heinrich Heine University Düsseldorf, Düsseldorf, Germany
   index: 3
 - name: Lawrence Livermore National Lab, Livermore, CA, USA
   index: 4
 - name: Faculty of Medicine and Health Sciences, McConnell Brain Imaging Centre, McGill University, Montreal, Canada
   index: 5
 - name: Department of Biological Engineering, Massachusetts Institute of Technology, Cambridge, USA
   index: 6
 - name: CHDI Management/CHDI Foundation, Princeton, NJ, USA
   index: 7
 - name: University of Oslo, Oslo, Norway
   index: 8
 - name: Stanford University, Stanford, CA, USA
   index: 9
 - name: The University of Austin at Austin, Austin, TX, USA
   index: 10
 - name: Massachusetts Institute of Technology, Cambridge, MA, USA
   index: 11
 - name: Department of Biological Psychology, Otto-von-Guericke-University Magdeburg, Magdeburg, Germany
   index: 12
 - name: Indiana University, Bloomington, IN, USA
   index: 13
 - name: McGill Centre for Integrative Neuroscience, Montreal, Canada
   index: 14
 - name: Montreal Neurological Institute, McGill University, Montreal, Canada
   index: 15
 - name: University of Pennsylvania, Philadelphia, PA
   index: 16
 - name: University of Massachusetts Medical School, Worcester, MA, USA
   index: 17
 - name: Quest Diagnostics, Marlborough, MA, USA
   index: 18
 - name: Independent Developer, Germany
   index: 19
date: 24 March 2021
bibliography: paper.bib

---

# Summary

The DataLad project ([datalad.org](http://datalad.org)) adapted the models of open-source software development and distribution to address technical limitations of today's data management, sharing, and provenance collection.
Born from the idea to provide a unified data distribution for neuroscience that takes a versatile system for data logistics
([git-annex](https://git-annex.branchable.com)), built on top of the most popular distributed version control system
([Git](https://git-scm.com)), DataLad delivers a completely open, pioneering platform for flexible decentralized research data management (dRDM) [@Hanke_2021].
It aims to make data management as easy as managing code, streamlining data consumption, update, and publication.
It aids handling data of any size or type, and can link them with precisely versioned, lightweight dependencies.
DataLad helps to make science more FAIR, by capturing complete and actionable process provenance of any data transformation to enable automatic re-computation.

# Statement of Need

Code, data, and computing environments are at the core of scientific practice.
Unobstructed access and efficient management of all those digital objects promotes scientific discovery through collaboration, reproducibility, and replicability.
Established and widely-adopted infrastructure and procedures, like software distributions, distributed version control systems, and social coding portals like GitHub, streamline the collaborative development and use of research software.
However, data have remained a “2nd-class citizen” in the contemporary scientific process, despite the increasing embracement of the FAIR principles [@FAIR2016].
1) Disconnected data portals force a cacophony of data access and authentication methods upon the scientific community; 2) data versioning is rarely performed, or nowhere close to the precision and inspectability that is standard in software development; and 3) data provenance---if shared at all---is often not complete, because their capture is rarely considered to be an integral part of the scientific process.
DataLad aims to solve all these issues by providing targeted interfaces and interoperability adapters to standard tools and services, scientific and commercial.
It enables workflows that are particularly suited for reproducible science, such as actionable process provenance capture for arbitrary command execution that enables automatic re-execution.
In order to maximize its utility and target audience, DataLad is available for all major operating systems, and can be integrated into established workflows and environments with minimal adjustments.

## Why Git and git-annex?

Git is the most popular version control system for software development[^1].
It is a distributed content management system, specifically tuned towards managing and collaborating on text files, and excels at making all content committed to Git reliably and efficiently available to all clones of a repository.
At the same time, Git is not designed to efficiently handle large (e.g., over a gigabyte) or binary files [see, e.g., @opensource:git-binary].
This makes it hard or impossible to use Git directly for distributed data storage with tailored access to individual files. <!-- IMHO the following sentence is unnecessarilly detailed and ultimately confusing for non Git-cracks, so I removed it: ", or even to fully remove file content without severely impacting the integrity of a repository." -->
Git-annex takes advantage of Git's ability to efficiently manage textual information to overcome this limitation.
File content managed by git-annex is placed into a managed repository annex, instead of committing it directly to Git.
Instead of the file content, git-annex only commits a compact reference that enables identification and association of a file name with the content.
File content references are typically based on a checksum of the content.
Using these identifiers, git-annex tracks content availability across all repository clones (local or remote), or external resources such as URLs pointing to individual files on the web.
Upon user request, git-annex automatically manages data transport to and from a local repository annex at a granularity of individual files.
With this simple approach, git-annex enables separate and optimized implementations for identification and transport of arbitrarily large files, using an extensible set of protocols, while retaining the distributed nature and compatibility with versatile workflows for versioning and collaboration provided by Git.

[^1]: https://en.wikipedia.org/wiki/Git#Adoption

## Why Git and git-annex alone are not enough?

<!-- MIH thinks: #1 nesting, #2 reproducible execution, #3 additional software adaptors for concrete services relevant for science -->

**They are generic and lack support for domain-specific solutions.** 
Git can interact with other repositories on the file system or accessible via a set of standard (ssh, http) or custom (Git) network transport protocols.
Interaction with non git-aware portals should then be implemented via custom Git transfer protocols, as, e.g., it was done in datalad-osf [@datalad-osf:zenodo].
Git-annex provides access to a wide range of external data storage resources via various protocols but cannot implement all idiosyncrasies of any individual data portal.
In particular, scientific data is frequently stored in compressed archives to reduce its storage demands, and/or on specialized servers, such as XNAT ([www.xnat.org](http://www.xnat.org)). Efficient scientific data processing therefore usually requires seamless access to a wide variety of different stores of scientific data.
To address this requirement, git-annex established a protocol [@git-annex:special_remotes_protocol] through which external tools can provide custom transport functionality transparently to the git-annex user.
This allowed DataLad and many other projects to facilitate access to an ever-growing collection of resources [@git-annex:special_remotes] and to overcome technological limitations (e.g., maximal file sizes, or file system inode limits).

**They require a layer above to establish a *distribution*.**
The DataLad project's initial goal was to provide data distributions <!-- this was "provide a data distribution". CM thinks: if "distribution" refers to a datalad dataset that can then be distributed, e.g. by sharing a link, then the word data distributions is almost a synonym for "datalad dataset", and it should read "data distribution". If the terms "data distribution" refers to the possibilty of distributing data to different location, it should read "data distribution". --> with unified access to already available public data archives in neuroscience, such as [crcns.org](http://crcns.org) and [openfmri.org](http://openfmri.org).
On their own, Git and git-annex do not provide user interfaces for searching across available repositories or for convenient manipulation of individual components of a data distribution. 
[datasets.datalad.org](http://datasets.datalad.org) became an example of such a data distribution curated by the DataLad team, which at the moment provides streamlined access to over 250 TBs of data across a wide range of projects and archives.
<!-- MIH thinks this needs a clarification of terms. If datasets.d.o is a distribution than datalad is "just a client tool" too. I think this is probably aimed at the nesting feature, and if so, we should use the term, because people can read about it in the handbook. This technical feature is then what is used to build a "unified data distribution" -->
<!-- YOH: good point, after all every distribution relies on client tools.  I have tried to address it above by removing the notion of "just a client tool".
 I do not think we can escape "metadata" completely -->
<!-- BEN adds to MIH: below we call ds.dl.org a testament of scalability, and
this is what I think it is. A showcase, not somehow a central or special part of
DataLad itself. Therefore I'd present it as the conclusion of what that
modularization allows for. Overall the "additional layer" the headline talks
about is not clear to me.-->
<!-- YOH: IMHO modularization is IMHO a very related but different aspect from "distribution"
 which is largely about bringing components from different resources together under a unified interface,
 with mechanisms to declare relationships (dependencies), often versioning, and then some notion of convenient URIs (package names vs urls).
 Any distribution indeed needs some level of modularization.
 As those are two aspects are very related, order could be swapped, but then we would need to re-work out "cross-referencing" -->

**Modularization is needed to scale.**
Research workflows impose additional demands for an efficient research data management (RDM) platform besides "version control" and "data transport".
Many research datasets contain millions of files, and that precludes placing such datasets in their entirety within a single Git/git-annex repository even if individual files are tiny in their size.
Such datasets should be partitioned into smaller subdatasets (e.g., a subdataset per each subject in the dataset comprising thousands of participants).
This modularization allows for not only scalable management, <!-- unclear how management of 10k small pieces becomes more scalable than one piece with 10k parts; YOH: just by virtue of being able to handle 10k * 10k files --> but also for the efficient reuse of a selected subset of datasets.
DataLad uses Git's submodule mechanism to unambiguously link (versions of) individual datasets into larger super-datasets, and further simplifies working with the resulting hierarchies of datasets with recursive operations across dataset boundaries.
<!-- BEN: There are more aspect of modularization than reuse and large-scale.
Most importantly, that's the notions of dependencies and a derivative
relationsship that can be expressed that way, I think. -->
<!-- YOH: well, there is "unambiguously link (versions of) " in above.  Could indeed be elaborated -->
With this, DataLad makes it trivial to operate on individual files deep in the hierarchy or entire sub-trees of datasets, providing a "mono-repo"-like user experience in datasets which are nested arbitrarily deep.
<!-- MIH: modularization is presented as #2, but it seems to be just #1 (nesting) described from a different angle -->
<!-- YOH: not sure what #2 here, since in above it is "reproducible execution" in "MIH thinks:".

As for #2 "reproducible execution" - I think we missed such subsection entirely, so I added it:
--> 
<!-- CM: Heading says: "Why Git and git-annex alone are not enough". This paragraph says "modulariyation is needed to scale" and  then describes how git-submodule supports modularizatoin (so, git is enough w.r.t. modulariztion!). Only then we describe what we add: i.e. a mono-repo-like experience, which is due to the recursive operations accross sub-modules. Should the title of the paragraph be something like: "Cross-module operations are required to scale"? Then a short sentence about "git supports nesting through the sub-module mechanism, we impleent recursive operation to use this mechanism to create a mono-repo experience. -->

**Annotation of changes is not "re-executable".**
A Git commit message is a freeform text intended to provide a human-readable description of introduced changes.
Changes themselves are typically represented by a patch (an exact difference between two versions) which could be applied to another version of the text file(s).
Such annotation is not sufficient to introduce changes by following the description, if they cannot be completely represented by such a patch.
<!-- YOH: may be strip above sentence away... I am just trying to lead somehow into "semantic" description of the change.
  E.g. that if author was very good with the description of change, some smart AI could have redone it following the description
  and not the patch.  The simplest analog could be "replaced word X with Y" where the patch would contain exact difference, but
  either will not be applicable or just would miss some Xs if applied to a vastly different version -->
<!-- CM: the sentence "Such annotation ... by such a patch." is difficult to understand. Does it mean: we cannot recreate changes, if the information is not in the commit message or the patch? How about the paragraph:

**Annotation of changes is not "re-executable".**
Unlike changes to text documents or source code, which are typically done "manually", manipulation of scientific data is most often performed by software. To support reproduction of such software-induced changes, DataLad adds a mechanism for capturing and re-performing that command invocation that lead to a specific change. To achieve this, Datalad uses git commit messages. A Git commit message is a freeform text intended to provide a human-readable description of the changes introduced with a commit (the changes themselves are represented by Git in an internal format, e.g. as a patch, that defines the exact difference between two versions of a file). DataLad uses the commit message to store a human- and machine-readable record of the command invocation which introduced the changes.
This allows for the data "change" to be re-executed to either verify that results reproduce, or to apply such a "change" to a completely different state.
 -->
Unlike changes to text documents or source code, which are typically done "manually", data manipulations are most often performed by software.
DataLad exploits this fact and enables automated annotation of changes which result from running an external command.
DataLad creates a commit message which does not only include a human-readable summary, but also a human- and machine-readable record of the command invocation which introduced the changes.
This allows for the data "change" to be re-executed to either verify that results reproduce, or to apply such a "change" to a completely different state. 

**Git and git-annex do not necessarily facilitate the best scientific workflow.**
Git and git-annex, being generic tools, come with rich interfaces and allow for a wide range of workflows.
DataLad strives to provide a higher level interface to more efficiently cover typical use cases encountered in the scientific practice than the direct invocation of individual Git and git-annex commands, and to encourage efficient computation and reproducible workflows.
To this end, DataLad is also accompanied by rich documentation [@datalad-handbook:zenodo] to guide a scientist of any technological competency level, and agnostic of the field of science.
<!-- key point thinks MIH: to some degree the handbook also "just" shows how to use git/git-annex to implement concrete processes that are of relevance for science. In some what "figuring out how to do it with git/git-annex is a major contribution, some of it implemented in code (simplified/alternative API), but otherwise written up in English -->

# Overview of the DataLad and its ecosystem

## DataLad core

The `datalad` Python package provides both a Python library and a command line tool which expose core DataLad functionality to fulfill a wide range of dRDM use cases for any domain.
DataLad (see \autoref{fig:one}) operates on DataLad datasets which are just Git (with optional git-annex for data) repositories with additional metadata and configuration.
 
![DataLad: a schematic overview of a dataset, datasets nesting, and selected DataLad commands for content and datasets management. DataLad Cheatsheet [@datalad-handbook:cheatsheet] provides a broader, yet still concise overview of these and other available commands. \label{fig:one}](figures/fig1.png)

Using Git's submodule mechanism, DataLad embraces and simplifies modular composition of smaller datasets into larger (super)datasets.
With this simple paradigm, DataLad fulfills the YODA principles for reproducible science [@yoda:myyoda] and facilitates efficient access, composition, scalability, reuse, sharing, and reproducibility of results  (see \autoref{fig:two}).

![DataLad datasets are reusable modular components, which could be nested to establish a complete provenance trail all the way from from a publication to the raw data. Various access schemes to datasets and data could be implemented.\label{fig:two}](figures/datalad-nesting-access.png)

As a testament of scalability, [datasets.datalad.org](http://datasets.datalad.org) provides a DataLad (super)dataset encapsulating thousands of datasets with unified access to over 250 TBs of primarily neural data from a wide range of hosting portals.

## Extensions

Like Git and git-annex, DataLad core not only provides a generic tool not encumbered by a specific field of science or domain, it also establishes the foundation to build specialized solutions on top of.
DataLad extensions mechanism allows to harmoniously extend DataLad's with a domain or technology specific functionality.
Some exemplar extensions include:

- [datalad-container](https://github.com/datalad/datalad-container) [@datalad-container:zenodo] to simplify management and use of Docker and Singularity containers typically containing complete computational environments;
- [datalad-crawler](https://github.com/datalad/datalad-crawler) [@datalad-crawler:zenodo] the functionality which initiated the DataLad project - to automate creation and updates of DataLad datasets from external resources;
- [datalad-neuroimaging](https://github.com/datalad/datalad-neuroimaging) [@datalad-neuroimaging:zenodo] to provide neuroimaging-specific procedures and metadata extractors;
- [datalad-osf](https://github.com/datalad/datalad-osf/) [@datalad-osf:zenodo] to collaborate using DataLad through the Open Science Framework (OSF).

The same mechanism of extensions is used for rapid development of new functionality to later be moved into the main DataLad codebase (e.g., [datalad-metalad](https://github.com/datalad/datalad-metalad/)).
The [datalad-extensions](https://github.com/datalad/datalad-extensions/) repository provides a list of extensions and continuous integration testing of their released versions against released and development versions of the DataLad core. 
The [datalad-extension-template](https://github.com/datalad/datalad-extension-template) template repository can be used for creating new DataLad extensions.

## External uses and integrations

[comment1]: <> (TODO: probably here cite some examples of scientific papers in the wild which used DataLad)

DataLad can be used as an independent tool as it used by scientists to access and/or manage data (see e.g. @Wittkuhn_2021, @datasets:LAAC-LSCP),
or as a core technology behind another tool or a larger platform.
[TemplateFlow](http://templateflow.github.io/) [@Ciric_2021] uses DataLad for the management of existing and orchestration of new submissions of neuroimaging templates.
[OpenNeuro](http://openneuro.org) uses DataLad for data logistics with data deposition to a public S3 bucket.
[CONP-PCNO](https://github.com/CONP-PCNO/) adopts aforementioned modular composition to deliver a rich collection of datasets with public or restricted access to data.
[ReproMan](http://reproman.repronim.org) integrates with DataLad to provide version control and data logistics.
[www.datalad.org/integrations.html](https://www.datalad.org/integrations.html) provides a more complete list of DataLad usage and integration with other projects, and @Hanke_2021 provides a systematic depiction of DataLad as a dRDM used by a number of projects. 


## Documentation

Developer-focused technical documentation at [docs.datalad.org](http://docs.datalad.org), with detailed descriptions of the command line and Python interfaces, is automatically generated from the DataLad core repository.
A comprehensive [handbook](http://handbook.datalad.org) [@datalad-handbook:zenodo] provides user-oriented documentation with an introduction to research data management, and numerous use case descriptions for novice and advanced users of all backgrounds [@datalad-handbook:use-cases].

## Installation

The handbook provides [installation instructions](http://handbook.datalad.org/r.html?install) for all major operating systems.
DataLad releases are distributed through [PyPI](https://pypi.org/project/datalad), [Debian](https://tracker.debian.org/pkg/datalad), [NeuroDebian](http://neuro.debian.net/pkgs/datalad.html), [brew](https://formulae.brew.sh/formula/datalad), and [conda-forge](https://anaconda.org/conda-forge/datalad).
The [datalad-installer](https://github.com/datalad/datalad-installer) (also available from PyPI) streamlines the installation of DataLad and its dependencies, in particular git-annex, across a range of deployment scenarios, such as continuous integration systems, or high-performance computing (HPC) environments.

## Development

DataLad has been developed openly in a public repository ([github.com/datalad/datalad](https://github.com/datalad/datalad)) since its inception in 2013.
At the time of this publication, the repository amassed over 13.5k commits, 2.5k merged PRs, and 2.3k closed (+700 open) issues from over 30 contributors.
Issue tracker, labels, milestones, and pull requests (from personal forks) are used to coordinate development.
DataLad heavily relies on the versatility and stability of the underlying core tools---Git and git-annex.
To avoid reimplementing the wheel and to benefit the git-annex user community at large, many aspects of the desired functionality are and have been implemented directly in git-annex through collaboration with the git-annex developer Joey Hess [@git-annex:projects-datalad].
To guarantee robust operation across various deployments, DataLad heavily utilizes continuous integration platforms (Appveyor, GitHub actions, and Travis CI) for testing DataLad core, building and testing git-annex (in a dedicated [github.com/datalad/git-annex](https://github.com/datalad/git-annex)), and integration testing 
with DataLad extensions ([datalad-extensions](https://github.com/datalad/datalad-extensions/)).

## Contributions

DataLad is released under [DFSG](https://en.wikipedia.org/wiki/Debian_Free_Software_Guidelines)- and [OSI](https://opensource.org/osd)-compliant MIT/Expat license, and license terms for reused in the code-base components are provided in the [COPYING](https://github.com/datalad/datalad/blob/master/COPYING) file.
[CONTRIBUTING.md](https://github.com/datalad/datalad/blob/master/CONTRIBUTING.md) file shipped within DataLad's source repository provides guidelines for submitting contributions.

[comment2]: <> (# Author Contributions: if desired/needed -- or drop altogether.)

# Conflicts of interest

There are no conflicts to declare.

# Acknowledgements

DataLad development was facilitated by a senior adviser Dr. James V. Haxby (Dartmouth College).
We express our gratitude to Joey Hess for the development and maintenance of git-annex, and for years of productive collaboration with the DataLad team.
We would like to extend our gratitude to 
Joey Zhou,
Matteo Visconti di Oleggio Castello,
John T. Wodder II,
Satya Ortiz-Gagné,
Jörg Stadler,
Andrew Connolly,
John Lee,
Nolan Nichols,
Elizabeth DuPre,
Cécile Madjar,
Gergana Alteva,
Timo Dickscheid,
Alex Waite,
[TODOADD: notable contributors]
for notable contributions to the codebase, bug reports, recommendations, and promotion of DataLad.

DataLad development was made possible thanks to support by 
NSF [1429999](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1429999), 
[1912266](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1912266) 
(PI: Halchenko) and BMBF 01GQ1411 and 01GQ1905 (PI: Hanke) 
through [CRCNS](https://www.nsf.gov/funding/pgm_summ.jsp?pims_id=5147) program.
It received significant contributions from ReproNim [1P41EB019936-01A1](https://projectreporter.nih.gov/project_info_details.cfm?aid=8999833&map=y) and DANDI [5R24MH117295-02](https://projectreporter.nih.gov/project_info_description.cfm?aid=9981835&icde=53349087) NIH projects.
It also received contributions from the Canadian Open Neuroscience Platform and the NeuroHub projects thanks in part to funding from a Brain Canada Platform Support Grant Competition Award in addition to funds and in-kind support from sponsor organizations, and from the Canada First Research Excellence Fund, awarded through the Healthy Brains, Healthy Lives initiative at McGill University, and the Brain Canada Foundation with support from Health Canada.
This development was supported by the European Regional Development Fund (Project: Center for Behavioral Brain Sciences Magdeburg, Imaging Platform), the European Union’s Horizon 2020 research and innovation programme under grant agreements [Human Brain Project (SGA3, H2020-EU.3.1.5.3, grant no. 945539)](https://cordis.europa.eu/project/id/945539), and [Virtual Brain Cloud (H2020-EU.3.1.5.3, grant no. 826421)](https://cordis.europa.eu/project/id/826421), the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation) under grants [SFB 1451 (431549029)](https://gepris.dfg.de/gepris/projekt/431549029) and [IRTG2150 (269953372)](https://gepris.dfg.de/gepris/projekt/269953372).


# References
