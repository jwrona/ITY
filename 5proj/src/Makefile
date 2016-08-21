#####
#Soubor: makefile
#Autor: Jan Wrona, xwrona00@stud.fit.vutbr.cz
#Datum: 28.04.2012
#Projekt: Projekt c. 5 pro predmet ITY
#####

NAME=proj5

latex: $(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex
	dvips $(NAME).dvi
	ps2pdf $(NAME).ps

vlna: $(NAME).tex
	vlna -l -m -n $(NAME).tex
clean:
	rm $(NAME).dvi  $(NAME).ps $(NAME).aux $(NAME).log $(NAME).out
