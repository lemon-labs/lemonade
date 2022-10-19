
!!! Success "Learning Objectives"
        
        After this lesson, you should be able to:

        *  Describe tools and approaches to creating research objects
        *  Describe best practices for reproducible research
        *  Understand benefits of establishing version control 

## Research Objects

Broadly, Research Objects (RO) are defined as a method for identification, aggregation, and exchange of scholarly information.

[Turing Way Guide to Reproducible Research](https://the-turing-way.netlify.app/reproducible-research/reproducible-research.html){target=_blank}

## GitHub

[:simple-github: Github Actions](https://github.com/actions){target=_blank}

[:octicons-codespaces-24: CodeSpaces](https://github.com/codespaces){target=_blank}

## Containers

[:simple-docker: Docker](https://docker.com){target=_blank}

[:simple-contaierd: containerd](https://containerd.io/){target=_blank}

## Orchestration

[:simple-kubernetes: Kubernetes](https://kubernetes.io/){target=_blank}

[simple-jupyterhub JupyterHub](https://jupyter.org/hub){target=_blank}

## Digital Object Identifier

[Zenodo](https://zenodo.org/){target=_blank}

[DataCite](https://datacite.org/){target=_blank}

# Hands-On



# Self-Assessment

??? Question "Research Objects must include all components of research: governance document, manuals, documentation, research papers, analysis code, data, software containers"

    ??? Failure "Answers"

        While a Research Object (RO) *may* include the entire kitchen sink from a research project, it does NOT always contain all of these things.

        Fundamentally, a RO should contain enough information and detail to reproduce a scientific study from its linked or self-contained parts. 

        Components like large datasets may not be a part of the RO, but the code or analysis scripts should have the ability to connect to or stream those data.