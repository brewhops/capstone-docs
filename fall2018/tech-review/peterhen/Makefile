tex = henry_peterson_tech_review_final

default:
	pdflatex $(tex).tex
	bibtex   $(tex)
	pdflatex $(tex).tex
	pdflatex $(tex).tex

clean:
	rm -rf *.aux *.log *.out *.toc *.bbl *.dvi *.blg *.bak
	clear
