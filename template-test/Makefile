CITEPROC=$(shell echo | pandoc --citeproc 2>/dev/null && echo '--citeproc' || echo '--filter=pandoc-citeproc')
CSL=$(shell grep csl: example.md | cut -d' ' -f2)

all: csl
	pandoc -s example.md -o example.pdf --template=../cs352-template.tex $(CITEPROC)

# ensure CSL citation style is present
csl:
	@[ -f $(XDG_DATA_HOME)/pandoc/csl/$(CSL) ] \
	|| [ -f ~/.local/share/pandoc/csl/$(CSL) ] \
	|| [ -f ./$(CSL) ] \
	|| wget -O $(CSL) https://raw.githubusercontent.com/citation-style-language/styles/master/$(CSL)
