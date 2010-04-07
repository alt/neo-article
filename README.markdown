
# neo-article

## Purpose

This is the draft for an article about the [Neo keyboard layout](http://neo-layout.org/) for [Die TeXnische Komödie](http://www.dante.de/DTK.html), written in the german language.

The main author is [Arno Trautmann](http://github.com/alt/neo-article).

## How to Compile

To compile all the images, use the makefile:

LaTeX --shell-escape makefile

Shell-escape needed here! (or compile all of the neo*.tex, ebene*.tex by hand)

After that, the article can be compiled with `pdflatex neo+xelatex.tex`. For bibliography, you must complement ‌‌‌`bibtex neo+xelatex` and recompile the article `pdflatex neo+xelatex.tex`. (bib will be generated automatically in the first neo+xelatex run.)
