# ebooks
LaTeX source files for VividCortex's ebooks.

This isn't intended to be a distribution mechanism for the ebooks---the final versions will be hosted on VividCortex's website. But it's a good place to collaborate on making them, getting external reviews, etc.

The directory organization convention is that each ebook will have a `.tex` file in the top level,
and a directory containing figures, reference material, etc.

You'll need the Roboto font and xelatex to build the PDFs, due to the custom fonts. You can't use the latex or pdflatex commands.

A quickstart for Mac users for installing LaTeX:

* Install BasicTex
* Install Tex Live Utility from GitHub
* Open a terminal and clone this repository, then `cd` into it and type `xelatex scalability.tex` or any other ebook name
* Install packages using Tex Live Utility, as needed
  * If you get an error like `! LaTeX Error: File 'footmisc.sty' not found` then install footmisc with Tex Live Utility
  * The titletoc package is part of titlesec
