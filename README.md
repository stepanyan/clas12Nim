# clas12Nim

This repo contains a collection of clas12 detector nim papers

Pre-requisites to compile:
--------------------------

- scons or MacTex
- latex (for mac: http://www.tug.org/mactex/)


How to get the tex files and created a pdf
-----------------------------------------------

First, clone the repository: 

```git clone https://github.com/JeffersonLab/clas12Nim.git```

Then navigate to your detector and use scons:

- to create the PDF: ```scons```
- to clean:  ```scons -c```

Alternatively (on an Apple computer with latex installed) you can use MacTex to open the main file, which has the same name as the system (for example: svt.tex for svt).

What to edit
------------

Edit these files:

- `titleAndAuthors.tex`: include the titles, list of authors and their addresses
- `abstract.tex`: paper abstract 
- `overview.tex`: introduction and overview
- `requirements.tex`: system requirements
- `design.tex`: system design
- `hardware.tex`: hardware components and construction
- `electronics.tex`: electronics
- `readout.tex`: signal and readout
- `calibration.tex`: calibration software suite and results
- `reconstruction.tex`: reconstruction algorithms and results
- `simulation.tex`: simulation geometry, digitization, results
- `performance.tex`: detector performance
- `conclusionsAndAcknowledgement.tex`: paper conclusion and aknowledgements
- `bibfile.bib`: article in the bibliography


How to commit to the repository
-------------------------------------

First, make sure you changed only the files relevant to your detector. You can find out which files you changed with the command

`git status`

To commit, use a nice comment:

`git commit -a -m"nice comment"`

Finally, push to the github repo:

`git push`


Bibliography
------------

Collect the references in the file bibfile.bib. You can use SPIRES to look for the article and use the bibtex link to add the "official" format to bibfile.bib.

Note: only the articles that are mentioned in the text with `\cite` will appear in the references.

