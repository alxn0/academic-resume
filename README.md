# An Academic Resume

This is my own academic resume, which used a (slightly) modified version
of [Anna Brandenberger's template](https://github.com/abrandenberger/academic-resume) 
which is also adapted from [Trey Hunner's template](https://github.com/treyhunner/resume).

I simply modified the indentation for `position` environment (i.e.,
`leftmargin=1em`) and created a new command, `publi`, to display
publications/chapters/conferences/etc.

I didn't liked the use of natbib (or biblatex), as it is hard to
customized displayed publications with `\nocite{*}`


Assuming a full LaTeX installation, just run `pdflatex resume.tex` on
the command line.
