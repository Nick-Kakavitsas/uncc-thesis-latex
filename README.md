# uncc-thesis-latex
## General information
This repository provides LaTeX class (.cls) and style (.sty) files that facilitate specifying Masters and Doctoral thesis documents that conform to the specifications of the UNC Charlotte graduate school.
<pre>
Files:
makefile   		Compiles the msthesis.pdf and phdthesis.pdf documents using 'make'.
			To use it, type 'make' in this folder from a linux shell/terminal.

unccspecs.sty		A UNC Charlotte (UNCC) thesis LaTeX style (.sty) file for use with LaTeX to help with formatting.
UNCC-thesis.cls		A UNC Charlotte (UNCC) thesis LaTeX class (.cls) file for use with LaTeX to help with formatting.
UNCC-thesis.layout	A UNC Charlotte (UNCC) thesis LaTeX layout (.layout) file for use with LyX for writing a thesis.
msthesis.lyx		An example of a Masters Thesis document which may be used as a template document in the LyX editor.
msthesis.tex		An example of a Masters Thesis document which may be used as a template document in a LaTeX editor.
phdthesis.lyx		An example of a Doctoral Thesis document which may be used as a template document in the LyX editor.
phdthesis.tex		An example of a Doctoral Thesis document which may be used as a template document in a LaTeX editor.
reference_db.bib	A sample BiBTeX database of references which has one entry for use by the example documents.
figs/TransVsKLLine.eps 	A sample encapsulated postscript (.eps) figure for use by the example documents.
figs/TransVsKLLine.pdf 	A sample portable document format (.pdf) figure for use by the example documents.
</pre>

## Instructions for overleaf
Here are some brief instructions on how to use these files in overleaf
1. Download the repository as a zip file
2. Upload the zip file to overleaf as a new project
3. If you're a masters student, delete the phd files, or vice versa for phd students
4. Update the document accordingly
	- Add packages that you might want to the top of the .tex file applicable to you
	- Maybe change the .tex file applicable to you to "main.tex"
	- If this is going to be for your dissertation proposal, use \doctype{dissertation proposal}
	- Update your title page information using \title in your main .tex file, with the other related commands -- \author, \degree, \major, \publicationyear, \advisor, \committeeMember
	- Update your abstract between the \begin{abstract} and \end{abstract} commands
	- Update your dedication between the \begin{dedication} and \end{dedication} commands
	- Update your acknowledgements between the \begin{acknowledgements} and \end{acknowledgements} commands
	- Update your preface between the \begin{preface} and \end{preface} commands
	- Update your acknowledgements between the \begin{acknowledgements} and \end{acknowledgements} commands
	-\tableofcontents{}, \listoftables, and \listoffigures all update automatically based on the section headers, tables, and figures in your document, respectively
	- Organize the rest of the document (sections, subsections, tables, etc) as you would in your discipline
	

