# Description of Project in Bioinformatics Files

## **data** folder:
- `halldorsson_2019.tsv` and `jonsson_2017.tsv`: the two initial datasets,
- `halldorsson_explore.rds`: data used for creating exploratory figures,
- `halldorsson_child_counts.rds` and `halldorsson_child_fract.rds`: data used for fitting the linear regression models,
- `halldorsson_counts_split.rds` and `halldorsson_fract_split.rds`: data used for fitting the logistic regression models.

## **src** folder:
- `00_read_data.Rmd`: reading in the `halldorsson_2019.tsv` dataset and creating the various `.rds` files that we rely on later in the analysis,
- Files starting with `01_`: exploratory data analysis,
- Files starting with `02_`: fitting full models,
- Files starting with `03_`: fitting models with cross-validation.