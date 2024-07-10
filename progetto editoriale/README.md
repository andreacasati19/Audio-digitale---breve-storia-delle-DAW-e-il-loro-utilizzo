# Contenuto del repository

Il seguente repository contiene i documenti che costituiscono un ebook il cui titolo è "Audio digitale - breve storia delle DAW e il loro utilizzo".
I documenti sono i seguenti:

- content.tex: contenuto vero e proprio del libro scritto in formato LaTeX
- content.md: contenuto vero e proprio del libro scritto in formato Markdown
- metadata.xml: metadati in formato xml scritti in formato Dublin Core
- stylesheet.css: foglio di stile per l'ebook da creare
- bibliografia.bib: bibliografia del testo in formato BibTeX
- IEEE.csl: stile per le citazioni e bibliografia

Per generare l'ebook finale in formato ePub è necessario utilizzare il software di conversione di formato [Pandoc](https://pandoc.org/).

Da riga di comando digitare: ```pandoc content.tex -o Audio\ digitale\ -\ breve\ storia\ delle\ DAW\ e\ il\ loro\ utilizzo.epub --citeproc --bibliography=bibliografia.bib --number-section --toc=true --css stylesheet.css --csl=IEEE.csl --epub-metadata=metadata.xml```
