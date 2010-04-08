
# neo-article

## Purpose

This is the draft for an article about the [Neo keyboard layout](http://neo-layout.org/) for [Die TeXnische Komödie](http://www.dante.de/DTK.html), written in the german language.

The main author is [Arno Trautmann](http://github.com/alt/neo-article).

## How to Compile

To compile, use the makefile:

    latex --shell-escape makefile

Insert 1 if you want to compile all files or 2 if you only want to compile the helper files (`ebene*.tex` and `neo*.tex`)

The option `--shell-escape` is needed here! (or compile all of the ‌`neo*.tex`, `ebene*.tex`, `neo+xelatex.tex` `neo+xelatex.aux` by hand)

If you want to compile by hand, you have to run `xelatex` on the `neo*.tex` and `ebene*.tex` first.

After that, the article can be compiled with `pdflatex neo+xelatex.tex`. For bibliography, you must complement `bibtex neo+xelatex` and recompile the article with `pdflatex neo+xelatex.tex`. (the `.bib` will be generated automatically in the first `neo+xelatex` run.)