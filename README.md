# Checklist of introduced taxa in Cyprus

## Rationale

This repository contains the functionality to standardize the data of the Checklist of introduced and invasive species in Cyprus to a [Darwin Core Archive](https://www.gbif.org/darwin-core) that can be harvested by [GBIF](https://www.gbif.org/).

## Workflow

[source data](data/raw)  → Darwin Core [mapping script](src/dwc_mapping.Rmd) → generated [Darwin Core files](data/processed)

## Published dataset

* [Dataset on the IPT](<!-- Add the URL of the dataset on the IPT here -->)
* [Dataset on GBIF](<!-- Add the DOI of the dataset on GBIF here -->)

## Repo structure

The repository structure is based on [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) and the [Checklist recipe](https://github.com/trias-project/checklist-recipe). Files and directories indicated with `GENERATED` should not be edited manually.

```
├── README.md              : Description of this repository
├── LICENSE                : Repository license
├── alien-species-cyprus.Rproj : RStudio project file
├── .gitignore             : Files and directories to be ignored by git
│
├── src
│   ├── dwc_mapping.Rmd    : Darwin Core mapping script
│
└── data
    ├── raw                : Source data, input for mapping script
    └── processed          : Darwin Core output of mapping script GENERATED
```

## Installation

1. Click on `Use this template` to create a new repository on your account
2. Open the RStudio project file
3. Open the `dwc_mapping.Rmd` [R Markdown file](https://rmarkdown.rstudio.com/) in RStudio
4. Install any required packages
5. Click `Run > Run All` to generate the processed data
6. Alternatively, click `Build > Build website` to generate the processed data and build the website in `docs/` (advanced)

## Contributors

[List of contributors](<!-- Add the URL to the GitHub contributors of your repository here, e.g. https://github.com/trias-project/checklist-recipe/contributors -->)

## License

[MIT License](LICENSE) for the code and documentation in this repository. The included data is released under another license.
