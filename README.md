

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# titanic
Analisys of the titanic dataset for the UOC Data Science Master

Tipología y ciclo de vida de los datos (Data Sciencie Master - UOC)

## members
- Alexis Germán Arroyo Peña
- Gabriel Pulido de Torres

## contents

- The file PRA2.pdf is the **resolution of the asigment** at [`PRA2.pdf`](PRA2.pdf)

The folder `data` contains the dataset used as input for the Practice:

- The file `data\test.csv` is the dataset used as input for the Practice. It contains the Titanic data from the kaggel challenge [Titanic](https://www.kaggle.com/c/titanic)

The folder `src` contains the source code used to generate the pdf:

- The file PRA2.Rmd is the R Mark Down source code of the pdf. The pdf is being "knitted" using this rmd as a source.
- The file PRA-header.html is the header needed to knit the rmd into html.

The file PRA2.html is the resolution of the asigment on html format.

The folder `final_data` contains the output data from the assignment

- The file `final_data\titanic_final.csv` contains the clean dataset with 12 variables, the nulls treated and that was being used to train the predict models

- The file `final_data\titanic_predict.csv' is the same file with another variable added *Survived_predicted* with the results of the Survived variable for the best predict model from the code.
