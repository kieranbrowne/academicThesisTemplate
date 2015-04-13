# Academic Thesis Template

This is a fork of Ben Swift's [academic LaTeX thesis template](https://github.com/benswift/academic-thesis-template)
for arts and humanities theses and exegeses.

### References

![footnotes](https://cloud.githubusercontent.com/assets/5771172/7110443/ba5e8d88-e1f4-11e4-88a4-185acfc4c5e9.png)
![bibliography](https://cloud.githubusercontent.com/assets/5771172/7110449/d1fb1182-e1f4-11e4-8775-6429f6a3329d.png)

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
