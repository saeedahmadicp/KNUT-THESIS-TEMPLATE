# KNUT-THESIS-TEMPLATE

This is the unofficial template for the Korea National University of Transportation (KNUT) thesis.

File Structures and Contents
---

Each of the files and directories in the template as described as below:

- `manuscript.tex`: It contains the main tex code including the imports, variables, and combining the abstract and all the pages
- *frontmatter*: The dimensions of the front cover pages are different from those of the rest of the thesis, so there is a separate Tex file, `frontmatter.tex`. First, you need to update this text file and generate the PDF file in the same directory for direct usage in the main thesis file. 
- *titlePages*: This directory contains the rest of the title pages, and as the dimensions of these pages as the same as the main thesis, there is no need to generate the pdf, these files are directly imported in the main thesis file
- *abstract*: This directory contains the abstract of the thesis both in English and Korean
- *chapters*: This directory contains the individual chapters in the thesis. These chapters are then imported and compiled in the main `manuscript.tex` file
- *figures*: This directory contains all the necessary graphics and figures used in the thesis. 
- `references.bib`: This file contains all the citations used in the thesis
--- 

Usage
---
Download the repository as a zip file and import it in [Overleaf](https://www.overleaf.com/project/#) for updating the latex text in Overleaf.

- first update the `title.tex` and `title2.text`, to update the contents of the front cover pages, and then compile the `frontmatter.tex` to generate the `frontmatter.pdf` pdf, save it in the same directory, as this file is directly imported in the main text file
- update the titlePages and the rest of the contents in the chapters and abstract
- save all the figures in the figures directory 
- put all your citations in the `references.bib` file
- compile the `manuscript.tex`, your thesis is ready to be print
---

TODO
---
- all the fonts used in this thesis are the default ones, for better results and to match with the university template, change the fonts and their sizes accordingly


