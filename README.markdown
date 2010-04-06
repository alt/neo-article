
# neo-article

## Purpose

This is the draft for an article about the [Neo keyboard layout](http://neo-layout.org/) for [Die TeXnische Komödie](http://www.dante.de/DTK.html), written in the german language.

The main author is [Arno Trautmann](http://github.com/alt/neo-article).

## How to Compile

At first, one has to compile the various images (‌‌`neo*.tex`, `ebene*.tex`) with XeTeX: `xelatex neo12.tex‌`, …

After that, the article itself can be compiled with `pdflatex neo+xelatex.tex` – and if you also want to get the bibliography, you must complement ‌‌‌`bibtex neo+xelatex.aux` and recompile the article `pdflatex neo+xelatex.tex`.
