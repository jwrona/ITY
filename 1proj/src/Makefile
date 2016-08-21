#####
#Soubor: makefile
#Autor: Jan Wrona, xwrona00@stud.fit.vutbr.cz
#Datum: 28.02.2012
#Projekt: Projekt c. 1 pro predmet ITY
#####

latex: proj1.tex
	latex proj1.tex
	latex proj1.tex
	dvips proj1.dvi
	ps2pdf proj1.ps

vlna: proj1.tex
	vlna -l -m -n proj1.tex
clean:
	rm proj1.dvi proj1.ps proj1.aux proj1.log
