## SDA Team 9

### Students
- Fennom Schalkwijk - 14619148
- Kelt Paehlig - 14634716
-

### Dataset
The [dataset](https://www.kaggle.com/datasets/alphiree/cardiovascular-diseases-risk-prediction-dataset) is created
based on the data from the 2021 [BRFSS](https://www.cdc.gov/brfss/index.html) survey. This survey is conducted in the
United States by the U.S. Department of Health & Human Services and contains data about many aspects of life, collected from all the states
from over 400.000 people. Do note that there may be a bias because of the fact
that all the data originates from the United States. The dataset we have used is a pre-processed
version of the survey which contains 19 unique variables and over 308.855 rows. The
variables are hand-picked according to the author of the pre-processed dataset and contain
information about the health and lifestyle of the participants of the survey, such as their age, weight, and if they have several
medical conditions, such as diabetes or arthritis.

### Dependencies and running project

- Python3.10

#### Packages
Use the packages found in requirements.txt by creating a virtual environment:

```
$ python3 -m venv venv
$ source venv/bin/activate
```

Then install the packages:

```
$ pip install -r requirements.txt
```

Updating the requirements.txt file can be done using:
```
$ pip freeze > requirements.txt
```

### Running project
Running the code for the project is as simple as running the
notebooks found in the notebooks folder.

`initial_visualizations.ipynb` creates and stores basic visualisations of the dataset.
`Exploration + initial implementation.ipynb` contains the data processing and analysis.

The graphs that are created in the notebooks are also saved in the
Graphs subfolder.

## TODO: more info about project
