### Updates
This template was last updated in Fall 2016.

### Introduction
This is a basic template for an NPRP final report.  It tries to mimic the
basic style of the Qatar National Research Fund's NPRP proposal template using Latex.  

This is NOT a template for the NPRP proposals.  For that check [here](https://github.com/rriley/nprp-template).

### Disclaimer
This template is *not* official nor sanctioned by QNRF.  I make no guarantee
that they will accept a report that uses it.  

### Instructions
* Use this as the base for your report.

* When you compile it, make SURE you are using the letter paper size.  
  * Using standard Latex I do the following:
    1. Run latex nprp.tex
    2. Run dvips -t letter -Ppdf nprp.dvi
    3. Run ps2pdf nprp.ps
  * Using pdflatex, it just works on my system, but this is potentially very system dependent.
  * The paper size might still be wrong, so you'll need to verify it in a PDF viewer.  The truth is, getting paper size correct in Latex is sometimes painful.  Pray that it works for you.
