=========================
My thesis
=========================

This is my thesis.

* Chukars
* Microraptor model tests
* Comparative study of more model tests
* Other factors

To compile
==========
1.  Run pdfLaTeX on main.tex
2.  Run bibtex on main.tex
3.  Run pdfLaTeX twice. 
4.  Run make index on main.tex
5.  Run pdfLaTeX twice. 

All references for a particular chapter must be added to the main bibliography file, now in thesis.bib. 

Revision control and syncing using Mercurial
--------------------------------------------
1. After making edits, commit your changes using:  hg commit -m "Enter a useful comment here."
2. To push your changes to the repository, use: hg push
3. To pull changes from the repository, use: hg pull, then hg update
4. To clone the repository using ssh, for example:
hg clone ssh:\\hg@bitbucket.org\devangel77b\evangelista-thesis-new

Revision control block on top of tex file
-----------------------------------------
Do not edit this.  After committing changes (hg commit -m "Made some changes"), update the block using the following:
1.  hg kwshrink
2.  hg kwexpand

Authors should have their usernames registered in main.tex




Thanks to
==============

* My family
* My advisor, Robert Dudley
* My birds
