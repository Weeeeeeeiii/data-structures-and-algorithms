test: test.cpp HeapSort.h
	g++ test.cpp -o test -std=c++20 -O2

report: report.pdf

report.pdf: report.tex
	xelatex report.tex
	rm report.aux report.log

clean:
	rm test report.pdf

.PHONY: report clean