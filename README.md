# Technical Reference

This is the common technical reference developed by the EURISE Network.

The documents contained in this repository are intended to form basic guidelines and references
for development and maintenance of infrastructure services for the participating infrastructures and beyond.
They rely heavily on work by the community and in particular
[CESSDA ERIC](https://www.cessda.eu/), [CLARIAH-NL](https://www.clariah.nl/), [DARIAH-DE](https://de.dariah.eu/) as well as the
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
# build all files and put them in the right place
make clean html latexpdf epub
cp _build/latex/TechnicalReference.pdf _build/epub/TechnicalReference.epub _build/html

# start fresh
git branch -D gh-pages
# add the new files to git to work with them
git add _build/html
git commit -m "Deploy GH Pages"
# take the files out into a new branch
git subtree split --branch gh-pages --prefix _build/html/
# force the new files to the github page
git push origin gh-pages --force
# return to the previous state
git reset --hard HEAD~1
```


## Development

The Technical Reference is still in early development.


