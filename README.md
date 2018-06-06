# DARIAH Technical Reference

This is the technical reference for the DARIAH Infrastructure.
The documents contained in this repository are intended to form basic guidelines and references
for development and maintenance of infrastructure services with DARIAH and beyond.
They rely heavily on work by the community and in particular
[CESSDA Eric](https://www.cessda.eu/), [CLARIAH-NL](https://www.clariah.nl/), [DARIAH-DE](https://de.dariah.eu/) as well as the
[Netherlands eScience Center](https://esciencecenter.nl/) and the [UK Software Sustainability Institute](https://www.software.ac.uk).

## Working with the TR

The documents are compiled with Sphinx, install everything to an venv
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


To publish to the GitHub Pages, make sure to commit your work and than do
```
make clean html latexpdf epub
cp _build/latex/TechnicalReference.pdf _build/epub/TechnicalReference.epub _build/html

git branch -D gh-pages
git add _build/html
git commit -m "Deploy GH Pages"
git subtree split --branch gh-pages --prefix _build/html/
git push origin gh-pages --force
git reset --hard HEAD~1
```


## Development

The Technical Reference is still in early development.

Work on these documents is carried out within “DESIR – DARIAH ERIC Sustainability Refined” for [DARIAH ERIC](https://www.dariah.eu/).
This project has received funding from the European Union’s Horizon 2020
research and innovation program under grant agreement 731081.
