# Installation

This project uses poetry for dependency management. To set up the environment:

```bash
uv venv bcgx_venv --python=3.12
source bcgx_venv/bin/activate # Activate it 
uv pip install -e . # Use the pyproject.toml to install dependencies
```

# Data

Data was provided by BCG X and is in the data folder.
Data file is too heavy to commit, please download the file and store it in the [data](/data) folder.

# EDA and modeling

The notebook [notebook](EDA_and_modeling.ipynb) details our approach to churn prediction.