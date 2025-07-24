
slides.ps: slides.tex
	latex slides.tex
	latex slides.tex
	dvipdf slides.dvi
	dvips slides.dvi

view: slides.ps
	gv -landscape slides.ps &

clean:
	rm -f slides.aux slides.dvi slides.log slides.not slides.out

mrproper: clean
	rm -f slides.toc slides.pdf slides.ps

