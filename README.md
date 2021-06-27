# Research compendium 


This repository contains all files necessary to reproduce the analysis for the paper.


# Authors of this repository

Emerson Del Ponte (delponte@ufv.br)

# Overview of contents

The root of the repository contains files that set the website structure (menus, etc.) and style  (`.yml`, `.css`), as well as the citation/reference style. There are four `.Rmd` files to generate each website page, which are separated according to the convention of a research compendium.

- `index.Rmd`: Describe the research, objectives, authorship, etc.
- `data.Rmd`: Contains the raw or raw-derived data.
- `code.Rmd`: Produces the main analysis report with a template that follows the Wickham and Grolemund's [model for a data science project](http://r4ds.had.co.nz/introduction.html):  import -> tidy -> transform-visualize-model -> communicate 


There are three basic folders:

- `data/` - raw and further processed data.
- `docs/` - html files of the research compendia with all text and figures.
- `supp/` - supplementary files that are not data or R codes.
- `figs/` - Figure 


# Licenses

Manuscript: [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)

Code: [MIT](https://opensource.org/licenses/MIT) year: 2017, copyright holder: Emerson Del Ponte

Data: [CC-0[(https://creativecommons.org/publicdomain/zero/1.0/)] attribution requested in reuse

# Credits

This compendium was developed based on the ideas and examples in other resources which suggest a research compendium structured as an R package. However, this is not an R package as I focused mainly on four main Rmd files that are used to generatethe html output of the compendium, but there there is clear separation of the data and the output files.

[Marwick et al. 2017](https://doi.org/10.7287/peerj.preprints.3192v1)

[jhollist manuscriptpackage](https://github.com/jhollist/manuscriptPackage)

[cboettig template](https://github.com/cboettig/template)

[benmarwick researchcompendium](https://github.com/benmarwick/researchcompendium)

[Reproducibility_in_Plant_Pathology](Reproducibility_in_Plant_Pathology)

[R for Data Science](http://r4ds.had.co.nz/)

# Contact

Emerson Del Ponte, Associate Professor, Departmento de Fitopatologia, Universidade Federal de Viçosa, Viçosa, MG Brazil
(+55) 31 38991103 
delponte@ufv.br
Twitter: @emdelponte

