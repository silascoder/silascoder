all: coding-resume.pdf softskill-resume.pdf

coding-resume.pdf: coding-resume.tex MagicalCV.cls
	lualatex coding-resume.tex
	
softskill-resume.pdf: softskill-resume.tex MagicalCV.cls
	lualatex softskill-resume.tex

clean: *.aux *.log *.out
	rm *.aux *.log *.out
