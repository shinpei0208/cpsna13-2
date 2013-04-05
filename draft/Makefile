all:
	latex draft.tex
	bibtex draft
	latex draft.tex
	latex draft.tex
	dvipdfmx draft.dvi

clean:
	rm -fr *~ *.log *.aux *.bbl *.blg *.dvi
