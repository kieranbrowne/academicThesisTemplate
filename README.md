## Academic Thesis Template

LaTeX tempalte for arts and humanities theses.
A fork of Ben Swift's [academic thesis template](https://github.com/benswift/academic-thesis-template)

#### Footnotes

![footnotes](https://cloud.githubusercontent.com/assets/5771172/7110443/ba5e8d88-e1f4-11e4-88a4-185acfc4c5e9.png)
Footnote citation with the `\footcite{}` tag.

#### Bibliography

![bibliography](https://cloud.githubusercontent.com/assets/5771172/7110449/d1fb1182-e1f4-11e4-8775-6429f6a3329d.png)

[Chicago Manual of Style](http://www.chicagomanualofstyle.org/home.html) references.
Use the google scholar cite function to export citations in the BibLaTeX 
format and append these to the bibliography file `thesis.bib`

#### Compile

To compile the document I recommend you use the `texlive-full` package.
Run using:
```
xelatex thesis
bibtex thesis
xelatex thesis
```

#### Licence

This thesis template is in the
[public domain](http://wiki.creativecommons.org/Public_domain).
