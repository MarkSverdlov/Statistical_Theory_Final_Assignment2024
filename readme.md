# Statistical Theory Final Assignment - 2024 2nd Semester - 8488775
## Preface
This is the final assignment for the statistical theory course in Bar
Ilan University. In this assignment we investigate the Steam Game
Dataset avaliable from Kaggle, and deduce various insights from it using
statistical tools learnt on the course.

This readme file records the content of the github repository
contatining all the products of our investigations: Jupyter notebooks,
interim data, and tex and pdf files of the presentation and text
accompanying the assignment. The repository doesn't contain the original
data, which is avaliable from Kaggle.

## Contents of the Repository
1. Exploration.ipynb - This notebook containes our preliminary
   investigations of the original data. In order to run it, one has to
   download the original data from Kaggle, name it
   "games\_may2024\_cleaned.csv", and place it in the same folder as the
   notebook.
1. Initial Results.ipynb - This notebook contains the initial results we
   procured for the presentation.
1. Pre-Processing Data.ipynb - This notebook contains all the code for
   pre-processing the original data from Kaggle. After its execution, it
   creates a new csv file called "Pre-Processed Data.csv" which we
   investigate henceforth.
1. Pre-Processed Data.csv - This file contains the data we analyze in
   all notebooks (except 'Exploration.ipynb'). It is created by
   processing the data from Kaggle using "Pre-Processing Data.ipynb".
1. Results.ipynb - This notebook contains all the results and analyses
   we perpetrated for the main text.
1. requirements.txt - This file contains the dependencies of the
   notebooks.

## How to Use
### Install the Code Dependencies
Run:
> py -m pip install -r requirements.txt

or:
> python -m pip install -r requirements.txt

If one wants to install the dependencies in a virtual environment, run:
> pip install -r requirements.txt

inside the virtual environment.

### *Optional* - Download the Original Data
The original data isn't contained in the repository, and one has to
download it from Kaggle in order to run the notebooks
"Exploration.ipynb" and "Pre-Processing Data.ipynb".

*Instructions:*
1. Download "games\_may2024\_cleaned.csv" from Kaggle (URL: https://www.kaggle.com/datasets/artermiloff/steam-games-
dataset/data).
1. Place it with the same name in the project's folder.

### *Optional* - Reprocess the Original Data
If one has downloaded the original data, it is possible to validate the
processing by running "Pre-Processing Data.ipynb". After running, it
will recreate the file "Pre-Processed Data.csv".

### *Requires the Original Data* - Rerun Exploration.ipynb
If one has downloaded the original data, it is now possible to rerun
"Exploration.ipynb" to procure the results.

### Reproduce the Results
After installing the required dependencies, it is possible to rerun the
notebooks: "Initial Results.ipynb" and "Results.ipynb" to reproduce the
results for the presentation and the main text respectively.

## Outer Resources
1. The original data is on Steam Games Dataset 2024 On Kaggle (URL:
   https://www.kaggle.com/datasets/artermiloff/steam-games-dataset/data).
1. The Python libraries used are: numpy, pandas and scipy (for computations
   and statistics), matplotlib and plotly (for graphing), and
   scikit-learn (for the linear model).
