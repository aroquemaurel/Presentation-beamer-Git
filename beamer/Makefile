.PHONY: clean withversion run

INPUT=main.tex
OUTPUT=main.pdf
DEP=$(wildcard *.sty *.jpg *.png *.eps)

$(OUTPUT): $(INPUT) $(DEP)
	pdflatex $(INPUT) 

clean:
	rm -f $(OUTPUT)
