# noteboard
Small LaTeX project for setting up portraits for the Condensed Matter Theory noteboard at the Niels Bohr Institute.

Here is how it works:

1. Add images to pictures folder.
2. Insert the following in (people.tex): 
	``\person{path/to/file}{Name of person}{Office}{Scientific subject}`` 
3. Compile ``people.tex`` to pdf using xelatex. 
 
You can switch to pdflatex compilation (or plain latex). See the [preamble](preamble.tex) for further information. XeLaTeX is used in order to typeset the document with the Minion Pro font.

The formatted pdf contains an picture of the person and the corresponding information nicely typeset. Print out four copies per A4 sheet, cut each copy out and put it up on the noteboard. Check out [the example pdf](people.pdf) for an example of the setup.