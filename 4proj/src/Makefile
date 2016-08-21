#####
#Soubor: makefile
#Autor: Jan Wrona, xwrona00@stud.fit.vutbr.cz
#Datum: 15.04.2012
#Projekt: Projekt c. 4 pro predmet ITY
#####

NAME=proj4

latex: $(NAME).tex
	latex $(NAME).tex
	bibtex $(NAME).aux
	latex $(NAME).tex
	latex $(NAME).tex
	dvips $(NAME).dvi
	ps2pdf -sPAPERSIZE=a4 $(NAME).ps

vlna: $(NAME).tex
	vlna -l -m -n $(NAME).tex
clean:
	rm $(NAME).dvi  $(NAME).ps $(NAME).aux $(NAME).log $(NAME).blg $(NAME).bbl
