all:pdf


pdf:
	latexmk -pdf Traduko

dvi:
	latexmk Traduko

room:
	rm -rf *.toc *.log *.aux *.out *.bbl *.blg *.fdb_latexmk *.fls

clean: room
	rm -f Traduko.pdf
	rm -f Traduko.dvi 
