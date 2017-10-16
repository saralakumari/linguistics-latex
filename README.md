# About linguistics-latex

This repository holds examples of LaTeX code for linguists to reuse. Pull requests are welcome. Each .tex file should ideally be a minimal working example, that is, a fully compilable document with all and only the required packages to accomplish the task at hand. Unicode source files are preferred (XeTeX).

## Contents

1. [UNESCO language vitality tables](UNESCO_Vitality_Tables.tex)

These are for writing language vitality assessments according to UNESCO's 2003 guidelines on [Language Vitality and Endangerment](http://www.unesco.org/new/en/culture/themes/endangered-languages/language-vitality/). 
The [PDF document from UNESCO](https://ich.unesco.org/doc/src/00120-EN.pdf) provides nine "language vitality scales" in table format. 
The .tex file here contains the exact wording of the nine tables, English version, transferred into LaTeX format. 
Its most useful feature is perhaps the cell widths, which are adjusted to distribute space efficiently despite widely differing numbers of characters in each cell, and which will adapt dynamically to your font size, page size, margins, etc. 
The cell width feature requires the `tabu` package. 

## Setup notes

I use XeLaTeX and recommend other linguists do too. 
Even without XeLaTex, some of the examples may still be useful. 
You'll have to edit the preambles to remove the packages {xltxtra} and {fontspec}; any font-setting commands; and possibly other XeLaTeX-requiring packages.

The rest of my setup:

- MikTeX distribution
- Windows 8.1
- Unicode source files compiled with `xelatex`and `bibtex`
- No special LaTeX editor, I use a general text editor and compile on the command line
