pdf:
	pandoc talk.md --slide-level 2 -t beamer -o talk.tex
	pdflatex main.tex
	zathura main.pdf

tex:
	pandoc --slide-level 2 -t beamer talk.md -o talk.tex

pdfdirect:
	pandoc --slide-level 2 -t beamer talk.md -o talk.pdf
	zathura talk.pdf
	# pandoc --toc --slide-level 2 -V theme:Frankfurt -t beamer talk.md -o talk.pdf
