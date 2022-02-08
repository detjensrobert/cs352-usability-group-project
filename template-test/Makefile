CITEPROC=$(shell echo | pandoc --citeproc && echo '--citeproc' || echo '--filter=pandoc-citeproc')

all: csl
	pandoc -s example.md -o example.pdf --template=../cs352-template.tex $(CITEPROC)

.ONESHELL:
.SILENT:
# ensure CSL citation style is present
csl:
	[ -f $(XDG_DATA_HOME)/pandoc/csl/ieee.csl ] \
	|| [ -f ~/.local/share/pandoc/csl/ieee.csl ] \
	|| [ -f ./ieee.csl ] \
	|| wget -O ieee.csl https://raw.githubusercontent.com/citation-style-language/styles/master/ieee.csl
