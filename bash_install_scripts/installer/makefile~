MAKEFILE=makefile

################################################################
## List targets
usage:
	@echo "usage: make [-OPT='options'] target"
	@echo "implemented targets"
	@perl -ne 'if (/^([a-z]\S+):/){ print "\t$$1\n";  }' ${MAKEFILE}

readme:
	@echo "Generating doc"
	@pandoc --css ${RSAT}/public_html/course.css --from markdown --to html  00_README.md > 00_README.html
	@echo "	00_README.html"
	@echo ""

build_image:
	./build_rsat-commands.sh
