# Technical Reference

[![Documentation Status](https://readthedocs.org/projects/technical-reference/badge/?version=latest)](https://technical-reference.readthedocs.io/en/latest/?badge=latest)

This is the common technical reference developed by the EURISE Network.

The documents contained in this repository are intended to form basic guidelines and references
for development and maintenance of infrastructure services for the participating infrastructures and beyond.
They rely heavily on work by the community and in particular
[CESSDA ERIC](https://www.cessda.eu/), [CLARIAH-NL](https://www.clariah.nl/), [DARIAH-DE](https://de.dariah.eu/) as well as the
[Netherlands eScience Center](https://esciencecenter.nl/) and the [UK Software Sustainability Institute](https://www.software.ac.uk).

## Working with the TR

The documents are compiled with Sphinx and automatically published on [Read the Docs](https://technical-reference.readthedocs.io/en/latest/) on commit.

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

The Technical Reference is still in early development.


