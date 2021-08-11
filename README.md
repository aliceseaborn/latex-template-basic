# LaTeX Template Basic

This repository has everything you need to build a basic LaTeX-rendered document complete with a bibliography and support for figures. The basic template is designed for brief documents which do not conform to a standard format (e.g. IEEE conference publication) and are not expected to grow beyond the length of a few pages. For larger documents or documents tailored to a specific format, please use alternative templates.

Please start by replacing this README file with a description of your project and specify the filename of your LaTeX document in the Makefile. By default, the Makefile will first run `pdflatex` to render your document and will utilize `bibtex` to process the project bibliography and then it will delete any intermediate auxiliary or log files. Additional targets exist to give developers more granular control of the rendering and cleaning processes.

The functionality of the procedures described above and the documents detailed herein were verified in a bash session on a Mac Mini (M1, 2020) running OSX Big Sur 11.4 using TeX Live 2020 running pdfTeX version 3.14159265-2.6-1.40.21 and BibTeX version 0.99d as of August 11 2021.


*Seaborn.*
