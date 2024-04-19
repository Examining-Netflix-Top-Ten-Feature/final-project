CSE6242-FINALPROJECT-TEAM166-ROSHAUNBRADY-GABRIELCARPIO-SIVANAGARAJAN-JESSERUIZ
DESCRIPTION
The package contains:
| README.txt
| DOC
|-- team166report.pdf
|-- team166poster.pdf
| CODE
|-- datapreprocessing_prod.ipynb
|-- Netflix Top 10 Model.ipynb
|-- DATA
|--|-- netflix daily top 10.csv
|--|-- netflix_titles.csv
|--|-- netflix_and_titles_ds1.csv **
|--|-- netflix_and_titles_melted_countries1.csv **
|--|-- netflix_and_titles_melted_genres1.csv **
|--|-- df_encoded.csv **

(** designates a file generated from the executed code)


INSTALLATION
The installation steps are within the Jupyter notebooks.

EXECUTION
Run Jupyter notebook called datapreprocessing_prod.ipynb to run through the data pre-processing steps, where we prepare the raw data for use in the modeling step. This will generate three CSV files, netflix_and_titles_ds1.csv , netflix_and_titles_melted_countries1.csv , netflix_and_titles_melted_genres1.csv
Run the Jupyter notebook called Netflix Top 10 Model.ipynb to run through the modeling steps using the cleaned data.