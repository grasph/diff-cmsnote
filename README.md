diff-cmsnote
============

Utility to produce a document showing differences between two versions a latex document based on the CMS edition 'tdt' tool, The utility is based on diffpdf.


Installation
------------

The application is a bash script, which was developed and tested on a linux system.

Required software on the system:
   * CMS document edition "tdr" tool
   * pdfdiff
   * latex suite and pdflatex
   * bash and sed commands

The three files diff-cmsnote, diff-preamble, and  diff-preprocess must be copied in the same directory.

Usage:
-----

diff-cmsnote [-k] A B ID

  *  -k: keep tempory files
  *  A: -r REV_A or -f DIR_A
  *  B: -r REV_B or -f DIR_B
  *  ID: note or paper ID, e.g. SMP-2015-016

