TARGET:=projectplan.pdf

OBJS:=projectplan.tex planning.tex

projectplan.pdf: ${OBJS}

%.dvi: ${OBJS}
	latex ${OBJS}

%.ps: %.dvi
	dvips $<

%.pdf: %.ps
	ps2pdf $<

