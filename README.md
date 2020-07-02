# My LaTeX CV

This is my CV template designed in LaTeX. I implemented it since it is easy to edit and add new information.

### Compiling the CV

There are two possible ways to edit and compile the CV. I suggest using the Overleaf.

#### Use Overleaf online editor

You can also use [Overleaf](https://www.overleaf.com/) online editor. You just open a new project and copy files from this repository there. Everything should work there just set the project's compiler to XeLaTeX.

#### Compile localy
You will need XeLaTex (pdfLaTeX will not work because of the different fonts used). If you do not have `xelatex` command already working you need to install it following [instructions](http://www.texts.io/support/).

You latex file can be compiled the following way:
```
xelatex example.tex
```
If you get an issue that says FontAwesome is missing. You can solve it with installing FontAwesome font in you system fonts - you can get it [here](https://github.com/h5p/font-awesome ) 
