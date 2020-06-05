# Technical Reference

[![Documentation Status](https://readthedocs.org/projects/technical-reference/badge/?version=latest)](https://technical-reference.readthedocs.io/en/latest/?badge=latest)

This is the common Technical Reference developed by the [EURISE Network](https://eurise-network.github.io/), a cooperation of
[CESSDA ERIC](https://www.cessda.eu/), [CLARIN ERIC](https://www.clarin.eu/) and [DARIAH ERIC](https://www.dariah.eu/).

The [Technical Reference](https://technical-reference.readthedocs.io/en/latest/) is available online and intended to form a set of basic guidelines
and references to inform development and maintenance of infrastructure services for the participating infrastructures and beyond.

## This reference's particular purpose

The EURISE Network Technical Reference, is a collection of guidelines and how-tos, mainly aimed at developers contributing to the participating infrastructures.
It serves as a combined introduction to many aspects of software engineering, while being neutral with respect to particular choices.
This ensures the largest possible intersection of recommendations, while allowing the partners to implement their own lightweight specifications on top.
This purpose sets it apart from many similar guides.

In creating the documents, existing work from the community has been taken into account.
In particular, work carried out by [CLARIAH-NL](https://www.clariah.nl/) as well as the
[Netherlands eScience Center](https://esciencecenter.nl/) and the [UK Software Sustainability Institute](https://www.software.ac.uk)
have been used, heavily relying on the [Netherlands eScience Center Guide](https://guide.esciencecenter.nl/) and the
[CLARIAH Software Quality Guidelines](https://github.com/CLARIAH/software-quality-guidelines).


## Working with the TR

The documents are compiled with Sphinx and automatically published on [Read the Docs](https://technical-reference.readthedocs.io/en/latest/) on commit.
Specific releases are available on Read the Docs to be used for implementations.

To work locally, install everything to an venv
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Compile with
```
make clean
make html
make latexpdf
```


## Development

The Technical Reference is still in early development and maintained by volunteers from the infrastructures involved.
Contributions are welcome, see [CONTRIBUTING.md](CONTRIBUTING.md), contributors are listed in [AUTHORS.md](AUTHORS.md).

This work was originally started as part of the “DESIR – DARIAH ERIC Sustainability Refined” project for [DARIAH](https://www.dariah.eu/),
receiving funding from the European Commission under grant agreement 731081 and has been transferred to the EURISE Network for future maintenance.

