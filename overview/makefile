pdf:
	pandoc talk.md --slide-level 2 -t beamer -o talk.tex
	pdflatex main.tex
	zathura main.pdf

tex:
	pandoc --slide-level 2 -t beamer talk.md -o talk.tex

pdfdirect:
	pandoc --slide-level 2 -t beamer talk.md -o talk.pdf
	zathura talk.pdf

reveal:
	pandoc --slide-level 1 --section-divs -i --table-of-contents -t html5 -s --template template.revealjs.html -o reveal.js/talk.html talk.md
