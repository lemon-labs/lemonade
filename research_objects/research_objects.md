
!!! Success "Learning Objectives"
        
        After this lesson, you should be able to:

        *  Describe tools and approaches to creating research objects
        *  Describe best practices for reproducible research
        *  Understand benefits of establishing version control 

## Research Objects

Broadly, Research Objects (RO) are defined as a method for identification, aggregation, and exchange of scholarly information.

[Turing Way Guide to Reproducible Research](https://the-turing-way.netlify.app/reproducible-research/reproducible-research.html){target=_blank}

### Governance Documents

??? Quote "Definition"

    Project Governance is the set of rules, procedures and policies that determine how projects are managed and overseen.

    "The set of policies, regulations, functions, processes, and procedures and responsibilities that define the establishment, management and control of projects, programmes or portfolios." - [APM (2012)](https://www.academia.edu/44132624/APM_BODY_OF_KNOWLEDGE){target=_blank}, [open.edu](https://www.open.edu/openlearn/mod/oucontent/view.php?id=27294&printable=1){target=_blank}

    [:material-wikipedia: Wikipedia Definition](https://en.wikipedia.org/wiki/Project_governance){target=_blank}

No matter how small, i.e., even single person-run projects, a good Project Governance structure can help keep work on track and headed toward a timely finish.

Establishing a project governance document at the onset of a project is a good way of setting boundaries, roles and responsibilities, pre-registration about what deliverables are expected, and what the consequences will be for breaking trust.

??? Tip "Example Governance Documents"

    [Munoz-Torres et al. 2020](https://zenodo.org/record/3839120#.YyUJA-zMLzd){target=_blank}


### Documentation


This website is rendered using [:simple-github: GitHub Pages](https://pages.github.com/){target=_blank} using [:simple-markdown: MkDocs](https://www.mkdocs.org/){target=_blank} and the [Material](https://squidfunk.github.io/mkdocs-material/){target=_blank} theme for MkDocs. 

Other popular website generators for GitHub Pages are [:simple-jekyll: Jekyll Theme](https://jekyllrb.com/){target=_blank} or [:simple-bootstrap: Bootstrap.js](https://getbootstrap.com/){target=_blank}.

[:simple-readthedocs: ReadTheDocs.org](https://readthedocs.org/){target=_blank} has become a popular tool for developing web-based documentation. Think of RTD as "Continuous Documentation".

[:material-book-arrow-down: Bookdown](https://bookdown.org/){target=_blank} is an open-source R package that facilitates writing books and long-form articles/reports with R Markdown.

[:simple-r: Quarto](https://quarto.org/){target=_blank} is an open-source scientific and technical publishing system built on Pandoc

[:simple-confluence: Confluence Wikis (CyVerse)](https://wiki.cyverse.org){target=_blank} are another tool
for documenting your workflow.

!!! Quote "Things to remember about Documentation"

    - Documentation should be written in such a way that people who did not write the documentation can read and then use or read and then teach others in the applications of the material.

    - Documentation is best treated as a living document, but version control is necessary to maintain it

    - Technology changes over time, expect to refresh documentation every 3-5 years as your projects age and progress.

*:simple-github: GitHub Pages*

-   You can pull templates from other GitHub users for your website,
    e.g. [:simple-jekyll: Jekyll themes](http://themes.jekyllrc.org/){target=_blank}
-   GitHub pages are free, fast, and easy to build, but limited in use
    of subdomain or URLs.

*:simple-readthedocs: ReadTheDocs*

-   publishing websites via
    [ReadTheDocs.com](https://readthedocs.com/dashboard/){target=_blank} costs money.
-   You can work in an offline state, where you develop the materials
    and publish them to your localhost using
    [Sphinx](https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html){target=_blank}
-   You can work on a website template in a GitHub repository, and
    pushes are updated in near real time using ReadTheDocs.com.

*:simple-markdown: Material MkDocs*

- publish via GitHub Actions
- Uses open source Material or ReadTheDocs Themes

*:material-book-arrow-down: Bookdown*

-   Bookdown websites can be hosted by [RStudio
    Connect](https://www.rstudio.com/products/connect/){target=_blank}
-   You can publish a Bookdown website using [Github
    Pages](https://github.blog/2016-08-17-simpler-github-pages-publishing/){target=_blank}

*:simple-r: Quarto*

-   [Build a website](https://quarto.org/docs/websites/) using Quarto's template builder
-   [Build with Github Pages](https://quarto.org/docs/publishing/github-pages.html)

*:simple-jupyter: JupyterBook*

-   [Based on Project Jupyter](https://jupyterbook.org/en/stable/start/overview.html){target=_blank} `ipynb` and MarkDown
-   Uses `conda` package management

*:simple-git: GitBook*

- [GitBook](https://docs.gitbook.com/){target=_blank} websites use MarkDown syntax
- Free for open source projects, paid plans are available


### GitHub

[:simple-github: Github Actions](https://github.com/actions){target=_blank}

[:octicons-codespaces-24: CodeSpaces](https://github.com/codespaces){target=_blank}

### Containers

[:simple-docker: Docker](https://docker.com){target=_blank}

[:simple-containerd: containerd](https://containerd.io/){target=_blank}

### Orchestration

[:simple-kubernetes: Kubernetes](https://kubernetes.io/){target=_blank}

[simple-jupyterhub JupyterHub](https://jupyter.org/hub){target=_blank}

### Digital Object Identifier

[Zenodo](https://zenodo.org/){target=_blank}

[DataCite](https://datacite.org/){target=_blank}

# Hands-On

1. Log into GitHub

2. Import 

# Self-Assessment

??? Question "Research Objects must include all components of research: governance document, manuals, documentation, research papers, analysis code, data, software containers"

    ??? Failure "Answer"

        While a Research Object *may* include the entire kitchen sink from a research project, it does NOT always contain all of these things.

        Fundamentally, a RO should contain enough information and detail to reproduce a scientific study from its linked or self-contained parts. 

        Components like large datasets may not be a part of the RO, but the code or analysis scripts should have the ability to connect to or stream those data.