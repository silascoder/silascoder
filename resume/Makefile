all: coding-resume.pdf softskill-resume.pdf template.pdf clean

coding-resume.pdf: coding-resume.tex
	lualatex coding-resume.tex
	
softskill-resume.pdf: softskill-resume.tex
	lualatex softskill-resume.tex

template.pdf: template.tex
	lualatex template.tex

clean:
	rm -rf *.aux *.log *.out *.gz
