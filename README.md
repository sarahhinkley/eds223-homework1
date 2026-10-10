# Environmental Justice in Kern County: Mapping PM2.5 and Communities of Color

## Purpose
In the United States, underrepresented communities of color have often faced greater exposure to pollution. Historically, these patterns have gone unrecognized in city planning and policy-making decisions. 

This repository explores that issue in Kern County, California, which houses the San Joaquin Valley, a huge trap for emissions from agriculture, oil and gas production, and freight traffic. The county is also home to large Hispanic and farmworker communities. Using maps at the census block group level, it compares annual average PM2.5 concentrations with the share of residents who are people of color to examine where higher pollution levels and communities of color overlap.

## Repository Overview
- `ej_screen.qmd`: Quarto document containing all code, maps, and written interpretation.
- `ej_screen.pdf`: Rendered version of the Quarto document.
- `data/`: EJScreen data used in the analysis. This folder is listed in .gitignore.
  
```{r}
EDS223-HW1
│   README.md
│   ej_screen.pdf
│   ej_screen.qmd
├── .quarto
     └───typst
└───data
     └───ejscreen 
```

## Data Access
The data comes from the U.S. Environmental Protection Agency's EJScreen: Environmental Justice Screening and Mapping Tool. EJScreen has since been taken down from the EPA website, but the data is still accessible by the public using this [unofficial archived version](https://pedp-ejscreen.azurewebsites.net/).

The dataset used for this analysis was provided by Annie Adams as a [downloadable folder](https://eds-223-geospatial.github.io/assignments/HW1.html) through Environmental Data Science 223 (EDS 223) at the University of California, Santa Barbara (UCSB).

## Author
Sarah A. Hinkley: [GitHub Profile](https://github.com/sarahhinkley)

## References
- U.S. Environmental Protection Agency. (2023). EJScreen: Environmental Justice Screening and Mapping Tool (Version 2.2). Archived version: https://pedp-ejscreen.azurewebsites.net/
- [EJScreen dataset provided for EDS 223](https://drive.google.com/file/d/1nG6Nj1bXfzQFOVMO8Km3eNy4SWu1YcIQ/view?usp=sharing)
