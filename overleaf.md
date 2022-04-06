### Overleaf

Many of you prefer overleaf for their thesis. I am fine with that, but please stick to these guidelines to keep you orgamized and me sane

1. Put the URL to your overleaf project LARGE in your github readme.
2. Organize your overleaf project well, as follows:
3. Create directories for 
    4. images
    5. preamble and style files
    6. sections
        7. For each section you create a seperate file which you include in `main.tex` at the top level.
        8. I suggest to use [the subfiles package](https://www.overleaf.com/learn/latex/Multi-file_LaTeX_projects), which is really nice and easy, and saves a lot of hassle.
    9. bib stuff
8. Top level contains `main.tex`  and the folders, and I guess that is it.