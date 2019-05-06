NBCONVERT=jupyter-nbconvert
PD=pandoc 
PD_FLAGS=-V geometry:a4paper -V urlcolor:blue --highlight-style pandoc/bp.theme
RM=/bin/rm -f

SRC=\
    00_Installing_Python.ipynb \
    01_Administrative_Information.ipynb \
    01_Introduction_to_Computers_and_Programming.ipynb \
    02_Input_Processing_and_Output.ipynb \
    03_Decision_Structures_and_Boolean_Logic.ipynb \
    04_Repetition_Structures.ipynb \
    05_Functions.ipynb \
    06_Files_and_Exceptions.ipynb \
    07_Lists_and_Tuples.ipynb \
	07a_Lists_Addendum.ipynb \
	07b_Tuples_Addendum.ipynb \
	08_More_About_Strings.ipynb \
	08a_Format_Strings.ipynb \
	09_Dictionaries_and_Sets.ipynb \
	09a_Dictionaries_Addendum.ipynb \
	10_Classes_and_Object-Oriented_Programming.ipynb \
	11_Inheritance.ipynb \
	11a_OO_Addendum.ipynb \
	12_Recursion.ipynb \
	X1_Regular_Expressions.ipynb

MD:=$(SRC:%.ipynb=%.md)
PDF:=$(SRC:%.ipynb=%.pdf)

%.md: %.ipynb
	$(NBCONVERT) --to markdown $<

%.pdf: %.md
	$(PD) $(PD_FLAGS) -o $@ $<

all: $(PDF)

markdown: $(MD)

pdf: $(PDF)

clean:
	-$(RM) $(MD) $(PDF)
