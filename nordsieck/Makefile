LL  := latexmk
DEP := $(wildcard *.tex)
MAIN=nordsieck
OUT=output

main: ${DEP}
	@${LL} -f -pdf ${MAIN} -auxdir=${OUT} -outdir=${OUT}

clean:
	@echo rm -rf ${OUT}
	@rm -rf ${OUT}

show:
	@zathura ${OUT}/${MAIN}.pdf
