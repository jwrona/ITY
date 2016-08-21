#####
#Soubor: makefile
#Autor: Jan Wrona, xwrona00@stud.fit.vutbr.cz
#Datum: 13.02.2012
#Projekt: Projekt c. 2 pro predmet ITY
#####

latex: proj2.tex
	latex proj2.tex
	latex proj2.tex
	dvips -t a4 proj2.dvi
	ps2pdf proj2.ps

vlna: proj2.tex
	vlna -l -m -n proj2.tex
clean:
	rm proj2.dvi proj2.ps proj2.aux proj2.log
