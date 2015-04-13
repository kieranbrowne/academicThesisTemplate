# Academic Thesis Template

This is a fork of Ben Swift's [academic LaTeX thesis template](https://github.com/benswift/academic-thesis-template)
for arts and humanities theses and exegeses.

### Bibliography

![footnotes](https://cloud.githubusercontent.com/assets/5771172/7110373/24b90836-e1f3-11e4-966e-f6fd01bcff5f.png)
![bibliography](https://cloud.githubusercontent.com/assets/5771172/7110370/210ca864-e1f3-11e4-96c6-ad6dd771392b.png)

- Support for footnote citation through `\footcite{}` 
- Chicago Manual of Style references.
Use the google scholar cite function to export citations in the BibLaTeX 
format and append these to the bibliography file `thesis.bib`

### Compile

To compile the document I recommend you use the `texlive-full` package.
Run using:
```
xelatex thesis
bibtex thesis
xelatex thesis
```

### Licence

This thesis template is in the
[public domain](http://wiki.creativecommons.org/Public_domain).
