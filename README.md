# PhD-thesis
The source for my PhD thesis (conducted at Plymouth University, U.K.) titled 'The Impact of Robot Tutor Social Behaviour on Children'. Please note that the copyright for many of the images is held by various publishers. Nothing should be published without consent from myself, or the relevant publisher (notes in the text about copyright where relevant).

Basic build steps:

(install glossaries package to your TeX distribution)
Run latex against 00_thesis.tex
Build the glossary (makeglossary %) against 00_thesis.tex
Build the document as usual (PDFLaTeX, BibTeX, PDFLaTeX, PDFLaTeX)
Whenever you modify the glossary make sure to rebuild it as in step 3, otherwise you can continue to just build as usual using PDFLaTeX and BibTeX.
