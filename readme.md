# How to convert LaTeX to TEI

* check the pdf `pdflatex main.pdf`
* run latexml `latexml main.tex --output=main.xml`
* run latexmlpost `latexmlpost main.xml --destination=main.tei --format=tei`
