# University of Western Ontario LaTeX Thesis Template

This is a modified version of the original University of Western Ontario (UWO) LaTeX thesis template, with Justin Veenstra the original author. I post it here as a couple colleagues (myself included) have had trouble compiling the original template.

You can use [`natbib`](https://journals.aas.org/authors/aastex.html) to manage citations. By default, this template follows the bibliography style of [The Astrophysical Journal](http://iopscience.iop.org/journal/0004-637X) (see also [the AASTeX package](https://journals.aas.org/authors/aastex/aasguide.html)).

To compile the example, run

1. `pdflatex ms.tex`
2. `bibtex intro` (if you place your references in a \*.bib file)
3. `bibtex appdx` (if you place your references in a \*.bib file)
4. `pdflatex ms.tex`

You can populate the template with chapters and appendices, with each as an independent TeX file.

For more info of the original template, check [UWO thesis formatting page](http://www.grad.uwo.ca/current_students/thesis/formatting.html).

Hope it helps!

Quan-Zhi Ye
