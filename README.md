# Griffin R&D Papers

## Aim : 

The aim is to automate documentation for reasearch purposes using pdfLatex. The user can :
1. Download research articles (.pdf) into the relevant subfolders catergorized for each research topic, OR,
2. Create a subfolder and add research articles into it. In this case, it is needed to update/edit the files once per subfolder creation.

### Adding papers into subfolders and generate pdf

The subfolders are under [Documents](./Documents/) folder, after adding the article into any of the folders, the user has to run [main.tex](./main.tex) latex file to generate the [main.pdf](./main.pdf). The generated PDF file contains links to all the articles arranged in a section wise hierarchy.

### Adding subfolders
In case the user wants to create subfolders for a new research topic, he can do so, but must edit [files.bat](./files.bat) and [main.tex](./main.tex) to generate clickable links to the all articles.
  