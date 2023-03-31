# LaTeX Report - Template
The latex document provides the fully functional template for typesetting B. Tech. Engineering Physics Project dissertation in the pdf format.  

# Pre-requisite
To compile the latex source, install miktex from https://miktex.org/download

In-built latex compiler is available with miktex. Please see the documentation of miktex for details.

# Usage 

1. Unzip the **report.zip** file and edit the initial details in the **init.tex** file in the parent folder.

2. Open the **frontpage.tex** file and compile to generate the _Frontpage_ of the project dissertation. 

`pdflatex frontpage.tex`

3. Open the **certificate.tex** file and compile to generate the _Certificate_ of the project. 

`pdflatex certificate.tex`

4. Open the **report.tex** file to and compile to generate the whole thesis is preloaded information. 

`pdflatex report.tex`

5. If everything goes well, then go to **chapter** folder and edit the respective chapter files given the folder. Once the editing of chapter are finished, Go back to parent folder and compile the **report.tex** to generate the **final report**.

6. For help in LaTeX typesetting, please visit: 

    a. https://latex-tutorial.com/tutorials/      
    b. https://www.learnlatex.org/en/

7. For any further queries, please feel free to e-mail at sarun@iitism.ac.in
