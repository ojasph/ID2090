a = ojas

$a.pdf: $a.tex
	pdflatex $a.tex
	rm -f $a.aux $a.log $a.out

PDF: $a.pdf
	xpdf $a.pdf
