template.pdf: template.dvi
	dvipdfmx template.dvi

template.dvi: *.tex
	platex template.tex
	#mendex template
	#pbibtex template
	platex template.tex
	#platex template.tex

clean:
	rm *.toc *.aux *.snm *.pdf *.dvi *.out *.log *.nav
