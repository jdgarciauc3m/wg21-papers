FINAL_DIR=final

LATEXMK=latexmk -pdf -silent -file-line-error -halt-on-error -outdir=$(FINAL_DIR) 

dis26.pdf:	*.tex config/*.tex
	$(LATEXMK) -jobname=dis26 slides.tex
