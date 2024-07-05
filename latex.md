---
title: "Latex"
layout: page
---

#### Thesis layout

For a scaled-down version of the LaTeX main file for my Ph.D. thesis see the [phdthesis repository](https://github.com/christianepeters/phdthesis) on GitHub which contains two files that might be useful:

- diss-cpp-header.tex includes comments on which package does what.
- chapterhead.tex defines the chapter heading I used.

I won't paste my full makefile, but you can compile the above using something along the following lines

```
latex $(TARGET).tex
bibtex $(TARGET) || echo Suppressed BIBTEX error
makeindex $(TARGET).idx
makeindex $(TARGET).nlo -s nomencl.ist -o $(TARGET).nls
latex $(TARGET).tex
```

Possibly it's necessary to re-run some of these commands until all links are set.


