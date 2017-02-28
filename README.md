# USC Dissertation/Thesis LaTeX Template

LaTeX document-style for typesetting Theses or Dissertations in accordance with the University of Southern California Regulations for [Format and Presentation of Theses and Dissertations](http://graduateschool.usc.edu/current-students/thesis-dissertation-submission/guidelines-for-format-and-presentation/).
It provides some alternative "bells and whistles" such as support for multi-volume documents.

## History

A brief history of LaTeX templates for dissertation and thesis at the University of Southern California:

- 1987-1991: Steven Cochran (cochran@iris.usc.edu) wrote the original `USCthesis.sty`, and maintained this package file. You could still find it on [CTAN](https://www.ctan.org/pkg/uscthesis)
- 2000-2001: Zufar Mulyukov (zufarmul@physics.usc.edu) wrote the `USC-Thesis.cls` class file partially based on Cochran's package, as the latter has become outdated for both latex and USC thesis editor requirements.
- 2001-2003: Brian P. Gerkey (gerkey@robotics.usc.edu) continued the maintenance of `USCthesis.sty`.

This repository is based on Gerkey's work and aims at making the updated template easier to find and easier to use.

## Repository Manifest

- [tex](./tex): LaTeX template
  - [USCthesis.sty](tex/USCthesis.sty): LaTeX package
  - [main.tex](tex/main.tex): main LaTeX file for dissertation structure.
  - [references.bib](tex/references.bib): sample bibliography file.
  - Other `.tex` files are sample content files referenced by `main.tex`.
- [layouts](./layouts): Sample layouts generated from template.
  - [final-layout.pdf](layouts/final-layout.pdf): dissertation layout
  - [proposal-layout.pdf](layouts/proposal-layout.pdf): dissertation proposal layout, for qualifying exams.
- [DOCUMENTATION](DOCUMENTATION): Documentation maintained by Cochran.
- [VERSIONS.log](VERSIONS.log): LaTeX log file of package revisions, 1987-2008.

## TODO

Document on other possible uses of the `USCthesis` package.

## License

Neither [Cochran](https://www.ctan.org/pkg/uscthesis) nor Gerkey specified a license or dis­tribution restrictions on the package.
In accordance with [CTAN license guide](https://www.ctan.org/license), I picked [GPLv3](http://www.gnu.org/licenses/gpl-3.0.en.html) for free redistribution and modification of the repository.

Contributions (issues and bull requests) are welcome!
