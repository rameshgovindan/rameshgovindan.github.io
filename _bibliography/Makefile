all:
	bibtool --sort.format='{%d(year)}' -S papers.bib | bibtool -K -o papers_sorted_keyed.bib
	cp papers_sorted_keyed.bib papers.bib
