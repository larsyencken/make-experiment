#
#  Makefile
#

default: help

help:
	@echo "=== {{cookiecutter.repo_name}} ==="
	@echo
	@echo "Usage:"
	@echo
	@echo "make run   	run the experiment"
	@echo "make clean	clean up temporary files"
	@echo

run: output/example.out

output/example.out: input/example.in
	cp -f $< $@

clean:
	rm -rf _temp/*

clobber: clean
	rm -rf output/*
