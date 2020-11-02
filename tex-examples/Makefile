main.pdf: main.tex mybib.bib  
	pdflatex main
	bibtex main
	pdflatex main
	pdflatex main

clean:  
	rm -rf *.out *.aux *.log *.bbl *.blg *.fls *.fdb_latexmk *.synctex.gz || true