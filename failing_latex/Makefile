TEX = pdflatex

.PHONY: all view

all : helloworld.pdf

helloworld.pdf : helloworld.tex
	$(TEX) helloworld.tex
	
make clean:
	rm helloworld.pdf helloworld.aux helloworld.log
