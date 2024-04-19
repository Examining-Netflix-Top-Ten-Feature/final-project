CSE6242-FINALPROJECT-TEAM166-ROSHAUNBRADY-GABRIELCARPIO-SIVANAGARAJAN-JESSERUIZ
DESCRIPTION
This project analyzes the Netflix Top Ten feature. The codebase includes two notebooks to preprocess the data and then to run machine learning models to build a predictive model that accurately forecasts the programs chance of being in the top ten. 

The zip file package contains:
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
The installation steps are within the Jupyter notebooks. Please read the final report to access the links to the source data, which is publicly available on Kaggle. This will be two csv files called netflix daily top 10.csv and netflix_titles.csv. Place these two files in the DATA repo, under the CODE repo in order to execute the Jupyter notebooks successfully.

EXECUTION
Run Jupyter notebook called datapreprocessing_prod.ipynb to run through the data pre-processing steps, where we prepare the raw data for use in the modeling step. This will generate three CSV files, netflix_and_titles_ds1.csv , netflix_and_titles_melted_countries1.csv , netflix_and_titles_melted_genres1.csv. These files are used in the data visualization in Tableau.
Run the Jupyter notebook called Netflix Top 10 Model.ipynb to run through the machine learning modeling steps.