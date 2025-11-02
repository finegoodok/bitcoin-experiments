# AT3 Data Product Experiments

Experimentation repository for building ML models to predict cryptocurrency prices (Bitcoin, Ethereum, XRP, Solana) using APIs and datasets. This repo follows the Cookiecutter Data Science template for structured data science workflows.

## Project Organization
├── LICENSE <- Open-source license if one is chosen
├── Makefile <- Makefile with convenience commands like make data or make train
├── README.md <- The top-level README for developers using this project.
├── data
│ ├── external <- Data from third party sources.
│ ├── interim <- Intermediate data that has been transformed.
│ ├── processed <- The final, canonical data sets for modeling.
│ └── raw <- The original, immutable data dump.
│
├── docs <- A default mkdocs project; see www.mkdocs.org
 for details
│
├── models <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks <- Jupyter notebooks. Naming convention is a number (for ordering),
│ the creator's initials, and a short - delimited description, e.g.
│ 1.0-jqp-initial-data-exploration.
│
├── pyproject.toml <- Project configuration file with package metadata for
│ 36120-group30-experiments and configuration for tools like black
│
├── references <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports <- Generated analysis as HTML, PDF, LaTeX, etc.
│ └── figures <- Generated graphics and figures to be used in reporting
│
├── requirements.txt <- The requirements file for reproducing the analysis environment, e.g.
│ generated with pip freeze > requirements.txt
│
├── setup.cfg <- Configuration file for flake8
│
└── 36120-group30-experiments <- Source code for use in this project.
├── init.py <- Makes 36120-group30-experiments a Python module
├── config.py <- Store useful variables and configuration
├── dataset.py <- Scripts to download or generate data
├── features.py <- Code to create features for modeling
├── modeling
│ ├── init.py
│ ├── predict.py <- Code to run model inference with trained models
│ └── train.py <- Code to train models
└── plots.py <- Code to create visualizations

Project based on the [cookiecutter data science project template](https://drivendata.github.io/cookiecutter-data-science/). #cookiecutterdatascience