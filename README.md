# AT3 Data Product Experiments

Experimentation repository for building ML models to predict cryptocurrency prices (Bitcoin, Ethereum, XRP, Solana) using APIs and datasets. This repo follows the Cookiecutter Data Science template for structured data science workflows.

## Project Organization

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- Makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io

## Setup Instructions
1. Clone the repo: `git clone https://github.com/parthtiwari1/36120-group30-experiments.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Install your extended custom Python package from AT1 (deployed on TestPyPI): `pip install -i https://test.pypi.org/simple/ [your-package-name]`
4. Run Jupyter Lab: `jupyter lab`
5. Store notebooks in `notebooks/` folder using naming: `36120-group30-[Student ID]-AT3-experiment_[number].ipynb` (e.g., `36120-group30-123456-AT3-experiment-1.ipynb`)
6. Save best models in `models/` folder.
7. For environment setup, ensure Python 3.11.4 is used (e.g., via virtualenv: `virtualenv -p python3.11 env; source env/bin/activate` or conda).

## Using the Makefile
- `make data`: Download or process raw data (customize `src/data/make_dataset.py` as needed).
- `make train`: Train models (update `src/models/train_model.py` for your experiments).
- `make clean`: Clean up temporary files.
- Customize the Makefile for group-specific tasks, like API data fetching.

Project based on the [cookiecutter data science project template](https://drivendata.github.io/cookiecutter-data-science/). #cookiecutterdatascience
