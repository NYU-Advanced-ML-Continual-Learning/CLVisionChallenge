JOBNAME = report
LATEX = pdflatex #-interaction=nonstopmode
BIBTEX = bibtex
RM = rm -rf


doc:
	$(LATEX) $(JOBNAME)
	$(BIBTEX) $(JOBNAME)
	$(LATEX) $(JOBNAME)
	$(LATEX) $(JOBNAME)
	$(LATEX) $(JOBNAME)

run:
	$(LATEX) $(JOBNAME)

clean:
	$(RM) *.{aux,bbl,blg,log,out}