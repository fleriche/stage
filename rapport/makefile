
all : rapport cleanrep

rapport :
	rubber -d rapport.tex
	mv rapport.pdf pdf

# Clean commands
clean : cleanpdf cleanrep 

cleanpdf :
	rm -f *.pdf

# Nettoyage du répertoire
cleanrep:
	rm -f *.aux *.cb *.cb2 *.log *.toc *.out *.lot *.lof *.maf *.mtc *.glo *.glsdefs *.ist *.ilg *.ind *.mtc0 *.synctex.gz
