LL  := latexmk
DEP := $(wildcard *.tex)
MAIN=main

main: ${DEP}
	${LL} -f -pdf ${MAIN} -auxdir=output -outdir=output
