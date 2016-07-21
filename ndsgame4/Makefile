
.PHONY : all
.PHONY : clean

all: game_diary.tex
	pdf

dot: class-diagram-opt.dot class-diagram-dbg.dot class-diagram-ver.dot
	dot -Tps class-diagram-opt.dot -o class-diagram-opt.ps
	dot -Tps class-diagram-dbg.dot -o class-diagram-dbg.ps
	dot -Tps class-diagram-ver.dot -o class-diagram-ver.ps

clean:
	-@rm -f thesis.dvi thesis.ps thesis.pdf *~ *.log *.aux 
