
<!-- README.md is generated from README.Rmd. Please edit that file -->

# MiSeq-SOP-demo

<!-- badges: start -->

[![build](https://github.com/SchlossLab/MiSeq-SOP-demo/actions/workflows/build.yml/badge.svg)](https://github.com/SchlossLab/MiSeq-SOP-demo/actions/workflows/build.yml)
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/SchlossLab/MiSeq-SOP-demo/blob/main/LICENSE.md)
<!-- badges: end -->

## Dependencies

- mothur
- R
- snakemake

R packages:

- here
- schtools
- tidyverse

## Re-using this template

If you re-use this template for a real project, you’ll need to fill in
some information in the following files:

- [LICENSE.md](LICENSE.md)
  - `YEAR`
  - `AUTHORS`
  - `FIRST_AUTHOR_LASTNAME`
  - `GITHUB_URL`
- MiSeq-SOP-demo.Rproj - rename this file to match your project.
- [paper/head.tex](paper/head.tex)
  - `RUNNING TITLE`
  - `FIRST AUTHOR LASTNAME`
  - `AUTHORS AND AFFILIATIONS`
- [paper/paper.Rmd](paper/paper.Rmd)
  - `TITLE`
  - Write the actual text of your paper. 🤓
- [paper/references.bib](paper/references.bib) - export your references
  from Zotero (or other reference manager) to this bibtex file.
- README.md - don’t edit this by hand, it’s created by knitting
  [README.Rmd](README.Rmd).
- [README.Rmd](README.Rmd).
  - `MiSeq-SOP-demo` - your project slug.
  - Change the text as you see fit to explain your project.

## Workflow

![rulegraph](figures/rulegraph.png)

## Directory Structure

    .
    ├── LICENSE.md
    ├── MiSeq-SOP-demo.Rproj
    ├── README.Rmd
    ├── config
    │   ├── README.md
    │   ├── demo.yaml
    │   └── slurm
    ├── data
    │   ├── README.md
    │   ├── miseqsopdata.zip
    │   ├── mothur
    │   ├── raw
    │   └── references
    ├── figures
    │   ├── dag.png
    │   └── rulegraph.png
    ├── log
    │   ├── hpc
    │   ├── mothur
    │   └── render_readme.log
    ├── paper
    │   ├── head.tex
    │   ├── mbio.csl
    │   ├── paper.Rmd
    │   ├── preamble.tex
    │   └── references.bib
    ├── results
    │   ├── current_files.summary
    │   ├── stability.opti_mcc.0.03.cons.tax.summary
    │   ├── stability.opti_mcc.0.03.subsample.shared
    │   ├── stability.opti_mcc.count.summary
    │   ├── stability.opti_mcc.groups.ave-std.summary
    │   ├── stability.opti_mcc.groups.rarefaction
    │   ├── stability.opti_mcc.list
    │   ├── stability.opti_mcc.sensspec
    │   ├── stability.opti_mcc.shared
    │   ├── stability.opti_mcc.steps
    │   └── stability.taxonomy
    └── workflow
        ├── Snakefile
        ├── envs
        ├── notebooks
        └── scripts

    16 directories, 27 files
