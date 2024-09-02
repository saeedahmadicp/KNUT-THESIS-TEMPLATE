# KNUT-THESIS-TEMPLATE

This is the unofficial template for the thesis of the Korea National University of Transporation (KNUT).

File Structures and Contents
---

Each of the files and directories in the template as describe as below:

- `manuscript.tex`: It contain the main tex code including the imports, variables and combining the abstract and all the pages
- *frontmatter*: The dimensions of the front cover pages is different than the rest of the thesis, that's why there is seperate tex file i.e., `frontmatter.tex`. First you need to update this tex file and generate the pdf file in the same directory for the direct usage in the main thesis file. 
- *titlePages*: This directory contain the rest of the title pages, and as the dimension of these page as same as the main thesis, so there is no need to generate the pdf, these files are directly imported in the main thesis file
- *abstract*: This directory contain the abtract of the thesis both in English and Korean
- *chapters*: This directory contains the individual chapters in the thesis. These chapter are then imported and compliled in the main `manuscript.tex` file
- *figures*: This direcoty contain all the necessary graphics and figures used in the thesis. 
- `references.bib`: This file contains all the citations used in the thesis
--- 

Usage
---
Downlaod the repository as zip file and import it in [Overleaf](https://www.overleaf.com/project/#) for updating the latex text in Overleaf.

- first update the `title.tex` and `title2.text`, to update the contents of the front cover pages, and then compile the `frontmatter.tex` to generate the `frontmatter.pdf` pdf, save it in the same directory, as this file is directly imported in the main text file
- update the titlePages and the rest of the contents in the chapters and abstract
- save all the figures in the figures directory 
- put all your citations in the `references.bib` file
- compile the `manuscript.tex`, your thesis is ready to be print
---

TODO
---
- all the fonts used in this thesis is the default one, for better results and matching with the univeristy template, change the fonts and their sizes accordingly


